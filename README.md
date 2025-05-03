Problem statement:
In ever-changing competitive market conditions, there is a need to make correct
decisions and plans for future events related to business like sales, production, and
many more. The effectiveness of a decision taken by business managers is influenced by
the accuracy of the models used. Demand is the most important aspect of a business's
ability to achieve its objectives. Many decisions in business depend on demand, like
production, sales, and staff requirements. Forecasting is necessary for business at both
international and domestic levels.

Problem Objective:
Fresh Analytics, a data analytics company, aims to comprehend and predict the demand
for various items across restaurants. The primary goal of the project is to determine the
sales of items across different restaurants over the years.

Project Task

- Data science

  - Preliminary analysis:
    a. Import the datasets into the Python environment.
    b. Examine the dataset's shape and structure, and look out for any outlier.
    c. Merge the datasets into a single dataset that includes the date, item id, price, item count, item names, kcal values, store id, and store name.
  - Exploratory data analysis:
    a. Examine the overall date wise sales to understand the pattern.
    b. Find out how sales fluctuate across different days of the week.
    c. Look for any noticeable trends in the sales data for different months of the year.
    d. Examine the sales distribution across different quarters averaged over the years. Identify any noticeable patterns.
    e. Compare the performances of the different restaurants. Find out which restaurant had the most sales and look at the sales for each restaurant across different years, months, and days.

  - Machine learning
    f. Identify the most popular items overall and the stores where they are being sold. Also, find out the most popular item at each store.
    g. Determine if the store with the highest sales volume is also making the most money per day.
    h. Identify the most expensive item at each restaurant and find out its calorie count.

  - Forecasting using machine learning algorithms:
    a. Build and compare linear regression, random forest, and XGBoost models for predictions.
    • Generate necessary features for the development of these models, like day of the week, quarter of the year, month, year, day of the month and so on.
    • Use the data from the last six months as the testing data.
    • Compute the root mean square error (RMSE) values for each model to compare their performances.
    • Use the best-performing models to make a forecast for the next year.

  - Deep learning
    - Forecasting using deep learning algorithms:
      a. Use sales amount for predictions instead of item count
      b. Build a long short-term memory (LSTM) model for predictions
      • Define the train and test series.
      • Generate synthetic data for the last 12 months.
      • Build and train an LSTM model.
      • Use the model to make predictions for the test data.
      c. Calculate the mean absolute percentage error (MAPE) and comment on the model's performance.
      d. Develop another model using the entire series for training, and use it to forecast for the next three months.
