
# 🛡️ Détection de Fuite de Données avec Streamlit

Bienvenue sur ce projet de détection de fuites de données basé sur un modèle de **Machine Learning non supervisé (AutoEncodeur)**.  
Cette solution permet d'identifier des anomalies dans des flux de données réseau à travers une interface **Streamlit** simple et interactive.

---

## 🚀 Démo en ligne

📎 [Accéder à l'application Streamlit](https://fuite-de-donn-es.streamlit.app) *(mettre à jour avec votre lien Streamlit Cloud)*

---

## 🧰 Technologies utilisées

- **Python 3**
- **Streamlit** : interface web interactive
- **TensorFlow / Keras** : AutoEncodeur pour la détection d'anomalies
- **Scikit-learn** : Prétraitement, standardisation, modèles classiques
- **Matplotlib / Seaborn** : Visualisation des erreurs de reconstruction
- **Pandas / NumPy** : Manipulation des données

---

## 🗂️ Structure du projet

```
📁 fuite-de-donnees/
├── fuite_streamlit.py          # Script principal de l'application Streamlit
├── requirements.txt            # Liste des dépendances à installer
├── https://drive.google.com/file/d/1n9K_27iuLb_Ljz69d3YMRe6R5HHzwpWD/view?usp=sharing  # Jeu de données réseau pour l'entraînement
└── README.md                   # Ce fichier
```

---

## 🛠️ Lancement local

1. **Cloner le dépôt**
```bash
git clone https://github.com/ton-utilisateur/fuite-de-donn-es.git
cd fuite-de-donnees
```

2. **Installer les dépendances**
```bash
pip install -r requirements.txt
```

3. **Lancer l'application Streamlit**
```bash
streamlit run fuite_streamlit.py
```

---

## 🧪 Fonctionnalités

- 📤 Upload de fichiers CSV de logs à analyser
- ⚠️ Détection automatique des anomalies via reconstruction AutoEncoder
- 📊 Visualisation dynamique des scores d'erreur
- ⏱️ Simulation en temps réel de flux de logs
- 🧾 Génération d’un **rapport PDF** avec histogramme d'erreur et seuil

---

## 👤 Auteur

**Stéphane Lionnel**  
Mastère Spécialisé - IA School  
📧 Contact : syoungoua0@gmail.com

---

## 📜 Licence

Projet réalisé à des fins pédagogiques. Toute reproduction doit mentionner l'auteur et la source.
