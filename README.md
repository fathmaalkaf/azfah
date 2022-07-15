<HTML>
<HEAD>
<meta charset="utf-8">
  <meta name="viewport" content="width=100%, initial-scale=1">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/css/bootstrap.min.css">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.6.0/jquery.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/js/bootstrap.min.js"></script>
  <style>
  .carousel-inner > .item > img,
  .carousel-inner > .item > a > img {
    width: 100%;
    margin: auto;
  }
  </style>
  <div class="container">
  <br>
  <div id="myCarousel" class="carousel slide" data-ride="carousel">
    <!-- Indicators -->
    <ol class="carousel-indicators">
      <li data-target="#myCarousel" data-slide-to="0" class="active"></li>
      <li data-target="#myCarousel" data-slide-to="1"></li>
      <li data-target="#myCarousel" data-slide-to="2"></li>
      <li data-target="#myCarousel" data-slide-to="3"></li>
    </ol>
    <!-- Wrapper for slides -->
    <div class="carousel-inner" role="listbox">
      <div class="item active">
        <img src="LAPTOP1.jpg" alt="Chania" width="1000" height="500">
        <div class="carousel-caption">
          <h3>Chania</h3>
          <p>The atmosphere in Chania has a touch of Florence and Venice.</p>
        </div>
      </div>
      <div class="item">
        <img src="img_chania2.jpg" alt="Chania" width="460" height="345">
        <div class="carousel-caption">
          <h3>Chania</h3>
          <p>The atmosphere in Chania has a touch of Florence and Venice.</p>
        </div>
      </div>
      <div class="item">
        <img src="img_flower.jpg" alt="Flower" width="460" height="345">
        <div class="carousel-caption">
          <h3>Flowers</h3>
          <p>Beautiful flowers in Kolymbari, Crete.</p>
        </div>
      </div>
      <div class="item">
        <img src="img_flower2.jpg" alt="Flower" width="460" height="345">
        <div class="carousel-caption">
          <h3>Flowers</h3>
          <p>Beautiful flowers in Kolymbari, Crete.</p>
        </div>
      </div>
    </div>
    <!-- Left and right controls -->
    <a class="left carousel-control" href="#myCarousel" role="button" data-slide="prev">
      <span class="glyphicon glyphicon-chevron-left" aria-hidden="true"></span>
      <span class="sr-only">Previous</span>
    </a>
    <a class="right carousel-control" href="#myCarousel" role="button" data-slide="next">
      <span class="glyphicon glyphicon-chevron-right" aria-hidden="true"></span>
      <span class="sr-only">Next</span>
    </a>
</div>
<style>
#name, #age, #gender, #email, #phone, #desc {
  background-color: lightblue;
  color: black;
  padding: 10px;
  text-align: center;
  border-radius: 18px;
}  
form {
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
}
button {
    color: white;
    background: purple;
    padding: 8px 12px;
    font-size: 20px;
    border: 2px solid white;
    border-radius: 14px;
    cursor: pointer;
    }
</style>
<title>
fattum
</title>
<p style="background-color:Tomato;">Welcome this is Azfah</p>
<div class="w3-container" id="contact">
    <h2>Contact</h2>
    <h1>Nai samajh ara form name kya likhna ki khair registration form boltio abke liye .</h1>
    <i class="fa fa-map-marker w3-text-red" style="width:30px"></i> location: Apke Dil main  <br>
    <i class="fa fa-phone w3-text-red" style="width:30px"></i> Phone: +tumaku yeh bhi yaad nai hai badal gaya admiiiiiii *crying on corner <span style='font-size:100px;'>&#128557;</span><br>
    <i class="fa fa-envelope w3-text-red" style="width:30px"> </i> Email: meraichmaloomnatumakutoh@mail.com<br>
     <form action="index.php" method="post">
            <input type="text" name="name" id="name" placeholder="Enter your name">
            <input type="text" name="age" id="age" placeholder="Enter your Age">
            <input type="text" name="gender" id="gender" placeholder="Enter your gender">
            <input type="email" name="email" id="email" placeholder="Enter your email">
            <input type="phone" name="phone" id="phone" placeholder="Enter your phone">
            <textarea name="desc" id="desc" cols="30" rows="10" placeholder="Enter any other information here"></textarea>
            <button type="button" onclick="alert('Thank you!')">Submit!</button>
        </form>
  </div>

<HEAD>
</HTML>

