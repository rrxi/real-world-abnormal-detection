## Google Colaboratory Using

1. new realworld.ipynb

2. ```bash
   !git clone https://github.com/rrxi/real-world-abnormal-detection.git
   ```

3. ```bash
   !pip install  keras==1.1.0
   ```

4. ```bash
   !pip install theano==1.0.2
   ```

5. update keras use theano

6. ```bash
   # train model
   !python TrainingAnomalyDetector_public.py
   ```

7. ```bash
   # test model
   !python Test_Anomaly_Detector_public.py
   ```

train output save in Trained_Models/TrainedModel_MIL_C3D

## Dataset

Dataset store in SampleVideos.

Download processed data form https://drive.google.com/drive/folders/1rZn-UHM_EcIXauJ0wRysQbh0mHQoNrfY

## Ref

https://github.com/WaqasSultani/AnomalyDetectionCVPR2018