<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Level 1 assessment</title>
  <link rel="stylesheet" href="style.css">
  <!-- Bootstrap CSS -->
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
  <!-- FontAwesome for icons -->
  <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css" rel="stylesheet">

</head>
<body>
<!-- nav bar -->
<nav class="navbar navbar-expand-lg navbar-light bg-white">
  <a class="navbar-brand" href="#"><img src="./images/logo.png" width="100px" height="100px"></a>

  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav"
      aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
  </button>


  <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav px-5">
          <!-- Dropdown Menu -->
          <li class="nav-item dropdown">
              <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown"
                  aria-haspopup="true" aria-expanded="false">
                  HOME
              </a>
              <div class="dropdown-menu" aria-labelledby="navbarDropdown">
                  <a class="dropdown-item" href="#">About</a>
              </div>
          </li>
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown"
                aria-haspopup="true" aria-expanded="false">
                SHOP
            </a>
            <div class="dropdown-menu" aria-labelledby="navbarDropdown">
                <a class="dropdown-item" href="#">About</a>
            </div>
        </li>
        <li class="nav-item dropdown">
          <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown"
              aria-haspopup="true" aria-expanded="false">
              BLOG
          </a>
          <div class="dropdown-menu" aria-labelledby="navbarDropdown">
              <a class="dropdown-item" href="#">About</a>
          </div>
      </li>
      <li class="nav-item dropdown">
        <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown"
            aria-haspopup="true" aria-expanded="false">
            ABOUT
        </a>
        <div class="dropdown-menu" aria-labelledby="navbarDropdown">
            <a class="dropdown-item" href="#">About</a>
        </div>
    </li>
    <li class="nav-item dropdown">
      <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown"
          aria-haspopup="true" aria-expanded="false">
          CONTACT
      </a>
      <div class="dropdown-menu" aria-labelledby="navbarDropdown">
          <a class="dropdown-item" href="#">About</a>
      </div>
  </li>
      </ul>

      

      <!-- Navbar Icons (Search, Like, Cart) -->
      <div class="navbar-icons px-5">
        <input type="search" class="border-1 rounded" placeholder="search">
        <a href="#" title="Account"><i class="fas fa-user px-3"></i></a>
          <a href="#" title="Like"><i class="fas fa-heart px-3"></i></a>
          <a href="#" title="Cart"><i class="fas fa-shopping-cart"></i></a>
      </div>
  </div>
</nav>


  
  <!-- carousel -->
<section class="bg-light">
  <div id="carouselExample" class="carouselslide" data-ride="carousel">
    <div class="carousel-inner">
        <!-- Carousel Item 1 -->
        <div class="carousel-item active">
          <div class="row w-100">
          <div class="carousel-content col-md-6">
            <h3 class="text-warning">Furniture Sofa</h3>
            <p>Interior Design in Home</p>
        </div>
            
                <div class="carousel-image col-md-6 mt-5 mb-5">
                    <img src="./images/whitesofa.jpg" class="d-block w-100 img1" alt="whitesofa">
                </div>
                
            </div>
        </div>

        <!-- Carousel Item 2 -->
        <div class="carousel-item ">
            <div class="row w-100">
              <div class="carousel-content col-md-6 ">
                <h3 class="text-warning">Furniture Sofa</h3>
                <p>Interior Design in Home</p>
            </div>
                <div class="carousel-image col-md-6 mt-5 mb-5">
                    <img src="./images/sofa.jpg" class="d-block w-100 img1" alt="sofa">
                </div>
                
            </div>
        </div>

        <!-- Carousel Item 3 -->
        <div class="carousel-item">
            <div class="row w-100">
              <div class="carousel-content col-md-6  ">
                <h3 class="text-warning">Furniture Sofa</h3>
                <p>Interior Design in Home</p>
            </div>
                <div class="carousel-image col-md-6 mt-5 mb-5">
                    <img src="./images/blacksofa.jpg" class="d-block w-100 img1" alt="blacksofa">
                </div>
               
            </div>
        </div>
    </div>

    <!-- Carousel Controls -->
    <a class="carousel-control-prev" href="#carouselExample" role="button" data-slide="prev">
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="sr-only">Previous</span>
    </a>
    <a class="carousel-control-next" href="#carouselExample" role="button" data-slide="next">
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="sr-only">Next</span>
    </a>
