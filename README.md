<!DOCTYPE html>
<html lang="ru">
	<head>
		<link rel="preconnect" href="https://fonts.gstatic.com">
		<link href="https://fonts.googleapis.com/css2?family=Cardo:ital@1&family=Open+Sans:wght@700&family=Raleway:wght@400;600;700&display=swap" rel="stylesheet">
		<link href="https://fonts.googleapis.com/css2?family=Dancing+Script&family=Lobster&display=swap" rel="stylesheet">
    	<link rel="stylesheet" type="text/css" href="brain.css">

    	<link rel="stylesheet" type="text/css" href="https://cdn.jsdelivr.net/npm/slick-carousel@1.8.1/slick/slick.css"/>
    	<link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">

		<meta charset="utf-8">
		<meta name="viewport" content="width=device-width, initial-scale=1">

		<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.6.0/jquery.min.js"></script>

		<title>Academy of Success</title>
	</head>

	<body>
	<!--HEADER-->
		<header class="header" id="header">
			<div class="container">
				<div class="header__inner">
					<div class="header__logo">
						<span class="academy">Academy</span> <span class="of">of</span> <span class="success">Success</span>
					</div>
					<nav class="nav" id="nav">
						<a class="nav__link" href="#" data-scroll="#feat">Особенности</a>
						<a class="nav__link" href="#" data-scroll="#blog">Блог</a>
						<a class="nav__link" href="#" data-scroll="#about">О нас</a>
					</nav>

					<button class="burger" type="button" id="navToggle">
						<span class="burger__item"></span>
					</button>
			</div>
		</header>


	<!--INTRO-->
		<div class="intro" id="intro">
			<div class="container">
				<div class="intro__inner">
					<h1 class="intro__title">
						<div class="welcome">Welcome to</div><div class="header__logo2"><span class="academy">Academy</span> <span class="of">of</span> <span class="success">Success</span></div>
					</h1>
					<h2 class="intro__description">
						Успех — это способность шагать от одной неудачи к другой, не теряя энтузиазма.
					</h2>
					<!--<a class="btn btn_red" href="#">Find Out More</a>-->
				</div>
			</div>
		</div>


	<!--FEATURES-->
	<div class="container">
		<div class="features" id="feat">
			<div class="features__item" data-aos="flip-up">
				<img class="features__icon" src="rocket.png" alt="" height="80">
				<h3 class="features__title">Креативность</h3>
				<div class="features__text"> Помогаем принимать творческие решения, понимать, принимать и создавать принципиально новые идеи.</div> 
			</div>

			<div class="features__item" data-aos="flip-up">
				<img class="features__icon" src="tick.png" alt="" height="80">
				<h3 class="features__title">Успешные задании</h3>
				<div class="features__text">Ученики успешно делают и заканчивают разные виды задании.</div>
			</div>

			<div class="features__item" data-aos="flip-up">
				<img class="features__icon" src="target.png" alt="" height="80">
				<h3 class="features__title">Достигание целей</h3>
				<div class="features__text">Наши ученики достигают своих целей, если интересуются в этом.</div>
			</div>

			<div class="features__item" data-aos="flip-up">
				<img class="features__icon" src="idea.png" alt="" height="80">
				<h3 class="features__title">Идеи</h3>
				<div class="features__text">Ученики придумывают много разных идеи и успешно их осуществляют.</div>
			</div>

			<div class="features__item" data-aos="flip-up">
				<img class="features__icon" src="thumb.png" alt="" height="80">
				<h3 class="features__title">Выполнеие упражнении</h3>
				<div class="features__text">Многие наши ученики выполняют упражнения, которые нужны для выполнения определённой задачи</div>
			</div>

			<div class="features__item" data-aos="flip-up">
				<img class="features__icon" src="circle.png" alt="" height="80">
				<h3 class="features__title">Моторика</h3>
				<div class="features__text">Развиваем двигательную активность организма. Под моторикой понимают последовательность движений.</div>
			</div>
		</div> <!--.features-->
	</div><!--.container-->

	<!--WORKS-->
