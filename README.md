

---

# Sales Forecasting

This project applies **Artificial Intelligence** to enhance sales forecasting methods through predictive analysis. Using machine learning techniques like **Random Forest** and **XGBoost**, this approach aims to help businesses forecast sales more accurately, optimize strategies, and effectively manage resources in response to market trends.

## Overview

Accurate sales forecasting is critical for businesses to predict revenue and make informed decisions. Traditional methods often rely on a single analysis type, which can limit accuracy. By integrating advanced machine learning models, this project improves the reliability of sales predictions, offering a more comprehensive forecasting approach.

## Dataset

The project uses the **BigMart** dataset, an open-source dataset that includes multiple attributes influencing sales:

- **Item Type**
- **Outlet Type**
- **Item MRP** (Maximum Retail Price)
- Additional sales-related factors

This dataset undergoes cleaning and pre-processing to ensure high-quality data for training the models.

## Models Used

Two powerful machine learning models were implemented for sales forecasting:

- **Random Forest:** A popular ensemble method that builds and merges multiple decision trees to improve accuracy and prevent overfitting.
  
- **XGBoost:** A fast and optimized gradient boosting algorithm that enhances prediction accuracy and performance using advanced tree-based models.

## Model Performance

After training, the models' performance was evaluated using **R-squared values**:

- **XGBoost:** 0.7456
- **Random Forest:** 0.7426

These results indicate that **XGBoost** slightly outperforms **Random Forest** in predicting sales, demonstrating its effectiveness for accurate forecasting in business applications.

## Installation & Setup

To run this project locally, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/sales-forecasting.git
   ```
2. **Navigate into the project directory:**
   ```bash
   cd sales-forecasting
   ```
3. **Install dependencies:**
   If you don’t have the necessary libraries, install them using pip:
   ```bash
   pip install -r requirements.txt
   ```
4. **Download the dataset:**
   The dataset can be downloaded from [BigMart Dataset](#). Make sure to place the dataset in the appropriate directory.

## Usage

To train the models and make predictions, run the following command:
```bash
python sales_forecasting.py
```
This will execute the training process and output the model performance, including the R-squared values for both **XGBoost** and **Random Forest**.

## License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for further details.

---

