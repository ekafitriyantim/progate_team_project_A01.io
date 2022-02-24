<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>Kalse</title>
    <link rel="stylesheet" href="stylesheet.css">
    <link rel="stylesheet" href="responsive.css">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
  </head>
  <body>
    <header>
      <div class="Header-logo">
        <div class="header-left">
          <img class="logo" src="https://i.ibb.co/SdHTXVF/Header-logo-TLOB.png">
        </div>
      </div>
    </header>
    <div class="top-wrapper">
      <div class="container">
        <h3>Welcome to</h3>
        <h1>THE LORE OF BOOKS</h1> 
      </div>
      <div class="btn">
        <button type="btn">Explore</button>
      </div>
      <div class="img">
        <img class="img-responsive image-resize" src="https://i.ibb.co/19kmBtz/pablo-198.png">
      </div>
      <div  class="img-person">
        <img class="img-responsive image-resize-2" src="https://i.ibb.co/gjY86PC/pablo-209.png">
      </div>
    </div>
    <div class="content"></div>
  </body>
</html>
* {
  box-sizing: border-box;
  }

  html, body,
ul, ol, li,
h1, h3, div {
  margin: 0;
  padding: 0;
}

div {
  display:block
}

header {
  height: 65px;
  width: 100%;
  background-color:rgb(29, 27, 27);
  position: relative;
  top: 0;
  z-index: 10;
}

.btn-wrapper {
  float:right;
  margin-right: 25px;
}

.btn-wrapper a {
  line-height: 65px;
  padding: 0 25px;
  color: white;
  display: block;
  float: left;
  transition: all 0.5s;
}

.logo {
    width: 140px;
    margin: 10px 10px;
}

.top-wrapper {
  text-align: center;
  padding: 120px 50px;
  height: 518px;
  margin: 0 auto;
  background-color: #ffe7d7;
  background-size: cover;
}

.container {
  text-align: center;
  font-family: "Avenir Next", sans-serif;
}

.container h3 {
  font-size: 25px;
}

.container h1 {
  font-size: 60px;
}

button {
  text-align: center;
  position:relative;
  top:50px;
  width:130px;
  height:40px;
  color:#ffe7d7;
  font-size: 17px;
  background: rgb(29, 27, 27);
  border: 0;
  border-radius: 50px;
  outline: none;
  margin-top:30px;
  font-family: "Avenir Next", sans-serif;
  text-align: center;
  cursor: pointer;
  box-sizing: border-box;
  display:inline-block;
  transition: transform 0.5s;
}

.btn:active{
  position: relative;
  top: 3px;
  bottom: 2px;
  box-shadow:none;
}

.image-resize {
  float:left;
  margin: -70px -80px;
  width: 350px;
  height: 300px;
}

.image-resize-2{
  float:right;
  margin: -80px -50px;
  width: 420px;
  height: 310px;
}

.content {
  height: 1000px;
  width: 100%;
  background-color:rgb(255, 253, 253);
  position: relative;
  top: 0;
  z-index: 10;
}
