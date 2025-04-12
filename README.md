<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Курсовые работы на заказ</title>
  <style>
  body {
    font-family: 'Segoe UI', sans-serif;
    margin: 0;
    padding: 0;
    background: #fdfdfd;
    color: #333;
    overflow-x: hidden;
  }
  header, footer {
    background-color: #ffffff;
    color: #222;
    padding: 20px;
    display: flex;
    align-items: center;
    justify-content: space-between;
    box-shadow: 0 2px 5px rgba(0,0,0,0.05);
  }
 .logo {
  max-width: 20px;  /* Уменьшение размера логотипа */
  height: auto;
  margin-right: 15px;
  border-radius: 50%;  /* Логотип остается круглым */
}

  .header-text {
    display: flex;
    flex-direction: column;
  }
  header h1 {
    font-size: 1.6em;
    margin: 0;
  }
  header p {
    margin: 5px 0 0;
    font-size: 0.95em;
    color: #666;
  }
  nav {
    background: #ffffff;
    border-top: 1px solid #eee;
    border-bottom: 1px solid #eee;
    padding: 10px 0;
    text-align: center;
  }
  nav a {
    color: #333;
    text-decoration: none;
    margin: 0 15px;
    transition: color 0.3s ease;
    font-weight: 500;
  }
  nav a:hover {
    color: #0a84ff;
  }
  .container {
    max-width: 1000px;
    margin: 20px auto;
    padding: 20px;
    background: #ffffff;
    border-radius: 12px;
    box-shadow: 0 2px 10px rgba(0,0,0,0.05);
  }
  .section {
    margin-bottom: 30px;
    animation: fadeInUp 0.8s ease both;
  }
  form input, form textarea, form select {
    width: 100%;
    padding: 12px;
    margin: 10px 0;
    border-radius: 6px;
    border: 1px solid #ccc;
    transition: border-color 0.3s ease;
  }
  form input:focus, form textarea:focus, form select:focus {
    border-color: #0a84ff;
    outline: none;
  }
  form button {
    background-color: #0a84ff;
    color: white;
    padding: 12px 24px;
    border: none;
    border-radius: 6px;
    cursor: pointer;
    font-size: 1em;
    transition: background 0.3s ease;
  }
  form button:hover {
    background-color: #006edc;
  }
  .features {
    display: flex;
    flex-wrap: wrap;
    gap: 20px;
    justify-content: space-between;
  }
  .feature-box {
    flex: 1 1 45%;
    background: #f0f8ff;
    padding: 15px;
    border-radius: 8px;
    border-left: 4px solid #0a84ff;
    transition: transform 0.3s ease;
  }
  .feature-box:hover {
    transform: scale(1.03);
  }
  .highlight {
    background-color: #e6f7ff;
    border-left: 5px solid #0a84ff;
    padding: 10px;
    margin: 20px 0;
    border-radius: 5px;
    animation: pulse 2s infinite;
  }
  footer {
    text-align: center;
    font-size: 0.9em;
    color: #777;
  }
  @keyframes fadeInUp {
    from { opacity: 0; transform: translateY(30px); }
    to { opacity: 1; transform: translateY(0); }
  }
  @keyframes pulse {
    0% { transform: scale(1); }
    50% { transform: scale(1.02); }
    100% { transform: scale(1); }
  }
</style>

