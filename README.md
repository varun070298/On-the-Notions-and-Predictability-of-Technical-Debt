# On-the-Notions-and-Predictability-of-Technical-Debt

Technical debt (TD) is a by-product of short-term optimisation that results in longterm disadvantages. Because every system gets more complicated while it is evolving, technical debt can emerge naturally. There are mainly 7 metrics that affect the technical debt score, they are:
1.	Bugs
2.	Code quality-
  a.	Cyclomatic complexity
  b.	Class coupling
  c.	Lines of code
  d.	Depth of inheritance
3.	Cycle time
4.	Code churn
5.	Code Coverage
6.	Code ownership
7.	Technical debt ratio (TDR) - (Remediation Cost ÷ Development Cost) × 100 = TDR

The impact of technical debt is great on the financial cost for development, management, and deployment, it also impacts the time needed to maintain the project. As technical debt affect all parts of a development cycle for any project, it is believed that it is a major aspect of measuring the long-term quality of a software project. 

It is still unclear what aspects of a project impact and build upon the existing measure of technical debt. Hence in this experiment, the ultimate task is to try and estimate the generalisation error in predicting technical debt using software metrics, and adaptive learning methodology. As software metrics are considered to be absolute regardless of how they are estimated.

The software metrics were compiled from an established data set; Qualitas.classCorpus, the data set can found here: http://java.labsoft.dcc.ufmg.br/qualitas.class/index.html and the notions of technical debt were collected from three different Static analysis tools; SonarQube, Codiga, and CodeClimate.

The adaptive learning methodology uses multiple parameters and multiple machine learning models, to remove any form of bias regarding the estimation.

The outcome suggests that it is not feasible to predict technical debt for smallsized projects using software-level metrics for now, but for bigger projects, it can be a good idea to have a rough estimation in terms of the number of hours needed to maintain the project.

## Research Questions
RQ1 

Is the notion of technical debt the same across static analysis tools? [Perhaps analyse the other higher-level quality goals, too]

RQ2 

Which of the low-level metrics  are the most important predictors for technical debt and other aggregated quality goals?

RQ2[a]

Which score(s) correlate most significantly with technical debt?

RQ3

Can a regression model trained on low-level metrics for predicting technical debt achieve an acceptable performance?

The Final Report is available here: https://lnu.diva-portal.org/smash/record.jsf?pid=diva2%3A1794704&dswid=-3082
