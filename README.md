AUTORADIO VINTAGE - version autonome (web / PWA)
================================================
Aucun logiciel a installer : c'est un site statique. Il suffit de le mettre en ligne,
puis d'ouvrir l'adresse sur n'importe quel appareil connecte a Internet.

FICHIERS (tous a mettre au même endroit) :
  index.html, manifest.webmanifest, sw.js, icon-192.png, icon-512.png,
  icon-maskable-512.png, apple-touch-icon.png, favicon.png

METTRE EN LIGNE (gratuit, 2 minutes) - il faut une adresse HTTPS :
  * Netlify Drop : app.netlify.com/drop -> glisser le DOSSIER décompresse. Adresse fournie aussitôt.
  * Cloudflare Pages : "Direct Upload" -> glisser le dossier.
  * GitHub Pages : créer un dépôt, y déposer les fichiers, Settings > Pages > branche main.
  (Ne pas ouvrir index.html par double-clic pour l'installer : l'installation exige https.)

INSTALLER SUR L'APPAREIL
  * Android / Chrome : menu (3 points) > "Installer l'application".
  * iPhone / iPad / Safari : bouton Partager > "Sur l'écran d'accueil".
  * PC / Chrome ou Edge : icone d'installation dans la barre d'adresse.

CE QUI EST SAUVEGARDE SUR CHAQUE APPAREIL
  Mémoires M1-M20 (appui long pour mémoriser), volume, égaliseur, dernière station.

DISPOSITIONS
  Téléphone en hauteur : mise en page verticale. Paysage, tablette, PC : face avant 15x8.
  Ecran tactile : zones larges, clavier a l'écran. Souris : comportement classique.

LIMITES
  * Certaines radios n'autorisent pas l'analyse audio : elles jouent quand même, mais l'égaliseur
    et le spectre sont alors inactifs pour ce flux.
  * Un flux en http simple est bloque par les navigateurs sur une page https : l'appli essaie
    sa version https ; si elle n'existe pas, la station est indisponible.
  * Sur iPhone, le son se coupe si l'écran se verrouille selon la version d'iOS.
