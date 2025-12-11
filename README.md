# Mise en place d'un environnement de gestion des utilisateurs et des ressources sous Windows Server 2016

## 📘 Description du projet
Ce projet présente la mise en place complète d’un environnement Windows Server 2016 permettant la gestion centralisée des utilisateurs, des groupes et des ressources au sein d’un domaine Active Directory.  
Il a été réalisé dans le cadre d’un laboratoire pratique afin de comprendre et maîtriser le fonctionnement d’un environnement d’entreprise basé sur Windows Server.

---

## 🎯 Objectifs du projet
- Déployer un contrôleur de domaine sous Windows Server 2016  
- Installer et configurer Active Directory Domain Services (AD DS)  
- Mettre en place un serveur DNS et DHCP  
- Créer et structurer des unités d’organisation (OU)  
- Gérer les utilisateurs, groupes et permissions  
- Configurer des stratégies de groupe (GPO)  
- Joindre un poste client au domaine  
- Tester l’authentification et la gestion des droits d’accès  
- Partager des ressources en réseau (dossiers, imprimantes, etc.)  

---

## 🏗️ Architecture du laboratoire
Le lab est composé des éléments suivants :

### 🔹 Machines virtuelles
- **Windows Server 2016** (Contrôleur de domaine)
- **Windows 10** (Client intégré au domaine)

### 🔹 Rôles et services installés
- AD DS (Active Directory Domain Services)
- DNS Server
- DHCP Server
- GPO Management
- Services de fichiers (SMB)

### 🔹 Réseau
- Réseau interne NAT  
- Adressage IP fixe pour le serveur  
- Distribution dynamique des IP via DHCP pour les clients  

---

## 🛠️ Étapes principales réalisées

### 1️⃣ Installation et promotion du serveur en contrôleur de domaine  
- Installation du rôle AD DS  
- Création du domaine  
- Configuration DNS intégrée

### 2️⃣ Création de l’arborescence Active Directory  
- Unités d’organisation : *Utilisateurs*, *Groupes*, *Postes clients*, *Ressources*  
- Création d’utilisateurs et groupes (sécurité & distribution)

### 3️⃣ Mise en place des GPO  
- Politique de mot de passe  
- Restrictions d’accès  
- Configuration de l’environnement utilisateur  
- Déploiement automatique des paramètres réseau

### 4️⃣ Configuration du DHCP  
- Création d’un scope  
- Définition des options DHCP (DNS, passerelle, etc.)  
- Attribution dynamique d’adresses IP

### 5️⃣ Partage des ressources  
- Création de dossiers partagés  
- Définition des permissions NTFS et de partage  
- Test des accès selon les groupes et utilisateurs

### 6️⃣ Joindre un poste client au domaine  
- Connexion via un compte de domaine  
- Vérification de l’application des GPO  
- Tests de connectivité réseau

---

## 📂 Contenu du dépôt
- Documentation complète du laboratoire  
- Captures d’écran de chaque étape  
- Fichiers de configuration (si disponibles)  
- Notes techniques / rapport final

---

## 📸 Captures d’écran
Un dossier **/screenshots** contient les images importantes du lab.

Exemple d’intégration dans le README :

```md
![Active Directory](./screenshots/active-directory.png)
