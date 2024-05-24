<p align = "center">МИНИСТЕРСТВО НАУКИ И ВЫСШЕГО ОБРАЗОВАНИЯ<br>
РОССИЙСКОЙ ФЕДЕРАЦИИ<br>
ФЕДЕРАЛЬНОЕ ГОСУДАРСТВЕННОЕ БЮДЖЕТНОЕ<br>
ОБРАЗОВАТЕЛЬНОЕ УЧРЕЖДЕНИЕ ВЫСШЕГО ОБРАЗОВАНИЯ<br>
«САХАЛИНСКИЙ ГОСУДАРСТВЕННЫЙ УНИВЕРСИТЕТ»</p>
<br><br><br><br><br><br>
<p align = "center">Институт естественных наук и техносферной безопасности<br>Кафедра информатики<br>Иванюшин Виталий Петрович</p>
<br><br><br>
<p align = "center"><br><strong>Лабораторная работа №2.«HTML»</strong><br>01.03.02 Прикладная математика и информатика</p>
<br><br><br><br><br><br><br><br><br><br><br><br>
<p align = "right">Научный руководитель<br>
Соболев Евгений Игоревич</p>
<br><br><br>
<p align = "center">г. Южно-Сахалинск<br>2024 г.</p>
<br><br><br><br><br><br><br><br><br><br><br><br>

<h1 align = "center">Введение</h1>

<p><b>HTML</b> —  стандартизированный язык гипертекстовой разметки документов для просмотра веб-страниц в браузере. Веб-браузеры получают HTML документ от сервера по протоколам HTTP/HTTPS или открывают с локального диска, далее интерпретируют код в интерфейс, который будет отображаться на экране монитора.</p>
<p><b>CSS</b> — формальный язык описания внешнего вида документа, написанного с использованием языка разметки. Также может применяться к любым XML-документам, например, к SVG или XUL.</p>


<h1 style="text-align: center">Задачи</h1>
<h2>Выполнить задачи по "HTML"</h2>




<h1 style="text-align: center">Решения</h1>

<h2 style="text-align: center">Файл 1.html</h2>

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Title</title>
    <style>
        h1, h2, h3 {
            font-weight: normal;
        }
    </style>
</head>
<body>
<h1 style="margin: 0; font-family: 'Calibri Light';">Это заголовок</h1>
<h3 style="font-family: 'Calibri Light'; margin-top: 0">Это заголовок</h3>
<h2><b>Это заголовок</b></h2>
<h2 style="font-family: 'Calibri Light'"><i>Это заголовок</i></h2>
<p style="font-size: 20px">Это <b>абзац</b></p>
<p style="font-size: 20px">Это ещё <i>абзац</i></p>
<h3>Это заголовок</h3>
<h1 style="font-family: 'Calibri Light'"><i>Это заголовок h1</i></h1>

</body>
</html>
```
<h2 style="text-align: center">Файл 2.html</h2>

```html
<!doctype html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport"
          content="width=device-width, user-scalable=no, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Document</title>
    <style>
        h1, h3 {
            font-weight: normal;
        }
    </style>
</head>
<body>
<h1 style="font-family: 'Calibri Light'">Что такое CMS</h1>
<p><b>CMS - </b>«система управления контентом» <b>(движок)</b> – написанная PHP-программистами основа для сайта, с помощью которой вы сможете управлять сайтом (добавлять контент, менять пункты меню и т.п.) не зная HTML и CSS.</p>
<p>Однако, для того чтобы сделать сайт с помощью <b>CMS</b> <i>потребуются услуги</i> и программиста, и дизайнера, и верстальщика. И капиталовложения.</p>
<h3 style="font-family: 'Calibri Light'"> Какие бывают cms</h3>
<p>Бывают различные системы управления контентом: для интернет-магазинов, для блогов, для форумов и т.д.</p>
<h3 style="font-family: 'Calibri Light'">Примеры cms</h3>
<p><i>Примеры популярных CMS</i>: Joomla, WordPress (для блогов), PhpBB (для форумов).</p>
<p><b>CMS-ки</b> бывают платные и бесплатные.</p>
</body>
</html>
```
<h2 style="text-align: center">Файл 3.html</h2>

```html
<!doctype html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport"
          content="width=device-width, user-scalable=no, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Document</title>
    <style>
        h1, h4 {
            font-weight: normal;
            font-family: "Calibri Light";
        }
    </style>
</head>
<body>
<h1 style="margin-bottom: 0">Списки</h1>
<h4 style="margin-top: 0">Список цветов</h4>
<ul>
    <li>Красный</li>
    <li>Желтый</li>
    <li>Зелёный</li>
    <li>Синий</li>
</ul>
<h4 style="margin-top: 0">Список цветов</h4>
<ol>
    <li>Иванов</li>
    <li>Петров</li>
    <li>Сидоров</li>
    <li>Николаев</li>
</ol>

<h4 style="margin-top: 0">Список цветов</h4>
<ol>
    <li>Иванов
        <ul>
            <li>Возраст - 23 года</li>
            <li>Курс - 3</li>
        </ul>
    </li>
    <li>Петров
        <ul>
            <li>Возраст - 19 лет</li>
            <li>Курс - 2</li>
        </ul>
    </li>
    <li>Сидоров
        <ul>
            <li>Возраст - 18 лет</li>
            <li>Курс - 1</li>
        </ul>
    </li>
</ol>
</body>
</html>
```
<h2 style="text-align: center">Файл 4.html</h2>

```html
<!doctype html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport"
          content="width=device-width, user-scalable=no, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Document</title>
    <style>
        h1, h3 {
            font-weight: normal;
            font-family: "Calibri Light";
        }
    </style>
</head>
<body>
<h1>
    <b>Что нужно знать, чтобы делать сайты</b>
</h1>
<ol>
    <li><b>HTML</b></li>
    <li><i>CSS</i></li>
    <li>PHP</li>
    <li>SQL</li>
    <li>JavaScript</li>
    <li>jQuery</li>
    <li>Flash</li>
    <li>SEO</li>
