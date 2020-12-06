Industry Review

An education company ‘X Education’ sells online courses to people from different occupations. It markets its courses on several websites and search engines like Google. Once these people land on the website, they browse the courses or fill up a form for the course or watch some demo videos. When these people fill up a form providing their email address or phone number, they are classified to be a Lead. 

Companies often gather a tremendous amount of data, such as browsing behaviour, email activities, and other contact data. This data can be the source of important competitive advantage by utilizing it in estimating a contact's purchase probability using predictive analytics. When leads are acquired, employees from the sales team start making calls, writing emails, etc. Through this process, some of the leads get converted while most do not. Companies often gather a tremendous amount of data, such as browsing behaviour, email activities, and other contact data.

To increase the efficiency in tracking hot leads we will apply machine learning. Here, machine learning can be used to perform lead scoring as a special application case of purchase probabilities and approaching a possible lead who purchases the product. Historical behavioural data is used as training data for the classification algorithm.

SCOPE: A calculated purchase probability is used by companies to solve different business problems, such as optimizing their sales processes and going about approaching the hot leads. This data can be the source of important competitive advantage by utilizing it in estimating a contact's purchase probability using predictive analytics.

Project Justification
Project Statement: An education company ‘X Education’ sells online courses to people from different occupations. It markets its courses on several websites and search engines like Google. Once these people land on the website, they browse the courses or fill up a form for the course or watch some demo videos. When these people fill up a form providing their email address or phone number, they are classified to be a Lead. When leads are acquired, employees from the sales team start making calls, writing emails, etc. Through this process, some of the leads get converted while most do not. The typical lead conversion rate at X education is around 30%. We aim at increasing this Lead Conversion rate.

Complexity involved: A business might have many potential customers leads but most of those customers will not turn into actual, paying customers in the end. A sales team must sort through a long list of potential customers and figure out how to spend their time. That is where lead scoring comes in. This is a system that analyses attributes about each new lead in relation to the chances of that lead becoming a customer and uses that analysis to score and rank all of the potential customers. With that new ranking, the sales team can then prioritize their time, and only spend time on the leads that are highly likely to become paying customers.

Project Outcome: Companies often gather a tremendous amount of data, such as browsing behaviour, email activities, and other contact data. A Machine Learning Model which gives the calculated purchase probability based on the data available can be used by companies to solve different business problems, such as optimizing their sales processes and going about approaching the hot leads and converting them to a customer. It is a highly valued process in marketing of sales products

Models used-
1) Logistic Regression
2) Naive bayes
3)Decision Tree
4) Random Forest
5)Gradientboost
6)AdaBoost

Summary: 

In this project, we aim to analyze the different attributes affecting the hot leads into conversion by building a
predictive model and scoring the predicted outcome. We used X education data to perform the experiments necessary. In order to predict the conversion of hot leads, we used the data such as specialization, total_visits, lead_source, occupation, ,lead_quality, lead_origin and other features as input to many machine learning algorithms we gave a try at and selecting the best model.

Feature extraction and feature importance are applied on base models first. Although we have done exhaustive EDA and Feature Engineering to reduce redundant information. After feature engineering and feature extraction pre-processing techniques, hyperparameter tuning is applied to improve the success rates and scalability of the algorithms. Considering the real time usage of the proposed system, achieving better or similar classification performance with minimal subset of features is an important factor for better ML modelling.

For model evaluation we have used a confusion matrix. A confusion matrix is a table that is often used to describe the performance of a classification model (or "classifier") on a set of test data for which the true values are known.
We have given more importance to Recall score as the significance of False Negative is high i.e., we don’t want to miss any lead who is a potential buyer, but our model has classified as negative

After evaluating the base model, we tried to improve the accuracy of our model using feature selection and some complex Algorithms. Feature selection is a process where you automatically select those features in your data that contribute most to the prediction variable or output. The findings show that removing some less important features and owning of business results in a more accurate and scalable system. Therefore, we applied Select KBest, SFS, RFE method.

Cross validation technique is used to check the robustness of a model. Cross Validation is an extremely useful
technique for assessing the performance of machine learning models. It is primarily used in applied machine
learning to estimate the skill of a machine learning model on unseen data. That is, to use a limited sample to estimate how the model is expected to perform in general when used to make predictions on data not used during the training of the model.


Business Insights: 

Key Observations:
The more time the user spends on the website, the better their chances of becoming a student.

We have observed the probability of a lead being converted into a customer increases with a small decrease of page_views_per_visit from its mean value the pivot point is when the total number of visits on the website is 6. When total visits cross 6, the conversion rate drops as total pageviews decrease.

Olark Chat and Direct traffic generate the maximum number of leads. The conversion Rate of Reference leads is high.

There exists an 80% conversion rate of working professionals who have previously worked/working in Finance Management, Human Resource Management, and Marketing Management. Unemployed people have been contacted in the highest number, but the conversion rate is low ~40%.

The last notable activity being SMS Sent has the highest conversion rate of ~70%. Email opened has a good conversion rate of ~40%.

Recommendation:
Approach the leads who spent more time and were not converted and collect the feedback to improve the user experience.

For the profiles having current occupation as “Unemployed” the company can look for relevant skills in the lead profile and approach the lead by coming up with offering scholarships and loans.

Integration of course recommender into chat bots to suggest to the user the course which interests them the most rather than going through the entire course catalogue and offering some free content in a particular course.

Since the ‘Email opened’ last notable activity has a good conversion rate of 40%. The company can go about increasing this interaction rate by reducing the output email for a particular user rather they can go about mentioning free course contents that the user might be interested in.

Deployment-
Made with Heroku app with the final model




