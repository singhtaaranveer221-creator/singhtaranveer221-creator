<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Taranveer Singh | Portfolio</title>

    <!-- CSS -->
    <link rel="stylesheet" href="style.css">

    <!-- Font Awesome -->
    <link rel="stylesheet"
    href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

    <!-- Google Font -->
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">
</head>
<body>

<!-- ================= NAVBAR ================= -->

<header>
    <nav>
        <h2 class="logo">Taranveer.</h2>

        <ul class="nav-links">
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#skills">Skills</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>

        <div class="menu-btn">
            <i class="fas fa-bars"></i>
        </div>
    </nav>
</header>

<!-- ================= HERO ================= -->

<section class="hero" id="home">

    <div class="hero-text">

        <h3>Hello, I'm</h3>

        <h1>Taranveer Singh</h1>

        <h2><span class="typing"></span></h2>

        <p>
            Computer Science student passionate about Linux,
            DevOps, Cloud Computing and building amazing projects.
        </p>

        <div class="buttons">

            <a href="#contact" class="btn">
                Contact Me
            </a>

            <a href="#projects" class="btn btn-outline">
                View Projects
            </a>

        </div>

    </div>

    <div class="hero-image">

        <img src="profile.png" alt="Profile">

    </div>

</section>

<!-- ================= ABOUT ================= -->

<section class="about" id="about">

<h2 class="section-title">About Me</h2>

<div class="about-container">

<div class="about-text">

<p>

Hi! I'm <strong>Taranveer Singh</strong>, a Computer Science
student from Haryana.

I enjoy solving programming problems,
working with Linux, learning DevOps,
and creating responsive websites.

Currently I'm improving my skills in
Docker, Git, GitHub, Nginx and Cloud Computing.

My goal is to become a skilled DevOps Engineer
and contribute to Open Source.

</p>

</div>

</div>

</section>

<!-- ================= SKILLS ================= -->

<section id="skills">

<h2 class="section-title">Skills</h2>

<div class="skills-container">

<div class="skill-card">
<i class="fab fa-cuttlefish"></i>
<h3>C</h3>
</div>

<div class="skill-card">
<i class="fas fa-code"></i>
<h3>C++</h3>
</div>

<div class="skill-card">
<i class="fab fa-html5"></i>
<h3>HTML</h3>
</div>

<div class="skill-card">
<i class="fab fa-css3-alt"></i>
<h3>CSS</h3>
</div>

<div class="skill-card">
<i class="fab fa-js"></i>
<h3>JavaScript</h3>
</div>

<div class="skill-card">
<i class="fab fa-git-alt"></i>
<h3>Git</h3>
</div>

<div class="skill-card">
<i class="fab fa-github"></i>
<h3>GitHub</h3>
</div>

<div class="skill-card">
<i class="fab fa-linux"></i>
<h3>Linux</h3>
</div>

</div>

</section>

<!-- ================= PROJECTS ================= -->

<section id="projects">

<h2 class="section-title">Projects</h2>

<div class="project-container">

<div class="project-card">

<h3>Portfolio Website</h3>

<p>
A responsive portfolio made using HTML, CSS and JavaScript.
</p>

<a href="#">View Project</a>

</div>

<div class="project-card">

<h3>Linux Notes</h3>

<p>
A collection of useful Linux commands and practice exercises.
</p>

<a href="#">View Project</a>

</div>

<div class="project-card">

<h3>DevOps Journey</h3>

<p>
Documenting my learning in Git, Docker, Linux and Cloud.
</p>

<a href="#">View Project</a>

</div>

</div>

</section>

<!-- ================= CONTACT ================= -->

<section id="contact">

<h2 class="section-title">Contact Me</h2>

<div class="contact-container">

<a href="https://github.com/singhtaranveer221-creator" target="_blank">
<i class="fab fa-github"></i>
GitHub
</a>

<a href="#">
<i class="fab fa-linkedin"></i>
LinkedIn
</a>

<a href="mailto:your@email.com">
<i class="fas fa-envelope"></i>
Email
</a>

</div>

</section>

<!-- ================= FOOTER ================= -->

<footer>

<p>
© 2026 Taranveer Singh • Designed with ❤️ using HTML, CSS & JavaScript
</p>

</footer>

<!-- JavaScript -->

<script src="https://cdn.jsdelivr.net/npm/typed.js@2.0.12"></script>

<script src="script.js"></script>

</body>
</html>
/* ===========================
   GOOGLE FONT
=========================== */

@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700;800&display=swap');

*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    scroll-behavior:smooth;
}

body{
    font-family:'Poppins',sans-serif;
    background:#0f172a;
    color:#fff;
    overflow-x:hidden;
}

/* Scrollbar */

::-webkit-scrollbar{
    width:10px;
}

::-webkit-scrollbar-track{
    background:#111827;
}

::-webkit-scrollbar-thumb{
    background:#38bdf8;
    border-radius:20px;
}

::-webkit-scrollbar-thumb:hover{
    background:#0ea5e9;
}

/* ===========================
   NAVBAR
=========================== */

