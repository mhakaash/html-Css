# html-Css
It's a website using simple HTML &amp; CSS
<!DOCTYPE html>
<html>
<head>
	<meta name="viewport" content="width=device-width, initial-scale=1"  />
	<title>Website for business</title>
	<link rel="stylesheet" type="text/css" href="al.css">
	<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css">
	<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css">
	<script src="https://code.jquery.com/jquery-3.3.1.slim.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js"></script>
</head>
<body>
<!-- Navigation Bar -->
<section id="nav-bar"
<nav class="navbar navbar-expand-lg navbar-light bg-light">
	<a class="navbar-brand" href="#"><img src="https://i.imgur.com/7Ceqv1n.png" alt="Bird"></a>
	<button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
	  <span class="navbar-toggler-icon"></span>
	</button>
	<div class="collapse navbar-collapse" id="navbarNav">
	  <ul class="navbar-nav ml-auto">
		<li class="nav-item">
		  <a class="nav-link" href="#">HOME</a>
		</li>
		<li class="nav-item">
		  <a class="nav-link" href="#">ABOUT US</a>
		</li>
		<li class="nav-item">
		  <a class="nav-link" href="#">SERVICES</a>
		</li>
		<li class="nav-item">
		  <a class="nav-link" href="#">OUR TEAM</a>
		</li>
		<li class="nav-item">
			<a class="nav-link" href="#">PRICE </a>
		  </li>
		  <li class="nav-item">
			<a class="nav-link" href="#">VISION</a>
		  </li>
		  <li class="nav-item">
			<a class="nav-link" href="#">CONTACT </a>
		  </li>
	  </ul>
	</div>
  </nav>
</section>
<!-- Slider for the site -->
<div id="slider">
	<div id="headerSlider" class="carousel slide" data-ride="carousel">
		<ol class="carousel-indicators">
		  <li data-target="#headerSlider" data-slide-to="0" class="active"></li>
		  <li data-target="#headerSlider" data-slide-to="1"></li>
		  <li data-target="#headerSlider" data-slide-to="2"></li>
		</ol>
		<div class="carousel-inner">
		  <div class="carousel-item active">
			<img src="https://i.imgur.com/aDKGLwz.jpg" class="d-block img-fluid" alt="Research">
			<div class="carousel-caption"><h5>Research</h5></div>
		  </div>
		  <div class="carousel-item">
			<img src="https://i.imgur.com/1DxOSTE.jpg" class="d-block img-fluid" alt="Advising">
			<div class="carousel-caption"><h5>Advising</h5></div>
		  </div>
		  <div class="carousel-item">
			<img src="https://i.imgur.com/bJhNQ0f.jpg" class="d-block img-fluid" alt="Consulting">
			<div class="carousel-caption"><h5>Consulting</h5></div>
		  </div>
		</div>
		<a class="carousel-control-prev" href="#headerSlider" role="button" data-slide="prev">
		  <span class="carousel-control-prev-icon" aria-hidden="true"></span>
		  <span class="sr-only">Previous</span>
		</a>
		<a class="carousel-control-next" href="#headerSlider" role="button" data-slide="next">
		  <span class="carousel-control-next-icon" aria-hidden="true"></span>
		  <span class="sr-only">Next</span>
		</a>
	  </div>
	  </div>
	  <!-- About -->
	  <section id="about">
		  <div class="container">
			  <div class="container">
				  <div class="row">
					  <div class="col-md-6"><h2>About Us</h2><div class="about-content">"Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum."</div>
					<button type="button" class="btn btn-primary">Read More>></button>
					</div>
					  <div class="col-md-6 skills-bar">
						  <p>Research</p>
						  <div class="progress">
							  <div class="progress-bar" style="width: 80%">80%</div>
						  </div>
						  <p>Consulting</p>
						  <div class="progress">
							  <div class="progress-bar" style="width: 85%">85%</div>
						  </div>
						  <p>Advising</p>
						  <div class="progress">
							  <div class="progress-bar" style="width: 75%">75%</div>
						  </div>
					
					</div>
				  </div>
			  </div>
		  </div>
		</section>
		<section id="services">
			<div class="container">
				<h1>Our Services</h1>	
				<div class="row services">
						<div class="col-md-3 text-center">
								<div class="icon">
									<i class="fa fa-question-circle"></i>
								</div>
								<h3>Survey</h3>
								<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
							</div>
					<div class="col-md-3 text-center">
						<div class="icon">
							<i class="fa fa-flask"></i>
						</div>
						<h3>Research</h3>
						<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
					</div>
					<div class="col-md-3 text-center">
						<div class="icon">
							<i class="fa fa-bar-chart"></i>
						</div>
						<h3>Advising</h3>
						<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
					</div>
					<div class="col-md-3 text-center">
						<div class="icon">
							<i class="fa fa-thumbs-up"></i>
						</div>
						<h3>Consulting</h3>
						<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
					</div>
				</div>
			</div>
		</section>
	<script type="text/javascript" src="ml.js"></script>
</body>
</html>
