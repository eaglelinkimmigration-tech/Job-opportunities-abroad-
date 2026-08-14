<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Prime Digital Services | Websites, CVs & Digital Solutions</title>

<meta name="description" content="Prime Digital Services provides professional websites, CVs, cover letters, graphic design, social media services and tech support.">

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Arial,Helvetica,sans-serif;
scroll-behavior:smooth;
}

body{
background:#f5f8fc;
color:#172033;
line-height:1.6;
}

a{
text-decoration:none;
}

header{
background:linear-gradient(135deg,#06183d,#087bd1);
color:white;
padding:18px 7%;
display:flex;
align-items:center;
justify-content:space-between;
position:sticky;
top:0;
z-index:1000;
box-shadow:0 3px 15px rgba(0,0,0,.2);
}

.logo{
font-size:22px;
font-weight:bold;
}

.logo span{
color:#5cc8ff;
}

nav{
display:flex;
gap:25px;
}

nav a{
color:white;
font-weight:bold;
font-size:15px;
}

.menu{
display:none;
font-size:28px;
cursor:pointer;
}

/* HERO */

.hero{
min-height:650px;
background:
linear-gradient(rgba(3,18,50,.85),rgba(3,18,50,.8)),
url("https://images.unsplash.com/photo-1556761175-b413da4baf72?auto=format&fit=crop&w=1600&q=80");
background-size:cover;
background-position:center;
display:flex;
align-items:center;
justify-content:center;
text-align:center;
color:white;
padding:70px 20px;
}

.hero-content{
max-width:850px;
}

.hero h1{
font-size:55px;
line-height:1.1;
margin-bottom:20px;
}

.hero h1 span{
color:#55c7ff;
}

.hero p{
font-size:21px;
margin-bottom:30px;
}

.buttons{
display:flex;
justify-content:center;
gap:15px;
flex-wrap:wrap;
}

.btn{
display:inline-block;
padding:15px 28px;
border-radius:8px;
font-weight:bold;
transition:.3s;
}

.primary{
background:#087bd1;
color:white;
}

.primary:hover{
background:#055da3;
}

.secondary{
background:white;
color:#06183d;
}

.secondary:hover{
background:#e7f4ff;
}

/* SECTIONS */

section{
padding:75px 7%;
}

.section-title{
text-align:center;
max-width:750px;
margin:0 auto 45px;
}

.section-title h2{
font-size:36px;
color:#06183d;
margin-bottom:12px;
}

.section-title p{
color:#64748b;
}

/* ABOUT */

.about{
display:grid;
grid-template-columns:1fr 1fr;
gap:50px;
align-items:center;
}

.about-image{
height:400px;
border-radius:20px;
background:
linear-gradient(rgba(6,24,61,.3),rgba(6,24,61,.3)),
url("https://images.unsplash.com/photo-1553877522-43269d4ea984?auto=format&fit=crop&w=1000&q=80");
background-size:cover;
background-position:center;
}

.about-text h2{
font-size:36px;
color:#06183d;
margin-bottom:18px;
}

.about-text p{
margin-bottom:18px;
color:#526074;
}

.check{
margin:12px 0;
font-weight:bold;
}

/* SERVICES */

.services{
display:grid;
grid-template-columns:repeat(3,1fr);
gap:22px;
}

.service-card{
background:white;
padding:30px 25px;
border-radius:16px;
text-align:center;
box-shadow:0 5px 20px rgba(0,0,0,.07);
transition:.3s;
border-top:4px solid #087bd1;
}

.service-card:hover{
transform:translateY(-7px);
box-shadow:0 10px 30px rgba(0,0,0,.12);
}

.service-icon{
font-size:48px;
margin-bottom:15px;
}

.service-card h3{
color:#06183d;
margin-bottom:10px;
font-size:21px;
}

.service-card p{
color:#64748b;
}

/* WHY */

.why{
background:#06183d;
color:white;
}

.why .section-title h2{
color:white;
}

.why .section-title p{
color:#b9c9dc;
}

.why-grid{
display:grid;
grid-template-columns:repeat(4,1fr);
gap:20px;
}

.why-card{
text-align:center;
padding:25px;
}

.why-card .icon{
font-size:42px;
margin-bottom:12px;
}

.why-card h3{
margin-bottom:8px;
}

/* PROCESS */

.process{
display:grid;
grid-template-columns:repeat(4,1fr);
gap:20px;
}

.step{
text-align:center;
position:relative;
}

.number{
width:55px;
height:55px;
margin:0 auto 15px;
background:#087bd1;
color:white;
border-radius:50%;
display:flex;
align-items:center;
justify-content:center;
font-size:22px;
font-weight:bold;
}

.step h3{
color:#06183d;
margin-bottom:8px;
}

.step p{
color:#64748b;
}

/* PRICING */

.pricing{
display:grid;
grid-template-columns:repeat(3,1fr);
gap:25px;
}

.price-card{
background:white;
border-radius:18px;
padding:35px 25px;
text-align:center;
box-shadow:0 5px 20px rgba(0,0,0,.08);
}

.price-card.featured{
border:3px solid #087bd1;
transform:scale(1.03);
}

.price-card h3{
color:#06183d;
font-size:23px;
}

.price{
font-size:38px;
font-weight:bold;
color:#087bd1;
margin:18px 0;
}

.price-card ul{
list-style:none;
margin-bottom:25px;
}

.price-card li{
margin:10px 0;
color:#526074;
}

/* PORTFOLIO */

.portfolio{
display:grid;
grid-template-columns:repeat(3,1fr);
gap:20px;
}

.portfolio-card{
background:white;
border-radius:15px;
overflow:hidden;
box-shadow:0 5px 20px rgba(0,0,0,.08);
}

.portfolio-card img{
width:100%;
height:220px;
object-fit:cover;
}

.portfolio-card div{
padding:20px;
}

.portfolio-card h3{
color:#06183d;
}

/* FORM */

.form-section{
background:#eef5fb;
}

.form-box{
max-width:850px;
margin:auto;
background:white;
padding:40px;
border-radius:20px;
box-shadow:0 8px 30px rgba(0,0,0,.1);
}

.form-box h2{
text-align:center;
color:#06183d;
margin-bottom:10px;
}

.form-intro{
text-align:center;
color:#64748b;
margin-bottom:25px;
}

label{
display:block;
font-weight:bold;
margin:18px 0 7px;
}

input,select,textarea{
width:100%;
padding:15px;
border:1px solid #d1dae5;
border-radius:9px;
font-size:16px;
outline:none;
}

input:focus,
select:focus,
textarea:focus{
border-color:#087bd1;
box-shadow:0 0 0 3px rgba(8,123,209,.1);
}

textarea{
min-height:190px;
resize:vertical;
}

.submit{
width:100%;
border:none;
background:#087bd1;
color:white;
padding:17px;
font-size:18px;
font-weight:bold;
border-radius:9px;
margin-top:25px;
cursor:pointer;
}

.submit:hover{
background:#055da3;
}

.success{
display:none;
background:#e8f8ef;
color:#16733b;
padding:15px;
margin-top:15px;
border-radius:8px;
text-align:center;
}

/* CONTACT */

.contact{
background:#06183d;
color:white;
text-align:center;
}

.contact h2{
font-size:36px;
margin-bottom:15px;
}

.contact p{
color:#c4d0df;
margin-bottom:10px;
}

.whatsapp{
display:inline-block;
margin-top:20px;
padding:15px 30px;
background:#25d366;
color:white;
border-radius:8px;
font-weight:bold;
}

/* FOOTER */

footer{
background:#030d21;
color:#aebbd0;
text-align:center;
padding:30px 20px;
}

footer strong{
color:white;
}

/* MOBILE */

@media(max-width:850px){

nav{
display:none;
position:absolute;
top:65px;
left:0;
width:100%;
background:#06183d;
flex-direction:column;
padding:25px;
}

nav.active{
display:flex;
}

.menu{
display:block;
}

.hero h1{
font-size:39px;
}

.hero p{
font-size:18px;
}

.about{
grid-template-columns:1fr;
}

.services{
grid-template-columns:1fr 1fr;
}

.why-grid{
grid-template-columns:1fr 1fr;
}

.process{
grid-template-columns:1fr 1fr;
}

.pricing{
grid-template-columns:1fr;
}

.price-card.featured{
transform:none;
}

.portfolio{
grid-template-columns:1fr;
}

}

@media(max-width:550px){

section{
padding:55px 5%;
}

.services{
grid-template-columns:1fr;
}

.why-grid{
grid-template-columns:1fr;
}

.process{
grid-template-columns:1fr;
}

.form-box{
padding:25px 18px;
}

.hero{
min-height:600px;
}

.hero h1{
font-size:34px;
}

.section-title h2{
font-size:30px;
}

}

/* FLOATING WHATSAPP */

.float-whatsapp{
position:fixed;
right:20px;
bottom:20px;
width:60px;
height:60px;
background:#25d366;
color:white;
border-radius:50%;
display:flex;
align-items:center;
justify-content:center;
font-size:30px;
box-shadow:0 5px 20px rgba(0,0,0,.25);
z-index:999;
}

</style>
</head>

<body>

<!-- HEADER -->

<header>

<div class="logo">
PRIME <span>DIGITAL</span>
</div>

<div class="menu" onclick="toggleMenu()">☰</div>

<nav id="nav">
<a href="#home">Home</a>
<a href="#about">About</a>
<a href="#services">Services</a>
<a href="#pricing">Pricing</a>
<a href="#portfolio">Portfolio</a>
<a href="#contact">Contact</a>
</nav>

</header>


<!-- HERO -->

<section class="hero" id="home">

<div class="hero-content">

<h1>
Your Vision.<br>
<span>Our Digital Expertise.</span>
</h1>

<p>
Professional websites, CVs, designs and digital solutions
for individuals and businesses.
</p>

<div class="buttons">

<a href="#request" class="btn primary">
Get Started
</a>

<a href="#services" class="btn secondary">
View Services
</a>

</div>

</div>

</section>


<!-- ABOUT -->

<section id="about">

<div class="about">

<div class="about-image"></div>

<div class="about-text">

<h2>About Prime Digital Services</h2>

<p>
Prime Digital Services is a digital solutions business helping
individuals and businesses build a strong and professional
presence online.
</p>

<p>
Whether you need a website for your business, a professional
CV for your next job application, or attractive graphics for
your brand, we're here to help.
</p>

<div class="check">✓ Professional work</div>
<div class="check">✓ Affordable prices</div>
<div class="check">✓ Fast delivery</div>
<div class="check">✓ Friendly customer support</div>

</div>

</div>

</section>


<!-- SERVICES -->

<section id="services">

<div class="section-title">

<h2>Our Services</h2>

<p>
Choose the service you need and tell us exactly what you want.
</p>

</div>


<div class="services">

<div class="service-card">

<div class="service-icon">🌐</div>

<h3>Website Creation</h3>

<p>
Professional, mobile-friendly websites for businesses,
organizations and individuals.
</p>

</div>


<div class="service-card">

<div class="service-icon">📄</div>

<h3>Professional CVs</h3>

<p>
Modern, professional CVs designed to present your skills
and experience clearly.
</p>

</div>


<div class="service-card">

<div class="service-icon">✉️</div>

<h3>Cover Letters</h3>

<p>
Professional cover letters customized for your job applications.
</p>

</div>


<div class="service-card">

<div class="service-icon">🎨</div>

<h3>Graphic Design</h3>

<p>
Logos, posters, flyers, banners and other business designs.
</p>

</div>


<div class="service-card">

<div class="service-icon">📱</div>

<h3>Social Media</h3>

<p>
Social media graphics and digital content to promote your business.
</p>

</div>


<div class="service-card">

<div class="service-icon">💻</div>

<h3>Tech Support</h3>

<p>
Help with websites, digital tools and other technology needs.
</p>

</div>

</div>

</section>


<!-- WHY CHOOSE US -->

<section class="why">

<div class="section-title">

<h2>Why Choose Us?</h2>

<p>
We focus on quality, simplicity and customer satisfaction.
</p>

</div>

<div class="why-grid">

<div class="why-card">

<div class="icon">⚡</div>

<h3>Fast</h3>

<p>We value your time and work efficiently.</p>

</div>


<div class="why-card">

<div class="icon">💰</div>

<h3>Affordable</h3>

<p>Professional services at reasonable prices.</p>

</div>


<div class="why-card">

<div class="icon">⭐</div>

<h3>Professional</h3>

<p>We create clean and modern digital solutions.</p>

</div>


<div class="why-card">

<div class="icon">🤝</div>

<h3>Reliable</h3>

<p>We communicate clearly and support our customers.</p>

</div>

</div>

</section>


<!-- HOW IT WORKS -->

<section>

<div class="section-title">

<h2>How It Works</h2>

<p>Getting started is simple.</p>

</div>


<div class="process">

<div class="step">

<div class="number">1</div>

<h3>Choose a Service</h3>

<p>Select what you need.</p>

</div>


<div class="step">

<div class="number">2</div>

<h3>Tell Us What You Need</h3>

<p>Give us your requirements and details.</p>

</div>


<div class="step">

<div class="number">3</div>

<h3>We Get to Work</h3>

<p>We create your digital solution.</p>

</div>


<div class="step">

<div class="number">4</div>

<h3>Receive Your Work</h3>

<p>Review and receive your completed project.</p>

</div>

</div>

</section>


<!-- PRICING -->

<section id="pricing">

<div class="section-title">

<h2>Simple Pricing</h2>

<p>
Starting prices. Final pricing depends on your requirements.
</p>

</div>


<div class="pricing">

<div class="price-card">

<h3>CV Package</h3>

<div class="price">
KSh 500+
</div>

<ul>

<li>✓ Professional CV</li>

<li>✓ Modern design</li>

<li>✓ Mobile/PDF ready</li>

</ul>

<a href="#request" class="btn primary">
Order Now
</a>

</div>


<div class="price-card featured">

<h3>Business Website</h3>

<div class="price">
KSh 3,500+
</div>

<ul>

<li>✓ Mobile-friendly</li>

<li>✓ Professional design</li>

<li>✓ WhatsApp contact</li>

<li>✓ Customer enquiry form</li>

</ul>

<a href="#request" class="btn primary">
Get Started
</a>

</div>


<div class="price-card">

<h3>Design Package</h3>

<div class="price">
KSh 1,000+
</div>

<ul>

<li>✓ Posters</li>

<li>✓ Social media designs</li>

<li>✓ Business graphics</li>

</ul>

<a href="#request" class="btn primary">
Order Now
</a>

</div>

</div>

</section>


<!-- PORTFOLIO -->

<section id="portfolio">

<div class="section-title">

<h2>Our Work</h2>

<p>
A few examples of what we can create for you.
</p>

</div>


<div class="portfolio">

<div class="portfolio-card">

<img src="https://images.unsplash.com/photo-1460925895917-afdab827c52f?auto=format&fit=crop&w=1000&q=80">

<div>

<h3>Business Websites</h3>

<p>Modern websites designed to help businesses grow online.</p>

</div>

</div>


<div class="portfolio-card">

<img src="https://images.unsplash.com/photo-1586281380349-632531db7ed4?auto=format&fit=crop&w=1000&q=80">

<div>

<h3>Professional CVs</h3>

<p>Clean and professional CV designs.</p>

</div>

</div>


<div class="portfolio-card">

<img src="https://images.unsplash.com/photo-1561070791-2526d30994b5?auto=format&fit=crop&w=1000&q=80">

<div>

<h3>Graphic Design</h3>

<p>Creative designs for brands and businesses.</p>

</div>

</div>

</div>

</section>


<!-- REQUEST FORM -->

<section class="form-section" id="request">

<div class="section-title">

<h2>Request a Service</h2>

<p>
Tell us what you need. Your request will be prepared for WhatsApp.
</p>

</div>


<div class="form-box">

<form id="contactForm">


<label>
Choose a Service
</label>

<select id="service" required>

<option value="">
-- Select a service --
</option>

<option>🌐 Website Creation</option>

<option>📄 Professional CV</option>

<option>✉️ Cover Letter</option>

<option>🎨 Logo / Poster Design</option>

<option>📱 Social Media Design</option>

<option>💻 Tech Support</option>

<option>🔧 Website Maintenance</option>

<option>Other</option>

</select>


<label>
Your Name
</label>

<input
type="text"
id="name"
placeholder="Enter your full name"
required
>


<label>
Your WhatsApp Number
</label>

<input
type="tel"
id="phone"
placeholder="Enter your WhatsApp number"
required
>


<label>
Tell Us More About What You Need
</label>

<textarea
id="details"
placeholder="Describe exactly what you need. You can include your requirements, preferred design, number of pages, deadline, budget, colors, examples you like, or any other useful information."
required
></textarea>


<button type="submit" class="submit">
SUBMIT
</button>


<div class="success" id="success">

Your request is being prepared. WhatsApp will open shortly...

</div>


</form>

</div>

</section>


<!-- CONTACT -->

<section class="contact" id="contact">

<h2>Let's Work Together</h2>

<p>
Have a project in mind? Contact Prime Digital Services today.
</p>

<p>
📱 WhatsApp: +254 119 619 620
</p>

<a
class="whatsapp"
href="https://wa.me/254119619620"
target="_blank"
>
💬 Chat With Us on WhatsApp
</a>

</section>


<!-- FOOTER -->

<footer>

<p>
<strong>PRIME DIGITAL SERVICES</strong>
</p>

<p>
Your Vision • Our Digital Expertise
</p>

<p>
Websites • CVs • Designs • Social Media • Tech Support
</p>

<p>
© 2026 Prime Digital Services. All Rights Reserved.
</p>

</footer>


<!-- FLOATING WHATSAPP -->

<a
class="float-whatsapp"
href="https://wa.me/254119619620"
target="_blank"
>
💬
</a>


<script>

function toggleMenu(){

document
.getElementById("nav")
.classList
.toggle("active");

}


document
.getElementById("contactForm")
.addEventListener("submit",function(event){

event.preventDefault();


const service =
document.getElementById("service").value;

const name =
document.getElementById("name").value;

const phone =
document.getElementById("phone").value;

const details =
document.getElementById("details").value;


const message =
`NEW CUSTOMER REQUEST

Service:
${service}

Customer Name:
${name}

Customer WhatsApp:
${phone}

What the customer needs:
${details}

Sent from Prime Digital Services website.`;


const whatsappNumber =
"254119619620";


const whatsappURL =
"https://wa.me/" +
whatsappNumber +
"?text=" +
encodeURIComponent(message);


document
.getElementById("success")
.style
.display="block";


setTimeout(function(){

window.location.href =
whatsappURL;

},800);

});

</script>

</body>
</html>
