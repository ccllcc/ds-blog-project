# ds-blog-project
## I. Project context
The project is a part of Udacity Data Science Nano degree program achievement.<br>
I have chosen the data set of StackOverFlow developer survey to conduct my data exploration and to draw insights.

## II. Business understanding
My main question is to explore what are the elements potentially linked to a developer's job satisfaction.<br>
All the questions in the project (blog) are around the job satisfaction topic.<br>
I have prepared 3 to 4 questions related to Job Satisfaction.<br>
### Q1:
How do certain personal interests, such as building things and problem solving, relate to job satisfaction?(Blog)<br>
How job security and diversity affects / relates to job satisfaction?<br>
### Q2:
How company size and company type affects / relates to job satisfaction? (Blog)
### Q3:
How job satisfaction, career satisfaction, weekly hour, salary correlate to each other? (Blog)<br>
### Q4:
Do serious coder has a better job satisfaction or pay?<br>


## III. Data understanding
<p>We I exam the data, I observed there is a large portion of the attributes are non-numerical.<br>
147 columns contains text value, 6 columns are numerical columns.<br>
When it comes to the completeness of the data, only 13 columns with less than 20% null values.</p>

## IV. Modeling, Evaluation
<p>And the end, I tried to build a model to predict job satisfaction using the numerical and non-numerical attributes.I have made the imputation on a two numerical columns, HoursPerWeek and CareerSatisfaction using mean. Those columns related to personal interests, such as BuildingThings, ProblemSolving, CompanyType and size are transfered into numerical ones using the pandas.get_dummies function.</p>

<p>At the end, it turned out that the model performed poor on both training and testing data.
This makes me think about how to improve the model performance, and the different process that I have adopted.
I belive there is a lot of work to be done and a lot of things to learn and try.</p>


## V. Repository structure
> - Data/plot: contains all plots generated from the jupyter notebook<br>
> - Data/ref: contains the link of a blog made by the instructor, as reference<br>
> - Data/survey_results_public: data set used for the project<br>
> - Data/survey_results_schema: file to understand the data<br>
> - .gitignore: file indicating to ignore the change of the file during each commit<br>
> - Readme: explain the project purpose and background, methodology, libraries used for the project<br>
> - satis_analysis: jupyter notebook for data exploration, modeling, plot generation

## VI. Librarie used for the project
Pandas/Numpy/Matplotlib/Seaborn/ScikitLearn/

## VII. Blog link
[What are the elements affect a developer's job satisfaction?]:
https://medium.com/what-are-the-elements-affect-developers-job/what-are-the-elements-affect-a-developers-job-satisfaction-f8eebee65845


## IIX. Github repository
[ds-blog-project]:
https://github.com/ccllcc/ds-blog-project

## IX. Acknowledgement
I have refer to the blog of the instructor as I have chosen the same data set for this blog project, his work inspired me a lot.
[How do you become a developer]:
https://medium.com/@josh_2774/how-do-you-become-a-developer-5ef1c1c68711

### N.B.
There were more stuff tried in jupyter notebook then those were used in the blog.<br>
The modeling was of little usage in illustrating my discoveries, so it was not documented in the blog.<br>

2020-12-08
