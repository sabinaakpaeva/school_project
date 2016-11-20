# school_project
<!DOCTYPE html>
<html lang="en">
	<head>
		<meta charset="utf-8">
		<title>Ninety one</title>
		<link href="css/jquery.bxslider.css" rel="stylesheet" />
		<link href="style.css" rel="stylesheet">
		<link href="css/font-awesome.min.css" rel="stylesheet"/>
		<link rel="shortcut icon" type="image/jpg" href="http://cs630423.vk.me/v630423574/ee2/ZJ47ioszrsg.jpg"/> 
		<link href="assets/css/bootstrapTheme.css" rel="stylesheet">
    <link href="assets/css/custom.css" rel="stylesheet">
<link href="owl-carousel/owl.carousel.css" rel="stylesheet">
<link href="owl-carousel/owl.theme.css" rel="stylesheet">
	</head>

<body style="background-color:#F0FFFF ">
<div class="nav-wrap">
		<nav class="navigation">
		<div class="nav" nav-menu-style="ninetyone">
			<ul class="nav-menu">
			<li class="active">
                <a href="https://www.instagram.com/91ninetyone.kz/"><img title="Go to official page" src="http://scontent.cdninstagram.com/t51.2885-19/s150x150/13188165_629787153844798_789303698_a.jpg" style="width: 50px; height: 50px"></a>
				<a href="index.html">Home</a></li>
				<li><a href="AZ.html">AZ</a></li>
				<li><a href="Bala.html">Bala</a></li>
				<li><a href="Zaq.html">ZaQ</a></li>
				<li><a href="Alem.html">Alem</a></li>
				<li><a href="Ace.html">Ace</a></li>
			</ul>
		</div>
		</nav>
	</div>
	</div>


	<div id="demo">
        <div class="container">
          <div class="row">
            <div class="span12">
              <div id="owl-demo" class="owl-carousel">
                <div class="item"><img src="91a.jpg" alt="91"></div>
                <div class="item"><img src="91f.jpg" alt="91"></div>                
                <div class="item"><img src="91main.jpg" alt="91"></div>
                 <div class="item"><img src="91.jpg" alt="91"></div>
                 <div class="item"><img src="91f2.jpg" alt="91"></div>
              </div>
            </div>
          </div>
        </div>
    </div>
    <script src="assets/js/jquery-1.9.1.min.js"></script>
    <script src="owl-carousel/owl.carousel.js"></script>
    <style>
    #owl-demo .item{
        margin: 10px;
    }
    #owl-demo .item img{
        display: block;
        width: 100%;
        height: auto;
    }
    </style>
    <script>
    $(document).ready(function() {
      $("#owl-demo").owlCarousel({
        autoPlay: 3000,
        items : 6,
        itemsDesktop : [5000,3],
        itemsDesktopSmall : [5000,3]
      });
    });
    </script>
	
	<h2 style="color: #800000" >List of soundtracks</h2>
	<p style="color: #800000 "> 1."Қайтадан"</p>
	<audio id="player" src="sound.mp3"></audio>
<div>
<button onclick="document.getElementById('player').play()">play</button>
<button onclick="document.getElementById('player').pause()">pause</button>
<button onclick="document.getElementById('player').volume+=0.1">louder</button>
<button onclick="document.getElementById('player').volume-=0.1">quieter</button> </div>

<p style="color:  #800000">2."Қалай қарайсың"</p>
	<audio id="player" src="sound2.mp3"></audio>
<div>
<button onclick="document.getElementById('player').play()">play</button>
<button onclick="document.getElementById('player').pause()">pause</button>
<button onclick="document.getElementById('player').volume+=0.1">louder</button>
<button onclick="document.getElementById('player').volume-=0.1">quieter</button> </div>

<p style="color:  #800000">3."Айыптама"</p>
	<audio id="player" src="sound3.mp3"></audio>
<div>
<button onclick="document.getElementById('player').play()">play</button>
<button onclick="document.getElementById('player').pause()">pause</button>
<button onclick="document.getElementById('player').volume+=0.1">louder</button>
<button onclick="document.getElementById('player').volume-=0.1">quieter</button> </div>

<video width="640" height="360" controls>
<source src="video.mp4" type="video/mp4" />
<source src="__VIDEO__.OGV" type="video/ogg" />
<object width="640" height="360" type="application/x-shockwave-flash" data="__FLASH__.SWF">
<param name="movie" value="__FLASH__.SWF" />
<param name="flashvars" value="controlbar=over&amp;image=__POSTER__.JPG&amp;file=__VIDEO__.MP4" />

</object>
</video>



<div id="footer">
<p> Copyright 2016 <a href="http://www.sabina.com/html15"></a> Ninetyone All right reserved.</p>
</div>

	</body>
</html>
