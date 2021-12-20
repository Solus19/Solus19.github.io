<!DOCTYPE html>
<html>
<head>

  <script src="java.js"></script>
  <script>var str=promt("test")</script>


  <meta charset="UTF-8">
  <title>Четыре правила вёрстки</title>
  <link rel="stylesheet" href="style.css">
  <link rel="icon" type="image" href="https://code.s3.yandex.net/web-code/rules-favicon.ico">
</head>
<body id="b0">
  <header class='header'>
    <div class='overlay'>
      <h1 class='header-title'>Четыре правила вёрстки</h1>
    </div>
  </header>

  <section class='content'>
    <div class='card'>
      <img src="https://pictures.s3.yandex.net/frontend-developer/free-course/card-1.jpg" class='card-image'  onclick="testFunction()">
      <h3 class='card-title'>
        Пустота
      </h3>
      <p class='card-text'>
        Простое правило, которое часто нарушают: ставить рядом элементы с похожим смыслом и окружать их пустым пространством. Пустота — мощное средство воздействия.
      </p>
    </div>
    
    <div class="card no-right-margin">
      <img src="https://pictures.s3.yandex.net/frontend-developer/free-course/card-2.jpg" class='card-image'>
      <h3 class='card-title'>
        Сетка
      </h3>
        <p class='card-text'>
          Размеры элементов и расстояния между ними укладываются в гармоничную схему — её называют сеткой. Если элемент выпадает, зритель может это заметить.
        </p>
      </div>
    
    <div class='card'>
      <img src="https://pictures.s3.yandex.net/frontend-developer/free-course/card-3.jpg" class='card-image'>
      <h3 class='card-title'>
        Шрифты
      </h3>
      <p class='card-text'>
        Не больше трёх шрифтов на сайт. Один для заголовков, второй — для всех остальных текстов, третий — для выделения важных слов. Должно хватить.
      </p>
    </div>
    
    <div class="card no-right-margin">
         <img src=" https://pictures.s3.yandex.net/frontend-developer/free-course/card-4.jpg" class='card-image'>
      <h3 class='card-title'>
        Цвета
      </h3>
      <p class='card-text'>
        Обычно на сайте два цвета: ведущий и акцентный. Подобрать удачную цветовую пару можно за счёт насмотренности или специальных инструментов. 
      </p>
    </div>
    
  </section>
  <footer class='footer'>
    <h4 class='footer-author'>
      Сделано из лени
    </h4>
  </footer>

</body>
</html>



