# lisson
<html>
	<head>
		<title>Cats</title>
		<style>
			*{
				padding: 0;
				margin: 0;
			}
		
			.header{
				color: white;
				background: #151c39e8;
				padding: 20px;
			}
			
			.menu-item{
				list-style: none;
			}
			
			.menu-link{
				text-decoration: none;
				color: white;
			}
			
			.banner-section{
				background: url(img/banner-bg.jpg);
				padding: 100px 0;
				background-size: cover;
			}
			
			.banner-title{
				font-size: 48px; 
			}
			
			.banner-text{
				color: white;
				text-align: center;
			}
			
/*начало css для карточек*/
			
			.cards-section{
				padding: 50px 0; /*необходимо прокомментировать каждое свойство!*/
			}
			
			.cards-title, .cards-description{
				color: #151c39;
				text-align: center;
			}
			
			.card
			{
				padding: 25px;
				margin-top: 25px;
				width: 25%;
				background: white;
				box-shadow: 0px 2px 7px #9e90ff;
				text-align: center;
			}
			
			.card:hover
			{ 
				box-shadow: 0px 10px 30px #9e90ff; 
			}

			.card-link
			{
				text-decoration: none;
				color: white;
			}

			.card-button
			{
				text-align: center;
				background: #151c39;
				padding: 10px 70px;
				border-radius: 10px;
			}

			.card-title, .card-text
			{
				margin-bottom: 10px;
			}
			
/*конец css для карточек*/
		</style>
		
	</head>
	<body>
	
		<header class="header">
			<div class="header-logo">
				<img class="logo-img" src="img/cat.png">
				<h1 class="logo-title">CATS</h1>
			</div>
			
			<div class="header-menu">
				<ul class="menu">
					<li class="menu-item">
						<a href="#" class="menu-link">Home</a>
					</li>
					<li class="menu-item">
						<a href="#" class="menu-link">About</a>
					</li>
					<li class="menu-item">
						<a  href="#" class="menu-link">Animals</a>
					</li>
				</ul>
			</div>
		</header>
		
		<main class="main">
		
			<section class="banner-section">
				<div class="banner-text">
					<h1 class="banner-title">Зоомагазин</h1>
					<div class="banner-description">Заведи питомца!</div>
				</div>
			</section>
			
			<section class="cards-section">
			
				<div class="cards-text">
					<h1 class="cards-title">Рекомендуемы животные!</h1>
					<div class="cards-description">Специально для вас</div>
				</div>
				
				<div class="cards">
					<div class="card">
						<img class="card-img" src="img/Vasily.jpg">
						<div class="card-body">
							<h3 class="card-title">Кот Василий</h3>
							<div class="card-text">Ищет добрых хозяев!</div>
							<div class="card-button">
								<a class="card-link" href="#">Узнать подробности</a>
							</div>
						<div>
					</div>
				</div>
			
			</section>
			
		</main>
		
		<footer class="footer">
		
		</footer>
	
	</body>
</html>
