# 🚢 Titanic Dataset - Data Cleaning & Preprocessing
This project demonstrates the complete preprocessing pipeline applied to the Titanic dataset. The goal is to clean raw data and prepare it for machine learning using Python and popular data science libraries.

# 📌 Objectives
Explore and understand raw Titanic dataset
Handle missing values and outliers
Convert categorical variables into numeric
Normalize and standardize numerical features
Prepare clean data for ML modeling

# 🛠️ Tools & Libraries Used
Python
Pandas
NumPy
Matplotlib & Seaborn (for visualization)
Scikit-learn (for encoding and scaling)

# 🧪 Steps Performed
Import Dataset & Libraries
Load Titanic CSV
View basic structure and summary statistics
Handle Missing Values
Fill Age with median
Fill Embarked with mode
Drop Cabin column (too many missing values)
Drop Irrelevant Columns
Removed Name and Ticket due to high cardinality
Encode Categorical Variables
Applied one-hot encoding on Sex and Embarked
Normalize/Standardize Numerical Features
Standardized Age, SibSp, Parch, Fare using StandardScaler
Visualize and Remove Outliers
Used boxplots to identify outliers
Removed outliers using Interquartile Range (IQR)
Save Cleaned Dataset
Final dataset saved as Titanic_Cleaned.csv

# 📁 File Structure

├── Titanic-Dataset.csv         # Original dataset
├── Titanic_Cleaned.csv         # Cleaned dataset (output)
├── data_cleaning_titanic.py    # Main preprocessing script
├── README.md                   # Project documentation
# 📷 Sample Output (Boxplot)
Example visualizations created for outlier detection.



# ✅ Requirements
Install all required libraries with:
pip install pandas numpy matplotlib seaborn scikit-learn

# 🚀 Run the Code

python data_cleaning_titanic.py
# 📬 Contact
For any queries or collaboration, feel free to reach out:

# Subodh Kanoujiya
# 📧 [subodhkanoujiya4@gmail.com]
# 🌐 GitHub: github.com/subodhkanoujiya4
