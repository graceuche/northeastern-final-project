# The Final Project for Northeaster University Accelerated Data Analytics Professional Certification Program

[Link to a Deepnote](https://deepnote.com/project/Final-Course-Project-04eeb7cc-c014-42cc-9688-959f70fd96bb/%2Fvisual_analysis.ipynb)

## Project Requirements

To complete the Data Analytics course at [Norheastern Univeristy](https://www.northeastern.edu/) I had to produce the final project to fulfill the following criteria:

1. Provide the project rationale.
1. Use a dataset of a minimum of 1000 records.
1. Provide evidence of data validity (explain the source of the data)
1. Utilizing a minimum of 3 data technologies, e.g., Pandas, Plotly, Google Sheets
1. Make regular ‘commits’ on GitHub, i.e., a minimum of 2 commits per working day
1. Make Pull Requests and request code reviews
1. Use data visualization: a minimum of 5 different types of data visualization from a minimum of 2 libraries, e.g., Plotly, Seaborn, Matplotlib, Google Sheets
1. Document the project in a Readme
1. Apply Agile methodologies, such as Kanban and GitHub issues
1. Use statistical and machine learning analysis, e.g.:
      - Linear regression
      - Logistical regression
      - Clustering
      - Classification
      - Text analysis
      - Hypothesis testing
1. Comment all code blocks
1. Present the project

## Rationale 

### Overall Rationale

Healthcare insurance plan in the United States is an agreement between an insurer and an insured. In exchange for premium pay­ments, the insurer agrees to cover certain medical services that are specified in the plan. Sounds simple and good, but not quite. 
Medical expenses are difficult to estimate due to individual circumstances and any existing comorbidities. As a result, the diagnosis, treatment, and recovery  of certain conditions on patient A will differ from patient B with similar diagnosis.
For example, patient A might have comorbidities that could affect the treatment, resulting in longer hospital stay and resources. On the other hand, patient B may respond to treatment and get discharged within the normal hospital stay.
Also,  some conditions are more prevalent for certain segments of the population. For instance, lung cancer is more likely among smokers than non-smokers. Heart disease is more likely among overweight individuals. As a result, insurance companies are more likely to pay more towards such individuals' medical care.

The main reason for choosing this dataset is because it comprises of some major factors that drive healthcare insurance cost in the United States, namely, age, sex, and comorbidities. Region on the hand would be a factor  depending on type of insurance -government funded or private. The columns of this  dataset help to investigate and understand the risk of underwriting in Health Insurance, the interplay of various attributes of the insured, and see how they affect the insurance premium.
 
In order for an insurance company to make money, it needs to collect more in yearly premiums than it spends on medical care for its beneficiaries. As a result, insurers invest a great deal of time and money to develop models that accurately forecast medical expenses. There have been many attempts to build a reliable machine learning algorithm to predict health insurance charges. However, none of the existing algorithms are fine-tuned to perfection yet. This project will compare two approaches to predicting healthcare charges. 
(decide which algorithms to compare)

### Personal Rationale

(add my biography)(add that I would focus on descriptive statistics in depth as a beginner)
(add that I would include lots of data visualization as that is my favorite part of data analytics)

## Data Set

For this analysis, I have used a simulated dataset. I have found it on [Kaggle](https://www.kaggle.com/). I was looking for a beginner dataset as my experience using Python and Pandas was exactly 12 weeks, however, I also really wanted to explore healthcare or/and health insurance data.

When I came across [this dataset](https://www.kaggle.com/datasets/mirichoi0218/insurance) it was clear from the discussion on Kaggle where it came from.

It was synthesized using demographic statistics from [the U.S. Census Bureau](https://www.census.gov/). Therefore, it approximately reflects the real-world conditions but the data is not for real people, hence I could use it without worrying about privacy issues.
These data were created for a book, “Machine learning with R” by Brett Lantz, available at [Northeastern Library](https://library.northeastern.edu/). Reading the relevant chapters in the book helped me get a better idea on how medical costs are predicted.

To sum up, the data set I am using is synthetic but realistic, thus I could get a good idea of the statistical metrics in the American healthcare system and yet not risk violating any privacy laws.

## Tech Stack

For my project, I have chosen the following stack:

- [Pandas](https://pandas.pydata.org/pandas-docs/stable/)
- [Plotly](https://plotly.com/)
- [Matplotlib](https://matplotlib.org/)

## Style Guides

### Style Guides for [Seaborn](https://seaborn.pydata.org/) Visualizations

All [Seaborn](https://seaborn.pydata.org/) visualizations should have titles in titlecase, e.g.,:

```
g = sns.catplot(x='region', y='charges',
            data=insurance_premium,
            hue='sex',
            kind='point')
g.fig.suptitle('Charges vs. Region', y=1.1) 
plt.show()
```

## Team and Processes

### Team

|Name|Github|LinkedIn|
| :------: | :----------------------------------------------------------------------------------------------: | :--------------------------------------------------------------------------: |
|  Katia - **Team Lead**   | [![GitHub icon](https://cdn4.iconfinder.com/data/icons/iconsimple-logotypes/512/github-16.png)](https://github.com/missKatiaPunter)|[![Linkedin](https://www.linkedin.com/favicon.ico)](https://www.linkedin.com/in/katia-punter-6313ba177/)
|  Grace - **Data Analyst**  | [![GitHub icon](https://cdn4.iconfinder.com/data/icons/iconsimple-logotypes/512/github-16.png)](https://github.com/graceuche) | [![Linkedin](https://www.linkedin.com/favicon.ico)](https://www.linkedin.com/in/grace-uche-mba-rhia-epic-credential-trainer-677022152/)|


### Processes

The basic Kanban board from GitHub Projects was used for Project Management 👇🏼

![Screenshot of the board](Grace-board.png)
