
<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Чеченский табор — Discord сервер</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #0c0f14;
      color: #e6edf3;
    }
    header {
      background: #ffd166;
      color: #1a1d24;
      padding: 20px;
      text-align: center;
    }
    header h1 { margin: 0; font-size: 1.8rem; }
    .container {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 30px;
      padding: 30px;
    }
    .content { max-width: 600px; }
    .btn {
      display: inline-block;
      margin-top: 15px;
      padding: 10px 16px;
      background: linear-gradient(180deg, #ffd166, #ffb703);
      color: #1a1d24;
      font-weight: bold;
      border-radius: 8px;
      text-decoration: none;
      transition: 0.25s;
    }
    .btn:hover { filter: brightness(1.1); }
    .server-card {
      background: rgba(255,255,255,0.05);
      border: 1px solid rgba(255,255,255,0.15);
      border-radius: 12px;
      padding: 20px;
      box-shadow: 0 8px 20px rgba(0,0,0,0.35);
    }
    footer {
      text-align: center;
      padding: 20px;
      color: #a9b1bd;
      font-size: 0.9rem;
    }
  </style>
</head>
<body>
  <header>
    <h1>Чеченский табор</h1>
    <p>Добро пожаловать на наш Discord сервер</p>
  </header>

  <div class="container">
    <!-- Левая часть -->
    <div class="content">
      <h2>О сервере</h2>
      <p>Наш лагерь — это уютное место для общения, юмора и совместных проектов. 
         Заходи и присоединяйся к комьюнити!</p>
      <!-- Кнопка-инвайт -->
      <a class="btn" href="https://discord.gg/SBPfb7r9Xg" target="_blank" rel="noopener">Присоединиться</a>
    </div>

    <!-- Правая часть: карточка + виджет -->
    <div class="server-card">
      <h3>Профиль сервера</h3>
      <p><strong>Имя:</strong> Чеченский табор</p>
      <p><strong>Дата основания:</strong> октябрь 2025</p>
      <p><strong>Участники:</strong> 2</p>
      <p><strong>Онлайн:</strong> 1</p>

      <!-- Discord Widget -->
      <iframe src="https://discord.com/widget?id=1433889550630916251&theme=dark"
              width="350" height="500" allowtransparency="true" frameborder="0"
              sandbox="allow-popups allow-popups-to-escape-sandbox allow-same-origin allow-scripts"></iframe>
    </div>
  </div>

  <footer>
    © 2025 • Сообщество «Чеченский табор»
  </footer>
</body>
</html>
