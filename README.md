<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <title>Ashish Kumar</title>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <link rel="shortcut icon" href="https://img.icons8.com/color/48/000000/hearts.png" type="image/x-icon" />

    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">
    <link rel='stylesheet' href='https://fonts.googleapis.com/css?family=Indie+Flower'>
    <link rel='stylesheet' href='https://maxcdn.bootstrapcdn.com/font-awesome/4.5.0/css/font-awesome.min.css'>
    <link href="https://fonts.googleapis.com/css?family=Quicksand:300,400,500,700" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css?family=Playfair+Display:400,400i,700" rel="stylesheet">
	
    <link rel="stylesheet" href="css/style.css">
    <link rel="stylesheet" href="css/animate.css">
    <link rel="stylesheet" href="css/flexslider.css">
    <link rel="stylesheet" href="css/services.css">
	<link rel="stylesheet" href="css/dark-mode-button.css">
	<link rel="stylesheet" href="css/dark-mode.css">
</head>

<body>

    <div class="header">
		<canvas></canvas><canvas></canvas>
		<div class="day-night-toggle-wrapper">
		  <label>
			<input type="checkbox" checked id="toggleDarkModeButton" onchange="toggleDarkMode()"/>
			<div class="switch">
			  <div class="circle">
				<div class="moon-spots"></div>
			  </div>
			  <div class="cloud">
				<div></div>
				<div></div>
			  </div>
			  <div class="stars">
				<div></div>
				<div></div>
			  </div>
			</div>
		  </label>
		</div>
        <div class="fixed-content">
            <img class="port" src="https://s3-us-west-2.amazonaws.com/s.cdpn.io/95581/cat.jpg">
            <h2>Ashish Kumar</h2>
            <p style="color:#fff;">Deep Learning | Open Source enthusiast</p>
            <div class="icon-row">
                <a href="https://github.com/Ashish760"><i class="fa fa-github"></i></a>
                <a href="www.linkedin.com/in/ashish-kumar-bba038195"><i class="fa fa-linkedin"></i></a>
               </i></a>
            </div>
        </div>
    </div>
    <div class="second">
		
        <div class="fixed-content">
			
            <h1>About Me</h1>
            <p>Wish me on July 27th,Photography is my passion.Want to become a Businessman.</p>
        </div>
    </div>

    <section class="colorlib-about" data-section="about">
        <div class="container">
			<div class="center">
				<script type="text/javascript">
					
					</script>
			</div>
        </div>
    </section>

    <br>
    <br>

    <section class="colorlib-skills" data-section="skills">
        <div class="colorlib-narrow-content">
            <div class="row">
                <div class="col-md-6 col-md-offset-3 col-md-pull-3 animate-box" data-animate-effect="fadeInLeft">
                    <h2>Skills</h2>
                    <hr>
                </div>
            </div>
			<div class="container">
				<p class="col animate-box" data-animate-effect="fadeInLeft"><b>Some of the significant aptitudes which will assist me with achieving your objectives.</b></p>
			</div>
           
            <div class="container">
                <div class="row">
				
                    <script type="text/javascript">
                        var skills = ["C++","Android", "MySQL", "GitHub/Git", "Photography"];
                        var value = [80, 85, 70, 40, 75];
                        for (let i = 0; i < skills.length; i++) {
                            var dir = (i % 2 == 0) ? "Right" : "Left";
                            document.write(
                                '<div class="col-md-6 animate-box" data-animate-effect="fadeIn' + dir + '">\
                                  <div class="progress-wrap">\
                                      <h3>' + skills[i] + '</h3>\
                                      <div class="progress">\
                                          <div class="progress-bar color-' + (i + 1) + '" role="progressbar" aria-valuenow="' + value[i] + '" aria-valuemin="0" aria-valuemax="100" style="width:' + value[i] + '%">\
                                              <span>' + value[i] + '%</span>\
                                          </div>\
                                      </div>\
                                  </div>\
                              </div>');
                        }
                    </script>
                </div>
            </div>
    </section>

    <br>
    <br>

    <section class="colorlib-experience" data-section="experience">
        <div class="colorlib-narrow-content">
            <div class="row">
                <div class="col-md-6 col-md-offset-3 col-md-pull-3 animate-box" data-animate-effect="fadeInLeft">
                    <h2>Work Experience</h2>
                    <hr>
                </div>
            </div>
            <div class="container">
                <div class="row">
                    <div class="col-md-12">
                        <div class="timeline-centered">
                            <script type="text/javascript">
                                var timeSpan = ["April 2008-March 2018", "June 2018 - Present"];
                                var AT = ["B.D.Academy", "Sree Ayyappa Public School"];
                                var internType = ["From Class UKG-10th", "Class 11th&12th"];
                                var descriptions = ["Started Study in class UKG and end after 10th board",
                                    "Studying in Class 11th&12th with commerce stream.",
                                 ];
                                var iclass = ["user", "code", "globe"];
                                var color = [5, 1, 2];
                                for (let i = 0; i < AT.length; i++) {
                                    var dir = (i % 2 == 0) ? "Right" : "Left";
                                    document.write(
                                        '<article class="timeline-entry animate-box" data-animate-effect="fadeIn' + dir + '">\
										<div class="timeline-entry-inner">\
											<div class="timeline-icon color-' + color[i] + '">\
												<i class="fa fa-' + iclass[i] + '"></i>\
											</div>\
											<div class="timeline-label">\
												<h2><a href="#">' + AT[i] + '</a> <span>' + timeSpan[i] + '</span></h2>\
												<p><strong><a href="#">' + internType[i] + '</a></strong>\
													<br> ' + descriptions[i] + '</p>\
												<p></p>\
											</div>\
										</div>\
									</article>');
                                }
                            </script>
                            <article class="timeline-entry begin animate-box" data-animate-effect="fadeInBottom">
                                <div class="timeline-entry-inner">
                                    <div class="timeline-icon color-3">
                                    </div>
                                </div>
                            </article>
                        </div>
                    </div>
                </div>
            </div>
            <div>
    </section>

    <section class="colorlib-project" data-section="project">
        <div class="colorlib-narrow-content">
            <div class="row">
                <div class="col-md-6 col-md-offset-3 col-md-pull-3 animate-box" data-animate-effect="fadeInLeft">
          var mulx10 = Array.from(Array(domains.length).keys());
                        for (let i = 0; i < domains.length; i++) {
                            var dir = (ids[i] % 2 == 0) ? "Right" : "Left";
                            document.write(
                                '<div class="col-md-12 animate-box" data-animate-effect="fadeIn' + dir + '">\
                              <a href="' + urls[i] + '" >\
                                <div class="services color-' + (mulx10[i] + 1) + '">\
                                  <span class="icon2"><i class="fa fa-' + icons[mulx10[i]] + '"></i></span>\
                                  <h3>' + domains[i] + '</h3>\
                                  <p>' + ppDomains[i] + '</p>\
                                </div>\
                              </a>\
                            </div>'
                            );
                        }
                    </script>
                </div>
            </div>
        </div>
    </section>
