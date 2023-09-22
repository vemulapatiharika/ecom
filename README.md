
<!DOCTYPE html>
<html>
<head>
	<title>E-commerce Website Home Page</title>
	<style>
		body {
			margin: 0;
			padding: 0;
			font-family: Arial, sans-serif;
		}
		header {
			background-color:green;
			color: #fff;
			padding: 20px;
			text-align: center;
		}
		h1 {
			margin: 0;
			font-size: 36px;
		}
		h2 {
			font-size: 24px;
			margin-bottom: 10px;
			text-transform: uppercase;
			border-bottom: 1px solid #ccc;
			padding-bottom: 10px;
		}
		.product {
			display: flex;
			flex-wrap: wrap;
			justify-content: center;
			align-items: center;
			margin: 20px;
			padding: 20px;
			border: 1px solid #ccc;
			border-radius: 10px;
			box-shadow: 0 0 10px #ccc;
			max-width: 800px;
		}
		.product img {
			width: 200px;
			height: 200px;
			object-fit: contain;
			margin-right: 20px;
		}
		.product-info {
			flex: 1;
		}
		.product h3 {
			font-size: 20px;
			margin: 0;
		}
		.product p {
			margin: 10px 0;
			font-size: 16px;
		}
		.product button {
			background-color:green;
			color: #fff;
			padding: 10px 20px;
			border: none;
			border-radius: 5px;
			cursor: pointer;
			font-size: 16px;
		}
		.product button:hover {
			background-color:green;
		}
	</style>
</head>
<body>
	<header>
		<h1>E-commerce Website</h1>
	</header>
	<main>
		<section>
			<h2>Electronics</h2>
            <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/ad/IPhone_1st_Gen.svg/255px-IPhone_1st_Gen.svg.png">
			<footer>
                <div class="footer-content">
                    <div class="footer-ul-container">
                        <ul class="category">
                            <li class="category-title">types of Electronics</li>
                            <li><a href="#" class="footer-link">smartwatch</a></li>
                            <li><a href="#" class="footer-link">tvs and appliances</a></li>
                            <li><a href="#" class="footer-link">mobiles</a></li>
                            <li><a href="#" class="footer-link">laptops</a></li>
                            <li><a href="#" class="footer-link">earphones</a></li>
                            <li><a href="#" class="footer-link">tablets</a></li>
                            <li><a href="#" class="footer-link">chargers and cables</a></li>
                            <li><a href="#" class="footer-link">powerbanks</a></li>
                            <li><a href="#" class="footer-link">home audio</a></li>
                           
                        </ul>
        </section>
		<section>
			<h2>Clothing</h2>
			<div class="product">
				<img src="https://upload.wikimedia.org/wikipedia/en/thumb/3/34/GuyLaroche_suit_jacket_83d40m_black_skirt_late1959_early1960_vintage.png/330px-GuyLaroche_suit_jacket_83d40m_black_skirt_late1959_early1960_vintage.png" alt="Product Image">
                <footer>
                    <div class="footer-content">
                        <div class="footer-ul-container">
                            <ul class="category">
                                <li class="category-title">men</li>
                                <li><a href="#" class="footer-link">t-shirts</a></li>
                                <li><a href="#" class="footer-link">sweatshirts</a></li>
                                <li><a href="#" class="footer-link">shirts</a></li>
                                <li><a href="#" class="footer-link">jeans</a></li>
                                <li><a href="#" class="footer-link">trousers</a></li>
                                <li><a href="#" class="footer-link">shoes</a></li>
                                <li><a href="#" class="footer-link">casuals</a></li>
                                <li><a href="#" class="footer-link">formals</a></li>
                                <li><a href="#" class="footer-link">sports</a></li>
                                <li><a href="#" class="footer-link">watch</a></li>
                            </ul>
                            <ul class="category">
                                <li class="category-title">women</li>
                                <li><a href="#" class="footer-link">t-shirts</a></li>
                                <li><a href="#" class="footer-link">sweatshirts</a></li>
                                <li><a href="#" class="footer-link">shirts</a></li>
                                <li><a href="#" class="footer-link">jeans</a></li>
                                <li><a href="#" class="footer-link">trousers</a></li>
                                <li><a href="#" class="footer-link">shoes</a></li>
                                <li><a href="#" class="footer-link">casuals</a></li>
                                <li><a href="#" class="footer-link">formals</a></li>
                                <li><a href="#" class="footer-link">sports</a></li>
                                <li><a href="#" class="footer-link">watch</a></li>
                            </ul>
                        </div>
                    </div>
                </footer>
            </section>
            <div class="product">
				<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/9c/Stevemannwristcomp.jpg/330px-Stevemannwristcomp.jpg" alt="Product Image">
				<div class="product-info">
					<h3>Product 1</h3>
					<p>Brand: Brand 1</p>
					<p>Price: $100</p>
					<button>Add to Cart</button>
				</div>
			</div>
			<div class="product">
				<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/5/54/Earpods.jpg/330px-Earpods.jpg" alt="Product Image">
				<div class="product-info">
					<h3>Product 2</h3>
					<p>Brand: Brand 2</p>
					<p>Price: $150</p>
					<button>Add to Cart</button>
				</div>
			</div>
		
