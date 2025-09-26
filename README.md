<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Equilíbrio Soluções</title>
  <style>
    /* Reset simples */
    * { margin: 0; padding: 0; box-sizing: border-box; }

    body {
      font-family: Arial, sans-serif;
      color: #333;
      line-height: 1.6;
    }

    header {
      background: #fff;
      padding: 15px 40px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      border-bottom: 1px solid #ddd;
      position: sticky;
      top: 0;
      z-index: 1000;
    }

    header img {
      height: 50px;
    }

    nav ul {
      list-style: none;
      display: flex;
      gap: 20px;
    }

    nav ul li a {
      text-decoration: none;
      color: #333;
      font-weight: bold;
    }

    .btn-cta {
      background: #2E7D32;
      color: #fff;
      padding: 10px 20px;
      border-radius: 6px;
      text-decoration: none;
      transition: 0.3s;
    }
    .btn-cta:hover { background: #1b5e20; }

    /* Banner */
    .hero {
      background: url('https://images.unsplash.com/photo-1568605114967-8130f3a36994') no-repeat center center/cover;
      color: #fff;
      text-align: center;
      padding: 120px 20px;
    }
    .hero h1 { font-size: 2.5rem; margin-bottom: 20px; }
    .hero p { font-size: 1.2rem; margin-bottom: 30px; }
    .hero a {
      margin: 0 10px;
    }

    /* Seções */
    section {
      padding: 60px 20px;
      max-width: 1100px;
      margin: auto;
    }

    .cards {
      display: flex;
      gap: 20px;
      flex-wrap: wrap;
      justify-content: center;
    }
    .card {
      flex: 1;
      min-width: 250px;
      background: #f9f9f9;
      padding: 20px;
      border-radius: 10px;
      text-align: center;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
    }
    .card h3 { margin-bottom: 10px; }

    /* Portfólio */
    .portfolio-logos {
      display: flex;
      gap: 30px;
      flex-wrap: wrap;
      justify-content: center;
      align-items: center;
    }
    .portfolio-logos img {
      height: 40px;
      opacity: 0.7;
    }

    /* Contato */
    form {
      display: flex;
      flex-direction: column;
      gap: 15px;
      max-width: 500px;
      margin: auto;
    }
    form input, form textarea {
      padding: 10px;
      border: 1px solid #ccc;
      border-radius: 6px;
    }
    form button {
      background: #2E7D32;
      color: #fff;
      border: none;
      padding: 12px;
      border-radius: 6px;
      cursor: pointer;
    }
    form button:hover { background: #1b5e20; }

    footer {
      background: #2E7D32;
      color: #fff;
      text-align: center;
      padding: 20px;
    }
  </style>
</head>
<body>

  <!-- Cabeçalho -->
  <header>
    <img src="logo.png" alt="Equilíbrio Soluções">
    <nav>
      <ul>
        <li><a href="#sobre">Sobre</a></li>
        <li><a href="#servicos">Serviços</a></li>
        <li><a href="#portfolio">Clientes</a></li>
        <li><a href="#blog">Blog</a></li>
        <li><a href="#contato">Contato</a></li>
      </ul>
    </nav>
    <a href="#contato" class="btn-cta">Solicite um Orçamento</a>
  </header>

  <!-- Banner -->
  <section class="hero">
    <h1>Soluções em Segurança do Trabalho e Meio Ambiente</h1>
    <p>Gestão inteligente, sustentável e em conformidade com a legislação.</p>
    <a href="#servicos" class="btn-cta">Nossos Serviços</a>
    <a href="#contato" class="btn-cta" style="background:#fff;color:#2E7D32;">Fale Conosco</a>
  </section>

  <!-- Sobre nós -->
  <section id="sobre">
    <h2>Sobre Nós</h2>
    <p>A <b>Equilíbrio Soluções</b> é especializada em consultoria de Engenharia de Segurança do Trabalho, Meio Ambiente e eSocial. Atuamos com foco na prevenção, sustentabilidade e resultados para empresas de todos os portes.</p>
    <div class="cards">
      <div class="card">
        <h3>Missão</h3>
        <p>Segurança do Trabalho, PGR, LTCAT, Auditorias e Treinamentos.</p>
      </div>
      <div class="card">
        <h3>Visão</h3>
        <p>Sustentabilidade, Gestão de Resíduos, Licenciamento e Monitoramento.</p>
      </div>
      <div class="card">
        <h3>Valores</h3>
        <p>Ética, Transparência, Inovação e Compromisso com Resultados.</p>
      </div>
    </div>
  </section>

  <!-- Serviços -->
  <section id="servicos">
    <h2>Serviços</h2>
    <div class="cards">
      <div class="card"><h3>Segurança do Trabalho</h3><p>PGR, LTCAT, PCMSO, NR Treinamentos</p></div>
      <div class="card"><h3>Meio Ambiente</h3><p>PGRS, Licenciamento, Monitoramentos</p></div>
      <div class="card"><h3>eSocial</h3><p>Implantação, Acompanhamento e Suporte</p></div>
    </div>
  </section>

  <!-- Portfólio -->
  <section id="portfolio">
    <h2>Clientes</h2>
    <div class="portfolio-logos">
      <img src="https://dummyimage.com/100x40/ccc/000.png&text=SIM" alt="Cliente 1">
      <img src="https://dummyimage.com/100x40/ccc/000.png&text=Brasil" alt="Cliente 2">
      <img src="https://dummyimage.com/100x40/ccc/000.png&text=ABC" alt="Cliente 3">
    </div>
  </section>

  <!-- Blog -->
  <section id="blog">
    <h2>Blog</h2>
    <div class="cards">
      <div class="card"><h3>NR OS</h3><p>Equipamentos de Proteção Individual</p></div>
      <div class="card"><h3>Legislação Ambiental</h3><p>Novas regras em avaliação</p></div>
      <div class="card"><h3>Práticas Sustentáveis</h3><p>Dicas para sua empresa</p></div>
    </div>
  </section>

  <!-- Contato -->
  <section id="contato">
    <h2>Fale Conosco</h2>
    <form>
      <input type="text" placeholder="Seu Nome" required>
      <input type="email" placeholder="Seu Email" required>
      <textarea rows="5" placeholder="Sua Mensagem"></textarea>
      <button type="submit">Enviar</button>
    </form>
  </section>

  <!-- Rodapé -->
  <footer>
    <p>© 2025 Equilíbrio Soluções - Todos os direitos reservados.</p>
  </footer>

</body>
</html>
