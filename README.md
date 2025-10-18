# Ex09 Event Registration Web Application
## Date:18/10/2025

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
```
HTML

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
      <img class="SEC-logo" src="img/SEC-logo-1-1.png" />
      <img class="saveetha-engineering" src="img/saveetha-engineering-college-sriperumbudur-chennai-1.png" />
      <div class="rectangle"></div>
      <div class="LOGIN">LOGIN</div>
      <div class="div"></div>
      <div class="text-wrapper">REGISTER NOW</div>
      <div class="text-wrapper-2">Already have an account?</div>
      <div class="HOSTEL-FEST">HOSTEL&nbsp;&nbsp; FEST</div>
      <img class="images" src="img/images-1.png" />
    </div>
  </body>
</html>

CSS

.android-medium {
  position: relative;
  width: 1080px;
  height: 1920px;
  background-color: #fdfdfd;
  border-radius: 40px;
  overflow: hidden;
  border: 20px solid;
  border-color: #1f1d1d;
}

.android-medium .SEC-logo {
  position: absolute;
  top: 333px;
  left: 292px;
  width: 496px;
  height: 478px;
  aspect-ratio: 1.04;
  object-fit: cover;
}

.android-medium .saveetha-engineering {
  position: absolute;
  top: 72px;
  left: 29px;
  width: 1022px;
  height: 212px;
  aspect-ratio: 4.81;
  object-fit: cover;
}

.android-medium .rectangle {
  position: absolute;
  top: 898px;
  left: 347px;
  width: 400px;
  height: 111px;
  background-color: #f6c6c4;
}

.android-medium .LOGIN {
  position: absolute;
  top: 881px;
  left: 347px;
  width: 462px;
  transform: rotate(0.32deg);
  -webkit-text-stroke: 1px #000000;
  font-family: "Kaisei Decol-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 96px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .div {
  position: absolute;
  top: 1081px;
  left: 274px;
  width: 549px;
  height: 100px;
  background-color: #f6c6c4;
}

.android-medium .text-wrapper {
  position: absolute;
  top: 1081px;
  left: 280px;
  width: 598px;
  font-family: "Kaisei Decol-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 64px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .text-wrapper-2 {
  position: absolute;
  top: 1195px;
  left: 325px;
  width: 596px;
  font-family: "Kaisei Decol-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .HOSTEL-FEST {
  position: absolute;
  top: 796px;
  left: 354px;
  width: 469px;
  font-family: "Kaisei Decol-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 48px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .images {
  position: absolute;
  top: 1355px;
  left: 103px;
  width: 873px;
  height: 524px;
  aspect-ratio: 1.67;
  object-fit: cover;
}


page 2
HTML
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
      <div class="text-wrapper">USERNAME</div>
      <img class="rectangle" src="img/rectangle-2.svg" />
      <div class="div">PASSWORD</div>
      <div class="rectangle-2"></div>
      <div class="rectangle-3"></div>
      <img class="arrow" src="img/arrow-1.svg" />
      <img class="BACK" src="img/BACK.png" />
      <div class="text-wrapper-2">FORGET PASSWORD?</div>
      <div class="rectangle-4"></div>
      <div class="text-wrapper-3">ENTER</div>
    </div>
  </body>
</html>

CSS

.android-medium {
  position: relative;
  width: 1080px;
  height: 1920px;
  background-color: #fdfdfd;
  border-radius: 40px;
  overflow: hidden;
  border: 20px solid;
  border-color: #000000;
}

.android-medium .text-wrapper {
  position: absolute;
  top: 490px;
  left: 238px;
  width: 747px;
  font-family: "Kaisei Decol-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 96px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .rectangle {
  position: absolute;
  top: 649px;
  left: 238px;
  width: 562px;
  height: 96px;
}

.android-medium .div {
  position: absolute;
  top: 778px;
  left: 250px;
  width: 608px;
  font-family: "Kaisei Decol-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 96px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.android-medium .rectangle-2 {
  position: absolute;
  top: 980px;
  left: 250px;
  width: 550px;
  height: 114px;
  background-color: #d9d9d9;
}

.android-medium .rectangle-3 {
  position: absolute;
  top: 38px;
  left: 45px;
  width: 231px;
  height: 78px;
  background-color: #d9d9d9;
}

.android-medium .arrow {
  position: absolute;
  top: 70px;
  left: 65px;
  width: 67px;
  height: 15px;
}

.android-medium .BACK {
  position: absolute;
  top: calc(50.00% - 895px);
  left: 129px;
  width: 114px;
  height: 37px;
}

.android-medium .text-wrapper-2 {
  position: absolute;
  top: 1127px;
  left: 319px;
  width: 539px;
  font-family: "Kaisei Decol-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .rectangle-4 {
  position: absolute;
  top: 1451px;
  left: 365px;
  width: 300px;
  height: 124px;
  background-color: #ba34237a;
}

.android-medium .text-wrapper-3 {
  position: absolute;
  top: 1451px;
  left: 399px;
  width: 380px;
  font-family: "Kaisei Decol-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 64px;
  letter-spacing: 0;
  line-height: normal;
}


page 3

HTML
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
      <div class="text-wrapper">EVENTS FOR REGISTRATION</div>
      <div class="rectangle"></div>
      <div class="div"></div>
      <div class="rectangle-2"></div>
      <div class="rectangle-3"></div>
      <img class="star" src="img/star-3.svg" />
      <div class="rectangle-4"></div>
      <img class="img" src="img/rectangle-12.svg" />
      <div class="TAP-TO">TAP&nbsp;&nbsp; TO</div>
      <div class="text-wrapper-2">REGISTER NOW</div>
      <div class="rectangle-5"></div>
      <img class="arrow" src="img/arrow-2.svg" />
      <div class="text-wrapper-3">BACK</div>
      <img class="star-2" src="img/image.svg" />
      <img class="star-3" src="img/star-5.svg" />
      <img class="star-4" src="img/star-4.svg" />
      <img class="star-5" src="img/star-2.svg" />
      <img class="star-6" src="img/star-1.svg" />
      <div class="text-wrapper-4">CRICKET</div>
      <div class="text-wrapper-5">FOOTBALL</div>
      <div class="text-wrapper-6">DANCE</div>
      <div class="text-wrapper-7">SONG</div>
      <div class="text-wrapper-8">VOLLEYBALL</div>
      <div class="text-wrapper-9">RELAY</div>
    </div>
  </body>
</html>

CSS

.android-medium {
  position: relative;
  width: 1080px;
  height: 1920px;
  background-color: #ffffff;
  border-radius: 40px;
  overflow: hidden;
  border: 20px solid;
  border-color: #000000;
}

.android-medium .text-wrapper {
  position: absolute;
  top: 107px;
  left: 168px;
  width: 880px;
  font-family: "Kaisei Decol-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 48px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .rectangle {
  position: absolute;
  top: 297px;
  left: 284px;
  width: 472px;
  height: 92px;
  background-color: #d9d9d9;
}

.android-medium .div {
  position: absolute;
  top: 451px;
  left: 284px;
  width: 472px;
  height: 92px;
  background-color: #d9d9d9;
}

.android-medium .rectangle-2 {
  position: absolute;
  top: 605px;
  left: 284px;
  width: 472px;
  height: 96px;
  background-color: #d9d9d9;
}

.android-medium .rectangle-3 {
  position: absolute;
  top: 763px;
  left: 284px;
  width: 472px;
  height: 92px;
  background-color: #d9d9d9;
}

.android-medium .star {
  top: 772px;
  left: 286px;
  position: absolute;
  width: 65px;
  height: 57px;
}

.android-medium .rectangle-4 {
  position: absolute;
  top: 912px;
  left: 275px;
  width: 529px;
  height: 98px;
  background-color: #d9d9d9;
}

.android-medium .img {
  position: absolute;
  top: 1077px;
  left: 280px;
  width: 476px;
  height: 104px;
}

.android-medium .TAP-TO {
  position: absolute;
  top: 1222px;
  left: 399px;
  width: 492px;
  font-family: "Kaisei Decol-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 48px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .text-wrapper-2 {
  position: absolute;
  top: 1286px;
  left: 328px;
  width: 884px;
  font-family: "Kaisei Decol-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 48px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .rectangle-5 {
  position: absolute;
  top: 28px;
  left: 37px;
  width: 247px;
  height: 79px;
  background-color: #d9d9d9;
}

.android-medium .arrow {
  position: absolute;
  top: 61px;
  left: 59px;
  width: 76px;
  height: 15px;
}

.android-medium .text-wrapper-3 {
  position: absolute;
  top: 32px;
  left: 150px;
  width: 155px;
  -webkit-text-stroke: 1px #2c1010;
  font-family: "Kaisei Decol-Regular", Helvetica;
  font-weight: 400;
  color: #ff0f0f;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .star-2 {
  top: 311px;
  left: 286px;
  position: absolute;
  width: 65px;
  height: 57px;
}

.android-medium .star-3 {
  top: 1086px;
  left: 286px;
  position: absolute;
  width: 65px;
  height: 57px;
}

.android-medium .star-4 {
  top: 936px;
  left: 284px;
  position: absolute;
  width: 65px;
  height: 57px;
}

.android-medium .star-5 {
  top: 614px;
  left: 286px;
  position: absolute;
  width: 65px;
  height: 57px;
}

.android-medium .star-6 {
  position: absolute;
  top: 467px;
  left: 286px;
  width: 65px;
  height: 57px;
}

.android-medium .text-wrapper-4 {
  position: absolute;
  top: 297px;
  left: 370px;
  width: 410px;
  font-family: "Kaisei Decol-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 64px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .text-wrapper-5 {
  position: absolute;
  top: 451px;
  left: 364px;
  width: 421px;
  font-family: "Kaisei Decol-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 64px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .text-wrapper-6 {
  position: absolute;
  top: 592px;
  left: 380px;
  width: 390px;
  font-family: "Kaisei Decol-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 64px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .text-wrapper-7 {
  position: absolute;
  top: 757px;
  left: 385px;
  width: 349px;
  font-family: "Kaisei Decol-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 64px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .text-wrapper-8 {
  position: absolute;
  top: 912px;
  left: 341px;
  width: 463px;
  font-family: "Kaisei Decol-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 64px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .text-wrapper-9 {
  position: absolute;
  top: 1070px;
  left: 373px;
  width: 374px;
  font-family: "Kaisei Decol-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 64px;
  letter-spacing: 0;
  line-height: normal;
}

page 4
HTML
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
      <img class="istockphoto" src="img/istockphoto-1451590744-612x612-1.png" />
      <div class="text-wrapper">THANK YOU</div>
      <div class="div">FOR YOUR REGISTRATION</div>
    </div>
  </body>
</html>

CSS

.android-medium {

position: relative;

width: 1080px;

height: 1920px;

background-color: #ffffff;

border-radius: 40px;

overflow: hidden;

border: 20px solid;

border-color: #000000;

android-medium .istockphoto {

position: absolute;

top: 271px;

left: 20px;

width: 1048px;

height: 568px;

aspect-ratio: 1.83;

object-fit: cover;

-android-medium-text-wrapper

position: absolute;

(1)

top: 714px;

left: 350px;

width: 730px;

height: 436px;

display: flex;

Found

align-items: center;

justify-content: center;
font-family: "Kaisei Decol-Regular", Helvetica;

font-weight: 400;

color: #000000;

font-size: 64px;

letter-spacing: 0;

line-height: normal;

android-medium.div {

position: absolute;

top: 1028px;

left: 315px;

width: 607px;

height: 171px;

display: flex;

align-items: center;

justify-content: center;

font-family: "Kadwa-Regular", Helvetica;

font-weight: 400;

color: #000000;

font-size: 40px;

letter-spacing: 0;

line-height: normal;
}
```

## OUTPUT:


## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
