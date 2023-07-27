# Jungkee Song - Data Science Portfolio

## About Me

Hello, I'm Jungkee Song, an experienced tech professional with a unique blend of skills in product management and data science. My strategic product leadership, coupled with my strong technical expertise, allows me to build data-driven products, conduct comprehensive data analysis, and create robust machine learning models. Currently, I'm enhancing my data science competencies through the Applied Data Science Program provided by MIT, which I expect to complete by mid-August 2023. I am passionate about harnessing data to uncover insightful narratives and drive product strategy and business growth. With my combined expertise in data science and product management, I am well-equipped to navigate complex challenges and create impactful solutions in both domains.

---

## Skills

- **Machine Learning:** Regression, Classification, Deep Learning, Unsupervised Learning
- **Data Analysis:** Exploratory Data Analysis, Feature Engineering, Hypothesis Testing, Product Experiments
- **Data and ML Tools:** Python, Pandas, NumPy, Scikit-learn, Scipy, TensorFlow, PyTorch, SQL
- **Product Leadership:** Product Management, Program Management, Cross-functional Leadership
- **Software Development:** JavaScript, Web Platform, Web Standards

---

## Certifications

- **[Applied Data Science Program](https://professional.mit.edu/course-catalog/applied-data-science-program-leveraging-ai-effective-decision-making), MIT** (Currently enrolled, completion expected by mid-August 2023)
- **[IBM Data Science](https://www.coursera.org/account/accomplishments/professional-cert/LNG94D7S4V8G), IBM Skills Network** on Coursera, March 2023
- **[Machine Learning](https://www.coursera.org/account/accomplishments/specialization/Y3LRQMM488TK), Stanford University & DeepLearning.AI** on Coursera, March 2023

---

## Projects

### **Project: ExtraaLearn: Which Customers Should We Invest In?**

*Project for the Applied Data Science Program, MIT*

See the full code in [the notebook](https://github.com/jungkees/mit-applied-datascience-portfolio/blob/main/mit-adsp-extraalearn-project.ipynb)

- **Background:** In the rapidly growing EdTech industry, which is projected to reach $286.62bn by 2023, startups like ExtraaLearn are experiencing a surge in customers, largely due to the shift to online learning amidst the COVID-19 pandemic. This creates the challenge of effectively identifying and nurturing the most promising customers.

- **Goal:** Develop a machine learning model to predict which of these customers are likely to convert into paying customers, and uncover the key factors that influence this conversion.

- **Data:** ExtraaLearn provided a dataset comprising 4,612 customers, each described by 14 features detailing acquisition methods and a label indicating conversion status.

- **Methodology:**
  - Conducted exploratory data analysis (EDA) to understand the data.
  - Preprocessed the data for model compatibility.
  - Defined metrics for model evaluation and divided data into training and test sets.
  - Built various classification models including Logistic Regression, Decision Tree, Random Forest, K-NN, and XGBoost. Further tuned hyperparameters for the Decision Tree and Random Forest models.
  - Evaluated each model's performance on training and test sets and selected the model with the best test set performance.

- **Metrics:** Prioritized precision over recall to minimize false positives, while ensuring a balance with recall to capture as many actual conversions as possible. Used accuracy and F1-score as main metrics, monitoring precision closely throughout the evaluation process.

- **Results:**
  - The optimized Random Forest model demonstrated superior performance with approximately 87% accuracy and 79% precision, although real-world data validation is necessary.
  - Key insights include the effectiveness of time spent on the website, the need for an improved mobile experience, the importance of profile completion, potential enhancements in education channels, and the high conversion rate of referral customers.
  - These findings emphasize the need for continuous iteration and real-world testing for concrete validation. For detailed insights and recommendations, please refer to the end of the notebook.

### **Project: FoodHub: Understanding Customer Behavior and Restaurant Preferences**

*Project for the Applied Data Science Program, MIT*

See the full code in [the notebook](https://github.com/jungkees/mit-applied-datascience-portfolio/blob/main/mit-adsp-foodhub-project.ipynb)

- **Background:** FoodHub, a popular food aggregator based in New York, wanted to explore their customer order data to gain insights into customer behavior and preferences. By better understanding these aspects, they aimed to enhance the customer experience and increase their overall revenue.

- **Goal:** Conduct an in-depth exploratory data analysis (EDA) with the intention to:
  - Understand customer behavior and restaurant preferences to enhance customer satisfaction and retention.
  - Identify relationships between variables that could influence customer ratings, thereby providing potential improvement points for restaurant performance.
  - Extract actionable insights that could positively impact FoodHub's business operations and revenue growth.

- **Data:** FoodHub provided a dataset of unique customer orders, including details such as restaurant name, cuisine type, cost of the order, day of the week, customer rating, food preparation time, and delivery time.

- **Methodology:**
  - Conducted initial data check and cleaning.
  - Undertook univariate, bivariate, and multivariate analyses.
  - Checked correlations between different features.
  - Derived insights on customer behavior and restaurant performance.

- **Metrics:** As an EDA project, the success was assessed based on the depth of insights derived and their potential actionability for FoodHub.

- **Results:**
  - Identified loyal customers, popular restaurants, and favored cuisines. Found that 71.18% of orders occurred on weekends.
  - Discovered high-rated restaurants with low revenue, indicating opportunities for increased exposure.
  - Found no significant correlation between total time and customer rating, suggesting the need for more data (e.g., delivery distance, delivery person feedback) for comprehensive insights.
  - Rating data was sparse, with only 61.2% of orders having ratings, indicating a need for improved feedback mechanisms.
  - For detailed findings and recommendations, please refer to the end of the notebook.


### **Project: Predicting Falcon 9 First Stage Landing Success**

*Capstone Project for the IBM Professional Data Science Program*

See the full code in [the notebooks](https://github.com/jungkees/IBM-data-science-capstone)

- **Background:** SpaceX has a competitive advantage in space launch contracts due to its ability to land and reuse the first stage of the Falcon 9 rocket, drastically reducing launch costs. As a data scientist, predicting the success of these landings can offer valuable insights into overall launch costs, a critical aspect for companies bidding against SpaceX.

- **Goal:** To develop a predictive model to determine the successful landing of the Falcon 9's first stage.

- **Data:** Utilized Falcon 9 launch data from SpaceX and Wikipedia, gathered via REST API and web scraping.

- **Methodology:**
  - Performed EDA using Pandas and SQL, visualized data through plots and interactive dashboards.
  - Cleaned and labeled important features including launch outcomes.
  - Identified and selected important features showing correlations.
  - Constructed Logistic Regression, SVM, Decision Tree, and K-NN classification models and tuned their hyperparameters.
  - Evaluated each model's performance on training and test sets, and selected the model with the best test set performance.

- **Metrics:** Employed accuracy and F1-score on the test sets to evaluate different models.

- **Results:**
  - Identified launch sites, orbits, payload mass, and flight numbers as significant features.
  - Achieved high levels of accuracy with Logistic Regression, SVM, Decision Tree, and KNN models trained with selected features. F1 scores of >=81.
  - Determined the Decision Tree Classifier as the optimal model for predicting landing success, with an F1 score of 0.94.
  - These findings provide valuable insights for potential competitors, enabling them to use the predictive model to estimate launch costs while considering bids against SpaceX. They are also beneficial for SpaceX, assisting them in their ongoing efforts to improve their first stage landing success rates and further reduce launch costs.

---

## Work Experience relevant to Data Science

### **Microsoft, Redmond WA**
*Senior Product Manager, The Microsoft Edge Team* — May 2018-April 2023
- Championed the use of data telemetry to analyze customer behaviors, informing the design and implementation of customer-focused strategies and products.
- Initiated and led the [Video Super Resolution](https://blogs.windows.com/msedgedev/2023/03/08/video-super-resolution-in-microsoft-edge/) project, beginning with a comprehensive opportunity analysis to identify key customer profiles and understand video quality metrics across the product. Leveraged machine learning to enhance video quality, achieving a 90% user preference rate and boosting user engagement and retention.
- Designed and implemented the [adaptive web notification score system](https://blogs.windows.com/msedgedev/2021/02/16/introducing-adaptive-notification-requests-in-microsoft-edge/), using customer accept/deny rates on notifications as primary data. This data-driven approach resulted in a 20% reduction in user frustration and a significant improvement in product retention.
- Took action against malicious notifications by utilizing data about the notification senders. Applied classification models to differentiate between malicious and non-malicious senders, optimizing precision and recall through iterative exploration and refinement of the model, contributing to enhanced user trust and satisfaction.
- Actively monitored customer feedback channels to prioritize issues causing the most customer frustration, such as camera/microphone failures during video calls, ensuring rapid response during the pandemic.
- Facilitated a smooth transition from legacy Edge to Chromium-based Edge, maintaining feature stability and parity based on customer data.

See the full experience at [LinkedIn](https://www.linkedin.com/in/jungkees/)

---

## Education

- Master of Science in Computer Science - NORTH CAROLINA STATE UNIVERSITY, Raleigh
- Bachelor of Science in Computer Science - KWANGWOON UNIVERSITY, Seoul

---

## Contact Me

[Contact me at LinkedIn](https://www.linkedin.com/in/jungkees/)

---
