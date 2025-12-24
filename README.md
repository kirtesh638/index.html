<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Tabs Project</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <div class="tabs-container">

    <div class="tabs">
      <button class="tab-btn active" data-tab="tab1">First Tab</button>
      <button class="tab-btn" data-tab="tab2">Second Tab</button>
      <button class="tab-btn" data-tab="tab3">Third Tab</button>
      <button class="tab-btn" data-tab="tab4">Fourth Tab</button>
    </div>

    <div class="tab-content active" id="tab1">
      <p>First Tab content to be displayed here.</p>
    </div>

    <div class="tab-content" id="tab2">
      <p>Second Tab content to be displayed here.</p>
    </div>

    <div class="tab-content" id="tab3">
      <p>Third Tab content to be displayed here.</p>
    </div>

    <div class="tab-content" id="tab4">
      <p>Fourth Tab content to be displayed here.</p>
    </div>

  </div>

  <script src="script.js"></script>
</body>
</html>
