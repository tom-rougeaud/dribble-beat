# Dribble Beat! 🏀

**Jouer : https://tom-rougeaud.github.io/dribble-beat/**

Jeu de rythme pour apprendre à dribbler au basket, pensé pour les 8-10 ans. Le téléphone est posé debout à 3 pas : la caméra frontale suit le corps et le ballon, la musique (style générique d’anime) donne le « boum » sur lequel faire rebondir le ballon. Le jeu note le rythme et la posture (ballon bas, genoux fléchis, regard devant, bout des doigts), avec combo, bonus Turbo et Points x3, événements « Change de main ! », « Accélère ! », « Plus bas ! », coach vocal et effets manga.

## Confidentialité

Tout se passe dans le navigateur. Les images de la caméra ne sont jamais enregistrées ni envoyées. Il n’y a ni compte, ni cookie, ni traceur, ni serveur. Les statistiques que la bibliothèque de Google essaie d’envoyer sont bloquées. Seuls les réglages, les records et (si on le demande) le prénom sont gardés, sur l’appareil.

## Contenu du dépôt

```
index.html                       le jeu complet (un seul fichier, contenu modifiable dans ses blocs JSON)
vendor/mediapipe/vision_bundle.js   moteur de détection MediaPipe Tasks Vision 1.0.1
vendor/mediapipe/wasm/              4 fichiers WebAssembly du moteur
vendor/mediapipe/models/            les 2 modèles officiels (corps, ballon)
```

Vérifier l’installation : dans le jeu, ⚙️ Réglages → 🩺 Vérifier l’installation.

## Crédits et licences

Conception : Tom Rougeaud, professeur de Maths-Sciences, académie de Dijon. Licence **CC BY-NC 4.0** (partage et adaptation libres, sans usage commercial, en citant l’auteur).
MediaPipe et ses modèles © Google, licence Apache 2.0 (copie dans `vendor/mediapipe/`). Musique et sons composés par l’appli (Web Audio).
