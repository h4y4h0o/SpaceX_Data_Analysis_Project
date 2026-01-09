In this project, we predict if the Falcon 9 first stage will land successfully. SpaceX advertises Falcon 9 rocket launches on its website, with a cost of 62 million dollars; other providers cost upward of 165 million dollars each, much of the savings is because SpaceX can reuse the first stage. Therefore if we can determine if the first stage will land, we can determine the cost of a launch. This information can be used if an alternate company wants to bid against SpaceX for a rocket launch.\

Here are the different data analysis tasks done in this project:\

1.Exploratory Data Analysis (EDA):\
  We collect data on the Falcon 9 first-stage landings. We used a RESTful API and web scraping. We convert the data into a dataframe and then perform some data wrangling.\
2. Interactive Visual Analytics an Dashbords:\
  We build a dashboard to analyze launch records interactively with Plotly Dash. We then build an interactive map to analyze the launch site proximity with Folium.\
3. Predictive Analysis:\
   We use machine learning to determine if the first stage of Falcon 9 will land successfully (Classification methods). We split the data into training data and test data to find the best Hyperparameter for SVM, Classification Trees, and Logistic Regression. Then find the method that performs best using test data.\
4. Present Our Data-Driven Insights:\
  We compile all of our activities into one place and deliver our data-driven insights to determine if the first stage of Falcon 9 will land successfully.
