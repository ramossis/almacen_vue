<template>
  <div id="app">
    <div class="container">
      <nav class="navbar navbar-expand-lg navbar-light bg-light">
  <div class="container-fluid">
    <a class="navbar-brand" href="#">Alamacenes Noodles</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav me-auto mb-2 mb-lg-0">
        <li class="nav-item">
          <a class="nav-link active" aria-current="page" href="#">Inicio</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Contactos</a>
        </li>
        <li class="nav-item dropdown">
          <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
            Categorias
          </a>
          <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
            <li><a class="dropdown-item" href="#">Fideos</a></li>
            <li><a class="dropdown-item" href="#">Aceites</a></li>
            <li><a class="dropdown-item" href="#">Limpieza</a></li>
            <li><a class="dropdown-item" href="#">Articulos En General</a></li>
            
          </ul>
        </li>
        <li class="nav-item">
          <a class="nav-link">Reportes</a>
        </li>
      </ul>
      <form class="d-flex">
        <input class="form-control me-2" type="search" placeholder="Buscar" aria-label="Search">
        <button class="btn btn-outline-success" type="submit">Buscar</button>
      </form>
    </div>
  </div>
</nav>
<div class="row">
  <div class="col">
    <div id="carouselExample" class="carousel slide" data-ride="carousel">
                <ol class="carousel-indicators">
                    <li data-target="#carouselExample" data-slide-to="0" class="active"></li>
                    <li data-target="#carouselExample" data-slide-to="1"></li>
                </ol>
                <div class="carousel-inner">
                    <div class="carousel-item active">
                      <img src="./public/img/kisspng-fast-food-convenience-food-junk-food-packaging-and-abarrotes-5b4003bc2f6470.3223172015309219161941.png" class="d-block w-100">
                    </div>
                    <div class="carousel-item">
                      <img src="./public/img/kisspng-vegetable-oil-soybean-oil-food-holy-anointing-oil-5d2d7cd8d05582.5651314415632621688534.png" class="d-block w-100">
                    </div>
                </div>
                <a href="#carouselExample" class="carousel-control-prev" role="button" data-slide="prev">
                    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                    <span class="visualy-hidden"></span>
                </a>
                <a href="#carouselExample" class="carousel-control-next" role="button" data-slide="next">
                  <span class="carousel-control-next-icon" aria-hidden="true"></span>
                  <span class="visualy-hidden"></span>
                </a>
            </div>
  </div>
</div>
<div class="row">
  <div class="col-6">
    <a href="" class="link-info">
      <h2>lorem </h2>
    <p class="lead">
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Accusamus amet soluta quia eius rem quod exercitationem beatae. Exercitationem, fuga culpa nihil aspernatur nulla dolores. Vitae reiciendis possimus architecto perferendis voluptates.
    </p>
    </a>
  </div>

  <div class="col-6">
    <a href="">
      <h2>lorem </h2>
    <p class="lead">
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Accusamus amet soluta quia eius rem quod exercitationem beatae. Exercitationem, fuga culpa nihil aspernatur nulla dolores. Vitae reiciendis possimus architecto perferendis voluptates.
    </p>
    </a>
  </div>
</div>
<div class="row">
  <div class="col-12">
    <h2>Contactanos</h2>
    <form>
  <div class="mb-3">
    <label for="exampleInputEmail1" class="form-label">Email address</label>
    <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp">
    <div id="emailHelp" class="form-text">We'll never share your email with anyone else.</div>
  </div>
  <div class="mb-3">
    <label for="exampleInputPassword1" class="form-label">Password</label>
    <input type="password" class="form-control" id="exampleInputPassword1">
  </div>
  <div class="mb-3 form-check">
    <input type="checkbox" class="form-check-input" id="exampleCheck1">
    <label class="form-check-label" for="exampleCheck1">Check me out</label>
  </div>
  <button type="submit" class="btn btn-primary">Submit</button>
</form>
  </div>
</div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'app',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>
