<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Qui suis-je ? — Corps & Plaisirs · Onyn Cossé</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,300;0,400;0,500;0,600;1,300;1,400;1,500&family=Jost:wght@300;400;500;600&display=swap" rel="stylesheet">
<link rel="stylesheet" href="styles.css">
</head>
<body>

<!-- ══ NAV ══ -->
<nav>
  <a class="nav-brand" href="index.html">
    <img class="nav-logo-img" src="assets/logo.png" alt="Corps & Plaisirs"
         onerror="this.style.display='none';this.nextElementSibling.style.display='flex'">
    <svg style="display:none;height:52px;width:auto" viewBox="0 0 200 56" fill="none" xmlns="http://www.w3.org/2000/svg">
      <text x="0" y="28" font-family="Cormorant Garamond,serif" font-size="20" font-weight="500" fill="#3d2314">CORPS &amp;</text>
      <text x="0" y="50" font-family="Cormorant Garamond,serif" font-size="20" font-weight="500" fill="#3d2314">PLAISIRS</text>
    </svg>
  </a>
  <ul class="nav-links">
    <li><a href="index.html" data-page="accueil">Accueil</a></li>
    <li><a href="cadre.html" data-page="cadre">Le cadre</a></li>
    <li><a href="qui.html" data-page="qui" class="active">Qui suis-je ?</a></li>
    <li><a href="accompagnements.html" data-page="accompagnements">Accompagnements</a></li>
    <li><a href="rendez-vous.html" data-page="rdv">Rendez-vous</a></li>
    <li><a href="contact.html" data-page="contact">Contact</a></li>
    <li><a href="faq.html" data-page="faq">FAQ</a></li>
    <li><a href="avis.html" data-page="avis">Avis</a></li>
  </ul>
  <div class="hamburger" onclick="toggleMenu()"><span></span><span></span><span></span></div>
</nav>
<div class="mob-nav" id="mobNav">
  <a href="index.html" onclick="closeMenu()">Accueil</a>
  <a href="cadre.html" onclick="closeMenu()">Le cadre</a>
  <a href="qui.html" onclick="closeMenu()">Qui suis-je ?</a>
  <a href="accompagnements.html" onclick="closeMenu()">Accompagnements</a>
  <a href="rendez-vous.html" onclick="closeMenu()">Rendez-vous</a>
  <a href="contact.html" onclick="closeMenu()">Contact</a>
  <a href="faq.html" onclick="closeMenu()">FAQ</a>
  <a href="avis.html" onclick="closeMenu()">Avis</a>
</div>

<!-- ══ PAGE QUI SUIS-JE ══ -->
<div id="pg-qui" class="page active sec" style="background:var(--blanc)">
  <div class="sh">
    <div class="stag">Découvrir</div>
    <h2 class="stitle">Qui <em>suis-je ?</em></h2>
    <div class="sdiv"></div>
  </div>
  <div class="qui-g">
    <div>
      <div class="qphoto">
        <img src="assets/photo-onyn.jpg" alt="Onyn Cossé"
             onerror="this.parentElement.style.minHeight='300px'">
      </div>
      <div class="qcard">
        <h4>Me contacter</h4>
        <div class="qci">📧 <a href="mailto:contact@corpsetplaisirs.fr">contact@corpsetplaisirs.fr</a></div>
        <div class="qci">📱 <a href="tel:+33769008729">+33 7 69 00 87 29</a></div>
        <div class="qci">📍 Le Mans — Consultations en visio</div>
        <div class="qci">🕐 Lundi au Samedi</div>
      </div>
    </div>
    <div class="qr">
      <h3>Mon parcours</h3>
      <p>Après un chemin personnel et professionnel nourri par la curiosité et l'humanité, j'ai choisi de me former à la sexo-thérapie pour accompagner les personnes dans leur rapport à la sexualité, au désir et au corps.</p>
      <p>Ma démarche est résolument intégrative : j'articule des apports de la psycho-sexologie clinique, de la pleine conscience et de l'hypnose éricksonienne pour proposer un accompagnement ancré, respectueux et sur mesure.</p>
      <p>J'accompagne les individus et les couples, quelles que soient leurs orientations sexuelles, leurs identités de genre ou leurs formes de relation. Mon engagement est simple : vous offrir un espace pour être pleinement vous-même.</p>

      <div class="fsec">
        <h3>Formations &amp; Diplômes</h3>
        <div class="fgrid">
          <div class="fcard">
            <span class="fbadge">En cours</span>
            <h4>Diplôme Universitaire</h4>
            <p>Université de Poitiers — Conseiller en Santé Sexuelle</p>
          </div>
          <div class="fcard">
            <span class="fbadge">Formation</span>
            <h4>École Psycho-Sexologie de Paris</h4>
            <p>Approche clinique et thérapeutique de la psycho-sexologie</p>
          </div>
          <div class="fcard">
            <span class="fbadge">Initiation</span>
            <h4>Hypnose éricksonienne</h4>
            <p>Séminaire — École Psycho-Sexologie de Paris</p>
          </div>
          <div class="fcard">
            <span class="fbadge">Initiation</span>
            <h4>Pleine Conscience</h4>
            <p>Mindfulness &amp; présence corporelle — École Psycho-Sexologie de Paris</p>
          </div>
        </div>
        <div class="flogos">
          <div class="flogo">🎓 Université de Poitiers<span>Diplôme Universitaire</span></div>
          <div class="flogo">🧠 École Psycho-Sexologie<span>de Paris</span></div>
          <div class="flogo">🏅 SNSC<span>Membre certifié</span></div>
        </div>
        <a href="https://www.snsc.fr" target="_blank" class="snsc-lnk">
          🏅 &nbsp;Membre du <strong>&nbsp;SNSC</strong> — Syndicat National des Sexologues Cliniciens
        </a>
      </div>

      <!-- Autre formation -->
      <div class="fsec">
        <h3>Autre formation</h3>
        <div class="fgrid">
          <div class="fcard fcard-link" onclick="openDiplome()" title="Cliquer pour voir le diplôme">
            <span class="fbadge" style="background:var(--vert)">Diplôme</span>
            <h4>Licence STAPS</h4>
            <p>Spécialité Éducation et Motricité — Enseignant·e d'EPS second degré<br>Université du Mans · 2025</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>

