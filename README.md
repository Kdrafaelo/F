<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <!-- Fonte -->
  <link href="https://fonts.googleapis.com/css?family=Roboto:300,400,700&display=swap" rel="stylesheet">
  <!-- Estilos -->
  <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/css/bootstrap.min.css" integrity="sha384-Vkoo8x4CGsO3+Hhxv8T/Q5PaXtkKtu6ug5TOeNV6gBiFeWPGFN9MuhOf23Q9Ifjh" crossorigin="anonymous">
  <link rel="stylesheet" href="css/styles.css">
  <!-- Scripts (jQuery não pode ser o slim que vem do Boostrap) -->
  <script
  src="https://code.jquery.com/jquery-3.4.1.min.js"
  integrity="sha256-CSXorXvZcTkaix6Yvo6HppcZGetbYMGWSFlBw8HfCJo="
  crossorigin="anonymous"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js" integrity="sha384-Q6E9RHvbIyZFJoft+2mJbHaEWldlvI9IOYy5n3zV9zzTtmI3UksdQRVvoxMfooAo" crossorigin="anonymous"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/js/bootstrap.min.js" integrity="sha384-wfSDF2E50Y2D1uUdj0O3uMBJnjuUD4Ih7YwaYd1iqfktj0Uod8GCExl3Og8ifwB6" crossorigin="anonymous"></script>
  <!-- Font Awesome -->
  <script src="https://kit.fontawesome.com/bf7e05c402.js" crossorigin="anonymous"></script>
  <!-- Progress Bar -->
  <script src="progressbar.js"></script>
  <!-- Parallax -->
  <script src="https://cdn.jsdelivr.net/parallax.js/1.4.2/parallax.min.js"></script>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!-- Favicon: -->
    <link rel="shortcut icon" href="./imagens/favicon.ico.png" type="image/x-icon">  <!--https://www.flaticon.com/br/buscar?word=dev&order_by=4-->
    <!--Bootstrap CSS-->
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css" integrity="sha384-MCw98/SFnGE8fJT3GXwEOngsV7Zt27NXFoaoApmYm81iuXoPkFOJwJ8ERdknLPMO" crossorigin="anonymous">
    
    <link rel="stylesheet" href="assets/reset.css">
    <link rel="stylesheet" href="assets/responsividade.css">
    <link rel="stylesheet" href="assets/menu.css">
    <link rel="stylesheet" href="assets/index.css"> 
    <link rel="stylesheet" href="assets/footer.css">
    <title>Home Frontenders</title>
</head>

