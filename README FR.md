# 🌐 OlaxeeTools

**OlaxeeTools** est un outil léger conçu pour **détecter et afficher votre adresse IP privée** directement sur votre réseau local.  
Il fournit à la fois une **interface web** (HTML, CSS, JS) et des exécutables autonomes pour les appareils **PC** et **Android**.

> 🔗 Site web officiel : [olaxeetools.vercel.app](https://olaxeetools.vercel.app)

---

## *Other languages ?* [Click Here](https://github.com/Olaxee/OlaxeeTools/?tab=readme-ov-file#-translations).

## 🧰 Caractéristiques

- Détecte vos adresses **IPv4** locales.
- **Interface utilisateur** simple et épurée, conçue avec HTML, CSS et JavaScript.
- Disponible pour **Windows, Linux, macOS et Android**.
- Fournit à la fois des versions **`.exe` (ordinateur)** et **`.apk` (mobile)**.
- **Open source** et léger (< 15 Mo).

---

## 📦 Versions

| Plateforme | Version | Fichier | SHA256 | Taille |
|-----------|----------|-------|--------|------|
| 🖥️ **Windows / macOS / Linux** | 2.0.80 | `iP_OlaxeeTools.exe` | `0db949fb0fccfa38b0a161c69419c0a6993b5adaf9b7e8afc6815736ce5619b5` | 12,4 Mo |
| 🤖 **Android** | 2.0.80 | `iP_OlaxeeTools.apk` | `c1c17fb5bb063b0a866c71feb412ded4256a13ac6f9d54539b0e8ff7b76079cf` | 44,2 Mo |

👉 [Voir toutes les versions](https://github.com/Olaxee/OlaxeeTools/releases)

---

## 💻 Pour les développeurs

Ce référentiel contient la version web d'OlaxeeTools :
- `index.html` — interface principale
- `script.js` — logique de détection et d'interactivité  
- `style.css` — mise en page et thème de l'interface utilisateur
 
### 🧩 Structure

| Langage | Utilisation |
|-----------|--------|
| **HTML** | Structure de la page |
| **CSS** | Design et mise en page |
| **JavaScript** | Logique et gestion des IP |

> Développement et déploiement via **Vercel**.  
> hébergé sur [Olaxee/OlaxeeTools](https://github.com/Olaxee/OlaxeeTools).

---

## 📲 Installation

### 🖥️ **PC (Windows, macOS, Linux)**

1. Téléchargez `iP_OlaxeeTools.exe` depuis la [page des releases](https://github.com/Olaxee/OlaxeeTools/releases).  
2. Double-cliquez sur le fichier exécutable pour démarrer le serveur local et ouvrir l'interface.  
3. Le programme détecte et affiche automatiquement votre adresse IP privée.

> 🧠 Ne nécessite aucune dépendance externe — exécutable portable.

---

### 📱 **Android**

1. Téléchargez `iP_OlaxeeTools.apk` depuis la page [des versions](https://github.com/Olaxee/OlaxeeTools/releases).  
2. Installez manuellement l'APK sur votre appareil :
   - Activez « Installer des applications inconnues » dans les paramètres si nécessaire.  
   - Appuyez sur le fichier pour l'installer.
3. Ouvrez l'application — ton adresses IPv4 locales s'afficheront.

> ⚠️ **Non compatible avec iOS.**

---

## 🧠 Aperçu technique

- **Backend :** script serveur local (basé sur Python pour la version `.exe`).  
- **Frontend :** interface web pure HTML / CSS / JS.  
- **Détection :** utilise les sockets du réseau local pour résoudre les adresses IP privées.  
- **Fallback :** affiche `1.1.1.1` si la détection échoue.

---

## 🔒 Sécurité

- Toutes les données restent **sur votre appareil local**.  
- Aucune adresse IP ou identifiant n'est transmis à l'extérieur.  
- Utilisation sécurisée dans des environnements hors ligne et sécurisés.

---

## 🚀 Déploiement

La version web d'OlaxeeTools est hébergée via **Vercel** :  
👉 [https://olaxeetools.vercel.app](https://olaxeetools.vercel.app)

Vous pouvez déployer votre propre version en utilisant :
```bash
npm install
vercel deploy
```

---

## 📞 Contact

**Responsable :** [@Olaxee](https://github.com/Olaxee)  
📧 **E-mail :** olaxee00@gmail.com / owenleroux09@gmail.com

Pour signaler un bug ou demander une fonctionnalité, veuillez ouvrir un ticket sur GitHub.

---

## 🧾 Licence

Ce projet est distribué en open source à des fins éducatives et de démonstration technique.  
© 2025 Olaxee — Tous droits réservés.

---

## 💬 Merci !

> Merci d'avoir téléchargé et soutenu **OlaxeeTools** ❤️  
> N'hésitez pas à ⭐ le dépôt si vous le trouvez utile !

---

## 🌐 Traductions

[Click Here](https://github.com/Olaxee/OlaxeeTools/wiki/Translations) *Paur d'autre langages*