</ol>
<h3>PHP и JavaScript</h3>
<p>Языки программирования <b>PHP</b> и <b>JavaScript</b> позволяют сделать сайт динамичным, то есть реагирующим на действия пользователя. Например, можно сделать красивую выпадающую менюшку или слайдер</p>
<h3>Виды скриптов</h3>
<p>Для этого пишутся скрипты (англ. <i>script</i> - «сценарий») - программы, позволяющиее реагировать на действия пользователя. Скрипты бывают двух видов:</p>
<ul>
    <li> те, которые выполняются на сервере, а результат их выполнения приходит в браузер к пользователю уже в готовом виде. Это скрипты, написанные на языке <b>PHP</b>. На нем пишуться <b>CMS-ки</b> – системы управления контентом.</li>
    <li>те, которые выполняются прямо в браузере пользователя. Это скрипты, написанные на языке <b>JavaScript</b>. Они чаще всего используются для, того чтобы сделать страницу более удобной и красивой.</li>
</ul>
</body>
</html>
```
<h2 style="text-align: center">Файл 5.html</h2>

```html
<!doctype html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport"
          content="width=device-width, user-scalable=no, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Document</title>
</head>
<body style="display: flex; flex-direction: column">
    <a href="1.html">Страница 1</a>
    <a href="2.html">Страница 2</a>
    <a href="3.html">Страница 3</a>
</body>
</html>
```
<h2 style="text-align: center">Файл 6.html</h2>

```html
<!doctype html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport"
          content="width=device-width, user-scalable=no, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Document</title>
</head>
<body>
    <img src="img/mop.jpeg" alt="мопс">
</body>
</html>
```

<h2 style="text-align: center">Файл 7.html</h2>

```html
<!doctype html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport"
          content="width=device-width, user-scalable=no, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Document</title>
</head>
<body>
    <img src="img/mop.jpeg" alt="мопс">
</body>
</html>
```

<h2 style="text-align: center">Файл 8.html</h2>

```html
<!doctype html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport"
          content="width=device-width, user-scalable=no, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Document</title>
</head>
<body>
    <img src="img/mop.jpeg" alt="мопс">
</body>
</html>
```
<h2 style="text-align: center">Файл 9.html</h2>

```html
<!doctype html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport"
          content="width=device-width, user-scalable=no, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Montserrat+Alternates:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap"
          rel="stylesheet">
    <title>Document</title>
    <link href="style/form.css" rel="stylesheet">
    <link href="style/btn.css" rel="stylesheet">
    <link href="style/var.css" rel="stylesheet">
</head>
<body>
<form class="form-vertical form-vertical_round" action="">
    <div class="form__header">Введите Ваши данные</div>
    <div class="form__group">
        <label for="name"> Имя </label>
        <input class="form__input" name="name" type="text" id="name" placeholder="Иван">
    </div>
    <div class="form__group">
        <label for="email"> email </label>
        <input class="form__input" name="email" type="email" id="email" placeholder="email@mail.ru">
    </div>
    <div class="form__group">
        <label for="comment"> Сообщение </label>
        <textarea class="form__textarea" name="email" id="comment"></textarea>
    </div>
    <button class="btn btn_success" type="submit">Отправить</button>
</form>
</body>
</html>
```
<h2 style="text-align: center">Файл 10.html</h2>

```html
<!doctype html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport"
          content="width=device-width, user-scalable=no, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Document</title>
    <link rel="stylesheet" href="style/table.css">
</head>
<body>
<table cellpadding="">
    <thead>
        <tr>
            <th scope="col">id</th>
            <th scope="col">Название</th>
            <th scope="col">Цена</th>
            <th scope="col">Описание</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <th scope="row">1</th>
            <td>книга</td>
            <td>500</td>
            <td>Книга со сказками Пушкина</td>
        </tr>
        <tr>
            <th scope="row">2</th>
            <td>Карандаши</td>
            <td>100</td>
            <td>Цветные карандаши</td>
        </tr>
        <tr>
            <th scope="row">3</th>
            <td>Тетрадь</td>
            <td>13</td>
            <td>Тетрадь 12 листов</td>
        </tr>
        <tr>
            <th scope="row">4</th>
            <td>Ручка</td>
            <td>23</td>
            <td>ручка чёрная геливая</td>
        </tr>
    </tbody>
</table>
</body>
</html>
```

<h2 style="text-align: center">Файл 11.html</h2>

```html
<!DOCTYPE html>
<html>
<head>
    <title>Интерактивная Яндекс-карта с маркерами</title>
    <script src="https://api-maps.yandex.ru/2.1/?apikey=ВАШ_API_КЛЮЧ&lang=ru_RU" type="text/javascript"></script>
    <style>
        #map {
            width: 800px;
            height: 600px;
        }
    </style>
</head>
<body>
    <h1>Моя интерактивная Яндекс-карта</h1>
    <div id="map"></div>

    <script>
        ymaps.ready(init);

        function init() {
            var myMap = new ymaps.Map("map", {
                center: [46.957771, 142.729587],
                zoom: 10
            });

            var placemark = new ymaps.Placemark([46.957771, 142.729587], {
                hintContent: 'Южно-Сахалинск',
                balloonContent: 'Островная столица'
            });

            myMap.geoObjects.add(placemark);
        }
    </script>
</body>
</html>

```

<h2 style="text-align: center">Файл 12.html</h2>

```html
<!doctype html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport"
          content="width=device-width, user-scalable=no, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Document</title>
    <style>
        body {
            margin: 0;
            padding: 0;
        }
        .nav, .nav__container-2 {
            text-decoration: none;
            list-style: none;
            margin: 0;
            padding: 0;
        }
        .navbar {
            width: 100%;
            display: flex;
            flex-direction: column;
            background-color: rgb(171, 193, 30);
            padding: 0 10px 0 10px;
        }
        .nav {
            display: flex;
            flex-direction: row;
            gap:15px;
        }
        .nav__element-1 {
            cursor: pointer;
            background-color: #f0a7d0;
            padding: 15px;
        }
        .nav__container-2 {
            display: none;
            background-color: rgb(116, 234, 252);
            padding: 15px;
        }
        .nav__element-2 {
            padding: 15px;
        }
        .nav__element-1_more {
            position: relative;
        }
        .nav__element-1_more:hover .nav__container-2 {
            display: block;
            position: absolute;
            top:48px;
            left: 0;
        }
        .nav__element-1:hover, .nav__element-2:hover {
            background-color: rgba(197, 115, 115, 0.91);
        }
    </style>
