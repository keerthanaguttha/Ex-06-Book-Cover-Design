# Ex-06-Book-Cover-Design

NAME : GUTTHA KEERTHANA

REFERENCE NUMBER : 23012783

DEPARTMENT : AIML

# AIM:
To create a book cover design using Html and Css code's

# Step1:
Select an image from online and make it as background image

# Step2:
Using vs code create a html and css files

# Step3:
Try some designs and some font over the image

# Step4:
Give the author name and photo down below the book cover

# Step5:
Run the Html Program to see the results

# PROGRAM :
book.css :
```
body {
  background-image: url("kp.jpeg.jpg");
  background-position : center;
  background-size: cover;
  background-repeat: no-repeat;
  margin-left: 100px;
  color:  white;
}

.edit {
  position: sticky;
  left: 0;
  font-size: 50px;
  color: orange;

  
  
    }

h1 {
  color: white;
  font-size: 50px;
}
p {
   
   font-size: 100px;
}

.direct {
  font-size: 50px;
}
img {
  bottom: 200px;
  margin-bottom: 100px;
  margin-right: 100px;
  float: right;
}
.create {
  position: fixed;
  right: 0;
  margin-bottom: 20px;
  margin-right: 100px;
  bottom: 100px; 
  color: white; 
}
```
book.html:
```
.name {
position: fixed;
left: 0;
margin-bottom: 150px;
margin-left: 100px;
bottom: 10px; 
color: white; 
font-size: 50px;

}

<!DOCTYPE html>
<html>
<head>
  <link rel="stylesheet" href="book.css">
</head>
<body>
   

<h1>Expert insight</h1>
<hr>
<p align="center"><b>Responsive Web Design with HTML5 and CSS</b></p>
<div class="direct">
  Develop future-proof responsive websites using latest html and css techniques
</div>


<div class="edit">
  Third Edition
  <img src= "author.jpg">
  <hr>
  
</div>
<div class="name">
  
  Ben Frain
</div>


</body>
</html>
```
# OUTPUT :
![image](https://github.com/keerthanaguttha/Ex-06-Book-Cover-Design/assets/145742927/f6c0a37e-fd1e-4f75-b778-27c367ea6292)


# RESULT :
The book cover design has been successfully created using HTML and CSS.
