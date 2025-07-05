Task 7: Support Vector Machines (SVM)

🔥 Objective

Use Support Vector Machines (SVM) for binary classification on the Breast Cancer dataset. Perform hyperparameter tuning and evaluate performance.


---

🗂 Dataset

Name: Breast Cancer Dataset

Source: sklearn.datasets.load_breast_cancer()

Features: 30 numerical features about tumor characteristics

Target: Malignant (0) or Benign (1)



---

⚙ Steps Performed

1️⃣ Loaded and prepared the dataset.
2️⃣ Scaled features using StandardScaler.
3️⃣ Split the data into training and testing sets.
4️⃣ Trained SVM with linear kernel and evaluated accuracy.
5️⃣ Trained SVM with RBF kernel.
6️⃣ Tuned hyperparameters (C and gamma) for the RBF kernel.
7️⃣ Achieved test accuracy of ~98% with tuned parameters.
8️⃣ (Optional) Cross-validation used to further evaluate performance.


---

✅ Results

Linear kernel test accuracy: Good, but slightly lower than RBF.

RBF kernel test accuracy (tuned): ~98.25%
