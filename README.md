# 🔧 NASA Turbofan RUL — Maintenance Prédictive

> Prédiction de la Durée de Vie Résiduelle (RUL) de turboréacteurs à partir des données capteurs NASA C-MAPSS.

## 🎯 Objectif

Estimer avec précision le nombre de cycles restants avant la défaillance d'un moteur, avec une erreur cible < 20 cycles (MAE).

## 🛠️ Stack technique

- **Analyse** — Pandas, NumPy, SciPy, Scikit-learn
- **Tracking** — MLflow
- **API** — FastAPI
- **Dashboard** — Streamlit
- **Infra** — Docker, AWS
- **CI/CD** — GitHub Actions

## 🛣️ Roadmap

- [ ] EDA + tests statistiques
- [ ] Feature engineering
- [ ] Modélisation + MLflow tracking
- [ ] API FastAPI
- [ ] Dashboard Streamlit
- [ ] Déploiement AWS

## 📝 Conventions de commit

Ce projet suit la convention [Conventional Commits](https://www.conventionalcommits.org/) :

- `eda:` — nouvelle analyse
- `feat:` — nouvelle fonctionnalité
- `fix:` — correction de bug
- `docs:` — documentation
- `chore:` — maintenance, setup
- `test:` — tests
- `refactor:` — refactoring sans nouvelle fonctionnalité
- `ci:` — pipeline CI/CD

## 🚀 Installation
```bash
git clone https://github.com/SimonGallien/nasa-turbofan-rul.git
cd nasa-turbofan-rul
uv sync
```