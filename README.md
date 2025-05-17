# mufasa_life-_of_Coding
PHP LIFE with LARAVEL
<html>

<body>
    $_REQUEST:
    <?php #Print REQUEST data here ?>
    <br>
    $_GET:
    <?php #Print GET data here ?>
    <br>
    $_POST:
    <?php #Print POST data here ?>
    <form method="get">
        GET Form: <input type="text" name="get_name">
        <input type="submit" value="Submit GET">
    </form>
    <form method="post">
        POST Form: <input type="text" name="post_name">
        <input type="submit" value="Submit POST">
    </form>
    <a href="index.php">Reset</a>
</body>

</html>

//the new form try to recheck the flow code//
<!DOCTYPE html>
<html lang="en" dir="ltr">
  <body>
    <h1>Welcome To This Form</h1>
    <form action="" method="POST">
          <label for="text">You can enter text here:</label>
    			<input type="text" name="text">
        <hr>
          <label for="num">You can enter a number here:</label>
          <input type="number" name="num">
        <hr>
          <label for="slider">You can slide this:</label>
          <br>
          <span>Left</span>
          <input type="range" name="slider" value="3" min="1" max="5">
          <span>Right</span>
        <hr>
       <label for="boxes">You can check these:</label>
          <input type="checkbox" name="boxes" value="first">
          <label for="first">First</label>
          <input type="checkbox" name="boxes"  value="second">
          <label for="second">Second</label>
          <input type="checkbox" name="boxes" value="third">
          <label for="third">Third</label>
        <hr>
      <label for="radio">You can select one of these:</label>
          <input type="radio" name="radio" value="true">
          <label for="true">TRUE</label>
          <input type="radio" name="radio" value="false">
          <label for="false">FALSE</label>
        <hr>
          <label for="dropdown">You can select one of these</label>
          <select name="dropdown">
            <option value="first">First</option>
            <option value="second">Second</option>
            <option value="third">Third</option>
          </select>
        <hr>
          <input type="submit" value="Submit to Reset">
      </form>
  </body>
</html>




//The validation of the some line of code to check for error and posibillity//
<!DOCTYPE html>
<html lang="en" dir="ltr">
  <body>
    <h1>Basic HTML Validation</h1>
    <form action="" method="POST">
      <label for="text">Enter your name here:</label>
    	<input id="name" name="name" type="text" required minlength="3" maxlength="100">
      <br><br>
      <label for="number">Enter your age here:</label>
      <input type="number" name="age" id="age" required min="1" max="123">
      <br><br>
        <label for="code">Best place to learn to code: (hint: starts with a "C")</label>
  <input id="code" name="code" type="text" required pattern="[cC]odecademy">
      <br><br>
      <input type="submit" value="Submit">
    </form>
  </body>
</html>
