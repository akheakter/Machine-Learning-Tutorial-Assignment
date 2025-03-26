# Air Quality Classification Project

This project employs a **Support Vector Machine (SVM)** classifier to predict air quality based on pollutant levels from the `city_day.csv` dataset. Written in Python, it’s optimized for **Google Colab**.

---

## Dataset

- `city_day.csv`: Daily air quality data with pollutants like `PM2.5`, `PM10`, `NO2`, `CO`, etc.
- Classifies air quality as **Good** (`1`, `PM2.5 ≤ 50`) or **Poor** (`0`, `PM2.5 > 50`).

---

## Prerequisites

- Google account for Colab access.
- `city_day.csv` file available for manual upload.
- Basic Google Colab and Python knowledge.

---

## How to Run in Google Colab

### 1. Open Google Colab
- Visit [Google Colab](https://colab.research.google.com/), sign in, and create a new notebook (**File > New Notebook**).

### 2. Upload the Code
- Click **`+ Code`**, paste the full code (including SVM sections) into the cell.

### 3. Upload the Dataset
- Download `city_day.csv` from GitHub: [https://github.com/akheakter/Machine-Learning-Tutorial-Assignment/blob/main/city_day.csv](https://github.com/akheakter/Machine-Learning-Tutorial-Assignment/blob/main/city_day.csv).
- Upload it manually to Colab:
  - Click the **Files** tab on the left panel.
  - Click **Upload** and select the downloaded `city_day.csv` from your local machine.
- The code assumes the file is in `/content/city_day.csv` (default Colab path).

### 4. Install Required Libraries
- Run: `!pip install pandas numpy scikit-learn matplotlib seaborn` (optional, pre-installed in Colab).

### 5. Run the Code
- Click **Run** or press **`Shift + Enter`** to execute.

---

## Outputs

- First few rows of the dataset
- Dataset info
- Training set shape
- Testing set shape
- SettingWithCopyWarning (optional)
- Pairplot visualization
- Best parameters from GridSearchCV
- Best cross-validation score
- Training accuracy
- Testing accuracy
- Confusion matrix plot
- Scatter plot of PM2.5 vs NO2 with predictions
- Feature importance bar plot (if linear kernel) or message (if non-linear kernel)
