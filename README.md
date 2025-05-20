# 🤖 Growth Wave AI Agents – Chatbot MVP

Ce projet constitue le **Minimum Viable Product (MVP)** d’un chatbot opérationnel permettant à des utilisateurs B2B de soumettre des fichiers de prospection et de les faire traiter automatiquement par des agents IA internes. Il vise à valider les hypothèses techniques et business autour de l’automatisation de l’enrichissement de données pour les campagnes outbound.

---

## 🎯 Objectif du Produit

Développer une interface simple (chatbot) qui permet de :

- Authentifier les utilisateurs
- Téléverser un fichier CSV de prospection
- Sélectionner un ou plusieurs agents IA ou workflows prédéfinis
- Exécuter les scripts de traitement automatiquement
- Télécharger le fichier enrichi, prêt à l’envoi

---

## 👥 Utilisateurs Cibles

- Consultants B2B  
- Agences de prospection  
- Équipes marketing et growth de SaaS  
- Toute structure ayant besoin de données de prospection nettoyées et enrichies

---

## 💡 Vision Long Terme

- Industrialiser les workflows d’enrichissement de données
- Offrir une plateforme self-service basée sur les agents internes
- Vendre cette solution en marque blanche à d’autres structures B2B

---


## 🧰 Stack Technique

- **Authentification** : Firebase Auth
- **Base de données** : Firestore
- **Stockage de fichiers** : Firebase Storage
- **Exécution des scripts** : Cloud Functions (Python) ou API privée
- **Notifications** : SendGrid ou nodemailer
- **Frontend** : Chatbot React intégré au site Growth Wave

---

## 🧠 Agents IA Disponibles

### Agents individuels
- 🧽 **First Name Cleaner**
- 🏷 **Civilité Detector**
- 🧾 **Full Name Cleaner**
- 🧹 **Deduplicator**

### Workflow préconfiguré
- 🔄 **"Prospection-ready"** =  
  `First Name Cleaner → Civilité Detector → Full Name Cleaner → Deduplicator`

---

## ✨ Fonctionnalités MVP

- [x] Authentification utilisateur
- [x] Système de crédits manuel
- [x] Upload de fichiers CSV
- [x] Sélection d’agents IA ou workflows
- [x] Lancement automatique des traitements
- [x] Étape manuelle de validation
- [x] Livraison du fichier traité
- [x] Logging admin & suivi des jobs


---

## ✅ Critères de Réussite

- Toutes les fonctionnalités majeures sont implémentées
- Peu ou pas de bugs bloquants
- Parcours utilisateur fluide (de l’upload à la récupération du fichier)
- Stack validée pour une montée en charge
- Feedback intégré par l’ensemble de l’équipe

---

## 📄 Licence

Projet interne – propriété de Growth Wave AI Lab.  
Usage restreint à l’équipe projet et tests clients privés.

---