</head>
<body>
<div class="navbar">
    <ul class="nav">
        
        <li class="nav__element-1 nav__element-1_more">Камни бесклнечности
            <ul class="nav__container-2">
                <li class="nav__element-2">Сила</li>
                <li class="nav__element-2">Пространство</li>
                <li class="nav__element-2">Реальность</li>
                <li class="nav__element-2">Душа</li>
                <li class="nav__element-2">Время</li>
                <li class="nav__element-2">Разум</li>
            </ul>
        </li>
        
    </ul>
</div>

</body>
</html>
```

<h2 style="text-align: center">Файл 13.html</h2>

```html
<!doctype html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport"
          content="width=device-width, user-scalable=no, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Document</title>
</head>
<body>
<audio controls>
    <source src="resource/m-8.mp3">
</audio>
</body>
</html>
```

<h2 style="text-align: center">Файл 14.html</h2>

```html
<!doctype html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport"
          content="width=device-width, user-scalable=no, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Document</title>
    <style>
        .gallery-content__item {
            display: inline-block;
            width: 250px;
            height: 250px;
        }

        .gallery-content__item img {
            width: 250px;
            height: 250px;
        }

        .gallery-content__item img:hover {
            width: 260px;
            height: 260px;
        }

        .gallery {
            display: none;
            position: absolute;
            top: 0;
            left: 0;
            width: 100vw;
            height: 100vh;
            background-color: rgba(0, 0, 0, 0.76);
            z-index: 999;
        }

        .gallery_open {
            display: block;
        }

        .gallery__wrapper {
            position: relative;
            width: 100%;
            height: 100%;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            overflow: hidden;
        }

        .gallery__container {
            width: 50%;
            height: 50%;
            display: flex;
            flex-direction: row;
        }

        .gallery__item {
            display: none;
            flex-shrink: 0;
            flex-grow: 1;
            flex-basis: 100%;
            max-width: 100%;
            color: white;
            width: 250px;
            border-radius: 10px;
            height: 100%;
        }

        .gallery__item img {
            width: 100%;
            height: 100%;
            transform-origin: center;
            object-fit: cover;
        }

        .gallery__btn {
            position: absolute;
            width: 50px;
            height: 75px;
            top: 50%;
            transform: translateY(-50%);
            z-index: 99999;
            cursor: pointer;

            background-color: #000000;
            display: flex;
            justify-content: center;
            align-items: center;
            font-size: 30px;
            font-weight: 700;
            color: white;
            border-radius: 10px;
        }

        .gallery__btn_next {
            right: 5px;
        }

        .gallery__btn_prev {
            left: 5px;
        }

        .gallery__btn_close {
            position: absolute;
            right: 5px;
            top: 5px;
            height: 50px;
            transform: none;
        }

        .gallery__btn_hidden {
            display: none;
        }
        .gallery__item_active {
            display: block;
        }
    </style>
</head>
<body>
<div class="gallery-content" id="galleryContent">
    <div class="gallery-content__item" data-src="/img/2.jpg">
        <img src="/img/2.jpg" alt="">
    </div>
    <div class="gallery-content__item" data-src="/img/6.jpg">
        <img src="/img/6.jpg" alt="">
    </div>
    <div class="gallery-content__item" data-src="/img/7.jpg">
        <img src="/img/7.jpg" alt="">
    </div>
    <div class="gallery-content__item" data-src="/img/3.jpg">
        <img src="/img/3.jpg" alt="">
    </div>
    <div class="gallery-content__item" data-src="/img/4.jpg">
        <img src="/img/4.jpg" alt="">
    </div>
    <div class="gallery-content__item" data-src="/img/5.jpg">
        <img src="/img/5.jpg" alt="">
    </div>
</div>

<div class="gallery" id="galleryId">
    <div class="gallery__wrapper">
        <div class="gallery__container">

        </div>
        <div class="gallery__btn gallery__btn_prev"><</div>
        <div class="gallery__btn gallery__btn_next"> ></div>
        <div class="gallery__btn gallery__btn_close">x</div>
    </div>
</div>

<script>
    let config = {
        contentId: 'galleryContent',
        galleryId: 'galleryId',
        btnNextClass: 'gallery__btn_next',
        btnPrevClass: 'gallery__btn_prev',
        btnCloseClass: 'gallery__btn_close',
        galleryContainer: 'gallery__container'
    }

    class Gallery {
        constructor(config) {
            this.content = document.getElementById(config.contentId).children;
            this.contentBlock = document.getElementById(config.contentId);
            this.index = 0;
            this.width = 0;
            this.imgZoom = '';
            this.gallery = document.getElementById(config.galleryId);
            this.gallerySlides = document.getElementsByClassName(config.galleryContainer)[0];
            this.btnPrev = document.getElementsByClassName(config.btnPrevClass)[0];
            this.btnNext = document.getElementsByClassName(config.btnNextClass)[0];
            this.btnClose = document.getElementsByClassName(config.btnCloseClass)[0];
            this.contentBlock.onclick = this.open.bind(this);
            this.gallerySlides.onmousemove = this.zoom.bind(this);
            this.gallerySlides.onmouseleave = this.unZoom.bind(this);
            this.btnClose.addEventListener('click', this.close.bind(this));
            this.btnPrev.addEventListener('click', this.prev.bind(this));
            this.btnNext.addEventListener('click', this.next.bind(this));
            for (let i = 0; i < this.content.length; i++) {
                this.gallerySlides.append(this.getTemplate(this.content[i].dataset.src));
                this.content[i].children[0].setAttribute('data-galleryid', i.toString());
            }
            this.gallerySlides = document.getElementsByClassName(config.galleryContainer)[0];
        }

        getTemplate(src) {
            let div = document.createElement('div');
            div.className = 'gallery__item';
            div.innerHTML = `<img src="${src}">`;
            return div;
        }

        open(event) {
            this.index = Number(event.target.dataset.galleryid);
            this.show(this.index);
            this.gallery.className = this.gallery.className.replace('', ' gallery_open ');
        }

        close() {
            this.gallery.className = this.gallery.className.replace(' gallery_open ', '');
        }

        show (index) {
            if (index > this.gallerySlides.children.length - 1) {
                this.index = 0;
                this.width = 0;
            }

            if (index < 0) {
                this.index = this.gallerySlides.children.length - 1
            }

            let i = 0;
            for (i; i < this.gallerySlides.children.length; i++) {
                this.gallerySlides.children[i].className = this.gallerySlides.children[i].className.replace(' gallery__item_active ', '');
            }

            this.gallerySlides.children[this.index].className = this.gallerySlides.children[this.index].className.replace('', ' gallery__item_active ');
        }

        next () {
            this.show(this.index += 1);
            this.width += this.gallerySlides.children[this.index].offsetWidth;
        }

        prev () {
            this.show(this.index -= 1);
            this.width -= this.gallerySlides.children[this.index].offsetWidth;
        }

        zoom (event) {
            const x = event.clientX - event.target.offsetLeft - 10;
            const y = event.clientY - event.target.offsetTop - 10;

            if (event.target.tagName === 'IMG') {
                this.imgZoom = event.target;
                event.target.style.transformOrigin = `${x}px ${y}px`;
                event.target.style.transform = 'scale(2)';
            }
        }

        unZoom () {
            this.imgZoom.style.transformOrigin = 'center';
            this.imgZoom.style.transform = 'scale(1)';
        }
    }

    gallery = new Gallery(config);
