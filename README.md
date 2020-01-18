
# Medical Cost in USA: a Data Visualisation Project 

The goal of this project is to analyse medical costs in the USA and extract the principal factors in expensive hospitalization.


## Data

The dataset used for this project can be found [here](https://www.kaggle.com/mirichoi0218/insurance).

Here is the list of features in this dataset :
* age: age of primary beneficiary
* sex: insurance contractor gender, female, male
* bmi: Body mass index, providing an understanding of body, weights that are relatively high or low relative to height, objective index of body weight ($kg / m ^ 2$) using the ratio of height to weight
* children: Number of children covered by health insurance / Number of dependents
* smoker: Smoking
* region: the beneficiary's residential area in the US, northeast, southeast, southwest, northwest.
* charges: Individual medical costs billed by health insurance

To go further in the analysis, I added a column to this dataset:
* BMI_range: range of body mass index depending on gender and age; categorical ('too low', 'optimal', 'acceptable', 'too high'). Data web scraped from Table 1 of [this article](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4681110/).


## Tools

* Python
* Pandas
* requests
* BeautifulSoup
* Matplotlib
* Seaborn

