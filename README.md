<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tocik Studio</title>
    <link rel="stylesheet" href="styles.css"> <!-- Подключаем CSS -->
    <!-- Подключаем шрифт Roboto -->
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700&display=swap" rel="stylesheet">
    <!-- Иконочный шрифт для соцсетей -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
</head>
<body>
    <!-- Шапка -->
    <header>
        <div class="container header-content">
            <div class="logo">Tocik Studio</div>
            <nav class="nav-links">
                <a href="#main">Главная</a>
                <a href="#news">Новости</a>
                <a href="#games">Игры</a>
            </nav>
            <a href="https://itch.io" class="nav-links">Itch.io</a>
        </div>
    </header>

    <!-- Главная секция -->
    <section class="hero" id="main">
        <div class="container hero-content">
            <h1>Tocik Studio</h1>
            <p>Мы создаем уникальные пиксель-арт игры с душой и вниманием к деталям. Погрузитесь в наши миры и откройте для себя магию ретро-стиля!</p>
        </div>
    </section>

    <!-- Секция новостей -->
    <section class="container" id="news">
        <div class="news-grid">
            <div class="main-news">
                <img src="./imm.jpg" alt="Главная новость">
                <div class="main-news-content">
                    <h2>Главная новость</h2>
                    <p>Текст основной новости...</p>
                </div>
            </div>
            <div class="side-news">
                <div class="news-tile">
                    <img src="./imm.jpg" alt="Новость 1">
                    <div class="news-tile-content">
                        <h3>Новость 1</h3>
                        <p>Краткое описание...</p>
                    </div>
                </div>
                <div class="news-tile">
                    <img src="./imm.jpg" alt="Новость 2">
                    <div class="news-tile-content">
                        <h3>Новость 2</h3>
                        <p>Краткое описание...</p>
                    </div>
                </div>
                <div class="news-tile">
                    <img src="./imm.jpg" alt="Новость 3">
                    <div class="news-tile-content">
                        <h3>Новость 3</h3>
                        <p>Краткое описание...</p>
                    </div>
                </div>
            </div>
        </div>
        <a href="#" class="view-all-btn">Смотреть все</a>
    </section>

    <!-- Секция игр -->
    <section class="container" id="games">
        <div class="games-grid">
            <div class="game-tile">
                <img src="./imm.jpg">
                <h3>Compilation</h3>
                <p>Атмосферна гра про цифрову реальність, де ти досліджуєш унікальний віртуальний світ і розкриваєш його таємниці.</p>
                <a href="#">Посилання</a>
            </div>
            <!-- Добавьте больше игр по аналогии -->
        </div>
    </section>

    <!-- Футер -->
    <footer>
        <div class="container">
            <div class="social-links">
                <a href="#"><i class="fab fa-twitter"></i></a>
                <a href="#"><i class="fab fa-discord"></i></a>
                <a href="#"><i class="fab fa-youtube"></i></a>
            </div>
            <nav class="nav-links" style="margin-top: 1rem;">
                <a href="#main">Главная</a>
                <a href="#news">Новости</a>
                <a href="#games">Игры</a>
            </nav>
        </div>
    </footer>
</body>
</html>
