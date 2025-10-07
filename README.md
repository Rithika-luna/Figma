# Ex09 Event Registration Web Application
## Date: 07.10.2025


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
      <img class="screenshot" src="img/screenshot-2025-10-06-142808-1.png" />
      <img class="img" src="img/screenshot-2025-10-06-210457-1.png" />
      <div class="rectangle"></div>
      <div class="INDIA-INTERNATIONAL">INDIA&nbsp;&nbsp;&nbsp;&nbsp;INTERNATIONAL <br />SPACE CONCLAVE 2025</div>
      <div class="div"></div>
      <div class="text-wrapper">LOGIN</div>
      <div class="rectangle-2"></div>
      <div class="text-wrapper-2">REGISTER</div>
      <div class="rectangle-3"></div>
      <p class="p">DATE : 18TH TO 19TH NOV 2025</p>
      <div class="rectangle-4"></div>
      <p class="text-wrapper-3">VENUE : THE LALIT, NEW DELHI</p>
    </div>
  </body>
</html>     
                                                                                           
                                                                                           
                                                                                                                                                               control.css 



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


 android-medium {
  background-color: #ffffff;
  width: 100%;
  min-width: 700px;
  min-height: 840px;
  position: relative;
}

.android-medium .screenshot {
  position: absolute;
  top: 22px;
  left: 10px;
  width: 690px;
  height: 796px;
  aspect-ratio: 0.87;
  object-fit: cover;
}

.android-medium .img {
  position: absolute;
  top: 104px;
  left: 145px;
  width: 334px;
  height: 664px;
  aspect-ratio: 0.5;
  object-fit: cover;
}

.android-medium .rectangle {
  position: absolute;
  top: 56px;
  left: 152px;
  width: 319px;
  height: 107px;
  background-color: #e29075;
}

.android-medium .INDIA-INTERNATIONAL {
  position: absolute;
  top: 81px;
  left: 169px;
  width: 387px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #324f8d;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .div {
  position: absolute;
  top: 391px;
  left: 233px;
  width: 157px;
  height: 48px;
  background: linear-gradient(
    90deg,
    rgba(34, 56, 126, 1) 0%,
    rgba(48, 77, 175, 1) 57%,
    rgba(62, 101, 228, 1) 100%
  );
}

.android-medium .text-wrapper {
  position: absolute;
  top: 402px;
  left: 283px;
  width: 78px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #ffffff;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .rectangle-2 {
  position: absolute;
  top: 458px;
  left: 233px;
  width: 157px;
  height: 53px;
  background: linear-gradient(
    180deg,
    rgba(63, 67, 148, 1) 0%,
    rgba(20, 21, 46, 1) 100%
  );
}

.android-medium .text-wrapper-2 {
  position: absolute;
  top: 470px;
  left: 253px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #ffffff;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .rectangle-3 {
  position: absolute;
  top: 601px;
  left: 182px;
  width: 279px;
  height: 50px;
  background-color: #401a1a;
}

