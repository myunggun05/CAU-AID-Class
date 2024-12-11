
# Usage

1. Run the script:
   ```bash
   python knn_iris_classifier.py
   ```
2. Enter the number of neighbors(`k`) when prompted.
3. View the model's accuracy and balanced accuracy in the console.
4. Input `sepal.length' and `petal.length` in the format `vlaue1, value2` to predict the iris species.

# Example
## Console Interaction:
```bash
Enter the number of neighbors (k) for KNN: 3
Model Accuracy: 0.96
Balanced Accuracy: 0.95
Enter the sepal. length and petal.length for the iris in the format 'sepal_length, petal_length': 5.1, 1.8
Predicted Label: Virginica
```

## Notes
- Ensure that the input for predictions is numeric and follows the correct format(`value1, vlaue2`).

## Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/CAU-AID-Class.git
   ```
2. Navigate to the project directory:
   ```bash
   cd CAU-AID-Class
   ```
3. Install required libraries:
   ```bash
   pip install pandas scikit-learn
   ```
4. Ensure the `iris.csv` dataset is available in the project directory.
