# Semiconductor Manufacturing Process - Yield Prediction

## Project Overview
This project aims to build a machine learning classifier to predict the pass/fail yield of semiconductor manufacturing process entities. Given the high-dimensional sensor data, we will explore feature selection techniques to identify the most relevant signals and improve model efficiency.

## Dataset
- **File:** `sensor-data.csv`
- **Size:** 1567 rows × 592 columns
- **Features:** 591 sensor signal variables
- **Target Column:**
  - `-1` → Pass
  - `1` → Fail
- **Objective:** Identify key signals impacting yield prediction and build an optimized classifier.

## Project Workflow
1. **Data Preprocessing:**
   - Handle missing values, outliers, and noise.
   - Normalize/standardize features if required.
2. **Exploratory Data Analysis (EDA):**
   - Identify feature importance and correlation.
   - Visualize data distributions and patterns.
3. **Feature Selection:**
   - Apply statistical and ML-based techniques to select relevant features.
4. **Model Development:**
   - Train and evaluate different classifiers (e.g., Logistic Regression, Random Forest, SVM, Neural Networks).
5. **Performance Evaluation:**
   - Compare models using accuracy, precision, recall, F1-score.
   - Optimize hyperparameters for the best-performing model.
6. **Deployment & Insights:**
   - Interpret key features impacting yield.
   - Generate a streamlined model for production use.

## Technologies Used
- **Programming Language:** Python
- **Libraries & Frameworks:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, TensorFlow/PyTorch (if deep learning is used)

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/Bhavani-Bhaskar/major_proj_ds.git
   cd major_proj_ds
   ```

## Results & Insights
- The feature selection process helps reduce computation time while maintaining model accuracy.
- Important signals affecting yield can be analyzed and shared with process engineers for process optimization.

## Contributors
- [Bhavani Bhaskar](https://github.com/Bhavani-Bhaskar)

## License
This project is licensed under the MIT License.

---
Feel free to contribute by submitting issues and pull requests!

