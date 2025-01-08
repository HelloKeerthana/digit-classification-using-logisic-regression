<h1>Digit Classification using Logistic Regression</h1>

<h2>Dataset</h2>
<p>The dataset used is the <strong>Digits dataset</strong> from <strong>sklearn.datasets</strong>. 
  It contains 8x8 pixel grayscale images representing digits (0 to 9). 
  Each image is flattened into a 64-dimensional vector, which is used as the feature set, and the corresponding digit label (0-9) serves as the target variable.</p>

<h2>Modules Used</h2>
<ul>
    <li><strong>sklearn.datasets</strong>: To load the Digits dataset.</li>
    <li><strong>sklearn.model_selection</strong>: For splitting the dataset into training and testing sets using <code>train_test_split</code>.</li>
    <li><strong>sklearn.preprocessing</strong>: For scaling the feature data using <code>StandardScaler</code>.</li>
    <li><strong>sklearn.linear_model</strong>: To apply Logistic Regression using <code>LogisticRegression</code>.</li>
    <li><strong>sklearn.metrics</strong>: For evaluating model performance, particularly accuracy using <code>accuracy_score</code>.</li>
    <li><strong>matplotlib.pyplot</strong>: For plotting the confusion matrix and model performance.</li>
</ul>

<h2>Process</h2>

<p>The dataset is loaded and then split into training and testing sets using <strong>train_test_split</strong>. 
  The features are standardized using <strong>StandardScaler</strong> to improve model performance.
  A <strong>Logistic Regression</strong> model is trained on the training data and evaluated using accuracy. 
  A confusion matrix is generated to visualize the classification performance.</p>

<h2>Output</h2>
<p>The output includes the accuracy of the model, and a confusion matrix plot showing how well the model classified each digit.</p>
