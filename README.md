# 🤖 Conception et développement d’un système d’analyse de données via un chatbot

Projet de fin d'études réalisé chez **Pixihive**, ce système intelligent vise à analyser les interactions entre un chatbot et les utilisateurs d’un site e-commerce, en exploitant des techniques de **data mining**, de **traitement automatique du langage (NLP)** et de **Business Intelligence**.

---

## 🎯 Objectifs du projet

- Concevoir une solution d’analyse conversationnelle autour d’un **chatbot e-commerce**
- Identifier les **intentions clients** et les regrouper par thématique
- Segmenter les utilisateurs selon leur comportement d’achat
- Recommander des produits en fonction des préférences détectées
- Optimiser l’assortiment produit grâce à l’analyse des demandes récurrentes

---

## 🛠️ Stack technique

- **MongoDB** – Stockage des dialogues clients
- **Python** – Prétraitement, NLP, segmentation
- **Scikit-learn, TF-IDF, Regex** – Classification des intentions
- **Power BI** – Visualisation des KPIs (clients, produits, intentions)
- **Pandas** – Analyse des interactions
- **Matplotlib / Seaborn** – Visualisation intermédiaire

---

## 🔍 Fonctionnalités développées

### 🧠 Analyse des intentions
- Classification automatique (achat, demande d’info, réclamation, recherche…)
- Extraction de mots-clés via NLP (tokenisation, lemmatisation)

### 👥 Segmentation client
- Clustering basé sur la fréquence, le type et la durée des échanges
- Groupes comportementaux : curieux, fidèles, mécontents, techniques…

### 🛒 Optimisation produit
- Mise en relation des intentions détectées avec les produits mentionnés
- Recommandation de produits complémentaires

---

## 📊 Dashboard Power BI

> ![Dashboard Pixibot](https://github.com/NajlaN/Pixihive/blob/main/dashboard%20com.png?raw=true)

Le tableau de bord permet de :

- Visualiser la répartition des intentions clients
- Suivre l’évolution des types de demandes dans le temps
- Identifier les segments clients les plus actifs
- Distinguer les produits les plus demandés ou recommandés

---

## 📁 Structure du dépôt

```bash
📦 Pixihive
 ┣ 📁 data/                      # Données issues du chatbot
 ┣ 📁 scripts/                   # Scripts d’analyse NLP et classification
 ┣ 📄 dashboard com.png          # Capture du dashboard Power BI
 ┣ 📄 dashboard.pbix            # Fichier Power BI
 ┣ 📄 README.md
