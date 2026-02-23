index.html  
products.html  
product-haybales.html  
style.css  
cart.js <!DOCTYPE html>  
<html>  
<head>  
<title>Mini Farm Supply Co.</title>  
<link rel="stylesheet" href="style.css">  
</head>  
  
<body>  
  
<header>  
<h1>Mini Farm Supply Co.</h1>  
<p>1/64 Scale Farm Supplies & Diorama Accessories</p>  
  
<nav>  
<a href="index.html">Home</a>  
<a href="products.html">Shop</a>  
</nav>  
</header>  
  
<section class="hero">  
<h2>Build Your Dream Farm Display</h2>  
<p>Hay bales, feed pallets, fences, tools, and custom accessories for 1/64 farm toys.</p>  
<a class="shopbtn" href="products.html">Shop Now</a>  
</section>  
  
<section class="featured">  
<h2>Featured Products</h2>  
  
<div class="product">  
<img src="haybales.jpg">  
<h3>Square Hay Bale Pack</h3>  
<p>$6.99</p>  
<a href="product-haybales.html">View Item</a>  
</div>  
  
<div class="product">  
<img src="pallets.jpg">  
<h3>Feed Pallet Set</h3>  
<p>$7.99</p>  
</div>  
  
</section>  
  
<footer>  
<p>© 2026 Mini Farm Supply Co.</p>  
</footer>  
  
</body>  
</html> body{  
font-family: Arial;  
margin:0;  
background:#f4f4f4;  
}  
  
header{  
background:#2f5d2f;  
color:white;  
padding:20px;  
text-align:center;  
}  
  
nav a{  
color:white;  
margin:15px;  
text-decoration:none;  
font-weight:bold;  
}  
  
.hero{  
background:#dfe8d8;  
padding:60px;  
text-align:center;  
}  
  
.shopbtn{  
background:#3d7a3d;  
color:white;  
padding:12px 20px;  
text-decoration:none;  
border-radius:6px;  
}  
  
.featured{  
padding:40px;  
text-align:center;  
}  
  
.product{  
background:white;  
padding:15px;  
margin:20px;  
display:inline-block;  
width:250px;  
box-shadow:0 0 10px rgba(0,0,0,.2);  
}  
  
.product img{  
width:100%;  
}  
  
footer{  
background:#222;  
color:white;  
text-align:center;  
padding:20px;  
margin-top:40px;  
} <!DOCTYPE html>  
<html>  
<head>  
<title>Square Hay Bale Pack</title>  
<link rel="stylesheet" href="style.css">  
<script src="cart.js"></script>  
</head>  
  
<body>  
  
<header>  
<h1>Mini Farm Supply Co.</h1>  
<a href="products.html">← Back to Shop</a>  
</header>  
  
<section class="featured">  
  
<h2>Square Hay Bale Pack (1/64)</h2>  
  
<img src="haybales.jpg" style="width:300px">  
  
<p>  
Handmade 1/64 scale square hay bales.  
Perfect for dioramas and farm displays.  
Pack of 12.  
</p>  
  
<h3>$6.99</h3>  
  
<button onclick="addToCart('Square Hay Bale Pack',6.99)">  
Add to Cart  
</button>  
  
</section>  
  
</body>  
</html> let cart = [];  
  
function addToCart(product, price){  
cart.push({product, price});  
alert(product + " added to cart!");  
console.log(cart);  
}  
- [ ]   
  