header{
    position:fixed;
    width:100%;
    top:0;
    left:0;
    z-index:1000;
    background:rgba(15,23,42,.8);
    backdrop-filter:blur(12px);
}

nav{
    width:90%;
    margin:auto;
    height:80px;

    display:flex;
    justify-content:space-between;
    align-items:center;
}

.logo{
    font-size:30px;
    color:#38bdf8;
    cursor:pointer;
}

.nav-links{
    display:flex;
    list-style:none;
}

.nav-links li{
    margin-left:35px;
}

.nav-links a{
    text-decoration:none;
    color:white;
    font-weight:500;
    transition:.3s;
}

.nav-links a:hover{
    color:#38bdf8;
}

.menu-btn{
    display:none;
    font-size:28px;
    cursor:pointer;
}

/* ===========================
   HERO
=========================== */

.hero{

    width:90%;
    margin:auto;

    min-height:100vh;

    display:flex;
    justify-content:space-between;
    align-items:center;
}

.hero-text{
    width:55%;
}

.hero-text h3{
    font-size:24px;
    color:#38bdf8;
}

.hero-text h1{

    font-size:65px;
    margin:15px 0;

}

.hero-text h2{

    color:#94a3b8;
    margin-bottom:20px;

}

.hero-text p{

    font-size:18px;
    line-height:1.8;
    color:#cbd5e1;

}

.hero-image{

    width:40%;
    display:flex;
    justify-content:center;

}

.hero-image img{

    width:380px;
    border-radius:50%;
    border:6px solid #38bdf8;
    box-shadow:0 0 40px rgba(56,189,248,.45);
    animation:float 4s ease-in-out infinite;

}

@keyframes float{

0%{
transform:translateY(0);
}

50%{
transform:translateY(-20px);
}

100%{
transform:translateY(0);
}

}

/* ===========================
   BUTTONS
=========================== */

.buttons{

    margin-top:35px;

}

.btn{

    display:inline-block;
    padding:14px 34px;

    background:#38bdf8;

    color:#fff;

    text-decoration:none;

    border-radius:50px;

    margin-right:20px;

    transition:.4s;

}

.btn:hover{

transform:translateY(-6px);

box-shadow:0 0 20px #38bdf8;

}

.btn-outline{

background:transparent;

border:2px solid #38bdf8;

}
/* ===========================
   BACKGROUND EFFECT
=========================== */

body::before{
    content:"";
    position:fixed;
    top:-200px;
    left:-200px;
    width:500px;
    height:500px;
    background:#38bdf8;
    opacity:.08;
    filter:blur(140px);
    border-radius:50%;
    z-index:-2;
}

body::after{
    content:"";
    position:fixed;
    bottom:-200px;
    right:-200px;
    width:500px;
    height:500px;
    background:#8b5cf6;
    opacity:.08;
    filter:blur(140px);
    border-radius:50%;
    z-index:-2;
}

/* ===========================
   SECTIONS
=========================== */

section{
    padding:100px 8%;
}

.section-title{

    text-align:center;
    font-size:42px;
    margin-bottom:60px;
    color:#38bdf8;
    position:relative;

}

.section-title::after{

    content:"";
    position:absolute;
    width:80px;
    height:4px;
    background:#38bdf8;
    bottom:-12px;
    left:50%;
    transform:translateX(-50%);
    border-radius:20px;

}

/* ===========================
   ABOUT
=========================== */

.about-container{

    display:flex;
    justify-content:center;
    align-items:center;

}

.about-text{

    max-width:850px;

    background:rgba(255,255,255,.05);

    padding:40px;

    border-radius:20px;

    backdrop-filter:blur(12px);

    border:1px solid rgba(255,255,255,.08);

    transition:.4s;

}

.about-text:hover{

    transform:translateY(-8px);

    box-shadow:0 0 25px rgba(56,189,248,.3);

}

.about-text p{

    font-size:18px;

    line-height:1.9;

    color:#d1d5db;

}

/* ===========================
   SKILLS
=========================== */

.skills-container{

    display:grid;

    grid-template-columns:repeat(auto-fit,minmax(180px,1fr));

    gap:30px;

}

.skill-card{

    background:#111827;

    padding:35px;

    border-radius:20px;

    text-align:center;

    transition:.4s;

    cursor:pointer;

}

.skill-card:hover{

    transform:translateY(-10px);

    box-shadow:0 0 30px rgba(56,189,248,.4);

}

.skill-card i{

    font-size:55px;

    color:#38bdf8;

    margin-bottom:20px;

}

.skill-card h3{

    font-size:22px;

    color:white;

}
/* ===========================
   ABOUT SECTION
=========================== */

section{
    padding:100px 10%;
}

.section-title{
    text-align:center;
    font-size:40px;
    margin-bottom:60px;
    color:#38bdf8;
    position:relative;
}

.section-title::after{
    content:"";
    width:90px;
    height:4px;
    background:#38bdf8;
    position:absolute;
    left:50%;
    bottom:-12px;
    transform:translateX(-50%);
    border-radius:20px;
}