.android-medium .p {
  position: absolute;
  top: 612px;
  left: 195px;
  width: 251px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #ffffff;
  font-size: 16px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .rectangle-4 {
  position: absolute;
  top: 670px;
  left: 183px;
  width: 278px;
  height: 41px;
  background-color: #2c0808;
}

.android-medium .text-wrapper-3 {
  position: absolute;
  top: 682px;
  left: 195px;
  width: 246px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #ffffff;
  font-size: 16px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}


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
      <img class="screenshot" src="img/screenshot-2025-10-06-142808-1.png" />
      <img class="img" src="img/screenshot-2025-10-07-090513-1.png" />
      <div class="rectangle"></div>
      <div class="text-wrapper">SPACE EVENTS</div>
      <p class="TRIP-TO-MARS-TRIP-TO">
        TRIP TO MARS<br />TRIP TO MOON<br />SEMINAR ON GALAXY<br />
        HUBBLE VIEW <br />QUOTES ABOUT ASTRONOMY<br />PICTURES WITH ASTRONOMERS<br />POETRY ABOUT UNIVERSE<br />SEMINAR
        ON MULTIVERSE
      </p>
      <img class="line" src="img/line-1.svg" />
      <img class="line-2" src="img/line-2.svg" />
      <img class="line-3" src="img/line-3.svg" />
      <img class="line-4" src="img/line-4.svg" />
      <img class="line-5" src="img/line-5.svg" />
      <img class="line-6" src="img/line-6.svg" />
      <img class="line-7" src="img/line-7.svg" />
      <img class="line-8" src="img/line-8.svg" />
      <img class="line-9" src="img/line-9.svg" />
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


                                                                                                                                                               style.css                                                             .android-medium 
{
  background-color: #ffffff;
  width: 100%;
  min-width: 1086px;
  min-height: 1519px;
  position: relative;
}

.android-medium .screenshot {
  position: absolute;
  top: 23px;
  left: 0;
  width: 1086px;
  height: 1474px;
  aspect-ratio: 0.77;
  object-fit: cover;
}

.android-medium .img {
  position: absolute;
  top: 199px;
  left: 155px;
  width: 631px;
  height: 1150px;
  aspect-ratio: 0.55;
  object-fit: cover;
}

.android-medium .rectangle {
  position: absolute;
  top: 80px;
  left: 155px;
  width: 631px;
  height: 119px;
  background-color: #9896ac;
}

.android-medium .text-wrapper {
  position: absolute;
  top: 101px;
  left: 214px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 64px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .TRIP-TO-MARS-TRIP-TO {
  position: absolute;
  top: 965px;
  left: 154px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #f0e4e4;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .line {
  top: 999px;
  left: 157px;
  width: 629px;
  height: 13px;
  position: absolute;
  object-fit: cover;
}

.android-medium .line-2 {
  top: 1043px;
  left: 160px;
  width: 626px;
  height: 7px;
  position: absolute;
  object-fit: cover;
}

.android-medium .line-3 {
  top: 1087px;
  left: 155px;
  width: 631px;
  height: 3px;
  position: absolute;
  object-fit: cover;
}

.android-medium .line-4 {
  top: 1131px;
  left: 157px;
  width: 618px;
  height: 5px;
  position: absolute;
  object-fit: cover;
}

.android-medium .line-5 {
  top: 1175px;
  left: 160px;
  width: 615px;
  height: 7px;
  position: absolute;
  object-fit: cover;
}

.android-medium .line-6 {
  top: 1224px;
  left: 160px;
  width: 626px;
  height: 12px;
  position: absolute;
  object-fit: cover;
}

.android-medium .line-7 {
  top: 1276px;
  left: 152px;
  width: 623px;
  height: 1px;
  position: absolute;
  object-fit: cover;
}

.android-medium .line-8 {
  top: 1330px;
  left: 160px;
  width: 615px;
  height: 3px;
  position: absolute;
  object-fit: cover;
}

.android-medium .line-9 {
  top: 944px;
  left: 155px;
  width: 631px;
  height: 11px;
  position: absolute;
  object-fit: cover;
}


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
      <img class="screenshot" src="img/screenshot-2025-10-06-142808-1.png" />
      <img class="img" src="img/screenshot-2025-10-07-092220-1.png" />
      <div class="rectangle"></div>
      <div class="text-wrapper">REGISTER YOURSELF</div>
      <div class="div"></div>
      <p class="NAME-AGE-DOB-GENDER">
        NAME :<br />AGE : <br />DOB :<br />GENDER :<br />DEPARTMENT :<br />REGISTER NO :<br />EMAIL ID :<br />NAME OF
        THE EVENT :<br />YEAR :<br />PLACE :<br />DISTRICT :<br />AADHAR NO :
      </p>
    </div>
  </body>
</html>                                                                                                                                                                                                                                                           global.css

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
  background-color: #ffffff;
  width: 100%;
  min-width: 700px;
  min-height: 958px;
  position: relative;
}

.android-medium .screenshot {
  position: absolute;
  top: 0;
  left: 0;
  width: 700px;
  height: 958px;
  background-blend-mode: hard-light;
  aspect-ratio: 0.87;
  object-fit: cover;
}

.android-medium .img {
  position: absolute;
  top: 156px;
  left: 157px;
  width: 409px;
  height: 733px;
  aspect-ratio: 0.56;
  object-fit: cover;
}

.android-medium .rectangle {
  position: absolute;
  top: 52px;
  left: 170px;
  width: 373px;
  height: 104px;
  background-color: #ada6f5;
}

.android-medium .text-wrapper {
  position: absolute;
  top: 84px;
  left: 190px;
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .div {
  position: absolute;
  top: 207px;
  left: 152px;
  width: 410px;
  height: 631px;
  border-radius: 11px;
  background-blend-mode: soft-light;
  background: linear-gradient(
    270deg,
    rgba(217, 217, 217, 1) 0%,
    rgba(115, 115, 115, 1) 100%
  );
}

.android-medium .NAME-AGE-DOB-GENDER {
  position: absolute;
  top: 312px;
  left: 166px;
  width: 396px;
  text-shadow: 0px 4px 4px #ed131340;
  font-family: "Inter-LightItalic", Helvetica;
  font-weight: 300;
  font-style: italic;
  color: #000000;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
}

```

## OUTPUT:

![alt text](<Screenshot 2025-10-07 111456-1.png>)

![alt text](<Screenshot 2025-10-07 111547.png>)

![alt text](<Screenshot 2025-10-07 111631.png>)


## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
