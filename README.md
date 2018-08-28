# Project Name: Cardiac Arrhythmia
# Problem Statement: 

The Electrocardiogram (ECG) is an established technique in cardiology for the analysis of cardiac condition of the patients. In its basic definition, ECG is the electrical representation of the contractile activity of the heart, and can be recorded fairly easily by using surface electrodes on the limbs or chest of the patient. The ECG is one of the most recognized and used biomedical signal in the field of medicine. The rhythm of the heart in terms of beats per minute (bpm) can be easily calculated by counting the R peaks of the ECG wave during one minute of recording. More importantly, rhythm and the morphology of the ECG waveform is altered by cardiovascular diseases and abnormalities such as the cardiac arrhythmias, which their automatic
detection and classification is the main focus of this study.


The aim of this project is to distinguish between the presence and absence of cardiac arrhythmia and to classify it in one of the 16 groups. 
  
      Class 01 refers to NORMAL ECG
      
      Classes 02 -15 refers to different classes of arrhythmia 
      
      Class 16 refers to the rest of unclassified ones. 
      
      
   Class Distribution:
   
       Class code :   Class   :                       Number of instances:
       01             Normal                                        245
       02             Ischemic changes (Coronary Artery Disease)    44
       03             Old Anterior Myocardial Infarction            15
       04             Old Inferior Myocardial Infarction            15
       05             Sinus tachycardy                              13
       06             Sinus bradycardy                              25
       07             Ventricular Premature Contraction (PVC)       3
       08             Supraventricular Premature Contraction        2
       09             Left bundle branch block                      9	
       10             Right bundle branch block                     50
       11             1. degree AtrioVentricular block              0	
       12             2. degree AV block                            0
       13             3. degree AV block                            0
       14             Left ventricule hypertrophy                   4
       15             Atrial Fibrillation or Flutter                5
       16             Others                                        22
   
   There are some softwares making such a classification. However there are differences between the cardiologist's and the programs classification. Taking the cardiologist's as a gold standard we aim to minimize this difference by means of machine learning tools." 

# Data set: 
  The data set of project is from UC Irvine Machine Learning Repository.
  https://archive.ics.uci.edu/ml/machine-learning-databases/arrhythmia/arrhythmia.data
  
  Cardiac Arrythmia Database contains 279 attributes, 206 of which are linear valued and the rest are nominal.
  
  Number of Instances: 452
  Number of Attributes: 279
  
  The CSV file uploaded to Github repository as well.
  https://github.com/MuzafferEstelik/Capstone_Project_1/blob/master/arrhythmia.csv
  
