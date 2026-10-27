# ML Network Intrusion Detector

**Student:** Amal Johnson  
**Project:** IBM SkillsBuild Cyber Security BootCamp 2026  
**Suggested Topic #6:** ML Network Intrusion Detector — Built a Scikit-learn model to classify network anomalies using public datasets.

## What this project does

This is a Python/Jupyter Notebook cybersecurity project. It uses the public **NSL-KDD** dataset and classifies network connections into:

- **0 = Normal**
- **1 = Attack**

It trains and compares:

1. Logistic Regression
2. Random Forest

It also produces accuracy, precision, recall, F1-score, a confusion matrix, feature importance, and a sample prediction.

## Files

- `AmalJohnson_MLNetworkIntrusionDetector.ipynb` — main Python/Jupyter project
- `requirements.txt` — required Python libraries
- `AmalJohnson_MLNetworkIntrusionDetector_ProjectReport.docx` — project report
- `README.md` — project instructions

## Running in Google Colab

1. Open Google Colab.
2. Upload `AmalJohnson_MLNetworkIntrusionDetector.ipynb`.
3. Tap **Connect**.
4. Run the code cells from top to bottom.
5. The notebook automatically downloads the NSL-KDD data.

If the dataset download fails, the notebook shows a clear error instead of producing confusing errors in later cells.

## Dataset

NSL-KDD is a commonly used public benchmark dataset for network intrusion-detection research. The standard `KDDTrain+.txt` and `KDDTest+.txt` files contain 41 network features plus an attack label and difficulty field.

Dataset information:
https://www.unb.ca/cic/datasets/nsl.html

A current public mirror is used only to download the dataset during notebook execution.

## Important

The model is an educational prototype. It should not be treated as a complete production intrusion-detection system.
