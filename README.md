# App-Market-Trends-A-Deep-Dive-into-Google-Play-Store-Dataset
## Introduction  
The Google Play Store hosts millions of apps across diverse categories. This project explores the data to uncover patterns in app ratings, installs, categories, and pricing to understand what drives app success.

## Objective  
- Perform Exploratory Data Analysis (EDA) on the Google Play Store dataset.  
- Clean and preprocess the data for accuracy.  
- Visualize trends in app categories, installs, reviews, and ratings.  
- Derive actionable insights for app developers and marketers.

## Tools & Technologies  
- **Programming Language:** Python  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn  
- **Data Source:** Kaggle - Google Play Store Dataset  
- **Visualization Types:** KDE Plots, Bar Charts, Countplots, Pie Charts

## Data Cleaning  
- Removed duplicates and null values for cleaner analysis.  
- Converted size from strings like '19M' to numeric values.  
- Handled inconsistent entries such as 'Varies with device'.  
- Parsed date columns into day, month, and year components.

## Exploratory Data Analysis (EDA)  

### Univariate Analysis  
- Rating distribution shows most apps range between 4.0 and 4.5.  
- Majority of apps are free and belong to categories like GAME, COMMUNICATION.  
- Countplots and pie charts illustrate app category proportions and type.

### Bivariate Analysis  
- Top installed apps vary significantly by category (e.g., GAME vs SOCIAL).  
- Paid apps tend to have higher average ratings compared to free apps.  
- Reviews and installs show positive correlation with rating but with exceptions.

## Key Insights  
- GAME and COMMUNICATION categories dominate total installs.  
- Perfect 5-star ratings are rare and may indicate review manipulation.  
- Pricing strategy affects user adoption, with most users preferring free apps.  
- Data cleaning was critical to avoid misleading conclusions.

## Conclusion  
This analysis provides a clear view of app market trends on Google Play Store. By understanding ratings, installs, and category performance, developers can make informed decisions. Visual tools helped identify patterns and outliers effectively.

## Contact    
- Email: [tanutambolit@gmail.com]
