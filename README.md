# Cagnotte 2e Vie : widgets OBS pour les streamers à distance

Affiche dans OBS la cagnotte Extra Life de l'équipe et la tienne, en direct. Le programme tourne sur ton ordinateur : il lit les dons sur Extra Life et met tes widgets à jour toutes les secondes. Ton look et tes réglages restent sur ton PC.

## Télécharger

- **Le programme** : [cagnotte-streamer.zip](https://github.com/tristanbest0802-beep/cagnotte-streamer-distance/releases/latest/download/cagnotte-streamer.zip) (environ 30 Mo)
- **Le guide pas à pas, avec captures** : [Guide-installation-streamer.pdf](Guide-installation-streamer.pdf)

## Ce qu'il te faut

- Un ordinateur Windows 10 ou 11, celui sur lequel tu streames
- OBS Studio
- Une connexion internet
- Ton ID Extra Life : le nombre à la fin de l'adresse de ta page de participant (`extra-life.org/participants/521334`)

## Installation

1. **Extraire le zip** : clic droit sur `cagnotte-streamer.zip`, puis *Extraire tout*. Ne lance rien depuis l'intérieur du zip.
2. **Double-cliquer sur `start.bat`** dans le dossier extrait. C'est la seule chose à lancer : au premier lancement, il installe tout seul ce dont il a besoin, Python compris.
   - Windows affiche un avertissement de sécurité : clique sur *Exécuter* (ou *Informations complémentaires*, puis *Exécuter quand même*). Ce n'est pas un virus : Windows prévient pour tout fichier téléchargé qui n'a pas de signature payante.
   - Laisse la fenêtre noire ouverte pendant tout l'événement.
3. **Entrer ton ID Extra Life** dans la page qui s'ouvre dans ton navigateur, puis *Enregistrer*.
4. **Ajouter tes widgets dans OBS** : *Sources*, puis *+*, puis *Navigateur*. Colle le lien copié depuis la page, en largeur 600 et hauteur 260. Un widget pour la cagnotte de l'équipe, un pour la tienne.

Facultatif : l'onglet *Personnaliser le widget* change les couleurs, la police et la devise. Dans *Réglages*, recopie le taux USD vers CAD annoncé par l'organisateur.

## Les fois suivantes

Double-clic sur `start.bat`, puis ouvre OBS. Tes widgets, ton ID et ton look sont conservés.

## Nouvelle version

Ferme la fenêtre noire, télécharge le nouveau zip et extrais-le au même endroit que le premier, en remplaçant les fichiers. Ton ID et ton look sont conservés.

## Un problème ?

La page *En cas de problème* du guide PDF couvre les cas courants. Sinon, contacte l'organisateur avec une capture d'écran (Windows + Maj + S).
