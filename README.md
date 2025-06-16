<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Имя Фамилия — Junior Developer</title>
  <style>
    /* Базовый минимализм + контраст */
    body { margin:0; font-family: Arial, sans-serif; background:#fafafa; color:#333; line-height:1.6; }
    header { background:#222; color:#fff; text-align:center; padding:60px 20px; }
    header h1 { margin:0; font-size:2.5rem; }
    header p { opacity:0.8; }
    a.btn { display:inline-block; margin-top:20px; padding:12px 25px; background:#ff6b6b; color:#fff; text-decoration:none; border-radius:5px; }
    section { max-width:800px; margin:40px auto; padding:0 20px; }
    h2 { border-bottom:2px solid #ff6b6b; display:inline-block; padding-bottom:5px; }
    .skills, .projects { display:grid; grid-template-columns:1fr 1fr; gap:20px; }
    .skill { background:#fff; padding:15px; border-radius:8px; box-shadow:0 2px 5px rgba(0,0,0,0.05); }
    .project { background:#fff; padding:20px; border-left:4px solid #ff6b6b; border-radius:5px; }
    footer { text-align:center; padding:20px; font-size:0.9rem; color:#777; }
  </style>
</head>
<body>

  <!-- 1. ГЕРОЙ -->
  <header>
    <h1>Иван Иванов</h1>
    <p>Junior Python/JavaScript Developer — делаю первые шаги в мире кода</p>
    <!-- CTA: Принцип «дефицита» -->
    <a href="#contact" class="btn">Связаться со мной (открыт до 31 июля)</a>
  </header>

  <!-- 2. НАВЫКИ -->
  <section id="skills">
    <h2>🔧 Навыки</h2>
    <div class="skills">
      <div class="skill">
        <h4>Python</h4>
        <p>FastAPI, Django (базовый уровень)</p>
      </div>
      <div class="skill">
        <h4>JavaScript</h4>
        <p>React, DOM, ES6+</p>
      </div>
      <div class="skill">
        <h4>Git & GitHub</h4>
        <p>Контроль версий, пул-реквесты</p>
      </div>
      <div class="skill">
        <h4>SQL</h4>
        <p>PostgreSQL, SQLite</p>
      </div>
    </div>
  </section>

  <!-- 3. ПРОЕКТЫ -->
  <section id="projects">
    <h2>🚀 Проекты</h2>
    <!-- Конкретика + социальное доказательство -->
    <div class="projects">
      <div class="project">
        <h3>Todo-приложение на React</h3>
        <p>SPA с регистрацией и сохранением задач в LocalStorage. ⭐️ 50+ звезд на GitHub</p>
      </div>
      <div class="project">
        <h3>API для библиотеки</h3>
        <p>Django REST API для управления книгами и пользователями. Обработано 1 000+ запросов в тесте</p>
      </div>
      <div class="project">
        <h3>Парсер вакансий</h3>
        <p>Скрипт на Python, собирающий вакансии с HeadHunter. Сэкономил 10+ часов ручного поиска</p>
      </div>
      <div class="project">
        <h3>Portfolio-сайт</h3>
        <p>Этот сайт! Адаптивен под мобильные и десктоп. Загружено >200 просмотров</p>
      </div>
    </div>
  </section>

  <!-- 4. ОБРАЗОВАНИЕ И СЕРТИФИКАТЫ -->
  <section id="education">
    <h2>🎓 Образование</h2>
    <ul>
      <li>2023–2025: Курсы «Python Developer» в XYZ-Academy (удостоверение №12345)</li>
      <li>2020–2023: Бакалавриат по ИТ, Университет АБВ</li>
    </ul>
  </section>

  <!-- 5. ОТЗЫВ -->
  <section id="testimonials">
    <h2>💬 Что говорят</h2>
    <p><em>«Иван очень быстро усвоил новый стек и помог нам запустить MVP за неделю»</em> — тимлид проекта</p>
  </section>

  <!-- 6. FAQ (снятие возражений) -->
  <section id="faq">
    <h2>❓ Вопросы</h2>
    <p><strong>Я мало работал в команде — справишься?</strong><br>Да, проходил коллаб-проекты и знаком с Git-flow.</p>
  </section>

  <!-- 7. КОНТАКТЫ -->
  <section id="contact">
    <h2>📬 Контакты</h2>
    <p>Email: ivan.ivanov@example.com</p>
    <p>GitHub: <a href="https://github.com/ivanivanov">github.com/ivanivanov</a></p>
    <p>Telegram: @ivan_codes</p>
  </section>

  <footer>
    &copy; 2025 Иван Иванов — готов к первым коммерческим задачам
  </footer>

</body>
</html>
