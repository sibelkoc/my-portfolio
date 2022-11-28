<template>
  <div class="content">
    <div id="home">
      <div class="wrapper">
        <img
          src="../assets/SibelLogo.png"
          alt="logo"
          style="max-width: 4em; display: flex; margin-right: 10px"
        />
        <div class="content-sibelkreation">
          <div class="ok">SibelKreation</div>
          <div class="ok">SibelKreation</div>
        </div>
      </div>
      <div class="text-home">
        <p>
          Après avoir étudié le développement web et web mobile,<br />
          je suis à la recherche d'un contrat d'apprentissage pour un BAC+3 en Web design/Ux design,
          ou en tant que responsable projet web marketing et communication digitale !<br />
        </p>
      </div>
      <q-btn
        push
        type="a"
        class="intro-contact"
        href="mailto:sibel.koc.pro@outlook.fr"
        label="Envoyer un email"
      />
    </div>

    <div class="sidebar-nav">
      <div class="sidebar-links">
        <div class="fade-in-section is-visible" style="transition-delay: 100ms">
          <div><a href="#home">/Accueil</a></div>
        </div>

        <div class="fade-in-section is-visible" style="transition-delay: 200ms">
          <div><a href="#about">/A Propos</a></div>
        </div>

        <div class="fade-in-section is-visible" style="transition-delay: 300ms">
          <div><a href="#experience">/Expériences</a></div>
        </div>

        <div class="fade-in-section is-visible" style="transition-delay: 400ms">
          <div><a href="#projects">/Créations</a></div>
        </div>

      </div>



      <div class="sidebar-logos" href="/">
        <a href="mailto:sibel.koc.pro@outlook.fr"
          ><svg
            class="MuiSvgIcon-root"
            focusable="false"
            viewBox="0 0 512 512"
            aria-hidden="true"
            style="font-size: 19px"
          >
            <path
              d="M464 64C490.5 64 512 85.49 512 112C512 127.1 504.9 141.3 492.8 150.4L275.2 313.6C263.8 322.1 248.2 322.1 236.8 313.6L19.2 150.4C7.113 141.3 0 127.1 0 112C0 85.49 21.49 64 48 64H464zM217.6 339.2C240.4 356.3 271.6 356.3 294.4 339.2L512 176V384C512 419.3 483.3 448 448 448H64C28.65 448 0 419.3 0 384V176L217.6 339.2z"
            ></path></svg
        ></a>
        <a href="https://github.com/sibelkoc"
          ><svg
            class="MuiSvgIcon-root"
            focusable="false"
            viewBox="0 0 496 512"
            aria-hidden="true"
            style="font-size: 19px"
          >
            <path
              d="M165.9 397.4c0 2-2.3 3.6-5.2 3.6-3.3.3-5.6-1.3-5.6-3.6 0-2 2.3-3.6 5.2-3.6 3-.3 5.6 1.3 5.6 3.6zm-31.1-4.5c-.7 2 1.3 4.3 4.3 4.9 2.6 1 5.6 0 6.2-2s-1.3-4.3-4.3-5.2c-2.6-.7-5.5.3-6.2 2.3zm44.2-1.7c-2.9.7-4.9 2.6-4.6 4.9.3 2 2.9 3.3 5.9 2.6 2.9-.7 4.9-2.6 4.6-4.6-.3-1.9-3-3.2-5.9-2.9zM244.8 8C106.1 8 0 113.3 0 252c0 110.9 69.8 205.8 169.5 239.2 12.8 2.3 17.3-5.6 17.3-12.1 0-6.2-.3-40.4-.3-61.4 0 0-70 15-84.7-29.8 0 0-11.4-29.1-27.8-36.6 0 0-22.9-15.7 1.6-15.4 0 0 24.9 2 38.6 25.8 21.9 38.6 58.6 27.5 72.9 20.9 2.3-16 8.8-27.1 16-33.7-55.9-6.2-112.3-14.3-112.3-110.5 0-27.5 7.6-41.3 23.6-58.9-2.6-6.5-11.1-33.3 2.6-67.9 20.9-6.5 69 27 69 27 20-5.6 41.5-8.5 62.8-8.5s42.8 2.9 62.8 8.5c0 0 48.1-33.6 69-27 13.7 34.7 5.2 61.4 2.6 67.9 16 17.7 25.8 31.5 25.8 58.9 0 96.5-58.9 104.2-114.8 110.5 9.2 7.9 17 22.9 17 46.4 0 33.7-.3 75.4-.3 83.6 0 6.5 4.6 14.4 17.3 12.1C428.2 457.8 496 362.9 496 252 496 113.3 383.5 8 244.8 8zM97.2 352.9c-1.3 1-1 3.3.7 5.2 1.6 1.6 3.9 2.3 5.2 1 1.3-1 1-3.3-.7-5.2-1.6-1.6-3.9-2.3-5.2-1zm-10.8-8.1c-.7 1.3.3 2.9 2.3 3.9 1.6 1 3.6.7 4.3-.7.7-1.3-.3-2.9-2.3-3.9-2-.6-3.6-.3-4.3.7zm32.4 35.6c-1.6 1.3-1 4.3 1.3 6.2 2.3 2.3 5.2 2.6 6.5 1 1.3-1.3.7-4.3-1.3-6.2-2.2-2.3-5.2-2.6-6.5-1zm-11.4-14.7c-1.6 1-1.6 3.6 0 5.9 1.6 2.3 4.3 3.3 5.6 2.3 1.6-1.3 1.6-3.9 0-6.2-1.4-2.3-4-3.3-5.6-2z"
            ></path></svg
        ></a>
        <a href="https://www.linkedin.com/in/sibel-koc/"
          ><svg
            class="MuiSvgIcon-root"
            focusable="false"
            viewBox="0 0 448 512"
            aria-hidden="true"
            style="font-size: 19px"
          >
            <path
              d="M416 32H31.9C14.3 32 0 46.5 0 64.3v383.4C0 465.5 14.3 480 31.9 480H416c17.6 0 32-14.5 32-32.3V64.3c0-17.8-14.4-32.3-32-32.3zM135.4 416H69V202.2h66.5V416zm-33.2-243c-21.3 0-38.5-17.3-38.5-38.5S80.9 96 102.2 96c21.2 0 38.5 17.3 38.5 38.5 0 21.3-17.2 38.5-38.5 38.5zm282.1 243h-66.4V312c0-24.8-.5-56.7-34.5-56.7-34.6 0-39.9 27-39.9 54.9V416h-66.4V202.2h63.7v29.2h.9c8.9-16.8 30.6-34.5 62.9-34.5 67.2 0 79.7 44.3 79.7 101.9V416z"
            ></path></svg
        ></a>
      </div>
    </div>

    <div id="about">
      <div class="section-header">
        <span class="section-title">A propos de moi</span>
      </div>
      <div class="about-content">
        <div class="about-description">
          <p>
            Je suis actuellement à la recherche d'un contrat d'apprentissage dans le but de réaliser un Bac+3 en <b>"WebDesign"</b> ou en <b>"Responsable de projet web marketing &amp; communication digitale"</b> à l'<b><a terget="_blank" href="https://www.iscod.fr/">ISCOD</a></b>.
            <br /><br />- Concernant la formation <b>"Web Design</b>, j'apprendrai différentes technologies et méthodes abordées tels que la culture graphique, 
            les chartes graphiques, la gestion de projet,  les suites adobes, le dessin et story bording,
            l'UX &amp; l'UI design; le web marketing ainsi que les CMS tel que Wordpress... <br />
            - Concernant la formation <b>"Responsable de projet web marketing &amp; communication digitale"</b>, j'apprendrai à intégrer le digital dans sa stratégie et communication plurimédia,
            conception et pilotage d'un plan marketing online, business plan, cybersécurité (niveau 1), web marketing, créer et maintenir un blog Wordpress, digital brand content, Google Ads, Photoshop,
            gestion des réseaux sociaux, la web conversion et l'expérience utilisateur, les stratégies marketing cross-canal, la gestion de projet, le référencement naturel, les tableaux de bord et KPIs appliqués au web marketing...
            <br /><br />
            <strong>En 3 lignes, l'ISCOD c'est :</strong><br/>
            - Une école 100% en ligne.<br />
            - Rythme de 4 jours en entreprise et 1 jour en formation.<br />
            - La journée consacrée à la formation sera décidée par l'employeur au début de la formation.<br />

            
            <br />
            Après être diplômée, je souhaiterais continuer mon cursus avec un
            BAC+5 en <b><a target="_blank" href="https://www.iscod.fr/formation-mastere-management-projet-digital-en-alternance"><u>
              Mastère management de projet digital</u></a></b> ou en <b><a target="_blank" href="https://www.iscod.fr/formation-marketing-communication-en-alternance">
              <u>Mastère marketing et communication</u></a></b> en
            alternance avec
            <a target="_blank" href="https://www.iscod.fr/"><u>l'ISCOD</u></a>
          </p>

          Voici quelques technologies avec lesquelles je travaille :
          <ul class="tech-stack">
            <div
              class="fade-in-section is-visible"
              style="transition-delay: 100ms"
            >
              <li>Javascript ES6+</li>
            </div>
            <div
              class="fade-in-section is-visible"
              style="transition-delay: 200ms"
            >
              <li>Python</li>
            </div>
            <div
              class="fade-in-section is-visible"
              style="transition-delay: 300ms"
            >
              <li>JS-React/Vue</li>
            </div>
            <div
              class="fade-in-section is-visible"
              style="transition-delay: 400ms"
            >
              <li>Quasar/Bootstrap</li>
            </div>
            <div
              class="fade-in-section is-visible"
              style="transition-delay: 500ms"
            >
              <li>Node.js/Express</li>
            </div>
            <div
              class="fade-in-section is-visible"
              style="transition-delay: 600ms"
            >
              <li>HTML &amp; CSS</li>
            </div>
            <div
              class="fade-in-section is-visible"
              style="transition-delay: 700ms"
            >
              <li>Php</li>
            </div>
            <div
              class="fade-in-section is-visible"
              style="transition-delay: 800ms"
            >
              <li>PhpMyAdmin &amp; MySql</li>
            </div>
            <div
              class="fade-in-section is-visible"
              style="transition-delay: 900ms"
            >
              <li>Github &amp; Gitlab &amp; Git</li>
            </div>
            <div
              class="fade-in-section is-visible"
              style="transition-delay: 900ms"
            >
              <li>CMS-Wordpress/UI-UX</li>
            </div>
            <div
              class="fade-in-section is-visible"
              style="transition-delay: 1000ms"
            >
              <li>Bureautique (office 365)</li>
            </div>
            <div
              class="fade-in-section is-visible"
              style="transition-delay: 1000ms"
            >
              <li>VSC; Oracle; Eclipse; Netbeans</li>
            </div>
          </ul>
          <br />
          En-dehors du travail, j'aime lire des livres et
          je continue mon apprentissage personnel dans le domaine du développement web et web mobile
          grâce à des plateformes contenant diverses technologies, outils et langages.
          Je me forme également en design (Blender 3d... )

        </div>

        <div class="about-image">
          <img src="../assets/Sibelweb.jpg" />
        </div>
      </div>
    </div>

    <div id="experience">
      <div class="section-header">
        <span class="section-title">Expériences</span>
      </div>

      <div>
        <q-splitter
          v-model="splitterModel"
          style="height: 350px; width: 1000px"
        >
          <template v-slot:before>
            <q-tabs v-model="tab" vertical class="tab">
              <q-tab
                style="
                  text-align: start;
                  justify-content: left;
                  font-family: made_tommy, sans-serif;
                "
                name="La_fabrique"
                label="La Fabrique de com"
              ></q-tab>
              <q-tab
                style="
                  text-align: start;
                  justify-content: left;
                  font-family: made_tommy, sans-serif;
                "
                name="Cood"
                label="Cood"
              ></q-tab>
              <q-tab
                style="
                  text-align: start;
                  justify-content: left;
                  font-family: made_tommy, sans-serif;
                "
                name="WCS"
                label="Wild Code School"
              ></q-tab>
              <q-tab
                style="
                  text-align: start;
                  justify-content: left;
                  font-family: made_tommy, sans-serif;
                "
                name="Alter"
                label="Alter Ego Digital"
              ></q-tab>
              <q-tab
                style="
                  text-align: start;
                  justify-content: left;
                  font-family: made_tommy, sans-serif;
                "
                name="Krea"
                label="Krea'Lab"
              ></q-tab>
            </q-tabs>
          </template>

          <template v-slot:after>
            <q-tab-panels
              v-model="tab"
              class="job-description"
              animated
              swipeable
              vertical
              transition-prev="jump-up"
              transition-next="jump-up"
            >

            <q-tab-panel name="La_fabrique">
                <div class="title-panel text-h4 q-mb-md">
                  Alternance BAC+3 chez
                  <p style="color: #94745b; display: inline-block"><a target="_blank" href="https://www.lafabriquedecom.fr/"><u>La fabrique de com</u></a></p>
                </div>
                <ul class="job-description">
                  <div
                    class="fade-in-section is-visible text-tab"
                    style="transition-delay: 100ms"
                  >
                    <li>
                      J’ai intégré une alternance pour un BAC+3 en conception développement d'application à la <a target="_blank" href="https://www.2itechacademy.com/programmes/concepteur-developpeur-dapplications/" >
              <u>2iTech</u></a> d’Orléans.
                    </li>
                  </div>
                  <div
                    class="fade-in-section is-visible text-tab"
                    style="transition-delay: 200ms"
                  >
                    <li>
                      Au sein d'une équipe d'illustrateurs et de graphiste, j'ai été amenée à réaliser la conception
                      et le développement technique de nouvelles applications web et/ou web mobiles...<br/><br/>
                      De la conception des sites internet, de leurs fonctionnalités et de m'adapter aux différents langages
                      du site et des outils utilisés.
                    </li>
                  </div>
                  <div
                    class="fade-in-section is-visible text-tab"
                    style="transition-delay: 200ms"
                  >
                  </div>
                </ul>
              </q-tab-panel>
              <q-tab-panel name="Cood">
                <div class="title-panel text-h4 q-mb-md">
                  Alternance BTS SIO chez
                  <p style="color: #94745b; display: inline-block"><a target="_blank" href="https://cood.fr/"><u>Cood</u></a></p>
                </div>
                <ul class="job-description">
                  <div
                    class="fade-in-section is-visible text-tab"
                    style="transition-delay: 100ms"
                  >
                    <li>
                      J’ai intégré une alternance à <a target="_blank" href="https://www.formation-aftec.com/" >
              <u>L'Aftec</u></a
            > d’Orléans.
                      Actuellement en BTS SIO spécialité solutions
                      logicielles et applications métiers avec l’entreprise <a href="https://cood.fr/" target="_blank"><u>Cood</u></a>
                      du <a target="_blank" href="https://www.le-lab-o.fr//"><u>Lab'O</u></a>. Je réponds à certaines missions de la start-up
                      concernant les univers créés.
                    </li>
                  </div>
                  <div
                    class="fade-in-section is-visible text-tab"
                    style="transition-delay: 200ms"
                  >
                    <li>
                      Je fais de la création d'univers de jeux à travers des
                      assets créés par un directeur artistique, afin d'animer
                      les réseaux sociaux. (Communication hebdomadaire /
                      Design).
                    </li>
                  </div>
                  <div
                    class="fade-in-section is-visible text-tab"
                    style="transition-delay: 200ms"
                  >
                    <li>
                      Refonte du site officiel : Clarification des objectifs;
                      Cadrage du projet; Planification de l'arborescence;
                      Référentiel des exigences fontionnelles; Référencement
                      SEO; Wireframming/ Maquettes; Création de contenu
                      ; Ui
                      Design; Méthode agile.
                    </li>
                  </div>
                </ul>
              </q-tab-panel>

              <q-tab-panel name="WCS">
                <div class="title-panel text-h4 q-mb-md">
                  Etudiante à la
                  <p style="color: #94745b; display: inline-block">
                    Wild Code School
                  </p>
                </div>
                <ul class="job-description">
                  <div
                    class="fade-in-section is-visible text-tab"
                    style="transition-delay: 100ms"
                  >
                    <li>
                      Etude sur les langages de programmation HTML/CSS, Python,
                      JavaScript (React/Js, Node/Js, Express).<br />
                      Design : UX UI<br />
                      Logiciels utilisés : MySql, PhpMyAdmin, VSC Visual Studio
                      Code, Github, Gitlab.<br />
                      Méthode agile : SCRUM.
                    </li>
                  </div>
                  <div
                    class="fade-in-section is-visible text-tab"
                    style="transition-delay: 200ms"
                  >
                    <li>
                      Réalisation de trois projets, deux fictifs et un réel sous
                      un temps limité de 6 semaines.<br />
                      Mon premier projet (fictif) est un site vitrine des
                      résidents du Labo d'Orleans.<br />
                      Mon second projet est la création d'un jeu (fictif) nommé
                      <a href="https://pokemon-battle.netlify.app/"
                        ><b>Pokemon-Battle</b></a
                      >
                      <br />
                      Mon troisième projet est la création d'un site (réel)
                      nommé :
                      <a href="https://51.38.188.2/"><b>Déliv'green</b></a>
                      étant une application mettant en relation des livreurs
                      particulier et professionnels. Une application où l'on
                      peut être coursier et un simple client souhaitant faire
                      livrer son colis ! <br />
                    </li>
                  </div>
                  <div
                    class="fade-in-section is-visible text-tab"
                    style="transition-delay: 200ms"
                  >
                    <li>
                      D'autre projets on été réalisés sous forme d'hackathon,
                      des défis à relever en seulement trois jours !
                    </li>
                  </div>
                </ul>
              </q-tab-panel>

              <q-tab-panel name="Alter">
                <div class="title-panel text-h4 q-mb-md">
                  Stage d'apprentissage chez
                  <p style="color: #94745b; display: inline-block">
                    Alter Ego Digital
                  </p>
                </div>
                <ul class="job-description">
                  <div
                    class="fade-in-section is-visible text-tab"
                    style="transition-delay: 100ms"
                  >
                    <li>
                      Développeur web front-end d'une durée de six semaines.<br />
                      Start-up permettant d'aider les autres entreprises à
                      réduire leur taux d'absentéisme, à réduire les douleurs
                      physiques des salariés à travers une plateforme proposant
                      des exercices physiques... <br />
                      Refonte d'une fonctionnalité.
                    </li>
                  </div>
                </ul>
              </q-tab-panel>

              <q-tab-panel name="Krea">
                <div class="title-panel text-h4 q-mb-md">
                  Stage d'apprentissage chez
                  <p style="color: #94745b; display: inline-block">Krea'Lab</p>
                </div>
                <ul class="job-description">
                  <div
                    class="fade-in-section is-visible text-tab"
                    style="transition-delay: 100ms"
                  >
                    <li>
                      Stage dans la start-up de Krea'lab de quatre semaines.<br />
                      Participation à trois projets (front-end) "Labo-Lamé"
                      "Primmo" "logigramme primmo".
                    </li>
                  </div>
                </ul>
              </q-tab-panel>
            </q-tab-panels>
          </template>
        </q-splitter>
      </div>
    </div>

    <div id="projects">
      <div class="section-header">
        <span class="section-title">Créations</span>
      </div>
      <div class="project-container">
        <ul class="projects-grid">
          <div
            class="fade-in-section is-visible"
            style="transition-delay: 100ms"
          >
            <li class="projects-card">
              <div class="card-header">
                <div class="folder-icon">
                  <svg
                    class="MuiSvgIcon-root"
                    focusable="false"
                    viewBox="0 0 24 24"
                    aria-hidden="true"
                    style="font-size: 35px"
                  >
                    <path
                      d="M20 6h-8l-1.41-1.41C10.21 4.21 9.7 4 9.17 4H4c-1.1 0-1.99.9-1.99 2L2 18c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V8c0-1.1-.9-2-2-2zm-1 12H5c-.55 0-1-.45-1-1V9c0-.55.45-1 1-1h14c.55 0 1 .45 1 1v8c0 .55-.45 1-1 1z"
                    ></path>
                  </svg>
                </div>
                <span class="external-links">
                  <svg
                    class="MuiSvgIcon-root"
                    @click="carousel = true"
                    focusable="false"
                    viewBox="0 0 24 24"
                    aria-hidden="true"
                    style="font-size: 25px; color: var(--lightest-slate)"
                  >
                    <path
                      d="M19 4H5c-1.11 0-2 .9-2 2v12c0 1.1.89 2 2 2h4v-2H5V8h14v10h-4v2h4c1.1 0 2-.9 2-2V6c0-1.1-.89-2-2-2zm-7 6l-4 4h3v6h2v-6h3l-4-4z"
                    ></path>
                  </svg>
                  <q-dialog v-model="carousel">
                    <q-carousel
                      transition-prev="slide-right"
                      transition-next="slide-left"
                      swipeable
                      animated
                      v-model="slide"
                      control-color="primary"
                      navigation
                      padding
                      height="500px"
                      max-width="100%"
                      class="bg-white shadow-1 rounded-borders"
                    >
                      <q-carousel-slide
                        :name="1"
                        class="column no-wrap flex-center"
                      >
                        <img
                          src="../assets/extra-terrestre-int.png"
                          alt="extra-terrestre-int"
                          style="width: 100%; height: 100%"
                        />
                      </q-carousel-slide>
                      <q-carousel-slide
                        :name="2"
                        class="column no-wrap flex-center"
                      >
                        <img
                          src="../assets/Forêt-ext.png"
                          alt="Forêt-ext"
                          style="width: 100%; height: 100%"
                        />
                      </q-carousel-slide>
                      <q-carousel-slide
                        :name="3"
                        class="column no-wrap flex-center"
                      >
                        <img
                          src="../assets/Foret-int.png"
                          alt="Foret-int"
                          style="width: 100%; height: 100%"
                        />
                      </q-carousel-slide>
                      <q-carousel-slide
                        :name="4"
                        class="column no-wrap flex-center"
                      >
                        <img
                          src="../assets/monde-merveilleur-exterieure.png"
                          alt="monde-merveilleur-exterieure"
                          style="width: 100%; height: 100%"
                        />
                      </q-carousel-slide>
                      <q-carousel-slide
                        :name="5"
                        class="column no-wrap flex-center"
                      >
                        <img
                          src="../assets/monde-merveilleurx-int.png"
                          alt="monde-merveilleur-int"
                          style="width: 100%; height: 100%"
                        />
                      </q-carousel-slide>
                      <q-carousel-slide
                        :name="6"
                        class="column no-wrap flex-center"
                      >
                        <img
                          src="../assets/monde-montagne-int.png"
                          alt="monde-montagne-int"
                          style="width: 100%; height: 100%"
                        />
                      </q-carousel-slide>
                      <q-carousel-slide
                        :name="7"
                        class="column no-wrap flex-center"
                      >
                        <img
                          src="../assets/montagne-ext.png"
                          alt="montagne-ext"
                          style="width: 100%; height: 100%"
                        />
                      </q-carousel-slide>
                      <q-carousel-slide
                        :name="8"
                        class="column no-wrap flex-center"
                      >
                        <img
                          src="../assets/extra-terrestre-ext.png"
                          alt="extra-terrestre-ext"
                          style="width: 100%; height: 100%"
                        />
                      </q-carousel-slide>
                      <q-carousel-slide
                        :name="9"
                        class="column no-wrap flex-center"
                      >
                        <img
                          src="../assets/ville-ext.png"
                          alt="ville-ext"
                          style="width: 100%; height: 100%"
                        />
                      </q-carousel-slide>
                      <q-carousel-slide
                        :name="10"
                        class="column no-wrap flex-center"
                      >
                        <img
                          src="../assets/Ville-int.png"
                          alt="Ville-int"
                          style="width: 100%; height: 100%"
                        />
                      </q-carousel-slide>
                    </q-carousel>
                  </q-dialog>
                </span>
              </div>
              <div class="card-title">Communication hebdomadaire</div>
              <div class="card-desc">
                Création d'illustrations de jeux pour les publier sur Instagram
                et Twitter afin de faire connaître nos différents univers de
                jeux/packs de jeux.
              </div>
              <div class="card-tech">Design / Graphique</div>
            </li>
          </div>

          <div
            class="fade-in-section is-visible"
            style="transition-delay: 200ms"
          >
            <li class="projects-card">
              <div class="card-header">
                <div class="folder-icon">
                  <svg
                    class="MuiSvgIcon-root"
                    focusable="false"
                    viewBox="0 0 24 24"
                    aria-hidden="true"
                    style="font-size: 35px"
                  >
                    <path
                      d="M20 6h-8l-1.41-1.41C10.21 4.21 9.7 4 9.17 4H4c-1.1 0-1.99.9-1.99 2L2 18c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V8c0-1.1-.9-2-2-2zm-1 12H5c-.55 0-1-.45-1-1V9c0-.55.45-1 1-1h14c.55 0 1 .45 1 1v8c0 .55-.45 1-1 1z"
                    ></path>
                  </svg>
                </div>
                <span class="external-links">
                  <a class="open-icon" href="https://cood.fr/">
                    <svg
                      class="MuiSvgIcon-root"
                      focusable="false"
                      viewBox="0 0 24 24"
                      aria-hidden="true"
                      style="font-size: 25px; color: var(--lightest-slate)"
                    >
                      <path
                        d="M19 4H5c-1.11 0-2 .9-2 2v12c0 1.1.89 2 2 2h4v-2H5V8h14v10h-4v2h4c1.1 0 2-.9 2-2V6c0-1.1-.89-2-2-2zm-7 6l-4 4h3v6h2v-6h3l-4-4z"
                      ></path>
                    </svg>
                  </a>
                </span>
              </div>
              <div class="card-title">Refonte du site Cood</div>
              <div class="card-desc">
                Refonte du site officiel : Clarification des objectifs; Cadrage
                du projet; Planification de l'arborescence; Référentiel des
                exigences fontionnelles; Référencement SEO; Wireframming/
                Maquettes; Création de contenu; Ui Design; Méthode agile.
              </div>
              <div class="card-tech">CMS (Wordpress), HTML/CSS, Design</div>
            </li>
          </div>

          <div
            class="fade-in-section is-visible"
            style="transition-delay: 300ms"
          >
            <li class="projects-card">
              <div class="card-header">
                <div class="folder-icon">
                  <svg
                    class="MuiSvgIcon-root"
                    focusable="false"
                    viewBox="0 0 24 24"
                    aria-hidden="true"
                    style="font-size: 35px"
                  >
                    <path
                      d="M20 6h-8l-1.41-1.41C10.21 4.21 9.7 4 9.17 4H4c-1.1 0-1.99.9-1.99 2L2 18c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V8c0-1.1-.9-2-2-2zm-1 12H5c-.55 0-1-.45-1-1V9c0-.55.45-1 1-1h14c.55 0 1 .45 1 1v8c0 .55-.45 1-1 1z"
                    ></path>
                  </svg>
                </div>
                <span class="external-links">
                  <a class="github-icon" href="">
                    <svg
                      class="MuiSvgIcon-root"
                      focusable="false"
                      viewBox="0 0 24 24"
                      aria-hidden="true"
                      style="font-size: 20px; color: var(--lightest-slate)"
                    >
                      <path
                        d="M12 .3a12 12 0 0 0-3.8 23.4c.6.1.8-.3.8-.6v-2c-3.3.7-4-1.6-4-1.6-.6-1.4-1.4-1.8-1.4-1.8-1-.7.1-.7.1-.7 1.2 0 1.9 1.2 1.9 1.2 1 1.8 2.8 1.3 3.5 1 0-.8.4-1.3.7-1.6-2.7-.3-5.5-1.3-5.5-6 0-1.2.5-2.3 1.3-3.1-.2-.4-.6-1.6 0-3.2 0 0 1-.3 3.4 1.2a11.5 11.5 0 0 1 6 0c2.3-1.5 3.3-1.2 3.3-1.2.6 1.6.2 2.8 0 3.2.9.8 1.3 1.9 1.3 3.2 0 4.6-2.8 5.6-5.5 5.9.5.4.9 1 .9 2.2v3.3c0 .3.1.7.8.6A12 12 0 0 0 12 .3"
                      ></path>
                    </svg>
                  </a>
                  <a
                    class="open-icon"
                    href="./blockly/index.html"
                  >
                    <svg
                      class="MuiSvgIcon-root"
                      focusable="false"
                      viewBox="0 0 24 24"
                      aria-hidden="true"
                      style="font-size: 25px; color: var(--lightest-slate)"
                    >
                      <path
                        d="M19 4H5c-1.11 0-2 .9-2 2v12c0 1.1.89 2 2 2h4v-2H5V8h14v10h-4v2h4c1.1 0 2-.9 2-2V6c0-1.1-.89-2-2-2zm-7 6l-4 4h3v6h2v-6h3l-4-4z"
                      ></path>
                    </svg>
                  </a>
                </span>
              </div>
              <div class="card-title">Projet Blockly</div>
              <div class="card-desc">
                Création d'une documentation intéractive nommée "Blockly", en
                s'inspirant de Three.js et en respectant la charte graphique.
              </div>
              <div class="card-tech">JavaScript, Vue.js, Quasar, Design</div>
            </li>
          </div>

          <div
            class="fade-in-section is-visible"
            style="transition-delay: 400ms"
          >
            <li class="projects-card">
              <div class="card-header">
                <div class="folder-icon">
                  <svg
                    class="MuiSvgIcon-root"
                    focusable="false"
                    viewBox="0 0 24 24"
                    aria-hidden="true"
                    style="font-size: 35px"
                  >
                    <path
                      d="M20 6h-8l-1.41-1.41C10.21 4.21 9.7 4 9.17 4H4c-1.1 0-1.99.9-1.99 2L2 18c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V8c0-1.1-.9-2-2-2zm-1 12H5c-.55 0-1-.45-1-1V9c0-.55.45-1 1-1h14c.55 0 1 .45 1 1v8c0 .55-.45 1-1 1z"
                    ></path>
                  </svg>
                </div>
                <span class="external-links">
                  <a class="open-icon" href="https://51.38.188.2/">
                    <svg
                      class="MuiSvgIcon-root"
                      focusable="false"
                      viewBox="0 0 24 24"
                      aria-hidden="true"
                      style="font-size: 25px; color: var(--lightest-slate)"
                    >
                      <path
                        d="M19 4H5c-1.11 0-2 .9-2 2v12c0 1.1.89 2 2 2h4v-2H5V8h14v10h-4v2h4c1.1 0 2-.9 2-2V6c0-1.1-.89-2-2-2zm-7 6l-4 4h3v6h2v-6h3l-4-4z"
                      ></path>
                    </svg>
                  </a>
                </span>
              </div>
              <div class="card-title">Projet Déliv'green</div>
              <div class="card-desc">
                Application mettant en relation des livreurs particuliers et
                professionnels. Une application où l'on peut être coursier et un
                simple client souhaitant faire livrer son colis !
              </div>
              <div class="card-tech">
                JavaScript, React.js, Bootstrap, PhpMyAdmin, Sql
              </div>
            </li>
          </div>

          <div
            class="fade-in-section is-visible"
            style="transition-delay: 500ms"
          >
            <li class="projects-card">
              <div class="card-header">
                <div class="folder-icon">
                  <svg
                    class="MuiSvgIcon-root"
                    focusable="false"
                    viewBox="0 0 24 24"
                    aria-hidden="true"
                    style="font-size: 35px"
                  >
                    <path
                      d="M20 6h-8l-1.41-1.41C10.21 4.21 9.7 4 9.17 4H4c-1.1 0-1.99.9-1.99 2L2 18c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V8c0-1.1-.9-2-2-2zm-1 12H5c-.55 0-1-.45-1-1V9c0-.55.45-1 1-1h14c.55 0 1 .45 1 1v8c0 .55-.45 1-1 1z"
                    ></path>
                  </svg>
                </div>
                <span class="external-links">
                  <a class="open-icon" href="https://51.38.188.2/">
                    <svg
                      class="MuiSvgIcon-root"
                      focusable="false"
                      viewBox="0 0 24 24"
                      aria-hidden="true"
                      style="font-size: 25px; color: var(--lightest-slate)"
                    >
                      <path
                        d="M19 4H5c-1.11 0-2 .9-2 2v12c0 1.1.89 2 2 2h4v-2H5V8h14v10h-4v2h4c1.1 0 2-.9 2-2V6c0-1.1-.89-2-2-2zm-7 6l-4 4h3v6h2v-6h3l-4-4z"
                      ></path>
                    </svg>
                  </a>
                </span>
              </div>
              <div class="card-title">Projet PokéBattle</div>
              <div class="card-desc">
                Petit jeu de combat dans le thème "Pokemon". Le jeu met en scène
                un combat avec un personnage choisi aléatoirement.
              </div>
              <div class="card-tech">JavaScript, React.js, PhpMyAdmin, Sql</div>
            </li>
          </div>

          <div
            class="fade-in-section is-visible"
            style="transition-delay: 600ms"
          >
            <li class="projects-card">
              <div class="card-header">
                <div class="folder-icon">
                  <svg
                    class="MuiSvgIcon-root"
                    focusable="false"
                    viewBox="0 0 24 24"
                    aria-hidden="true"
                    style="font-size: 35px"
                  >
                    <path
                      d="M20 6h-8l-1.41-1.41C10.21 4.21 9.7 4 9.17 4H4c-1.1 0-1.99.9-1.99 2L2 18c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V8c0-1.1-.9-2-2-2zm-1 12H5c-.55 0-1-.45-1-1V9c0-.55.45-1 1-1h14c.55 0 1 .45 1 1v8c0 .55-.45 1-1 1z"
                    ></path>
                  </svg>
                </div>
              </div>
              <div class="card-title">Mini Jeux</div>
              <div class="card-desc">
                Plusieurs mini jeux en mode "brouillon" sous php.
              </div>
              <div class="card-tech">A venir</div>
            </li>
          </div>
        </ul>
      </div>
    </div>

    <div class="footer">
        <p> N'hésitez pas à visiter la version mobile (petite interface à la Microsoft) !</p>

      <div>Construit et réalisé par Sibel Koç</div>
      <div>Tous droits réservés ©</div>
    </div>
  </div>
