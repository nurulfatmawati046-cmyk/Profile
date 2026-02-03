<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Nurul Fatmawati</title>
<meta name="description" content="Portfolio dan CV Online Development IT">

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">

<style>
*{
  margin:0;
  padding:0;
  box-sizing:border-box;
  font-family:'Poppins',sans-serif;
  scroll-behavior:smooth;
}

body{
  background:#0b0f1a;
  color:#fff;
  line-height:1.6;
  overflow-x:hidden;
}

/* ================= NAVBAR ================= */
nav{
  position:fixed;
  top:0;
  width:100%;
  background:rgba(0,0,0,0.9);
  display:flex;
  justify-content:space-between;
  align-items:center;
  padding:15px 40px;
  z-index:1000;
}

nav h2{ color:#00f7ff; }

nav ul{
  display:flex;
  list-style:none;
  gap:25px;
}

nav a{
  color:white;
  text-decoration:none;
  font-size:14px;
}

.menu-toggle{
  display:none;
  font-size:26px;
  cursor:pointer;
  color:#fff;
}

/* ================= SECTION ================= */
section{
  padding:100px 10%;
  scroll-margin-top:90px;
}

h2{
  text-align:center;
  margin-bottom:40px;
  color:#00f7ff;
}

/* ================= HERO ================= */
.hero{
  min-height:100vh;
  display:flex;
  align-items:center;
  justify-content:center;
  gap:60px;
  flex-wrap:wrap;
  padding-top:120px;
}

.avatar{
  width:240px;
  height:240px;
  border-radius:50%;
  background:linear-gradient(145deg,#00f7ff,#0088ff);
  display:flex;
  align-items:center;
  justify-content:center;
  font-size:110px;
  color:#000;
  box-shadow:0 0 40px #00f7ff;
}

.hero-text span{ color:#00f7ff; }

.btn{
  margin-top:20px;
  display:inline-block;
  padding:10px 20px;
  background:#00f7ff;
  color:#000;
  text-decoration:none;
  border-radius:6px;
  font-weight:bold;
}

/* ================= CONTENT ================= */
.timeline{max-width:800px;margin:auto;}
.item{
  margin-bottom:20px;
  padding:20px;
  background:#151b2d;
  border-left:4px solid #00f7ff;
  border-radius:6px;
}

.projects{
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
  gap:20px;
}

.card{
  background:#151b2d;
  padding:12px;
  border-radius:10px;
}

.card img{
  width:100%;
  border-radius:8px;
}

/* ================= CONTACT ================= */
.contact-icons{
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(180px,1fr));
  gap:18px;
}

.contact-item{
  background:#151b2d;
  padding:14px;
  border-radius:10px;
  text-decoration:none;
  color:#fff;
  display:flex;
  justify-content:center;
  gap:10px;
}

/* ================= FOOTER ================= */
footer{
  text-align:center;
  padding:25px;
  background:#000;
  color:#aaa;
}

/* ================= MEDIA QUERY ================= */
@media(max-width:768px){

  nav{
    padding:15px 20px;
  }

  .menu-toggle{
    display:block;
  }

  nav ul{
    position:absolute;
    top:65px;
    left:0;
    width:100%;
    background:#000;
    flex-direction:column;
    align-items:center;
    gap:20px;
    padding:25px 0;
    display:none;
  }

  nav ul.active{
    display:flex;
  }

  section{
    padding:80px 6%;
  }

  .hero{
    flex-direction:column;
    text-align:center;
  }

  .avatar{
    width:170px;
    height:170px;
    font-size:80px;
  }

  .projects{
    grid-template-columns:1fr;
  }

  .contact-icons{
    grid-template-columns:1fr;
  }
}
</style>
</head>

<body>

<nav>
  <h2>Nurul Fatmawati</h2>
  <div class="menu-toggle" onclick="toggleMenu()">☰</div>
  <ul id="menu">
    <li><a href="#about">About</a></li>
    <li><a href="#skills">Skills</a></li>
    <li><a href="#education">Education</a></li>
    <li><a href="#experience">Experience</a></li>
    <li><a href="#projects">Portfolio</a></li>
    <li><a href="#contact">Contact</a></li>
  </ul>
</nav>

<script>
function toggleMenu(){
  document.getElementById("menu").classList.toggle("active");
}
</script>

</body>
</html>