<body>
    <header>
        <div class="container">

            <div class="menu-section on">
                <div class="menu-toggle">
                    <div class="one"></div>
                    <div class="two"></div>
                    <div class="three"></div>
                </div>
                <nav id="nav" class="navbar fixed-top navbar-blue bg-blue">
                    <a class="logo-index" href="index.html"><img src="assets/imagens/logo-dev2.png" alt="Logo" id="logo-index"></a>

                    <a href="index.html">Home</a>
                    <a href="servico.html">Serviço</a>
                    <a href="cadastro.html">Cadastro</a>
                    <a href="contato.html">Contato</a>
                    <a href="login.html">Login</a>
                    <a href="recuperacao-senha.html">Recuperar Senha</a>
                </nav>
            </div>
        </div>
        <section id="container-trasition">
            <div id="divBusca">
                <input type="text" id="txtBusca" placeholder="Buscar..."/>
                <a href="#">
                <img id="lupa-busca" src="assets/imagens/lupa.png" alt="lupa">
                </a>
            </div>
        </section>
    </header>
    <main>
        <div class="container-fluid">
          <!-- slider -->
          <div id="mainSlider" class="carousel slide" data-ride="carousel">
            <ol class="carousel-indicators">
              <li data-target="#mainSlider" data-slide-to="0" class="active"></li>
              <li data-target="#mainSlider" data-slide-to="1"></li>
              <li data-target="#mainSlider" data-slide-to="2"></li>
            </ol>
            <div class="carousel-inner">
              <div class="carousel-item active">
                <img src="assets/imagens/img/banner-1.jpg" class="d-block w-100" alt="Projetos de e-commerce">
    
                <!-- tirar classe d-none -->
    
                <div class="carousel-caption d-md-block">
                  <h2>Batendo cabeça com JavaScripts?</h5>
                  <p>Conte conosco.</p>
                  <a href="#" class="main-btn">Ver portfólio</a>
                </div>
              </div>
              <div class="carousel-item">
                <img src="assets/imagens/img/banner-2.jpg" class="d-block w-100" alt="Engenharia de software">
                <div class="carousel-caption d-md-block">
                  <h2>Está querendo tirar o projeto do papel?</h5>
                  <p>Nossa equipe de engenharia de software está pronta para lhe atender.</p>
                  <a href="#" class="main-btn">Entre em contato</a>
                </div>
              </div>
              <div class="carousel-item">
                <img src="assets/imagens/img/banner-3.jpg" class="d-block w-100" alt="Manutenção em software">
                <div class="carousel-caption d-md-block">
                  <h2>Está buscando manutenção no seu software?</h5>
                  <p>Frontenders conta com engenheiros qualificados para resolver seu problema.</p>
                  <a href="#" class="main-btn">Entre em contato</a>
                </div>
              </div>
            </div>
            <a class="carousel-control-prev" href="#mainSlider" role="button" data-slide="prev">
              <span class="carousel-control-prev-icon" aria-hidden="true"></span>
              <span class="sr-only">Previous</span>
            </a>
            <a class="carousel-control-next" href="#mainSlider" role="button" data-slide="next">
              <span class="carousel-control-next-icon" aria-hidden="true"></span>
              <span class="sr-only">Next</span>
            </a>
          </div>
          <!-- Sobre a empresa -->
          <div id="about-area">
            <div class="container">
                <div class="row">
                  <div class="col-12"> 
                    <h3 class="main-title">Sobre Frontenders</h3>
                  </div>
                  <div class="col-md-6">
                    <img class="img-fluid" src="assets/imagens/img/agencia.jpg" alt="Agência hDC">
                  </div>
                  <div class="col-md-6">
                    <h3 class="about-title">Uma agência que pensa no futuro</h3>
                    <p>Nossos projetos são adaptados ao cliente e seu propósito.</p>
                    <p>Após a especificação do projetos os arquitetos de software definirão as melhores tecnologias para seu projeto.</p>
                    <p>E nossos designers trabalharão na sua interface/layout para impulsionar o negócio.</p>
                    <p>Veja outros diferenciais:</p>
                    <ul id="about-list">
                      <li><i class="fas fa-check"></i> Utilização de Machine Learning / AI</li>
                      <li><i class="fas fa-check"></i> Layout responsivo para todos os dispositivos</li>
                      <li><i class="fas fa-check"></i> Integração com diversos sistemas do mercado</li>
                      <li><i class="fas fa-check"></i> Sistema de pagamento próprio</li>
                      <li><i class="fas fa-check"></i> Desenvolvimento com metodologia ágil</li>
                    </ul>
                  </div>
                </div>
              </div>
          </div>
         
          <!-- Dados da empresa -->
          <div id="data-area">
            <div class="container">
              <div class="row">
                <div class="col-md-3 col-xs-6 circle-box">
                  <div id="circleA"></div>
                  <p>Projetos entregues</p>
                </div>
                <div class="col-md-3 col-xs-6 circle-box">
                  <div id="circleB"></div>
                  <p>Clientes Felizes</p>
                </div>
                <div class="col-md-3 col-xs-6 circle-box">
                  <div id="circleC"></div>
                  <p>Colaboradores</p>
                </div>  
                <div class="col-md-3 col-xs-6 circle-box">
                  <div id="circleD"></div>
                  <p>Cafézinhos</p>
                </div>
              </div>
            </div>
          </div>
          
            <!-- Portfólio -->
          <div id="portfolio-area">
            <div class="container">
              <div class="row">
                <div class="col-md-12">
                  <h3 class="main-title">Conheça nossos projetos</h3>
                </div>
                <div class="col-md-12" id="filter-btn-box">
                  <button class="main-btn filter-btn active" id="all-btn">Todos</button>
                  <button class="main-btn filter-btn" id="dev-btn">Desenvolvimento</button>
                  <button class="main-btn filter-btn" id="dsg-btn">Design</button>
                  <button class="main-btn filter-btn" id="seo-btn">SEO</button>
                </div>
                <div class="col-md-4 project-box dev">
                  <img src="assets/imagens/img/proj1.jpg" class="img-fluid" alt="Projeto 1">
                </div>
                <div class="col-md-4 project-box dsg">
                  <img src="assets/imagens/img/proj2.jpg" class="img-fluid" alt="Projeto 2">
                </div>
                <div class="col-md-4 project-box seo">
                  <img src="assets/imagens/img/proj3.jpg" class="img-fluid" alt="Projeto 3">
                </div>
                <div class="col-md-4 project-box dev">
                  <img src="assets/imagens/img/proj4.jpg" class="img-fluid" alt="Projeto 4">
                </div>
                <div class="col-md-4 project-box dsg">
                  <img src="assets/imagens/img/proj5.jpg" class="img-fluid" alt="Projeto 5">
                </div>
                <div class="col-md-4 project-box seo">
                  <img src="assets/imagens/img/proj6.jpg" class="img-fluid" alt="Projeto 6">
                </div>
              </div>
            </div>
          </div>
          
        </div>
      </main>
    <footer class="footer-container">
        <p class="paragrafo-footer">
            <span class="span-footer">Site Desenvolvido por:</span>
            <a class="footer-flex" href="https://github.com/Perasinho" target="_blank">Gabriel
                <img class="media" src="assets/imagens/github.png" alt="GitHub">
            </a>
            <a class="footer-flex" href="https://github.com/leticiacosta003" target="_blank">Letícia
                <img class="media" src="assets/imagens/github.png" alt="GitHub">
            </a>
            <a class="footer-flex" href="https://github.com/Kdrafaelo" target="_blank">Rafaela
                <img class="media" src="assets/imagens/github.png" alt="GitHub">
            </a>
            <a class="footer-flex" href="https://github.com/regiane18" target="_blank">Regiane
                <img  class="media" src="assets/imagens/github.png" alt="GitHub">
            </a>
            <a class="footer-flex" href="https://github.com/thaynalp" target="_blank">Thayná
                <img class="media" src="assets/imagens/github.png" alt="GitHub">
            </a>
        </p>
    </footer>
    <!-- Scripts do projeto -->
    <script src="scripts/script.js"></script>
    <script src="scripts/menu.js"></script>
    <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.3/umd/popper.min.js" integrity="sha384-ZMP7rVo3mIykV+2+9J3UJ46jBk0WLaUAdn689aCwoqbBJiSnjAK/l8WvCWPIPm49" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/js/bootstrap.min.js" integrity="sha384-ChfqqxuZUCnJSK3+MXmPNIyE6ZbWh2IMqE241rYiqJxyMiZ6OW/JmZQ5stwEULTy" crossorigin="anonymous"></script>
    
</body>
</html>
