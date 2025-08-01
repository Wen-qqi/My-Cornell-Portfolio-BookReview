# Book Review Machine Learning Model

For my final project for Break Through Tech AI Machine Learning Foundations Course, I built a sentiment analysis model to classify book reviews as either positive or negative, using the review text as the main feature. This binary classification problem helps determine the overall tone of customer feedback. The model can add value for companies by identifying which books are well-received, enabling better recommendation systems. For example, books with positive reviews can be promoted to more users, while readers who leave favorable feedback can be recommended similar titles or other works by the same author. This approach supports personalized marketing, improves user engagement, and provides insights into customer preferences.

* Tools: Python, Pandas, scikit-learn, TensorFlow, Matplotlib, Keras, Jupyter Notebook

# Analysis

This version of the model appears to be the most balanced and generalizable. The test results showed 80% accuracy with a loss of 0.472, which indicates a reasonably good performance. I experimented with various hyperparameters and model adjustments, including adding regulazations, dropout layers, earlystopping, ReducedLROnPlateau, and removing a hidden layer.

While these changes did not significantly improve accuracy, they did helped reduce the loss. Based on the results, I believe the model has no major overfitting issues and should generalize relatively well to new and unseen data. However, I do think there is still room for improvement, potentially by tuning the hyperparameters more precisely and using different models. 
