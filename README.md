<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Десногорск Онлайн</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header, nav, main, footer {
            padding: 20px;
        }
        header {
            background-color: #2c3e50;
            color: white;
        }
        nav {
            background-color: #34495e;
        }
        nav a {
            color: white;
            margin-right: 15px;
            text-decoration: none;
        }
        section {
            margin-bottom: 40px;
        }
        .gallery img {
            width: 200px;
            margin: 10px;
        }
        .articles article {
            margin-bottom: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Десногорск Онлайн</h1>
        <p>Информационный портал о городе Десногорск</p>
    </header>
    <nav>
        <a href="#weather">Погода</a>
        <a href="#gallery">Фотогалерея</a>
        <a href="#articles">Статьи</a>
    </nav>
    <main>
        <section id="weather">
            <h2>Погода в Десногорске</h2>
            <!-- Вставьте виджет погоды здесь -->
            <a class="weatherwidget-io" href="https://forecast7.com/ru/54d1512d29/desnogorsk/" data-label_1="ДЕСНОГОРСК" data-label_2="Погода" data-theme="original" >ДЕСНОГОРСК Погода</a>
            <script>
            !function(d,s,id){
              var js,fjs=d.getElementsByTagName(s)[0];
              if(!d.getElementById(id)){
                js=d.createElement(s);js.id=id;
                js.src='https://weatherwidget.io/js/widget.min.js';
                fjs.parentNode.insertBefore(js,fjs);
              }
            }(document,'script','weatherwidget-io-js');
            </script>
        </section>
        <section id="gallery">
            <h2>Фотогалерея</h2>
            <div class="gallery">
                <img src="photo1.jpg" alt="Фото 1">
                <img src="photo2.jpg" alt="Фото 2">
                <img src="photo3.jpg" alt="Фото 3">
                <!-- Добавьте больше изображений по мере необходимости -->
            </div>
        </section>
        <section id="articles">
            <h2>Интересные статьи</h2>
            <div class="articles">
                <article>
                    <h3>История Десногорска</h3>
                    <p>Краткое описание статьи о истории города...</p>
                    <a href="article1.html">Читать далее</a>
                </article>
                <article>
                    <h3>Достопримечательности</h3>
                    <p>Краткое описание статьи о достопримечательностях...</p>
                    <a href="article2.html">Читать далее</a>
                </article>
                <!-- Добавьте больше статей по мере необходимости -->
            </div>
        </section>
    </main>
    <footer>
        <p>&copy; 2025 Десногорск Онлайн</p>
    </footer>
</body>
</html>