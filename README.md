# zeiss
digital design

<!DOCTYPE html><html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Refan Portfolio</title>  <style>
    * {margin:0;padding:0;box-sizing:border-box;font-family:'Poppins',sans-serif;}

    body {
      background: linear-gradient(135deg, #020617, #0f172a);
      color: white;
      overflow-x: hidden;
      transition: background 0.4s, color 0.4s;
    }

    body.light {
      background: #f1f5f9;
      color: #020617;
    }

    header {
      text-align: center;
      padding: 90px 20px;
      animation: fadeIn 1.2s ease;
    }

    header h1 {font-size: 48px;letter-spacing:2px;}
    header p {opacity:0.7;margin-top:10px;}

    .btn {
      margin-top:25px;
      display:inline-block;
      padding:12px 30px;
      background:linear-gradient(45deg,#22c55e,#4ade80);
      border-radius:30px;
      text-decoration:none;
      color:white;
      transition:0.3s;
      box-shadow:0 0 15px rgba(34,197,94,0.5);
    }

    .btn:hover {transform:scale(1.1);}

    .toggle {
      position: fixed;
      top: 20px;
      right: 20px;
      background: #111;
      padding: 10px 15px;
      border-radius: 20px;
      cursor: pointer;
      font-size: 14px;
    }

    body.light .toggle {background:#ddd;color:#000;}

    .section-title {text-align:center;margin:60px 0 20px;font-size:26px;}

    .gallery {
      display:grid;
      grid-template-columns:repeat(auto-fit,minmax(280px,1fr));
      gap:25px;
      padding:20px;
    }

    .card {
      background:#020617;
      border-radius:20px;
      overflow:hidden;
      transition:0.4s;
      box-shadow:0 10px 25px rgba(0,0,0,0.6);
    }

    body.light .card {background:white;}

    .card:hover {transform:translateY(-12px) scale(1.03);}

    .card img {width:100%;display:block;}

    .card p {padding:12px;font-size:14px;opacity:0.8;}

    .price {text-align:center;margin:60px 20px;}

    .price-box {
      display:inline-block;
      padding:25px 35px;
      background:#020617;
      border-radius:20px;
    }

    body.light .price-box {background:white;}

    .testimoni {
      padding:40px 20px;
      text-align:center;
    }

    .testi-box {
      max-width:500px;
      margin:10px auto;
      background:#020617;
      padding:20px;
      border-radius:15px;
      opacity:0.8;
    }

    body.light .testi-box {background:white;}

    .whatsapp {
      position:fixed;
      bottom:20px;
      right:20px;
      background:#22c55e;
      padding:15px;
      border-radius:50%;
      text-decoration:none;
      color:white;
      font-size:20px;
    }

    footer {text-align:center;padding:40px;opacity:0.6;}

    @keyframes fadeIn {
      from {opacity:0;transform:translateY(20px);} 
      to {opacity:1;transform:translateY(0);} 
    }
  </style></head><body><div class="toggle" onclick="toggleMode()">🌙 Mode</div><header>
  <h1>Refan Aprilino</h1>
  <p>Graphic Designer | YouTube Thumbnail Specialist</p>
  <a href="#" class="btn">Hire Me</a>
</header><h2 class="section-title">My Work</h2><div class="gallery">
  <div class="card"><img src="1.jpg"><p>Gaming Thumbnail</p></div>
  <div class="card"><img src="2.jpg"><p>Streaming Thumbnail</p></div>
  <div class="card"><img src="3.jpg"><p>MLBB Design</p></div>
  <div class="card"><img src="4.jpg"><p>VTuber Debut</p></div>
</div><div class="price">
  <h2 class="section-title">Price List</h2>
  <div class="price-box">
    Basic : Rp10K <br>
    Standard : Rp20K <br>
    Premium : Rp30K+
  </div>
</div><div class="testimoni">
  <h2 class="section-title">Testimoni</h2>
  <div class="testi-box">"Desainnya keren banget, CTR naik!"</div>
  <div class="testi-box">"Fast response & hasil memuaskan 🔥"</div>
</div><a href="https://wa.me/6281234567890" class="whatsapp">💬</a>

<footer>© 2026 Refan Portfolio</footer><script>
function toggleMode(){
  document.body.classList.toggle('light');
}
</script></body>
</html>