<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Beauty Salon</title>

<style>
body{
  margin:0;
  font-family: Arial, sans-serif;
  background:#fff5f8;
  color:#333;
}

/* Header */
header{
  background: linear-gradient(135deg, #f8c8dc, #fff);
  text-align:center;
  padding:60px 20px;
}

header h1{
  font-size:40px;
  color:#b76e79;
  margin:0;
}

header p{
  font-size:18px;
  color:#555;
}

/* Sections */
section{
  padding:50px 20px;
  text-align:center;
}

h2{
  color:#b76e79;
  margin-bottom:20px;
}

/* Services */
.services{
  display:flex;
  justify-content:center;
  gap:20px;
  flex-wrap:wrap;
}

.card{
  background:#fff;
  width:250px;
  padding:20px;
  border-radius:15px;
  box-shadow:0 5px 15px rgba(0,0,0,0.1);
}

.card img{
  width:100%;
  border-radius:10px;
}

/* Button */
.btn{
  background:#b76e79;
  color:white;
  padding:10px 20px;
  border:none;
  border-radius:20px;
  cursor:pointer;
  margin-top:10px;
}

.btn:hover{
  background:#a05a66;
}

/* Footer */
footer{
  background:#f8c8dc;
  text-align:center;
  padding:20px;
  margin-top:30px;
}
</style>
</head>

<body>

<header>
  <h1>Beauty Salon 💖</h1>
  <p>Hair • Nails • Beauty Care</p>
</header>

<section>
  <h2>Our Services</h2>

  <div class="services">

    <div class="card">
      <img src="https://via.placeholder.com/250x150?text=Hair+Style" alt="">
      <h3>Hair Styling</h3>
      <button class="btn">Book</button>
    </div>

    <div class="card">
      <img src="https://via.placeholder.com/250x150?text=Nails" alt="">
      <h3>Nail Art</h3>
      <button class="btn">Book</button>
    </div>

  </div>
</section>

<section>
  <h2>About Us</h2>
  <p>
    We provide elegant beauty services with a soft luxury experience 💅💖
  </p>
</section>

<footer>
  © 2026 Beauty Salon
</footer>

</body>
</html>