</template>

<script>
import { onMounted, onUnmounted } from "vue";
import { ref } from "vue";


export default {
  name: "Web-page",
  props: {},
  setup() {
    onMounted(() => {
      document.addEventListener("scroll", animateIfInView);
    });
    onUnmounted(() => {
      document.removeEventListener("scroll", animateIfInView);
    });
    function animateIfInView() {
      console.log("je rentre");
      var monTableau = document.getElementsByClassName("fade-in-section");
      for (let i = 0; i < monTableau.length; i++) {
        const element = monTableau[i];
        if (isElementInViewport(element)) {
          element.classList.add("is-visible");
        } else {
          // (Optional) Fade out when out of view
          element.classList.remove("is-visible");
        }
      }

      function isElementInViewport(el) {
        var rect = el.getBoundingClientRect();

        return (
          rect.top >= 0 &&
          rect.left >= 0 &&
          rect.bottom <=
            (window.innerHeight ||
              document.documentElement
                .clientHeight) /*or $(window).height() */ &&
          rect.right <=
            (window.innerWidth ||
              document.documentElement.clientWidth) /*or $(window).width() */
        );
      }
    }
    return {
      tab: ref("La_fabrique"),
      splitterModel: ref(20),
      carousel: ref(false),
      slide: ref(1),
    };
  },

};
</script>

