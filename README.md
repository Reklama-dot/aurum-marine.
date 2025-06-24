<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>AURUM MARINE — Custom Yacht Branding</title>
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@700&family=Montserrat:wght@400;600&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header class="hero">
    <img src="logo.png" alt="AURUM MARINE Logo" class="logo">
    <h1>AURUM MARINE</h1>
    <h2>Custom Yacht Branding</h2>
    <div class="contacts">
      <span>г. Конаково, Тверская область</span>
      <span>Тел: <a href="tel:89000178526">8 900 017-85-26</a></span>
      <span>Email: <a href="mailto:reklama.knk@gmail.com">reklama.knk@gmail.com</a></span>
    </div>
    <nav>
      <ul class="menu">
        <li><a href="#">Главная</a></li>
        <li><a href="#">Услуги</a></li>
        <li><a href="#">Портфолио</a></li>
        <li><a href="#">Контакты</a></li>
      </ul>
    </nav>
  </header>
  <main>
    <section class="about">
      <h3>Премиальный брендинг яхт и катеров</h3>
      <p>Создаём уникальный стиль для вашего судна — от разработки дизайна до профессионального нанесения.</p>
    </section>
    <section class="services">
      <h3>Наши услуги</h3>
      <div class="service-list">
        <div class="service-item">
          <span class="icon">⛵</span>
          <h4>Брендирование яхт</h4>
          <p>Эксклюзивные решения для вашего судна.</p>
        </div>
        <div class="service-item">
          <span class="icon">🎨</span>
          <h4>Дизайн и макетирование</h4>
          <p>Премиальные макеты и визуализация.</p>
        </div>
        <div class="service-item">
          <span class="icon">🛠️</span>
          <h4>Профессиональное нанесение</h4>
          <p>Гарантия качества и долговечности.</p>
        </div>
      </div>
    </section>
    <section class="cta">
      <h3>Оставьте заявку</h3>
      <form>
        <input type="text" placeholder="Ваше имя" required>
        <input type="tel" placeholder="Телефон" required>
        <input type="email" placeholder="Email" required>
        <button type="submit">Отправить</button>
      </form>
    </section>
  </main>
  <footer>
    <div class="footer-contacts">
      <span>г. Конаково, Тверская область</span>
      <span>Тел: <a href="tel:89000178526">8 900 017-85-26</a></span>
      <span>Email: <a href="mailto:reklama.knk@gmail.com">reklama.knk@gmail.com</a></span>
    </div>
    <div class="copyright">
      © 2024 AURUM MARINE. Все права защищены.
    </div>
  </footer>
</body>
</html> 
body {
  background: #181d23;
  color: #d4af37;
  font-family: 'Montserrat', Arial, sans-serif;
  margin: 0;
  padding: 0;
}

.hero {
  text-align: center;
  padding: 60px 20px 40px 20px;
  background: #181d23;
}

.logo {
  width: 180px;
  margin-bottom: 20px;
}

h1 {
  font-family: 'Playfair Display', serif;
  font-size: 3rem;
  margin: 0;
  color: #d4af37;
  letter-spacing: 2px;
}

h2 {
  font-family: 'Montserrat', sans-serif;
  font-size: 1.5rem;
  margin: 10px 0 30px 0;
  color: #bfa14a;
  letter-spacing: 1px;
}

.menu {
  list-style: none;
  padding: 0;
  margin: 30px 0 0 0;
  display: flex;
  justify-content: center;
  gap: 40px;
}

.menu li a {
  color: #d4af37;
  text-decoration: none;
  font-weight: 600;
  font-size: 1.1rem;
  transition: color 0.2s;
}

.menu li a:hover {
  color: #fff;
}

.contacts span {
  display: block;
  margin: 8px 0;
  color: #bfa14a;
}

.about, .services, .cta {
  max-width: 800px;
  margin: 40px auto;
  background: #20242b;
  border-radius: 16px;
  padding: 32px 24px;
  box-shadow: 0 4px 24px rgba(0,0,0,0.12);
}

.about h3, .services h3, .cta h3 {
  font-family: 'Playfair Display', serif;
  color: #d4af37;
  margin-top: 0;
}

.service-list {
  display: flex;
  gap: 32px;
  justify-content: center;
  flex-wrap: wrap;
}

.service-item {
  background: #23272f;
  border-radius: 12px;
  padding: 24px 16px;
  width: 220px;
  text-align: center;
  box-shadow: 0 2px 12px rgba(0,0,0,0.08);
}

.service-item .icon {
  font-size: 2.5rem;
  margin-bottom: 12px;
  display: block;
}

.cta form {
  display: flex;
  flex-direction: column;
  gap: 16px;
  max-width: 400px;
  margin: 0 auto;
}

.cta input, .cta button {
  padding: 12px;
  border-radius: 8px;
  border: none;
  font-size: 1rem;
}

.cta input {
  background: #181d23;
  color: #d4af37;
  border: 1px solid #bfa14a;
}

.cta button {
  background: #d4af37;
  color: #181d23;
  font-weight: bold;
  cursor: pointer;
  transition: background 0.2s;
}

.cta button:hover {
  background: #bfa14a;
}

footer {
  background: #181d23;
  color: #bfa14a;
  text-align: center;
  padding: 24px 0 12px 0;
  margin-top: 40px;
}

.footer-contacts span {
  display: block;
  margin: 4px 0;
}

a {
  color: #d4af37;
  text-decoration: none;
}
