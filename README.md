# Scrips para la competencia 01

**DM EyF 2024**

https://www.kaggle.com/competitions/dm-ey-f-2024-primera/

Comisión: lunes

Alumno: Santiago Tedoldi

Este repo contiene 5 notebooks que hacen a la entrega final de la competencia. 

## Creación del target e ingeniería de variables
  Notebook_comp01_target.ipynb
  Notebook_comp01_fe_agr_3.ipynb

Estos scripts permiten generar el set de datos que genera el input de los demás notebooks.

## Notebook pipeline de entrenamiento y predicción
  Script_comp01_v02_pipeline_training_entrega.ipynb

Este produce el CSV elegido como entrega:

predicciones_xgboost_FE_3_118_s_proba_mean_thr_opt_kaggle13T-10-202400-08-29.csv

## Back-testing
  Script_comp01_pipeline_back-testing.ipynb

Esto soporta algunas de las decisiones tomadas en el pipeline de entrenamiento y predicción.

## Entregas a Kaggle por API
  Script_comp01_kaggle_api_submissions.ipynb

Idem al back-testing.