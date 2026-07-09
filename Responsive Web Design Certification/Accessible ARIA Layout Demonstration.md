```
# index.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Accessible ARIA Layout Demonstration</title>
  <style>
    /* Basic styling for visualization - hidden attributes handle screen readers */
    [hidden] { display: none !important; }
    .feed-container { max-width: 600px; margin: 20px auto; font-family: sans-serif; }
    .feed-card { border: 1px solid #ccc; padding: 15px; margin-bottom: 20px; border-radius: 8px; }
    .toolbar-row { background: #f0f0f0; padding: 8px; display: inline-flex; gap: 5px; border-radius: 4px; }
    .note-box { background: #fff3cd; border-left: 4px solid #ffc107; padding: 10px; margin: 15px 0; }
    .tooltip-popup { background: #333; color: #fff; padding: 5px 10px; border-radius: 4px; font-size: 12px; position: absolute; }
    .math-block { font-family: "Courier New", Courier, monospace; background: #e9ecef; padding: 10px; display: inline-block; }
    .layout-table { width: 100%; border-collapse: collapse; }
  </style>
</head>
<body>

  <!-- FEED element acts as the main scrollable container -->
  <main class="feed-container" role="feed" aria-label="Educational Activity Feed">
    
    <!-- First article item inside the feed -->
    <article class="feed-card" role="article" aria-posinset="1" aria-setsize="-1">
      <h2>Activity 1: Algebra Homework</h2>

      <!-- PRESENTATION / NONE roles on layout-only elements to strip semantic meaning -->
      <table class="layout-table" role="presentation">
        <tbody role="none">
          <tr>
            <td>
              <!-- TOOLBAR element grouping interactive layout tools -->
              <div class="toolbar-row" role="toolbar" aria-label="Homework editor controls" aria-orientation="horizontal">
                
                <!-- Button utilizing a TOOLTIP via aria-describedby -->
                <button type="button" id="btn-save" aria-label="Save progress" aria-describedby="tip-save">
                  💾 Save
                </button>
                
                <button type="button" aria-label="Print worksheet">
                  🖨️ Print
                </button>
              </div>

              <!-- TOOLTIP element strictly tied to the save button -->
              <div id="tip-save" class="tooltip-popup" role="tooltip" hidden>
                Saves your draft locally
              </div>
            </td>
          </tr>
        </tbody>
      </table>

      <!-- NOTE element provides ancillary text context -->
      <div class="note-box" role="note" aria-label="System Notice">
        <p><strong>Heads up:</strong> Math answers must be fully simplified before final submission.</p>
      </div>

      <p>Please review and solve the following target equation:</p>

      <!-- MATH element containing mathematical formulas -->
      <div class="math-block" role="math" aria-label="f of x equals x squared plus two x minus five">
        <math xmlns="http://w3.org">
          <mi>f</mi><mo>(</mo><mi>x</mi><mo>)</mo>
          <mo>=</mo>
          <msup><mi>x</mi><mn>2</mn></msup>
          <mo>+</mo>
          <mn>2</mn><mi>x</mi>
          <mo>−</mo>
          <mn>5</mn>
        </math>
      </div>

    </article>
  </main>

  <script>
    // Simple interactive demonstration JavaScript for the tooltip visibility
    const saveBtn = document.getElementById('btn-save');
    const tooltip = document.getElementById('tip-save');

    // Show tooltip on focus or hover
    const showTooltip = () => tooltip.removeAttribute('hidden');
    const hideTooltip = () => tooltip.setAttribute('hidden', '');

    saveBtn.addEventListener('mouseenter', showTooltip);
    saveBtn.addEventListener('focus', showTooltip);
    saveBtn.addEventListener('mouseleave', hideTooltip);
    saveBtn.addEventListener('blur', hideTooltip);
  </script>


</body>
</html>
```
<img width="608" height="401" alt="image" src="https://github.com/user-attachments/assets/f84e3ecb-bc5d-4522-b940-1fa97a73d682" />