</script>
</body>
</html>
```

<h2 style="text-align: center">Файл 15.html</h2>

```html
<!doctype html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport"
          content="width=device-width, user-scalable=no, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Montserrat+Alternates:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap"
          rel="stylesheet">
    <title>Document</title>
    <link href="style/btn.css" rel="stylesheet">
    <link href="style/var.css" rel="stylesheet">
    <style>
        .form-ad {
            font-family: "Montserrat Alternates", sans-serif;
            font-weight: 400;
            padding: 15px;
            margin: 15px;
            border: 1px solid var(--color-silver-light);
            border-radius: var(--main-round-border);
            max-height: 150px;
        }
        .form-ad__container_grid {
            display: grid;
            grid-template-columns: 1fr 4fr 1fr 1fr;
            grid-gap: 10px;
        }
        .form-ad__container_flex {
            display: flex;
            gap: 10px
        }
        .form-ad__container_flex_vertical {
            flex-direction: column;
        }
        .form-ad__container_flex_between {
            justify-content: space-between;
        }
        .form-ad__ad-image {
            width: 100%;
            height: 100%;
        }
        .form-ad__ad-image>img {
            min-width: 100px;
            max-height: 140px;
            width: 100%;
        }
        .form-ad__quantity-input {
            box-sizing: border-box;
            width: 100%;
            border: 1px solid var(--color-silver-light-2);
            border-radius: var(--main-round-border);
            height: 30px;
            margin-top: 5px;
            font-size: 1em;
            padding: 2px 10px 2px 10px;
        }
        .form-ad__title {
            font-size: 1.3rem;
        }
    </style>
</head>
<body>
<form class="form-ad" action="">
    <div class="form-ad__container_grid">
        <div class="form-ad__ad-image">
            <img src="img/1.jpg">
        </div>
        <div class="form-ad__container_flex form-ad__container_flex_vertical">
            <div class="form-ad__title">Перчатка Бесконечности.</div>
            <div class="form-ad__description">Ограниченное предложение!</div>
        </div>
        <div class="form-ad__price">599</div>
        <div class="form-ad__container_flex form-ad__container_flex_vertical form-ad__container_flex_between">
            <div class="form-ad__quantity">
                <label>
                    <input class="form-ad__quantity-input" type="number" name="quantity" value="1">
                </label>
            </div>
            <button class="btn btn_success" onclick="alert('Куплено')">Купить</button>
        </div>
    </div>
</form>

<script>
const quantity = document.getElementsByClassName('form-ad__quantity');
let price = [];
for (let i = 0; i < quantity.length; i++) {
    quantity[i].addEventListener('change', (e) => {
        let card = e.target.parentNode.parentNode.parentNode.parentNode;

        if (price[i] === undefined) {
            price[i] = Number(card.children[2].textContent);
        }

        card.children[2].textContent = price[i] * Number(e.target.value);
    })
}
</script>
</body>
</html>
```
<h2 style="text-align: center">Файл 16.html</h2>

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <iframe width="560" height="315" src="https://www.youtube.com/embed/I7p27cYI7D8?si=pdSqNVeGwCCZY6k0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

    <iframe width="560" height="315" src="https://www.youtube.com/embed/JLOJx6ewvPs?si=LO-O6zO8EhvkIxU_" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

    <iframe width="560" height="315" src="https://www.youtube.com/embed/mNJxFgr2UoA?si=elAj-k0Jm1ERONyM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

    <iframe src="https://www.retrogames.cc/embed/16882-battle-city-japan.html" width="600" height="450" frameborder="no" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true" scrolling="no"></iframe>
</body>
</html>
```

<h2 style="text-align: center">Файл 17.html</h2>

