# CITIZEN SERVICES- EY TECHATHON
ChatSewa.ai - Government Scheme Recommendation and Document Verification System
This project demonstrates a recommendation engine that suggests relevant government schemes to users based on their demographic information, including income, family size, age, and location. Additionally, it integrates document verification functionality using machine learning (ML) models, such as Random Forest and Gradient Boosting, to predict the most relevant schemes for the users.

The project also includes a series of visualizations (bar graph, histogram, pie chart, heatmap, and boxplot) to understand the distribution of user data and the results from the recommendation engine.

Features
Government Scheme Recommendations: Uses machine learning algorithms to predict the most relevant schemes based on user demographics.
Document Verification: A powerful system for verifying the authenticity of documents uploaded by the user.
Predictive Model: Alerts users about important deadlines, renewals, and upcoming opportunities related to the government schemes.
Natural Language Processing: Ability to process free-form queries from users.
Data Visualizations: Includes multiple visualizations like bar graphs, histograms, pie charts, heatmaps, and box plots to analyze the dataset and model performance.
Machine Learning Models: Implements Random Forest and Gradient Boosting algorithms to predict the eligibility of users for various schemes.
Requirements
Python 3.x
Pandas
NumPy
Matplotlib
Seaborn
scikit-learn
You can install the required libraries using pip:

bash
Copy code
pip install pandas numpy matplotlib seaborn scikit-learn
Dataset
The dataset used in this project is synthetic and includes the following columns:

Income: The income level of the user.
Family_Size: The number of people in the user's family.
Age: The age of the user.
Location: The user's location (Urban or Rural).
Eligible_Scheme: The government scheme(s) the user is eligible for.
Example data:
plaintext
Copy code
Income | Family_Size | Age | Location | Eligible_Scheme
50000  | 4           | 35  | Urban    | Scheme_A
30000  | 5           | 60  | Rural    | Scheme_B
...
How to Use
Clone the repository to your local machine:

bash
Copy code
git clone https://github.com/your-username/ChatSewa-ai.git
cd ChatSewa-ai
Make sure you have all the dependencies installed (as mentioned above).

Run the main Python script to train the models and visualize the results:

bash
Copy code
python recommendation_system.py
The script will display various visualizations including:

A bar graph showing the distribution of users among schemes.
A histogram displaying the income distribution of users.
A pie chart showing the percentage of users from urban and rural areas.
A heatmap to visualize the correlation between numerical features.
A boxplot comparing income and age distributions across different schemes.
The script will also output the predictions for a new user based on their demographic profile.

Example of Output:
plaintext
Copy code
Random Forest Accuracy: 0.87
Gradient Boosting Accuracy: 0.85

Random Forest Classification Report:
              precision    recall  f1-score   support
        0       0.91      0.85      0.88        20
        1       0.85      0.89      0.87        15

Recommended Scheme (Random Forest): Scheme_A
Recommended Scheme (Gradient Boosting): Scheme_A
Visualizations
The following visualizations are generated:

Bar Graph: Distribution of eligible schemes.
Histogram: Distribution of user incomes.
Pie Chart: Distribution of users based on location (Urban vs Rural).
Heatmap: Correlation between features (Income, Family Size, Age, and Location).
Boxplot: Income distribution per eligible scheme.
Boxplot: Age distribution per eligible scheme.
ML Models Used
Random Forest Classifier: A robust ensemble model that provides predictions based on multiple decision trees.
Gradient Boosting Classifier: An advanced ensemble technique that builds trees sequentially to improve accuracy.
Conclusion
This project provides a comprehensive and user-friendly government scheme recommendation engine. It uses machine learning to predict the best scheme for users based on demographic data and visualizations for better decision-making. By integrating document verification and predictive models, ChatSewa.ai can help users stay on top of their government-related responsibilities and improve their access to benefits.

License
This project is licensed under the MIT License.
