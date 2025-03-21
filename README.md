# 📧 Backend Server with Email Sending 

## 📝 Description
Ce projet est un serveur backend simple qui permet d'envoyer des emails via une API. Il utilise Node.js avec Express et un script dédié à l'envoi d'emails.

## ⚙️ Prérequis 
Avant de lancer le projet, assurez-vous d'avoir installé :
- [Node.js](https://nodejs.org/)
- Un service SMTP ou une API d'envoi d'email (ex : Mailgun, SendGrid, ou autre)

## 🖥️ Installation 
1. Clonez le projet :
   ``` bash
   git clone https://github.com/ayohsan/website-backend.git
   cd website-backend
   ```

2. Installez les dépendances :
   ``` bash
   npm install
   ```

3. Configurez les variables d'environnement :
   - Créez un fichier `.env.local` ou `.env.production` en fonction de votre environnement.
   - Ajoutez vos configurations SMTP ou API d'envoi d'email.

## 🚀 Utilisation 
1. Démarrez le serveur :
   ```bash
   node server.js
   ```
   ou avec Nodemon (si installé) :
   ```bash
   npm run dev
   ```

2. Envoyer un email :
   - Le script `send-mail.js` est utilisé pour envoyer des emails.
   - Modifiez-le selon vos besoins (expéditeur, destinataire, contenu, etc.).

## 💪 Contribution 
Les contributions sont les bienvenues !
- Forkez le projet
- Créez une branche (`feature/ma-fonctionnalite`)
- Faites vos modifications et ouvrez une Pull Request

## 📜 Licence 
Ce projet est sous licence MIT. Vous êtes libre de l'utiliser et de le modifier. 🔓

---
*Développé avec ❤️ par Trafnosleep*
