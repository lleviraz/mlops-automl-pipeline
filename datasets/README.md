# datasets folder - borrowed from Kaggle
https://www.kaggle.com/datasets/vikrishnan/boston-house-prices and https://www.kaggle.com/datasets/floser/french-motor-claims-datasets-fremtpl2freq

To download and use from a Colab notebook, copy this code to a cell:

DS_DIR='/content/mlops-automl-pipeline/datasets'

!git clone https://github.com/lleviraz/mlops-automl-pipeline.git && unzip -n {DS_DIR}/french_motor_archive.zip -d {DS_DIR}/ && ls {DS_DIR}/