<style scoped>
.content {
  width: 100%;
  overflow-x: hidden;
  overflow-y: hidden;
}

/* home--------------------- */
#home {
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  padding-left: 10%;
  padding-top: 13%;
  min-height: 100vh;
}

.wrapper {
  text-align: center;
  font-size: 36px;
  display: flex;
  align-items: flex-end;
}

.content-sibelkreation {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: "made_tommy", sans-serif;
  font-size: calc(30px + 4vw);
  color: #94745b;
  text-shadow: 0 0 2px;
  align-items: flex-end;
  font-weight: 300;
  display: flex;
}

.content-sibelkreation .ok {
  position: absolute;
}

.content-sibelkreation .ok:nth-child(1) {
  color: transparent;
  -webkit-text-stroke: 2px #94745b;
}

.content-sibelkreation .ok:nth-child(2) {
  color: #94745b;
  animation: animate 4s ease-in-out infinite;
}

.text-home {
  font-family: "made_tommy";
  color: var(--slate);
  max-width: 50%;
  font-size: 18px;
  text-align: justify;
  margin: 0;
  width: 80%;
  padding-bottom: 20px;
  margin-top: 20px;
  font-weight: 500;
}

.intro-contact {
  font-weight: bolder;
  padding: 10px 30px;
  cursor: pointer;
  border: 1px solid #94745b;
  border-radius: 4px;
  text-decoration-color: #94745b;
  font-size: 15px;
  align-content: center;
  justify-content: center;
}

