<!DOCTYPE html>
<html lang="en">
<head>
 
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p" crossorigin="anonymous"></script>
</head>
<body>
  <nav  class="navbar navbar-expand-lg navbar-light bg-light">
    <a style="color: rgb(65, 7, 223);" class="navbar-brand" href="#">WEB DEVLOPMENT</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
  
    <div style="margin-left:30rem" class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav mr-auto">
        <li class="nav-item active">
          <a class="nav-link" href="#">Home <span class="sr-only"></span></a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#about">About us</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#contract">Contract  us</a>
        </li>
        
          <div class="dropdown-menu" aria-labelledby="navbarDropdown">
            <a class="dropdown-item" href="#">Action</a>
            <a class="dropdown-item" href="#">Another action</a>
            <div class="dropdown-divider"></div>
            <a class="dropdown-item" href="#">Something else here</a>
          </div>
        </li>
        <li class="nav-item">
          <a class="nav-link disabled" href="#our">Our Services</a>
        </li>
      </ul>
      <form class="navbar-nav mr-auto">
        <input class="form-control mr-sm-2" type="search" placeholder="Search" aria-label="Search">
        <button  class="btn btn-outline-success my-2 my-sm-0" type="submit">Search</button>
      </form>
    </div>
  </nav>
  
    <div id="carouselExampleCaptions" class="carousel slide" data-bs-ride="carousel">
        <div class="carousel-indicators">
          <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
          <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="1" aria-label="Slide 2"></button>
          <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="2" aria-label="Slide 3"></button>
        </div>
        <div class="carousel-inner">
          <div class="carousel-item active">
            <img src="file:///C:/Users/Public/Pictures/Sample%20Pictures/Penguins.jpg" width="400px" height="400px" class="d-block w-100 " alt="...">
            <div class="carousel-caption d-none d-md-block">
              <h5>First slide label</h5>
              <p>Some representative placeholder content for the first slide.</p>
            </div>
          </div>
          <div class="carousel-item">
            <img src="file:///C:/Users/Public/Pictures/Sample%20Pictures/Jellyfish.jpg" width="400px" height="400px" class="d-block w-100" alt="...">
            <div class="carousel-caption d-none d-md-block">
              <h5>Second slide label</h5>
              <p>Some representative placeholder content for the second slide.</p>
            </div>
          </div>
          <div class="carousel-item">
            <img src="file:///C:/Users/Public/Pictures/Sample%20Pictures/Lighthouse.jpg" width="400px" height="400px" class="d-block w-100" alt="...">
            <div class="carousel-caption d-none d-md-block">
              <h5>Third slide label</h5>
              <p>Some representative placeholder content for the third slide.</p>
            </div>
          </div>
        </div>
        <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="prev">
          <span class="carousel-control-prev-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Previous</span>
        </button>
        <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="next">
          <span class="carousel-control-next-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Next</span>
        </button>
      </div>
      <div class="text-center to the parent div to align text or any item inside to the center">
        <div id="about"><h1>ABOUT US</h1></div>
        <div class="container">
            <div class="row">
              <div  class="col">
                <img src="file:///C:/Users/Public/Pictures/Sample%20Pictures/Penguins.jpg"
                class="img-responsive" alt="Responsive image"
                width="500px" height="300px"/>
              </div>
              <div class="col">
              <h4 style="font-style: italic;">Penguins are flightless seabirds that live almost exclusively below the equator. Some island-dwellers can be found in warmer climates, but most???including emperor, ad??lie, chinstrap, and gentoo penguins???reside in and around icy Antarctica. They live almost exclusively in the southern hemisphere: only one species, the Gal??pagos penguin, is found north of the Equator. Highly adapted for life in the wate.</h4>
              </div>
              <div class="text-center to the parent div to align text or any item inside to the center">
                <div id="our"><h1  style="margin-top: 50px;" >OUR SERVICES</h1></div>
              
           <div style="margin-top: 70px;" class="container">
                <div class="row align-items-start">
                  <div class="col">
                    <div class="col-md-6 mb-4">
                <img style="border-radius: 50%; margin-left: 50px;" alt="image" height="200px" width="200px" src="file:///C:/Users/STUDENT/Downloads/index.jpg"
                          >
                    </div>
                      <h2 style="margin-right: 70px; " class="my-5 h2">Web Developer</h2>
                      <p style="margin-top:-50px;">Web development is the work involved in developing a website for the Internet or an intranet. Web development can range from developing a simple single static page of plain text to complex web applications, electronic businesses, and social network services.</p>
                  </div>
                  <div class="col">
                    <div class="col-md-6 mb-4">
                <img style="border-radius: 50%;" alt="image" height="200px" width="200px" src="file:///C:/Users/STUDENT/Downloads/an.png"
                          >
                    </div>
                      <h2 style="margin-right: 70px;" class="my-5 h2">Android Developer</h2>
                      <p style="margin-top: -50px; ">Web development is the work involved in developing a website for the Internet or an intranet. Web development can range from developing a simple single static page of plain text to complex web applications, electronic businesses, and social network services.</p>
                  </div>
                  <div class="col">
                    <div class="col-md-6 mb-4">
                <img style="border-radius: 50%;" alt="image" height="200px" width="200px" src="file:///C:/Users/STUDENT/Downloads/ios.jpg"
                          >
                    </div>
                      <h2 style="margin-right: 70px;" class="my-5 h2">ios Developer</h2>
                      <p style="margin-top: -50px; ">Web development is the work involved in developing a website for the Internet or an intranet. Web development can range from developing a simple single static page of plain text to complex web applications, electronic businesses, and social network services.</p>
                  </div>
                </div>
                <div style="margin-top: 50px;" class="text-center to the parent div to align text or any item inside to the center">
                   
                        <div class="container">
                            <div class="row align-items-start">
                              <div class="col">
                                LEARN ABOUT WEB DEVELOPMENT
                                <img src="file:///C:/Users/STUDENT/Downloads/index.jpg"
                class="img-responsive" alt="Responsive image"            
                width="300" height="300" />
                      <h5>A List Apart. A List Apart: as a web development blog, this one could really be considered as apart from the rest. They offer unique, original content and regularly post about everything to do with website design and development</h5>
                              </div>
                              <div class="col">
                                LEARN ABOUT YOUR SELF
                                <img src="file:///C:/Users/Public/Pictures/Sample%20Pictures/Koala.jpg"
                class="img-responsive" alt="Responsive image"             
                width="300" height="300" />
                <h5>
                    A List Apart. A List Apart: as a web development blog, this one could really be considered as apart from the rest. They offer unique, original content and regularly post about everything to do with website design and development
                </h5>
                              </div>
                              <div class="col">                    
                                LEARN ABOUT EARTH
                                <img src="file:///C:/Users/STUDENT/Downloads/earth.jpG"
                class="img-responsive" alt="Responsive image"             
                width="300" height="300" />
                <h5>A List Apart. A List Apart: as a web development blog, this one could really be considered as apart from the rest. They offer unique, original content and regularly post about everything to do with website design and development</h5>
                              </div>
                            </div>
                      </div>
                     
                    
<div class="container contact-form">
   </div>
    <form method="post">
        <h3 id="contract">Contract Us</h3>
       <div class="row">
            <div class="col-md-6">
                <div class="form-group">
                    <input type="text" name="txtName" class="form-control" placeholder="Your Name *" value="" />
                </div>
                <div class="form-group">
                    <input type="text" name="txtEmail" class="form-control" placeholder="Your Email *" value="" />
                </div>
                <div class="form-group">
                    <input type="text" name="txtPhone" class="form-control" placeholder="Your Phone Number *" value="" />
                </div>
                <div class="form-group">
                    <input type="submit" name="btnSubmit" class="btnContact" value="Send Message" />
                </div>
            </div>
            <div class="col-md-6">
                <div class="form-group">
                    <textarea name="txtMsg" class="form-control" placeholder="Your Message *" style="width: 100%; height: 150px;"></textarea>
                </div>
            </div>
        </div>
    </form>
</div>
</body>
<footer>
    
    <div  class="text-center p-3" style="background-color: rgba(0, 0, 0, 0.2);">
        ?? 2022 Copyright: web development
        
      </div>
     
    </footer>

</html>

