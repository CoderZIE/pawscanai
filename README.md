# PawscanAI

## Coding Task Summary

### Approaches Used:

1. **Decision Tree:**
   - Achieved an accuracy of 74%.
   - Decision trees are known for their interpretability and ease of understanding the decision-making process.

2. **Deep Neural Network (DNN) Classifier:**
   - Utilized a DNN with 4 hidden layers having neurons arranged as (128, 64, 32, 16).
   - Used ReLU activation function and cross-entropy loss.
   - Despite these settings, the model did not yield satisfactory results.

3. **Random Forest Classifier:**
   - Achieved an accuracy of 82.83% comparable to highest accuracy of 84.179%.
   - Implemented from scikit-learn, which provided the best results among the methods tested.
   - Random forests are ensemble methods that combine multiple decision trees to improve accuracy and robustness.

### Dataset Cleaning and Preparation:
- Removed the 'id' column from the dataset.
- Eliminating non-essential features like 'id' helps in preventing overfitting and focuses the model on relevant data for classification in academic datasets.

### Conclusion:
Due to time constraints, further in-depth analysis and feature engineering were not fully explored. Dataset understanding and cleaning are important steps that can  impact model performance and give insights from ML tasks.
