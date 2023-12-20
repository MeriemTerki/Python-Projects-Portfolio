# Python-Projects-Portfolio

## 🚀 Analyzing Crime in Los Angeles Project

### **Project Overview**

Welcome to the City of Angels! this project aims to analyze crime data to uncover patterns in criminal behavior. The insights gained will assist the LAPD in allocating resources effectively and implementing targeted crime prevention strategies across different areas of Los Angeles.

### **Steps**
1. **Identify Peak Crime Hour**
   - Determine the hour with the highest frequency of crimes and store it as an integer variable called `peak_crime_hour`.
2. **Locate Area with Highest Night Crimes**
   - Find the area with the largest frequency of night crimes (committed between 10 pm and 3:59 am) and save it as a string variable called peak_night_crime_location.
3. **Analyze Crimes by Victim Age Group**
   - Examine the number of crimes committed against victims in different age groups (<18, 18-25, 26-34, 35-44, 45-54, 55-64, 65+). Save the results as a pandas Series 
     called victim_ages.

View my project [here](https://github.com/MeriemTerki/Python-Projects-Portfolio/blob/main/Analyzing-Crime-in-Los-Angeles/Analyzing-Crime-in-Los-Angeles.ipynb).


## 🚀 The GitHub History of the Scala Language Project

### **Project Overview**

Explore and analyze Scala's real-world project repository data with nearly 30,000 commits and over a decade of development history. Scala, a mature and versatile programming language, has gained recognition in the field of data science.

### **Steps**

1. **Data Collection:**
   - **Datasets:**
     - *pulls_2011-2013.csv:* Basic info about pull requests (late 2011 to 2013).
     - *pulls_2014-2018.csv:* Similar info for pull requests (2014 to 2018).
     - *pull_files.csv:* Details of files modified.

2. **Data Preparation and Cleaning:**
   - Combine data from two pull DataFrames.
   - Convert date strings to DateTime objects (UTC).

3. **Merging DataFrames:**
   - Merge two DataFrames into one.

4. **Project Activity Visualization:**
   - Chart monthly pull request counts.
   - Understand contribution evolution.

5. **Community Dynamics:**
   - Plot user pull request histogram.
   - Assess camaraderie and new contributor barriers.

6. **Recent Changes in Files:**
   - Identify files changed in the last ten pull requests.
   - Pinpoint active codebase areas.

7. **Contributors to a Specific File:**
   - Determine top developers for a specific file.
   - Gain insights into key contributors.

8. **Recent Contributors to a File:**
   - Identify users with the last ten pull requests to a file.
   - Understand recent contributors.

9. **Analyzing Developer Contributions Over Time:**
   - Analyze pull requests by developers over the years.
   - Understand key developers' contribution trends.

10. **Visualizing Developer Contributions to a Specific File Over Time:**
    - Examine developer experience with a specific file over time.
    - Measure pull requests for key contributors.
      

View my project [here](https://github.com/MeriemTerki/Python-Projects-Portfolio/blob/main/The-GitHub-History-of-the-Scala-Language/The-GitHub-History-of-the-Scala-Language.ipynb).


## 🚀 Visualizing the History of Nobel Prize Winners Project

### **Project Overview**

Explore and analyze the Nobel Prize dataset, a comprehensive collection of prizewinning data spanning from 1901 to 2023. The dataset is sourced from the Nobel Prize API and is available in the 'nobel.csv' file in the data folder.

### Steps

1. **Data Loading:**

##### Libraries:
- Pandas for data manipulation.
- Seaborn for visualization.
- NumPy for numerical operations.

2. **Most Commonly Awarded Gender and Birth Country:**
   - Identify and store the most commonly awarded gender and birth country among Nobel laureates.
3. **Proportion of USA-Born Winners Over Decades:**
   - Calculate the proportion of USA-born winners per decade.
   - Display the proportions of USA-born winners per decade.
   - Display the lineplot of USA Born Winners Over Decades
4. **Proportion of Female Laureates Over Decades:**
   - Calculate the proportion of female laureates per decade and category.
   - Visualize this with a relational line plot.
5. **First Woman Nobel Prize Winner:**
   - Identify and display information about the first woman to win a Nobel Prize.
6. **Repeat Winners:**
   - Identify and display laureates who have received two or more Nobel Prizes.

View my project [here](https://github.com/MeriemTerki/Python-Projects-Portfolio/blob/main/Visualizing-the-History-of-Nobel-Prize-Winners/Visualizing-the-History-of-Nobel-Prize-Winners.ipynb).


## 🚀 Furniture Retailer Campaign: Keyword Generation

### **Project Overview**

Join our digital marketing agency in creating a powerful set of search keywords for a major online furniture retailer. The challenge? Craft a prototype campaign for sofas, convertible sofas, love seats, recliners, and sofa beds. The catch? Target price-sensitive customers with promotions and discounts, all while working within a tight budget.

### **Steps**

 1. **Unleash the Power Words**

    - Explore words that resonate with savvy shoppers: 'buy', 'price', 'discount', 'promotion', 'promo', and 'shop'.

 2. **Fusion of Words and Products**

    - Combine these impactful words with each furniture product, unleashing a dynamic array of search keywords.

 3. **Data Alchemy: DataFrame Creation**

    - Transform this fusion into a DataFrame, a canvas for crafting our campaign masterpiece.

4. **Renaming the Scene**

    - Give our DataFrame a polished look by assigning meaningful names to its columns.

5. **Campaign Chronicles**

    - Introduce a 'Campaign' column, giving our efforts a distinct identity - 'SEM_Sofas'.

6. **Crafting Match Types**

    - Create a 'Criterion Type' column, setting the stage with the precision of 'Exact' match.

7. **Echoes of Keywords: 'Phrase' Edition**

    - Duplicate the keyword symphony, this time embracing the versatility of 'Phrase' match.

8. **Save and Unveil**

    - Capture our campaign in a CSV file, ready for its grand entrance. Delve into a summary, a glimpse of our campaign's structure.

View my project [here](https://github.com/MeriemTerki/Python-Projects-Portfolio/blob/main/Generating-Keywords-for-Google-Ads.ipynb).


## 🚀 Soccer Goal Analysis

### **Project Overview**

This project, led by a sports journalist specializing in soccer analysis, investigates whether more goals are scored in women's international soccer matches compared to men's. The analysis utilizes statistical hypothesis testing and focuses on data from official FIFA World Cup matches since January 1, 2002.

### **Hypotheses**

- **Null Hypothesis (H0):** The mean number of goals scored in women's international soccer matches is equal to that of men's.
- **Alternative Hypothesis (H1):** The mean number of goals scored in women's international soccer matches is greater than that of men's.

### **Datasets**

Two datasets, namely `women_results.csv` and `men_results.csv`, have been compiled. These datasets contain results from official men's and women's international football matches since the 19th century.

### **Methodology**

 1. **Data Preparation**

   - The datasets are loaded and filtered to include only FIFA World Cup matches since January 1, 2002.

 2. **Data Transformation**

    - Relevant columns are selected, and a new column is created to represent the total goals scored in each match. This information is crucial for the subsequent analysis.

 3. **Hypothesis Testing**

    - The Wilcoxon-Mann-Whitney test is employed to compare the mean goals scored between women's and men's matches. The test is conducted using both the Pingouin and SciPy 
      libraries.

 4. **Result Interpretation**

     - The p-value obtained from the hypothesis test is analyzed. If the p-value is less than or equal to 0.01, the null hypothesis is rejected; otherwise, it is failed to 
       be rejected. The outcome is then summarized to provide a clear interpretation of the results.


View my project [here](https://github.com/MeriemTerki/Python-Projects-Portfolio/blob/main/Hypothesis-Testing-with-Men's-and-Women's-Soccer-Matches/Hypothesis-Testing-with-Men's-and-Women's-Soccer-Matches.ipynb).