```html
<!doctype html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport"
          content="width=device-width, user-scalable=no, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Document</title>
    <style>
        .slider {
            max-width: 100%;
            margin: 0 auto;
            position: relative;
        }
        .slider__wrapper {
            overflow: hidden;
        }
        .slider__container {
            display: flex;
            font-size: 7rem;
            will-change: transform;
            transition: transform 0.5s cubic-bezier(0.7, -0.22, 1, -0.24);
        }

        .slider__item {
            flex-shrink: 0;
            flex-grow: 1;
            flex-basis: 100%;
            max-width: 100%;
            height: 300px;
            justify-content: center;
            align-items: center;
            color: white;
            width: 250px;
            border-radius: 10px;
            background: #198754;
        }
        .slider__item img {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }
        .slider__btn {
            position: absolute;
            top: 50%;
            display: flex;
            flex-direction: row;
            justify-content: center;
            align-items: center;
            width: 40px;
            height: 40px;
            text-align: center;
            border: none;
            background: rgba(119, 119, 119, 0.39);
            transform: translateY(-50%);
            cursor: pointer;
        }
        .slider__btn_prev {
            left: 0;
        }
        .slider__btn_next {
            right: 0;
        }
        .slider__btn_hidden {
            display: none;
        }
    </style>
</head>
<body>
<div class="slider" style="width: 500px">
    <div class="slider__wrapper">
        <div class="slider__container" id="slider">
            <div class="slider__item">
                <img src="img/6.jpg" alt="картинка 1">
            </div>
            <div class="slider__item">
                <img src="img/1.jpg" alt="картинка 2">
            </div>
            <div class="slider__item">
                <img src="img/2.jpg" alt="картинка 3">
            </div>
            <div class="slider__item">
                <img src="img/3.jpg" alt="картинка 4">
            </div>
            <div class="slider__item">
                <img src="img/4.jpg" alt="картинка 5">
            </div>
            <div class="slider__item">
                <img src="img/5.jpg" alt="картинка 6">
            </div>
            <div class="slider__item">
                <img src="img/7.jpg" alt="картинка 7">
            </div>
            <div class="slider__item">
                <img src="img/2.jpg" alt="картинка 8">
            </div>
            <div class="slider__item">
                <img src="img/3.jpg" alt="картинка">
            </div>
            <div class="slider__item">
                <img src="img/4.jpg" alt="картинка">
            </div>
            <div class="slider__item">
                <img src="img/5.jpg" alt="картинка">
            </div>
            <div class="slider__item">
                <img src="img/6.jpg" alt="картинка">
            </div>
        </div>
    </div>
    <button class="slider__btn slider__btn_prev"></button>
    <button class="slider__btn slider__btn_next"> ></button>
</div>

<script>
    class Slider {
        constructor(nameSliderItems, btnPrev, btnNext, idSlider) {
            this.slides = document.getElementsByClassName(nameSliderItems);
            this.index = 0;
            this.width = 0;
            this.widthAll = 0;
            this.slider = document.getElementById(idSlider);
            this.btnPrev = document.getElementsByClassName(btnPrev)[0];
            this.btnNext = document.getElementsByClassName(btnNext)[0];
            this.btnPrev.addEventListener('click', this.prev.bind(this));
            this.btnNext.addEventListener('click', this.next.bind(this));
            for (let i = 0; i < this.slides.length; i++) {
                this.widthAll += this.slides[i].offsetWidth;
            }

            this.changeBtn();
        }
        show (index) {
            if (index > this.slides.length - 1) {
                console.log(index )
                this.index = 1;
                this.width = 0;
            }

            if (index < 1) {
                this.index = this.slides.length - 1
            }

            let i = 0;
            for (i; i < this.slides.length; i++) {
                this.slides[i].className = this.slides[i].className.replace(' slider__item_active ', '');
            }

            this.slides[this.index].className = this.slides[this.index].className.replace('', ' slider__item_active ');
        }

        next () {
            this.show(this.index += 1);
            this.width += this.slides[this.index].offsetWidth;
            this.changePosition()
        }

        prev () {
            this.show(this.index -= 1);
            this.width -= this.slides[this.index].offsetWidth;
            this.changePosition()
        }

        changeBtn () {
            if (this.width + this.slides[this.index].offsetWidth >= this.widthAll) {
                this.btnNext.className =  this.btnNext.className.replace('', ' slider__btn_hidden ');
            } else {
                this.btnNext.className =  this.btnNext.className.replace(' slider__btn_hidden ', '');
            }

            if (this.width === 0) {
                this.btnPrev.className =  this.btnPrev.className.replace('', ' slider__btn_hidden ');
            } else {
                this.btnPrev.className =  this.btnPrev.className.replace(' slider__btn_hidden ', '');
            }
        }

        changePosition () {
            this.changeBtn();
            this.slider.setAttribute('style', `transform: translate3d(${-this.width}px, 0px, 0px)`);
        }
     }

    let slider = new Slider('slider__item', 'slider__btn_prev', 'slider__btn_next', 'slider');
    slider.show(0);
</script>
</body>
</html>
```

<h2 style="text-align: center">Файл 18.html</h2>

```html
<!doctype html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport"
          content="width=device-width, user-scalable=no, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Document</title>
    <link href="style/form.css" rel="stylesheet">
    <link href="style/btn.css" rel="stylesheet">
    <link href="style/var.css" rel="stylesheet">
</head>
<body>
<form class="form-vertical form-vertical_round" action="" id="myForm">
    <p id="errorMessage" class="btn btn_danger" style="display: none">Пожалуйста, заполните все поля корректно.</p>

    <div class="form__header">Оставьте свои контакты мы скоро с вами свяжемся</div>
    <div class="form__group">
        <label for="name"> имя </label>
        <input class="form__input" type="text" id="name" name="name" placeholder="Иван" required>
    </div>
    <div class="form__group">
        <label for="email"> email </label>
        <input class="form__input" name="email" type="email" id="email" placeholder="email@mail.ru">
    </div>
    <div class="form__group">
        <label for="password"> пароль </label>
        <input class="form__input" type="password" id="password" name="password">
    </div>
    <button class="btn btn_success" type="submit">Отправить</button>
</form>

<script>
    document.getElementById('myForm').addEventListener('submit', function(event) {
        if (!validateForm()) {
            event.preventDefault(); // Отмена отправки формы, если данные не прошли валидацию
            document.getElementById('errorMessage').style.display = 'block';
        }
    });

    function validateForm() {
        let nameInput = document.getElementById('name');
        let emailInput = document.getElementById('email');
        let passwordInput = document.getElementById('password');

        let name = nameInput.value.trim();
        let email = emailInput.value.trim();
        let password = passwordInput.value.trim();

        let isValid = true;
        
        if (name === '') {
            nameInput.classList.add('form__input_error');
            isValid = false;
        } else {
            nameInput.classList.remove('form__input_error');
        }
        
        let emailPattern = /^[^\s@]+@[^\s@]+\.[^\s@]+$/;
        if (!email.match(emailPattern)) {
            emailInput.classList.add('form__input_error');
            isValid = false;
        } else {
            emailInput.classList.remove('form__input_error');
        }
        
        if (password.length < 6) {
            passwordInput.classList.add('form__input_error');
            isValid = false;
        } else {
            passwordInput.classList.remove('form__input_error');
        }

        return isValid;
    }
</script>
</body>
</html>
```
<h2 style="text-align: center">Файл 19.html</h2>

