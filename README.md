# Week 3 Class Activity

## Assessing bias in the Wikipedia Talk Corpus

The objective of this code is to analyse bias in the Toxicity data annotated from the Wikimedia Talk Corpus. The main document with the analysis can be found [here](https://docs.google.com/document/d/1ILZgf6DjLGt0C3EwsSzOzrNcNV-FV85AwECKLFR5dfA/edit?usp=sharing).



## Data Source

Wulczyn, Ellery; Thain, Nithum; Dixon, Lucas (2016): Wikipedia Detox. figshare. [doi.org/10.6084/m9.figshare.4054689](doi.org/10.6084/m9.figshare.4054689)

The data set contains comments from 2001-2016 that were scored on their level of toxicity by approximately 10 different crowdworkers.

The toxicity score is defined as:
| toxicity_score | Description                                                                                                                                  |
|----------------|----------------------------------------------------------------------------------------------------------------------------------------------|
| -2             | Very Toxic (A very hateful, aggressive, or disrespectful comment that is very likely to make you leave a discussion)                         |
| -1             | Toxic (A rude, disrespectful, or unreasonable comment that is somewhat likely to make you leave a discussion                                 |
| 0              | Neither                                                                                                                                      |
| 1              | Healthy Contribution (A reasonable, civil, or polite contribution that is somewhat likely to make you want to continue a discussion)         |
| 2              | Very Healthy Contribution (A very polite, thoughtful, or helpful contribution that is very likely to make you want to continue a discussion) |

In addition, the dataset contains information about the worker's demographics.

The Toxicity dataset can be downloaded from [The Personal Attacks Figshare dataset](https://figshare.com/articles/Wikipedia_Talk_Labels_Personal_Attacks/4054689), and the schema can be found in the [dataset docummentation page](https://meta.wikimedia.org/wiki/Research:Detox/Data_Release#Toxicity).



## Analysis Files
 * data_statement_exploration.ipynb: Has the code necessary to obtain the distribution of toxicity_score, as well as range of dates, and number of comments and workers.
 * analysis_of_worker_demographics.ipynb: Has the code with analysis for demographics of the crowdworkers who annotated the comments

## License

Plese refer to the project [MIT license](LICENSE) for more details.
