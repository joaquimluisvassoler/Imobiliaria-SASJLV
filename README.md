<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Imobiliária Ourimóveis</title>
  <link rel="stylesheet" href="styles.css">
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
    }
    header {
      background-color: #003366;
      color: white;
      padding: 1rem;
      text-align: center;
    }
    nav {
      background-color: #0055a5;
      display: flex;
      justify-content: center;
      gap: 1rem;
      padding: 1rem;
    }
    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }
    .hero {
      background: url('banner-imoveis.jpg') center/cover no-repeat;
      color: white;
      text-align: center;
      padding: 6rem 1rem;
    }
    .hero h1 {
      font-size: 2.5rem;
      margin-bottom: 1rem;
    }
    .section {
      padding: 3rem 1rem;
      max-width: 1000px;
      margin: auto;
    }
    .section h2 {
      color: #003366;
      margin-bottom: 1rem;
    }
    .cards {
      display: flex;
      flex-wrap: wrap;
      gap: 1rem;
    }
    .card {
      flex: 1 1 calc(33% - 1rem);
      background-color: #f1f1f1;
      padding: 1rem;
      border-radius: 8px;
    }
    footer {
      background-color: #003366;
      color: white;
      text-align: center;
      padding: 2rem 1rem;
      margin-top: 2rem;
    }
    .form-group {
      margin-bottom: 1rem;
    }
    input, textarea {
      width: 100%;
      padding: 0.5rem;
      border: 1px solid #ccc;
      border-radius: 4px;
    }
    .map-container {
      margin-top: 1rem;
    }
  </style>
</head>
<body>
  <header>
    <h1>Imobiliária Ourimóveis</h1>
    <p>Segurança jurídica para cada negociação</p>
  </header>

  <nav>
    <a href="#comprar">Comprar</a>
    <a href="#alugar">Alugar</a>
    <a href="#diferenciais">Diferenciais</a>
    <a href="#sobre">Sobre Nós</a>
    <a href="#contato">Contato</a>
  </nav>

  <section class="hero">
    <h1>Seu imóvel com proteção jurídica do início ao fim</h1>
    <p>Veja nossos imóveis à venda ou para locação</p>
    <a href="https://wa.me/5514999999999" target="_blank" style="display: inline-block; background-color: #25d366; color: white; padding: 1rem 2rem; text-decoration: none; border-radius: 4px; margin-top: 1rem;">Fale conosco no WhatsApp</a>
  </section>

  <section id="diferenciais" class="section">
    <h2>Diferenciais</h2>
    <div class="cards">
      <div class="card">
        <h3>Assessoria Jurídica Completa</h3>
        <p>Todos os contratos são elaborados com acompanhamento do nosso escritório parceiro.</p>
      </div>
      <div class="card">
        <h3>Gestão Digital de Locação</h3>
        <p>Portal exclusivo para inquilinos e proprietários com boletos, extratos e comunicação.</p>
      </div>
      <div class="card">
        <h3>Contrato Digital</h3>
        <p>Assine online com total validade jurídica e agilidade.</p>
      </div>
    </div>
  </section>

  <section id="sobre" class="section">
    <h2>Sobre Nós</h2>
    <p>Somos uma imobiliária que alia segurança jurídica, atendimento humanizado e tecnologia de ponta. Nossa atuação é resultado da parceria entre profissionais altamente qualificados do mercado imobiliário e o escritório S.A.S. Advogados, tradicional e consolidado em Ourinhos. Essa união estratégica garante aos nossos clientes um serviço completo, unindo expertise comercial e respaldo jurídico especializado, assegurando tranquilidade, confiança e excelência em todas as etapas das negociações imobiliárias.</p>
  </section>

  <section id="contato" class="section">
    <h2>Fale Conosco</h2>
    <form>
      <div class="form-group">
        <input type="text" placeholder="Nome" required>
      </div>
      <div class="form-group">
        <input type="email" placeholder="E-mail" required>
      </div>
      <div class="form-group">
        <input type="text" placeholder="Telefone ou WhatsApp" required>
      </div>
      <div class="form-group">
        <textarea placeholder="Mensagem" rows="5" required></textarea>
      </div>
      <button type="submit" style="background-color: #003366; color: white; padding: 0.75rem 2rem; border: none; border-radius: 4px;">Enviar</button>
    </form>

    <div class="map-container">
      <iframe src="https://www.google.com/maps?q=Ourinhos,+SP&output=embed" width="100%" height="300" style="border:0; margin-top: 2rem;" allowfullscreen="" loading="lazy"></iframe>
    </div>
  </section>

  <footer>
    <p>&copy; 2025 Imobiliária Ourimóveis - Todos os direitos reservados</p>
  </footer>
</body>
</html>