/* about---------------------------- */

#about {
  padding-left: 10%;
  padding-right: 25%;
  min-height: 80vh;
}
.fade-in-section {
  opacity: 0;
  -webkit-transform: translate(0, 50px);
  -moz-transform: translate(0, 50px);
  -ms-transform: translate(0, 50px);
  transform: translate(0, 50px);
  -webkit-transition: opacity 0.6s 0.1s, transform 0.6s ease;
  transition: opacity 0.6s 0.1s, transform 0.6s ease;
  transition-delay: 0ms;
}

.fade-in-section.is-visible {
  opacity: 1 !important;
  -webkit-transform: translate(0, 0) !important;
  -moz-transform: translate(0, 0) !important;
  -ms-transform: translate(0, 0) !important;
  transform: translate(0, 0) !important;
}

.section-header {
  display: flex;
  padding-bottom: 42px;
  width: 100vw;
}
.section-header:after {
  content: "";
  display: block;
  width: 300px;
  margin-top: 39px;
  height: 1px;
  margin-left: 20px;
  background-color: #d4af92;
}
.section-title {
  font-family: "made_tommy";
  color: #d4af92;
  font-size: 46px;
  font-weight: 700;
}
.about-content {
  display: flex;
  flex-direction: row;
}
.about-description {
  font-family: "made_tommy";

  color: var(--slate);
  max-width: 600px;
  font-size: 18px;
  text-align: justify;
  margin: 0;
}
p {
  margin-top: 0;
  margin-bottom: 1rem;
}

