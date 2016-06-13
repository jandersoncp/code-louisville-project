<?php
	if (isset($_POST["submit"])) {
		$name = $_POST['name'];
		$email = $_POST['email'];
		$message = $_POST['message'];
		$from = 'Demo Contact Form'; 
		$to = 'example@domain.com'; 
		$subject = 'Message from Contact Demo ';
		
		$body ="From: $name\n E-Mail: $email\n Message:\n $message";
		// Check if name has been entered
		if (!$_POST['name']) {
			$errName = 'Please enter your name';
		}
		
		// Check if email has been entered and is valid
		if (!$_POST['email'] || !filter_var($_POST['email'], FILTER_VALIDATE_EMAIL)) {
			$errEmail = 'Please enter a valid email address';
		}
		
		//Check if message has been entered
		if (!$_POST['message']) {
			$errMessage = 'Please enter your message';
		}
// If there are no errors, send the email
if (!$errName && !$errEmail && !$errMessage && !$errHuman) {
	if (mail ($to, $subject, $body, $from)) {
		$result='<div class="alert alert-success">Thank You! I will be in touch</div>';
	} else {
		$result='<div class="alert alert-danger">Sorry there was an error sending your message. Please try again later.</div>';
	}
}
	}
?>

<!DOCTYPE html>
<html lang="en">
    <head>
        <!-- Meta Tags and title -->
        <meta charset="utf-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1">
        
        <title>Premier Chefs - Contact Us</title>
        <link rel='shortcut icon' href='../img/logos/favicon.ico' type='image/x-icon'/ >
        
        <!-- Fonts -->
        <link href='https://fonts.googleapis.com/css?family=Lato:400,300,700|Montserrat|Poiret+One' rel='stylesheet' type='text/css'>
         <link href='https://fonts.googleapis.com/css?family=Open+Sans:400,700,300' rel='stylesheet' type='text/css'>
        
        <!-- CSS (Bootstrap included)-->
        
        <link rel="stylesheet" href="css/normalize.css">
        <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/css/bootstrap.min.css" integrity="sha384-1q8mTJOASx8j1Au+a5WDVnPi2lkFfwwEAa8hDDdjZlpLegxhjVME1fgjWPGmkzs7" crossorigin="anonymous">
        <link rel="stylesheet" href="css/stylesheet.css"> 
        
    </head>
        
    <header>
         <nav>
            <!-- Header container box -->
            <a href="index.html"><img class="small-logo" src="../img/logos/PC_logo_small.png"></a>

            <section class="navbar navbar-inverse navbar-fixed-top" role="navigation"> 
                <section class="container"> 
                    <div class="navbar-header"> 
                        <button type="button" class="navbar-toggle" data-toggle="collapse" data-target=".navbar-collapse"> 
                            <span class="sr-only">Toggle navigation</span>
                            <span class="icon-bar"></span>
                            <span class="icon-bar"></span>
                            <span class="icon-bar"></span>
                        </button>
                    </div>
                     <div class="collapse navbar-collapse">
                        <ul class="nav navbar-nav right"> 
                            <li><a href="index.html">HOME</a></li>
                            <li><a href="about.html">OUR STORY</a></li>
                            <li><a href="services.html">SERVICES</a></li>
                            <li><a href="/menus/starters.html">MENUS</a></li>
                            <li><a href="contact.html" class="current">CONTACT</a></li>
                        </ul>
                    </div>
                    </section>
            </section>
        </nav>           
    </header>
    
    <body>
        <section class="wrapper">
            <h2 class="about-heading mobile-hide">CONTACT US</h2>
            <hr class="mobile-hide">
            
            <section class="contact-row row">
                
                <div class="contact col-sm-6 open mobile-hide">
                    <iframe src="http://widget.websta.me/in/thepremierchefs/?r=1&w=3&h=2&b=1&p=10" allowtransparency="true" frameborder="0" scrolling="no" style="border:none;overflow:hidden;width:510px; height: 340px" ></iframe> <!-- websta - websta.me -->
                </div>
                
                <div class="contact col-sm-6">
                    <h3 class="contact-head open">Questions for the Chefs?</h3>
                    <h4 class="open">Contact us!</h4>
                    <a href="https://www.facebook.com/The-Premier-Chefs-528440757337128/?fref=ts&ref=br_tf" target="_blank"><img class="contact-social" src="img/social-icons/Facebook.png"></a>
                    <a href="https://www.instagram.com/thepremierchefs/" target="_blank"><img class="contact-social" src="img/social-icons/instagram.png"></a>
                    <p class="contact-content"><a href="mailto:christie@thepremierplanners.com" class="open">Email: Christie@thepremierplanners.com</a></p>
                    <p class="contact-content open">Tel: <a href="tel:3525143001" class="open">(352) 514-3001</a></p>
                </div>
                
            </section>
            
            <section class="row">
                <div class="col-md-6 col-md-offset-3">
                    <form class="form-horizontal" role="form" method="post" action="index.php">
                        <div class="form-group">
                            <label for="name" class="col-sm-2 control-label">Name</label>
                            <div class="col-sm-10">
                                <input type="text" class="form-control" id="name" name="name" placeholder="First & Last Name" value="<?php echo htmlspecialchars($_POST['name']); ?>">
                                <?php echo "<p class='text-danger'>$errName</p>";?>
                            </div>
                        </div>
                        <div class="form-group">
                            <label for="email" class="col-sm-2 control-label">Email</label>
                            <div class="col-sm-10">
                                <input type="email" class="form-control" id="email" name="email" placeholder="example@domain.com" value="<?php echo htmlspecialchars($_POST['email']); ?>">
                                <?php echo "<p class='text-danger'>$errEmail</p>";?>
                            </div>
                        </div>
                        <div class="form-group">
                            <label for="message" class="col-sm-2 control-label">Message</label>
                            <div class="col-sm-10">
                                <textarea class="form-control" rows="4" name="message"><?php echo htmlspecialchars($_POST['message']);?></textarea>
                                <?php echo "<p class='text-danger'>$errMessage</p>";?>
                            </div>
                        </div>
                        <div class="form-group">
                            <div class="col-sm-10 col-sm-offset-2">
                                <input id="submit" name="submit" type="submit" value="Send" class="btn btn-primary">
                            </div>
                        </div>
                        <div class="form-group">
                            <div class="col-sm-10 col-sm-offset-2">
                                <?php echo $result; ?>	
                            </div>
                        </div>
                    </form> 
                </div>
            </section>
            
            <hr>
            
           
            <section class="blog-row row">
                <div class="col-sm-12 open">
                    <h2>Hungry for more? Check out our blog!</h2>
                    <p class="blog open">Chock full of delicious recipes, culinary tips and more.</p>
                    <a href="http://www.thepremierchefs.wordpress.com" target="_blank" class="open"><button class="blog-btn open">PREMIER BLOG</button></a>
                </div>
            </section>
            
            <section class="row">
                <div class="col-md-6 col-md-offset-3">
                    <?php include 'contact.php';?>
                </div>
            </section>
           
        
        </section>
        
        <!-- End wrapper -->  
         <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.0/jquery.min.js"></script>
        <script src="http://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/js/bootstrap.min.js"></script>
        
    </body>
    
    
    <footer class="social-copyright">
        <p class="copyright open">Copyright Premier Chefs, LLC. All rights reserved.</p>
        <a href="https://www.facebook.com/The-Premier-Chefs-528440757337128" target="_blank"><img class="social-icons" src="../img/social-icons/Facebook.png"></a>
        <a href="https://www.instagram.com/thepremierchefs/"><img class="social-icons" src="../img/social-icons/instagram.png" target="_blank"></a>
    </footer>
    
</html>