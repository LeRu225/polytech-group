POLYTECH GROUP - SITE WEB
=========================

Contenu
  index.html     la page + tous les textes du site (bloc de donnees en haut du fichier)
  candidat.html  redirige les anciens liens d'espace candidat vers index.html
  css/           style.css  -> couleurs (noir et or), decors de chaque rubrique, transitions
  js/            script.js (fonctionnement), config.js (adresse du service d'inscription),
                 pdf.min.js + pdf.worker.min.js (affichage protege de la charte)
  images/        logos et photos (mettre le QR Wave dans images/wave-qr.png)
  videos/        temoignage-1.mp4, temoignage-2.mp4
  backend/       Code.gs + INSTALLATION-INSCRIPTIONS.txt (service des inscriptions, a installer)

Mise en ligne (Netlify ou Cloudflare Pages)
  Deposez le dossier complet SANS le dossier backend/ (il sert a Google Apps Script).
  index.html doit rester au meme niveau que css, js, images, videos.

Modifier le contenu a la main (dans index.html, bloc "data")
  Telephones : "phones":[{"label":"Numero 1","num":"+225 ..."}, ...]
  Liens : "whatsapp":"https://...", "tiktok":"https://..."
  Videos : "src":"videos/temoignage-1.mp4" (ou un lien YouTube)
  Tarifs affiches : "register":{"one":15000,"two":25000,"fee":0.01,...}
  Gardez les guillemets et les virgules tels quels.
