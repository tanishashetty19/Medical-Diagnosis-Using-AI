
#  Disease Prediction App  

A **Streamlit-based web application** that predicts the likelihood of various diseases like **Heart Disease, Parkinson’s Disease, Lung Cancer, Diabetes and Hypo-Thyroid Disease**, using **Machine Learning models**. AI based medical diagnosis sytem. 

## Features  
- **User-friendly UI** using **Streamlit**  
- **Predicts multiple diseases** based on user input  
- **Machine Learning models** trained for high accuracy  
- **Interactive visualization** with a background image  

## Tech Stack  
- **Python** (ML models & backend)  
- **Streamlit** (for web UI)  
- **Pickle** (to load pre-trained models)  
- **Machine Learning** (trained on real-world datasets)  

## Installation  
1. **Clone the repository:**  
   ```bash
   git clone https://github.com/your-username/disease-prediction-app.git  
   cd disease-prediction-app
2. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
3. **Run the Application:**
   ```bash
   streamlit run app.py
## Diseases Supported
- **Heart Disease**
- **Parkinson's Disease**
- **Hypo-Thyroid Disease**
- **Lung Cancer**
- **Diabetes**
- 
## Patient Data(Input)
- **Diabetes Prediction**
- Number of Pregnancies – The number of times the patient has been pregnant (for females).
- Glucose Level – Blood sugar level in mg/dL.
- Blood Pressure – Systolic blood pressure value in mmHg.
- Skin Thickness – Thickness of skin fold in mm, indicating body fat percentage.
- Insulin Level – Fasting insulin level in µU/mL.
- BMI (Body Mass Index) – A measure of body fat calculated as weight (kg) / height² (m²).
- Diabetes Pedigree Function – A value representing genetic risk of diabetes based on family history.
- Age – The patient’s age in years.
  
- **Heart Disease Prediction**
- Age – The patient’s age in years.
- 	Sex – 1 for male, 0 for female.
- 	Chest Pain Type (CP) – A value from 0 to 3 indicating the severity of chest pain.
- 	Resting Blood Pressure (trestbps) – Blood pressure in mmHg when at rest.
- 	Serum Cholesterol (chol) – The total cholesterol level in mg/dL.
-  Fasting Blood Sugar (fbs) – 1 if fasting blood sugar is above 120 mg/dL, 0 otherwise.
-  Resting Electrocardiographic Results (restecg) – Measures electrical activity of the heart (0 to 2 scale).
-  Maximum Heart Rate (thalach) – The highest heart rate achieved during exercise.
-  Exercise-Induced Angina (exang) – 1 if the patient experiences chest pain during exercise, 0 otherwise.
-  ST Depression (oldpeak) – A value indicating changes in the heart’s ST segment (important in ECG tests).
-  Slope of the Peak Exercise ST Segment (slope) – A value indicating heart stress response.
-  Major Vessels (ca) – Number of major blood vessels (0 to 3).
-  Thalassemia (thal) – A blood disorder indicator (values 0 to 2).
  
-  **Parkinson’s Disease Prediction**
-  MDVP: Fo(Hz) – The fundamental frequency of the voice.
-  MDVP: Fhi(Hz) – Highest frequency reached in voice samples.
-  MDVP: Flo(Hz) – Lowest frequency reached in voice samples.
-  MDVP: Jitter(%) – Variation in frequency, indicating voice instability.
-  MDVP: Jitter(Abs) – Absolute jitter value.
-  MDVP: RAP – Relative amplitude perturbation.
-  MDVP: PPQ – A measure of pitch variation.
-  Jitter: DDP – Another indicator of voice stability.
-  MDVP: Shimmer – Variation in amplitude, indicating weakness in voice.
-  MDVP: Shimmer(dB) – Shimmer measured in decibels.
-  Shimmer: APQ3, APQ5, APQ – Different measures of amplitude variation.
-  Shimmer: DDA – A shimmer-based diagnostic indicator.
-  NHR (Noise-to-Harmonics Ratio) – Measures breathiness in the voice.
-  HNR (Harmonics-to-Noise Ratio) – Measures clarity of speech.
-  RPDE, DFA – Indicators of speech pattern complexity.
-  Spread1, Spread2 – Measures of frequency spread.
-  D2 – Nonlinear measure of voice changes.
-  PPE (Pitch Period Entropy) – Measures randomness in pitch.
- 
-  **Lung Cancer Prediction**
-  Gender – 1 for male, 0 for female.
-  Age – The patient’s age in years.
-  Smoking – 1 if the patient is a smoker, 0 otherwise.
-  Yellow Fingers – 1 if the patient has yellow-stained fingers (common in heavy smokers).
-  Anxiety – 1 if the patient experiences anxiety frequently.
-  Peer Pressure – 1 if smoking was influenced by social pressure.
-  Chronic Disease – 1 if the patient has other chronic illnesses.
-  Fatigue – 1 if the patient experiences excessive tiredness.
-  Allergy – 1 if the patient has frequent allergic reactions.
-  Wheezing – 1 if the patient experiences wheezing sounds while breathing.
-  Alcohol Consumption – 1 if the patient regularly consumes alcohol.
-  Coughing – 1 if the patient has persistent coughing.
-  Shortness of Breath – 1 if the patient struggles to breathe.
-  Swallowing Difficulty – 1 if the patient finds it hard to swallow food.
-  Chest Pain – 1 if the patient experiences frequent chest pain.
  
-  **Hypo-Thyroid Disease Prediction**
-  Age – The patient’s age in years.
-  Sex – 1 for male, 0 for female.
-  On Thyroxine – 1 if the patient is taking thyroid medication, 0 otherwise.
-  TSH Level – Thyroid-Stimulating Hormone level in the blood.
-  T3 Measured – 1 if T3 hormone was measured, 0 otherwise.
-  T3 Level – The level of Triiodothyronine (T3) hormone.
-  TT4 Level – Total Thyroxine (T4) hormone level
 
