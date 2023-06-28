# AED_mon0channel
Audio Event detection using SED 2022 SONY TAU dataset
We have converted into MONO channel AED data
Create a virtual ENV python3 -m venv SED-2022
Activate virtual ENV source SED-2022/bin/activate
We have parameters.py file consists of hyper parameters 
Add the proper dataset  path in parameters.py
create a labels using python batch_feature_extraction.py
Train the model using python train_seldnet.py
