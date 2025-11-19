💓 AI-Powered Heart Disease Risk Detection (with OCR Integration)

An end-to-end intelligent system designed to analyze medical data, extract clinical values from medical reports, and prepare a complete ML-ready pipeline for predicting heart disease risk.
Built with real datasets, OCR, feature engineering, and scalable data processing.

🚀 Project Overview

This project aims to support early detection of heart disease by combining:

Clinical dataset analysis

Machine learning preprocessing

OCR-based medical report extraction

The system cleans raw heart disease datasets, reads medical PDFs/images, extracts numeric health indicators, and prepares fully processed data for predictive modeling.

🧠 Key Features

✔ OCR pipeline using Tesseract + OpenCV
✔ Medical PDF/image preprocessing
✔ Automatic text extraction & value parsing
✔ Complete data cleaning workflow
✔ Handling missing values & outliers
✔ Feature engineering (risk score, normalization, encoding)
✔ Train/Validation/Test split
✔ Ready for model training (Milestone 2)

🗂 Project Structure
📁 heart-disease-ocr-ml
 ├── data/
 │   ├── raw/          # Unprocessed datasets
 │   └── processed/    # Cleaned datasets
 ├── ocr_samples/      # Medical PDFs/images
 ├── notebooks/        # Colab notebooks
 ├── models/           # For training models (Milestone 2)
 ├── README.md
 └── requirements.txt

📊 Technologies & Libraries

Python 3.x

Pandas, NumPy, Scikit-learn

OpenCV, pytesseract, pdf2image

Matplotlib, Seaborn

Google Colab + Drive Integration

🔍 OCR Flow

Convert PDF pages to images

Preprocess (denoise, threshold) using OpenCV

Extract text with Tesseract

Parse key medical values (BP, Cholesterol, etc.)

Add extracted values to dataset

🧹 Data Preprocessing Steps

Missing value imputation

Handling major missing columns

Outlier removal

Normalization & Standardization

Categorical encoding

Derived feature creation

Dataset splitting

📈 Deliverables Achieved (Milestone 1)

✔ Clean, structured dataset
✔ OCR text extraction system
✔ End-to-end preprocessing pipeline
✔ EDA insights & feature summary
✔ Ready for model development

🛠 Next Steps (Milestone 2)

Train ML models (Logistic Regression, Random Forest, XGBoost)

Evaluate using accuracy, F1, ROC-AUC

Hyperparameter tuning

Save model in models/ directory

Build API or UI integration

🤝 Contributions

Contributions, issues, and suggestions are welcome!
Feel free to open a pull request or raise an issue.

📬 Contact

For queries or collaboration:
Sohan Kondass
📧 sohank1866@gmail.com

🌐 GitHub: https://github.com/Sohan-Kondas
