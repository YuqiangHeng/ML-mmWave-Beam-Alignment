# ML-mmWave-Beam-Alignment

Download the dataset for AP selection and Beam selection at:
https://drive.google.com/drive/folders/1FpkOcnzWkBrOJWae5xrB1tDeXaeWAj2V?usp=sharing

Load a dataset in python using pickle. 
Each dataset is a dictionary containing: 
'AP_location_cartesian': cartesian coordinates of the serving AP,
'UE_location_cartesian': cartesian coordinates of the UEs,
'Hmatrices_real': real component of the channel matrices,
'Hmatrices_imag': imaginery component of the channel matrices
