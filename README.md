<!doctype html>
<html lang="ru">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>AnimalHome</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
    <link rel="stylesheet" type="text/css" href="css/style.css">
  </head>
  <body>
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
      <div class="container-fluid">
        <a class="navbar-brand" href="#">AnimalHome</a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav me-auto">
            <li class="nav-item"><a class="nav-link" href="#dogs">Взять собаку</a></li>
            <li class="nav-item"><a class="nav-link" href="#cats">Взять кошку</a></li>
            <li class="nav-item"><a class="nav-link" href="#about">О нас</a></li>
            <li class="nav-item"><a class="nav-link" href="#donate">Пожертвовать</a></li>
            <li class="nav-item"><a class="nav-link" href="#about">Контакты</a></li>
          </ul>
        </div>
      </div>
    </nav>
<section>
  <div class="container text-center">
    <h1 class="mb-4">Добро пожаловать в AnimalHome</h1>
    <div class="row align-items-center justify-content-center">
      <div class="col-md-8">
        <p class="text-start">Мопсы – это преданные и добрые собаки, которые станут прекрасными компаньонами. Они обожают играть, любят людей и отлично подходят для проживания в квартире.</p>
      </div>
      <div class="col-md-4">
        <img src="https://petplays.com.ua/wp-content/uploads/2024/01/vertical-selective-focus-closeup-pug-dog-sitting-ground.jpg" class="w-100 rounded" alt="Мопс">
      </div>
    </div>
  </div>
