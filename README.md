# Radiomics based Prediction of Radiation Tumor Necrosis vs Progression <br />
Radiomics based prediction of Tumor Progression vs Radiation Tumor necrosis on 3DFSPGR Sequence <br />

# Dataset <br />
   TMH 3DFSPGR 3D MRI Data(~140 Patients) - Mannualy Annotated <br />
# Models Used <br />
   XG-Boost with Train-Test Split of 0.3 <br />

# Configuration <br />
   Image Preprocessing - Skull Stripping, Resizing, Normalization <br />
   Radiomic Feature Extraction - 1500+ High Order Features including Wavelet Transformed features   <br />
   Tabular Data Pre-Processing - Outlier Removal, Pearson Corrleation, Class Imbalance correction, GridSearchCV, SelectKBest, Min Max Scaling <br />
   Trained on final 150 best selected features <br />

# Results <br />
   Accuracy of 0.75 with sensitivity of 0.8 and 0.6 respectively on the testing set. AUC of 0.75 <br />

![ Alt text ](https://github.com/parth-radonc/Brain_RTN_Progression/blob/main/Results/res.jpg?raw=true) 

 
