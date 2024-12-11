
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
- Modifiy the dataset loading path in the script if necessary.

## License
This project is licensed under the MIT License.

## Author
Developed by 이명건
