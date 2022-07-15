<HTML>
<HEAD>

<style>
   p {font-size: 50px; 
 text-align: center;
 background: orange;
   }
#name, #age, #gender, #email, #phone, #desc {
  background-color: lightblue;
  color: black;
  padding: 10px;
  text-align: center;
  border-radius: 18px;
    width: 100%;
    margin: 21px 0px;
}
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
<p style="background-color: orange;">Welcome this is Azfah</p>
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
  <link rel="stylesheet" href="form.html">

<HEAD>
</HTML>

