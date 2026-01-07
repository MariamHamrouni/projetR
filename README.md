# Projet Quarto — Périmètres irrigués (Tunisie)

## Contenu
- `data/perimetres-irrigues-public.xlsx` : dataset
- `notebooks/Perimetres_Irrigues_EDA_KPI.ipynb` : notebook (Colab) EDA + KPI + graphes
- `rapport/` : site Quarto (Accueil + Rapport + Dashboard)
- `requirements.txt` : dépendances Python
- `render.ps1` / `render.sh` : génération en local
- `.github/workflows/quarto-gh-pages.yml` : déploiement GitHub Pages (gh-pages)

## Générer le site en local
```bash
cd rapport
quarto render
```
Résultat : `rapport/_site/`

## Notebook (Google Colab)
Importer `notebooks/Perimetres_Irrigues_EDA_KPI.ipynb` et uploader le fichier Excel.

## Déploiement GitHub Pages (option)
Push sur `main` → Actions → publication sur `gh-pages`.
