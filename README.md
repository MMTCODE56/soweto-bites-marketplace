
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Soweto Bites Marketplace</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

<header>
  <h1>Soweto Bites</h1>

  <nav>
    <a href="#">Home</a>
    <a href="#">Restaurants</a>
    <a href="#">Drivers</a>
    <a href="#">Vendors</a>
  </nav>
</header>

<section class="hero">
  <h2>The Township Marketplace Revolution</h2>

  <p>
    Connecting restaurants, logistics,
    vendors and customers into one digital ecosystem.
  </p>

  <button>Join Marketplace</button>
</section>

<section class="features">

  <div class="card">
    <h3>Restaurant Dashboard</h3>
    <p>Manage orders and menus.</p>
  </div>

  <div class="card">
    <h3>Delivery Tracking</h3>
    <p>Real-time logistics system.</p>
  </div>

  <div class="card">
    <h3>AI Analytics</h3>
    <p>Business intelligence tools.</p>
  </div>

</section>

<footer>
  <p>© 2026 Soweto Bites Marketplace</p>
</footer>

</body>
</html># soweto-bites-marketplace
*{
  margin:0;
  padding:0;
  box-sizing:border-box;
  font-family:Arial;
}

body{
  background:#0f172a;
  color:white;
}

header{
  background:#111827;
  display:flex;
  justify-content:space-between;
  align-items:center;
  padding:20px;
}

nav a{
  color:white;
  text-decoration:none;
  margin-left:20px;
}

.hero{
  height:80vh;
  display:flex;
  flex-direction:column;
  justify-content:center;
  align-items:center;
  text-align:center;
  padding:20px;
}

.hero h2{
  font-size:3rem;
  margin-bottom:20px;
}

.hero p{
  max-width:700px;
  line-height:1.7;
  margin-bottom:30px;
}

button{
  background:#22c55e;
  border:none;
  padding:15px 30px;
  border-radius:10px;
  color:white;
  font-size:1rem;
  cursor:pointer;
}

.features{
  display:flex;
  justify-content:center;
  gap:20px;
  flex-wrap:wrap;
  padding:60px 20px;
}

.card{
  background:#1e293b;
  padding:30px;
  border-radius:15px;
  width:300px;
}