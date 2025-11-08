<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8"/>
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Profil - Nouveau Modèle</title>
  <style>
    :root{
      --bg:#0f141b;
      --fg:#e9eef5;
      --accent:#ff6b46;
    }
    *{box-sizing:border-box}
    body{
      margin:0;
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Arial, sans-serif;
      background:#0b111a;
      color:#e6e6e6;
    }
    header{
      text-align:center;
      padding:28px 16px 12px;
      border-bottom:1px solid rgba(255,255,255,.08);
      background:#111821;
    }
    .wave{
      font-weight:700;
      font-size:28px;
      letter-spacing:2px;
      color:#fff;
      text-shadow:0 0 8px rgba(0,150,255,.6);
    }
    .badge{display:inline-block;margin-top:8px;color:#cbd5e1}
    h1{font-size:40px;margin:6px 0 0}
    .subtitle{font-size:20px;margin-top:6px;color:#cbd5e1}
    .hero{
      padding:40px 20px 60px;
      display:flex;
      flex-direction:column;
      align-items:center;
      gap:18px;
    }
    .card{
      width:320px;height:320px;
      border-radius:20px;
      background:url('https://images.unsplash.com/photo-1519389950473-47ba0277781c?w=800&q=60') center/cover no-repeat;
      box-shadow:0 20px 40px rgba(0,0,0,.5);
      display:flex;align-items:flex-end;justify-content:center;
      position:relative;
    }
    .overlay{
      width:100%;height:100%;
      border-radius:20px;
      background:linear-gradient(to top, rgba(0,0,0,.8), rgba(0,0,0,.3) 60%, transparent);
      display:flex;align-items:flex-end;justify-content:center;padding:16px;
      color:white;
    }
    .overlay h2{margin:0;font-size:22px;text-shadow:0 2px 6px rgba(0,0,0,.7)}
    .footer-space{height:40px}
    .code{font-family: ui-monospace,SFMono-Regular,Monaco,Consolas,"Liberation Mono";font-size:12px; color:#88d3ff}
  </style>
</head>
<body>
  <header>
    <div class="wave" aria-label="Welcome">
      👋 Salut, je suis
    </div>
    <h1>Nouvelle Démo de Profil</h1>
    <div class="badge">🚀 Un candidat passionné de développement Web</div>
  </header>

  <section class="hero">
    <div class="card" aria-label="image de présentation">
      <div class="overlay">
        <h2>Super Développeur Web — Nouveau Modèle</h2>
      </div>
    </div>

    <div class="subtitle">📌 Début de code inspiré par le modèle ci-dessus</div>

    <!-- Exemple de contenu textuel pour la section “À propos” -->
    <p class="code" style="text-align:center; max-width:720px;">
      <strong>&lt;header&gt;</strong> // Entête similaire
      <br/>
      <strong>&lt;h1&gt;</strong> Nouveau Titre — Ton Nom
      <br/>
      <strong>&lt;p&gt;</strong> Slogan ou court descriptif
      <br/>
      <strong>&lt;/header&gt;</strong>
    </p>
  </section>

  <section style="text-align:center;margin:20px 0;">
    <a href="#" style="color:#8ab4f8;text-decoration:none;font-weight:600;">LinkedIn</a> •
    <a href="#" style="color:#8ab4f8;text-decoration:none;margin-left:6px;font-weight:600;">Email</a>
  </section>

  <footer class="footer-space" aria-label="fin de page"></footer>
</body>
</html>
