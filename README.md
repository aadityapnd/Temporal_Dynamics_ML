# Data Driven Modeling of Temporal Dynamics using Machine Learning

This repository contains a **Jupyter Notebook** with code implementations for all cases demonstrated in the research paper:

> **"Data Driven Modeling of Temporal Dynamics using Machine Learning: Application to Gas Turbine Generators"**

submitted to the **North American Power Symposium (NAPS) 2025**.

## 📓 Notebook Details

- `apande26.ipynb`

The notebook includes:

- Data loading and preprocessing
- Feature engineering with **lagged voltage sequences and power outputs**
- Random Forest model training and evaluation
- Plots of **Validation RMSE** and **Test RMSE** vs. input parameters

## 💡 Problem Statement

The primary objective of this research is to employ a non-parametric and computationally efficient method, namely the Random Forest Regressor, for predicting the dynamic power output of a gas turbine engine generator, utilizing a sequence of time-series endogenous and exogenous features as inputs. Additionally, this research aims to explore novel approaches to improve the Random Forest model's performance, with the goal of achieving a low Root Mean Squared Error (RMSE).

## 📊 Results

The notebook generates plots showing how **RMSE varies with different sequence lengths of endogenous and exogenous variables**, helping analyze model performance.

## ⚙️ Requirements

- Python >= 3.7
- Jupyter Notebook
- numpy
- pandas
- scikit-learn
- matplotlib
- seaborn

### 🔧 To install dependencies:
pip install jupyter numpy pandas scikit-learn matplotlib seaborn

## 🚀 Running the notebook

1. Clone this repository:
    ```
    git clone https://github.com/aadityapnd/Temporal_Dynamics_ML.git
    ```
2. Navigate to the directory:
    ```
    cd Temporal_Dynamics_ML.git
    ```
3. Launch Jupyter Notebook:
    ```
    jupyter notebook
    ```
4. Open `apande26.ipynb` and run all cells.

## 📁 Data

The required data files are included in the repository under the `data/` folder.

## ✏️ Author

- **Name:** Aaditya Pandey
- **Email:** apande26@ncsu.edu
- **Affiliation:** FREEDM Systems Center, NCSU

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---


