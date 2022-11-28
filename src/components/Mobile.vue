<template>
  <div class="all">
    <img class="Me" src="../assets/Sibel.png" />

    <div class="container">
      <div class="wrapper">
        <div class="typing">Bienvenue sur mon portfolio.</div>
      </div>
      <div class="title">SibelKreation ☕</div>
    </div>

    <div class="square">
      <div class="inline-all">
        <div class="first-box">
          <div class="medContainer">
            <div class="flip-box-inner-medContainer">
              <div class="flip-box-front-medContainer">
                <img
                  src="../assets/aboutMe.png"
                  alt="aboutMe"
                  style="max-width: 100%"
                />
              </div>
              <div class="flip-box-back-medContainer">
                <div class="title-card">A propos</div>
                <div class="q-pa-md q-gutter-sm">
                  <q-btn
                    push
                    label="Voir"
                    style="color: #fff"
                    @click="small = true"
                  />
                  <q-dialog v-model="small">
                    <q-card style="width: 300px">
                      <q-card-section>
                        <div class="text-h6">
                          Je m'appelle Sibel koç d'où le nom SibelKreation !
                        </div>
                      </q-card-section>

                      <q-card-section class="q-pt-none">
                        <div class="text">
                          J'ai 22 ans, je suis passionnée par le web, les métiers du digital et
                          surtout par l'UI design et le web design !<br /><br />
                          Acceptée à L'ISCOD, je souhaiterais continuer
                          avec une troisième année d'alternance dans le but
                          d'obtenir un BAC+3 en WebDesign.<br /><br />
                          Après avoir obtenu des connaissances dans le développement web,
                          je souhaiterai pour cette troisième année apprendre différentes technologies et méthodes abordées tels que la culture graphique, 
                      les chartes graphiques, la gestion de projet,  les suites adobes (Photoshop; Illustrator; InDesign; Adobe XD; Premiere et After Effect),
            l'UX &amp; l'UI design; le web marketing ainsi que les CMS tels que Wordpress...<br/>
            Cela, me permettra d'acquérir différentes connaissances afin de répondre à tous les besoins graphiques et design !<br /><br />
                        </div>
                      </q-card-section>

                      <q-card-actions align="right" class="bg-white text-teal">
                        <q-btn flat label="OK" v-close-popup />
                      </q-card-actions>
                    </q-card>
                  </q-dialog>
                </div>
              </div>
            </div>
          </div>
        </div>

        <div class="second-box">
          <div class="lilContainer">
            <div class="flip-box-inner-lilContainer">
              <div class="flip-box-front-lilContainer">
                <img
                  src="../assets/mail.png"
                  alt="logoMail"
                  style="max-width: 100%"
                />
              </div>
              <div class="flip-box-back-lilContainer">
                <q-btn
                  type="a"
                  href="mailto:sibel.koc.pro@outlook.fr"
                  label="Envoyer un email"
                  style="
                    font-size: 10px;
                    width: 90%;
                    margin: 5px;
                    align-content: center;
                    justify-content: center;
                    padding: 15px;
                    max-height: 80%;
                    top: 5%;
                  "
                />
              </div>
            </div>
          </div>

          <div class="lilContainerX">
            <div class="flip-box-inner-lilContainerX">
              <div class="flip-box-front-lilContainerX">
                <img
                  src="../assets/discord.png"
                  alt="logoDiscord"
                  style="max-width: 100%"
                />
              </div>

              <div class="flip-box-back-lilContainerX">
                <q-btn
                  label="Discord"
                  style="
                    font-size: 10px;
                    width: 90%;
                    margin: 5px;
                    align-content: center;
                    justify-content: center;
                    padding: 15px;
                    max-height: 80%;
                    top: 5%;
                  "
                  @click="open('right')"
                />

                <q-dialog v-model="dialog" :position="position">
                  <q-card style="width: 200px">
                    <q-card-section class="row items-center no-wrap">
                      <div>
                        <div
                          style="
                            font-size: 1.5em;
                            font-family: 'made_tommy', sans-serif;
                            color: #94745b;
                          "
                          class="text-weight-bold"
                        >
                          𝕾𝖚ʞ𝖚𝖓𝖆#5979
                        </div>
                        <div class="text-grey">Discord</div>
                      </div>
                    </q-card-section>
                  </q-card>
                </q-dialog>
              </div>
            </div>
          </div>

          <div class="lilContainerX">
            <div class="flip-box-inner-lilContainerX">
              <div class="flip-box-front-lilContainerX">
                <img
                  src="../assets/linkedin.png"
                  alt="logoLinkedin"
                  style="max-width: 100%"
                />
              </div>

              <div class="flip-box-back-lilContainerX">
                <q-btn
                  label="Linkedin"
                  @click="card = true"
                  style="
                    font-size: 10px;
                    width: 90%;
                    margin: 5px;
                    align-content: center;
                    justify-content: center;
                    padding: 15px;
                    max-height: 80%;
                    top: 5%;
                  "
                />

                <q-dialog v-model="card">
                  <q-card style="min-width: 80%" class="my-card">
                    <q-img
                      src="../assets/linke.png"
                      style="
                        width: 100%;
                        align-content: center;
                        justify-content: center;
                        border-radius: 10px;
                      "
                    />
                    <q-card-section>
                      <div style="font-size: 1.5em" class="col">
                        Recherche alternance BAC +3<br />
                        WebDesigner / Développeur web <br />
                      </div>
                    </q-card-section>

                    <q-card-section class="q-pt-none">
                      <div style="font-size: 1.4em" class="text-grey">
                        Sujets de prédilection :<br />
                        #développementweb #Design et #alternance<br />
                        Orléans, Centre-Val de Loire, France<br />
                      </div>
                    </q-card-section>

                    <q-separator />

                    <q-card-actions align="right">
                      <q-btn
                        push
                        label="Coordonnées"
                        style="background-color: #d2d0fc; color: white"
                        @click="alert = true"
                      />
                      <q-dialog v-model="alert">
                        <q-card style="min-width: 70%">
                          <q-card-section>
                            <div style="font-size: 2em" class="text-h6">
                              Coordonnées
                            </div>
                          </q-card-section>

                          <q-card-section class="q-mb-md">
                            <div
                              style="
                                font-size: 1.5em;
                                margin-bottom: 10px;
                                font-family: 'made_tommy', sans-serif;
                                color: #777;
                              "
                              class="text-subtitle1"
                            >
                              Mon profil<br />
                            </div>

                            <div
                              style="font-size: 1.4em"
                              class="text-caption text-brown-4"
                            >
                              <a href="https://www.linkedin.com/in/sibel-koc"
                                ><b>linkedin.com/in/sibel-koc</b></a
                              ><br />
                            </div>
                          </q-card-section>

                          <q-separator />

                          <q-card-section class="q-my-md">
                            <div
                              style="
                                font-size: 1.5em;
                                margin-bottom: 10px;
                                font-family: 'made_tommy', sans-serif;
                                color: #777;
                              "
                              class="text-subtitle1"
                            >
                              E-mail<br />
                            </div>

                            <div
                              style="font-size: 1.4em"
                              class="text-caption text-brown-4"
                            >
                              <a href="mailto:sibel.koc.pro@outlook.fr"
                                ><b>sibel.koc.pro@outlook.fr</b></a
                              ><br />
                            </div>
                          </q-card-section>

                          <q-separator />

                          <q-card-section class="q-mt-md">
                            <div
                              style="
                                font-size: 1.5em;
                                margin-bottom: 10px;
                                font-family: 'made_tommy', sans-serif;
                                color: #777;
                              "
                              class="text-subtitle1"
                            >
                              Anniversaire<br />
                            </div>

                            <div
                              style="
                                font-size: 1.4em;
                                font-family: 'made_tommy', sans-serif;
                              "
                              class="text-gray"
                            >
                              <b>22 Octobre</b>
                            </div>
                          </q-card-section>

                          <q-card-actions align="right">
                            <q-btn
                              flat
                              label="OK"
                              color="primary"
                              v-close-popup
                            />
                          </q-card-actions>
                        </q-card>
                      </q-dialog>
                    </q-card-actions>
                  </q-card>
                </q-dialog>
              </div>
            </div>
          </div>

          <div class="lilContainer">
            <div class="flip-box-inner-lilContainer">
              <div class="flip-box-front-lilContainer">
                <img
                  src="../assets/github.png"
                  alt="logoGithub"
                  style="max-width: 100%"
                />
              </div>

              <div class="flip-box-back-lilContainer">
                <q-btn
                  label="Github"
                  style="
                    font-size: 10px;
                    width: 90%;
                    margin: 5px;
                    align-content: center;
                    justify-content: center;
                    padding: 15px;
                    max-height: 80%;
                    top: 5%;
                  "
                  @click="open1('right')"
                />

                <q-dialog v-model="dialog1" :position="position1">
                  <q-card style="width: 200px">
                    <q-card-section class="row items-center no-wrap">
                      <div>
                        <div
                          style="
                            font-size: 1.5em;
                            font-family: 'made_tommy', sans-serif;
                            color: #94745b;
                          "
                          class="text-weight-bold"
                        >
                          /sibelkoc
                        </div>
                        <div class="text-grey">Github</div>
                      </div>
                    </q-card-section>
                  </q-card>
                </q-dialog>
              </div>
            </div>
          </div>
        </div>
      </div>

      <div class="reverse-all">
        <div class="first-box-reverse">
          <div class="medContainer">
            <div class="flip-box-inner-medContainer">
              <div class="flip-box-front-medContainer">
                <img
                  src="../assets/creation.png"
                  alt="creation"
                  style="max-width: 100%"
                />
              </div>

              <div class="flip-box-back-medContainer">
                <div class="title-card">Mes créations</div>
                <div class="q-pa-md q-gutter-sm">
                  <q-btn
                    push
                    label="Voir"
                    style="color: white"
                    @click="dialogMaxToggle = true"
                  />

                  <q-dialog
                    v-model="dialogMaxToggle"
                    persistent
                    :maximized="maximizedToggle"
                    transition-show="slide-up"
                    transition-hide="slide-down"
                  >
                    <q-card
                      style="background-color: #d4c4b7"
                      class="text-white"
                    >
                      <q-bar>
                        <q-space />

                        <q-btn dense flat icon="close" v-close-popup>
                          <q-tooltip class="bg-white text-primary"
                            >Close</q-tooltip
                          >
                        </q-btn>
                      </q-bar>

                      <q-card
                        style="
                          color: #918f73;
                          margin: 20px;
                          border-radius: 20px;
                          top: 10;
                        "
                        class="my-card"
                      >
                        <q-card-section>
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
                            <div class="text-h6">Design</div>
                            <br />
                          </div>
                          <div class="text-subtitle2">
                            Communication hebdomadaire
                          </div>
                          <div class="text-grey">
                            Création de petit jeux pour les publier sur
                            Instagram et Twitter afin de faire connaître nos
                            différents univers de jeux.
                          </div>
                        </q-card-section>

                        <q-separator />

                        <q-card-actions style="justify-content: end">
                          <span class="external-links">
                            <svg
                              class="MuiSvgIcon-root"
                              @click="carousel = true"
                              focusable="false"
                              viewBox="0 0 24 24"
                              aria-hidden="true"
                              style="
                                font-size: 25px;
                                color: var(--lightest-slate);
                              "
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
                                    style="width: 100%; height: 50%"
                                  />
                                </q-carousel-slide>
                                <q-carousel-slide
                                  :name="2"
                                  class="column no-wrap flex-center"
                                >
                                  <img
                                    src="../assets/Forêt-ext.png"
                                    alt="Forêt-ext"
                                    style="width: 100%; height: 50%"
                                  />
                                </q-carousel-slide>
                                <q-carousel-slide
                                  :name="3"
                                  class="column no-wrap flex-center"
                                >
                                  <img
                                    src="../assets/Foret-int.png"
                                    alt="Foret-int"
                                    style="width: 100%; height: 50%"
                                  />
                                </q-carousel-slide>
                                <q-carousel-slide
                                  :name="4"
                                  class="column no-wrap flex-center"
                                >
                                  <img
                                    src="../assets/monde-merveilleur-exterieure.png"
                                    alt="monde-merveilleur-exterieure"
                                    style="width: 100%; height: 50%"
                                  />
                                </q-carousel-slide>
                                <q-carousel-slide
                                  :name="5"
                                  class="column no-wrap flex-center"
                                >
                                  <img
                                    src="../assets/monde-merveilleurx-int.png"
                                    alt="monde-merveilleur-int"
                                    style="width: 100%; height: 50%"
                                  />
                                </q-carousel-slide>
                                <q-carousel-slide
                                  :name="6"
                                  class="column no-wrap flex-center"
                                >
                                  <img
                                    src="../assets/monde-montagne-int.png"
                                    alt="monde-montagne-int"
                                    style="width: 100%; height: 50%"
                                  />
                                </q-carousel-slide>
                                <q-carousel-slide
                                  :name="7"
                                  class="column no-wrap flex-center"
                                >
                                  <img
                                    src="../assets/montagne-ext.png"
                                    alt="montagne-ext"
                                    style="width: 100%; height: 50%"
                                  />
                                </q-carousel-slide>
                                <q-carousel-slide
                                  :name="8"
                                  class="column no-wrap flex-center"
                                >
                                  <img
                                    src="../assets/extra-terrestre-ext.png"
                                    alt="extra-terrestre-ext"
                                    style="width: 100%; height: 50%"
                                  />
                                </q-carousel-slide>
                                <q-carousel-slide
                                  :name="9"
                                  class="column no-wrap flex-center"
                                >
                                  <img
                                    src="../assets/ville-ext.png"
                                    alt="ville-ext"
                                    style="width: 100%; height: 50%"
                                  />
                                </q-carousel-slide>
                                <q-carousel-slide
                                  :name="10"
                                  class="column no-wrap flex-center"
                                >
                                  <img
                                    src="../assets/Ville-int.png"
                                    alt="Ville-int"
                                    style="width: 100%; height: 50%"
                                  />
                                </q-carousel-slide>
                              </q-carousel>
                            </q-dialog>
                          </span>
                        </q-card-actions>
                      </q-card>

                      <q-card
                        style="
                          color: #918f73;
                          margin: 20px;
                          border-radius: 20px;
                          top: 10;
                        "
                        class="my-card"
                      >
                        <q-card-section>
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
                            <div class="text-h6">CMS Wordpress</div>
                            <br />
                          </div>
                          <div class="text-subtitle2">
                            Refonte du site
                            <a href="https://www.cood.fr/"><b>Cood.fr</b></a>
                          </div>
                          <div class="text-grey">
                            Réalisation de la refonte du site www.cood.fr
                          </div>
                        </q-card-section>

                        <q-separator />

                        <q-card-actions style="justify-content: end">
                          <span class="external-links">
                            <a class="open-icon" href="https://cood.fr/">
                              <svg
                                class="MuiSvgIcon-root"
                                focusable="false"
                                viewBox="0 0 24 24"
                                aria-hidden="true"
                                style="
                                  font-size: 25px;
                                  color: var(--lightest-slate);
                                "
                              >
                                <path
                                  d="M19 4H5c-1.11 0-2 .9-2 2v12c0 1.1.89 2 2 2h4v-2H5V8h14v10h-4v2h4c1.1 0 2-.9 2-2V6c0-1.1-.89-2-2-2zm-7 6l-4 4h3v6h2v-6h3l-4-4z"
                                ></path>
                              </svg>
                            </a>
                          </span>
                        </q-card-actions>
                      </q-card>

                      <q-card
                        style="
                          color: #918f73;
                          margin: 20px;
                          border-radius: 20px;
                          top: 10;
                        "
                        class="my-card"
                      >
                        <q-card-section>
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
                            <div class="text-h6">Développement</div>
                            <br />
                          </div>
                          <div class="text-subtitle2">
                            Projet
                            <a
                              href="http://s3-sibel.s3-website.eu-west-3.amazonaws.com/#/"
                              ><b>Blockly</b></a
                            >
                            POur l'entreprise Cood
                          </div>
                          <div class="text-grey">
                            Création d'une documentation interactive nommée
                            "Blockly", en s'inspirant de Three.js et en
                            respectant la charte graphique.<br />
                            Cood propose deux univers le Cood Studio (platforme
                            de jeux qui permet d'apprendre la logique du code)
                            et la Cood Academy (application permettant
                            d'apprendre le numérique).<br />
                            Dans le Cood Studio l'apprentissage du code se fait
                            grâce à "blockly".<br />
                            Ce sont des blocs pouvant être assemblés à l’aide
                            d’un glisser-déposer et permettent de créer une
                            syntaxe complexe.<br />
                            En bref, c'est une bibliothèque qui met à
                            disposition un éditeur de code graphique.
                          </div>
                        </q-card-section>

                        <q-separator />

                        <q-card-actions style="justify-content: end">
                          <span class="external-links">
                            <a
                              class="open-icon"
                              href="http://s3-sibel.s3-website.eu-west-3.amazonaws.com/#//"
                            >
                              <svg
                                class="MuiSvgIcon-root"
                                focusable="false"
                                viewBox="0 0 24 24"
                                aria-hidden="true"
                                style="
                                  font-size: 25px;
                                  color: var(--lightest-slate);
                                "
                              >
                                <path
                                  d="M19 4H5c-1.11 0-2 .9-2 2v12c0 1.1.89 2 2 2h4v-2H5V8h14v10h-4v2h4c1.1 0 2-.9 2-2V6c0-1.1-.89-2-2-2zm-7 6l-4 4h3v6h2v-6h3l-4-4z"
                                ></path>
                              </svg>
                            </a>
                          </span>
                        </q-card-actions>
                      </q-card>

                      <q-card
                        style="
                          color: #918f73;
                          margin: 20px;
                          border-radius: 20px;
                          top: 10;
                        "
                        class="my-card"
                      >
                        <q-card-section>
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
                            <div class="text-h6">Développement</div>
                            <br />
                          </div>
                          <div class="text-subtitle2">
                            <a href="https://51.38.188.2/"
                              ><b>Déliv'green</b></a
                            >
                          </div>
                          <div class="text-grey">
                            Application mettant en relation des livreurs
                            particuliers et professionnelles. Une application où
                            l'on peut être coursier et un simple client
                            souhaitant faire livrer son colis !
                          </div>
                        </q-card-section>

                        <q-separator />

                        <q-card-actions style="justify-content: end">
                          <span class="external-links">
                            <a class="open-icon" href="https://51.38.188.2/">
                              <svg
                                class="MuiSvgIcon-root"
                                focusable="false"
                                viewBox="0 0 24 24"
                                aria-hidden="true"
                                style="
                                  font-size: 25px;
                                  color: var(--lightest-slate);
                                "
                              >
                                <path
                                  d="M19 4H5c-1.11 0-2 .9-2 2v12c0 1.1.89 2 2 2h4v-2H5V8h14v10h-4v2h4c1.1 0 2-.9 2-2V6c0-1.1-.89-2-2-2zm-7 6l-4 4h3v6h2v-6h3l-4-4z"
                                ></path>
                              </svg>
                            </a>
                          </span>
                        </q-card-actions>
                      </q-card>

                      <q-card
                        style="
                          color: #918f73;
                          margin: 20px;
                          border-radius: 20px;
                          top: 10;
                        "
                        class="my-card"
                      >
                        <q-card-section>
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
                            <div class="text-h6">Développement</div>
                            <br />
                          </div>
                          <div class="text-subtitle2">
                            <a href="https://pokemon-battle.netlify.app/"
                              ><b>Pokemon-Battle</b></a
                            >
                          </div>
                          <div class="text-grey">
                            Petit jeu de combat dans le thème "Pokemon"
                            reprenant les personnages. Le jeu met en scène un
                            combat avec un personnage choisis aléatoirement.
                          </div>
                        </q-card-section>

                        <q-separator />

                        <q-card-actions style="justify-content: end">
                          <span class="external-links">
                            <a class="open-icon" href="https://51.38.188.2/">
                              <svg
                                class="MuiSvgIcon-root"
                                focusable="false"
                                viewBox="0 0 24 24"
                                aria-hidden="true"
                                style="
                                  font-size: 25px;
                                  color: var(--lightest-slate);
                                "
                              >
                                <path
                                  d="M19 4H5c-1.11 0-2 .9-2 2v12c0 1.1.89 2 2 2h4v-2H5V8h14v10h-4v2h4c1.1 0 2-.9 2-2V6c0-1.1-.89-2-2-2zm-7 6l-4 4h3v6h2v-6h3l-4-4z"
                                ></path>
                              </svg>
                            </a>
                          </span>
                        </q-card-actions>
                      </q-card>

                      <q-card
                        style="
                          color: #918f73;
                          margin: 20px;
                          border-radius: 20px;
                          top: 10;
                        "
                        class="my-card"
                      >
                        <q-card-section>
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
                            <div class="text-h6">Développement</div>
                            <br />
                          </div>
                          <div class="text-subtitle2">Mini jeux</div>
                          <div class="text-grey">
                            Plusieurs mini jeux en mode "brouillon" sous php.
                          </div>
                        </q-card-section>
                      </q-card>
                    </q-card>
                  </q-dialog>
                </div>
              </div>
            </div>
          </div>
        </div>

        <div class="second-box-reverse">
          <div class="lilContainer">
            <div class="flip-box-inner-lilContainer">
              <div class="flip-box-front-lilContainer">
                <img
                  src="../assets/skills.png"
                  alt="logoSkills"
                  style="max-width: 100%"
                />
              </div>

              <div class="flip-box-back-lilContainer">
                <q-btn
                  label="Compétences"
                  style="
                    font-size: 10px;
                    width: 90%;
                    margin: 5px;
                    align-content: center;
                    justify-content: center;
                    padding: 15px;
                    max-height: 80%;
                    top: 5%;
                  "
                  @click="medium = true"
                />

                <q-dialog v-model="medium">
                  <q-card style="width: 700px; max-width: 80vw">
                    <q-card-section>
                      <div class="text-h6">Compétences</div>
                    </q-card-section>

                    <q-card-section class="q-pt-none">
                      <div
                        style="
                          font-family: 'made_tommy', sans-serif;
                          color: #777;
                        "
                        class="rating"
                      >
                        HTML/CSS<q-rating
                          v-model="ratingModelHTML"
                          color="brown-3"
                          size="1.5em"
                          readonly
                        />
                      </div>

                      <div
                        style="
                          font-family: 'made_tommy', sans-serif;
                          color: #777;
                        "
                        class="rating"
                      >
                        JS Vue/React<q-rating
                          v-model="ratingModelJS"
                          color="brown-3"
                          size="1.5em"
                          readonly
                        />
                      </div>

                      <div
                        style="
                          font-family: 'made_tommy', sans-serif;
                          color: #777;
                        "
                        class="rating"
                      >
                        Quasar/Bootstrap<q-rating
                          v-model="ratingModelQuasar"
                          color="brown-3"
                          size="1.5em"
                          readonly
                        />
                      </div>

                      <div
                        style="
                          font-family: 'made_tommy', sans-serif;
                          color: #777;
                        "
                        class="rating"
                      >
                        Node JS Express<q-rating
                          v-model="ratingModelNode"
                          color="brown-3"
                          size="1.5em"
                          readonly
                        />
                      </div>

                      <div
                        style="
                          font-family: 'made_tommy', sans-serif;
                          color: #777;
                        "
                        class="rating"
                      >
                        Php<q-rating
                          v-model="ratingModelPhp"
                          color="brown-3"
                          size="1.5em"
                          readonly
                        />
                      </div>

                      <div
                        style="
                          font-family: 'made_tommy', sans-serif;
                          color: #777;
                        "
                        class="rating"
                      >
                        Python<q-rating
                          v-model="ratingModelPython"
                          color="brown-3"
                          size="1.5em"
                          readonly
                        />
                      </div>

                      <div
                        style="
                          font-family: 'made_tommy', sans-serif;
                          color: #777;
                        "
                        class="rating"
                      >
                        PhpMyAdmin/ MySql<q-rating
                          v-model="ratingModelBdd"
                          color="brown-3"
                          size="1.5em"
                          readonly
                        />
                      </div>

                      <div
                        style="
                          font-family: 'made_tommy', sans-serif;
                          color: #777;
                        "
                        class="rating"
                      >
                        Visual Studio Code<q-rating
                          v-model="ratingModelVSC"
                          color="brown-3"
                          size="1.5em"
                          readonly
                        />
                      </div>

                      <div
                        style="
                          font-family: 'made_tommy', sans-serif;
                          color: #777;
                        "
                        class="rating"
                      >
                        Github &amp; Gitlab &amp; Git<q-rating
                          v-model="ratingModelGit"
                          color="brown-3"
                          size="1.5em"
                          readonly
                        />
                      </div>

                      <div
                        style="
                          font-family: 'made_tommy', sans-serif;
                          color: #777;
                        "
                        class="rating"
                      >
                        CMS; Wordpress; UI; UX<q-rating
                          v-model="ratingModelCMS"
                          color="brown-3"
                          size="1.5em"
                          readonly
                        />
                      </div>

                      <div
                        style="
                          font-family: 'made_tommy', sans-serif;
                          color: #777;
                        "
                        class="rating"
                      >
                        Bureautiques (office 365)<q-rating
                          v-model="ratingModelBureau"
                          color="brown-3"
                          size="1.5em"
                          readonly
                        />
                      </div>
                      <div
                        style="
                          font-family: 'made_tommy', sans-serif;
                          color: #777;
                        "
                        class="rating"
                      >
                        VSC; Oracle; Eclipse; Netbeans<q-rating
                          v-model="ratingModelBureau"
                          color="brown-3"
                          size="1.5em"
                          readonly
                        />
                      </div>
                    </q-card-section>

                    <q-card-actions align="right" class="bg-white text-teal">
                      <q-btn flat label="OK" v-close-popup />
                    </q-card-actions>
                  </q-card>
                </q-dialog>
              </div>
            </div>
          </div>

          <div class="lilContainer">
            <div class="flip-box-inner-lilContainer">
              <div class="flip-box-front-lilContainer">
                <img
                  src="../assets/car.png"
                  alt="logoCar"
                  style="max-width: 100%"
                />
              </div>

              <div class="flip-box-back-lilContainer">
                <q-btn
                  label="Permis"
                  style="
                    font-size: 10px;
                    width: 90%;
                    margin: 5px;
                    align-content: center;
                    justify-content: center;
                    padding: 15px;
                    max-height: 80%;
                    top: 5%;
                  "
                  @click="open2('top')"
                />

                <q-dialog v-model="dialog2" :position="position2">
                  <q-card style="width: 200px">
                    <q-card-section class="row items-center no-wrap">
                      <div>
                        <div
                          style="
                            font-size: 2em;
                            font-family: 'made_tommy', sans-serif;
                            color: #94745b;
                          "
                          class="text-weight-bold"
                        >
                          Permis B
                        </div>
                        <div style="font-size: 1.5em" class="text-grey">
                          Véhiculé
                        </div>
                      </div>
                    </q-card-section>
                  </q-card>
                </q-dialog>
              </div>
            </div>
          </div>

          <div class="lilContainer-lang">
            <div class="flip-box-inner-lilContainer-lang">
              <div class="flip-box-front-lilContainer-lang">
                <img
                  src="../assets/lang.png"
                  alt="logoLang"
                  style="max-width: 100%"
                />
              </div>

              <div class="flip-box-back-lilContainer-lang">
                <q-btn
                  label="Langues"
                  style="
                    font-size: 10px;
                    width: 90%;
                    margin: 5px;
                    align-content: center;
                    justify-content: center;
                    padding: 15px;
                    max-height: 80%;
                    top: 5%;
                  "
                  @click="mediumLang = true"
                />

                <q-dialog v-model="mediumLang">
                  <q-card style="width: 700px; max-width: 80vw">
                    <q-card-section>
                      <div class="text-h6">Langues</div>
                    </q-card-section>

                    <q-card-section class="q-pt-none">
                      <div
                        style="
                          font-family: 'made_tommy', sans-serif;
                          color: #777;
                          font-weight: 400;
                        "
                        class="rating"
                      >
                        Français <q-space></q-space> Courant
                      </div>

                      <div
                        style="
                          font-family: 'made_tommy', sans-serif;
                          color: #777;
                          font-weight: 400;
                        "
                        class="rating"
                      >
                        Turc <q-space></q-space> Courant
                      </div>

                      <div
                        style="
                          font-family: 'made_tommy', sans-serif;
                          color: #777;
                          font-weight: 400;
                        "
                        class="rating"
                      >
                        Anglais <q-space></q-space> Intermédiaire avancée
                      </div>

                      <div
                        style="
                          font-family: 'made_tommy', sans-serif;
                          color: #777;
                          font-weight: 400;
                        "
                        class="rating"
                      >
                        Espagnol <q-space></q-space> Pré-Intermédiaire
                      </div>
                    </q-card-section>

                    <q-card-actions align="right" class="bg-white text-teal">
                      <q-btn flat label="OK" v-close-popup />
                    </q-card-actions>
                  </q-card>
                </q-dialog>
              </div>
            </div>
          </div>
        </div>
      </div>

      <div class="exp">
        <div class="flip-box-inner-exp">
          <div class="flip-box-front-exp">
            <div>
              <img
                src="../assets/exp.png"
                alt="experiences"
                style="max-width: 100%; max-height: 100%"
              />
            </div>
          </div>

          <div class="flip-box-back-exp">
            <div class="title-card">Mes expériences...</div>
            <div class="btn-exp">
              <q-btn
                push
                label="INFORMATIQUES."
                color="transparent"
                text-color="white"
                style="height: 50%; width: 80%"
                class="btn-exp-design"
                @click="firstExp = true"
              />

              <q-dialog v-model="firstExp">
                <q-card>
                  <q-card-section>
                    <div class="text-h6">Mes débuts dans le domaine...</div>
                  </q-card-section>

                  <q-separator />

                  <q-card-section style="max-height: 50vh" class="scroll">
                    <div>

                     <b style="color: #94745b; font-size: 1.2em"
                        >BAC+3 en alternance</b
                      ><br />
                      <b>
                        <a href="https://www.lafabriquedecom.fr/"><b>La fabrique de com</b></a> -
                        <a href="https://www.2itechacademy.com/programmes/concepteur-developpeur-dapplications/"
                          ><b>2iTech</b></a
                        ></b
                      ><br />
                      <div style="margin-bottom: 8px" class="text-grey">
                        Sep.2022 à Nov.2022<br />
                        Orléans, Centre-Val de Loire, France<br />
                      </div>
                      <div
                        style="
                          font-family: 'made_tommy', sans-serif;
                          color: #777;
                        "
                      >
                        
                      </div>
                         Au sein d'une équipe d'illustrateurs et de graphiste, j'ai été amenée à réaliser la conception
                      et le développement technique de nouvelles applications web et/ou web mobiles...<br/><br/>
                      De la conception des sites internet, de leurs fonctionnalités et de m'adapter aux différents langages
                      <br/><br/>
                      <b style="color: #94745b; font-size: 1.2em"
                        >BTS SIO en alternance</b
                      ><br />
                      <b>
                        <a href="https://www.cood.fr/"><b>Cood</b></a> -
                        <a href="https://www.formation-aftec.com/"
                          ><b>Aftec</b></a
                        ></b
                      ><br />
                      <div style="margin-bottom: 8px" class="text-grey">
                        Oct.2020 - Juin.2022<br />
                        Orléans, Centre-Val de Loire, France<br />
                      </div>
                      <div
                        style="
                          font-family: 'made_tommy', sans-serif;
                          color: #777;
                        "
                      >
                        - Création d'univers de jeux à travers
                        d'assets(communication hebdomadaire - Design)<br />
                        - Création de maquettes et refonte du site
                        <a href="https://www.cood.fr/"><b>Cood</b></a> (
                        développement web et design - utilisation du CMS
                        Wordpress)<br />
                        - Projet
                        <a
                          href="http://s3-sibel.s3-website.eu-west-3.amazonaws.com/#/"
                          ><b>Blockly</b></a
                        >. C'est une documentation interactive pour l'univers du
                        Cood Studio (développement - Quasar - Vue.js...)
                      </div>
                      <br /><br />

                      <b style="color: #94745b; font-size: 1.2em"
                        >Etudiante
                        <a
                          href="https://www.wildcodeschool.com/fr-FR/formations/formation-developpeur-web/orleans?utm_campaign=FR_SEARCH+-+Marque&utm_term=wild%20code%20school%20orl%C3%A9ans&utm_source=adwords&utm_medium=ppc&hsa_grp=127727580462&hsa_src=g&hsa_cam=14821000047&hsa_ad=565956857686&hsa_ver=3&hsa_kw=wild%20code%20school%20orl%C3%A9ans&hsa_net=adwords&hsa_tgt=kwd-1488208655486&hsa_mt=e&hsa_acc=4421706736&gclid=CjwKCAjw9e6SBhB2EiwA5myr9q5zSd3akcwCZvW4V7d8s-xoUysrSOcR9r5VG4a_phQu7wKNXsh3qhoCwQEQAvD_BwE"
                          ><b>Wild Code School</b></a
                        >
                        - WCS.</b
                      ><br />
                      <div style="margin-bottom: 8px" class="text-grey">
                        Oct.2019 - Juil.2020 - 10 mois<br />
                        Orléans, Centre-Val de Loire, France<br />
                      </div>
                      <div
                        style="
                          font-family: 'made_tommy', sans-serif;
                          color: #777;
                        "
                      >
                        Étude sur les langages de programmation HTML/CSS,
                        Python, JavaScript (React/Js, Node/Js, Express).<br />
                        Travail sur des domaines liés au design: UX UI<br />
                        Logiciel utilisé: MySql, PhpMyAdmin, VSC Visual Studio
                        Code, Github, Gitlab.<br />
                        Pratique de la méthode agile: SCRUM. <br />

                        Réalisation de trois projets: deux fictifs et un réel
                        sous un temps limité de 6 semaines.<br />
                        Mon premier projet (fictif) est un site vitrine des
                        résidents du Labo d'Orléans, mon second est la création
                        d'un jeu (fictif) nommé
                        <a href="https://pokemon-battle.netlify.app/"
                          ><b>Pokemon-Battle</b></a
                        >.<br />
                        Mon troisième projet est la création d'un site (réel)
                        nommé:
                        <a href="https://51.38.188.2/"><b>Déliv'green</b></a>
                        étant une application mettant en relation des livreurs
                        particulier et professionnelles. Une application où l'on
                        peut être coursier et un simple client souhaitant faire
                        livrer son colis !<br />

                        D'autres projets ont été réalisés sous forme d'hackathon,
                        des défis à relever en seulement trois jours !
                      </div>
                      <br /><br />

                      <b style="color: #94745b; font-size: 1.2em"
                        >Stage
                        <a
                          href="https://www.google.com/search?gs_ssp=eJzj4tVP1zc0TDZLtigpycs1YLRSNagwMU81STU1MrNINDc1NEuxtDKosDQzSjJJTjNJMjYzTE42SfISTMwpSS1SSE3PV0jJTM8sScwBAPWCFbc&q=alter+ego+digital&oq=aletr+ego+digi&aqs=chrome.1.69i57j46i13i175i199j0i22i30l7.3226j0j7&sourceid=chrome&ie=UTF-8"
                          ><b>Alter Ego Digital</b></a
                        ></b
                      ><br />
                      <div style="margin-bottom: 8px" class="text-grey">
                        Mars.2020 - Avril.2020 - 2 mois<br />
                        Orléans, Centre-Val de Loire, France<br />
                      </div>
                      <div
                        style="
                          font-family: 'made_tommy', sans-serif;
                          color: #777;
                        "
                      >
                        Plateforme permettant d'aider les autres entreprises à
                        réduire leur taux d'absentéisme, à réduire les douleurs
                        physiques des salariés...<br />
                        Travail sur la refonte d'une fonctionnalité du site.<br />
                      </div>
                      <br /><br />

                      <b style="color: #94745b; font-size: 1.2em"
                        >Stage
                        <a href="https://www.krealab.fr/"><b>Krea'Lab</b></a></b
                      ><br />
                      <div style="margin-bottom: 8px" class="text-grey">
                        Mai.2019 - Août.2019 - 2 mois<br />
                        Orléans, Centre-Val de Loire, France<br />
                      </div>
                      <div
                        style="
                          font-family: 'made_tommy', sans-serif;
                          color: #777;
                        "
                      >
                        Participation à trois projets (front-end) "Labo-Lamé"
                        "Primmo" "logigramme primmo".
                      </div>
                      <br /><br />
                    </div>
                    <div class="wrapper2">
                      <div class="typing2">
                        D'autres expériences sont à venir...
                      </div>
                    </div>
                  </q-card-section>

                  <q-separator />
                </q-card>
              </q-dialog>

              <q-btn
                push
                label="EN DEHORS."
                color="transparent"
                text-color="white"
                style="height: 50%; width: 80%"
                class="btn-exp-design"
                @click="secondExp = true"
              />

              <q-dialog v-model="secondExp">
                <q-card>
                  <q-card-section>
                    <div class="text-h6">En dehors de mon domaine...</div>
                  </q-card-section>

                  <q-separator />

                  <q-card-section style="max-height: 50vh" class="scroll">
                    <div>
                      <b style="color: #94745b; font-size: 1.2em"
                        >Assistante laboratoire
                        <a href="https://www.aurea.eu/"
                          ><b>Auréa AgroSciences</b></a
                        ></b
                      ><br />
                      <div style="margin-bottom: 8px" class="text-grey">
                        Juin.2020 - Sept.2020 - 4 mois<br />
                        Ardon, Centre-Val de Loire, France<br />
                      </div>
                      <div
                        style="
                          font-family: 'made_tommy', sans-serif;
                          color: #777;
                        "
                      >
                        - Préparer et réaliser des analyses techniques,
                        scientifiques et/ou des activités expérimentales dans le
                        cadre de procédures définies<br />
                        - Appliquer les règles d’hygiène, de santé, de sécurité
                        et de conditions de travail<br />
                        - Exploiter des résultats d’analyses<br />
                        - Exécuter des tâches de gestion courante telles que la
                        gestion des stocks, gestion des déchets<br />
                        - Maintenir et entretenir des matériels<br />
                        - Préparer et / ou réaliser des analyses techniques ou
                        scientifiques<br />
                        - Préparer et exécuter des protocoles prévus.
                      </div>

                      <br /><br />

                      <b style="color: #94745b; font-size: 1.2em"
                        >Préparateur de commande chez Amazon</b
                      ><br />
                      <div style="margin-bottom: 8px" class="text-grey">
                        Avril.2020 - Nov.2020 - 8 mois<br />
                        Saran, Centre-Val de Loire, France<br />
                      </div>
                      <br />

                      <b style="color: #94745b; font-size: 1.2em"
                        >Préparateur de commande chez CTLOG International</b
                      ><br />
                      <div style="margin-bottom: 8px" class="text-grey">
                        Janv.2021 - 1 mois<br />
                        Meung-sur-Loire, Centre-Val de Loire, France<br />
                      </div>
                      <div
                        style="
                          font-family: 'made_tommy', sans-serif;
                          color: #777;
                        "
                      >
                        - Réceptionner et stocker les marchandises<br />
                        - Emballer et expédier les commandes clients<br />
                        - Réceptionner les marchandises<br />
                        - Vérifier la conformité des commandes reçues<br />
                        - Assurer le flux de colis sur le site en utilisant les
                        moyens mis à disposition
                      </div>

                      <br /><br />

                      <b style="color: #94745b; font-size: 1.2em"
                        >Technicien de surface chez TOUTENET</b
                      ><br />
                      <div style="margin-bottom: 8px" class="text-grey">
                        Nov.2017 - Mars.2020 2 ans 5 mois<br />
                        Saint-Jean-de-la-Ruelle, Centre-Val de Loire, France<br />
                      </div>
                      <div
                        style="
                          font-family: 'made_tommy', sans-serif;
                          color: #777;
                        "
                      >
                        Au sein de sociétés de services de propreté, de
                        collectivités territoriales, d'associations en contact
                        avec différents intervenants (clients, usagers, agents
                        de la collectivité, ...).<br />
                        CDD durant les périodes de vacances scolaires.<br />
                        CDI durant le week-end.
                      </div>

                      <br /><br />

                      <b style="color: #94745b; font-size: 1.2em"
                        >Technicien de surface chez SAMSIC</b
                      ><br />
                      <div style="margin-bottom: 8px" class="text-grey">
                        Juil.2019 - Août.2019 2 mois<br />
                        Saint-Jean-de-la-Ruelle, Centre-Val de Loire, France.
                      </div>
                      <br /><br />

                      <b style="color: #94745b; font-size: 1.2em"
                        >Technicien de surface chez PRO IMPEC</b
                      ><br />
                      <div style="margin-bottom: 8px" class="text-grey">
                        Août.2018 - 1 mois<br />
                        Orléans, Centre-Val de Loire, France<br />
                      </div>
                      <br /><br />

                      <b style="color: #94745b; font-size: 1.2em"
                        >Technicien de surface chez PRO-NET SARL</b
                      ><br />
                      <div style="margin-bottom: 8px" class="text-grey">
                        Juil.2018 - Août.2018 2 mois<br />
                        Orléans, Centre-Val de Loire, France.
                      </div>
                      <br /><br />

                      <b style="color: #94745b; font-size: 1.2em"
                        >Technicien de surface chez INETEX CENTRE VAL DE
                        LOIRE</b
                      ><br />
                      <div style="margin-bottom: 8px" class="text-grey">
                        Mars.2017 - Août.2018 1 mois<br />
                        Orléans, Centre-Val de Loire, France<br />
                      </div>
                    </div>
                  </q-card-section>

                  <q-separator />
                </q-card>
              </q-dialog>
            </div>
          </div>
        </div>
      </div>
    </div>

    <div class="footer">
      <p> N'hésitez pas à visiter la version PC !</p>
      <div>Construit et réalisé par Sibel Koç</div>
      <div>Tous droits réservés ©</div>
    </div>
  </div>
</template>

<script>
import { ref } from "vue";

export default {
  name: "Mobile-page",
  props: {},
  setup() {
    const dialog = ref(false);
    const position = ref("right");
    const dialog1 = ref(false);
    const position1 = ref("right");
    const dialog2 = ref(false);
    const position2 = ref("top");

    return {
      small: ref(false),
      firstExp: ref(false),
      secondExp: ref(false),
      dialog,
      position,
      card: ref(false),
      alert: ref(false),
      dialog1,
      position1,
      position2,
      dialog2,
      dialogMaxToggle: ref(false),
      maximizedToggle: ref(true),
      medium: ref(false),
      mediumLang: ref(false),
      ratingModelHTML: ref(5),
      ratingModelJS: ref(3),
      ratingModelQuasar: ref(4),
      ratingModelNode: ref(3),
      ratingModelPhp: ref(2),
      ratingModelPython: ref(3),
      ratingModelBdd: ref(4),
      ratingModelVSC: ref(4),
      ratingModelGit: ref(4),
      ratingModelCMS: ref(4),
      ratingModelBureau: ref(5),
      carousel: ref(false),
      slide: ref(1),

      open(pos) {
        position.value = pos;
        dialog.value = true;
      },

      open1(pos) {
        position1.value = pos;
        dialog1.value = true;
      },

      open2(pos) {
        position2.value = pos;
        dialog2.value = true;
      },
    };
  },
};
</script>


<style scoped>
.text {
  color: #777;
  font-family: "made_tommy", sans-serif;
}

/* photo */
.Me {
  width: 50%;
  box-shadow: 5px 5px 5px 0px #c7ad9e2f;
  border-radius: 80%;
}

/* Deux lignes de texte */

.container {
  max-width: 100% !important;
}

/* bienvenue ... -> text typing */
.wrapper {
  display: flex;
  align-items: center;
  justify-content: center;
}

.typing {
  width: 24ch;
  animation: typing 6s steps(35), blink 0.2s step-end infinite alternate;
  white-space: nowrap;
  overflow: hidden;
  border-right: 3px solid;
  font-family: -"Square Peg", cursive;
  font-size: calc(20px + 2vw);
  color: #94745b;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  border-right: 10px solid rgba(#94745b, 0.75);
  text-shadow: 0 0 2px;
}

/* sibelKreation title */

.title {
  margin-bottom: 15px;

  white-space: nowrap;
  overflow: hidden;
  font-family: -"Square Peg", cursive;
  font-size: calc(20px + 1vw);
  color: #94745b;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  border-right: 10px solid rgba(#94745b, 0.75);
  text-shadow: 0 0 2px;
}

/* style square -- interface menus */

.square {
  width: 100%;
  padding: 10px 20px 10px 20px;
  justify-content: center;
}

/* style box first line */

.inline-all {
  display: flex;
  justify-content: center;
  justify-content: space-around;
  margin-bottom: 10px;
}

.first-box {
  flex: 1;
  margin-right: 10px;
}

.second-box {
  flex: 1;
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  grid-template-rows: repeat(2, 1fr);
  grid-column-gap: 5px;
  align-items: flex-start;
}

/* style box second line */

.reverse-all {
  display: flex;
  flex-direction: row-reverse;
  justify-content: center;
  justify-content: space-around;
  margin-bottom: 10px;
}

.first-box-reverse {
  flex: 1;
}

.second-box-reverse {
  margin-right: 10px;
  flex: 1;
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  grid-template-rows: repeat(2, 1fr);
  grid-column-gap: 5px;
  align-items: flex-start;
  grid-template-rows: 50%;
}

/* flip card aboutMe/creation */

.medContainer {
  background-color: transparent;
  perspective: 1000px;
}

.flip-box-inner-medContainer {
position: relative;
  min-height: 100%;
  text-align: center;
  transition: transform 0.8s;
  transform-style: preserve-3d;
  justify-content: center;
}

.medContainer:hover .flip-box-inner-medContainer {
  transform: rotateY(180deg);
}

.flip-box-front-medContainer,
.flip-box-back-medContainer {
  position: relative;
  -webkit-backface-visibility: hidden;
  backface-visibility: hidden;
}

.flip-box-back-medContainer {
  background-color: #c7ad9e;
  color: white;
  transform: rotateY(180deg);
  position: absolute;
  top: 0;
  height: 100%;
  width: 100%;
}

/* card à propos  */

.text-h6 {
  font-size: 1.2em;
  font-weight: 600;
  color: #94745b;
  font-family: "made_tommy", sans-serif;
}

.text-subtitle2 {
  font-size: 15px;
  font-weight: 400;
  margin-bottom: 8px;
}

/* flip card mail/discord/In/github/skills/car */

/* YYYYYYYYYYYYYYYYYYYYYYYY */

.lilContainer {
  background-color: transparent;
  perspective: 1000px;
}

.flip-box-inner-lilContainer {
  position: relative;
  min-height: 100%;
  text-align: center;
  transition: transform 0.8s;
  transform-style: preserve-3d;
  justify-content: center;
}

.lilContainer:hover .flip-box-inner-lilContainer {
  transform: rotateY(180deg);
}

.flip-box-front-lilContainer,
.flip-box-back-lilContainer {
  position: relative;
  -webkit-backface-visibility: hidden;
  backface-visibility: hidden;
}

.flip-box-back-lilContainer {
  background-color: #c7ad9e;
  color: white;
  transform: rotateY(180deg);
  position: absolute;
  top: 0;
  height: 100%;
  width: 100%;
}

/* XXXXXXXXXXXXXXXXXXXXXXXX */

.lilContainerX {
  background-color: transparent;
  perspective: 1000px;
}

.flip-box-inner-lilContainerX {
  position: relative;
  min-height: 100%;
  text-align: center;
  transition: transform 0.8s;
  transform-style: preserve-3d;
  justify-content: center;
}

.lilContainerX:hover .flip-box-inner-lilContainerX {
  transform: rotateX(180deg);
}

.flip-box-front-lilContainerX,
.flip-box-back-lilContainerX {
  position: relative;
  -webkit-backface-visibility: hidden;
  backface-visibility: hidden;
}

.flip-box-back-lilContainerX {
  background-color: #c7ad9e;
  color: white;
  transform: rotateX(180deg);
  position: absolute;
  top: 0;
  height: 100%;
  width: 100%;
}

.mailto {
  font-size: 15px;
  font-weight: 400;
  margin-bottom: 8px;
  color: #fff;
}
.mailto:hover {
  transform: scale(1.33);
}

.rating {
  display: inline;
  justify-content: space-between;
  display: flex;
  padding-right: 10px;
  padding-left: 2;
  margin-bottom: 10px;
}

/* flip card lang */

.lilContainer-lang {
  background-color: transparent;
  perspective: 1000px;
  grid-column: 1/4;
  grid-row: 2;
}

.flip-box-inner-lilContainer-lang {
  position: relative;
  text-align: center;
  transition: transform 0.8s;
  transform-style: preserve-3d;
}

.lilContainer-lang:hover .flip-box-inner-lilContainer-lang {
  transform: rotateX(180deg);
}

.flip-box-front-lilContainer-lang,
.flip-box-back-lilContainer-lang {
  position: relative;
  -webkit-backface-visibility: hidden;
  backface-visibility: hidden;
}

.flip-box-back-lilContainer-lang {
  background-color: #c7ad9e;
  color: white;
  transform: rotateX(180deg);
  position: absolute;
  top: 0;
  height: 100%;
  width: 100%;
}

/* flip card experience*/

.exp {
  background-color: transparent;
  perspective: 1000px;
  margin-top: 5px;
}

.title-card {
  font-size: 1.5em;
  font-weight: 600;
  margin-top: 10px;
}

/* bouton dans experience */
.btn-exp {
  grid-column-gap: 10px;
  margin: 10px;
  justify-content: center;
  align-items: center;
  height: 70%;
  display: flex;
  grid-template-columns: repeat(2, 1fr);
}

.btn-exp-design {
  padding: 20px 15px 20px 15px;
  font-size: 10px;
  font-weight: 500;
}

/* typing dans experience */

.wrapper2 {
  display: flex;
  align-items: left;
  justify-content: left;
}

.typing2 {
  width: 29ch;
  animation: typing 6s steps(35), blink 0.2s step-end infinite alternate;
  white-space: nowrap;
  overflow: hidden;
  border-right: 3px solid;
  font-family: -"Square Peg", cursive;
  font-size: calc(15px);
  color: #94745b;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  border-right: 10px solid rgba(#94745b, 0.75);
  text-shadow: 0 0 2px;
}

.flip-box-inner-exp {
  position: relative;
  min-height: 100%;
  text-align: center;
  transition: transform 0.8s;
  transform-style: preserve-3d;
  justify-content: center;
}
.exp:hover .flip-box-inner-exp {
  transform: rotateX(180deg);
}

/*pour cacher la box à l'arriere */
.flip-box-front-exp,
.flip-box-back-exp {
  position: relative;
  -webkit-backface-visibility: hidden;
  backface-visibility: hidden;
}

.flip-box-back-exp {
  background-color: #c7ad9e;
  color: white;
  transform: rotateX(180deg);
  position: absolute;
  top: 0;
  height: 100%;
  width: 100%;
}

.footer {
  font-family: "NTR", sans-serif;
  color: var(--slate);
  text-align: center;
  width: 100%;
  font-size: 16px;
  padding-bottom: 40px;

  align-items: center;
  padding-top: 30px;
}

.folder-icon {
  color: #d4af92;
  justify-content: center;
  display: inline-flex;
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
  margin-right: 10px;
  margin-top: -5px;
}

@keyframes typing {
  from {
    width: 0;
  }
}

@keyframes blink {
  50% {
    border-color: transparent;
  }
}

@keyframes pulse {
  0%,
  100% {
    animation-timing-function: ease-in;
  }
  50% {
    transform: scale(1.33);
  }
}
</style>
