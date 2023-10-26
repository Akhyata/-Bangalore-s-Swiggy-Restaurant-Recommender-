![image](https://github.com/Akhyata/-Bangalore-s-Swiggy-Restaurant-Recommender-/assets/143725909/fce3e4f6-92ba-4e7a-8aaf-151604ac0e8f)
#### Bangalore's Swiggy Restaurant Recommender 🍽️🤖 

#### Overview 🌐:
- **Description**: Developed a comprehensive restaurant recommendation system for Swiggy users in Bangalore. The system combines web scraping, data manipulation, and machine learning to offer personalized dining suggestions.
- **Context and Significance**: In a bustling city like Bangalore, this project aimed to enhance the dining experiences of Swiggy users by providing tailored restaurant recommendations based on various factors such as location, cuisine, and price.

#### Data Source 📊📂:
- **Format**: Retrieved data in HTML format and processed it for analysis.
- Data:
       - https://www.swiggy.com/

       - https://www.swiggy.com/restaurants/glens-bakehouse-lavelle-road-ashok-nagar-bangalore-17376
- **Data Extraction**: Employed Selenium and Beautiful Soup to extract restaurant data from Swiggy's website in Bangalore.
                       Here we exract the details like restaurant names, ratings, prices, cuisines, and more.
![Screenshot 2023-10-26 225413](https://github.com/Akhyata/-Bangalore-s-Swiggy-Restaurant-Recommender-/assets/143725909/f882eb23-75d5-47d7-ab38-a1d179ffa204)
![image](https://github.com/Akhyata/-Bangalore-s-Swiggy-Restaurant-Recommender-/assets/143725909/769a1dc9-0105-4f1b-8184-6e026f7ddc5c)

- **Data Cleaning**: Thoroughly cleaned and preprocessed the data, addressing missing values and inconsistencies using pandas.
![Screenshot 2023-10-26 230551](https://github.com/Akhyata/-Bangalore-s-Swiggy-Restaurant-Recommender-/assets/143725909/07ac1f82-8f56-4426-aa2a-cc4ba28386e8)
![image](https://github.com/Akhyata/-Bangalore-s-Swiggy-Restaurant-Recommender-/assets/143725909/7b8a6c4b-8a44-4720-80df-26c395b85a8d)

#### Data Manipulation 🧹:
- **Data Transformation**: Utilized Python and Pandas to transform and structure the data, preparing it for modeling.
- **Data Conversion**: Converted the processed data into an Excel format for accessibility and further analysis.
![image](https://github.com/Akhyata/-Bangalore-s-Swiggy-Restaurant-Recommender-/assets/143725909/3810811c-5cb5-4cde-bfd7-80ee5b931996)

#### Exploratory Data Analysis (EDA) 📊📈:
- **Data Exploration**: Conducted thorough exploratory data analysis (EDA) using Pandas to gain insights into the restaurant data. EDA included examining price distribution, cuisine preferences, and other key attributes.

![image](https://github.com/Akhyata/-Bangalore-s-Swiggy-Restaurant-Recommender-/assets/143725909/461199d2-38aa-4dbc-b27c-17e46da1631d)
![image](https://github.com/Akhyata/-Bangalore-s-Swiggy-Restaurant-Recommender-/assets/143725909/dc0b58c1-decc-49f7-8980-14205dec9d9b)

#### Data Visualization 📊📈:
- **Visualization Tools**: Leveraged Seborn for data visualization and Matplotlib for creating insightful charts and graphs to visually represent the findings from EDA.

![image](https://github.com/Akhyata/-Bangalore-s-Swiggy-Restaurant-Recommender-/assets/143725909/6b273fc3-ed10-4d7a-a5b0-895117e2afb3)
![image](https://github.com/Akhyata/-Bangalore-s-Swiggy-Restaurant-Recommender-/assets/143725909/d10f381e-5ee7-4727-8481-b92bb08940de)

#### Machine Learning Modeling 🤖:
- **Feature Selection**: Employed Principal Component Analysis (PCA) to reduce dimensionality and select relevant features.

![image](https://github.com/Akhyata/-Bangalore-s-Swiggy-Restaurant-Recommender-/assets/143725909/a670f052-2e0e-4aa6-a3aa-0fe9cf45c621)

- **Linear Regression - Price Prediction**: Developed a linear regression model with price as the target variable, achieving a remarkable R2-score of 0.9999999994289045, indicating the model's exceptional predictive accuracy.

![image](https://github.com/Akhyata/-Bangalore-s-Swiggy-Restaurant-Recommender-/assets/143725909/347d971d-eb57-4c38-bb06-674b2a4da138)

- **Random Forest Classifier - Cuisines Prediction**: Built a Random Forest Classifier for predicting restaurant cuisines with a high accuracy of metrics.accuracy_score: 0.9990266060999351, ensuring precise cuisine recommendations.

![image](https://github.com/Akhyata/-Bangalore-s-Swiggy-Restaurant-Recommender-/assets/143725909/746ca4ef-aae5-4529-a29c-5d54d3373a88)

- **Random Forest Classifier - Location Prediction**: Developed a Random Forest Classifier to predict restaurant locations, achieving an accuracy score of model prediction: 0.8763326226012793, enhancing location-based recommendations.

![image](https://github.com/Akhyata/-Bangalore-s-Swiggy-Restaurant-Recommender-/assets/143725909/7c044736-15cd-41fd-9816-759a62cef84c)

#### Data Scaling 📏:
- **Data Standardization**:
   Implemented the StandardScaler from Scikit-Learn to standardize and scale the data for improved modeling.
  
![image](https://github.com/Akhyata/-Bangalore-s-Swiggy-Restaurant-Recommender-/assets/143725909/1b077d18-8ddb-466b-842e-9c64dfa44d12)

#### Label Encoding 🏷️:
- **Cuisine Label Encoding**:
  Employed the LabelEncoder to encode the cuisine column, facilitating machine learning model compatibility.
![image](https://github.com/Akhyata/-Bangalore-s-Swiggy-Restaurant-Recommender-/assets/143725909/b845cf06-d655-4320-a7b4-6c3cbb76ef1a)

- **Location Label Encoding**: Utilized the LabelEncoder for encoding location data to enhance the accuracy of location-based predictions.
![image](https://github.com/Akhyata/-Bangalore-s-Swiggy-Restaurant-Recommender-/assets/143725909/ca2cb667-7e5a-4826-994f-78d860061404)

#### Model Training and Testing 📚:
**Data Splitting**: Split the dataset into training and testing sets using the train_test_split function with a test size of 20% and a fixed random state of 55 for reproducibility.

![image](https://github.com/Akhyata/-Bangalore-s-Swiggy-Restaurant-Recommender-/assets/143725909/e8929269-78c7-41c2-8fc9-b47264f150cf)
![image](https://github.com/Akhyata/-Bangalore-s-Swiggy-Restaurant-Recommender-/assets/143725909/19e733ff-4289-40c4-829b-935b1e7d7904)

#### Web Page Formation 💻:
- A user-friendly web interface will be created to allow users to input their preferences for cuisine, location, and price.
- The system will provide recommendations through the web page, making it accessible and interactive for users.
- The web page will display recommendations in a clear and visually appealing format, helping users easily digest the insights provided.
![image](https://github.com/Akhyata/-Bangalore-s-Swiggy-Restaurant-Recommender-/assets/143725909/c7cc2cc1-0b79-476f-ba8f-d691971f954c)

#### Result 📊:
- The project will generate detailed recommendations based on user input.
  These recommendations will help aspiring restaurant owners make informed decisions regarding their restaurant's cuisine, pricing, location, and more.
![image](https://github.com/Akhyata/-Bangalore-s-Swiggy-Restaurant-Recommender-/assets/143725909/591da2ef-13f3-47d0-b0ed-6c2074e58ace)
![image](https://github.com/Akhyata/-Bangalore-s-Swiggy-Restaurant-Recommender-/assets/143725909/75d77038-55de-47b3-b5bc-118bbc701fab)

#### Challenges Faced ⚙️:
- **Data Extraction Challenges**: Extracting relevant and accurate data from Swiggy's website presented initial challenges due to the site's structure.
- **Model Selection Dilemma**: Choosing the perfect machine learning model for restaurant recommendations required careful consideration and experimentation.
- **Web Page Development**: Creating an interactive web interface with HTML, CSS, and Python posed design and implementation challenges.
  
#### Future Scope 🚀:
- Future enhancements could involve incorporating user-specific preferences and real-time data updates to provide more precise recommendations.
- Consider adding features such as user reviews and restaurant ratings to further enhance the recommendation system's accuracy and relevance.
- Explore deploying the recommender system with the web interface as a standalone application, making it accessible to a wider audience.

#### Tools Used 🛠️:
![image](https://github.com/Akhyata/-Bangalore-s-Swiggy-Restaurant-Recommender-/assets/143725909/bbbbd0e0-50fc-49b9-abc0-dbc3666563d7)

#### Conclusion 📖:
- In summary, the Restaurant Recommendation Model project addresses the challenge of deciding where to dine by providing personalized recommendations.
  It involves data extraction, preprocessing, and machine learning modeling to predict restaurant prices. 
  The interactive web application enhances user experience, and visualizations provide valuable insights into restaurant trends.
  While the project has limitations, it demonstrates the potential of data-driven dining decisions and successfully delivers a sophisticated restaurant recommendation system for Swiggy users in Bangalore, 
  ensuring a highly personalized dining experience.
