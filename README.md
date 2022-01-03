# CUS 635 - Web Data Mining Project: Collection and Processing of Medical Questions

## Purposes:
Understanding customers' needs often require to investigate and analyze data outside an organization. In this project, we learned how t identify useful sources of data, web scraping data, data preprocessing, and data analysis. 

## Project Description
When new treatment options become available in the market, there is a significant increase of questions by HealthCare Practitioners (HCP, e.g. family doctors) before the treatment is prescribed to their patients as they have to evaluate the risk-benefit profile of the new product.
Understanding these questions can produce useful insight into the needs of HCP and prepare to fulfill these needs with products and information that address real medical necessities.

## Tasks
In this research, the focus was on the data acquisition, cleaning, and Named Entity Recognition (NERs). 

## Data Understanding & Acquisition
Data was acquired using web scraping tool, Python Beautiful Soup, from reliable medical websites.

## Data Cleaning
The data preprocessing includes:
- Removing Punctuation & Stopwording
- Lemmatization
- Build Vocabulary
- Lexical Diversity
- Counting Words
- Frequency Distribution
- Finding Important Words
- Collocations, 2-grams & Co-Occurences

## Data folder
1. File provider.txt contains data extracted from the National Institute of Health's Clinical Questions Collection (1999 - 2003), a “repository of questions that have been collected between 1991 – 2003 from healthcare providers in clinical settings across the country.”
2. patient.txt contains questions of a medical nature asked by the general public from two sources:
- The Medical Question Pairs (MQP) Dataset, a list of patient-asked questions randomly sampled from a crawl of HealthTap
- Patient-asked questions scraped from www.thecorrect.com

## Findings
### Insights From the Most Frequent Words
PATIENTS: Most of the concerns from patients were pregnancy related. 
![image](https://user-images.githubusercontent.com/87792252/147958263-f47edbf1-af97-45ac-9d10-cffe9dde0857.png)

HEALTHCARE PROVIDERS: Providers were mostly asking about the process of treating patients not about specific medical concerns. 

