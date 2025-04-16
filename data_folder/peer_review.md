# Peer Review for: Justin

Peer Review by: Kersha Broussard

My GitHub Repository: https://github.com/kersha0530/ml_regression_kbroussard 

My README.md: https://github.com/kersha0530/ml_regression_kbroussard/blob/main/README.md 

My Notebook: https://github.com/kersha0530/ml_regression_kbroussard/blob/main/regression_kbroussard.ipynb

My Peer Review: https://github.com/kersha0530/ml_regression_kbroussard/blob/main/data_folder/peer_review.md

Notebook I Reviewed: https://github.com/SchroderJ-pixel/ml-06-medical-cost/blob/main/regression_schroder.ipynb



### 1. Clarity & Organization  
Justin’s notebook is structured clearly, with clean code blocks, section labels, and informative comments. The reflections are present and thoughtfully written. The visualizations are well spaced and contribute meaningfully to the story. 



### 2. Feature Selection & Justification  
The features selected (like BMI, smoking status, age, and region) are highly relevant to medical cost predictions. Feature engineering was done well with proper one-hot encoding and scaling. 



### 3. Model Performance & Comparisons  
Multiple models were evaluated, including Linear and Polynomial Regression. Performance metrics like R² and RMSE were clearly shown, and the comparisons between pipeline versions were insightful. 



### 4. Reflection Quality  
Justin’s reflections were thoughtful and honest—especially his comment about becoming more confident in Python and loving Jupyter. The challenges and suggestions he shared could be helpful for future students. 



###  Final Comments
Excellent work, Justin! The overall project is professional and well-documented. If you'd like to take it further, you might try experimenting with Ridge Regression or adding more interpretability plots like SHAP or Partial Dependence.

* SHAP (SHapley Additive exPlanations) is a method for interpreting the predictions of machine learning models. It's based on game theory and helps answer the question:

“Which features had the biggest impact on this specific prediction?”

* Partial Dependence Plots show how the model’s predictions change when one or two features vary, while all other features are held constant. Useful for identifying non-linear relationships.

It answers:

“What happens to the prediction if we increase age while keeping everything else fixed?”

Tool | Best For | Shows...
SHAP | Individual prediction insights | Feature contribution to each prediction
Partial Dependence | Global trend analysis | How target prediction changes with a feature

