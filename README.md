1. The main objective of this work is to build a classification model to predict failure of the pump using sensor data.

2. As per industry standard, I have dropped the columns having missing values more than 40%.

3. The columns which have correlation value of at least 0.1 were selected for the modelling.

4. Sensor values were standardized to a common scale to ensure features with larger numeric ranges did not dominate model learning.

5. Target variable has been defined like is defined as a binary indicator that equals 1 if the machine enters an abnormal status at any time within the next 15/30/ 60 minutes, and 0 otherwise.

6. Logistic Regression : Train AUC-ROC  - 88% Test AUC-ROC - 83%

7. Random Forest : Train AUC-ROC  - 96% Test AUC-ROC - 94%

