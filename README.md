# Data-related-salaries
The objective is to do EDA on data related job postings (USA). Later we can try to predict a salary using job posting information.

![job_desc](description_wordcloud.png)
Words used in job postings.

# Why?
When applying for a data related job (Data scientist, Data Analyst...), it can be hard to forget how well some companies can pay for your time. Of course, as a mathematical person, the compensations can be a deciding factor between two otherwise similar jobs. The point of the whole tool is to help you understand what different positions are paying, which can then be leveraged in the interviews for your own benefit. Do not let employers lowball you!

# Results:
We managed to get 60% accuracy with our models. Such accuracy is not necessarily bad considering our data and the number of categories predicted (3-10).
Categorical values of the state where the job location was surprisingly dominant in the salary ranges. California was the top tech hub and there the salaries were significantly greater than anywhere else according to the data. Though, within the state of California there were many jobs that were low salaried, making the predictions quite inaccurate.

To improve our results we should consider using neural nets on the job description texts.


# TODO:

- [x] Read the data and clean it
- [x] Perform EDA.
    - We do this to get a clearer picture of the dataset.
    - [x] Re-do with new data and add section about the data given title
- [x] Create a prediction/classifier model and try to predict the salary/salary range when given information about the job.
- [ ] ~~Dockerize and deploy, so that anyone can use the tool~~
