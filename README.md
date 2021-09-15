# HSE
Домашки 

<!doctype html>



<html>



	<head>
		<title> Личная страница Тимофея Будько </title>
	 	<!-- Required meta tags -->
	 	<meta charset="utf-8">
	 	<meta name="viewport" content="width=device-width, initial-scale=1">

		<meta name="description" content="Личная страница и контакты">

		<!-- Bootstrap Core CSS -->
		<link href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css" rel="stylesheet" media="screen">


	</head>
	
 	
	<body>

<!-- меню (navigation bar) -->

		<nav id="mainNav" class="navbar navbar-default navbar-fixed-top navbar-custom">

 -->
			<div class="container"> 
				<div class="navbar-header"> 
					<a href="https://ling.hse.ru/" class="navbar-brand">Школа лингвистики НИУ ВШЭ</a> 
				</div> 
				<nav class="collapse navbar-collapse" id="bs-navbar"> 
					<ul class="nav navbar-nav navbar-right"> 
						<li> <a href="https://lingvocodes.github.io/HSEinfo/ba-ling-2021/index.html">Страница курса</a> </li> 
						<li> <a href="https://lingvocodes.github.io/HSEinfo/ba-ling-2021/latin_2.html">Страница группы</a> </li> 
<!-- поправьте номер группы в URL, если нужно (от 1 до 4) -->
					</ul>
				</nav> 
			</div>
		</nav>

<!-- начинается шапка. у тега header есть атрибут style, который задает цвет фона и отступы. поменяйте значения атрибутов и посмотрите, как изменится страница -->

		<header style="background-color:pink; padding-top:70px; "> 
			<div class="container"> 
				<div class="row">
					<div class="col-md-4">
						<br><br>
<!-- здесь и дальше нужно поменять весь содержательный текст, чтобы получилась ваша личная страница -->
						<h1>Тимофей Будько</h1>
						<hr> <!-- это горизонтальная линия -->
						<p><i>Человек, НЕ умеющий и НЕ хотящий, но обязанный <b>создавать</i> HTML</b></p> 
					</div>
					<div class="col-md-4">
<!-- img - тег для вставки изображений. Мы использовали атрибут style, чтобы задать размер изображения и ширину рамки-->
<!-- Измените URL на URL вашей фотографии, а также настройте размер изображения -->
<img src="https://sun9-53.userapi.com/c627524/u273895478/video/x_a283728c.jpg" style="height:320px; margin:20px 20px 40px 20px; " >
					</div>
				</div>
			</div>
		</header>


		<section id="portfolio">
			<div class="container">

<!-- атрибут col-md-... говорит, что контент будет разделен на несколько столбцов, их ширина соотносится как 3 - 6 - 3 (Bootstrap использует воображаемую сетку из 12 равных по ширине колонок) -->
				<div class="col-md-3">

<!-- <article> не влияет на оформление, но помогает структурировать контент на осмысленые разделы -->
					<article>
						<h3>Место учебы</h2>
						<p>Фундаментальная и прикладная лингвистика, НИУ ВШЭ, Москва</p>
					</article>
					<article>
						<h3>Родной город</h2>
						<p>Москва</p>
					</article>
					<article>
						<h3>Школа</h2>
<!-- когда будете менять текст, не используйте бюрократических слов типа ГБОУ СОШ, ну пожаалуйста -->
						<p>АНОО "Ломоносовский лицей"</p>
					</article>
				</div>

				<div class="col-md-6">
					<article>
						<h3>Тут можно написать</h2>
						<p>Еще много много много много много много <br>
						много <br>
						поменьше <br>
						ну нормально <br>
						уже не слишком много <br>
						мало <br>
						чуток  <br>
						много <br>
						всего о себе</p>
					</article>
				</div>

				<div class="col-md-3">
					<h3>Я в соцсетях</h3>
<!-- тег <ul> - unordered list. Еще бывает тег <ol> -->
					<ul>
						<li>https://vk.com/id424059438</li>
						<li>Facebook</li>
						<li>https://twitter.com/home</li>
						<li>@timofeyster</li>
					</ul>
				</div>
			</div>
		</section>

<!-- это подвал. В этой части страницы обычно ставят копирайт (с помощью символа &copy;) и пишут об истории создания страницы. Поставьте свой копирайт -->
		<footer class="bs-docs-footer"> 
			<div class="container"> 
				<p style="text-align:right; ">&copy; Т. Будько, 2021</p> 
			</div>
		</footer>
	</body>
</html>
