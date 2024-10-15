# On-the-Notions-and-Predictability-of-Technical-Debt

Technical debt (TD) is a by-product of short-term optimisation that results in longterm
disadvantages. Because every system gets more complicated while it is evolving,
technical debt can emerge naturally. The impact of technical debt is great on the
financial cost for development, management, and deployment, it also has an impact
on the time needed to maintain the project. As technical debt affect all parts of a
development cycle for any project, it is believed that it is a major aspect of measuring
the long-term quality of a software project. 

It is still not clear what aspects
of a project impact and build upon the existing measure of technical debt. Hence
in this experiment, the ultimate task is to try and estimate the generalisation error
in predicting technical debt using software metrics, and adaptive learning methodology.
As software metrics are considered to be absolute regardless of how they are
estimated.

The software metrics were compiled from an established data set; Qualitas.class
Corpus, and the notions of technical debt were collected from three different Static
analysis tools; SonarQube, Codiga, and CodeClimate.

The adaptive learning methodology uses multiple parameters and multiple machine
learning models, to remove any form of bias regarding the estimation.

The outcome suggests that it is not feasible to predict technical debt for smallsized
projects using software-level metrics for now, but for bigger projects, it can be
a good idea to have a rough estimation in terms of the number of hours needed to
maintain the project.