</head>
<body>
  <header>
    <img src="https://scontent.fala7-1.fna.fbcdn.net/v/t39.30808-6/490023522_1202965921415926_6141329830785597534_n.jpg?stp=dst-jpg_p526x296_tt6&_nc_cat=111&ccb=1-7&_nc_sid=127cfc&_nc_eui2=AeHsKpFVgRB3t43HOpMy3NVNdYk8U1b2Ehp1iTxTVvYSGrY6bq60iwPTdXnuoaMizCWxjJA5_KaZf9pFjlwiEwFR&_nc_ohc=_Pq-XwY0bkQQ7kNvwEuxQus&_nc_oc=AdlmlZOKrFLPxXAPDl8ERInw06OtC0AjERYCyPi-9vavavGF0jBcnpdX-yZG8UFBl1M&_nc_zt=23&_nc_ht=scontent.fala7-1.fna&_nc_gid=WIJlQCSO2tEmE3FAipaCsw&oh=00_AfGhOTkScAJEJVjvG8HB6zkve8EU2yqCbV_DPPqhjFbY4g&oe=67FF3F7B" alt="Логотип" class="logo">
    <div class="header-text">
      <h1>Курсовые работы на заказ</h1>
      <p>Быстро. Качественно. По ГОСТу. Гарантия оригинальности.</p>
    </div>
  </header>

  <!-- Остальной код остаётся прежним -->

  <nav>
    <a href="#about">О нас</a>
    <a href="#features">Преимущества</a>
    <a href="#catalog">Каталог</a>
    <a href="#order">Заказать</a>
    <a href="#reviews">Отзывы</a>
    <a href="#faq">FAQ</a>
    <a href="#contacts">Контакты</a>
  </nav>

  <div class="container">
    <section id="about" class="section">
      <h2>О нас</h2>
      <p>Наша команда профессиональных авторов помогает студентам с 2020 года. Мы создаём уникальные курсовые, дипломные, отчёты и рефераты по различным дисциплинам. Каждый заказ — это индивидуальный подход, соблюдение требований и сроков.</p>
      <div class="highlight">
        <strong>Новинка:</strong> теперь доступна быстрая проверка на антиплагиат и консультации по защите работы!
      </div>
    </section>

    <section id="features" class="section">
      <h2>Наши преимущества</h2>
      <div class="features">
        <div class="feature-box">
          <h3>Индивидуальный подход</h3>
          <p>Каждая работа создаётся под конкретные требования ВУЗа и преподавателя.</p>
        </div>
        <div class="feature-box">
          <h3>Гарантия качества</h3>
          <p>Оригинальность от 80%, соблюдение всех методических указаний.</p>
        </div>
        <div class="feature-box">
          <h3>Срочное выполнение</h3>
          <p>Курсовые за 24 часа — это реально!</p>
        </div>
        <div class="feature-box">
          <h3>Поддержка 24/7</h3>
          <p>Наши менеджеры на связи в Telegram и WhatsApp в любое время.</p>
        </div>
      </div>
    </section>

    <section id="catalog" class="section">
      <h2>Каталог работ</h2>
      <ul>
        <li>Экономика: бухучёт, финансы, маркетинг</li>
        <li>Юриспруденция: гражданское право, уголовное право</li>
        <li>Психология: общая, возрастная, педагогическая</li>
        <li>Педагогика, социология, культурология</li>
        <li>ИТ и математика: программирование, анализ данных</li>
        <li>История, философия, искусствоведение</li>
        <li>Дипломные, отчёты по практике, презентации</li>
      </ul>
    </section>

    <section id="order" class="section">
  <h2>Заказать работу</h2>
  <form>
    <input type="text" placeholder="Ваше имя" required />
    <input type="email" placeholder="Ваш Email" required />
    <input type="text" placeholder="Тема работы" required />
    <input type="tel" placeholder="Ваш номер телефона" required />
    <select required>
      <option disabled selected>Выберите тип работы</option>
      <option>Курсовая</option>
      <option>Дипломная</option>
      <option>Реферат</option>
      <option>Отчёт по практике</option>
      <option>Презентация</option>
      <option>Другое</option>
    </select>
    <textarea placeholder="Подробности: дисциплина, объём, срок..." rows="5" required></textarea>
    <button type="submit">Отправить заказ</button>
  </form>
</section>


    <section id="reviews" class="section">
      <h2>Отзывы</h2>
      <p><strong>Парвиз:</strong> Спасибо! Курсовую сделали быстро!</p>
      <p><strong>Нурмурат:</strong> Работа на 5, антиплагиат 92%. Рекомендую!</p>
      <p><strong>Аружан:</strong> Очень быстро и профессионально. Спасибо за презентацию и отчёт!</p>
      <p><strong>Тимур:</strong> Помогли с расчётной частью по экономике, всё правильно и чётко.</p>
    </section>

    <section id="faq" class="section">
      <h2>Часто задаваемые вопросы (FAQ)</h2>
      <div class="faq-item">
        <h4>Как быстро вы выполняете заказы?</h4>
        <p>Срок зависит от объема, в среднем от 2 до 5 дней. Срочные заказы — от 12 часов.</p>
      </div>
      <div class="faq-item">
        <h4>Что делать, если преподаватель просит доработку?</h4>
        <p>Мы вносим правки бесплатно в течение 7 дней после сдачи работы.</p>
      </div>
      <div class="faq-item">
        <h4>Вы даёте гарантии на антиплагиат?</h4>
        <p>Да, минимальный уровень антиплагиата — 70%, часто выше 85-90%. Возможен отчёт из "Антиплагиат.ВУЗ".</p>
      </div>
    </section>

    <section id="contacts" class="section">
      <h2>Контакты</h2>
      <p>Email: srazgulevmajmun@gmail.com</p>
      <p>Telegram: <a href="https://t.me/randomnyecyfry" target="_blank">@randomnyecyfry</a></p>
      <p>WhatsApp: <a href="https://wa.me/77716601243" target="_blank">+7 (771) 660 1243</a></p>
      <p>Instagram: <a href="https://instagram.com/na1llx" target="_blank">@kursraboty</a></p>
    </section>
  </div>

  <footer>
    <p>&copy; 2025 Курсовые на заказ. Все права защищены.</p>
  </footer>
</body>
</html>

