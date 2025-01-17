# SAE1.04-
# Gestion d’Épicerie – Base de Données Access  

## 🎯 Objectif du Projet  
Ce projet a été développé pour simuler la gestion complète d’une épicerie, en utilisant **Microsoft Access**. L’objectif principal est de démontrer des compétences en modélisation de données, en gestion de formulaires et en génération de rapports.  

Le projet est conçu pour répondre aux besoins suivants :  
- Suivi des stocks de produits.  
- Gestion des clients.  
- Création et impression de tickets de caisse.  
- Suivi des revenus mensuels.  
- Identification des produits à faible stock.  

---

## 🛠️ Fonctionnalités Principales  
### **1. Gestion des Produits**  
- **Ajout, modification et suppression de produits.**  
- Suivi des quantités en stock, avec alerte sur les faibles stocks.  
- Organisation des produits par catégories.  

### **2. Gestion des Clients**  
- Enregistrement des informations clients (nom, contact, etc.).  
- Possibilité de rechercher un client rapidement via des formulaires.  

### **3. Génération de Tickets de Caisse**  
- Ajout de plusieurs produits à une vente.  
- Calcul automatique des sous-totaux et du total.  
- Impression d’un ticket personnalisé pour chaque vente.  

### **4. Suivi des Revenus Mensuels**  
- Visualisation des revenus par mois.    

### **5. Rapports Détaillés**  
- **Inventaire des produits :** Vue complète des stocks.  
- **Revenus mensuels :** Analyse des performances mensuelles.  
- **Produits à faible stock :** Liste des produits nécessitant un réapprovisionnement.  
- **Ticket de caisse :** Rapport spécifique pour chaque vente.
   

---

## 📋 Organisation des Données  
### **Structure des Tables**  
1. **Produit :** Gère les informations sur les produits (ID, nom, prix, stock, etc.).  
2. **Client :** Contient les informations des clients.  
3. **Vente :** Enregistre les transactions (ID vente, client, date).  
4. **Détail_Vente :** Associe les ventes aux produits (quantité, prix unitaire).
5. **Stock :** Associe un produit à un emplacement dans le stock pour savoir les quantité du produit restante.
6. **Catégorie :** Associe un produit à une catégorie de produit(exemple Produit Laitier).

### **Relations**  
Les tables sont reliées de manière à maintenir l’intégrité des données, notamment via des relations **un-à-plusieurs** :  
- Un produit peut être lié à plusieurs ventes via Détail_Vente.  
- Une vente est associée à un client unique.

---

## 🖥️ Formulaires Développés  
1. **Menu Principal :**  
   Permet d’accéder aux différents modules du projet (gestion des produits, clients, etc.).  
2. **Gestion des Produits :**  
   Formulaire interactif pour gérer les produits. Inclut un champ de recherche et des boutons pour ajouter ou modifier.  
3. **Gestion des Clients :**  
   Interface simple pour gérer les informations des clients.  
4. **Création de Tickets de Caisse :**  
   Formulaire interactif permettant de sélectionner un client, ajouter des produits à une vente, et générer un ticket.  

---

## 📈 États Générés  
1. **Inventaire des Produits :** Vue d’ensemble des stocks actuels.  
2. **Revenus Mensuels :** Tableau et graphique des revenus générés chaque mois.  
3. **Produits à Faible Stock :** Liste des produits avec une quantité critique.  
4. **Ticket de Caisse :** Rapport imprimable pour une vente donnée.  

---

## 🧰 Technologies Utilisées  
- **Microsoft Access :** Pour la conception de la base de données et des interfaces.  
- **PowerAmc :** Pour créer le Modèle Conceptuel de Donnée.  

---

## 🚀 Comment Utiliser le Projet  
1. Ouvrez le fichier zip Access fourni (`.accdb`).  
2. Décompressez le fichier fourni.
3. Ouvrez **Access.accdb** suyr Access pour naviguer entre les fonctionnalités.
4. Pour l'explication detaillé du projet ouvrez le **Rapport.pdf**.

---

  
