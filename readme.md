# Rocket - Projet Animalier

Projet pédagogique de pratique HTML, CSS et JavaScript sur le thème animalier.

## Objectif

Chaque apprenant est responsable d'une page dédiée à un animal de son choix. L'objectif est de pratiquer la création de pages web complètes (HTML, CSS, JS) en conditions réelles avec Git.

## Structure du projet

```
projet-rocket/
├── index.html
├── style.css
├── script.js
├── assets/
│   ├── images/
│   └── logo/
└── page/
    ├── chat/
    │   ├── chat.html
    │   ├── chat.css
    │   └── chat.js
    ├── chien/
    │   ├── chien.html
    │   ├── chien.css
    │   └── chien.js
    └── ...
```

Chaque apprenant crée un dossier dans `page/` portant le nom de son animal, contenant ses trois fichiers.

## Utilisation de Git

### 1. Récupérer le projet (une seule fois)

```bash
git clone https://github.com/mickael-dvlp/Projet-Rocket.git
```

### 2. Avant chaque session de travail

Toujours récupérer les dernières modifications avant de commencer :

```bash
git pull
```

### 3. Pousser ses modifications

Une fois ton travail terminé :

```bash
git add .
git commit -m "ajout page <nom-de-ton-animal>"
git push
```

## Règles

- Ne pas modifier `index.html`, `style.css` ou `script.js` sans en parler au chef de projet. Petit message dans le discord pour prévenir.

- Travailler uniquement dans son dossier `page/<ton-animal>/`

- Toujours faire un `git pull` avant de commencer à coder pour récupérer les maj des autres developpeurs !

-
