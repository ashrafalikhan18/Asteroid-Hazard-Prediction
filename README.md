# About
Asteroids are small, rocky bodies that orbit the sun which are primarily found in the asteroid belt between Mars and Jupiter.Some asteroids are classified as near-Earth asteroids(NEO'S) if their orbits bring them close to the Earth’s orbit.
As a data scientist at NASA I am responsible for analyzing the dataset of near Earth objects (NEOs) to improve our comprehension of these entities and strengthen our defense strategies for planets. This dataset contains details about NEOs, such as their features like absolute brightness estimated size orbital traits and other relevant parameters.With the growing number of detected asteroids, there's an increasing need to classify these objects efficiently to prioritize monitoring and potential mitigation efforts.

#### Experiment Strategy:
- Developing a classification model to accurately predict whether an asteroid is potentially hazardous based on the given features. This classification will help NASA focus on the most threatening NEOs, ensuring efficient use of resources and timely action.
- Identifing which asteroids near Earth are dangerous to prioritize monitoring and actions.

### Steps:

    Data Exploration and Cleaning:
        Understanding features like size, speed, and orbit.
        Cleaning the data and handle any missing values.
    
    Model Selection:
        K-Nearest Neighbors (KNN): Simple and effective for classification.
        Decision Tree: Easy to interpret and handles complex relationships.
        
    Training and Evaluation:
        Train both models using a training dataset.
        Use cross-validation to test the models.
        Evaluate using accuracy, precision, recall, F1 score, and ROC-AUC, focusing on recall to avoid missing dangerous asteroids.
        
    Model Optimization:
        Fine-tune model parameters using grid search or random search.
        Combine models using ensemble methods if needed.

    Deployment:

        Implement the best-performing model into NASA's system.
        Continuously monitor and update the model with new data.

    Expected Benefits:
        Better detection of dangerous asteroids.
        Enhanced preparedness for potential asteroid impacts.
Conclusion:
By using KNN and Decision Tree models, NASA can improve its ability to identify and respond to asteroid threats, ensuring Earth's safety and advancing space monitoring technology.
