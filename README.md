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
<img width="1046" height="408" alt="v" src="https://github.com/user-attachments/assets/c4cf5881-6a7d-40a7-8518-69081387e121" />
<img width="1038" height="415" alt="p" src="https://github.com/user-attachments/assets/2a425d8e-fb4f-4137-bbbf-541c51439ad8" />
<img width="1027" height="414" alt="q" src="https://github.com/user-attachments/assets/a4d27305-868e-4c52-82e9-82494a2ae5f9" />
<img width="1037" height="409" alt="t" src="https://github.com/user-attachments/assets/58108b50-82ba-491a-90cd-95cfc4c6424e" />










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


