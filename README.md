# Housing Price Prediction

This project uses machine learning models to predict annual housing prices based on various features. The dataset and implementation demonstrate data preprocessing, feature engineering, and model training, including a neural network and other machine learning techniques.

## Dataset

The dataset used for this project is hosted on Google Drive. You can download it using the link below:

- **[Download Dataset](https://drive.google.com/drive/folders/12Rywce6HK8wlXVjM4ds2qahWf_taugYJ?usp=drive_link)**

### Dataset Overview
The dataset contains the following features:
- **LivingSqFt**: Square footage of the living area.
- **RoomsNbr**: Number of rooms in the property.
- **Med.Income**: Median income of the area.
- **Perc_18**: Percentage of the population under 18.
- **Price.Annual**: Target variable representing the annual housing price.

---

## Features of the Project

### Key Steps:
1. **Data Preprocessing**:
   - Feature scaling using `StandardScaler`.
   - Feature engineering with interaction terms like `RoomSize_Avg` and `Income_Percentage`.
   - Handling missing values and removing highly correlated features.

2. **Machine Learning Models**:
   - Random Forest Regressor with hyperparameter tuning using `GridSearchCV`.
   - Neural Network for regression using TensorFlow/Keras.

3. **Evaluation Metrics**:
   - **Mean Absolute Error (MAE)** for measuring model performance.
   - **R² Score** to evaluate the model's ability to explain variance.

4. **Model Saving and Deployment**:
   - Models are saved using `joblib` and `TensorFlow` for reuse without retraining.

---

## Requirements

To run this project, ensure you have the following installed:
- Python 3.7+
- TensorFlow
- Scikit-learn
- Pandas
- NumPy
- Matplotlib

Install dependencies using:
```bash
pip install -r requirements.txt
