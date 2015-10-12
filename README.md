# Lubuntu-Web-Page
nav bar html

<!DOCTYPE html>
<html>
  <body class="news">
  <header>
    <link rel="stylesheet" href="main.css">
    <div class="nav">
      <ul>
        <li class="home"><a href="#">Home</a></li>
        <li class="About Us"><a class="active" href="#">About Us</a></li>
        <li class="Merchandise"><a href="C:\Users\10043593\Documents\GitHub\Lubuntu-Web-Page\merchandise.html">Merchandise</a></li>
        <a href="#"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/2/27/Lubuntu_logo.svg/2000px-Lubuntu_logo.svg.png"></a>
      </ul>
    </div>
  </header>
</body>
</html>


nav bar css

body {
  margin: 0;
  padding: 0;
  background: #ccc;
}

.nav ul {
  list-style: none;
  background-color: white;
  text-align: center;
  padding: 0;
  margin: 0;
}

.nav li {
  font-family: 'Oswald', sans-serif;
  font-size: 1.2em;
  line-height: 40px;
  height: 40px;
  border-bottom: 1px solid #888;
}

.nav a {
  text-decoration: none;
  color: #001F5C;
  display: block;
  transition: .5s background-color;
}

.nav a:hover {
  background-color: #B2B2B2;
}


@media screen and (min-width: 600px) {
  .nav li {
    width: 150px;
    border-bottom: none;
    height: 50px;
    line-height: 50px;
    font-size: 1.4em;
    
  }
  
  .nav li {
    display: inline-block;
    margin-right: -4px;
  }
  
  .nav img {
      max-height: 45px;
      position: absolute;
      top: 2px;
      left: 5px;
  }