```html
<!doctype html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport"
          content="width=device-width, user-scalable=no, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Document</title>
    <link rel="stylesheet" href="style/var.css">
</head>
<style>
    .navbar {
        display: flex;
        align-items: center;
        justify-content: space-between;
        min-height: 50px;
        background-color: #ff6363;
        color: white;
        padding: 10px;
    }

    .burger {
        display: flex;
        position: relative;
        z-index: 100;
        align-items: center;
        justify-content: flex-end;
        width: 30px;
        height: 18px;
    }

    .burger span {
        height: 2px;
        width: 100%;
        transform: scale(1);
        background-color: white;
    }

    .burger::before, .burger::after {
        content: '';
        position: absolute;
        height: 2px;
        width: 100%;
        background-color: white;
        transition: all 0.3s ease 0s;
    }

    .burger::before {
        top: 0;
    }

    .burger::after {
        bottom: 0;
    }

    .burger.active span {
        transform: scale(0);
    }

    .burger.active::before {
        top: 50%;
        transform: rotate(-45deg) translate(0, -51%);
    }

    .burger.active::after {
        top: 50%;
        transform: rotate(45deg) translate(0, 51%);
    }

    /* Стили для мобильного меню */
    .mobile-menu {
        display: none;
        flex-direction: column;
        position: fixed;
        height: 100%;
        top: 0;
        left: 0;
        bottom: 0;
        right: 0;
        z-index: 50;
        overflow-y: auto;
        padding: 50px 40px;
        background-color: black;
        animation: burgerAnim 0.4s;
        overflow-x: hidden;
    }
    .mobile-menu>ul>li>a {
        color: #dddddd;
        text-decoration: none;
        font-size: 40px;
    }
    .mobile-menu>ul {
        display: flex;
        flex-direction: column;
    }
    .mobile-menu>ul>li {
        padding: 10px;
    }
    .mobile-menu {
        width: 100%;
        padding: 0 40px;
    }
    .mobile-menu ul {
        width: 100%;
        list-style: none;
        display: flex;
        justify-content: space-between;
    }
    @keyframes burgerAnim {
        from {
            opacity: 0;
        }
        to {
            opacity: 1;
        }
    }

    .burger.active {
        display: flex;
    }
    .mobile-menu.open {
        display: flex;
    }
</style>
<body>
<div class="navbar">
    <div class="burger">
        <span></span>
    </div>
    <nav id="mobileMenu" class="mobile-menu">
        <ul>
            <li><a href="#">Фильмы</a></li>
            <li><a href="#">Комиксы</a></li>
            <li><a href="#">Сериалы</a></li>
            <li><a href="#">Мультфильмы</a></li>
            <li><a href="#">Игры</a></li>
        </ul>
    </nav>
</div>

<script>
    document.querySelector('.burger').addEventListener('click', function() {
        this.classList.toggle('active');
        document.querySelector('.mobile-menu').classList.toggle('open')
    });
</script>
</body>
</html>
```

<h2 style="text-align: center">Файл 20.html</h2>

```html
<!doctype html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport"
          content="width=device-width, user-scalable=no, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Document</title>
</head>
<body>
<canvas id="myCanvas" width="1000" height="500"></canvas>
<script>
    var canvas = document.getElementById('myCanvas');
    var context = canvas.getContext('2d');

    // прямоугольник
    context.fillStyle = '#ff0000';
    context.fillRect(50, 50, 100, 100);

    // круг
    context.beginPath();
    context.arc(200, 100, 50, 0, 2 * Math.PI);
    context.fillStyle = '#00ff00';
    context.fill();

    // линия
    context.beginPath();
    context.moveTo(550, 150);
    context.lineTo(150, 250);
    context.strokeStyle = '#0000ff';
    context.lineWidth = 5;
    context.stroke();
</script>
</body>
</html>
```

<h2 style="text-align: center">Файл 21.html</h2>

```html
<!doctype html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport"
          content="width=device-width, user-scalable=no, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Document</title>
    <link href="style/var.css" rel="stylesheet">
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css" rel="stylesheet">
</head>
<style>
    .navbar__item {
        display: inline-block;
        vertical-align: middle;
        line-height: normal;
        padding: 10px;
        position: relative;
    }

    .navbar__item a {
        position: absolute;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
    }
</style>
<body style="display: flex; flex-direction: column; font-size: 4rem">

<div class="navbar__item">
    <i class="fa-brands fa-vk" style="color: var(--blue)"></i> vk
    <a href="https://vk.com/houston27"></a>
</div>
</body>
</html>
```
<h2 style="text-align: center">Файл 22.html</h2>