<!-- MODAL DIPLÔME LICENCE -->
<div class="diplome-modal-bg" id="diplome-modal">
  <div class="diplome-modal">
    <button class="diplome-modal-close" onclick="closeDiplome()">×</button>
    <img src="assets/diplome-staps.jpg" alt="Diplôme Licence STAPS — Onyn Cossé">
  </div>
</div>

<!-- ══ FOOTER ══ -->
<footer id="site-footer">
  <p style="font-family:'Cormorant Garamond',serif;font-size:1.02rem;color:var(--sable);margin-bottom:8px">Corps &amp; Plaisirs — Onyn Cossé, Sexo-thérapeute</p>
  <p><a href="mailto:contact@corpsetplaisirs.fr">contact@corpsetplaisirs.fr</a> &nbsp;·&nbsp; <a href="tel:+33769008729">+33 7 69 00 87 29</a></p>
  <p style="margin-top:8px;opacity:.44;font-size:.68rem">Membre SNSC · DU Santé Sexuelle Poitiers · École Psycho-Sexologie de Paris</p>
  <p style="margin-top:4px;opacity:.3;font-size:.64rem">© 2026 Onyn Cossé · @corpsetplaisirs</p>
</footer>

<!-- ══ ADMIN ══ -->
<button id="adm-btn" onclick="openAdm()" title="Gérer mes disponibilités">⚙️</button>
<div class="adm-bg" id="adm-bg">
  <div class="adm-box">
    <div class="adm-hd"><h2>⚙️ Gestion</h2><button class="adm-x" onclick="closeAdm()">×</button></div>
    <div class="adm-body">
      <div class="adm-sec"><h3>Jours</h3><div class="dtog" id="dtog"></div></div>
      <div class="adm-sec"><h3>Créneaux</h3><div class="smgr" id="smgr"></div>
        <div class="asr"><input type="time" id="new-t"><button class="bsm" onclick="addSlot()">+ Ajouter</button><span class="sm" id="sm1"></span></div>
      </div>
      <div class="adm-sec"><h3>Jours fermés</h3>
        <div class="dor"><input type="date" id="cl-date"><button class="bsm" onclick="addClosed()">Bloquer</button></div>
        <div id="cl-list" style="display:flex;flex-wrap:wrap;gap:7px;margin-top:8px"></div>
      </div>
      <div class="adm-sec"><h3>Créneaux réservés</h3><div id="adm-booked" style="display:flex;flex-wrap:wrap;gap:8px;margin-top:8px"></div></div>
      <div class="adm-sec"><h3>Demandes</h3><div class="rdv-lst" id="adm-rdv"><p class="hint">Aucune demande.</p></div></div>
      <button class="bsm" style="width:100%;padding:12px" onclick="saveAdm()">💾 Sauvegarder</button>
      <span class="sm" id="sm2" style="display:block;text-align:center;margin-top:8px"></span>
    </div>
  </div>
</div>

<script src="main.js"></script>
</body>
</html>
