<!doctype html>
<html lang="fr">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Café Ginette — Brasserie de quartier à Toulouse</title>
  <meta name="description" content="Café Ginette — brasserie de quartier à Toulouse : cuisine accessible & responsable, soirées, dj sets, quizz. Menu, réservation, contact." />
  <meta property="og:title" content="Café Ginette — Toulouse" />
  <meta property="og:description" content="Brasserie de quartier : accessible & responsable. Menu, réservation, contact." />
  <meta property="og:type" content="website" />
  <meta name="theme-color" content="#B1412E" />

  <style>
    :root{
      --bg:#0b0b0c;
      --card:#121214;
      --muted:#a6a6ad;
      --text:#f4f4f6;
      --brand:#B1412E;         /* rouge Ginette */
      --brand2:#E0B078;        /* doré doux */
      --ring: rgba(177,65,46,.35);
      --radius: 18px;
      --shadow: 0 20px 60px rgba(0,0,0,.45);
      --shadow2: 0 10px 30px rgba(0,0,0,.35);
      --max: 1120px;
    }
    *{box-sizing:border-box}
    html,body{margin:0;padding:0;background:radial-gradient(1200px 600px at 20% 0%, rgba(177,65,46,.25), transparent 60%),
                               radial-gradient(900px 600px at 90% 10%, rgba(224,176,120,.18), transparent 55%),
                               var(--bg);
              color:var(--text);
              font-family: ui-sans-serif, system-ui, -apple-system, Segoe UI, Roboto, Arial, "Apple Color Emoji","Segoe UI Emoji";
              line-height:1.45;}
    a{color:inherit}
    .wrap{max-width:var(--max); margin:0 auto; padding: 18px 16px 48px;}
    .nav{
      display:flex; align-items:center; justify-content:space-between; gap:12px;
      padding: 14px 14px; border-radius: 20px;
      background: rgba(255,255,255,.04);
      border: 1px solid rgba(255,255,255,.08);
      box-shadow: var(--shadow2);
      position: sticky; top: 12px; z-index: 20;
      backdrop-filter: blur(10px);
    }
    .brand{display:flex; align-items:center; gap:10px; min-width: 210px;}
    .brand img{height:34px; width:auto; display:block; filter: drop-shadow(0 8px 18px rgba(0,0,0,.35));}
    .brand strong{font-size: 14px; letter-spacing:.4px; opacity:.95}
    .navlinks{display:flex; gap:14px; align-items:center; flex-wrap:wrap; justify-content:flex-end}
    .navlinks a{opacity:.9; text-decoration:none; font-weight:600; font-size: 13px; padding:10px 10px; border-radius: 12px;}
    .navlinks a:hover{background: rgba(255,255,255,.06)}
    .btn{
      display:inline-flex; align-items:center; justify-content:center; gap:10px;
      padding: 12px 14px; border-radius: 14px; text-decoration:none; font-weight:800;
      border: 1px solid rgba(255,255,255,.12);
      box-shadow: 0 10px 30px rgba(0,0,0,.25);
    }
    .btn.primary{background: linear-gradient(135deg, var(--brand), #8f2f22); border-color: rgba(255,255,255,.10)}
    .btn.ghost{background: rgba(255,255,255,.04)}
    .btn:hover{transform: translateY(-1px)}
    .hero{
      margin-top: 18px;
      display:grid; gap:16px;
      grid-template-columns: 1.1fr .9fr;
      align-items:stretch;
    }
    @media (max-width: 980px){
      .hero{grid-template-columns: 1fr}
      .brand{min-width: 0}
    }
    .panel{
      background: rgba(255,255,255,.04);
      border: 1px solid rgba(255,255,255,.08);
      border-radius: var(--radius);
      box-shadow: var(--shadow);
      overflow:hidden;
    }
    .heroLeft{padding: 26px 22px; position:relative}
    .kicker{display:inline-flex; gap:8px; align-items:center; font-weight:900; letter-spacing:.35px; font-size: 12px; color: rgba(255,255,255,.92)}
    .dot{width:8px; height:8px; border-radius:999px; background: var(--brand); box-shadow: 0 0 0 6px rgba(177,65,46,.20)}
    h1{margin: 12px 0 10px; font-size: 44px; line-height:1.05}
    @media (max-width: 520px){ h1{font-size: 36px;} }
    .lead{color: rgba(244,244,246,.86); font-size: 16px; max-width: 62ch}
    .pills{display:flex; flex-wrap:wrap; gap:10px; margin-top:14px}
    .pill{
      display:inline-flex; gap:8px; align-items:center;
      padding: 9px 10px; border-radius: 999px;
      background: rgba(255,255,255,.05);
      border: 1px solid rgba(255,255,255,.08);
      color: rgba(244,244,246,.88);
      font-weight:700; font-size: 13px;
    }
    .heroCtas{display:flex; flex-wrap:wrap; gap:10px; margin-top:18px}
    .heroRight{
      position:relative;
      padding: 22px;
      display:flex; flex-direction:column; gap:12px;
    }
    .card{
      background: rgba(0,0,0,.25);
      border: 1px solid rgba(255,255,255,.08);
      border-radius: 16px;
      padding: 16px;
    }
    .card h3{margin:0 0 8px; font-size: 16px}
    .muted{color: var(--muted)}
    .grid{
      margin-top: 16px;
      display:grid; gap:16px;
      grid-template-columns: 1fr 1fr 1fr;
    }
    @media (max-width: 980px){ .grid{grid-template-columns: 1fr} }
    .sectionTitle{margin: 30px 0 10px; font-size: 22px}
    .two{
      display:grid; gap:16px; grid-template-columns: 1.1fr .9fr;
      align-items: stretch;
    }
    @media (max-width: 980px){ .two{grid-template-columns: 1fr} }
    .menuImg{
      width:100%; height:auto; border-radius: 14px;
      border: 1px solid rgba(255,255,255,.10);
      box-shadow: 0 14px 40px rgba(0,0,0,.35);
      background:#1a1a1c;
    }
    .list{margin: 0; padding-left: 18px}
    .list li{margin: 7px 0}
    .form{
      display:grid; gap:10px;
    }
    label{font-weight:800; font-size: 13px}
    input, textarea, select{
      width:100%;
      padding: 12px 12px;
      border-radius: 14px;
      border: 1px solid rgba(255,255,255,.12);
      background: rgba(255,255,255,.04);
      color: var(--text);
      outline: none;
    }
    input:focus, textarea:focus, select:focus{ box-shadow: 0 0 0 6px var(--ring); border-color: rgba(255,255,255,.18) }
    textarea{min-height: 90px; resize: vertical}
    .footer{
      margin-top: 26px; padding-top: 18px;
      border-top: 1px solid rgba(255,255,255,.10);
      color: rgba(244,244,246,.70);
      display:flex; justify-content:space-between; gap:10px; flex-wrap:wrap;
      font-size: 13px;
    }
    .tiny{font-size:12px; color: rgba(244,244,246,.62)}
    .badge{
      display:inline-flex; align-items:center; gap:8px;
      padding: 10px 12px; border-radius: 16px;
      background: rgba(177,65,46,.14);
      border: 1px solid rgba(177,65,46,.26);
      font-weight:900;
    }
  </style>
</head>

<body>
  <div class="wrap">
    <!-- NAV -->
    <nav class="nav">
      <div class="brand">
        <img src="https://cafeginette.com/wp-content/uploads/2023/08/logo-ginette-rouge.png" alt="Café Ginette" />
        <div>
          <div style="font-weight:900; letter-spacing:.2px;">Café Ginette</div>
          <div class="tiny">Brasserie de quartier — Toulouse</div>
        </div>
      </div>

      <div class="navlinks">
        <a href="#concept">Concept</a>
        <a href="#menu">Menu</a>
        <a href="#evenements">Événements</a>
        <a href="#reservation">Réservation</a>
        <a class="btn ghost" href="#contact">📍 Accès</a>
        <a class="btn primary" href="tel:+33561570876">📞 Appeler</a>
      </div>
    </nav>

    <!-- HERO -->
    <section class="hero">
      <div class="panel heroLeft">
        <div class="kicker"><span class="dot"></span> 46 Avenue des Minimes — Toulouse</div>
        <h1>Une brasserie de quartier<br/>accessible & responsable.</h1>
        <p class="lead">
          Un peu populaire, un peu branchée, un peu festive, un peu cosy… <b>un peu tout</b>.
          Ici, on cuisine avec des partenaires locaux, des produits de saison, et on garde l’esprit simple : bien manger, bien boire, bien vivre.
        </p>

        <div class="pills">
          <span class="pill">🍻 Prix accessibles</span>
          <span class="pill">🥕 Produits de saison</span>
          <span class="pill">♻️ Démarche responsable</span>
          <span class="pill">🎶 Jams • DJ sets • Quizz</span>
        </div>

        <div class="heroCtas">
          <a class="btn primary" href="#reservation">Réserver</a>
          <a class="btn ghost" href="#menu">Voir le menu</a>
          <a class="btn ghost" href="https://www.google.com/maps?q=Caf%C3%A9+Ginette+46+Avenue+des+Minimes+Toulouse" target="_blank" rel="noreferrer">Itinéraire</a>
        </div>

        <div style="margin-top:14px" class="tiny">
          *Démo proposée (design + expérience client). Horaires et certains détails peuvent être ajustés.
        </div>
      </div>

      <aside class="panel heroRight">
        <div class="card">
          <div class="badge">⭐ Réserver en 10 secondes</div>
          <p class="muted" style="margin:10px 0 0">
            Choisis ton canal préféré : téléphone (immédiat) ou Facebook (comme aujourd’hui). On peut ajouter un formulaire de demande de réservation.
          </p>
          <div style="display:flex; gap:10px; flex-wrap:wrap; margin-top:12px;">
            <a class="btn primary" href="tel:+33561570876">📞 05 61 57 08 76</a>
            <a class="btn ghost" href="https://www.facebook.com/" target="_blank" rel="noreferrer">Réserver via Facebook</a>
          </div>
        </div>

        <div class="card">
          <h3 style="margin:0 0 6px;">Infos rapides</h3>
          <div class="muted">📍 46 Avenue des Minimes, Toulouse</div>
          <div class="muted">🚇 Métro : Minimes–Nougaro / Canal du Midi</div>
          <div class="muted">🗓️ Événements toute la semaine</div>
          <div class="tiny" style="margin-top:10px">
            On peut ajouter : horaires, lien Google Business, galerie photos, avis, réservation intégrée.
          </div>
        </div>
      </aside>
    </section>

    <!-- CONCEPT -->
    <h2 class="sectionTitle" id="concept">Le concept</h2>
    <div class="grid">
      <div class="panel" style="padding:18px">
        <h3 style="margin:0 0 8px">Accessible</h3>
        <p class="muted" style="margin:0">
          Une brasserie de quartier qui garde des prix cohérents avec le pouvoir d’achat, sans sacrifier l’expérience.
        </p>
      </div>
      <div class="panel" style="padding:18px">
        <h3 style="margin:0 0 8px">Responsable</h3>
        <p class="muted" style="margin:0">
          Produits de saison, partenaires locaux, attention à l’empreinte et à la revalorisation des déchets.
        </p>
      </div>
      <div class="panel" style="padding:18px">
        <h3 style="margin:0 0 8px">Vivant</h3>
        <p class="muted" style="margin:0">
          Jams swing, DJ sets, concerts, quizz… un café qui bouge et qui rassemble.
        </p>
      </div>
    </div>

    <!-- MENU -->
    <h2 class="sectionTitle" id="menu">Le menu du soir</h2>
    <div class="two">
      <div class="panel" style="padding:18px">
        <p class="muted" style="margin:0 0 12px">
          Un menu lisible sur mobile, en 1 scroll. Ici on peut intégrer une version “texte” plus légère + une image pour la carte du moment.
        </p>
        <img class="menuImg" src="https://cafeginette.com/wp-content/uploads/2025/11/menu-octobre-soir-ginette-2.jpg" alt="Menu du soir Café Ginette" />
        <div class="tiny" style="margin-top:10px">
          Astuce conversion : ajouter un bouton “Réserver” juste sous le menu.
        </div>
        <div style="display:flex; gap:10px; flex-wrap:wrap; margin-top:12px;">
          <a class="btn primary" href="#reservation">Réserver</a>
          <a class="btn ghost" href="tel:+33561570876">Appeler</a>
        </div>
      </div>

      <div class="panel" style="padding:18px" id="evenements">
        <h3 style="margin:0 0 8px">Événements</h3>
        <p class="muted" style="margin:0 0 12px">
          Une section simple pour annoncer les rendez-vous de la semaine (DJ set, quizz, concert…).
        </p>
        <ul class="list">
          <li><b>Quizz</b> — (à compléter)</li>
          <li><b>DJ set</b> — (à compléter)</li>
          <li><b>Jam / live</b> — (à compléter)</li>
        </ul>
        <div class="tiny" style="margin-top:10px">
          On peut aussi intégrer un mini “Agenda” + un lien Instagram pour les visuels.
        </div>

        <div style="margin-top:14px" class="card">
          <h3 style="margin:0 0 8px">Suivre l’actu</h3>
          <div style="display:flex; gap:10px; flex-wrap:wrap;">
            <a class="btn ghost" href="https://www.instagram.com/" target="_blank" rel="noreferrer">Instagram</a>
            <a class="btn ghost" href="https://www.facebook.com/" target="_blank" rel="noreferrer">Facebook</a>
          </div>
        </div>
      </div>
    </div>

    <!-- RESERVATION -->
    <h2 class="sectionTitle" id="reservation">Réservation</h2>
    <div class="two">
      <div class="panel" style="padding:18px">
        <h3 style="margin:0 0 8px">Réserver maintenant</h3>
        <p class="muted" style="margin:0 0 12px">
          Deux clics : appeler, ou réserver via Facebook. (Et si vous voulez : formulaire intégré.)
        </p>
        <div style="display:flex; gap:10px; flex-wrap:wrap;">
          <a class="btn primary" href="tel:+33561570876">📞 Appeler</a>
          <a class="btn ghost" href="https://www.facebook.com/" target="_blank" rel="noreferrer">💬 Réserver via Facebook</a>
          <a class="btn ghost" href="https://www.google.com/maps?q=Caf%C3%A9+Ginette+46+Avenue+des+Minimes+Toulouse" target="_blank" rel="noreferrer">🗺️ Itinéraire</a>
        </div>
        <div class="tiny" style="margin-top:10px">
          *Le lien Facebook/Instagram peut être remplacé par les URLs officielles.
        </div>
      </div>

      <div class="panel" style="padding:18px">
        <h3 style="margin:0 0 8px">Demande de réservation (option)</h3>
        <p class="muted" style="margin:0 0 12px">
          Formulaire simple. Ici en démo, il envoie un e-mail via votre application mail.
        </p>

        <form class="form" action="mailto:contact@cafeginette.com" method="post" enctype="text/plain">
          <div>
            <label for="name">Nom / Prénom</label>
            <input id="name" name="Nom" placeholder="Ex: Julie Martin" required />
          </div>
          <div>
            <label for="phone">Téléphone</label>
            <input id="phone" name="Téléphone" placeholder="Ex: 06 00 00 00 00" required />
          </div>
          <div style="display:grid; gap:10px; grid-template-columns: 1fr 1fr;">
            <div>
              <label for="date">Date</label>
              <input id="date" name="Date" type="date" required />
            </div>
            <div>
              <label for="time">Heure</label>
              <input id="time" name="Heure" type="time" required />
            </div>
          </div>
          <div>
            <label for="people">Couverts</label>
            <select id="people" name="Couverts">
              <option>1</option><option>2</option><option>3</option><option>4</option>
              <option>5</option><option>6</option><option>7</option><option>8+</option>
            </select>
          </div>
          <div>
            <label for="msg">Message (optionnel)</label>
            <textarea id="msg" name="Message" placeholder="Allergies, poussette, terrasse…"></textarea>
          </div>

          <button class="btn primary" type="submit">Envoyer la demande</button>
          <div class="tiny">
            Pour un vrai usage pro : on branche Formspree / Netlify Forms / un outil de réservation.
          </div>
        </form>
      </div>
    </div>

    <!-- CONTACT -->
    <h2 class="sectionTitle" id="contact">Contact & Accès</h2>
    <div class="panel" style="padding:18px">
      <div class="two" style="grid-template-columns: 1fr 1fr;">
        <div>
          <h3 style="margin:0 0 8px">Café Ginette</h3>
          <p class="muted" style="margin:0 0 8px">46 Avenue des Minimes, Toulouse</p>
          <p class="muted" style="margin:0 0 8px">🚇 Minimes–Nougaro / Canal du Midi</p>
          <p class="muted" style="margin:0 0 12px">📞 <a href="tel:+33561570876">05 61 57 08 76</a></p>

          <div style="display:flex; gap:10px; flex-wrap:wrap;">
            <a class="btn primary" href="tel:+33561570876">Appeler</a>
            <a class="btn ghost" href="https://www.google.com/maps?q=Caf%C3%A9+Ginette+46+Avenue+des+Minimes+Toulouse" target="_blank" rel="noreferrer">Itinéraire</a>
          </div>

          <div class="tiny" style="margin-top:10px">
            Horaires : à ajouter (ou import auto via Google Business).
          </div>
        </div>

        <div class="card">
          <h3 style="margin:0 0 8px">Ce que ce nouveau site améliore</h3>
          <ul class="list">
            <li>Boutons <b>Appeler / Réserver / Itinéraire</b> visibles immédiatement</li>
            <li>Menu consultable en 1 scroll (mobile first)</li>
            <li>Section événements claire</li>
            <li>Formulaire de demande (option)</li>
            <li>Structure SEO + partage (OpenGraph)</li>
          </ul>
        </div>
      </div>
    </div>

    <div class="footer">
      <div>© Café Ginette — Démo de refonte (proposition)</div>
      <div class="tiny">Design & structure : version démonstration. Contenus/photos supplémentaires : à intégrer avec le client.</div>
    </div>
  </div>
</body>
</html>
