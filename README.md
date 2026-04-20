# 📊 Dashboard Power BI - Analyse de la performance (Assurance Maladie)

## 🎯 Objectif du projet

Ce projet a pour objectif de construire un tableau de bord interactif permettant d’analyser la performance opérationnelle, la qualité de service et les coûts à partir de données de santé simulées.

---

## 📁 Structure du projet

```
assurance-maladie-powerbi/
│
├── data/        # Données sources (CSV)
├── report/      # Fichier Power BI (.pbix)
├── images/      # Captures du dashboard
├── README.md
```

---

## 📊 Données utilisées

Le dataset contient les informations suivantes :

* Données patients (âge, genre, groupe sanguin)
* Conditions médicales
* Dates d’admission et de sortie
* Coûts (Billing Amount)
* Type d’admission (Emergency, Urgent, Elective)
* Résultats médicaux (Normal, Abnormal, Inconclusive)

---

## 🔧 Préparation des données (Power Query)

* Nettoyage des noms (formatage)
* Gestion des types de données
* Conversion des montants (gestion du format régional)
* Création de nouvelles colonnes :

  * Durée de séjour
  * Année / Mois
  * Segmentation par âge
  * Indicateurs (urgence, anomalie)

---

## 📈 KPI développés

* 💰 Coût total
* 💸 Coût moyen par patient
* ⏱ Durée moyenne de séjour
* 🚨 Taux d’admissions urgentes
* ⚠️ Taux d’anomalies (tests médicaux)
* 📊 Nombre total de patients

---

## 📊 Dashboard (Power BI)

### 🟦 Vue d’ensemble

* Indicateurs clés (KPI)
* Répartition des patients
* Coûts globaux

### 🟩 Performance opérationnelle

* Analyse des durées de séjour
* Activité par hôpital et médecin

### 🟨 Qualité des services

* Analyse des résultats médicaux
* Taux d’anomalie

### 🟥 Analyse temporelle

* Évolution des admissions
* Tendances des coûts

---

## 🛠 Outils utilisés

* Power BI
* Power Query
* DAX
* Excel / CSV

---

## 📸 Aperçu du dashboard

<img width="1920" height="800" alt="donnée" src="https://github.com/user-attachments/assets/1434f28f-06a0-49b4-bebf-7db662fa4907" />

<img width="1920" height="800" alt="vu d&#39;ensemble" src="https://github.com/user-attachments/assets/60201f7f-12e4-4649-a53d-01440f3091c1" />

<img width="1920" height="800" alt="analyse temp" src="https://github.com/user-attachments/assets/d0a2da44-8c0d-4bc3-bf1a-5bc8bf5c9c84" />

##<img width="1920" height="800" alt="Performance" src="https://github.com/user-attachments/assets/2b1826ba-f7a0-4881-8b91-534fb78a6d3e" />

<img width="1920" height="800" alt="qualite service" src="https://github.com/user-attachments/assets/77aabef1-a719-4c61-8391-735bb493d481" />



 🚀 Résultats

Ce projet permet :

* d’identifier les facteurs impactant les coûts
* d’analyser la performance des établissements
* de suivre la qualité des services de santé

---

## 👤 Auteur

* Nom : DAFFE Souleymane
* Profil : data Scientist / Data Analyst
* link : linkedin.com/in/jules-souleymane
* Portfolio : https://souleymaneprojet.github.io/portfolio/


