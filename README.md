# Ex.06 Book Front Cover Page Design
## Date:06-10-2025

## AIM:
To design a book front cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Create a Django Admin project.

### Step 2:
Create an app in the Django interface.

### Step 3:
Create a folder named 'static' in the app folder.

### Step 4:
Create a new HTML file in the static folder.

### Step 5:
Write the HTML code with relevant CSS properties.

### Step 6:
Choose the appropriate style and color scheme.

### Step 7:
Insert the images in their appropriate places.

### Step 8:
Publish the website in the LocalHost.

## PROGRAM:
~~~
book.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Book Cover</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="cover">
    <div class="inner-box">
      <h3 class="top">SEC Insights</h3>
      <h1 class="title">FUNDAMENTALS OF<br>WEB APPLICATION<br>DEVELOPMENT</h1>
      <p class="subtitle">Deep Dive in HTML, CSS & JS Basics<br>Top seller of 2025</p>

      <div class="bottom">
        <p class="special">SPECIAL EDITION</p>
        <div class="line"></div>
        <div class="bottom-row">
          <p class="author">T.NITHYAA SHREE</p>
          <img class="photo">
          <p class="sec">SEC</p>
        </div>
      </div>
    </div>
  </div>
</body>
</html>

style.css

body {
  margin: 0;
  padding: 0;
  height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  background: #ddd;
}

.cover {
  width: 500px;
  height: 700px;
  background: url("back.jpg");
  border: 8px solid rgb(5, 5, 5); /* outer red border */
  box-sizing: border-box;
  position: relative;
  padding: 10px;
}
 
.inner-box {
  width: 100%;
  height: 100%;
  border: 3px solid rgb(5, 5, 5); /* inner thin red line */
  box-sizing: border-box;
  padding: 30px;
  position: relative;
}

.top {
  color: rgb(24, 23, 23);
  font-weight: bold;
  border-bottom: 2px solid rgb(8, 8, 8);
  display: inline-block;
  padding-bottom: 3px;
  margin-top: 10px;
}

.title {
  color: rgb(202, 110, 25);
  font-weight: bold;
  text-align: center;
  margin-top: 100px;
  line-height: 1.3;
  font-size: 26px;
}

.subtitle {
  color: rgb(10, 10, 10);
  text-align: center;
  margin-bottom: 100px;
}

.bottom {
  position: absolute;
  bottom: 40px;
  left: 30px;
  right: 30px;
}

.special {
  color: rgb(15, 15, 14);
  font-weight: bold;
  margin-bottom: 5px;
}

.line {
  width: 100%;
  height: 2px;
  background-color: rgb(22, 21, 21);
  margin-bottom: 10px;
}

.bottom-row {
  display: flex;
  align-items: center;
  justify-content: space-between;
}

.author {
  color: rgb(14, 13, 13);
  font-weight: bold;
}

.photo {
  width: 80px;
  height: 100px;
  border: 2px solid rgb(14, 13, 13);
  background:url("Myphoto.jpg") no-repeat center/cover;
  position: absolute;
  right:0px;
  bottom: 70px;
}

.sec {
  color: rgb(4, 4, 4);
  font-weight: bold;
  bottom: 200px;
  right: 0px;
}

~~~


## OUTPUT:
![alt text](<Screenshot (40).png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
