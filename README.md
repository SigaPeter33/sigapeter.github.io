<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>SigaPeter | Portfólio</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: "Poppins", sans-serif;
    }

    body {
      background-color: #0a1a2f;
      color: #fff;
      line-height: 1.6;
    }

    header {
      text-align: center;
      padding: 60px 20px;
      background: linear-gradient(180deg, #0d2240, #0a1a2f);
    }

    header h1 {
      font-size: 2.5rem;
      color: #ffffff;
    }

    header p {
      font-size: 1.2rem;
      color: #b0c4de;
      margin-top: 10px;
    }

    .btn {
      display: inline-block;
      margin-top: 25px;
      padding: 10px 25px;
      background-color: #1e3a8a;
      color: white;
      text-decoration: none;
      border-radius: 10px;
      transition: 0.3s;
    }

    .btn:hover {
      background-color: #3b82f6;
    }

    section {
      padding: 60px 20px;
      max-width: 1000px;
      margin: auto;
    }

    h2 {
      text-align: center;
      margin-bottom: 30px;
      color: #9dc1ff;
    }

    .projects {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 20px;
    }

    .project-card {
      background-color: #102542;
      border-radius: 12px;
      overflow: hidden;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.3);
      transition: 0.3s;
    }

    .project-card:hover {
      transform: translateY(-5px);
    }

    .project-card img {
      width: 100%;
      height: 180px;
      object-fit: cover;
    }

    .project-card .content {
      padding: 15px;
    }

    .project-card h3 {
      color: #fff;
      margin-bottom: 10px;
    }

    .project-card p {
      color: #b0c4de;
      font-size: 0.9rem;
    }

    footer {
      text-align: center;
      padding: 30px 10px;
      background-color: #08101f;
      color: #9dc1ff;
      font-size: 0.9rem;
    }
  </style>
</head>
<body>

  <header>
    <h1>SigaPeter</h1>
    <p>Editor de Vídeo e Programador</p>
    <a href="#" class="btn">Canal SigaPeter</a>
  </header>

  <section>
    <h2>Projetos Recentes</h2>
    <div class="projects">
      <div class="project-card">
        <img src="https://via.placeholder.com/400x200.png?text=Thumb+do+Vídeo+1" alt="Projeto 1">
        <div class="content">
          <h3>Remo x Athletico - Pré-Jogo</h3>
          <p>Thumb e vinheta criadas no After Effects e Photoshop para live do canal.</p>
        </div>
      </div>

      <div class="project-card">
        <img src="https://via.placeholder.com/400x200.png?text=Thumb+do+Vídeo+2" alt="Projeto 2">
        <div class="content">
          <h3>Introdução Cinemática</h3>
          <p>Animação de abertura criada no Premiere com transições e trilha sonora original.</p>
        </div>
      </div>
    </div>
  </section>

  <footer>
    © 2025 SigaPeter — Todos os direitos reservados.
  </footer>

</body>
</html>
