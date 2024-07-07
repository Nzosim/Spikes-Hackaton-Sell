<template>
  <link href="https://fonts.googleapis.com/css2?family=Dela+Gothic+One&display=swap" rel="stylesheet">
  <div class="background-orange"></div>
  <div class="background-blue"></div>
  <div class="background-violet"></div>
  <img class="grille" src="@/assets/grille.svg" alt="grille d'arriere plan">
  <div class="header">
    <div>
      <img src="@/assets/logo.svg" alt="logo" height="17px" width="auto" />
      <p>Sell</p>
    </div>
    <div class="twitter">
      <img src="@/assets/twitter.svg" alt="logo" height="17px" width="auto" />
      <p>Follow us on Twitter</p>
    </div>
  </div>
  <p class="birthday">Introducing a new online selling platform 🎉</p>
  <div class="main">
    <p>Best way to sell</p>
    <p>your digital product</p>
  </div>
  <div class="sub">
    <p>Go from Zero to Hero with simple platform that helps</p>
    <p>creators like you sell their digital products online.</p>
  </div>
  <div class="form-container">
    <div class="form">
      <input type="text" placeholder="Your best email address" />
      <button>Try it out</button>
    </div>
  </div>
  <div class="number">
    <img src="@/assets/p1.png">
    <img src="@/assets/p2.png" style="margin-left: -15px;">
    <img src="@/assets/p3.png" style="margin-left: -15px;">
    <img src="@/assets/p4.png" style="margin-left: -15px;">
    <img src="@/assets/p5.png" style="margin-left: -15px;">
    <p><span>More than 100+</span> users are selling their products <br>online with simple & easy ways</p>
  </div>
</template>

<style>
body {
  background-color: #F5F5F5;
  font-family: 'DM Sans', sans-serif;
}

.background-orange {
  background-color: rgba(254, 164, 146, 0.5);
  height: 700px;
  width: 700px;
  border-radius: 500px 500px;
  position: absolute;
  top: -140px;
  left: 15%;
  filter: blur(120px);
  z-index: -1;
}

.background-blue {
  background-color: rgb(146, 196, 254);
  height: 550px;
  width: 550px;
  border-radius: 500px 500px;
  position: absolute;
  top: -170px;
  right: 20%;
  filter: blur(100px);
  z-index: -1;
}

.header {
  display: flex;
  background-color: #282828;
  height: 25px;
  width: 606px;
  border-radius: 10px;
  margin-left: auto;
  margin-right: auto;
  margin-top: 50px;
}

.header img {
  margin-left: 10px;
  margin-right: 5px;
}

.header div {
  display: flex;
  align-items: center; 
  color: white;
}

.twitter {
  margin-left: auto;
  margin-right: 10px;
  font-family: 'inter', sans-serif;
  font-size: 12px;
  padding-right: 10px;
}

.birthday {
  font-size: 12px;
  color: white;
  margin-top: 50px;
  background: linear-gradient(90deg, #E693A5, #3951E5);
  border-radius: 50px;
  padding: 8px;
  width: 250px;
  margin-left: auto;
  margin-right: auto;
  text-align: center;
}

.main {
  margin-top: 60px;
}

.main p {
  font-size: 48px;
  line-height: 10px;
  font-family: 'Dela Gothic One', cursive;
  text-align: center;
}

.sub {
  margin-top: 50px;
}

.sub p {
  text-align: center;
  color: #626262;
  line-height: 8px;
}

.form-container {
  display: flex;
  justify-content: center;
  margin-top: 50px;
}

.form {
  display: flex;
  border-radius: 10px;
  font-family: 'DM Sans', sans-serif;
}

.form input {
  width: 250px;
  border: none;
  border-radius: 5px; 
  margin-right: 10px;
  padding: 15px;
}

button {
  background-color: #314EE7;
  color: white;
  border-radius: 5px;
  border: none;
  padding: 0 30px;
}

.grille {
  position: absolute;
  top: 30px;
  width: 60%;
  left: 20%;
  z-index: -1;
}

.number {
  display: flex;
  justify-content: center;
  margin-top: 25px;
}

.number img {
  width: 30px;
  height: 30px;
  border-radius: 50px;
  margin-left: -15px;
  margin-top: 20px;
}

.number p {
  margin-left: 10px;
  font-family: 10px;
  opacity: 0.5;
}

.number p span {
  font-weight: bold;
  color: black;
  opacity: 0.9;
}
</style>