<!--	<div class="works">
		<div class="works__item">
			<img class="works__photo" src="img/wbear.jpg" height="350px">
			<div class="works__content">
				<div class="works__title">Project Name</div>
				<div class="works__text">Projcts Content</div>
			</div>
		</div>

		<div class="works__item">
			<img class="works__photo" src="img/snow.jpg" height="350px">
			<div class="works__content">
				<div class="works__title">Project Name</div>
				<div class="works__text">Projcts Content</div>
			</div>
		</div>

		<div class="works__item">
			<img class="works__photo" src="img/lbear.jpg" height="350px">
			<div class="works__content">
				<div class="works__title">Project Name</div>
				<div class="works__text">Projcts Content</div>
			</div>
		</div>

		<div class="works__item">
			<img class="works__photo" src="img/ssnow.jpg" height="350px">
			<div class="works__content">
				<div class="works__title">Project Name</div>
				<div class="works__text">Projcts Content</div>
			</div>
		</div>

		<div class="works__item">
			<img class="works__photo" src="img/snoww.jpg" height="350px">
			<div class="works__content">
				<div class="works__title">Project Name</div>
				<div class="works__text">Projcts Content</div>
			</div>
		</div>

		<div class="works__item">
			<img class="works__photo" src="img/polarbear.jpg" height="350px">
			<div class="works__content">
				<div class="works__title">Project Name</div>
				<div class="works__text">Projcts Content</div>
			</div>
		</div>

		<div class="works__item">
			<img class="works__photo" src="img/snnow.jpg" height="250px">
			<div class="works__content">
				<div class="works__title">Project Name</div>
				<div class="works__text">Projcts Content</div>
			</div>
		</div>

		<div class="works__item">
			<img class="works__photo" src="img/bbear.jpg" height="350px">
			<div class="works__content">
				<div class="works__title">Project Name</div>
				<div class="works__text">Projcts Content</div>
			</div>
		</div>
	</div>--><!--works-->
	
	<!--TELLINGS-->

	<div class="tell"  id="blog">
		<div class="container">

					<div class="tell__item">
						<div class="tell__photo">
							<img class="tell__img" src="steve.jpg" height="400px">
						</div>
						<div class="tell__content">
							<div class="tell__text">
								"Ваше время ограничено, не тратьте его, живя другой жизнью. Не позволяйте взглядам других заглушать свой собственный внутренний голос."
							</div>
							<div class="tell__author">
								-Стив Джобс
							</div>
						</div>
					</div>	

		</div><!--.container-->
	</div><!--.tell-->

	<!--FOOOTER-->
	<footer class="footer"  id="about">
		<div class="container">

			<div class="footer__inner">
				<div class="footer__block">
					<h4 class="footer__title">Местоположение</h4>
					<address class="footer__address">
						<div>Казахстан, Актобе</div>
						<div>ул.101 Стрелковой Бригады 2А</div>
					</address>
				</div>

				<div class="footer__block">
					<h4 class="footer__title">Соц сети</h4>
					<a href="https://www.instagram.com/darina_aktobe/?hl=ru"><img class="footer__logo" src="instagram.svg" width="40px" height="40px"></a>
					<a href="#"><img class="footer__logo" src="twitter.svg" width="40px" height="40px"></a>
					<a href="#"><img class="footer__logo" src="vk.svg" width="40px" height="40px"></a>
				</div>

				<div class="footer__block">
					<h4 class="footer__title">Контактные номера</h4>
					<div class="footer__text">
						<div>88 88 88</div> 
						<div>8 888 888 88 88</div>
					</div>
				</div>
			</div><!--.footer__inner-->
		</div><!--container-->

			<div class="footer__copyright">
				<div class="footer__copyright__text">
					<div>Автор сайта <span class="name">Айбар</span></div>
					<div>Разработчик-программист веб-сайтов</div>
				</div>
			</div>
	</footer> 

	<script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
	<script src="java.js"></script>

	</body>
</html>