</section>
    
  <section class="container mt-5" id="carousel">
      <div id="animalCarousel" class="carousel slide" data-bs-ride="carousel">
        <div class="carousel-indicators">
          <button type="button" data-bs-target="#animalCarousel" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
          <button type="button" data-bs-target="#animalCarousel" data-bs-slide-to="1" aria-label="Slide 2"></button>
          <button type="button" data-bs-target="#animalCarousel" data-bs-slide-to="2" aria-label="Slide 3"></button>
          <button type="button" data-bs-target="#animalCarousel" data-bs-slide-to="3" aria-label="Slide 4"></button>
          <button type="button" data-bs-target="#animalCarousel" data-bs-slide-to="4" aria-label="Slide 5"></button>
          <button type="button" data-bs-target="#animalCarousel" data-bs-slide-to="5" aria-label="Slide 6"></button>
        </div>
        <div class="carousel-inner">
          <div class="carousel-item active">
            <img src="https://tomall.ru/dog/foto/b/139-p.jpg" class="d-block w-100" alt="retriever">
          </div>
          <div class="carousel-item">
            <img src="https://as2.ftcdn.net/jpg/01/35/48/35/1000_F_135483510_2HQ2Fysi8QQVPAfLQlW6rIiN8NzlpPHh.jpg" class="d-block w-100" alt="scottish fold">
          </div>
          <div class="carousel-item">
            <img src="https://www.bethowen.ru/upload/medialibrary/c58/c586b93d9568b9af0acb7229f2b44b35.jpg" class="d-block w-100" alt="british shorthair">
          </div>
          <div class="carousel-item">
            <img src="https://ajo-pet.ru/u/blog/94_big_0.jpg" class="d-block w-100" alt="siamese cat">
          </div>
          <div class="carousel-item">
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTiGo41t3Xiph2Aza_uXmdNuRT9Mv2aVwPXnA&s" class="d-block w-100" alt="german shepherd">
          </div>
          <div class="carousel-item">
            <img src="https://storage.yandexcloud.net/yac-wh-sb-prod-s3-media-03005/uploads/breed/689/d20ef42c7ee0f73d9bf43fb5c3538e9f.webp" class="d-block w-100" alt="labrador retriever">
          </div>
        </div>
        <button class="carousel-control-prev" type="button" data-bs-target="#animalCarousel" data-bs-slide="prev">
          <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        </button>
        <button class="carousel-control-next" type="button" data-bs-target="#animalCarousel" data-bs-slide="next">
          <span class="carousel-control-next-icon" aria-hidden="true"></span>
        </button>
      </div>
    </section>
 <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
    
    <section class="container mt-5" id="cats">
      <h2 class="text-center">Кошки</h2>
      <div class="row">
        <div class="col">
          <div class="card" style="width: 18rem;">
            <img class="card-img-top" src="https://as2.ftcdn.net/jpg/01/35/48/35/1000_F_135483510_2HQ2Fysi8QQVPAfLQlW6rIiN8NzlpPHh.jpg" alt="Scottish Fold">
            <div class="card-body">
              <h5 class="card-title">Скоттиш фолд</h5>
              <p class="card-text">Милый и спокойный кот с висячими ушками.</p>
              <button class="btn btn-primary" onclick="toggleDetails('cat-details')">Подробнее</button>
              <p id="cat-details" style="display:none;">Эта порода известна своей дружелюбностью и мягким характером. Отличный питомец для семьи!</p>
            </div>
          </div>
        </div>
        <div class="col">
          <div class="card" style="width: 18rem;">
            <img class="card-img-top" src="https://www.bethowen.ru/upload/medialibrary/c58/c586b93d9568b9af0acb7229f2b44b35.jpg" alt="British Shorthair">
            <div class="card-body">
              <h5 class="card-title">Британская короткошерстная</h5>
              <p class="card-text">Крупный и плюшевый кот с независимым характером.</p>
              <button class="btn btn-primary" onclick="toggleDetails('british-details')">Подробнее</button>
              <p id="british-details" style="display:none;">Эта порода известна своей силой и уравновешенным характером, отличный выбор для семьи!</p>
            </div>
          </div>
        </div>
        <div class="col">
          <div class="card" style="width: 18rem;">
            <img class="card-img-top" src="https://ajo-pet.ru/u/blog/94_big_0.jpg" alt="Siamese Cat">
            <div class="card-body">
              <h5 class="card-title">Сиамская кошка</h5>
              <p class="card-text">Активная и общительная кошка с красивыми голубыми глазами.</p>
              <button class="btn btn-primary" onclick="toggleDetails('siamese-details')">Подробнее</button>
              <p id="siamese-details" style="display:none;">Сиамские кошки очень привязаны к своим хозяевам и любят общение.</p>
            </div>
          </div>
        </div>
      </div>
    </section>
    
    <section class="container mt-5" id="dogs">
      <h2 class="text-center">Собаки</h2>
      <div class="row">
        <div class="col">
          <div class="card" style="width: 18rem;">
            <img class="card-img-top" src="https://tomall.ru/dog/foto/b/139-p.jpg" alt="Golden Retriever">
            <div class="card-body">
              <h5 class="card-title">Золотистый ретривер</h5>
              <p class="card-text">Дружелюбная и умная собака, отличный семейный друг.</p>
              <button class="btn btn-primary" onclick="toggleDetails('retriever-details')">Подробнее</button>
              <p id="retriever-details" style="display:none;">Ретриверы обожают детей и легко обучаемы!</p>
            </div>
          </div>
        </div>
        <div class="col">
          <div class="card" style="width: 18rem;">
            <img class="card-img-top" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTiGo41t3Xiph2Aza_uXmdNuRT9Mv2aVwPXnA&s" alt="German Shepherd">
            <div class="card-body">
              <h5 class="card-title">Немецкая овчарка</h5>
              <p class="card-text">Верная и умная собака, отличная для охраны и службы.</p>
              <button class="btn btn-primary" onclick="toggleDetails('germanshepherd-details')">Подробнее</button>
              <p id="germanshepherd-details" style="display:none;">Немецкие овчарки очень умны и преданы своему хозяину.</p>
            </div>
          </div>
        </div>
        <div class="col">
          <div class="card" style="width: 18rem;">
            <img class="card-img-top" src="https://storage.yandexcloud.net/yac-wh-sb-prod-s3-media-03005/uploads/breed/689/d20ef42c7ee0f73d9bf43fb5c3538e9f.webp" alt="Labrador Retriever">
            <div class="card-body">
              <h5 class="card-title">Лабрадор ретривер</h5>
              <p class="card-text">Идеальный семейный питомец, всегда дружелюбный и веселый.</p>
              <button class="btn btn-primary" onclick="toggleDetails('labrador-details')">Подробнее</button>
              <p id="labrador-details" style="display:none;">Лабрадоры обожают детей и активный образ жизни.</p>
            </div>
          </div>
        </div>
      </div>
    </section>
    
    <section class="container mt-5" id="donate">
      <h2 class="text-center">Форма обращения</h2>
      <form>
        <div class="mb-3">
          <label for="userName" class="form-label">Ваше имя</label>
          <input type="text" class="form-control" id="userName" required>
        </div>
        <div class="mb-3">
          <label for="userEmail" class="form-label">Ваш Email</label>
          <input type="email" class="form-control" id="userEmail" required>
        </div>
        <div class="mb-3">
          <label for="actionType" class="form-label">Выберите действие</label>
          <select class="form-control" id="actionType">
            <option value="adopt">Забрать животное</option>
            <option value="donate">Сделать пожертвование</option>
          </select>
        </div>
        <div class="mb-3" id="amountField" style="display:none;">
          <label for="amount" class="form-label">Сумма</label>
          <input type="number" class="form-control" id="amount">
        </div>
        <button type="submit" class="btn btn-primary">Отправить</button>
      </form>
    </section>
    
    <footer class="bg-dark text-light text-center py-3 mt-5" id="about">
      <p>О нас: AnimalHome помогает бездомным животным найти любящие семьи.</p>
      <p>Адрес: ул. Приютная, 10, г. Москва</p>
      <p>Время работы: Пн-Вс 09:00 - 20:00</p>
      <p>Телефон: +7 (999) 123-45-67</p>
      <p>Email: contact@animalhome.ru</p>
    </footer>
    
    <script>
      function toggleDetails(id) {
        var details = document.getElementById(id);
        details.style.display = details.style.display === "none" ? "block" : "none";
      }
      document.getElementById('actionType').addEventListener('change', function() {
        document.getElementById('amountField').style.display = this.value === 'donate' ? 'block' : 'none';
      });
    </script>


  </body>
</html>
