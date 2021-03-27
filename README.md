

The pandas project consists of two jupyter notebooks:



-The first jupyter notebook is about cleaning the dataset. It begins droping some columns and then start with the 1st part:FIRST TOY MODEL: demographics. Focus on age and sex column, cleaning and droping NaN values using different types of pandas libraries. In the 2nd part: TOY MODEL 2: space-time statistics, we use value_Counts in order to take some insightful information.


-The second jupyter notebook is about analyzing and giving some conclussions. After it, it has a dataframe with some interesting information and a surprise.







# W2 Project - Data cleaning & wrangling

The goal of this project is to combine everything you have learned about data
wrangling, cleaning, and manipulation with Pandas so you can see how it all works
together. For this project, you will start with this messy data set Shark Attack.
You will need to import it, use your data wrangling skills to clean it up,
prepare it to be analyzed, and then export it as a clean CSV data file.
Some graphs to better understand the data will surely be useful!!

## TODOs

1. Toy model 1: demographics
   1. Focus on columns 'Age' and 'Sex'
   2. Choose a strategy to deal with missing values
   3. Extract statistics
   4. Report your procedure and conclusions with 4-5 sentences
2. Toy model 2: space-time statistics
   1. Focus on date and location columns
   2. Choose a cleaning strategy
   3. Extract statistics and draw at least two graphs that are insightful
   4. Report your procedure and conclusions with a paragraph
3. Free project
   1. With no column restrictions, choose an interesting hypothesis/model
   2. Clean the data accordingly
      - You can use: `df.describe()`, `df["column"]`, etc.
      - Use at least 5 data cleaning techniques inside a file named `clean.ipynb`
      - Null values, columns drop, duplicated data, string manipulation,
      apply fn, categorize, regex, etc.  
   3. Extract statistics and draw at least 3-4 graphs that are insightful
   4. Show data that validates the conclusions based on your hypotesis in a file
   named `analysis.ipynb`
   5. Build a compelling story-telling around your findings.
   Think of your stakeholders and convince them with your conclusions!
   (Some slides with few text and pretty plots are normally useful)

## Suggested Ways to Get Started

- Examine the data and try to understand what the fields mean before diving into
data cleaning and manipulation methods.
- Break the project down into different steps -- Use the topics covered in the
lessons to form a check list, add anything else you can think of that may be
wrong with your data set, and then work through the check list.
- Use the tools in your tool kit -- your knowledge of Python, data structures,
Pandas, and data wrangling.
-  Work through the lessons in class & ask questions when you need to! Think
about adding relevant code to your project each night, instead of, you know...
procrastinating.
- Commit early, commit often, don’t be afraid of doing something incorrectly
because you can always roll back to a previous version.
- Consult documentation and resources provided to better understand the tools
you are using and how to accomplish what you want.

## How to deliver the project

1. Create a new repo with the name `data-cleaning-pandas` in your github account.
   - Create a `README.md` file on repo root with project documentation
   - At least 1 jupyter notebook is required
   - **DO NOT UPLOAD SHARKs ATTACK DATASET TO GITHUB**
2. Do a `PR` with the link of your repo copy pasted inside
`m1/pandas-project/PROJECT-REPO.md` on our labs repo.

## Links & Resources

- <https://www.kaggle.com/teajay/global-shark-attacks>
- <https://numpy.org/doc/1.18/>
- <https://pandas.pydata.org/>
- <https://docs.python.org/3/library/functions.html>
