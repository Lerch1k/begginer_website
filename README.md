
<html lang="en">
<head>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
	<div class="container">
		<div class="person">
			<div class="person__name">
				<div class="photo"></div>
				<div class="name"><h2>Валерія Вдовиченко</h2><h3>full-stack разработчик</h3></div>
			</div>
			<div class="person__info">
			<p class="p1">Lorem ipsum dolor sit, amet, consectetur adipisicing elit. Dicta cupiditate, iure ut? Nostrum, culpa? Deserunt, odio laudantium id facilis soluta aperiam beatae vel voluptatum, tempore. Perferendis laborum omnis quos officiis eligendi iusto. Quam velit maiores dolorem, nesciunt inventore praesentium, magni iste cupiditate vero sapiente minima, quae error! Deserunt cum perferendis eveniet, repudiandae doloremque beatae ab, nostrum inventore quod eos blanditiis, tenetur perspiciatis sed eum quis voluptates qui? Consequatur atque temporibus rem in ab. Tempora voluptatem debitis distinctio magnam voluptates sint. Debitis reprehenderit est laboriosam cupiditate nisi alias modi. Quibusdam numquam eligendi rerum ad, consectetur voluptatem necessitatibus magnam ullam esse? Debitis veniam delectus amet perspiciatis libero officia! Ut rem, nobis officia hic nesciunt accusantium! Inventore beatae pariatur, fuga unde enim et ipsa non voluptate quos provident, consectetur aliquid quas distinctio esse ipsum. Molestiae alias ut labore perspiciatis repudiandae assumenda exercitationem maxime a ratione porro accusamus eius deserunt sapiente, aperiam obcaecati veritatis.</p>
			<p class="p2">
				Lorem ipsum dolor sit amet consectetur <a href="#">adipisicing</a> elit. Suscipit rem culpa <a href="#">eius</a> pariatur voluptate veritatis rerum, enim dicta sit. Id.
			</p>
			<nav>
				<a href="#">linkedin.com</a>
				<a href="#">ler4ik@gmail.com</a>
				<a href="#">Ler4ik</a>
				<a href="#">https://github.com/Lerch1k</a>
			</nav>
			</div>
		</div>
	</div>
	<style>
		body{
						background-color: #E6F8FF;
		}
		nav{
			display: flex;
			flex-wrap: wrap;
		}
		a{
			text-decoration: none;
			color: inherit;
			cursor: pointer;
		}
		.p2 a{
			color: white;
			text-decoration: underline;
		}
		.p1{
			font-family: sans-serif;
			font-size: 16px;
			padding: 10px 0px;
		}
		.p2{color:#247e80;
			margin-bottom: 10px;
			font-family: arial;
		}
		nav a{
			transition: color 0.3s;
			text-align: center;
			margin-top: 5px;
			display: inline-block;
			flex-basis: 50%;
		}
		nav a:hover{
			transition: color 0.3s;
			color: white;
		}
		*{
			color: black;
			margin: 0px;
			padding: 0px;
		}
		.container{
			width: 620px;
			margin: auto;
			background-color: #D1E6E8;
			padding: 20px 20px;
		}
		.person{
			padding-top: 100px;
			
		}
		.person__name{
			padding-bottom: 10px;
			border-bottom: 1px solid black;
			display: flex;
			justify-content: space-around;
		}
		.name{
			margin-top: 10px;
			margin-left: 50px;
		}
		h2{
			font-size: 40px;
		}
		.name h3{
			margin-top: 40px;
			font-size: 23px;
		}
		.person .photo{
			border-radius: 50%;
			width: 200px;
			height: 200px;
			background-image: url("123123.jpg");
			background-size: cover;
		}
	</style>
</body>
</html>
