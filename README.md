# TFG - Brain connectivity alterations in Multiple Sclerosis

Aquest repositori conté el treball de fi de grau sobre l'estudi de la connectivitat cerebral en pacients amb Esclerosi Múltiple (EM) mitjançant teoria de grafs i aprenentatge automàtic.

## Descripció

S'han analitzat dades de ressonància magnètica (FA, GM i RS) de 270 participants per modelar xarxes neuronals i investigar diferències de connectivitat entre grups clínics. A continuació, s'han aplicat models de classificació basats en:

- SVM
- Logistic Regression
- Graph Neural Networks (GCN)

L'objectiu principal és detectar patrons de connectivitat alterats associats a la malaltia i avaluar la capacitat predictiva dels models.

## Estructura del repositori

- `GNNs.ipynb` — experimentació amb xarxes neuronals de grafs
- `grafs.ipynb` — construcció i anàlisi de grafs de connectivitat
- `embedding.ipynb` — processament i representacions d'embedding
- `models.ipynb` — entrenament i comparació de models de classificació
- `anàlisi_descriptiu.ipynb` — anàlisi descriptiva de les dades
- `csvs.zip` — fitxers CSV preparats per a l'execució del projecte
- `TFG.pdf` / `TFG_Judit.pdf` / `TFG_PPT_Judit.pdf` — documentació i presentació del treball

## Dades

Les dades preparades per a l'execució del projecte es troben incloses dins de `csvs.zip`.

Si necessites la versió original o la base de dades completa, hi ha un enllaç compartit al Drive:

https://drive.google.com/file/d/1RHwVcF5J04S-Ay6FRFc3Ze68XKkvrDVc/view?usp=sharing

## Requisits

Es recomana un entorn Python 3.9+ amb les següents dependències:

- pandas
- numpy
- networkx
- scikit-learn
- matplotlib
- seaborn
- jupyter
- torch / torch-geometric (si es vol executar la part de GNN)

## Execució

1. Clona el repositori.
2. Descomprimeix `csvs.zip` si cal.
3. Obre els notebooks amb Jupyter Notebook o JupyterLab.
4. Executa les cel·les en ordre per reproduir el pipeline d'anàlisi i modelatge.

## Notes

- La carpeta `csvs` és la que es genera en executar el codi i conté les dades preprocessades per als experiments.
- El projecte està desenvolupat majoritàriament en Jupyter Notebook.

## Autoria

Treball de fi de grau de Judit.

---

English summary:

This repository contains a final-degree project focused on brain connectivity alterations in Multiple Sclerosis patients using graph theory and machine learning. MRI-derived features were modeled as brain networks, and several classifiers were evaluated, including SVM, Logistic Regression, and Graph Neural Networks.
