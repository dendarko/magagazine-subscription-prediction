
# Magazine Subscription Prediction

This project analyzes and predicts customer subscription behavior for a magazine company using machine learning models, including Logistic Regression and Support Vector Machines (SVM). The goal is to understand the factors driving subscription behavior and recommend a model for the company to use in future strategies.

## Project Files

- **Notebook**: [Structured_Understanding_Subscription_Behavior.ipynb](./Structured_Understanding_Subscription_Behavior.ipynb)
- **Paper**: [Magazine_Subscription_Paper.pdf](./Magazine_Subscription_Paper.pdf)

## Key Steps

1. **Data Cleansing and Feature Engineering**: We cleaned the dataset and created new features such as `Customer_Tenure` to better capture customer loyalty.
2. **Multicollinearity Handling**: Removed highly collinear features using Variance Inflation Factor (VIF) analysis to ensure model stability and interpretability.
3. **Model Building**: Developed Logistic Regression and SVM models to predict whether a customer will subscribe.
4. **Fine-Tuning**: Fine-tuned both models using Grid Search for hyperparameter optimization.
5. **Model Comparison**: Compared the performance of both models and made a final recommendation based on key metrics such as accuracy, precision, and recall.

## Results

- **Logistic Regression**: 88% accuracy, precision of 0.71, and recall of 0.36 for predicting subscriptions.
- **SVM**: 87% accuracy, precision of 0.73, and recall of 0.28 for predicting subscriptions.
  
The **Logistic Regression** model is recommended due to its better balance between precision and recall and its interpretability.

## Setup Instructions

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/your-username/magazine-subscription-prediction.git
   ```
2. Navigate into the project directory:
   ```bash
   cd magazine-subscription-prediction
   ```
3. Install the required dependencies (if applicable, you can include a `requirements.txt` file):
   ```bash
   pip install -r requirements.txt
   ```
4. Run the Jupyter notebook to explore the project and replicate the results:
   ```bash
   jupyter notebook Structured_Understanding_Subscription_Behavior.ipynb
   ```

## Authors

- Pinkesh Tandel
- Dennis Darko

## Course

- ALY6020: Predictive Analytics
- Northeastern University, College of Professional Studies, Vancouver, BC, Canada
- Under the guidance of Dr. Nina Rajabi Nasab

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
