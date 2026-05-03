# beauty-salon
Your next home
index.html
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Beauty Salon</title>
<style>
body {
  margin:0;
  font-family: Arial, sans-serif;
  background:#fff;
  color:#333;
}
header {
  text-align:center;
  padding:60px 20px;
  background:linear-gradient(to right,#f8d7da,#fce4ec);
}
h1 {font-size:32px;}
button {
  padding:12px 25px;
  background:#ff4d6d;
  color:white;
  border:none;
  border-radius:25px;
  cursor:pointer;
}
.section {
  padding:40px 20px;
  text-align:center;
}
.services {
  display:flex;
  flex-wrap:wrap;
  justify-content:center;
  gap:20px;
}
.card {
  padding:20px;
  border-radius:15px;
  box-shadow:0 0 10px rgba(0,0,0,0.1);
  width:200px;
}
.footer {
  background:#f8d7da;
  padding:20px;
}
</style>
</head>

<body>

<header>
  <h1>Glow Beauty Salon</h1>
  <p>Feel Confident. Look Beautiful.</p>
  <button onclick="window.location.href='https://wa.me/201000000000'">
    Book Now on WhatsApp
  </button>
</header>

<div class="section">
  <h2>About Us</h2>
  <p>We provide high-quality beauty services with professional care and modern techniques.</p>
</div>

<div class="section">
  <h2>Our Services</h2>
  <div class="services">
    <div class="card">Hair Styling</div>
    <div class="card">Makeup</div>
    <div class="card">Nails</div>
    <div class="card">Skincare</div>
  </div>
</div>

<div class="section">
  <h2>Testimonials</h2>
  <p>"Amazing service and results!"</p>
  <p>"Best salon ever!"</p>
</div>

<div class="section">
  <h2>Contact Us</h2>
  <p>Instagram: @salon</p>
  <p>Location: Cairo</p>
</div>

<div class="footer">
  <p>© 2026 Beauty Salon</p>
</div>

</body>
</html>
