<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>git-journey</title>
<style>
  body {
    background-color: #000;
    color: #00ff00;
    font-family: 'Courier New', Courier, monospace;
    font-size: 2em;
    text-align: center;
    margin-top: 20vh;
  }
  .warp {
    
    display: inline-block;
    font-weight: 900;
  }
</style>
</head>
<body>

  <div class="warp"></div> <!-- This is where the typing text will appear -->

  <!-- Add the Typed.js library -->
  <script src="https://cdn.jsdelivr.net/npm/typed.js@2.0.12"></script>
  
  <!-- Animation code -->
  <script>
    var typed = new Typed('.warp', {
      strings: ["Hello world <br> tishad is here!<br/>"],
      typeSpeed: 100,    // speed of typing
      backSpeed: 50,     // speed of deleting (if you want it)
      loop: true         // repeats forever
    });
  </script>

</body>
</html>
