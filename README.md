# EX01 Developing a Simple Webserver
## Date:29.03.2024

## AIM:
To develop a simple webserver to serve html pages.

## DESIGN STEPS:
### Step 1: 
HTML content creation.

### Step 2:
Design of webserver workflow.

### Step 3:
Implementation using Python code.

### Step 4:
Serving the HTML pages.

### Step 5:
Testing the webserver.

## PROGRAM:
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Saveetha Engineering College</title>
   <style>
     a{
        padding: 15px 20px 30px 40px;
        text-decoration: none;
        color: red;
    }
   </style>
</head>
<body>
     
<div class="row">

<div class="col-5">

<a href=""><i class="bi bi-twitter"></i></a>

<a href=""><i class="bi bi-youtube"></i></a> 

<a href=""><i class="bi bi-facebook"></i></a>

<a href=""><i class="bi bi-linkedin"></i></a>

<a href=""><i class="bi bi-pinterest"></i></a>

<a href=""><i class="bi bi-whatsapp"></i></a>

<a href=""><i class="bi bi-instagram"></i></a>

</div>
    
    <div style="display:flex">
        <div style="width: 30%;">
            <img src="logo.jpeg" style="width: 100%;" alt=""/>
        </div>
        <div style="width: 50%; padding-top: 15px; ">
            <a href="">Home</a>
            <a href="">About</a>
            <a href="">Department</a>
            <a href="">Life at sec</a>
            <a href="">Admission</a>
            <a href="">Placement</a>
        </div>
        <div style="width: 20%; padding-top: 10px;">
            <input
                 type="text"
                 style="
                    width: 80%;
                    border-radius: 15px;
                    background-image: url('book.png'),url('search.png');
                    background-size: contain;
                    background-repeat: no-repeat;
                    background-position: 1%,95%;
                    height: 30px; padding-left: 50px;"
            placeholder="Book search"
            />
        </div>
        
    </div>
 <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link
         href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
    
        </head>
<body>
    <div id="carouselExampleIndicators" class="carousel slide">
        <div class="carousel-indicators">
          <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
          <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="1" aria-label="Slide 2"></button>
          <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="2" aria-label="Slide 3"></button>
        </div>
        <div class="carousel-inner">
          <div class="carousel-item active">
            <img src="1.jpeg" class="d-block w-100" alt="...">
          </div>
          <div class="carousel-item">
            <img src="2.jpeg" class="d-block w-100" alt="...">
          </div>
          <div class="carousel-item">
            <img src="3.jpeg" class="d-block w-100" alt="...">
          </div>
         
        </div>
        <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="prev">
          <span class="carousel-control-prev-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Previous</span>
        </button>
        <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="next">
          <span class="carousel-control-next-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Next</span>
        </button>
      </div>
      <script
            src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" crossorigin="anonymous"></script>

</body>
</html>

## OUTPUT:
![alt text](<../output 1.png>)
![alt text](<../output 2.png>)
![alt text](<../output 3.png>)



## RESULT:
The program for implementing simple webserver is executed successfully.