</div>
</section>

<!-- TOP PRODUCTS -->
  <div class="container mt-5 text-center topproduct">
    <h3 class="topproduct">TOP PRODUCTS</h3> 
    <h6>Lorem ipsum dolor sit amet consectetur adipisicing elit.</h6>
  </div>
  <div class="product container mt-5">
    <div class="row">
      <div class="col-lg-4 col-md-4 col-sm-12 col-12 mb-4">
        <div class="card border-0 bg-light">
            <img class="mx-auto my-3" src="./images/Service 1.png" style="width: 70px;height: 70px;object-fit: cover;">
            <h5 class="card-title text-center">Flower Vase Vases</h5>
          <p class="card-text mt-3 text-center mb-5"><del>$105.00</del>  $80.00</p>
        </div>
    </div>
    <div class="col-lg-4 col-md-4 col-sm-12 col-12 mb-4">
      <div class="card border-0 bg-light">
          <img class="mx-auto my-3" src="./images/Service 2.png" style="width: 70px;height: 70px;object-fit: cover;">
          <h5 class="card-title text-center">Flower Vase Vases</h5>
        <p class="card-text mt-3 text-center mb-5"><del>$105.00</del>  $80.00</p>
      </div>
  </div>

    <div class="col-lg-4 col-md-4 col-sm-12 col-12 mb-4">
      <div class="card border-0 bg-light">
          <img class="mx-auto my-3" src="./images/Service 3.png" style="width: 70px;height: 70px;object-fit: cover;">
          <h5 class="card-title text-center">Flower Vase Vases</h5>
        <p class="card-text mt-3 text-center mb-5"><del>$105.00</del>  $80.00</p>
      </div>
  </div>
  <div class="row">
    <div class="col-lg-4 col-md-4 col-sm-12 col-12 mb-4">
      <div class="card border-0 bg-light">
          <img class="mx-auto my-3" src="./images/Service 1.png" style="width: 70px;height: 70px;object-fit: cover;">
          <h5 class="card-title text-center">Flower Vase Vases</h5>
        <p class="card-text mt-3 text-center mb-5"><del>$105.00</del>  $80.00</p>
      </div>
  </div>
  <div class="col-lg-4 col-md-4 col-sm-12 col-12 mb-4">
    <div class="card border-0 bg-light">
        <img class="mx-auto my-3" src="./images/Service 2.png" style="width: 70px;height: 70px;object-fit: cover;">
        <h5 class="card-title text-center">Flower Vase Vases</h5>
      <p class="card-text mt-3 text-center mb-5"><del>$105.00</del>  $80.00</p>
    </div>
</div>

  <div class="col-lg-4 col-md-4 col-sm-12 col-12 mb-4">
    <div class="card border-0 bg-light">
        <img class="mx-auto my-3" src="./images/Service 3.png" style="width: 70px;height: 70px;object-fit: cover;">
        <h5 class="card-title text-center">Flower Vase Vases</h5>
      <p class="card-text mt-3 text-center mb-5"><del>$105.00</del>  $80.00</p>
    </div>
</div>
 </div>
  
<button class="mx-auto bg-white mb-5">Load More</button>

