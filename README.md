# CNT-Al-Composite-Predictor-with-UI
This repository features a physics-informed ML workflow to predict Carbon Nanotube-Aluminum (CNT-Al) composite properties. It includes CNT_Al_Complete_Pipeline.ipynb for data parsing, physics-constrained imputation, and training, alongside CNT_Al_Prediction_UI.ipynb for interactive single-sample, batch, and sensitivity inference.

# How to use:
# CNT_Al_Complete_Pipeline.ipynb
  i. Upload the notebook to Colab
  ii. Select T4 GPU environment
  iii. Press Run All
  iv. When prompted to upload the .xlsx file in the second cell click upload and select "CNT-Al_Composite.xlsx"
  v. All the results will be completed automatically and finally the results will be zipped and prompted to download
  vi. Download and save

#CNT_AL_Prediction_UI.ipynb
  i. From the outputs of the first notebook find the 4 files named "scaler_X.pkl", "scaler_Y.pkl", "model_metadata.json" and "best_model.pkl"
  ii. Upload the second notebook to Colab and again select GPU environment
  iii. Run All
  iv. When prompted to upload the 4 files select them and click upload
  v. All the analysis will be done automatically
  vi. There is an interactive slider UI in "STEP-6". You can manually provide input features here and can get the predictions based on the best trained model from the first notebook
  vii. There is also a cell to upload a csv file in "STEP-7" for batch prediction of multiple samples at once
  viii. After successful run all the outputs will be zipped and prompted to download
