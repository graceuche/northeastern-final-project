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

My name is Grace Uche. I am a Professional Registered Health Information Administrator with a Master Degree in Business Administration. I am also a Licensed Health and Life Insurance Broker. As a Health Information Management professional, for over 15 years, I have had the opportunity to practice and work in different healthcare settings. Most of my work has been in educating and training  students in both Associates and Bachelors degrees in the Health Information Management programs. I help students to successfully complete the program, sit and pass the national certification exams, and obtain a job in the field.

The  quest for knowledge drove me into Health and Life Insurance because I wanted to understand how insurance companies operate, factors that determine insurability and coverage suitability. Furthermore, I wanted to explore situations that might deter individuals from getting coverage.

As an educator, I have successfully taught courses in Data Management. However, as a coder I was an absolute beginner 12 weeks ago. Therefore, I was set to produce a final project with an extensive Exploratory Data Analysis section which should allow me to practice and to demonstrate  my newly acquired Python skills.

During the 12 weeks of the Data Analytics Career Accelerator course I developed passion for Data Visualization, so another on of my personal goals was to explore various Data Visualization libraries in Python and assess their suitability for various stages of Exploratory Data Analysis.

To sum up, I set to myself the following personal goals:
- gain personal knowledge about the health insurability of the American population by exploring a representative sample of the USA population
- visualize a representative sample of the USA population by factors that determine health insurance charges
- explore summative statistics of the representative sample of the USA population by factors that determine health insurance charges
- compare some machine learning algorithms that allow predicting health insurance charges

I wanted to gain more knowledge and experiences in the health insurance sector that could transfer into various roles..



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
