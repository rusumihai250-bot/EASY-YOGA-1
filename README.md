<!DOCTYPE html>
<html lang="ro">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Easy Yoga</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">

<style>
body {
    margin: 0;
    font-family: 'Poppins', sans-serif;
    background: #f4f7f4;
    color: #333;
}

/* HEADER */
header {
    background: linear-gradient(rgba(0,0,0,0.4), rgba(0,0,0,0.4)),
    url('https://images.unsplash.com/photo-1506126613408-eca07ce68773') center/cover;
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
    color: white;
}

header h1 {
    font-size: 60px;
    margin: 0;
    animation: fadeIn 2s ease;
}

header p {
    font-size: 22px;
    margin-top: 10px;
    animation: fadeIn 3s ease;
}

button {
    padding: 15px 30px;
    background: #2e7d32;
    color: white;
    border: none;
    font-size: 18px;
    margin-top: 20px;
    border-radius: 30px;
    cursor: pointer;
    transition: 0.3s;
}

button:hover {
    background: #1b5e20;
    transform: scale(1.05);
}

/* SECTIONS */
section {
    padding: 70px 20px;
    text-align: center;
}

/* SERVICES */
.services {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 20px;
}

.card {
    background: white;
    padding: 30px;
    width: 280px;
    border-radius: 20px;
    box-shadow: 0 10px 25px rgba(0,0,0,0.1);
    transition: 0.3s;
}

.card:hover {
    transform: translateY(-10px);
}

/* CONTACT */
.contact {
    background: #e8f5e9;
}

/* FOOTER */
footer {
    background: #2e7d32;
    color: white;
    padding: 20px;
}

/* ANIMATION */
@keyframes fadeIn {
    from {opacity: 0; transform: translateY(20px);}
    to {opacity: 1; transform: translateY(0);}
}

/* MOBILE */
@media (max-width: 768px) {
    header h1 {
        font-size: 40px;
    }

    .services {
        flex-direction: column;
        align-items: center;
    }
}
</style>
</head>

<body>

<header>
    <div>
        <h1>EASY YOGA</h1>
        <p>Гармония тела, разума и энергии</p>
        <button onclick="window.location.href='https://wa.me/37369404887'">
            Записаться
        </button>
    </div>
</header>

<section>
    <h2>О нас</h2>
    <p>Мы создаём пространство спокойствия, энергии и внутреннего баланса через йогу и медитацию</p>
</section>

<section>
    <h2>Наши занятия</h2>
    <div class="services">
        <div class="card">
            <h3>Йога</h3>
            <p>Подходит для любого уровня подготовки</p>
        </div>

        <div class="card">
            <h3>Медитация</h3>
            <p>Глубокое расслабление и концентрация</p>
        </div>

        <div class="card">
            <h3>Растяжка</h3>
            <p>Гибкость и здоровье тела</p>
        </div>
    </div>
</section>

<section class="contact">
    <h2>Контакты</h2>
    <p>📍 Кишинёв</p>
    <p>📞 +37369404887</p>
    <p>Instagram: easy_yoga33</p>
</section>

<footer>
    <p>© EASY YOGA | Все права защищены</p>
</footer>

</body>
</html>