.about-description ul {
  padding-top: 18px;
  list-style-type: none;
  display: grid;
  grid-template-columns: repeat(2, minmax(300px, 20px));
}

ul {
  list-style: none;
  margin-left: -40px;
}

.about-description li {
  position: relative;
  padding-left: 20px;
  font-size: 18px;
  color: var(--slate);
}
.about-description li:before {
  content: "▹ ";
  color: var(--green-bright);
  position: absolute;
  left: 0;
}
.about-image {
  padding-left: 40px;
}
.about-image img {
  max-width: 300px;
  height: auto;
  border-radius: 10px;
  margin-left: 30px;
  box-shadow: 6px 13px 23px -5px rgb(0 0 0 / 46%);
  border: none;
}
/* Experiences---------------------------- */

#experience {
  padding-left: 10%;
  padding-right: 25%;
  min-height: 80vh;
  padding-top: 10%;
}
.q-tab-panel {
  background-color: transparent !important;
  overflow: hidden;
}
.text-tab {
  text-align: start;
}
.job-description {
  max-width: 900px;
  font-family: "made_tommy", sans-serif;
  font-size: 20px;
  background-color: transparent;
}
.job-description li {
  position: relative;
  padding-left: 30px;
  padding-bottom: 16px;
  font-size: 15px;
  text-align: justify;
}
.job-description li:before {
  content: "▹ ";
  position: absolute;
  left: 0;
}
ul {
  list-style: none;
  margin-left: -40px;
}
.title-panel {
  font-family: "made_tommy";
  color: #d4af92;
  font-weight: 700;
  text-align: start;
  justify-content: left;
}

