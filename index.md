
<!DOCTYPE html>
<html>
<script src="stats.js"> hello</script>


<!--
Page setup
-->

<head>The Ascent</head>
<p>

  <button onclick="startGame()"> click me </button>
</p>

<p>
  <div id = "str"> str</div>
</p>

<p onload = begin()></p>

<script>
  function begin() {
    var act = 10;
    myGamePiece = new component(30, 30, "red", 10, 120);
    myGamePiece.gravity = 0.05;
    myScore = new component("30px", "Consolas", "black", 280, 40, "text");
    setTimeout(function () {
                document.getElementById('message').innerHTML =
                    'The page has finished loading! After 5 second';
            }, 5000); 
</script>



<script>
  window.onload = startgame() {
    var Inv = ["error","sword"];
    myGamePiece = new component(30, 30, "red", 10, 120);
    myGamePiece.gravity = 0.05;
    myScore = new component("30px", "Consolas", "black", 280, 40, "text");
    setTimeout(function () {
                document.getElementById('message').innerHTML =
                    'The page has finished loading! After 5 second';
            }, 5000); 
  };
  
</script>


</html>

