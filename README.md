# Jesse Jin's Portfolio

Data Science Portfolio
### [LeetCode Algorithm](https://github.com/jesse980107/Leetcode) and [SQL](https://github.com/jesse980107/SQL) 
![Language](https://img.shields.io/badge/language-MySQL%20%2F%20PostgreSQL%20%2F%20Python-orange)&nbsp;![Update](https://img.shields.io/badge/update-daily%20%2F%20weekly-green.svg)&nbsp;
To continuously improve my programming and problem-solving skills, I regularly practice on LeetCode, focusing on both SQL queries and algorithmic challenges. This consistent practice enhances my ability to write efficient code and approach complex problems systematically, skills that I apply directly to my data science projects and professional work.

- Mastered complex SQL concepts including advanced window functions, recursive CTEs, and intricate multi-table joins
- Tackled a diverse array of algorithmic problems, conquering challenges in areas such as dynamic programming, graph theory, and optimization algorithms
- Developed highly optimized solutions, consistently achieving top-tier runtime and memory usage performances
- Demonstrated proficiency in Python for algorithmic problems and SQL for database queries

  
### [ReasearchQFinder: News Research Tool](https://github.com/jesse980107/research_tool_project)
ReasearchQFinder is a user-friendly news research tool designed for effortless information retrieval. Users can input article URLs and ask questions to receive relevant insights from any domain.

![ReasearchQFinder](images/ReasearchQFinder.jpg)

- Load URLs or upload text files containing URLs to fetch article content
- Process article content through LangChain's UnstructuredURL Loader
- Construct an embedding vector using OpenAI's embeddings and leverage FAISS, a powerful similarity search library, to enable swift and effective retrieval of relevant information
- Interact with the LLM's (Chatgpt) by inputting queries and receiving answers along with source URLs


### [End-To-End Data Engineering Project with Azure ](https://github.com/jesse980107/Azure-Data-Pipeline-Implementation-for-Olympic-Data-Analysis)
This project demonstrates a comprehensive data pipeline using Azure Data Factory, Data Lake Gen 2, Azure Databricks, and Azure Synapse Analytics. The goal is to process and analyze data from the 2021 Tokyo Olympics and visualize the results using Power BI.

![Architecture Diagram](images/Architecture%20Diagram.png)
The architecture consists of the following components:
1. **Data Source**: Raw data origin
2. **Data Integration**:
   - **Azure Data Factory**: Orchestrates data ingestion and initial transformation
   - **Data Lake Gen 2**: Stores raw data in the `raw-data` folder
3. **Transformation**:
   - **Azure Databricks**: Transforms and processes data using Apache Spark
   - **Data Lake Gen 2**: Stores transformed data in the `transform-data` folder
4. **Analytics**:
   - **Azure Synapse Analytics**: Performs advanced analytics and find insight
5. **Dashboard**:
   - **Power BI, Looker Studio, Tableau**: Visualizes the processed data

### [Twitter/X Influencer Post Monitor](https://github.com/jesse980107/Twitter-X-Influencer-Post-Reply-Monitor/tree/main)
This project is a web crawler designed to monitor tweets/replies from a specific Twitter/X influencer, such as Elon Musk. The crawler logs into Twitter, navigates to the influencer's page, and retrieves the latest tweet's URL and content. The project uses Selenium WebDriver to automate and interact with the web page.

- Uses ChromeDriver to open a headless window
- Automated login to Twitter
- Navigation to a specified Twitter influencer's page
- Retrieval of the latest tweet's URL and content
- Detection of changes in tweets to identify new posts
- Extracts the information of new post/reply and pushes it to WeChat bot via API

### [U.S. Insurance Bill Estimator](https://github.com/jesse980107/U.S.-Insurance-Bill-Estimator)
For this example I build a bill charge estimator to an insurance plan each year based on the policy holder’s demographic information. This could be useful for someone who is insurance director. They could use a customer's information to estimate their hopspital bill and help them determine which insurence plan is better for this costomer.
* Creat a tool that estimate costomer's hospital bill to help insurence director determine which insurence plan is better for their costomers
* Engineered features from BMI and ages
* Optimized Linear, Quadratic and Interaction terms added, and standardized with Backward Selection algorithm to reach the best model

![](images/Residual%20Plot%203.png)

### [Online Shopping Intention Analysis](https://github.com/jesse980107/online-shopping)
With the growth of online shopping, it has become important to understand the factors that influence a consumer’s intention to buy from a website rather than just browse. This emerging topic is of interest to both academics and machine learning practitioners.
From the matrix below, it is clear that we have poorly bundled many successful revenue sessions as uninterested customers, which means when the high bounce rate combined with a short product-related page duration, there are still a lot of customers. targets.

![](images/Normalized%20Confusion%20Matrix.png)

### [Kaggle competition - Predict Rossmann Store Sales](https://github.com/jesse980107/Predict-Rossmann-Store-Sales-by-Gradient-Boosting-XGBoost)
Rossmann operates over 3,000 drug stores in 7 European countries. Currently, Rossmann store managers are tasked with predicting their daily sales for up to six weeks in advance. Store sales are influenced by many factors, including promotions, competition, school and state holidays, seasonality, and locality.
* Did a lot of feature engineering
* I build a sales estimator by using GBMs with XGBoost
![](images/Final%20result.png)
