# Data-Science-for-economist_final-project
Berkeley Summer School 2023 ECON 148

# Gender-Based Analysis of Changes in Mortality Rates Across Different Income Percentiles Over the Years: Is There a Time Trend of Decreasing or Increasing Disparities?


### Group Members: 
Anzhela Baghdasaryan: Modeling, Project Clean-up (25%)

Avitra Phon: Modeling (25%)

Bryan Tan: Background, EDA, Data variable anlaysis and description (25%)

Sahil Gupta-Haji: Interpretation and analysis (25%)

Link to dataset:http://www.equality-of-opportunity.org/data/
From The Association Between Income and Life Expectancy in the United States, 2001-2014
TABLE 15
http://www.equality-of-opportunity.org/data/health/health_ineq_online_table_15.csv

### Project Background and Objective

The association between income and life expectancy is a crucial indicator of health inequality and social justice. A paper published in JAMA in 2016 has shown that higher income is associated with longer life expectancy and lower mortality rates in the United States and other countries. However, the trends and patterns of mortality rates by income percentiles over time and across regions are not well understood. Moreover, the causes of death that contribute to the income-mortality gradient may differ by age, sex, race, ethnicity, and geography.

This project is based on the dataset and the journal article by Chetty et al. (2016), which used data from the National Vital Statistics System (NVSS) and the Internal Revenue Service (IRS) to estimate mortality rates by household income percentiles for the U.S. population aged 40 to 76 years from 2001 to 2014. The article reported several findings, such as:
- The gap in life expectancy between the wealthiest and poorest 1% of individuals was 14.6 years (95% CI, 14.4 to 14.8 years) for men and 10.1 years (95% CI, 9.9 to 10.3 years) for women.
- Individuals in the bottom 1% of the income distribution at age 40 years had life expectancies comparable to those of individuals in countries with much lower life expectancies than the United States, such as Sudan and Pakistan.
- For individuals in the bottom 5% of the income distribution, life expectancy differed substantially across local areas. Conversely, differences in life expectancy across areas were smaller for individuals in higher income groups.
- Life expectancy for low-income individuals was positively correlated with access to health care, quality of healthcare, healthy behaviors, social cohesion, environmental factors, and income inequality.

**The central objectives for this project are:**
- To replicate and validate the main results of the article by Chetty et al. (2016), using descriptive statistics, regression analysis, hypothesis testing, and visualization techniques.
- To explore additional research questions that are not addressed by the article, such as:
        - How do mortality rates by income percentiles vary by sex?
        - How do mortality rates by income percentiles change over time?
        - Is there a time trend of decreasing or increasing disparities in mortality across income levels?
These questions are important to answer because they can provide new insights into the relationship between income and mortality in the United States, and identify potential areas for policy intervention to reduce health inequalities and improve population health. By using quantitative analysis methods, we can rigorously test hypotheses, measure effects, assess uncertainties, and generalize results to wider populations. Quantitative analysis can also help us communicate our findings effectively using graphs, tables, and charts.

The aforementioned paper is titled “The Association Between Income and Life Expectancy in the United States, 2001-2014” and used deidentified US tax records to estimate race- and ethnicity-adjusted life expectancy at 40 years of age by household income percentile, sex, and geographic area.

**Some of the assumptions and limitations made in the paper are:**
- The income measure used in the paper is based on pre-tax household earnings and does not include income from capital gains, which may underestimate the income of the very rich.
- The paper assumes that individuals who die or emigrate are missing at random and that their mortality rates are similar to those observed in the data.
- The paper assumes that the relationship between income and mortality is captured by a Gompertz function, which is a common parametric model for human mortality.
- The study's findings on the relationship between income and life expectancy should not be seen as causal effects due to unmeasured confounding variables.

These assumptions may affect the validity and generalizability of the paper’s findings. However, the paper also performed several sensitivity analyses to test the robustness of the results to different specifications and data sources.

### Data Description
Our project utilizes a dataset compiled from national records detailing mortality rates and income percentiles in the United States, differentiated by gender. The data spans from the years 2001 to 2014. The associated academic paper, titled "Examining the association between income and life expectancy in the United States in the years 2001-2014", provides comprehensive insights into the data and the correlation between income and life expectancy during these years.

The dataset is structured as panel data with yearly granularity. The key feature of our dataset is the 'Year of Death' (yod), as each observation retains the same characteristics for gender and income percentile within the specific year. This feature allows us to examine how mortality rates have changed year over year, providing a detailed temporal snapshot. The scope of our data encompasses a 13-year period from 2001 to 2014, ensuring a comprehensive view of trends and shifts in mortality rates over this timeframe.

The 'Mortality Rate' (mortrate) is designated as the target variable in our study, the variable we aim to predict or explain. On the other hand, the explanatory variables, or features, include 'Gender' (gnd), 'Household Income Percentile' (pctile), 'Age at Death' (age_at_d), 'Year of Death' (yod), and 'Mean Household Income' (hh_inc). These features will aid us in our investigation of the evolution of mortality rates across different income percentiles over time. Furthermore, they will assist in identifying whether there are discernible trends of decreasing or increasing disparities in mortality across different income levels.




