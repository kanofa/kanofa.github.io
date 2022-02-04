---
title: fan
date: 2022-02-04 21:42:30
layout: false
---
{% raw %}
<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<title>16宫格翻牌游戏</title>
<link rel="icon" href="img/icon.png" sizes="192x192"/>
<link rel="stylesheet prefetch" href="https://fonts.googleapis.com/css?family=Coda">
<link rel="stylesheet prefetch" href="css/font-awesome.min.css">
<link rel="stylesheet" href="css/app.css">
</head>
<body>
<div class="container">
	<header>
		<h2>16宫格翻牌匹配</h2>
	</header>
<section class="score-panel">
		<ul class="stars">
			<li><i class="fa fa-star"></i></li>
			<li><i class="fa fa-star"></i></li>
			<li><i class="fa fa-star"></i></li>
		</ul>
翻开 <span class="moves">0</span> 次

<div class="restart" onClick="run()">
			<i class="fa fa-repeat"> 重玩</i>
		</div>
	</section>
<ul class="deck" id="deck">
</ul>
</div>
<script src="js/jquery.min.js"></script>
<script src="js/app.js"></script>
</body>
</html>
{% endraw %}