<!DOCTYPE html>
<html lang="ru">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Елизавета Конева | Создание сайтов</title>

<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
scroll-behavior:smooth;
}

body{
font-family:Inter,sans-serif;
background:#f7f7f7;
color:#222;
}

body::before{
content:"";
position:fixed;
width:700px;
height:700px;
background:radial-gradient(circle,#dfefff 0%,transparent 70%);
top:-250px;
right:-150px;
z-index:-2;
animation:move 12s infinite alternate;
}

body::after{
content:"";
position:fixed;
width:600px;
height:600px;
background:radial-gradient(circle,#ffe7f0 0%,transparent 70%);
bottom:-250px;
left:-150px;
z-index:-2;
animation:move2 15s infinite alternate;
}

@keyframes move{
to{
transform:translate(-120px,100px);
}
}

@keyframes move2{
to{
transform:translate(120px,-80px);
}
}

header{
position:fixed;
top:20px;
left:50%;
transform:translateX(-50%);
width:min(1150px,94%);
padding:18px 40px;
background:rgba(255,255,255,.75);
backdrop-filter:blur(18px);
border-radius:18px;
box-shadow:0 10px 35px rgba(0,0,0,.08);
display:flex;
justify-content:space-between;
align-items:center;
z-index:100;
}

.logo{
font-size:24px;
font-weight:800;
}

nav a{
margin-left:25px;
text-decoration:none;
color:#555;
font-weight:600;
}

.hero{
min-height:100vh;
display:flex;
align-items:center;
justify-content:center;
padding:140px 8%;
gap:70px;
flex-wrap:wrap;
}

.hero img{
width:360px;
border-radius:30px;
box-shadow:0 25px 60px rgba(0,0,0,.15);
}

.hero-text{
max-width:620px;
}

.hero h1{
font-size:58px;
line-height:1.05;
margin-bottom:25px;
}

.hero p{
font-size:20px;
color:#666;
margin-bottom:35px;
}

.button{
display:inline-block;
padding:16px 34px;
background:#111;
color:white;
text-decoration:none;
border-radius:50px;
margin-right:15px;
transition:.3s;
}

.button:hover{
transform:translateY(-4px);
}

section{
padding:90px 8%;
}

.title{
font-size:42px;
margin-bottom:15px;
text-align:center;
}

.subtitle{
text-align:center;
color:#666;
max-width:750px;
margin:auto auto 55px;
}

.cards{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:25px;
}

.card{
background:white;
padding:35px;
border-radius:24px;
transition:.35s;
box-shadow:0 10px 30px rgba(0,0,0,.05);
}

.card:hover{
transform:translateY(-8px);
}

.card h3{
margin-bottom:15px;
}

.card p{
color:#666;
}

.about{
max-width:900px;
margin:auto;
background:white;
padding:50px;
border-radius:30px;
box-shadow:0 10px 35px rgba(0,0,0,.05);
font-size:18px;
line-height:1.8;
}

.steps{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
gap:25px;
}

.step{
background:white;
padding:30px;
border-radius:22px;
text-align:center;
box-shadow:0 8px 25px rgba(0,0,0,.05);
}

.step span{
font-size:40px;
display:block;
margin-bottom:15px;
}

.contacts{
text-align:center;
}

.contact-buttons{
margin-top:35px;
}

.contact-buttons a{
display:inline-block;
margin:10px;
padding:18px 34px;
border-radius:50px;
text-decoration:none;
font-weight:700;
background:#111;
color:white;
transition:.3s;
}

.contact-buttons a:hover{
transform:translateY(-4px);
}

footer{
padding:35px;
text-align:center;
color:#777;
}

@media(max-width:900px){

header nav{
display:none;
}

.hero h1{
font-size:42px;
}

.hero{
text-align:center;
}

.hero img{
width:280px;
}

}

</style>

</head>

<body>

<header>

<div class="logo">
Елизавета Конева
</div>

<nav>

<a href="#services">Услуги</a>

<a href="#about">Обо мне</a>

<a href="#contacts">Контакты</a>

</nav>

</header>

<section class="hero">

<img src="photo.jpg">

<div class="hero-text">

<h1>Создаю современные сайты для бизнеса и личных проектов</h1>

<p>

Здравствуйте!

Меня зовут Елизавета Конева.

Создаю современные сайты-визитки, лендинги и небольшие веб-проекты с красивым дизайном, адаптацией под мобильные устройства и удобной навигацией.

</p>

<a class="button" href="https://t.me/koneva_elizaveta">Telegram</a>

<a class="button" href="http://api.whatsapp.com/send?phone=79917494932">WhatsApp</a>

</div>

</section>

<section id="services">

<h2 class="title">Что я могу сделать</h2>

<p class="subtitle">

Каждый сайт создаётся индивидуально, с современным дизайном и адаптацией под любые устройства.

</p>

<div class="cards">

<div class="card">

<h3>💻 Сайт-визитка</h3>

<p>Стильный сайт для специалиста, компании или личного бренда.</p>

</div>

<div class="card">

<h3>🚀 Лендинг</h3>

<p>Продающая страница для услуги, товара или мероприятия.</p>

</div>

<div class="card">

<h3>🎨 Портфолио</h3>

<p>Красивый сайт для фотографа, дизайнера, музыканта или художника.</p>

</div>

<div class="card">

<h3>📱 Адаптивный дизайн</h3>

<p>Все сайты корректно работают на телефонах, планшетах и компьютерах.</p>

</div>

</div>

</section>

<section>

<h2 class="title">Как проходит работа</h2>

<div class="steps">

<div class="step">

<span>1️⃣</span>

Обсуждение проекта

</div>

<div class="step">

<span>2️⃣</span>

Создание дизайна

</div>

<div class="step">

<span>3️⃣</span>

Разработка сайта

</div>

<div class="step">

<span>4️⃣</span>

Публикация и поддержка

</div>

</div>

</section>

<section id="about">

<h2 class="title">Обо мне</h2>

<div class="about">

Я создаю современные сайты с упором на минимализм, скорость работы и удобство использования. Каждый проект разрабатывается индивидуально с учётом пожеланий клиента. Главная цель — сделать сайт, который выглядит профессионально, быстро загружается и помогает представить ваши услуги или бизнес в лучшем виде.

</div>

</section>

<section id="contacts" class="contacts">

<h2 class="title">Контакты</h2>

<p>

Если у вас есть идея проекта или появились вопросы — напишите мне.

</p>

<div class="contact-buttons">

<a href="https://t.me/koneva_elizaveta">
Telegram
</a>

<a href="http://api.whatsapp.com/send?phone=79917494932">
WhatsApp
</a>

</div>

</section>

<footer>

© 2026 Елизавета Конева

</footer>

</body>

</html>
