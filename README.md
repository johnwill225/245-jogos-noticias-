# 245-jogos-noticias-<!DOCTYPE html><html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Portal Gamer</title>
  <style>
    :root {
      --primary-color: #00bcd4;
      --background-color: #0f0f0f;
      --card-background: #1e1e1e;
      --text-color: #e0e0e0;
      --shadow-color: rgba(0, 188, 212, 0.3);
    }* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  background: var(--background-color);
  color: var(--text-color);
  line-height: 1.6;
}

header {
  background: #1f1f1f;
  padding: 2.5rem 1rem;
  text-align: center;
  box-shadow: 0 2px 5px #000;
}

header h1 {
  color: var(--primary-color);
  font-size: 3rem;
  margin-bottom: 0.5rem;
}

nav {
  margin-top: 1rem;
}

nav a {
  color: var(--primary-color);
  margin: 0 1.5rem;
  text-decoration: none;
  font-weight: 600;
  font-size: 1.1rem;
  transition: color 0.3s ease;
}

nav a:hover {
  color: #ffffff;
}

main {
  padding: 4rem 8%;
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
  gap: 2.5rem;
}

article {
  background: var(--card-background);
  padding: 2rem;
  border-radius: 16px;
  box-shadow: 0 0 25px var(--shadow-color);
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

article:hover {
  transform: translateY(-5px);
  box-shadow: 0 0 35px var(--shadow-color);
}

h2 {
  color: var(--primary-color);
  margin-bottom: 1.2rem;
  font-size: 1.8rem;
}

img {
  width: 100%;
  height: auto;
  border-radius: 12px;
  margin-bottom: 1rem;
}

p {
  font-size: 1rem;
  color: #ccc;
}

footer {
  background: #1f1f1f;
  text-align: center;
  padding: 2rem;
  margin-top: 3rem;
  color: #aaa;
  font-size: 1rem;
  border-top: 2px solid #333;
}

  </style>
</head>
<body>  <header>
    <h1>Portal Gamer</h1>
    <nav>
      <a href="#atuais">Jogos Atuais</a>
      <a href="#2d3d">2D & 3D</a>
      <a href="#lancamentos">Lançamentos</a>
    </nav>
  </header>  <main>
    <article id="atuais">
      <h2>Jogos da Atualidade</h2>
      <img src="https://upload.wikimedia.org/wikipedia/en/f/f5/Elden_Ring_Box_art.jpg" alt="Elden Ring 2">
      <p>Os jogos mais populares de 2025 estão redefinindo a forma como nos conectamos e jogamos. <strong>Elden Ring 2</strong> continua a saga sombria com um mundo ainda mais imersivo. <strong>Fortnite</strong> se reinventa a cada temporada, agora com eventos interativos em tempo real. <strong>Call of Duty: Modern Warfare 4</strong> retorna às origens com gráficos de ponta e jogabilidade refinada, agradando tanto veteranos quanto novatos.</p>
      <img src="https://cdn2.unrealengine.com/fortnite-og-overview-01-1920x1080-8c2228369c45.jpg" alt="Fortnite">
      <img src="https://upload.wikimedia.org/wikipedia/en/2/20/Call_of_Duty_Modern_Warfare_II_Key_Art.jpg" alt="Call of Duty Modern Warfare">
    </article><article id="2d3d">
  <h2>Jogos 2D e 3D</h2>
  <img src="https://upload.wikimedia.org/wikipedia/en/9/9f/Celeste_box_art_final.png" alt="Celeste">
  <p>Os jogos 2D ainda brilham em 2025 com obras-primas como <strong>Celeste</strong>, que combina narrativa emocional com desafios de plataforma precisos. Por outro lado, os jogos 3D como <strong>Super Mario Odyssey</strong> e <strong>Sonic Frontiers</strong> expandem os limites da exploração em mundos tridimensionais vibrantes. A escolha entre 2D e 3D agora é uma questão de estilo e experiência, pois ambos entregam qualidade e inovação.</p>
  <img src="https://upload.wikimedia.org/wikipedia/en/8/8d/Super_Mario_Odyssey.jpg" alt="Super Mario Odyssey">
  <img src="https://upload.wikimedia.org/wikipedia/en/8/88/Sonic_Frontiers_cover.jpg" alt="Sonic Frontiers">
</article>

<article id="lancamentos">
  <h2>Últimos Lançamentos</h2>
  <img src="https://upload.wikimedia.org/wikipedia/en/e/e5/Grand_Theft_Auto_VI_cover_art.jpg" alt="GTA VI">
  <p>Os lançamentos recentes estão dando o que falar. <strong>GTA VI</strong> finalmente chegou com um mapa dinâmico e narrativa cinematográfica. <strong>Hollow Knight: Silksong</strong> leva os metroidvanias a um novo patamar com arte detalhada e combate fluido. <strong>Metroid Prime 5</strong> entrega uma experiência de ficção científica envolvente com ambientações atmosféricas e gameplay estratégico.</p>
  <img src="https://upload.wikimedia.org/wikipedia/en/5/55/Hollow_Knight_Silksong_cover_art.png" alt="Hollow Knight: Silksong">
  <img src="https://upload.wikimedia.org/wikipedia/en/c/c6/Metroid_Prime_3_Corruption_PAL.jpg" alt="Metroid Prime">
</article>

  </main>  <footer>
    <p>Criado por João, Pedro e Olavo</p>
  </footer></body>
</html>
