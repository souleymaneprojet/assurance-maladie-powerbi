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


<img width="1041" height="537" alt="P4" src="https://github.com/user-attachments/assets/e8de9528-d6c4-4d0e-a41a-f07ac0a72cd8" />

<img width="1038" height="535" alt="P3" src="https://github.com/user-attachments/assets/cddffed9-9db3-4a5b-aabd-d7b4413028c7" />

<img width="1046" height="540" alt="P2" src="https://github.com/user-attachments/assets/4c69e173-210e-49aa-9d00-4a29847a6b57" />

<img width="1045" height="544" alt="P1" src="https://github.com/user-attachments/assets/903bff21-0583-4617-af03-f1e73a7f9042" />


## 🚀 Résultats

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


