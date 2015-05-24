<html>
<head>
	<title>My Bootstrap Exercise</title>
</head>
<body>
	<!-- Nav Bar -->
	<nav class="navbar navbar-default">
	  <div class="container-fluid">
	    <!-- Brand and toggle get grouped for better mobile display -->
	    <div class="navbar-header">
	      <a class="navbar-brand" href="#">
	      	<img src="http://logonoid.com/images/bootstrap-logo.png" width="35px">
	      </a>
	    </div>

	    <!-- navbar -->
	    <div class="collapse navbar-collapse" id="bs-example-navbar-collapse-1">
	      <ul class="nav navbar-nav">
	      	<li class="active nav1"><a href="#">Home</a></li>
	      	<li><a class="nav1" href="#myCarousel">Carousel</a></li>
	      	<li><a class="nav1" href="#signup">Sign up</a></li>
	      </ul>
	        </li>
	      </ul>
	    </div><!-- /.navbar-collapse -->
	  </div><!-- /.container-fluid -->
	</nav>
	<!-- carousel -->
	<div class="carouselPage col-lg-12 col-md-12 col-sm-8">
	    <div id="myCarousel" class="carousel slide" data-interval="5000" data-ride="carousel">
	    	<!-- Carousel indicators -->
	        <ol class="carousel-indicators">
	            <li data-target="#myCarousel" data-slide-to="0" class="active"></li>
	            <li data-target="#myCarousel" data-slide-to="1"></li>
	            <li data-target="#myCarousel" data-slide-to="2"></li>
	        </ol>   
	       <!-- Carousel items -->
	        <div class="carousel-inner">
	            <div class="item">
	                <h2>Welcome to my Bootstrap!</h2>
	                <div class="carousel-caption">
	                  <h3>Hello World.</h3>
	                  <p>My first Bootstrap.</p>
	                </div>
	            </div>
	            <div class="item slide2">
	                <h2>Change of Color!</h2>
	                <div class="carousel-caption">
	                  <h3>rainbow colors</h3>
	                </div>
	            </div>
	            <div class="active item slide3">
	                <h2 style="color:black;">Sign up now!</h2>
	                <div class="carousel-caption">
	                  <h3>What you waiting for?</h3>
	                  <a class="button" href="#signup">Sign up!</a>
	                </div>
	            </div>
	        </div>
	        <!-- Carousel nav -->
	        <a class="carousel-control left" href="#myCarousel" data-slide="prev">
	            <span class="glyphicon glyphicon-chevron-left"></span>
	        </a>
	        <a class="carousel-control right" href="#myCarousel" data-slide="next">
	            <span class="glyphicon glyphicon-chevron-right"></span>
	        </a>
	    </div>
	</div>

	<!-- Sign up Form -->
	<div id= "signup" class="well col-lg-4 col-lg-offset-4
	col-md-4 col-md-offset-4 col-sm-3" >
			<center><h1>Sign Up Form</h1></center>
			<form>
		  <div class="form-group">
		    <label for="exampleInputEmail1">Email address</label>
		    <input type="email" class="form-control" id="exampleInputEmail1" placeholder="Enter email">
		  </div>
		  <div class="form-group">
		    <label for="exampleInputPassword1">Password</label>
		    <input type="password" class="form-control" id="exampleInputPassword1" placeholder="Password">
		  </div>

		  <div class="checkbox">
		    <label>
		      <input type="checkbox"> Remember Me
		    </label>
		  </div>
		  <button type="submit" class="btn btn-success">Submit<span class="glyphicon glyphicon-hand-up" aria-hidden="true"></button>
		</form>
	</div>
</body>
<!-- Latest compiled and minified CSS -->
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.4/css/bootstrap.min.css">
<!-- Optional theme -->
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.4/css/bootstrap-theme.min.css">
<!-- jquery -->
<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.2/jquery.min.js"></script>
<!-- Latest compiled and minified JavaScript -->
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.4/js/bootstrap.min.js"></script>
<!-- stylesheet -->
<style type="text/css">

h2{
    margin: 0;     
    color: #666;
    padding-top: 90px;
    font-size: 52px;
    font-family: "trebuchet ms", sans-serif;    
}
.item{
    background: #333;    
    text-align: center;
    height: 300px !important;
}
.carousel{
    margin-top: 20px;
}
.carouselPage{
	margin: 20px;
}
.slide2 {
    background: linear-gradient(to right,
     #e61f44,#e65d1f,#fdf200,#71ee6d,#3d93da,#4b0082,#551a8b);
}
.slide3 {
    background: url(http://img.xcitefun.net/users/2015/01/371699,xcitefun-sleepy-puppy-pics-pups-dog-pictures-pics.jpg) 0px -120px;
    background-size: cover;
}
.nav1{
    border-radius: 5px;
    border: 2px solid;
}

.button{
    border-radius: 5px;
    border: 2px solid #6495ED;
    background-color: #BCD2EE;
    height: 50px;
    width: 120px;
    margin: auto;
    text-align: center; 
    text-decoration: none;
    color: #3D59AB;  
}
</style>
</html>