```html
<!doctype html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport"
          content="width=device-width, user-scalable=no, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Document</title>
    <link href="style/form.css" rel="stylesheet">
    <link href="style/btn.css" rel="stylesheet">
    <link href="style/var.css" rel="stylesheet">
</head>
<body>
<div style="display:flex; justify-content: center">
    <form class="form-vertical form-vertical_round" style="width: 300px" action="" id="myForm">
        <p id="errorMessage" class="btn btn_danger" style="display: none">Пожалуйста, заполните все поля корректно.</p>

        <div class="form__header">Регистрация</div>
        <div class="form__group">
            <label for="name"> имя </label>
            <input class="form__input" type="text" id="name" name="name" placeholder="Иван" required>
        </div>
        <div class="form__group">
            <label for="email"> email </label>
            <input class="form__input" name="email" type="email" id="email" placeholder="email@mail.ru">
        </div>
        <div class="form__group">
            <label for="password"> пароль </label>
            <input class="form__input" type="password" id="password" name="password">
        </div>
        <div class="form__group">
            <label for="password2"> повторите пароль </label>
            <input class="form__input" type="password" id="password2" name="password">
        </div>
        <button class="btn btn_success" type="submit">зарегистрироваться</button>
    </form>
</div>

<script>
    let message = '';
    document.getElementById('myForm').addEventListener('submit', function(event) {
        if (!validateForm()) {
            event.preventDefault(); // Отмена отправки формы, если данные не прошли валидацию
            document.getElementById('errorMessage').style.display = 'block';
            document.getElementById('errorMessage').textContent = message;
        }
    });

    function validateForm() {
        let nameInput = document.getElementById('name');
        let emailInput = document.getElementById('email');
        let passwordInput = document.getElementById('password');
        let password2Input = document.getElementById('password2');

        let name = nameInput.value.trim();
        let email = emailInput.value.trim();
        let password = passwordInput.value.trim();
        let password2 = password2Input.value.trim();

        if (name === '') {
            nameInput.classList.add('form__input_error');
            message = 'Имя не указано';
            return false;
        } else {
            nameInput.classList.remove('form__input_error');
        }

        let emailPattern = /^[^\s@]+@[^\s@]+\.[^\s@]+$/;
        if (!email.match(emailPattern)) {
            message = 'неверный формат email';
            emailInput.classList.add('form__input_error');
            return false;
        } else {
            emailInput.classList.remove('form__input_error');
        }

        if (!checkPassword(password)) {
            passwordInput.classList.add('form__input_error');
            message = 'пароль должен иметь 6 символов или больше, обязательно должны быть символы .?#%, строчные и заглавные буквы';
            return false;
        } else {
            passwordInput.classList.remove('form__input_error');
        }

        if (password !== password2) {
            passwordInput.classList.add('form__input_error');
            password2Input.classList.add('form__input_error');
            message = 'пароли не совпадают';
            return false;
        } else {
            passwordInput.classList.remove('form__input_error');
            password2Input.classList.remove('form__input_error');
        }

        return true;
    }

    function checkPassword(password) {
        if (password.length < 6) {
            return false;
        }

        if (!/[.?#%]/.test(password)) {
            return false;
        }

        if (!/[a-z]/.test(password) || !/[A-Z]/.test(password)) {
            return false;
        }

        return true;
    }
</script>
</body>
</html>
```

<h2 style="text-align: center">Файл 23.html</h2>

```html
<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport"
          content="width=device-width, user-scalable=no, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Document</title>
    <link href="style/form.css" rel="stylesheet">
    <link href="style/btn.css" rel="stylesheet">
    <link href="style/var.css" rel="stylesheet">
    <link rel="stylesheet" href="style/table.css">
</head>
<head>
    <title>Табличное представление данных</title>
    <style>
        table {
            border-collapse: collapse;
            width: 100%;
        }

        th, td {
            border: 1px solid #ddd;
            padding: 8px;
            text-align: left;
        }

        th {
            cursor: pointer;
        }

        .filter-input {
            margin-bottom: 10px;
        }
    </style>
</head>
<body>
<div style="display:flex; flex-direction:column; justify-content: center; align-items: center; text-align: center;">
    <div style="width: 80%">
        <h1>Сортировка</h1>
        <label>
            <input type="text" id="filterInput" class="filter-input form__input" placeholder="Фильтр">
        </label>

        <table id="dataTable">
            <thead>
            <tr>
                <th onclick="sortTable(0)">Фильм</th>
                <th onclick="sortTable(1)">Год</th>
                <th onclick="sortTable(2)">Фаза</th>
            </tr>
            </thead>
            <tbody>
            <tr>
                <td>Железный человек</td>
                <td>2008</td>
                <td>1</td>
            </tr>
            <tr>
                <td>Невероятный Халк</td>
                <td>2008</td>
                <td>1</td>
            </tr>
            <tr>
                <td>Железный Человек 3</td>
                <td>2013</td>
                <td>2</td>
            </tr>
            <tr>
                <td>мстители: Финал</td>
                <td>2019</td>
                <td>3</td>
            </tr>
            <tr>
                <td>Человек-Паук: Нет пути домой</td>
                <td>2021</td>
                <td>4</td>
            </tr>
            </tbody>
        </table>
    </div>
</div>


<script>
    function sortTable(columnIndex) {
        let table, rows, switching, i, x, y, shouldSwitch;
        table = document.getElementById("dataTable");
        switching = true;

        while (switching) {
            switching = false;
            rows = table.getElementsByTagName("tr");

            for (i = 1; i < (rows.length - 1); i++) {
                shouldSwitch = false;
                x = rows[i].getElementsByTagName("td")[columnIndex];
                y = rows[i + 1].getElementsByTagName("td")[columnIndex];

                if (x.innerHTML.toLowerCase() > y.innerHTML.toLowerCase()) {
                    shouldSwitch = true;
                    break;
                }
            }

            if (shouldSwitch) {
                rows[i].parentNode.insertBefore(rows[i + 1], rows[i]);
                switching = true;
            }
        }
    }

    document.getElementById("filterInput").addEventListener("input", function() {
        let filterValue = this.value.toLowerCase();
        let table = document.getElementById("dataTable");
        let rows = table.getElementsByTagName("tr");

        for (let i = 1; i < rows.length; i++) {
            let rowData = rows[i].getElementsByTagName("td");
            let showRow = false;

            for (let j = 0; j < rowData.length; j++) {
                let cellData = rowData[j].innerHTML.toLowerCase();

                if (cellData.indexOf(filterValue) > -1) {
                    showRow = true;
                    break;
                }
            }

            rows[i].style.display = showRow ? "" : "none";
        }
    });
</script>
</body>
</html>
```
<h2 style="text-align: center">Файл 24.html</h2>

```html
<!doctype html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport"
          content="width=device-width, user-scalable=no, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Montserrat+Alternates:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap"
          rel="stylesheet">
    <title>Document</title>
    <style>
        * {
            font-family: "Montserrat Alternates", sans-serif;
            font-weight: bold;
            font-style: normal;
        }
    </style>
</head>
<body>
    <h1>Перчатка Бесконечности</h1>

    <p>Металлическая перчатка для левой руки, выкованная из металла Уру, способная поглотить силу всех шести Камней Бесконечности, и предназначенная для использования Камней Бесконечности. Металл, из которого состоит Перчатка, позволяет владельцу менее болезненно переносить воздействие Камней Бесконечности на себе.</p>
    
    <h2>Камни Бесконечности</h2>
    
    <p>это шесть сингулярностей — остаточных систем, спрессованных в слитки кристаллической формы, образовавшиеся во время возникновения Вселенной в процессе Большого Взрыва.</p>
    
    <h3>Список камней</h3>
    
    <ul>
        <li>Фиолетовый - камень силы</li>
        <li>Синий - камень пространства</li>
        <li>Красный - камень реальноси</li>
        <li>Оранжевый - камень души</li>
        <li>Зелёный - камень времени</li>
        <li>Жёлтый - камень разума</li>
    </ul>
    
    <p>Примечание: цвет камней и их количество написано для Земли-199999 и подобных ей Земель</p>
    
    <h3>Фото перчатки со всеми камнями</h3>
</body>
</html>
```

