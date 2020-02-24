<!DOCTYPE html>
<html lang="en">
<head>
  <title></title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.4.1/css/bootstrap.min.css">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.4.1/jquery.min.js"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.16.0/umd/popper.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.4.1/js/bootstrap.min.js"></script>
</head>
<style>
    body{
    margin:0px;
    }
    .bg-image-home{
     background: linear-gradient(to bottom, #0f75bc 50%, #052942 100%);
     background-repeat: no-repeat;
     background-size:cover;
     height: 100vh;  
    }
    .first-image, .second-image{
    background-color: #ffffff;
    }
    img.row-img {
    width: 100%;
    border-radius: 10px;
    height: 100%;
    }
    .text-col {
    padding: 4%;
    }
    .first-container{
    margin-top: 14%;
    padding-right: 0px;
    padding-left: 0px;
    border-radius: 10px;
    }
    .second-container {
    padding-right: 0px;
    padding-left: 0px;
    border-radius: 10px;
    }
    .bg-image-home h1 {
    font-size: 35px;
    font-family: 'Open Sans', sans-serif;
    color: #2e384d;
    }
    .bg-image-home p {
    font-family: 'Open Sans', sans-serif;
    color: #b0bac9;
    font-size: 16px;
    }
    button.btn-primary {
    background-color: #0f75bc;
    padding: 10px 85px;
    color: #f7f7f2;
    margin-top: 2%;
    }
    .second-image h1 {
    text-align: right;
    }
    .second-image p {
    text-align: right;
    }
    .second-image button.btn-primary {
    float: right;
    }
    img.user-img {
    width: 40px;
    }
    li.nav-item.dropdown {
    margin-top: 10px;
    }
    img.logohome {
    margin-top: 6px;
    }

/*****MOBILE MEDIA QUERY*****/
    @media only screen and (max-width: 768px) {
    .first-container {
    margin-top: 24%;
    text-align: center;
    }
    .bg-image-home h1 {
    font-size: 24px;
    }
    .second-container {
    text-align: center !important;
    }
    .second-image h1 {
    text-align: center;
    }
    .second-image p {
    text-align: center;
    }
    .second-image button.btn-primary {
    float: none;
    }
    .bg-image-home {
    padding: 4%;
    }
    .bg-image-home {
    height: 100%;
    }
    .text-col {
    padding: 8%;
    }
}

/*****IPAD MEDIA QUERY*****/
    @media only screen 
and (min-device-width : 768px) 
and (max-device-width : 1024px)  { 
  .first-container {
    margin-top: 18%;
    text-align: center;
    }
    .bg-image-home {
    height: 100vh;
    }
    .second-container {
    text-align: center !important;
    }
    .second-image h1 {
    text-align: center;
    }
    .second-image p {
    text-align: center;
    }
    .second-image button.btn-primary {
    float: none;
    }
}
</style>

<body>
      <nav class="navbar navbar-expand-lg navbar-light bg-light shadow fixed-top">
        <button class="navbar-toggler navbar-toggler-right" type="button" data-toggle="collapse" data-target="#navbarTogglerDemo02" aria-controls="navbarTogglerDemo02" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <a class="navbar-brand" href="#!"><img src="assets/login-screen/Voice.ai-logo.png" alt="logo" ></a>
      
        <div class="collapse navbar-collapse custom-navbar" id="navbarTogglerDemo02">
          <ul class="navbar-nav ml-auto right-nav">
            <li class="nav-item">
              <a class="nav-link" href="#"><img src="assets/home-screen/Home.jpg" alt="logo-home" class="logohome"></a>
            </li>
            <li class="nav-item dropdown">
              <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                Johan deo
              </a>
              <div class="dropdown-menu" aria-labelledby="navbarDropdown">
                <a class="dropdown-item" href="#">Logout</a>
              </div>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#"><img src="assets/home-screen/user.png" alt="arrow" class="user-img"></a>
            </li>
          </ul>
        </div>
      </nav>



<section class="bg-image-home">
    
<div class="container ">
  <div class="row">
    <div class="col-md-12 first-container first-image">
        <div class="row">
            <div class="col-md-6 col-12 order-sm-1 order-2 text-col"><h1>CRM - Call Matedata Analysis</h1>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
            <button type="button" class="btn btn-primary">View Dashboard</button></div>
            <div class="col-md-6 col-sm-12 order-1"><img src="assets/home-screen/CRM-analysis-single.jpg" alt="crm-analysis" class="row-img"></div>
        </div>
      </div>
    </div>
  </div>


    
    <div class="container mt-4">
      <div class="row">
        <div class="col-md-12 second-container second-image">
            <div class="row">
                <div class="col-md-6 col-sm-12 col-12"><img src="assets/home-screen/call-ingestion-single.jpg" alt="conversional-analysis" class="row-img"></div>
                <div class="col-md-6 col-sm-12 col-12 text-col">
                  <h1>Conversational Analytics</h1>
              <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
                    <button type="button" class="btn btn-primary">View Dashboard</button></div>
            </div>
          </div>
        </div>
      </div>
    </section>


</body>
</html>
