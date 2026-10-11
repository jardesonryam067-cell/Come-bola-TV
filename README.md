
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>COME BOLA TV | Futebol é aqui</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

<header>
  <div class="logo">
    <img src="logo-comebola.png" alt="Logo Come Bola TV">
    <h2>COME BOLA <span>TV</span></h2>
  </div>

  <nav>
    <a href="#inicio">Início</a>
    <a href="#videos">Vídeos</a>
    <a href="#sobre">Sobre</a>
    <a href="#cobertura">Solicitar cobertura</a>
  </nav>
</header>

<section class="hero" id="inicio">
  <p class="destaque">⚽ FUTEBOL LOCAL • PIAUÍ</p>
  <h1>A RESENHA DO FUTEBOL <span>É AQUI!</span></h1>
  <p>
    Transmissões, entrevistas, melhores momentos
    e toda a emoção do futebol regional.
  </p>

  <a class="botao" href="#cobertura">
    SOLICITAR COBERTURA
  </a>

  <a class="botao secundario"
     href="https://www.youtube.com/results?search_query=COME+BOLA+TV"
     target="_blank">
    ▶ ASSISTIR NO YOUTUBE
  </a>
</section>

<section class="secao" id="videos">
  <h2>📺 VÍDEOS E TRANSMISSÕES</h2>
  <p>Acompanhe os jogos e conteúdos da Come Bola TV.</p>

  <div class="videos">
    <div class="card">
      <h3>⚽ Jogos ao vivo</h3>
      <p>Transmissões dos campeonatos regionais.</p>
      <a href="https://www.youtube.com/results?search_query=COME+BOLA+TV"
         target="_blank">Assistir vídeos</a>
    </div>

    <div class="card">
      <h3>🎙️ Entrevistas</h3>
      <p>Jogadores, treinadores e bastidores.</p>
    </div>

    <div class="card">
      <h3>🏆 Melhores momentos</h3>
      <p>Os grandes lances e a resenha do futebol.</p>
    </div>
  </div>
</section>

<section class="secao sobre" id="sobre">
  <h2>SOBRE A COME BOLA TV</h2>
  <p>
    Somos um projeto de mídia esportiva dedicado às transmissões,
    entrevistas e cobertura do futebol local em Picos e região do Piauí.
  </p>

  <a href="https://www.instagram.com/comebolatv/"
     target="_blank" class="botao">
    SEGUIR NO INSTAGRAM
  </a>
</section>

<section class="secao cobertura" id="cobertura">
  <h2>📋 SOLICITE A COBERTURA DO SEU JOGO</h2>
  <p>Preencha as informações da partida.</p>

  <form id="formulario">

    <label>Nome do responsável</label>
    <input name="responsavel" required>

    <label>Telefone para contato</label>
    <input name="telefone" type="tel" required>

    <label>Campeonato</label>
    <select name="campeonato" required>
      <option value="">Escolha o campeonato</option>
      <option>Campeonato municipal</option>
      <option>Campeonato regional</option>
      <option>Campeonato rural</option>
      <option>Torneio ou amistoso</option>
      <option>Outro</option>
    </select>

    <label>Nome do campeonato, se for outro</label>
    <input name="outroCampeonato">

    <label>Data da partida</label>
    <input name="data" type="date" required>

    <label>Horário da partida</label>
    <input name="horario" type="time" required>

    <label>Local do jogo e cidade</label>
    <input name="local" required>

    <label>Time 1</label>
    <input name="time1" required>

    <label>Time 2</label>
    <input name="time2" required>

    <label>Informações adicionais</label>
    <textarea name="detalhes" rows="4"></textarea>

    <button type="submit" class="botao">
      ENVIAR SOLICITAÇÃO
    </button>

    <p id="mensagem"></p>
  </form>
</section>

<footer>
  <h2>COME BOLA <span>TV</span> ⚽</h2>
  <p>A resenha do futebol é aqui!</p>

  <a href="https://www.instagram.com/comebolatv/"
     target="_blank">Instagram</a>

  <a href="https://www.youtube.com/results?search_query=COME+BOLA+TV"
     target="_blank">YouTube</a>

  <a href="https://wa.me/558981250748"
     target="_blank">WhatsApp: (89) 8125-0748</a>

  <p>© 2026 Come Bola TV</p>
</footer>

<script src="script.js"></script>
</body>
</html>
