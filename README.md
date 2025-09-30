# Bienvenue sur ma page de DEV — **zabuzafr**

> Développeur & architecte technique — J’optimise, j’automatise et je rends les plateformes **plus rapides, fiables et scalables**.

---

<style>
/************
 * Thème Jekyll coloré + NAV sticky
 ************/
:root{
  --bg:#0f1020;           /* nuit indigo */
  --grad1:#7a1e1e;        /* rouge laqué */
  --grad2:#c5a253;        /* or doux */
  --ink:#e7e8ff;          /* encre claire */
  --muted:#aab1d6;        /* texte secondaire */
  --card:#161733;         /* panneau */
  --border:#282a4a;       /* bordure douce */
  --accent:#ffc857;       /* accent doré */
}
html,body{background:var(--bg);} 
main{font:16px/1.7 system-ui,-apple-system,Segoe UI,Roboto,Ubuntu,Cantarell,Noto Sans,Helvetica,Arial,"Apple Color Emoji","Segoe UI Emoji";color:var(--ink);}
.container{max-width:1050px;margin:0 auto;padding:20px}
.navwrap{position:sticky;top:0;z-index:50;background:linear-gradient(180deg,#0f1020f2,#0f1020e6);backdrop-filter:saturate(140%) blur(6px);border-bottom:1px solid var(--border)}
.nav{display:flex;gap:14px;align-items:center;justify-content:space-between;padding:10px 20px}
.nav a{color:var(--ink);text-decoration:none;font-size:14px;opacity:.9}
.nav a:hover{opacity:1;text-decoration:underline}
.brand{display:flex;gap:10px;align-items:center}
.brand .dot{width:10px;height:10px;border-radius:99px;background:var(--accent)}

.hero{position:relative;overflow:hidden;border:1px solid var(--border);border-radius:20px;background:linear-gradient(135deg,var(--grad1),var(--grad2));padding:48px;margin:24px 0;}
.hero h1{font-size:40px;margin:0 0 10px}
.hero p{margin:0;color:#fff;opacity:.92}
.hero .cta{display:inline-block;margin-top:18px;padding:10px 16px;border-radius:999px;background:#00000022;border:1px solid #ffffff80;color:#fff;text-decoration:none}

.grid{display:grid;gap:16px}
.cards{grid-template-columns:repeat(auto-fit,minmax(240px,1fr))}
.card{background:var(--card);border:1px solid var(--border);border-radius:16px;padding:16px}
.card h3{margin:.2rem 0 0.4rem}
.small{color:var(--muted);font-size:14px}
.badges img{height:20px;margin:2px;vertical-align:middle}

section h2{font-size:26px;margin:28px 0 10px}
hr{border:none;border-top:1px solid var(--border);margin:28px 0}

kbd{background:#0002;padding:2px 6px;border:1px solid #fff2;border-radius:6px}
.footer{opacity:.8;font-size:14px}

/* Formulaire */
form label{display:block;font-size:14px;margin:6px 0 4px;color:var(--muted)}
form input, form textarea{width:100%;background:#0f1026;border:1px solid var(--border);border-radius:10px;color:var(--ink);padding:10px}
form button{margin-top:8px;background:var(--grad1);border:1px solid #ffffff22;color:#fff;border-radius:999px;padding:10px 16px;cursor:pointer}
form button:hover{filter:brightness(1.05)}

/* Ancre retour haut */
.totop{position:fixed;right:16px;bottom:16px;background:#0008;color:#fff;border:1px solid #fff2;border-radius:999px;padding:8px 12px;text-decoration:none}
</style>

<div class="navwrap">
  <nav class="nav">
    <div class="brand"><span class="dot"></span><strong>zabuzafr</strong></div>
    <div class="links">
      <a href="#profil">Profil</a>
      <a href="#competences">Compétences</a>
      <a href="#technos">Technos</a>
      <a href="#experiences">Missions</a>
      <a href="#projets">Projets</a>
      <a href="#contact">Contact</a>
    </div>
  </nav>
</div>

<div class="container">
  <section class="hero">
    <h1>Bienvenue 👋 — Je suis <strong>zabuzafr</strong></h1>
    <p>Bienvenue sur ma page de développeur. Ici, je présente mes <strong>compétences</strong>, <strong>projets</strong> et <strong>expériences</strong>.</p>
    <a class="cta" href="#projets">Voir mes projets</a>
  </section>

  <section id="profil">
    <h2>À propos</h2>
    <div class="card">
      <p>
        **Architecte technique & développeur.** Je conçois, déploie et optimise des <strong>infrastructures critiques</strong>. Expertise avancée <strong>IBM AIX</strong>, <strong>PowerVM</strong> et clusters <strong>HACMP/PowerHA</strong> haute disponibilité ; contribution à des environnements complexes à grande échelle (dont <strong>SAP</strong>, <strong>DB2 PureScale</strong>) et <strong>migrations stratégiques</strong> avec objectifs de continuité de service.
      </p>
      <p>
        Côté développement, je maîtrise <strong>C/C++</strong> et <strong>Java</strong>, avec une spécialité dans le <strong>portage d’applications de Linux vers FreeBSD</strong>, en améliorant performances et compatibilité. Je conçois également des solutions pour <strong>datacenters</strong> et <strong>domotique</strong> : intégration d’<strong>onduleurs photovoltaïques</strong> sur <strong>Raspberry Pi</strong> et <strong>Arduino</strong>.
      </p>
      <p class="small">
        Conception récente d’une **plateforme cloud pour PME** basée sur <strong>Proxmox</strong> et <strong>OpenStack</strong>, offrant des services évolutifs et sur mesure. Approche : expertise système, optimisation et développement de solutions personnalisées pour les contextes exigeants.
      </p>
    </div>
    <details style="margin-top:10px" open>
      <summary><strong>English bio</strong></summary>
      <div class="card" style="margin-top:10px">
        <p>
          **Technical Architect & Developer.** I design, implement, and optimize <strong>mission‑critical infrastructure</strong>. Advanced expertise in <strong>IBM AIX</strong>, <strong>PowerVM</strong>, and <strong>HACMP/PowerHA</strong> high‑availability clusters; contributions to large‑scale, complex environments (including <strong>SAP</strong>, <strong>DB2 PureScale</strong>) and <strong>zero‑downtime migrations</strong>.
        </p>
        <p>
          On the software side, I’m proficient in <strong>C/C++</strong> and <strong>Java</strong>, with a focus on <strong>porting applications from Linux to FreeBSD</strong> while improving performance and compatibility. I also build solutions for <strong>data centers</strong> and <strong>home automation</strong>, integrating <strong>photovoltaic inverters</strong> with <strong>Raspberry Pi</strong> and <strong>Arduino</strong>.
        </p>
        <p class="small">
          Recently, I designed an **SMB‑friendly cloud stack** based on <strong>Proxmox</strong> and <strong>OpenStack</strong>, delivering scalable and tailored services. My approach blends hands‑on engineering, system optimization, and custom solution development.
        </p>
      </div>
    </details>
  </section>

  <section id="competences">
    <h2>Compétences clés</h2>
    <div class="grid cards">
      <div class="card"><h3>Développement</h3><p class="small">C/C++, Java · Portage Linux → FreeBSD · Optimisation & compatibilité</p></div>
      <div class="card"><h3>Infrastructures critiques</h3><p class="small">AIX, PowerVM, HACMP/PowerHA · Clusters HA · Exploitation SAP / DB2 PureScale</p></div>
      <div class="card"><h3>Cloud & Virtualisation</h3><p class="small">Proxmox, OpenStack · Migrations & modernisation</p></div>
      <div class="card"><h3>Stockage & Sauvegarde</h3><p class="small">SAN (Hitachi, IBM), Spectrum Protect/TSM · PRA/haute dispo</p></div>
      <div class="card"><h3>IoT & Embarqué</h3><p class="small">Raspberry Pi, Arduino · Intégration onduleurs photovoltaïques</p></div>
      <div class="card"><h3>Sécurité & Alerting</h3><p class="small">Solutions alignées <strong>PCI DSS</strong> · Supervision & alertes</p></div>
    </div>
  </section>

  <section id="technos">
    <h2>Technos maîtrisées</h2>
    <div class="card">
      <div class="badges">
        <img alt="AIX" src="https://img.shields.io/badge/AIX-002b36"/>
        <img alt="Linux" src="https://img.shields.io/badge/Linux-111"/>
        <img alt="FreeBSD" src="https://img.shields.io/badge/FreeBSD-a00000?logo=freebsd&logoColor=fff"/>
        <img alt="IBM%20Power" src="https://img.shields.io/badge/IBM%20Power-1b3a8a"/>
        <img alt="PowerVM" src="https://img.shields.io/badge/PowerVM-334a9f"/>
        <img alt="HACMP/PowerHA" src="https://img.shields.io/badge/HACMP%2FPowerHA-333"/>
        <img alt="SAN" src="https://img.shields.io/badge/SAN-233"/>
        <img alt="TSM" src="https://img.shields.io/badge/Spectrum%20Protect%20(TSM)-20445e"/>
        <img alt="Oracle" src="https://img.shields.io/badge/Oracle-db4437"/>
        <img alt="DB2" src="https://img.shields.io/badge/DB2-0f6d5f"/>
        <img alt="Proxmox" src="https://img.shields.io/badge/Proxmox-E57000?logo=proxmox&logoColor=fff"/>
        <img alt="OpenStack" src="https://img.shields.io/badge/OpenStack-ed1944?logo=openstack&logoColor=fff"/>
        <img alt="C++" src="https://img.shields.io/badge/C%2B%2B-00599C?logo=c%2B%2B&logoColor=fff"/>
        <img alt="Java" src="https://img.shields.io/badge/Java-ED8B00?logo=openjdk&logoColor=fff"/>
      </div>
      <p class="small" style="margin-top:8px">Documentation, supervision (Grafana), scripts d’audit AIX, automatisations TSM, guides de migration.</p>
    </div>
  </section>

  <section id="experiences">
    <h2>Missions (sélection)</h2>
    <div class="grid cards">
      <div class="card">
        <h3>Architecte technique — STET</h3>
        <p class="small">Référent système & stockage (prod sensible). Spectrum Protect/TSM, PowerVM/AIX, SAN (HDS/IBM). ➜ <strong>PRA</strong> renforcé, <strong>optimisations</strong> perfs DB Oracle.</p>
      </div>
      <div class="card">
        <h3>Architecte technique — ENIM</h3>
        <p class="small">Conception AIX/Linux pour bases Oracle sur PowerVM. Migrations AIX→Linux, sécurité, consolidation. ➜ <strong>standardisation</strong> environnements.</p>
      </div>
      <div class="card">
        <h3>Expert IBM PowerVM AIX/GPFS — PMU</h3>
        <p class="small">Optimisation DB2 PureScale : affinité CPU/Mémoire, tuning GPFS, sizing LPAR/CF. ➜ <strong>latence réduite</strong>, <strong>capacité accrue</strong>.</p>
      </div>
      <div class="card">
        <h3>Cloud Capacity Planner — Silca</h3>
        <p class="small">Plans capacitaires mensuels/trimestriels (AIX P7/P8, Linux). ➜ <strong>prévisions</strong> fiables & recommandations d’optimisation.</p>
      </div>
    </div>
  </section>

  <section id="projets">
    <h2>Projets & contenus</h2>
    <div class="card">
      <p class="small">(À compléter) — Exemples : scripts d’audit AIX, automatisations backup TSM, tableaux de capacity planning, guides de migration AIX→FreeBSD/Linux.</p>
    </div>
  </section>

  <section id="contact">
    <h2>Contact</h2>
    <div class="grid cards">
      <div class="card">
        <h3>GitHub</h3>
        <p class="small"><a href="https://github.com/zabuzafr">github.com/zabuzafr</a></p>
      </div>
      <div class="card">
        <h3>Email</h3>
        <p class="small"><a href="mailto:contact@zabuzafr.dev">contact@zabuzafr.dev</a> (exemple)</p>
      </div>
      <div class="card">
        <h3>Formulaire</h3>
        <form action="https://formspree.io/f/VOUS-REMPLACEZ-CET-ID" method="POST">
          <label>Votre email</label>
          <input type="email" name="email" required>
          <label>Message</label>
          <textarea name="message" rows="4" required></textarea>
          <button type="submit">Envoyer</button>
          <p class="small">Remplacez l’ID Formspree pour activer l’envoi.</p>
        </form>
      </div>
    </div>
  </section>

  <hr/>
  <p class="footer">© <span id="y"></span> — zabuzafr. Propulsé par GitHub Pages (Jekyll). Style coloré personnalisé.</p>
</div>

<a href="#" class="totop" title="Haut de page">↑ Haut</a>

<script>document.getElementById('y').textContent = new Date().getFullYear()</script>