<!-- special sale  -->
 <div class="container-fluid">
  <div class="row">
    <div class="col-sm-12 col-md-6 col-lg-6 col-xl-6 bg-light text-center sale ">
         <h3 class="mt-5">HOT DEALS THIS WEEK</h3>
         <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Libero nisi quae ea nequem.</p>
         <button class="bg-white rounded">SHOP NOW</button>
         <img class="mx-4 mb-4" src="./images/whitesofa.jpg" width="200" height="200">
    </div>
    <div class="col-sm-12 col-md-6 col-lg-6 col-xl-6 text-center sale1" style="background-color: rgb(174, 177, 177);">
      <h3 class="mt-5"><span class="bg-warning text-white">SPECIAL COLLECTION</span></h3>
      <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Libero nisi quae ea nequem.</p>
      <button class="bg-white border-0 rounded mb-2">SHOP NOW</button>
      <div>
      <img class="mx-4 mb-4" src="./images/blacksofa.jpg" width="200" height="200">
    </div>
 </div>
   </div>
  </div>
 <!-- our blog -->
 <div class="container mt-5 text-center ourblg1">
  <h3 class="ourblg">OUR BLOG</h3> 
  <h6>Lorem ipsum dolor sit amet consectetur adipisicing elit.</h6>
  <div class="row mx-5 px-5">
    <div class="col-12 col-md-6 col-lg-6 col-xl-6 ">
  <div class="card mt-5" style="width: 18rem;">
    <img class="card-img-top" src="./images/whitesofa.jpg" alt="Card image cap">
    <div class="card-body">
      <h5 class="card-title">Best Fashion Designers</h5>
      <p class="card-text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Placeat, debitis eaque maxime aut ducimus cupiditate omnis similique fuga perferendis.</p>
      <a href="#">Read More</a>
    </div>
  </div> 
  </div>
  <div class="col-12 col-md-6 col-lg-6 col-xl-6 px-5 ">
    <div class="card mt-5" style="width: 18rem;">
      <img class="card-img-top" src="./images/sofa.jpg" alt="Card image cap">
      <div class="card-body">
        <h5 class="card-title">Attached To The Design</h5>
        <p class="card-text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Placeat, debitis eaque maxime aut ducimus cupiditate omnis similique fuga perferendis.</p>
        <a href="#">Read More</a>
      </div>
    </div> 
    </div>
  </div>
</div>


  <!-- Bootstrap JS and dependencies -->
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.3/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>


  <!--PARTNERS-->
  <section class="partner">
    <div class="container-fluid bg-light mt-5 px-5">
      <div class="row">
        <div class="col">
           <img class="me-5 px-2" src="./images/_-22.png" width="140px" height="70px">
         </div>
        <div class="col">
          <img class="me-5 px-2" src="./images/_-23.png" width="140px" height="70px"> 
         </div>
           <div class="col">
             <img class="me-5 px-2" src="./images/_-24.png" width="140px" height="70px"> 
           </div>
           <div class="col">
              <img class="me-5 px-2" src="./images/_-25.png" width="140px" height="70px"> 
           </div>
           <div class="col px-2">
              <img src="./images/_-26.png" width="140px" height="70px">
           </div>
     </div>
   </div> 
 </section>

  <!--FOOTER-->
  <footer>
     <div class="container">
       <div class="row">
        <div class="col-lg-3 col-md-6 col-xl-3  col-6 col-sm-6  mt-5">
          <h6 class="ourservices2">GET IN TOUCH</h6> 
          <ul class="navbar-nav">
            <li class="nav-item"><a class="nav-link" href="#">143 castle road 517 district,Wyov Port Canada</a></li>
            <li class="nav-item"><a class="nav-link" href="#">Phone : +3 123456 789</a></li>
            <li class="nav-item"><a class="nav-link" href="#">Email : info@gmail.com</a></li>
            <li class="nav-item">OPENING : 8:00am - 7:30pm</li>
          </ul>
        </div>
         <div class="col-lg-3 col-md-6 col-xl-3  col-6 col-sm-6  mt-5">
           <h6 class="ourservices0">ELEMENT</h6> 
           <ul class="navbar-nav text-dark">
             <li class="nav-item"><a class="nav-link" href="#">Column</a></li>
             <li class="nav-item"><a class="nav-link" href="#">Accordion and toggle</a></li>
             <li class="nav-item"><a class="nav-link" href="#">Typography</a></li>
             <li class="nav-item"><a class="nav-link" href="#">Pie chart</a></li>
             <li class="nav-item"><a class="nav-link" href="#">Pricing table</a></li>
           </ul>
         </div>
         <div class="col-lg-3 col-md-6 col-xl-3  col-6 col-sm-6  mt-5">
           <h6 class="ourservices1">INFORMATION</h6> 
           <ul class="navbar-nav">
             <li class="nav-item"><a class="nav-link" href="#">My Account</a></li>
             <li class="nav-item"><a class="nav-link" href="#">About Us</a></li>
             <li class="nav-item"><a class="nav-link" href="#">Contact Us</a></li>
             <li class="nav-item"><a class="nav-link" href="#">Check Out</a></li>
             <li class="nav-item"><a class="nav-link" href="#">Wishlist</a></li>
           </ul>
         </div>
         
         <div class="col-lg-3 col-md-6 col-xl-3  col-6 col-sm-6 mt-5">
           <h6 class="ourservices4">NEWSLETTER</h6> 
           <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Officiis!</p>
           <div class="d-flex form-serach">
             <input type="search" class="text shadow-lg border-0 " placeholder="  Email Address">
             <button class="btn btn bg-warning border-0">Search</button>
          </div>
       </div>
     </div>
   </footer>
  
    <!-- Copyright -->
    <div class="mt-3 container-fluid  p-3 bg-light text-dark text-center">
      Copyright © 2020 Furniture shop. All rights reserved.
    </div>
    <!-- Copyright -->

   
