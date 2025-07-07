This code was developed for the WiDS Datathon 2025 competition (link) to predict ADHD outcomes and sex in children. The dataset was relatively small (around 1,200 samples) but extremely high-dimensional, with over 19,000 features, making it prone to overfitting. Interestingly, our model showed signs of underfitting, especially for the female gender, likely due to class imbalance and limited representation.

To address the imbalance and ensure the model saw all available data, we applied techniques like stratified K-Fold cross-validation with downsampling, which helped balance the training process across folds. We also tuned decision thresholds to improve F1 score on the imbalanced labels. Overall, our pipeline was designed with caution to handle the complexity and sparsity of the data effectively.

![image](https://github.com/user-attachments/assets/c18c5f5e-7ea7-43c6-9088-544298df88fe)
