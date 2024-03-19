# landingpage

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Consultoria Para Saude</title>
  <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
  <link rel="stylesheet" href="a.css">
</head>
<body>

  <nav class="navbar navbar-expand-xl navbar-dark bg-dark">
    <div class="container">
      <div class="navbar-brand"> Consultoria</div>
      
       
     
        <ul class="navbar-nav ml-auto">
          <li class="nav-item">
            <a class="nav-link" href="#benefits">Benefícios</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#testimonials">Depoimentos</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#contact">Contato</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>

  <header class="jumbotron text-center">
    <div class="container">
      <h1>Consultoria Na saúde</h1>
      <p class="lead">Obtenha orientação profissional para ficar saudavel.</p>
      <a class="btn btn-primary btn-lg" href="#contact" role="button">Agende uma Consulta Gratuita</a>
    </div>
  </header>

  <section id="benefits">
    <div class="container">
      <h2 class="text-center ">Benefícios da Consultoria </h2>
      <div class="row">
        <div class="col-md-4">
          <div class="card">
            <div class="card-body">
              <h5 class="card-title">Planejamento </h5>
              <p class="card-text">Desenvolvemos um plano sob medida para suas metas.</p>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card">
            <div class="card-body">
              <h5 class="card-title">Educação Alimentar</h5>
              <p class="card-text">Aprenda habilidades essenciais para gerenciar suas refeições</p>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card">
            <div class="card-body">
              <h5 class="card-title">Acompanhamento Profissional</h5>
              <p class="card-text">Tenha suporte contínuo de um medico e nutricionista.</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <section id="testimonials" class="bg-light">
    <div class="container">
      <h2 class="text-center mb-4 ">Depoimentos</h2>
      <div class="row">
        <div class="col-md-4">
          <div class="card">
            <div class="card-body">
              <p class="card-text">"A consultoria financeira me ajudou a alcançar minhas metas. Recomendo fortemente!"</p>
              <p class="text-muted">- Ruanes Burgo</p>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card">
            <div class="card-body">
              <p class="card-text">"Estou muito satisfeita com os resultados. Me sinto mais confiante em relação ao meu futuro ." </p>
              <p class="text-muted">- Perikão</p>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card">
            <div class="card-body">
              <p class="card-text">"Excelente serviço! A consultoria  me ajudou a eliminar peso e minha depressão." </p>
              <p class="text-muted">- Kevin enpaz</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <section id="contact">
    <div class="container">
      <h2 class="text-center mb-4">Entre em Contato</h2>
      <div class="row justify-content-center">
        <div class="col-md-6">
          <form>
            <div class="form-group">
              <label for="name">Nome</label>
              <input type="text" class="form-control" id="name" required>
            </div>
            <div class="form-group">
              <label for="email">Email</label>
              <input type="email" class="form-control" id="email" required>
            </div>
            <div class="form-group">
              <label for="message">Mensagem</label>
              <textarea class="form-control" id="message" rows="5" required></textarea>
            </div>
            <button type="submit" class="btn btn-primary btn-block">Enviar</button>
          </form>
        </div>
      </div>
    </div>
  </section>

  <footer class="py-4 bg-dark text-white text-center">
    <div class="container">
      <p>&copy; 2024 Consultoria Financeira. Todos os direitos reservados.</p>
    </div>
  </footer>

</body>
</html>



CSS


section {
    padding: 60px 0;
  }
  

  .card-text {
    font-size: 18px;
  }
  

  
