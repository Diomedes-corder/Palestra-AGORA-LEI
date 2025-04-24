<!DOCTYPE html>
<html lang="pt-br">
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Palestra Regina Queiroz</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background-color: #f4f4f4;
    }
    .container {
      max-width: 800px;
      margin: auto;
      background: #fff;
      padding: 20px;
    }
    h1, h2 {
      color: #222;
    }
    .section {
      margin-bottom: 30px;
    }
    input, select {
      padding: 10px;
      margin: 8px 0;
      width: 100%;
      box-sizing: border-box;
    }
    button {
      padding: 12px 20px;
      background: #28a745;
      color: #fff;
      border: none;
      cursor: pointer;
    }
    button:hover {
      background: #218838;
    }
    .alert {
      background: #e0f7fa;
      padding: 10px;
      border-left: 4px solid #00acc1;
    }
    .form-container {
      background: white;
      padding: 30px 40px;
      border-radius: 12px;
      box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
      width: 100%;
      max-width: 700px;
    }
    .form-container h2 {
      text-align: center;
      color: #333;
      margin-bottom: 20px;
    }
    .form-container input {
      width: 100%;
      padding: 12px;
      margin: 10px 0;
      border: 1px solid #ccc;
      border-radius: 8px;
      font-size: 16px;
    }
  </style>
</head>
<body>
</div>
  <div class="container">
    <h1>
      <div style="text-align: center; margin-top: 20px; margin-bottom: 10px;">
      <img src="logo-outliers.png" alt="Logo Outliers" style="width: 400px; height: auto;">
      </h1>
      <h1>PALESTRA - AGORA É LEI</h1>
    </div>
    <div class="container">
    </body>
    <h2>GESTÃO DE PESSOAS EM FATORES PSICOSSOCIAIS NAS ORGANIZAÇÕES</h2>
    <div class="section">
      <p><strong>📅 Data:</strong> 13/05/2025 às 18:47</p>
      <p><strong>Local:</strong>Rua 17, esquina com a rua 01, Setor Vila Gomes, perto da Zezinho Autopeças e Mecanica Porangatu - GO</p>
      <p><strong>📄 Sobre o evento</strong></p>
      <p>Toda empresa será obrigada por lei, criar e executar Políticas Psicossociais em relação a NR01 - Atualizada dentro da PGR, ou seja, ter uma Política Psicossocial de gestão de Pessoas como condutora na organização em relação a fatores como:</p>
      <p>•Estresse;</p>
      <p>•Ritmo do trabalho;</p>
      <p>•Comunicação;</p>
      <p>•Má gestão de Mudanças;</p>
      <p>•Falta de clareza organizacional, dentre outros fatores.</p> 
      <p>O objetivo da Palestra além da clareza na condução da gestão de pessoas é principalmente um norteamento para gerir a GERAÇÃO Z e a MILLENIUNS que estão impactando o mercado e a produtividade das organizações.</p>  
    </div>

    <div class="section">
      <div class="form-container">
        <h2>Inscrição</h2>
        <form id="formulario">
          <input type="text" id="nome" placeholder="Seu nome" required>
          <input type="email" id="email" placeholder="Seu e-mail" required>
          <input type="text" id="whatsapp" placeholder="Seu número WhatsApp" required>
          <input type="text" id="empresa" placeholder="Nome da Empresa" required>
          <input type="text" id="ramo" placeholder="Ramo de Atividade" required>

          <button type="submit" style="background-color: #25D366; color: white; font-weight: bold;">
            Enviar via WhatsApp
          </button>
        </form>
      </div>
    </div>

    <div class="section">
      <h2>Resumo de Pagamento</h2>
      <div class="alert">
        <section style="max-width: 600px; margin: 20px auto; font-family: Arial, sans-serif;">
          <h2>Pagamento da Inscrição</h2>
          <p><strong>Valor:</strong> R$100,00</p>
          <p><strong>Chave PIX:</strong> 54906707000190</p>
          <p><strong>Banco:</strong> C6 Bank (336)</p>

          <p>Use seu aplicativo bancário para fazer o pagamento via PIX utilizando a chave acima.</p>

          <p>Depois de realizar o pagamento, envie o comprovante pelo WhatsApp:</p>
          <a href="https://wa.me/+5562999020381?text=Olá%20novamente,%20segue%20o%20comprovante%20do%20PIX%20da%20inscrição%20da%20PALESTRA%20-%20AGORA%20É%20LEI."
            target="_blank" 
            style="text-decoration: none;">
            <button style="background-color: #25D366; color: white; padding: 10px 20px; border: none; border-radius: 5px; font-size: 16px;">
              Enviar o Comprovante via WhatsApp
            </button>
          </a>
        </section>
      </div>
    </div>
  </div>

  <script>
    document.getElementById("formulario").addEventListener("submit", function(e){
      e.preventDefault();

      const nome = document.getElementById("nome").value;
      const email = document.getElementById("email").value;
      const whatsapp = document.getElementById("whatsapp").value;
      const empresa = document.getElementById("empresa").value;
      const ramo = document.getElementById("ramo").value;

      const mensagem = `Olá! Gostaria de me inscrever na palestra com os seguintes dados:\n*Nome:* ${nome}\n*E-mail:* ${email}\n*WhatsApp:* ${whatsapp}\n*Empresa:* ${empresa}\n*Ramo:* ${ramo}`;

      const numero = "5562999020381";
      const link = `https://wa.me/${numero}?text=${encodeURIComponent(mensagem)}`;
      window.open(link, "_blank");
    });
  </script>
</body>
</html>
