# section2
Ayunni Jasmine (1816714)

HTML Codes:
<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <title>Assignment 1</title>
    <link rel="stylesheet" href="style.css">
  </head>

  <!--Ayunni Jasmine (1816714) Section 2-->

  <body>

    <img src="iium logo.jpg" class="iium">

    <div class="river">

    </div>

    <h2>Web-Based Mahallah <br>Pre-Registration</h2>

    <nav>
      <ul class="links">
        <li> <a href="#Login">Login</a></li><br>
      </ul>
    </nav>

    <form class="form" action="index.html" method="post">
      <input class="matric" type="text" name="matric no" max="10" placeholder="Enter matric no." required>
      <br>
      <input class="password" type="text" name="password" placeholder="Enter password" required>
      <br>
      <input class="remember" type="checkbox">&nbsp Remember me <br>
      <button class="login" type="submit">Login</button>

    </form>

    <br><br><br>
    <p class="footnote"><a href="#">Privacy Policy</a> &nbsp <a href="#">Disclaimer</a> &nbsp Copyright 2016</p>

    <br><br><br><br><br><br><br><br><br><br><br><br>
    <a class="download" href="http://photos.iium.edu.my/flagship/river_of_life.jpg">Download image here</a>

  </body>
</html>


CSS Codes:

* {
  font-family: Helvetica;
}

h2 {
  margin-left: 710px;
  margin-top: 50px;
  position: absolute;
}

body {
  color: black;
  font-size: 18px;
}

ul {
  list-style-type: none;
  margin-top: 150px;
  font-size: 20px;
}


li {
  float: right;
  margin-right: 640px;
}

li a {
  display: block;
  text-decoration: none;
  color: black;
  border-bottom: 3px solid blue;
  padding-bottom: 6px;
  position: fixed;

}

form {
  position: fixed;
  margin-left: 710px;
  font-size: 16px;
}

.matric {
  padding: 10px;
  padding-right: 120px;
}

.password {
  padding: 10px;
  padding-right: 120px;
  margin-top: 5px;
}

.remember {
  margin-top: 10px;
  font-size: 16px;
}

.login {
  padding-left: 123px;
  padding-right: 123px;
  padding-top: 10px;
  padding-bottom: 10px;
  margin-top: 10px;
}

.iium {
  width: 190px;
  height: 55px;
  margin-left: 1040px;
  margin-bottom: 0;
  margin-top: 55px;
}

.river {
  position: fixed;
  top: 0;
  bottom: 0;
  transform: translate(-50%, - 50%);
  background-image: url(river_of_life.jpg);
  width: 700px;
  height: 700px;
  margin-left: 70px;
  overflow: hidden;
}

.river::before {
  content: '';
  background: white;
  position: fixed;
  width: 1000px;
  height: 500px;
  margin-left: 10px;
  margin-bottom: 200px;
  overflow: hidden;
  transform-origin: top right;
  transform: rotate(23deg);
}

.river::after {
  content: '';
  background: white;
  position: fixed;
  width: 1000px;
  height: 500px;
  margin-left: 10px;
  margin-top: 665px;
  overflow: hidden;
  transform-origin: bottom left;
  transform: rotate(-23deg);
}

.footnote {
  font-size: 12px;
  float: right;
  margin-right: 120px;
  margin-top: 180px;
}

.footnote a {
  text-decoration: none;
}

.download {
  margin-left: 80px;
  position: absolute;
}
