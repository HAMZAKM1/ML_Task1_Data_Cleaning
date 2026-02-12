# ML Task 1: Data Cleaning & Preprocessing

## Objective
Learn how to clean and prepare raw data for Machine Learning models.

## Dataset
- **Source:** Titanic dataset
- **File:** `train.csv`

## Steps Performed
1. **Exploratory Data Analysis (EDA)**:  
   - Checked data types, null values, and descriptive statistics.
2. **Handling Missing Values**:  
   - Filled numerical columns (`Age`) with median.
   - Filled categorical columns (`Embarked`) with mode.
   - Dropped columns with too many missing values (`Cabin`) and irrelevant ones (`Name`, `Ticket`, `PassengerId`).
3. **Encoding Categorical Variables**:  
   - Converted `Sex` and `Embarked` to numerical values using Label Encoding.
4. **Feature Scaling**:  
   - Standardized numerical features (`Age`, `Fare`, `SibSp`, `Parch`) using `StandardScaler`.
5. **Outlier Detection and Removal**:  
   - Used IQR method and visualized using boxplots.
6. **Data Visualization**:  
   - Plotted survival counts and correlation heatmap.
7. **Final Dataset**:  
   - Cleaned, encoded, scaled, and ready for ML modeling.

## Tools Used
- Python, Jupyter Notebook
- Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

## How to Run
1. Clone the repository.
2. Open `Task1_Data_Cleaning.ipynb` in Jupyter Notebook.
3. Ensure `train.csv` is in the correct path.
4. Run all cells sequentially.