<div class="footer">
        <div class="second">
            <div class="fixed-content">
                <h1>Contact Me</h1>
            </div>
        </div>
        <div class="fixed-content">
            <div class="icon-row blue">
               
                <a href="https://www.facebook.com/ashishk3138""><i class="fa fa-facebook"></i></a>
                <a href="mailto:ashishk3138@gmail.com"><i class="fa fa-envelope"></i><a/a>
			
                <a href="https://join.skype.com/invite/VXybIHoBnfsT"><i class="fa fa-skype"></i></a>
            </div>
            <p></p>
            <i class="fa fa-chevron-up blue" style="color:#bbb;" onclick="window.scroll({  top: 0,  left: 0,  behavior: 'smooth'});"></i>
        </div>
    </div>

    <script src='https://cdnjs.cloudflare.com/ajax/libs/jquery/2.1.3/jquery.min.js'></script>
    <script src='https://maxcdn.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js'></script>
    <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js" integrity="sha384-UO2eT0CpHqdSJQ6hJty5KVphtPhzWj9WO1clHTMGa3JDZwrnQq4sF86dIHNDz0W1" crossorigin="anonymous"></script>
    <script src="js/jquery.easing.js"></script>
    <script src="js/jquery.waypoints.min.js"></script>
    <script src="js/jquery.flexslider-min.js"></script>
    <script src="js/owl.carousel.min.js"></script>
    <script src="js/jquery.countTo.js"></script>
    <script src="js/services.js"></script>
    <script src="js/modernizr.min.js"></script>
	<script src="js/hex.js"></script>
	<script src="js/dark.mode.toggle.js"></script>
    <script src="js/script.js"></script>

</body>

</html>
