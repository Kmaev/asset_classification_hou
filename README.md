# asset_classification_hou
This repository provides an example of asset classification in Houdini using Logistic Regression. The aim is to demonstrate how machine learning models can be integrated into the 3D asset creation pipeline for automated classification tasks.

Process:

    Dataset Creation: I created a simple dataset consisting of 3D assets, 
    specifically a torus and a sphere, as a quick example. 
    These assets were selected to showcase how machine learning can differentiate between 
    simple geometries based on specific features (e.g., shape, size, etc.).

    Model Training: I trained a Logistic Regression model from the scikit-learn library 
    to classify the assets. The training data was labeled manually with the corresponding 
    asset types (torus, sphere).

    Feature Engineering: Basic features like object dimensions and geometric properties 
    were used to train the model. In a real-world scenario, more complex features such as texture,
    surface area, or topology could be integrated.

    Model Evaluation: The performance of the model was evaluated on a validation set. 
    The accuracy of the classification model was measured, and potential areas of improvement were identified.

Technologies Used:

    Houdini: For asset creation and 3D geometry manipulation.
    Python & scikit-learn: For machine learning and logistic regression modeling.

