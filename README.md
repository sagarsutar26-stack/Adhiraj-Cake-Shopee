<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Sweet Cake Shop</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial, Helvetica, sans-serif;
}

body{
    background:#f5f5f5;
    color:#333;
}

header{
    background:#7B241C;
    color:white;
    padding:20px;
    text-align:center;
}

nav{
    background:#922B21;
    text-align:center;
    padding:12px;
}

nav a{
    color:white;
    text-decoration:none;
    margin:15px;
    font-size:18px;
}

nav a:hover{
    color:#FFD700;
}

.hero{
    padding:50px 20px;
    text-align:center;
    background:white;
}

.hero img{
    width:80%;
    max-width:650px;
    border-radius:15px;
    box-shadow:0px 10px 20px rgba(0,0,0,.3);
}

.hero h2{
    margin-top:20px;
    color:#7B241C;
    font-size:36px;
}

.hero p{
    margin-top:15px;
    font-size:18px;
    line-height:1.6;
}

.btn{
    display:inline-block;
    margin-top:25px;
    padding:12px 30px;
    background:#C0392B;
    color:white;
    text-decoration:none;
    border-radius:8px;
    font-size:18px;
}

.btn:hover{
    background:#922B21;
}

section{
    padding:50px 20px;
    text-align:center;
}

.cards{
    display:flex;
    justify-content:center;
    flex-wrap:wrap;
    gap:20px;
    margin-top:25px;
}

.card{
    width:280px;
    background:white;
    padding:20px;
    border-radius:10px;
    box-shadow:0 5px 15px rgba(0,0,0,.2);
}

.card h3{
    color:#7B241C;
    margin-bottom:10px;
}

footer{
    background:#7B241C;
    color:white;
    text-align:center;
    padding:20px;
    margin-top:40px;
}
</style>

</head>

<body>

<header>
<h1> Sweet Cake Shop</h1>
<p>Fresh Cakes | Birthday Cakes | Wedding Cakes</p>
</header>

<nav>
<a href="#">Home</a>
<a href="#">About</a>
<a href="#">Gallery</a>
<a href="#">Menu</a>
<a href="#">Contact</a>
</nav>

<section class="hero">

<img src="cake.jpg" alt="Chocolate Cherry Cake">

<h2>Chocolate Cherry Layer Cake</h2>

<p>
A delicious three-layer chocolate cake topped with cherries,
chocolate ganache, whipped cream, and blueberry filling.
Perfect for birthdays, anniversaries, and special occasions.
</p>

<a href="#" class="btn">Order Now</a>

</section>

<section>

<h2>Why Choose Us?</h2>

<div class="cards">

<div class="card">
<h3> Fresh Ingredients</h3>
<p>Made daily using premium chocolate, fresh cream, and seasonal fruits.</p>
</div>

<div class="card">
<h3> Beautiful Decoration</h3>
<p>Professionally decorated cakes for birthdays, weddings, and celebrations.</p>
</div>

<div class="card">
<h3> Fast Delivery</h3>
<p>Same-day delivery available in selected locations.</p>
</div>

</div>

</section>

<section style="background:white;">

<h2>Contact Us</h2>

<p>Email: info@sweetcakeshop.com</p>

<p>Phone: 9284485735 </p>

<p>Open: Monday - Sunday | 9:00 AM - 9:00 PM</p>

</section>

<footer>

<p>© 2026 Sweet Cake Shop. All Rights Reserved.</p>

</footer>

</body>
</html>