/* Créations---------------------------- */

#projects {
  padding-left: 10%;
  padding-right: 25%;
  min-height: 80vh;
  padding-top: 10%;
}
.projects-grid {
  display: grid;
  grid-template-columns: repeat(3, minmax(300px, 1fr));
  grid-gap: 10px;
}
.projects-card {
  cursor: default;
  display: flex;
  flex-direction: column;
  position: relative;
  height: 100%;
  padding: 2rem 1.75rem;
  background-color: #d4c4b794;
  border-radius: 16px;
}
.card-header:first-child {
  border-radius: calc(0.25rem - 1px) calc(0.25rem - 1px) 0 0;
}
.card-header {
  margin-top: -20px;
  display: flex;
  padding: 1.25em 0 !important;
  flex-direction: row;
  justify-content: space-between;
  border-bottom: none !important;
}
.card-title {
  font-family: "made_tommy";
  color: #d4af92;
  font-size: 24px;
  font-weight: 700;
  margin-bottom: 20px;
}
.folder-icon {
  color: #d4af92;
}
.github-icon {
  margin-top: 6px;
}
.open-icon {
  margin-left: 10px;
}
.card-desc {
  font-family: "made_tommy";
  font-size: 15px;
  font-weight: 300;
}
.card-tech {
  font-size: 14px;
  font-family: "made_tommy";
  font-weight: 300;
  margin-top: 20px;
  color: #d4af92;
}

