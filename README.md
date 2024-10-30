
<html><head><base href="https://wilmerdelgadocieza.blogspot.com/">
<style>
:root {
  --primary: #ffa413;
  --secondary: #033f88;
  --light: #f1f2f3;
  --dark: #333;
}

body {
  margin: 0;
  font-family: 'Roboto', sans-serif;
  background: var(--light);
}

.header {
  background: white;
  padding: 1rem;
  text-align: center;
  box-shadow: 0 2px 4px rgba(0,0,0,0.1);
}

.logo {
  max-width: 300px;
  height: auto;
}

.player {
  background: white;
  padding: 1rem;
  margin: 1rem auto;
  max-width: 800px;
  border-radius: 8px;
  box-shadow: 0 2px 4px rgba(0,0,0,0.1);
}

.contact-bar {
  background: var(--secondary);
  color: white;
  padding: 0.5rem;
  text-align: center;
}

.social-links {
  display: flex;
  justify-content: center;
  gap: 1rem;
  padding: 1rem;
}

.social-btn {
  background: var(--primary);
  color: white;
  padding: 0.5rem 1rem;
  border-radius: 4px;
  text-decoration: none;
  transition: opacity 0.2s;
}

.social-btn:hover {
  opacity: 0.9;
}

.content {
  max-width: 1200px;
  margin: 0 auto;
  padding: 2rem;
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 2rem;
}

@media (max-width: 768px) {
  .content {
    grid-template-columns: 1fr;
  }
}

footer {
  background: var(--secondary);
  color: white;
  padding: 2rem;
  text-align: center;
}
</style>
</head>
<body>

<header class="header">
  <img src=" https://i.ibb.co/mhw9LGh/DJ-WILMER-PNG-ORIGINAL.png
" alt="DJ WILMER logo" class="logo" width="300" height="202">
</header>

<div class="player">
  <iframe src=" https://stream.zeno.fm/wttrxavefwzuv" 
    style="width:100%;height:84px;border:none;"></iframe>
</div>

<div class="contact-bar">
  PUBLICIDAD: +984335569 DJ WILMER Programacion Variado
</div>

<div class="social-links">
  <a href="https://web.facebook.com/DelgadoCiezaWilmer" class="social-btn" target="_blank">
    <i class="fab fa-facebook"></i> Facebook
  </a>
  <a href="/tv-en-vivo" class="social-btn">
    <i class="fas fa-tv"></i> TV EN VIVO
  </a>
  <a href="#" class="social-btn">
    <i class="fas fa-download"></i> Descargar App
  </a>
</div>

<div class="content">
  <div class="facebook-feed">
    <div class="fb-page" 
      data-href="https://web.facebook.com/DelgadoCiezaWilmer/"
      data-tabs="timeline"
      data-width="500"
      data-height="800"
      data-small-header="false"
      data-adapt-container-width="true"
      data-hide-cover="false"
      data-show-facepile="true">
    </div>
  </div>
  
  <div class="comments-section">
    <div class="fb-comments" 
      data-href=" https://wilmerdelgadocieza.blogspot.com/"
      data-width="100%"
      data-numposts="20"
      data-order-by="reverse_time">
    </div>
  </div>
</div>

<footer>
  <p>Sitio Web oficial. https://wilmerdelgadocieza.blogspot.com</p>
  <p>Dj Wilmer © 2015/2024</p>
  <p>Telf: 984335569</p>
  <p>WhatsApp: +51 984335569</p>
  <p>Dirección: Camporredondo Luya,Amazonas, Perú</p>
</footer>

<script async defer crossorigin="anonymous" 
  src="https://connect.facebook.net/es_LA/sdk.js#xfbml=1&version=v11.0&appId= 104330711265702">
</script>

<script src="https://kit.fontawesome.com/a076d05399.js"></script>

</body></html>