</body>
</html>


CSS



/* carousel styles */

.carousel-item .carousel-content {
  padding: 50px;
  margin-top:50px;
}

.carousel-item .carousel-content h3 {
  font-size: 40px;
  padding-top: 60px;
  padding-left: 40px;
 /* align-items: center; */
}

.carousel-item .carousel-content p {
  font-size: 2rem;
 font-weight: bold;
 padding-left: 40px;
}

/* Set equal height for carousel items to align both the image and content */
.carousel-item {
  display: flex;
  /* justify-content: center;
  align-items: center; */
 
}

.carousel-item .carousel-image, .carousel-item .carousel-content {
  width: 50%;
}

/* product */
.product .card {
  transition: transform 0.3s ease;
}

.product .card:hover {
  transform: translateY(-10px); /* Adjust as needed */
  box-shadow: 0px 5px 15px rgb(99, 98, 98); /* Optional: Add shadow */
  border-radius:20px;
  box-shadow: large;
}
  .product h5:hover {
      color:rgb(255,193,7,1);
  }
/* partner */
.partner{
  transition: transform 0.3s ease;
}
  .partner:hover {
    transform: translateY(-5px); /* Adjust as needed */
    box-shadow: 0px 5px 15px rgb(99, 98, 98); /* Optional: Add shadow */
    border-radius:20px;
    box-shadow: large;
  }

  /* responsive */
@media (min-width:375px) and (max-width:768px){
  .sale{
    margin-bottom: 20px !important;
    margin-left: 30px;
  }
  .sale1{
    margin-bottom: 20px !important;
    margin-left: 30px;
  }
  .topproduct{
    margin-left: 100px;
  }
  .topproduct h6{
    margin-left: 100px;
  }
  .product{
    margin:30px !important;
  }
}
@media (min-width:537px) {
  .form-serach {       
      left: 20% !important;         
  }
}
@media (min-width:375px) and (max-width:485px) {
  .form-serach input{
      width:100%;
  }
  .form-serach button{
      margin-inline: -5px !important;
  }
  .form-serach img{
      width:10px;
      height:10px ;
  }
}
@media (min-width:991px) {
  .form-serach input{
      max-width:100%;
  }
  .form-serach button{
      margin-left: -15px !important;
  }
  .form-serach img{
      width:15px;
      height:15px ;
  }
}
