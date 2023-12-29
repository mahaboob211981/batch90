<!DOCTYPE html>
<html lang="en">
<head>
<title>Page Title</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;
}

/* Style the body */
body {
  font-family: Arial, Helvetica, sans-serif;
  margin: 0;
}
.column {
  float: left;
  width: 50%;
  padding: 10px;
  height: 100px; /* Should be removed. Only for demonstration */
}

.column13 {
  float: left;
  width: 50%;
  padding: 10px;
  height: auto; /* Should be removed. Only for demonstration */
}
/* Header/logo Title */
.header {
  padding: 80px;
  text-align: center;
  background: #1abc9c;
  color: white;
}

/* Increase the font size of the heading */
.header h1 {
  font-size: 50px;
}

/* Style the top navigation bar */
.navbar {
  overflow: hidden;
  background-color: #333;
}

/* Style the navigation bar links */
.navbar a {
  float: left;
  display: block;
  color: white;
  text-align: center;
  padding: 14px 20px;
  text-decoration: none;
}

/* Right-aligned link */
.navbar a.right {
  float: right;
}

/* Change color on hover */
.navbar a:hover {
  background-color: #ddd;
  color: black;
}



/* Create two unequal columns that sits next to each other */
/* Sidebar/left column */
.side {
  -ms-flex: 30%; /* IE10 */
  flex: 30%;
  background-color: #f1f1f1;
  padding: 20px;
}

/* Main column */
.main {   
  -ms-flex: 70%; /* IE10 */
  flex: 70%;
  background-color: white;
  padding: 20px;
}

/* Fake image, just for this example */
.fakeimg {
  background-color: #aaa;
  width: 100%;
  padding: 20px;
}

/* Footer */
.footer {
  padding: 20px;
  text-align: center;
  background: #ddd;
}

/* Responsive layout - when the screen is less than 700px wide, make the two columns stack on top of each other instead of next to each other */
@media screen and (max-width: 700px) {
  .row {   
    flex-direction: column;
  }
}

/* Responsive layout - when the screen is less than 400px wide, make the navigation links stack on top of each other instead of next to each other */
@media screen and (max-width: 400px) {
  .navbar a {
    float: none;
    width: 100%;
  }
}
.row:after {
  content: "";
  display: table;
  clear: both;
}
</style>
</head>
<body>
<div class="row">
  <div class="column" style="background-color:#aaa;">
     <h3>welcom to my world</h3>
  </div>
  <div class="column navbar" style="background-color:#bbb;">
   <a href="#" class="right">my account</a>
  <a href="#" class="right">sign up</a>
  <a href="#" class="right">Login</a>
  </div>
</div>


<div class="row">
  <div class="column13" style="background-color:#aaa;">
    <div class="row">
  <div class="side">
   

<form action="/action_page.php">
  <label for="fname">First name:</label><br>
  <input type="text" id="fname" name="fname" value=" "><br>
  <label for="lname">Last name:</label><br>
  <input type="text" id="lname" name="lname" value=" "><br><br>
 
</form> 
</div>
</div>
<br>
  <div class="main">
    <form action="/action_page.php">  
  <input type="radio" id="male" name="gender" value="male">
  <label for="male">Male</label><br>
  <input type="radio" id="female" name="gender" value="female">
  <label for="female">Female</label><br>
  <input type="radio" id="other" name="gender" value="other">
  <label for="other">Other</label>

 
</form>
<br>




<form action="/action_page.php">
  <label for="district">Choose your district:</label>
  <br>
  <select name="district" id="cars">
    <option value="select">select</option>
    <option value="kurnool">kurnool</option>
    <option value="kadapa">kadapa</option>
    <option value="nellur">nellur</option>
  </select>

  
</form>
<br>




  

<form action="/action_page.php">
  <input type="checkbox" id="vehicle1" name="vehicle1" value="Bike">
  <label for="vehicle1"> I have a bike</label><br>
  <input type="checkbox" id="vehicle2" name="vehicle2" value="Car">
  <label for="vehicle2"> I have a car</label><br>
  <input type="checkbox" id="vehicle3" name="vehicle3" value="Boat">
  <label for="vehicle3"> I have a boat</label><br><br>
  
</form>

  </div>
  <form action="/action_page.php" id="usrform">
  Name: <input type="text" name="usrname">
  
</form>
<br>
<textarea rows="2" cols="10" name="comment" form="usrform">
Enter text here...</textarea>


  </div>
  <div class="column13 " style="background-color:#bbb;">
 <img src="img_girl.jpg" alt="Girl in a jacket" width="300" height="300px"> 

<br>
<p>1. Is it already dark there? It is already dark here. There are a large number of stars in the sky. The sky always amazes me. It seems to be limitless without any boundaries. You have a strange resemblance to this sky. You amaze me just like this beautiful sky and my feelings for you have no boundaries. I am simply unable to put limits or boundaries to my love for you. It keeps on increasing.</p>
  </div>
</div>


<br>


<div class="footer">
  <div class="row"> 
  <div class="column1 navbar" style="background-color:#bbb;">
   <a href="#" class="right">copyrights reserved@2021 myworld!</a>
  <div class="column2 navbar" style="background-color:#bbb;">
   <a href="#" class="left">any queris:my world@gmail.com!</a>
  </div>
      </div>

</div>

</div>
<br>

</body>
</html>
