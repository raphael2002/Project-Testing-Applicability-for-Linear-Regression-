# Project-Testing-Applicability-for-Linear-Regression-using machine learning algorithms
# About the Project:
The popular TV show "Sole Survivor" drops participants alone into remote areas to test their survival skills. They are then given ratings based on areas such as physical fitness and mental toughness. 
# Objective: 
To determine the accuracy and validity of the survival scores assigned by specialists to contestants using linear regression analysis.
Predicting next season's winners using the  sole survivor next dataset.
# Dataset:
The dataset contains the following columns:
Name
Leadership
MentalToughness
SurvivalSkills
RiskTaking
Resourcefulness
Adaptability
PhysicalFitness
Teamwork
Stubbornness
SurvivalScore
# Methodology:
* Data Preparation:
  Extracted predictor variables after analyzing heatmap: SurvivalSkills, PhysicalFitness, Adaptability, Stubbornness
  Response variable: SurvivalScore.
* Model Fitting:
  Split the data into training (80%) and testing (20%) sets.
  Fitted a linear regression model using the training data.
* Model Evaluation:
    Evaluated the model using Mean Squared Error (MSE) and R-squared metrics.
    Conducted residual analysis to check the model assumptions.
# Results:
* Mean Squared Error (MSE):
  The MSE was 6.021, which is relatively high, indicating that the model's predictions are not close to the actual SurvivalScores.
* R-squared:
  The R-squared value was 0.5, which is less than 0.7, suggesting that the model does not explain a significant portion of the variance in Survival Scores.
* Residual Analysis:
  If we look at the residual qq plot, we see the imperfect alignment.
# Conclusion:
Based on the linear regression analysis, it appears that the survival specialists are "not" scoring the contestants well. The low R-squared value suggests that the SurvivalScores are not consistent with the contestants' attributes. The high MSE further supports the inaccuracy of the scores.
# Predicting Next Season's Winners
Finally, performed linear regression on next season's participants using sole survivor past data and predicted their survival scores. Predicted the top 3 participants most likely to win next season and their predicted scores. 

Note: This project was built as part of a learning journey and is intended for demonstration only.
