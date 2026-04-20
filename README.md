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
<img width="1208" height="554" alt="vue ensemble" src="https://github.com/user-attachments/assets/d1ed7b5b-ff65-4467-8344-40cecd28f50c" />
<img width="1058" height="477" alt="per" src="https://github.com/user-attachments/assets/de8c2b45-c586-42a1-abaa-77bbc7f22695" />
<img width="1049" height="482" alt="qua" src="https://github.com/user-attachments/assets/03ea846c-9054-4ba5-9d73-fea0f0a978cc" />
<img width="1058" height="478" alt="tep" src="https://github.com/user-attachments/assets/c2eacf05-c250-4bad-af67-74f162c5158c" />






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


