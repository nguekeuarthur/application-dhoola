# 📊 Application Dhoola - Dashboard Analytics

Application de tableau de bord analytique développée avec **Streamlit** pour visualiser et analyser les données d'utilisation de l'application Dhoola.

## 🚀 Fonctionnalités

L'application comprend plusieurs pages interactives :

- **📊 Tableau de bord** - Vue d'ensemble des statistiques générales (sessions, utilisateurs, taux de rétention, conversions)
- **📈 Audience** - Analyse de l'audience et du comportement des utilisateurs
- **📲 Données analytiques** - Métriques d'engagement détaillées
- **🌐 Données géographiques** - Répartition géographique des utilisateurs avec cartes interactives

## 📋 Prérequis

- Python 3.8+
- pip (gestionnaire de paquets Python)

## ⚙️ Installation

1. **Cloner le dépôt**
   ```bash
   git clone https://github.com/nguekeuarthur/application-dhoola.git
   cd application-dhoola
   ```

2. **Créer un environnement virtuel** (recommandé)
   ```bash
   python -m venv venv
   
   # Windows
   venv\Scripts\activate
   
   # Linux/macOS
   source venv/bin/activate
   ```

3. **Installer les dépendances**
   ```bash
   pip install -r requirements.txt
   ```

## 🏃 Lancement de l'application

```bash
streamlit run app.py
```

L'application sera accessible à l'adresse : `http://localhost:8501`

## 📦 Dépendances principales

| Package | Description |
|---------|-------------|
| `streamlit` | Framework web pour les applications de données |
| `pandas` | Manipulation et analyse de données |
| `plotly` | Visualisations interactives |
| `prophet` | Prévisions de séries temporelles |
| `babel` | Internationalisation |

## 📁 Structure du projet

```
application-dhoola/
├── app.py                    # Point d'entrée de l'application
├── Dashboard.py              # Page du tableau de bord principal
├── Usage.py                  # Page d'analyse de l'audience
├── Engagement.py             # Page des données analytiques
├── Maps.py                   # Page des données géographiques
├── connect.py                # Configuration de connexion
├── collectionAnalyseAndAll.py # Scripts d'analyse
├── Analyse/                  # Dossier d'analyses supplémentaires
├── requirements.txt          # Dépendances Python
├── Dhoola.pbix              # Rapport Power BI
└── *.csv                     # Fichiers de données
```

## 📊 Données

L'application utilise plusieurs fichiers CSV pour l'analyse :

- `users.csv` - Données des utilisateurs
- `sessions_with_pages_true.csv` - Données des sessions
- `transaction.csv` - Données des transactions
- `prestataires.csv` - Données des prestataires
- Et d'autres fichiers de données métier...

## 🤝 Contribution

Les contributions sont les bienvenues ! N'hésitez pas à :

1. Fork le projet
2. Créer une branche (`git checkout -b feature/AmazingFeature`)
3. Commit vos changements (`git commit -m 'Add some AmazingFeature'`)
4. Push sur la branche (`git push origin feature/AmazingFeature`)
5. Ouvrir une Pull Request

## 👤 Auteur

**Arthur Nguekeu**

- GitHub: [@nguekeuarthur](https://github.com/nguekeuarthur)

## 📝 Licence

Ce projet est sous licence libre. Voir le fichier `LICENSE` pour plus de détails.

---

⭐ Si ce projet vous a été utile, n'hésitez pas à lui donner une étoile sur GitHub !
