# Predizione del Prezzo di Auto Usate

Elaborato finale per il corso di **Programmazione di Applicazioni Data Intensive**  
A.A. 2025/26 – Laurea in Ingegneria e Scienze Informatiche, DISI – Università di Bologna, Cesena

## Descrizione

Progetto di machine learning per la stima del prezzo di auto usate a partire dalle 
caratteristiche del veicolo (anno, marca, chilometraggio, condizione, ecc.).  
L'obiettivo è aiutare un potenziale acquirente a valutare se un annuncio è sopra o sotto il valore di mercato.

## Dataset

- **Fonte:** Kaggle – [Used Cars Dataset (Craigslist)](https://www.kaggle.com/datasets/austinreese/craigslist-carstrucks-data)
- **Dimensione:** ~420.000 righe, 26 colonne
- **Target:** `price` (variabile continua → regressione)

## Struttura del progetto

- Data cleaning e rimozione outlier
- Analisi esplorativa (EDA)
- Feature engineering (variabili temporali, geografiche, testuali)
- Addestramento e confronto modelli con cross-validation e grid search
- Analisi PCA
- Confronto feature importance XGBoost vs Random Forest

## Requisiti

```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost scikit-learn-intelex
```
