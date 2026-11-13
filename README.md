## Question:

Is attending a more expensive college associated with higher earnings after college, and is this relationship different for public and private universities?

## The Data

This is the college scorecard data, publicly available on data.gov. I am using the latest update, noted to be November 2 2026 (accessed November 6 2026).

## The why

College is becoming increasingly expensive at an alarming rate. For many, it has simply become too much and is written off as a bad investment. For others, even if they see it as a good investment they may find that the debt is crippling. I want to explore this dilemma by answering which undergraduate degrees have the best ROI and provide insight to those who see university education as a risky investment.

## Variables

Average annual net price: NPT4_PUB (Public schools) | Quantitative

NPT4_PRIV (Private schools) | Quantitative

Median earnings 10 years after entry: MD_EARN_WNE_P10 | Quantitative

Institution type: CONTROL | Categorical | Private == 2 , Public == 1

Institution name: INSTNM | Identifier |

Predominant Degree: PREDDEG (bachelors == 3) | Identifier

## Repository

Most-Recent-Cohorts-Institution.csv -> csv file containing the college scorecard data I used.

InProgressCollegeChoice.qmd -> quarto file (not rendered) with analysis.
