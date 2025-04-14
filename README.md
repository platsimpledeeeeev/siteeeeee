# 🌆 Bordeaux RP — Site Web Officiel

Bienvenue sur le site officiel de **Bordeaux RP**, un serveur roleplay sérieux et immersif basé sur Discord & FiveM.

---

## 🚀 Fonctionnalités

- 🎉 Page d’accueil animée avec AOS
- 🎭 Section création de personnage (conseils RP)
- 📝 Formulaire Google Forms intégré pour les candidatures
- 🔐 Connexion via Discord pour accéder à la **Banque RP**
- 🌙 Design sombre et responsive (TailwindCSS)

---

## 📁 Structure des fichiers

bordeaux-rp-site/ ├── index.html # Fichier principal du site └── assets/ # Images, scripts, CSS si besoin (facultatif)

yaml
Copier
Modifier

> Le site est **statique** (HTML/CSS/JS), donc tu peux l’héberger partout !

---

## 🧪 Tester en local

1. Ouvre `index.html` dans ton navigateur  
2. Clique sur les boutons et vérifie que l’animation AOS fonctionne  
3. Le bouton **"Se connecter avec Discord"** doit pointer vers ton app OAuth si tu l’as configuré

---

## 🌐 Déploiement

Tu peux déployer le site :

- 🟢 **Gratuit** sur :
  - [Vercel](https://vercel.com/)
  - [Netlify](https://netlify.com/)
  - [GitHub Pages](https://pages.github.com/)
- 💼 Professionnel :
  - OVH / Ionos / PlanetHoster
  - VPS avec Nginx

---

## 🔗 Liens à modifier

- Le lien du **formulaire Google** :  
  Remplace l’`iframe src` dans `index.html` par ton vrai lien.

- Le lien du bouton "Connexion Discord" :  
  Dirige-le vers ton serveur Express/OAuth (ex: `https://bank.bordeauxrp.fr/login`)

---

## 👨‍💻 Auteur

Site créé avec ❤️ pour la communauté **Bordeaux RP**.  
Design simple, animations fluides, et 100% personnalisable.
