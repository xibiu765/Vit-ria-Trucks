# Vitoria Truks 
Site oficial da Vitória Trucks – peças e desmontagem de caminhões
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Vitória Trucks</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background: #f4f4f4;
      color: #333;
    }
    header {
      background: #002f6c;
      color: white;
      text-align: center;
      padding: 20px 10px;
    }
    header img {
      max-width: 120px;
      display: block;
      margin: 0 auto 10px;
    }
    .container {
      padding: 20px;
      max-width: 900px;
      margin: auto;
      background: white;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }
    h1, h2 {
      color: #002f6c;
    }
    .orcamento {
      margin-top: 30px;
      text-align: center;
    }
    .orcamento a {
      background-color: #25D366;
      color: white;
      padding: 15px 25px;
      border-radius: 8px;
      text-decoration: none;
      font-size: 18px;
      display: inline-block;
    }
    .categorias {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 10px;
      margin-top: 20px;
    }
    .categoria {
      background: #002f6c;
      color: white;
      padding: 10px 20px;
      border-radius: 5px;
    }
    .produtos {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
      margin-top: 30px;
    }
    .produto {
      background: #f9f9f9;
      border: 1px solid #ddd;
      border-radius: 8px;
      padding: 15px;
      text-align: center;
    }
    .produto img {
      max-width: 100%;
      border-radius: 5px;
      margin-bottom: 10px;
    }
    .produto h3 {
      margin: 10px 0;
      color: #002f6c;
    }
    .produto a {
      background-color: #25D366;
      color: white;
      padding: 10px 15px;
      border-radius: 5px;
      text-decoration: none;
      display: inline-block;
    }
    .produto-placeholder {
      background: #ddd;
      height: 180px;
      display: flex;
      align-items: center;
      justify-content: center;
      color: #666;
      border-radius: 5px;
      margin-bottom: 10px;
    }
    footer {
      text-align: center;
      font-size: 14px;
      padding: 20px;
      color: #777;
    }
  </style>
</head>
<body>
  <header>
    <img src="logo.png" alt="Vitória Trucks Logo" />
    <h1>Vitória Trucks</h1>
    <p>CNPJ: 09.255.279/0001-29</p>
  </header>

  <div class="container">
    <h2>Sobre Nós</h2>
    <p>Somos especialistas em peças e desmontagem de caminhões. Atendemos com qualidade, garantia e procedência. Trabalhamos com motores, câmbios, eixos, cabines e muito mais.</p>

    <h2>Peças que Trabalhamos</h2>
    <div class="categorias">
      <div class="categoria">Motores</div>
      <div class="categoria">Câmbios</div>
      <div class="categoria">Eixos</div>
      <div class="categoria">Cabines</div>
      <div class="categoria">Lataria</div>
      <div class="categoria">Suspensão</div>
    </div>

    <h2 style="margin-top: 40px;">Produtos em Destaque</h2>
    <div class="produtos">
      <div class="produto">
        <div class="produto-placeholder">Imagem do Motor MB 364</div>
        <h3>Motor MB 364</h3>
        <a href="https://wa.me/5584988911625" target="_blank">📲 Orçar no WhatsApp</a>
      </div>
      <div class="produto">
        <div class="produto-placeholder">Imagem do Motor MB 457</div>
        <h3>Motor MB 457</h3>
        <a href="https://wa.me/5584988911625" target="_blank">📲 Orçar no WhatsApp</a>
      </div>
      <div class="produto">
        <div class="produto-placeholder">Imagem de Motor Scania</div>
        <h3>Motor Scania</h3>
        <a href="https://wa.me/5584988911625" target="_blank">📲 Orçar no WhatsApp</a>
      </div>
      <div class="produto">
        <div class="produto-placeholder">Imagem de Motor Volvo</div>
        <h3>Motor Volvo</h3>
        <a href="https://wa.me/5584988911625" target="_blank">📲 Orçar no WhatsApp</a>
      </div>
      <div class="produto">
        <div class="produto-placeholder">Imagem de Câmbio Mercedes</div>
        <h3>Câmbio Mercedes</h3>
        <a href="https://wa.me/5584988911625" target="_blank">📲 Orçar no WhatsApp</a>
      </div>
      <div class="produto">
        <div class="produto-placeholder">Imagem de Câmbio Volkswagen</div>
        <h3>Câmbio Volkswagen</h3>
        <a href="https://wa.me/5584988911625" target="_blank">📲 Orçar no WhatsApp</a>
      </div>
      <div class="produto">
        <div class="produto-placeholder">Imagem de Sucata Cabine MB</div>
        <h3>Sucata Cabine MB</h3>
        <a href="https://wa.me/5584988911625" target="_blank">📲 Orçar no WhatsApp</a>
      </div>
    </div>

    <div class="orcamento">
      <h2>Fazer um Orçamento</h2>
      <p>Fale direto com a gente pelo WhatsApp:</p>
      <a href="https://wa.me/5584988911625" target="_blank">📲 Fazer Orçamento no WhatsApp</a>
    </div>
  </div>

  <footer>
    <p>© 2025 Vitória Trucks – Todos os direitos reservados.</p>
  </footer>
</body>
</html>
