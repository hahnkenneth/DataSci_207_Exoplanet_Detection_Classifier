All of our individual code can be found in the /code files directory. We used this to compile the final_code.ipynb file. The data is in the /data file as a .csv file taken from [Kaggle](https://www.kaggle.com/datasets/nasa/kepler-exoplanet-search-results)

From the syllabus...

Final Project
In Weeks 11–14, students will work on a group project (ideally three to four people) that is more
open ended. Groups can choose from a few recommended topics (hosted on Kaggle) or
potentially select their own. Grading will reflect individual contributions, group size, and the
application of concepts from the course to the selected task, including data analysis, modeling,
experiments, and analysis of errors.

From bcourses (https://bcourses.berkeley.edu/courses/1536768) ...

Final Project Rubric
Your slides should include:

Title, Authors
(15%) Motivation: Introduce your question and why the question is interesting. Explain what has been done before in this space. Describe your overall plan to approach your question. Provide a summary of your results.
(15%) Data: Describe in detail the data you are using, including the source(s) of the data, preprocessing applied to the data, and relevant statistics.
(15%) Modeling: Describe in detail the models (baseline + improvement over baseline) that you use in your approach.
(30%) Experiments: Provide insight into the effect of different hyperperameter choices. Please include tables, figures, graphs to illustrate your experiments.
(10%) Conclusions: Summarize the key results, what has been learned, and avenues for future work.
(15%) Code submission: Provide link to your team's GitHub repo. The code should be well commented and organized.
Contributions: Specify the contributions of each author (e.g., data processing, algorithm implementation, slides, etc.). Note that the final project grade is individual, based on each member's contribution and team size.

Description of variables
https://exoplanetarchive.ipac.caltech.edu/docs/API_kepcandidate_columns.html

Transit signal-to-noise
Transit depth
Ingress duration
Transit duration
Impact parameter
Planetary radius

Could do some correlation analysis

Some of these might be interaction terms. 

About 5% of missing data.

Tips: Don't impute with mean or median values, use values outside the range, etc.
Have a unknown value.

Use 0 as missing values.

koi_pdisposition might be our Y
koi_score might be our Y, goal to minimize loss between prediction and koi_score
