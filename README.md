# Ex09 Event Registration Web Application
## Date: 16-10-2025
## Name: NAVEENKUMAR V
## Reg.no: 25016071

## AIM:
To design, develop and deploy a web application for event registration.

## DESIGN STEPS:

### Step 1:
Create a new frame.

### Step 2:
Select any one preset size of your choice.

### Step 3:
Select the shapes you need.

### Step 4:
Import images as needed.

### Step 5:
Create pages based on your need and link them.

### Step 6:

Validate the HTML and CSS code.

### Step 6:

Publish the website in the given URL.

## DESIGN TOOL:
Figma

## CODE:
Page-1
```
index.html

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="android-medium">
      <img class="text-on-a-path" src="img/text-on-a-path.svg" />
      <div class="text-wrapper">Register</div>
      <div class="div">Register</div>
      <div class="text"></div>
      <img class="ex-image" src="img/ex9-image2-1.png" />
      <img class="rectangle" src="img/rectangle-1.svg" />
      <div class="text-wrapper-2">Register</div>
      <div class="rectangle-2"></div>
      <div class="text-wrapper-3">Login</div>
      <div class="SAVEETHA-s-SPORTS">SAVEETHA’S&nbsp;&nbsp;SPORTS EVENT DAY</div>
    </div>
  </body>
</html>

global.css

@import url("https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css");
* {
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}
html,
body {
  margin: 0px;
  height: 100%;
}
/* a blue color as a generic focus style */
button:focus-visible {
  outline: 2px solid #4a90e2 !important;
  outline: -webkit-focus-ring-color auto 5px !important;
}
a {
  text-decoration: none;
}

style.css

.android-medium {
  position: relative;
  width: 5768px;
  height: 9678px;
  background-color: #f8e113;
  overflow: hidden;
}

.android-medium .text-on-a-path {
  position: absolute;
  top: 10381px;
  left: 3636px;
  width: 4086px;
  height: 1017px;
}

.android-medium .text-wrapper {
  position: absolute;
  top: 5650px;
  left: 821px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 12px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .div {
  top: 5426px;
  left: 821px;
  width: 4190px;
  font-family: "Inter-Regular", Helvetica;
  color: #ffffff;
  font-size: 24px;
  position: absolute;
  font-weight: 400;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .text {
  position: absolute;
  top: 4601px;
  left: 892px;
  width: 1874px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .ex-image {
  position: absolute;
  top: 0;
  left: 0;
  width: 5768px;
  height: 9678px;
  aspect-ratio: 1;
  object-fit: cover;
}

.android-medium .rectangle {
  position: absolute;
  top: 5160px;
  left: 1802px;
  width: 2932px;
  height: 829px;
}

.android-medium .text-wrapper-2 {
  top: 5394px;
  left: 2385px;
  width: 1448px;
  font-family: "Irish Grover-Regular", Helvetica;
  color: #000000;
  font-size: 300px;
  position: absolute;
  font-weight: 400;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .rectangle-2 {
  position: absolute;
  top: 3751px;
  left: 1502px;
  width: 3097px;
  height: 850px;
  background-color: #d9d9d9;
  border-radius: 425px;
}

.android-medium .text-wrapper-3 {
  position: absolute;
  top: 3989px;
  left: 2706px;
  width: 739px;
  font-family: "Inter-ExtraBold", Helvetica;
  font-weight: 800;
  color: #db0808;
  font-size: 250px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .SAVEETHA-s-SPORTS {
  position: absolute;
  top: 1751px;
  left: 774px;
  width: 4560px;
  text-shadow: 0px 4px 4px #00000040;
  font-family: "Irish Grover-Regular", Helvetica;
  font-weight: 400;
  color: #1114f6ed;
  font-size: 300px;
  letter-spacing: 0;
  line-height: normal;
}
```
Page-2
```
index.html

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="box"><img class="rectangle" src="img/rectangle-2.png" /></div>
  </body>
</html>

global.css

@import url("https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css");
* {
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}
html,
body {
  margin: 0px;
  height: 100%;
}
/* a blue color as a generic focus style */
button:focus-visible {
  outline: 2px solid #4a90e2 !important;
  outline: -webkit-focus-ring-color auto 5px !important;
}
a {
  text-decoration: none;
}

style.css

.box {
  width: 5768px;
  height: 9678px;
}

.box .rectangle {
  position: fixed;
  top: 0;
  left: 0;
  width: 5768px;
  height: 9678px;
  object-fit: cover;
}
```
Page-3
```
index.html

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="frame">
      <img class="SP" src="img/SP-1.png" />
      <div class="text-wrapper">EVENT REGISTERATION FORM</div>
      <div class="rectangle"></div>
      <img class="img" src="img/rectangle-5.svg" />
      <div class="div"></div>
      <img class="rectangle-2" src="img/rectangle-7.png" />
      <div class="rectangle-3"></div>
      <div class="rectangle-4"></div>
      <div class="rectangle-5"></div>
      <div class="rectangle-6"></div>
      <img class="rectangle-7" src="img/rectangle-12.svg" />
      <div class="text-wrapper-2">FULL NAME</div>
      <div class="text-wrapper-3">GENDER</div>
      <div class="text-wrapper-4">AGE</div>
      <div class="text-wrapper-5">REG.NO</div>
      <div class="text-wrapper-6">DEPARTMENT</div>
      <div class="text-wrapper-7">MOBILE.NO</div>
      <div class="text-wrapper-8">EVENTS TO REGISTER</div>
      <div class="text-wrapper-9">REGISTER</div>
      <div class="rectangle-8"></div>
      <div class="text-wrapper-10">EMAIL</div>
    </div>
  </body>
</html>

global.css

@import url("https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css");
* {
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}
html,
body {
  margin: 0px;
  height: 100%;
}
/* a blue color as a generic focus style */
button:focus-visible {
  outline: 2px solid #4a90e2 !important;
  outline: -webkit-focus-ring-color auto 5px !important;
}
a {
  text-decoration: none;
}

style.css

.frame {
  background-color: #d7da10;
  overflow: hidden;
  width: 100%;
  min-width: 5768px;
  min-height: 9545px;
  position: relative;
}

.frame .SP {
  position: absolute;
  top: 0;
  left: 0;
  width: 5768px;
  height: 9545px;
  aspect-ratio: 1.75;
  object-fit: cover;
}

.frame .text-wrapper {
  position: absolute;
  top: 599px;
  left: 926px;
  width: 4319px;
  -webkit-text-stroke: 1px #000000;
  font-family: "Irish Grover-Regular", Helvetica;
  font-weight: 400;
  color: #1c1a1a;
  font-size: 300px;
  letter-spacing: 0;
  line-height: normal;
}

.frame .rectangle {
  position: absolute;
  top: 1107px;
  left: 0;
  width: 5246px;
  height: 551px;
  background-color: #da9e9e;
}

.frame .img {
  position: absolute;
  top: 1812px;
  left: 1373px;
  width: 4395px;
  height: 499px;
}

.frame .div {
  position: absolute;
  top: 3131px;
  left: 404px;
  width: 100px;
  height: 100px;
  background-color: #d9d9d9;
}

.frame .rectangle-2 {
  position: absolute;
  top: 2523px;
  left: 0;
  width: 3825px;
  height: 608px;
}

.frame .rectangle-3 {
  position: absolute;
  top: 3231px;
  left: 1373px;
  width: 4395px;
  height: 752px;
  background-color: #ffadad;
}

.frame .rectangle-4 {
  position: absolute;
  top: 4083px;
  left: -241px;
  width: 4656px;
  height: 668px;
  background-color: #f38e8e;
}

.frame .rectangle-5 {
  position: absolute;
  top: 4982px;
  left: 1596px;
  width: 4172px;
  height: 641px;
  background-color: #ff9898;
}

.frame .rectangle-6 {
  position: absolute;
  top: 6532px;
  left: -63px;
  width: 5309px;
  height: 562px;
  background-color: #e68585;
}

.frame .rectangle-7 {
  position: absolute;
  top: 8023px;
  left: 1136px;
  width: 3564px;
  height: 918px;
}

.frame .text-wrapper-2 {
  position: absolute;
  top: 1218px;
  left: 247px;
  width: 1940px;
  font-family: "Irish Grover-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 300px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.frame .text-wrapper-3 {
  position: absolute;
  top: 1889px;
  left: 1672px;
  width: 1940px;
  font-family: "Irish Grover-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 300px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.frame .text-wrapper-4 {
  position: absolute;
  top: 2649px;
  left: 432px;
  width: 1857px;
  font-family: "Irish Grover-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 300px;
  letter-spacing: 0;
  line-height: normal;
}

.frame .text-wrapper-5 {
  position: absolute;
  top: 3375px;
  left: 1907px;
  width: 2149px;
  font-family: "Irish Grover-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 300px;
  letter-spacing: 0;
  line-height: normal;
}

.frame .text-wrapper-6 {
  position: absolute;
  top: 4214px;
  left: 256px;
  width: 1931px;
  font-family: "Irish Grover-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 300px;
  letter-spacing: 0;
  line-height: normal;
}

.frame .text-wrapper-7 {
  position: absolute;
  top: 5126px;
  left: 1833px;
  width: 1849px;
  font-family: "Irish Grover-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 300px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.frame .text-wrapper-8 {
  position: absolute;
  top: 6653px;
  left: 39px;
  width: 3133px;
  font-family: "Irish Grover-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 300px;
  letter-spacing: 0;
  line-height: normal;
}

.frame .text-wrapper-9 {
  position: absolute;
  top: 8315px;
  left: 2131px;
  width: 1481px;
  font-family: "Irish Grover-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 300px;
  letter-spacing: 0;
  line-height: normal;
}

.frame .rectangle-8 {
  position: absolute;
  top: 5786px;
  left: 0;
  width: 4056px;
  height: 563px;
  background-color: #e39898;
}

.frame .text-wrapper-10 {
  position: absolute;
  top: 5888px;
  left: 247px;
  width: 1320px;
  font-family: "Irish Grover-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 300px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}
```
Page-4
```
index.html

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="frame">
      <img class="sp" src="img/sp2-1.png" />
      <img class="logo" src="img/logo-3.png" />
      <div class="text-wrapper">THANK YOU</div>
      <p class="we-are-all-eagerly">
        We are all eagerly&nbsp;&nbsp;waiting for your participation in the sports events
      </p>
      <div class="div">Contact us</div>
      <div class="email-sec-gmail-com">Email:&nbsp;&nbsp;sec@gmail.com<br />Phone:&nbsp;&nbsp;6978453457</div>
    </div>
  </body>
</html>

global.css

@import url("https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css");
* {
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}
html,
body {
  margin: 0px;
  height: 100%;
}
/* a blue color as a generic focus style */
button:focus-visible {
  outline: 2px solid #4a90e2 !important;
  outline: -webkit-focus-ring-color auto 5px !important;
}
a {
  text-decoration: none;
}

style.css

.frame {
  background-color: #f28585;
  width: 100%;
  min-width: 5678px;
  min-height: 9492px;
  position: relative;
}

.frame .sp {
  position: absolute;
  top: 0;
  left: 0;
  width: 5678px;
  height: 9492px;
  aspect-ratio: 1.5;
  object-fit: cover;
}

.frame .logo {
  position: absolute;
  top: 540px;
  left: 182px;
  width: 5313px;
  height: 799px;
  aspect-ratio: 6.65;
  object-fit: cover;
}

.frame .text-wrapper {
  position: absolute;
  top: 1552px;
  left: 2088px;
  width: 1599px;
  font-family: "Irish Grover-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 300px;
  letter-spacing: 0;
  line-height: normal;
}

.frame .we-are-all-eagerly {
  position: absolute;
  top: 4774px;
  left: 1669px;
  width: 3144px;
  font-family: "Inria Sans-Bold", Helvetica;
  font-weight: 700;
  color: #e72e2e;
  font-size: 300px;
  letter-spacing: 0;
  line-height: normal;
}

.frame .div {
  position: absolute;
  top: 7022px;
  left: 1764px;
  width: 2006px;
  font-family: "Inria Sans-Bold", Helvetica;
  font-weight: 700;
  color: #15c243;
  font-size: 400px;
  letter-spacing: 0;
  line-height: normal;
}

.frame .email-sec-gmail-com {
  position: absolute;
  top: 7959px;
  left: 1468px;
  width: 3345px;
  font-family: "Inria Sans-Bold", Helvetica;
  font-weight: 700;
  color: #ffffff;
  font-size: 300px;
  letter-spacing: 0;
  line-height: normal;
}
```

## OUTPUT:
<img width="1920" height="1080" alt="Ex09" src="https://github.com/user-attachments/assets/9c7dbf5f-7fc0-4bba-91c9-e1c83c67fde2" />

## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
