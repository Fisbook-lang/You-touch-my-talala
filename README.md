<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Custom Prank Button</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="container">
    <button id="prankButton" class="custom-button">Surprise Button!</button>
  </div>

  <!-- Hidden Modal for Video -->
  <div id="videoModal" class="modal">
    <div class="modal-content">
      <span class="close">&times;</span>
      <iframe id="prankVideo" width="560" height="315" src="https://www.youtube.com/embed/dQw4w9WgXcQ" 
        frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </div>
  </div>

  <script src="script.js"></script>
</body>
</html>
