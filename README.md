<!DOCTYPE html>
<html lang="ru">
<head>
<meta charset="UTF-8">
<title>Футбол для всех</title>
<style>
  body {
    font-family: Arial, sans-serif;
    background-color: #c7f0a2; 
    color: #000;
    margin: 0;
    padding: 0;
  }
  header {
    background-color: #2e7d32;
    color: white;
    padding: 20px;
    text-align: center;
  }
  nav {
    background-color: #81c784;
    padding: 10px;
    text-align: center;
  }
  nav a {
    color: white;
    margin: 0 15px;
    text-decoration: none;
    font-weight: bold;
  }
  nav a:hover {
    text-decoration: underline;
  }
  section {
    max-width: 800px;
    margin: 20px auto;
    padding: 20px;
    background-color: #ffffffcc;
    border-radius: 10px;
  }
  h2 {
    color: #2e7d32;
  }
  img {
    max-width: 100%;
    height: auto;
    margin: 10px 0;
    border: 2px solid #2e7d32;
    border-radius: 5px;
  }
  .card-yellow {
    background-color: #fff176;
    padding: 10px;
    display: inline-block;
    margin: 5px 0;
    font-weight: bold;
    border-radius: 5px;
  }
  .card-red {
    background-color: #e57373;
    padding: 10px;
    display: inline-block;
    margin: 5px 0;
    font-weight: bold;
    border-radius: 5px;
    color: white;
  }
</style>
</head>
<body>

<header>
  <h1>Футбол для всех</h1>
  <p>Простое объяснение основных правил футбола</p>
</header>

<nav>
  <a href="#offsides">Офсайд</a>
  <a href="#penalty">Пенальти</a>
  <a href="#freekick">Штрафной удар</a>
  <a href="#out">Аут</a>
  <a href="#corner">Угловой</a>
  <a href="#cards">Карточки</a>
</nav>

<section id="offsides">
  <h2>Офсайд</h2>
  <p>Игрок не должен находиться ближе к воротам соперника, чем мяч и предпоследний защитник в момент передачи. Проще: нельзя стоять у ворот и ждать мяч.</p>
  <img src="https://footbolno.ru/wp-content/uploads/2016/07/line-ofside.jpg.webp" alt="Схема офсайда">
</section>

<section id="penalty">
  <h2>Пенальти</h2>
  <p>Назначается за нарушение правил в штрафной площади. Удар выполняется с 11 метров, один на один с вратарём.</p>
  <img src="https://footbolno.ru/wp-content/uploads/2020/04/Rasstoyanie-probitiya-penalti.jpg" alt="Пенальти">
</section>

<section id="freekick">
  <h2>Штрафной удар</h2>
  <p>Назначается за нарушение правил вне штрафной площади. Игрок выполняет удар с места нарушения.</p>
  <img src="https://photobooth.cdn.sports.ru/preset/post/f/3f/907ac207d4205b4804a5536f4dba7.png"Штрафной удар">
</section>

<section id="out">
  <h2>Аут</h2>
  <p>Если мяч полностью пересёк боковую линию, он вводится в игру руками игроком соперника.</p>
  <img src="https://lh4.googleusercontent.com/proxy/yz0NukUAgCSxxxhQsHK2UAbNPKG14tBSLXEp1pFEjEy_vL2szH9IoQtyCyMfxZxkDvFH73_AjIikLDTnLsxLogkuSGwNGwwNORFnwA1PmOCOcTdFu1FYobpC7Yb159dN62ha" alt="Аут">
</section>

<section id="corner">
  <h2>Угловой</h2>
  <p>Если мяч полностью пересёк линию ворот от игрока защитника, выполняется удар с угла поля.</p>
  <img src="https://ice-profy.ru/wp-content/uploads/2023/07/3-8-1024x576.jpg" alt="Угловой">
</section>

<section id="cards">
  <h2>Карточки</h2>
  <p>Жёлтая карточка — предупреждение:</p>
  <div class="card-yellow">ЖЁЛТАЯ</div>
  <p>Красная карточка — удаление игрока с поля:</p>
  <div class="card-red">КРАСНАЯ</div>
</section>

</body>
</html>
