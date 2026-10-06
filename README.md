# MotionView

Lecteur vidéo, musique et photos pour Windows 10 et 11 : il ouvre les formats courants sans codec à installer,
enchaîne les épisodes d'une série, affiche les sous-titres et les paroles, et lit les vidéos en ligne à partir du
lien de leur page. Vos fichiers restent sur l'ordinateur. À l'ouverture, MotionView demande seulement s'il existe
une nouvelle version ; ses compléments (modèle de sous-titres, banque de sons MIDI, FFmpeg, yt-dlp) ne se
téléchargent qu'après votre accord.

## Télécharger

La dernière version est dans **Releases**, à droite de cette page, et toujours à la même adresse :
https://github.com/Axel-sell/motionview-mises-a-jour/releases/latest

- `MotionView-<version>-installateur.exe` installe MotionView pour la personne connectée, sans droits
  d'administrateur. Ensuite, MotionView regarde à chaque ouverture si une nouvelle version existe et la
  propose ; il peut aussi l'installer tout seul (Réglages › Confidentialité et mises à jour).
- `MotionView-<version>-portable.zip` fait tourner MotionView sans rien installer : décompresser le fichier
  (clic droit › Extraire tout…), puis ouvrir `MotionView.exe` dans le dossier obtenu.

Windows ne connaît pas encore MotionView : le navigateur peut dire que le fichier est rarement téléchargé
(choisir « Conserver »), puis Windows afficher « Windows a protégé votre ordinateur » (cliquer sur
« Informations complémentaires », puis « Exécuter quand même »).

Ce dépôt ne contient que les versions publiées. Chacune est accompagnée d'une fiche signée
(`motionview-version.json`) : MotionView n'installe une mise à jour que si la signature de la fiche et
l'empreinte de chaque fichier concordent.

Conçu par Alex NGASSA.
