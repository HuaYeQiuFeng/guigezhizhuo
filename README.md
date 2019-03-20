<!DOCTYPE html>
<html lang="zh-CN">
	<head>
		<meta charset="utf-8" />
		<meta http-equiv="X-UA-Compatible" content="IE=edge">
		<meta name="viewport" content="width=device-width, initial-scale=1, maxium-scale=1,minimum-scale=1, user-scalable=no">
		<title>浏览器</title>
		<link rel="stylesheet" href="bootstrap-3.3.7-dist/css/bootstrap.min.css">
		<link rel="stylesheet" type="text/css" href="css/main.css">
		<script src="bootstrap-3.3.7-dist/js/jquery-1.11.1.min.js"></script>
		<script src="bootstrap-3.3.7-dist/js/bootstrap.min.js"></script>
	</head>
	<body>
		<nav class="navbar navbar-default navbar-fixed-top navbar-inverse" role="navigation">
			<div class="container">
				<div class="navbar-header">
					<button type="button" class="navbar-toggle collapsed" data-toggle="collapse" data-target="#demo-navbar">
						<span class="sr-only">Toggle navigation</span>
						<span class="icon-bar"></span>
						<span class="icon-bar"></span>
						<span class="icon-bar"></span>
					</button>
					<a class="navbar-brand" href="#">浏览器</a>
				</div>
				<div class="collapse navbar-collapse" id="demo-navbar">
					<ul class="nav navbar-nav">
						<li class="active"><a href="#">综述</a></li>
						<li><a href="#" data-toggle="modal" data-target="#state">简述</a></li>
						<li class="dropdown">
							<a href="#" class="dropdown-toggle" data-toggle="dropdown">特点<span class="caret"></span></a>
							<ul class="dropdown-menu" role="menu">
								<li><a href="#">Chrome</a></li>
								<li><a href="#">firfox</a></li>
								<li><a href="#">opera</a></li>
								<li class="divider"><a></a></li>
								<li><a href="#">safari</a></li>
								<li><a href="#">IE</a></li>
							</ul>
						</li>
						<li><a href="#" data-toggle="modal" data-target="#about">关于</a></li>
					</ul>
				</div>
			</div>
		</nav>
		<div id="carousel-example-generic" class="carousel slide" data-ride="carousel">
			<ol class="carousel-indicators">
				<li data-target="#carousel-example-generic" data-slide-to="0" class="active"></li>
					<li data-target="#carousel-example-generic" data-slide-to="1"></li>
					<li data-target="#carousel-example-generic" data-slide-to="2"></li>
					<li data-target="#carousel-example-generic" data-slide-to="3"></li>
					<li data-target="#carousel-example-generic" data-slide-to="4"></li>
			</ol>
			<div class="carousel-inner" role="listbox">
				<div class="item active">
					<img src="img/chrome-big.jpg" alt=""><div class="carousel-caption">
						<h1>Chrome</h1>
						<p>Google Chrome,又称谷歌浏览器，是由Google(谷歌)公司开发的一个浏览器。</p>
						<p><a class="btn btn-lg btn-primary" href="#" role="buttom" target="_blank">点我下载</a></p>
					</div>
				</div>
				<div class="item">
					<img src="img/firefox-big.jpg" alt=""><div class="carousel-caption">
						<h1>Firefox</h1>
						<p>Mozilla Firefox，中文名通常称为“火狐”或“火狐浏览器”，是一个开源网页浏览器。</p>
						<p><a class="btn btn-lg btn-primary" href="#" role="buttom" target="_blank">点我下载</a></p>
					</div>
				</div>
				<div class="item">
					<img src="img/ie-big.jpg" alt=""><div class="carousel-caption">
						<h1>Safari</h1>
						<p>Safari，是苹果计算机的最新操作系统Mac OS X中的浏览器。</p>
						<p><a class="btn btn-lg btn-primary" href="#" role="buttom" target="_blank">点我下载</a></p>
					</div>
				</div>
				<div class="item">
					<img src="img/opera-big.jpg" alt=""><div class="carousel-caption">
						<h1>Opera</h1>
						<p>Opera浏览器，是一款挪威Opera Software ASA公司制作的支持多页面标签式浏览的网络浏览器。</p>
						<p><a class="btn btn-lg btn-primary" href="#" role="buttom" target="_blank">点我下载</a></p>
					</div>
				</div>
				<div class="item">
					<img src="img/safari-big.jpg" alt=""><div class="carousel-caption">
						<h1>Internet Explorer</h1>
						<p>Internet Explorer，简称 IE，是微软公司推出的一款网页浏览器。</p>
						<p><a class="btn btn-lg btn-primary" href="#" role="buttom" target="_blank">点我下载</a></p>
					</div>
				</div>
			</div>
			<a class="left carousel-control" href="#carousel-example-generic" rol="button" data-slide="prev">
				<span class="glyphicon glyphicon-chevron-left"></span>
				<span class="sr-only">previous</span>
			</a>
			<a class="right carousel-control" href="#carousel-example-generic" rol="button" data-slide="prev">
				<span class="glyphicon glyphicon-chevron-right"></span>
				<span class="sr-only">next</span>
			</a>
		</div>
		<div class="container" id="summary-container">
			<div class="row">
				<div class="col-md-4">
					<img src="img/chrome-logo-small.jpg" />
					<h1>Chrome</h1>
						<p>Google Chrome,又称谷歌浏览器，是由Google(谷歌)公司开发的一个浏览器。</p>
						<p><a class="btn btn-default" href="#" role="buttom" target="_blank">点我下载</a></p>
				</div>
				<div class="col-md-4">
					<img src="img/firefox-logo-small.jpg" />
					<h1>Firefox</h1>
						<p>Mozilla Firefox，中文名通常称为“火狐”或“火狐浏览器”，是一个开源网页浏览器。</p>
						<p><a class="btn btn-default" href="#" role="buttom" target="_blank">点我下载</a></p>
				</div>
				<div class="col-md-4">
					<img src="img/safari-logo-small.jpg" />
					<h1>Safari</h1>
						<p>Safari，是苹果计算机的最新操作系统Mac OS X中的浏览器。</p>
						<p><a class="btn btn-default" href="#" role="buttom" target="_blank">点我下载</a></p>
				</div>
			</div>
			<hr class="divider"/>
		</div>
	<div class="container">	
		<ul class="nav nav-tabs" role="tablist" id="tab-list">
			<li class="active"><a href="#tab-chrome" role="tab" data-toggle="tab">Chrome</a></li>
			<li><a href="#tab-firefox" role="tab" data-toggle="tab">firefox</a></li>
			<li><a href="#tab-safari" role="tab" data-toggle="tab">safari</a></li>
			<li><a href="#tab-opera" role="tab" data-toggle="tab">opera</a></li>
			<li><a href="#tab-ie" role="tab" data-toggle="tab">IE</a></li>
		</ul>
		<div class="tab-content conr">
			
			<div class="tab-pane active" id="tab-chrome">
			 <div class="row feature">
				<div class="col-md-7">
				<h2 class="feature-heading">Google Chrome<span class="text-muted">使用最广的浏览器</span></h2>
				<p class="lead">Google Chrome,又称谷歌浏览器，是由Google(谷歌)公司开发的一个浏览器。</p>
				</div>
				<div class="col-md-5">
					<img class="feature-image img-responsive" src="img/chrome-logo.jpg">
				</div>
			 </div>	
			</div>
			
			<div class="tab-pane" id="tab-firefox">
			 <div class="row feature">v
				<div class="col-md-7">
				<img class="feature-image img-responsive" src="img/firefox-logo.jpg">
				</div>
				<div class="col-md-5">
					<h2 class="feature-heading">Mozilla Firefox<span class="text-muted">美丽的狐狸</span></h2>
				<p class="lead">Mozilla Firefox，中文名通常称为“火狐”或“火狐浏览器”，是一个开源网页浏览器， 使用Gecko引擎（非ie内核），支持多种操作系统如Windows、Mac和linux。</p>
				</div>
			 </div>
			</div>
			<div class="tab-pane" id="tab-safari">
			 <div class="row feature">
				<div class="col-md-7">
				<h2 class="feature-heading">Safari<span class="text-muted">Mac用户首选</span></h2>
				<p class="lead">Safari，是苹果计算机的最新操作系统Mac OS X中的浏览器，使用了KDE的KHTML作为浏览器的运算核心。 Safari在2003年1月7日首度发行测试版，并成为Mac OS X v10.3与之后的默认浏览器，也是iPhone与IPAD和iPod touch的指定浏览器。</p>
				</div>
				<div class="col-md-5">
					<img class="feature-image img-responsive" src="img/safari-logo.jpg">
				</div>
			 </div>
			</div>
			<div class="tab-pane" id="tab-opera">
			 <div class="row feature">
				<div class="col-md-7">
				<img class="feature-image img-responsive" src="img/chrome-logo.jpg">
				</div>
				<div class="col-md-5">
					<h2 class="feature-heading">Oper<span class="text-muted">小众但易用</span></h2>
				<p class="lead">Opera浏览器，是一款挪威Opera Software ASA公司制作的支持多页面标签式浏览的网络浏览器。 是跨平台浏览器可以在Windows、Mac和Linux三个操作系统平台上运行。.</p>
				</div>
			 </div>
			</div>
			<div class="tab-pane" id="tab-ie">
			 <div class="row feature">
				<div class="col-md-7">
				<h2 class="feature-heading">IE<span class="text-muted">你懂得</span></h2>
				<p class="lead">Internet Explorer，原称Microsoft Internet Explorer(6版本以前)和Windows Internet Explorer(7，8，9，10版本)， 简称IE，是美国微软公司推出的一款网页浏览器。它采用的排版引擎(俗称内核)为Trident。</p>
				</div>
				<div class="col-md-5">
					<img class="feature-image img-responsive" src="img/chrome-logo.jpg">
				</div>
			 </div>
			 </div>
			 <hr class="divider" />
			 <footer class="pull-right"><a href="#top">回到顶部</a></footer>
			 <p>@ 2019新年好</p>
		</div>
	</div>	
	<div class="modal fade" id="about">
		<div class="modal-dialog">
			<div class="modal-content">
				<div class="modal-header">
					<button type="button" class="close" data-dismiss="modal"><span aria-hidden="true">&times;</span><span class="sr-only">close</span></button>
					<h4 class="modal-title">注意事项</h4>
				</div>
				<div class="modal-body">该网站仅用于参考</div>
				<div class="modal-footer">
					<button type="button" class="btn btn-default" data-dismiss="modal">了解了</button>
			</div>
		</div>
	  </div>	
	</div>
	
	<div class="modal fade" id="state">
		<div class="modal-dialog">
			<div class="modal-content">
				<div class="modal-header">
					<button type="button" class="close" data-dismiss="modal"><span aria-hidden="true">&times;</span><span class="sr-only">close</span></button>
					<h4 class="modal-title">简述</h4>
				</div>
				<div class="modal-body">网页浏览器是个显示网站服务器或文件系统内的文件，并让用户与这些文件交互的一种应用软件。它用来显示在万维网或局域网等内的文字、图像及其他信息。这些文字或图像，可以是连接其他网址的超链接，用户可迅速及轻易地浏览各种信息。大部分网页为HTML格式，有些网页需特定浏览器才能正确显示。个人电脑上常见的网页浏览器按照2010年1月的市场占有率依次是微软的Internet Explorer、Mozilla的Firefox、Google的Chrome、苹果公司的Safari和Opera软件公司的Opera。浏览器是最常用的客户端程序。万维网是全球最大的链接文件网络文库。</div>
				<div class="modal-footer">
					<button type="button" class="btn btn-default" data-dismiss="modal">明白了</button>
			</div>
		</div>
	  </div>	
	</div>
	</body>
</html>