/* menu--------------------- */
.sidebar-nav {
  display: flex;
  flex-direction: column;
  align-items: flex-end;
  position: fixed;
  right: 0;
  padding-right: 5%;
  bottom: 10%;
  background-color: transparent;
}

.sidebar-links {
  display: flex;
  flex-direction: column;
  text-align: right;
  font-family: "made_tommy";

  letter-spacing: 0em;
  line-height: 1.6em;
  font-size: 16px;
  padding: 0.2em;
  font-weight: bold;
}

a {
  text-decoration: none !important;
  color: var(--green-bright) !important;
}

a:hover {
  color: var(--lightest-slate) !important;
}

.sidebar-logos {
  padding-top: 42px;
  width: 70px;
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  padding-bottom: 8px;
}

.MuiSvgIcon-root {
  fill: currentColor;
  width: 1em;
  height: 1em;
  display: inline-block;
  font-size: 1.5rem;
  transition: fill 200ms cubic-bezier(0.4, 0, 0.2, 1) 0ms;
  flex-shrink: 0;
  user-select: none;
  cursor: pointer;
}

.q-carousel {
  max-width: 100%;
}
.footer {
  font-family: "made_tommy";
  color: var(--slate);
  text-align: center;
  width: 100%;
  font-size: 16px;
  padding-bottom: 40px;

  align-items: center;
  padding-top: 50px;
}

@keyframes animate {
  0%,
  100% {
    clip-path: polygon(
      0% 45%,
      16% 44%,
      33% 50%,
      54% 60%,
      70% 61%,
      84% 59%,
      100% 52%,
      100% 100%,
      0% 100%
    );
  }

  50% {
    clip-path: polygon(
      0% 60%,
      15% 65%,
      34% 66%,
      51% 62%,
      67% 50%,
      84% 45%,
      100% 46%,
      100% 100%,
      0% 100%
    );
  }
}
</style>

<style lang="scss">
html {
  scroll-behavior: smooth;
}

body {
  margin: 0;
  scroll-behavior: smooth;
}
</style>
