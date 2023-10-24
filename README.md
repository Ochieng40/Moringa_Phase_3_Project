# Moringa_Phase_3_Project

**Overview**:
In this project, we've focused on developing classification models to predict customer churn for SyriaTel, a telecommunications company. Churn prediction is crucial for businesses as it helps them identify customers at risk of leaving and take proactive measures to retain them. Our goal was to explore whether there are predictable patterns in the data that can help SyriaTel reduce customer churn and the associated financial losses.

**Business and Data Understanding:**
Understanding customer churn is vital for telecom companies like SyriaTel. It means that customers are leaving for competitors, and this can have significant financial implications. Our analysis started with a deep dive into the data, examining various features such as account length, international plan, voice mail plan, and more. We looked for patterns and relationships that could help us predict churn.

**Modeling**:
We built three different classification models: Logistic Regression, Random Forest, and a Tuned Random Forest. These models were chosen because they are well-suited for binary classification tasks. While the technical details of model implementation aren't necessary for a non-technical audience, what's important is that we used these models to predict whether a customer is likely to churn or stay with SyriaTel.

**Evaluation**:
We evaluated the models using various metrics, such as accuracy, precision, recall, and F1-score. These metrics help us understand how well the models are performing. For example, accuracy tells us the percentage of correct predictions, while precision tells us how many of the positive predictions are accurate. Recall informs us about the percentage of actual positive cases the model correctly predicted. The F1-score is a balance between precision and recall. For specific numbers, you can refer to the respective sections for each model.

**Recommendations**:
Based on our analysis, we found that the Random Forest model and the Tuned Random Forest model performed the best in terms of accuracy, precision, recall, and F1-score. This means they are effective in predicting customer churn. For SyriaTel, this means they can use these models to identify customers at risk of leaving and take targeted actions to retain them. For instance, they can offer discounts, improve customer service, or provide personalized incentives to keep customers satisfied.

**Next Steps**:
Moving forward, it's important to implement these models in a real-world environment. SyriaTel should integrate them into their customer management systems to make real-time predictions. Additionally, they can further improve the models by collecting more data and refining their features. Continuous monitoring of model performance is also essential to ensure they remain effective in the ever-changing telecommunications landscape.

**Features that are Important in Predicting Target Variable**
From the feature importance analysis, we can infer that several features related to call usage, such as total day charge and total day minutes, are highly influential in predicting churn. Additionally, the number of customer service calls appears to be a critical factor contributing to customer churn. This insight suggests the importance of focusing on these aspects to reduce churn rates.

	total day charge: 0.1368
	total day minutes: 0.1346
	customer service calls: 0.1180
	international plan: 0.0810
	total eve minutes: 0.0676
	total eve charge: 0.0619
	total intl calls: 0.0491
	total intl minutes: 0.0455
	total intl charge: 0.0443
	total night charge: 0.0391
	total night minutes: 0.0377
	total day calls: 0.0332
	total night calls: 0.0330
	account length: 0.0315
	number vmail messages: 0.0294
	total eve calls: 0.0289
	voice mail plan: 0.0200
	area code: 0.0085

![image](https://github.com/Ochieng40/Moringa_Phase_3_Project/assets/110474885/bc1079c6-d84f-436c-8f7e-de856b539c6b)