<h2 style="text-align: center">Файл 25.html</h2>

```html
<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport"
          content="width=device-width, user-scalable=no, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Document</title>
    <link rel="stylesheet" href="style/table.css">
    <style>
        .drag-item {
            width: 100px;
            height: 100px;
            padding: 10px;
            text-align: center;
            background-color: #f1f1f1;
            border: 1px solid #ccc;
            border-radius: 4px;
            cursor: move;
            text-wrap: normal;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            z-index: 50;
        }

        .drop-area {
            display: flex;
            position: relative;
            flex-direction: row;
            justify-content: flex-start;
            align-content: start;
            flex-wrap: wrap;
            min-height: 500px;
            width: 80%;
            background-color: #e9e9e9;
            border: 2px dashed #aaa;
            border-radius: 4px;
            margin-top: 20px;
            padding: 10px;
            gap:15px;
        }

        .drop-area__wrap {
            display: flex;
            flex-direction: column;
        }

        .drop-area__center {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            cursor: default;
        }
    </style>
</head>
<body>
<h1>Drag and Drop</h1>

<div style="display: flex; flex-wrap: wrap; flex-direction: row; gap: 15px;">
    <div class="drag-item" draggable="true">
        <span>Перетащи 1</span>
    </div>
    <div class="drag-item" draggable="true">
        <span>Перетащи 2</span>
    </div>
    <div class="drag-item" draggable="true">
        <span>Перетащи 3</span>
    </div>
    <div class="drag-item" draggable="true">
        <span>Перетащи 4</span>
    </div>



</div>

<div class="drop-area__wrap" style="display: flex; flex-direction: column;">
    <div class="drop-area" id="dropArea">
        <span class="drop-area__center">Жду</span>
    </div>
</div>
<script>
    let dragItem = document.getElementsByClassName('drag-item');
    for (let i = 0; i < dragItem.length; i++) {
        dragItem[i].id = `drag${i}`
        dragItem[i].addEventListener('dragstart', drag);
    }

    let dropArea = document.getElementById('dropArea');

    dropArea.addEventListener('dragover', allowDrop);
    dropArea.addEventListener('drop', drop);

    function allowDrop(event) {
        event.preventDefault();
    }

    function drag(event) {
        event.dataTransfer.setData('text', event.target.id);
    }

    function drop(event) {
        event.preventDefault();
        let data = event.dataTransfer.getData('text');
        let draggedItem = document.getElementById(data);

        if (event.target.className === 'drop-area') {
            event.target.appendChild(draggedItem);
        }
    }
</script>
</body>
</html>
```
<h2 style="text-align: center">Файл 26.html</h2>

```html
<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport"
          content="width=device-width, user-scalable=no, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <link rel="stylesheet" href="style/var.css">
    <title>Document</title>

    <style>
        body {
            font-family: "Calibri Light",serif;
            font-weight: bold;
            background-color: var(--blue);
        }
        .cards {
            padding: 10px;
        }
        .cards__grid {
            display: grid;
            grid-template-columns: repeat(4, 1fr);
            grid-template-rows: repeat(2, 1fr);
            grid-gap: 10px;
        }
        .card__grid_1 {
            display: grid;
            grid-column-start: 1;
            grid-column-end: 3;
            grid-row-start: 1;
            grid-row-end: 3;
        }
        .card__grid_2 {
            display: grid;
            grid-column-start: 3;
            grid-column-end: 5;
            grid-row-start: 1;
            grid-row-end: 1;
        }
        .card__grid_3 {
            display: grid;
            grid-column-start: 3;
            grid-column-end: 3;
            grid-row-start: 2;
            grid-row-end: 2;
        }
        .card__grid_4 {
            display: grid;
            grid-column-start: 4;
            grid-column-end: 4;
            grid-row-start: 2;
            grid-row-end: 2;
        }
        .card {
            background-color: rgba(0, 0, 0, 0.66);
            padding: 15px;
            border-radius: var(--main-round-border);
        }
        .card__first {
            background-color: rgba(255, 69, 0, 0.91);
        }
        .card {
            display: flex;
            flex-direction: column;
            justify-content: space-between;
            gap: 50px;
            color: white;
        }
        .card__link {
            width: 20px;
            height: 20px;
            padding: 15px;
            text-align: center;
            border-radius: var(--main-round-border);
            background-color: var(--orange);
        }
        .card__link_first {
            background-color: rgba(0, 0, 0, 0.93);
            max-width: max-content;
            max-height: max-content;
            width: auto;
            height: auto;
            padding: 20px 25px;
        }
        .text-big {
            font-size: 3rem;
        }
        .text-small {
            font-size: 2rem;
        }
        .text-xs {
            font-size: 1.3rem;
        }
        @media screen and (max-width: 768px) {
            .cards__flex {
                display: flex;
                flex-direction: column;
            }
        }
    </style>
</head>
<body>
<div class="cards">
    <div class="cards__grid cards__flex">
        <div class="card card__grid_1 card__first">
            <div class="text-big">
                Комиксы MARVEL
            </div>
            <div class="card__link card__link_first"><div class="text-xs">Подберём по вуксу</div></div>
        </div>
        <div class="card card__grid_2">
            <div class="text-small">
                Логан
            </div>

            <div class="card__link">></div>
        </div>
        <div class="card card__grid_3">
            <div class="text-small">
                Мстители
            </div>

            <div class="card__link">></div>
        </div>
        <div class="card card__grid_4">
            <div class="text-small">
                Человек-Паук
            </div>

            <div class="card__link">></div>
        </div>
        
    </div>
</div>
</body>
</html>
```


<h1 align = "center">Вывод</h1>
<p>По итогу проделанной лабораторной работы, были созданы страницы по заданиям с использованием HTML, CSS</p>
