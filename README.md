<html>
<head>
	<title>MrLich</title>
	<link href="main.css" rel="stylesheet">
	<meta property="og:title" content="MrLich">
	<link rel="shortcut icon" href="favicon.ico" type="image/x-icon">

  <script type="text/javascript" language="JavaScript">
	function ctitle() {
		  var title = document.title,
			  animSeq = ["/", "\\", "|"],
			  animIndex = 0,
			  titleIndex = 0;
		  function doInverseSpinZeroPitch() {
			  var loadTitle = title.substring(0, titleIndex);
			  if (titleIndex > title.length) {
				  animIndex = 0;
				  titleIndex = 0
			  }
			  if (animIndex > 2) {
				  titleIndex++;
				  animIndex = 0
			  }
			  document.title = loadTitle + animSeq[animIndex];
			  animIndex++
		  }
		  window.setInterval(doInverseSpinZeroPitch, 250);
	  };
  </script>
  <script src="https://kit.fontawesome.com/2d7741f44c.js" crossorigin="anonymous"></script>
  <link rel="stylesheet" href="font-awesome.min.css">
</head>
<body>
<video id="music" controls="" loop="" autoplay="" name="media" preload="auto" hidden>
	<source src="mf2.mp3" type="audio/mp3">
</video>
<video autoplay="1" loop="1"><source src="fon.mp4" type="video/mp4"/></video>  
	<div class="pageOverlay">
	<div class="bg-animation">
	<div id='stars'></div>
	<div id='stars2'></div>
	</div>
	<img border="0">
      <div id="main">
		<div class="lightbox">
			<div class="wrapper">
				<div class="titles animate">
				<h1>MrLich</h1>
					<div class="media animate">
						<a href="https://vk.com/l_l_l_mister_lich_l_l_l" target="_blank">
							<i class="fab fa-vk fa-lg"></i>
						</a>
						<a href="http://steamcommunity.com/id/grandproject/" target="_blank">
							<i class="fab fa-steam-symbol fa-lg"></i>
						</a>
						<a href="https://discord.gg/bgdNzhg" id="Discord">
							<i class="fab fa-discord fa-lg"></i>
						</a>
						<a href="https://github.com/GrandLich" id="Discord">
							<i class="fab fa-github fa-lg"></i>
						</a>
					</div>
				<hr>
				<div class="projects"><a target="_blank">• Just a Russian Java developer •</a></div>
				</div>
			</div>
		</div>
	</div>
</body>
<script>
  var audio = document.getElementById("music");
  audio.volume = 0.04;
</script>
</html>
