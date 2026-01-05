## Hi there 👋

<!--
**dakemultiservices/dakemultiservices** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->


Code : 
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />

  <!-- SEO -->
  <meta name="description" content="Dake Multiservices is an authorized Digital CSC Center in Parbhani providing Aadhaar, PAN, Banking, Government and Online Services." />
  <meta name="keywords" content="CSC Center Parbhani, Dake Multiservices, Aadhaar PAN CSC, Digital Seva Kendra Maharashtra" />
  <meta name="author" content="Dake Multiservices" />

  <title>Dake Multiservices | Digital CSC Center Parbhani</title>

  <!-- Fonts & Icons -->
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">

  <style>
    *{margin:0;padding:0;box-sizing:border-box;font-family:'Poppins',sans-serif}
    body{background:#f4f7fb;color:#222;scroll-behavior:smooth}

    /* NAVBAR */
    nav{
      position:fixed;top:0;width:100%;z-index:1000;
      background:#ffffff;
      box-shadow:0 2px 10px rgba(0,0,0,.1);
      display:flex;justify-content:space-between;align-items:center;
      padding:12px 35px;
    }
    nav h2{color:#0b5ed7;font-weight:700}
    nav span{color:#198754}
    nav a{text-decoration:none;color:#222;margin-left:22px;font-weight:500}
    nav a:hover{color:#0b5ed7}

    /* HERO */
    header{
      min-height:100vh;
      background:linear-gradient(rgba(0,0,0,.65),rgba(0,0,0,.65)),url('https://images.unsplash.com/photo-1581092160607-ee67b3d77b9b');
      background-size:cover;background-position:center;
      color:#fff;display:flex;align-items:center;justify-content:center;
      text-align:center;padding:20px
    }
    header h1{font-size:3.2rem;animation:fadeDown 1.2s}
    header h1 span{color:#00d4ff}
    header p{margin:20px 0;font-size:1.2rem;animation:fadeUp 1.6s}

    .btn{
      padding:15px 38px;border:none;border-radius:40px;
      background:linear-gradient(45deg,#0b5ed7,#00d4ff);
      color:#fff;font-size:1rem;font-weight:600;cursor:pointer;transition:.3s
    }
    .btn:hover{transform:scale(1.05);opacity:.9}

    section{padding:90px 25px;max-width:1200px;margin:auto}

    /* SERVICES */
    .services{display:grid;grid-template-columns:repeat(auto-fit,minmax(260px,1fr));gap:28px}
    .card{
      background:#fff;padding:35px;border-radius:22px;text-align:center;
      box-shadow:0 12px 30px rgba(0,0,0,.12);transition:.4s
    }
    .card i{font-size:42px;color:#0b5ed7;margin-bottom:15px}
    .card:hover{transform:translateY(-15px)}

    /* STATS */
    .stats{display:grid;grid-template-columns:repeat(auto-fit,minmax(200px,1fr));gap:25px;text-align:center}
    .stat-box{background:#0b5ed7;color:#fff;padding:35px;border-radius:20px}
    .stat-box h3{font-size:2.2rem}

    /* ABOUT */
    .about{text-align:center;max-width:900px;margin:auto;font-size:1.05rem}

    /* CONTACT */
    .contact-grid{display:grid;grid-template-columns:1fr 1fr;gap:30px}
    .contact-box{
      background:#198754;color:#fff;padding:45px;border-radius:25px
    }
    .contact-box p{margin:12px 0}

    .contact-form{
      background:#fff;padding:40px;border-radius:25px;box-shadow:0 10px 25px rgba(0,0,0,.12)
    }
    .contact-form input,.contact-form textarea{
      width:100%;padding:14px;margin-bottom:15px;border-radius:12px;border:1px solid #ccc
    }

    footer{background:#000;color:#fff;text-align:center;padding:22px;margin-top:60px}

    /* WhatsApp */
    .whatsapp{
      position:fixed;bottom:20px;right:20px;background:#25d366;color:#fff;
      padding:15px 18px;border-radius:50%;font-size:26px;box-shadow:0 8px 20px rgba(0,0,0,.3)
    }

    @keyframes fadeDown{from{opacity:0;transform:translateY(-50px)}to{opacity:1}}
    @keyframes fadeUp{from{opacity:0;transform:translateY(50px)}to{opacity:1}}

    @media(max-width:768px){.contact-grid{grid-template-columns:1fr}}
  </style>
</head>
<body>

<nav>
  <h2>Dake <span>Multiservices</span></h2>
  <div>
    <a href="#home">Home</a>
    <a href="#services">Services</a>
    <a href="#about">About</a>
    <a href="#contact">Contact</a>
    <a href="#" onclick="toggleLang()">मराठी</a>
  </div>
</nav>

<header id="home">
  <div>
    <h1 id="title-en">Dake <span>Multiservices</span></h1>
    <h1 id="title-mr" style="display:none">डाके <span>मल्टीसर्व्हिसेस</span></h1>

    <p id="tag-en">Authorized Digital CSC Center – Government & Online Services</p>
    <p id="tag-mr" style="display:none">अधिकृत डिजिटल CSC केंद्र – सर्व सरकारी व ऑनलाइन सेवा</p>

    <button class="btn" onclick="document.getElementById('services').scrollIntoView({behavior:'smooth'})">Explore Services</button>
  </div>
</header>

<section id="services">
  <h2 style="text-align:center;margin-bottom:40px">Our Services</h2>
  <div class="services">
    <div class="card"><i class="fa-solid fa-id-card"></i><h3>Aadhaar Services</h3><p>Update, Print, Linking</p></div>
    <div class="card"><i class="fa-solid fa-address-card"></i><h3>PAN Card</h3><p>New / Correction</p></div>
    <div class="card"><i class="fa-solid fa-building-columns"></i><h3>Banking Services</h3><p>AEPS, DBT, Money Transfer</p></div>
    <div class="card"><i class="fa-solid fa-file-lines"></i><h3>Government Forms</h3><p>All Online Applications</p></div>
    <div class="card"><i class="fa-solid fa-graduation-cap"></i><h3>Education Services</h3><p>Scholarship, Exams</p></div>
    <div class="card"><i class="fa-solid fa-bolt"></i><h3>Bill Payments</h3><p>Electricity, Gas, Mobile</p></div>
  </div>
</section>

<section>
  <div class="stats">
    <div class="stat-box"><h3>5+</h3><p>Years Experience</p></div>
    <div class="stat-box"><h3>5000+</h3><p>Happy Customers</p></div>
    <div class="stat-box"><h3>25+</h3><p>Services</p></div>
    <div class="stat-box"><h3>100%</h3><p>Trusted Work</p></div>
  </div>
</section>

<section id="about">
  <h2 style="text-align:center;margin-bottom:20px">About Dake Multiservices</h2>
  <div class="about">
    <p>Dake Multiservices is an authorized Digital CSC Center operating under Digital India initiative. We provide fast, secure and transparent government and digital services to citizens with complete trust.</p>
  </div>
</section>

<section id="contact">
  <h2 style="text-align:center;margin-bottom:30px">Contact Us</h2>
  <div class="contact-grid">
    <div class="contact-box">
      <h3>Get in Touch</h3>
      <p><i class="fa-solid fa-location-dot"></i> Shree Ram Nagar, Near By Pawan Raka Hospital, Deshmukh Hotel, Parbhani, Maharashtra</p>
      <p><i class="fa-solid fa-phone"></i> +91 9890928417</p>
      <p><i class="fa-solid fa-envelope"></i> dakemultiservices@gmail.com</p>
      <a class="btn" style="margin-top:15px;display:inline-block" href="https://www.google.com/maps/search/?api=1&query=Shree+Ram+Nagar+Parbhani" target="_blank">Get Direction</a>
    </div>
    <div class="contact-form">
      <h3>Send Enquiry</h3>
      <input type="text" placeholder="Your Name" />
      <input type="email" placeholder="Your Email" />
      <textarea rows="4" placeholder="Your Message"></textarea>
      <button class="btn">Submit</button>
    </div>
  </div>
</section>

<footer>
  <p>© 2026 Dake Multiservices | Digital CSC Center</p>
</footer>

<a class="whatsapp" href="https://wa.me/919890928417" target="_blank"><i class="fa-brands fa-whatsapp"></i></a>

<script>
  function toggleLang(){
    const en = document.querySelectorAll('[id$="-en"]');
    const mr = document.querySelectorAll('[id$="-mr"]');
    en.forEach(e=>e.style.display = e.style.display==='none'?'block':'none');
    mr.forEach(m=>m.style.display = m.style.display==='none'?'block':'none');
  }
</script>
</body>
</html>
