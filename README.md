# ds-blog-project
I. Project context
The project is a part of Udacity Data Science Nano degree program achievement.
I have chosen the data set of StackOverFlow developer survey to conduct my data exploration and to draw insights.

II. Business understanding
My main question is to explore what are the elements potentially linked to a developer's job satisfaction.
All the questions in the project (blog) are around the job satisfaction topic.
I have prepared 3 to 4 questions related to Job Satisfaction.
Q1:
How do certain personal interests, such as building things and problem solving, relate to job satisfaction?(Blog)
How job security and diversity affects / relates to job satisfaction?
Q2:
How company size and company type affects / relates to job satisfaction? (Blog)
Q3:
How job satisfaction, career satisfaction, weekly hour, salary correlate to each other? (Blog)
Q4:
Do serious coder has a better job satisfaction or pay?


III. Data understanding
We I exam the data, I observed there is a large portion of the attributes are non-numerical.
147 columns contains text value, 6 columns are numerical columns.
When it comes to the completeness of the data, only 13 columns with less than 20% null values.

IV. Modeling, Evaluation
And the end, I tried to build a model to predict job satisfaction using the numerical and non-numerical attributes.
I have made the imputation on a two numerical columns, HoursPerWeek and CareerSatisfaction using mean.
Those columns related to personal interests, such as BuildingThings, ProblemSolving, CompanyType and size are transfered into numerical ones using the pandas.get_dummies function.

At the end, it turned out that the model performed poor on both training and testing data.
This makes me think about how to improve the model performance, and the different process that I have adopted.
I belive there is a lot of work to be done and a lot of things to learn and try.

N.B.
There were more stuff tried in jupyter notebook then those were used in the blog.
The modeling was of little usage in illustrating my discoveries, so it was not documented in the blog.

2020-12-07