.about-container{
    display:flex;
    justify-content:center;
    align-items:center;
}

.about-text{
    max-width:900px;
    background:rgba(255,255,255,.05);
    padding:35px;
    border-radius:20px;
    backdrop-filter:blur(10px);
    border:1px solid rgba(255,255,255,.1);
    transition:.4s;
}

.about-text:hover{
    transform:translateY(-10px);
    box-shadow:0 10px 30px rgba(56,189,248,.25);
}

.about-text p{
    line-height:1.9;
    font-size:18px;
    color:#d1d5db;
}

/* ===========================
   SKILLS
=========================== */

.skills-container{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(180px,1fr));
    gap:30px;
}

.skill-card{
    background:#111827;
    border-radius:18px;
    padding:35px;
    text-align:center;
    transition:.4s;
    border:1px solid rgba(255,255,255,.08);
}

.skill-card:hover{
    transform:translateY(-12px);
    box-shadow:0 0 25px rgba(56,189,248,.45);
}

.skill-card i{
    font-size:55px;
    color:#38bdf8;
    margin-bottom:18px;
}

.skill-card h3{
    font-size:22px;
    font-weight:600;
}

/* ===========================
   PROJECTS
=========================== */

.project-container{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(300px,1fr));
    gap:35px;
}

.project-card{
    background:#111827;
    padding:30px;
    border-radius:20px;
    transition:.4s;
    border:1px solid rgba(255,255,255,.08);
}

.project-card:hover{
    transform:translateY(-10px);
    box-shadow:0 0 30px rgba(56,189,248,.3);
}

.project-card h3{
    color:#38bdf8;
    margin-bottom:15px;
}

.project-card p{
    color:#d1d5db;
    line-height:1.7;
    margin-bottom:25px;
}

.project-card a{
    text-decoration:none;
    color:#38bdf8;
    font-weight:600;
}

.project-card a:hover{
    color:white;
}
// ===============================
// Typing Animation
// ===============================

var typed = new Typed(".typing", {
    strings: [
        "Computer Science Student",
        "Linux Enthusiast",
        "Future DevOps Engineer",
        "Web Developer",
        "Open Source Learner"
    ],
    typeSpeed: 80,
    backSpeed: 50,
    backDelay: 1500,
    loop: true
});


// ===============================
// Mobile Menu
// ===============================

const menuBtn = document.querySelector(".menu-btn");
const navLinks = document.querySelector(".nav-links");

menuBtn.addEventListener("click", () => {
    navLinks.classList.toggle("active");
});


// ===============================
// Close Menu After Clicking
// ===============================

document.querySelectorAll(".nav-links a").forEach(link => {

    link.addEventListener("click", () => {

        navLinks.classList.remove("active");

    });

});


// ===============================
// Navbar Background on Scroll
// ===============================

window.addEventListener("scroll", () => {

    const header = document.querySelector("header");

    if(window.scrollY > 80){

        header.style.background = "rgba(15,23,42,.95)";
        header.style.boxShadow = "0 5px 20px rgba(0,0,0,.3)";

    }

    else{

        header.style.background = "rgba(15,23,42,.8)";
        header.style.boxShadow = "none";

    }

});


// ===============================
// Active Navigation
// ===============================

const sections = document.querySelectorAll("section");
const navItems = document.querySelectorAll(".nav-links a");

window.addEventListener("scroll", () => {

    let current = "";

    sections.forEach(section => {

        const sectionTop = section.offsetTop - 120;

        if(pageYOffset >= sectionTop){

            current = section.getAttribute("id");

        }

    });

    navItems.forEach(link => {

        link.classList.remove("active");

        if(link.getAttribute("href") == "#" + current){

            link.classList.add("active");

        }

    });

});


// ===============================
// Reveal Animation
// ===============================

const revealElements = document.querySelectorAll(
".about, .skill-card, .project-card, .contact-container"
);

function reveal(){

    revealElements.forEach(el=>{

        const windowHeight = window.innerHeight;

        const top = el.getBoundingClientRect().top;

        if(top < windowHeight - 120){

            el.classList.add("show");

        }

    });

}

window.addEventListener("scroll", reveal);

reveal();


// ===============================
// Smooth Scroll
// ===============================

document.querySelectorAll('a[href^="#"]').forEach(anchor => {

    anchor.addEventListener("click", function(e){

        e.preventDefault();

        document.querySelector(this.getAttribute("href"))
        .scrollIntoView({

            behavior:"smooth"

        });

    });

});


// ===============================
// Hero Image Tilt Effect
// ===============================

const image = document.querySelector(".hero-image img");

image.addEventListener("mousemove",(e)=>{

    image.style.transform = "rotate(2deg) scale(1.03)";

});

image.addEventListener("mouseleave",()=>{

    image.style.transform = "rotate(0deg) scale(1)";

});


// ===============================
// Console Message 😄
// ===============================

console.log("%cWelcome to Taranveer's Portfolio 🚀",
"color:#38bdf8;font-size:22px;font-weight:bold;");
