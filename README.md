# Predict Disease Outcome Based on Genetic and Clinical Data

This project uses machine learning to predict disease outcomes using genetic and clinical data provided in a CSV file. The model automatically detects the target column (assumed to be the last one), handles missing values, scales the features, and trains a Random Forest classifier. No manual input is required beyond uploading the dataset.

## Features
- Upload a CSV file with clinical/genetic data
- Automatically detects the target column (last column)
- Handles missing values and scales features
- Trains a Random Forest model
- Outputs accuracy and classification report

## Technologies Used
- Python
- scikit-learn
- pandas
- Google Colab

## Dataset Format
Ensure your dataset is in `.csv` format, with the target column as the last column.

Example:
| Age | GeneA | GeneB | BloodPressure | Outcome |
|-----|-------|-------|----------------|---------|
| 45  | 0.23  | 0.67  | 120            | 1       |
| 52  | 0.12  | 0.89  | 135            | 0       |

## Output
After training, the model will display:
- Accuracy score
- Precision, Recall, F1-score (classification report)

## How to Use
1. Open the notebook in Google Colab
2. Upload your dataset when prompted
3. The model will train and display results automatically

## License
This project is licensed under the MIT License.

## Contributing
Feel free to fork the repository and submit pull requests to improve the project or add new features.
