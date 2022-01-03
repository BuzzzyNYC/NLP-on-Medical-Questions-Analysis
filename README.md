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
HEALTHCARE PROVIDERS: Providers were mostly asking about the process of treating patients not about specific medical concerns. 

### Terms That Occur Together
HEALTHCARE PROVIDERS
>
  “Magnetic resonance” 
  “computerized tomography” 
  “atrial fibrillation” 
  “myocardial infarction” 
  “pertussis vaccine” 
  “atrial flutter”
>
PATIENTS

>
  “Hello doctor”
  “please help” 
  “burning sensation” 
  “birth control shot”
  “need know”
  “cure liver” 
  “insulin diabetes”
>  
### Common Topics Asked by the Public 
```
Topics (k = 4)
Women’s Reproductive Health
Postnatal Care
Diabetes Symptoms 
General Internal Symptoms
```
Topics generally touch on various symptoms that pertain to the topics above, or general distrust in various treatment methods. Public questions also seem to come from a majority of women patients.

### Common Topics Asked by Health Care Providers
```
Topics (k = 4)
Medical Tests/Screening 
Diagnostic procedures
Medical Diagnosis
Treatment for Diagnosis 
```
Topics tend to generalize diagnostic tests and procedures that result in medical diagnosis. Once diagnosed, medical providers move forward with questions regarding treating symptoms. 

### Common Topics Asked by Both
```
Topics (k = 4)
Women’s reproductive health 
Preventative care
Treatments & Diagnostic Procedures
General Internal Symptoms
```
Topics gear toward understanding what is going on with the patient. Both HCP & Patients mention symptoms as an attempt to diagnose and treat various health conditions. 

### Treatment & Diagnosis Procedures
* PATIENTS: Terms that appear frequently across patient-asked questions: 
 Diagnosed, Normal, Symptom, Test & Level are important in all patient groups.
 
 Patients tend to ask about treatments in doses, antibiotic treatments, pills and therapy. 
 
* Healthcare Providers: Terms that appear frequently across healthcare provider questions:  
 Patient, Pain, Treat, Drug & Diagnosis hold a significance in all provider groups.

 HCPs tend to discuss diagnostic procedures such as biopsy,  X-Rays, MRIs, ultrasound & tomography. 
 
### Preventative Care

Women were more likely to ask about preventative care. 

Patients were most concerned about cancer, tests, breast health and abnormal symptoms across all inquiries.

For HCP providers, terms such as test, indication, normal, history & screening were present across multiple question clusters.

### Woman’s Reproductive Health 
Patients were mostly inclined to ask about reproductive health. Specifically, they asked about pregnancy, sexual healthcare, prenatal and postnatal care. 

Patients were mostly likely to ask about issues regarding menstruation, pregnancy, birth control and ovulation.

Whereas Providers mostly asked about women’s health issues with regards to pregnancy, pap smears, ultrasounds and motherhood. 

# Conclusion
For both HCPs and the general public, there are information gaps with regards to women’s reproductive health and women’s health in general. 

We can see examples of this as shown in the large percentage of women-related issues that made up questions for both sets. 

The majority of reproductive inquiries from both were pregnancy-related. This indicates that medical information for pregnancy may not be as comprehensive for patients or that pregnancy is the main concern for patients seeking medical information online.  

Patients are acutely aware of their own symptoms; they also tend to shop for multiple opinions of possible illnesses from that list of symptoms.

Questions asked by HCPs also tend to look for a second opinion of symptoms affecting patients: they are, in effect, asking on behalf of their patients. 

Questions asked by patients tend to be from women; questions asked by HCPs also tend to be about female patients. 

# Applications

More robust medical education, research and educational outreach focused on women’s health, especially with:
* pregnancy 
* prenatal and postnatal health
* general internal wellness

Federally-backed or board-certified online resource for checking list of symptoms for possible causes as a second-opinion resource for patients and healthcare providers. 
* Provider resource could contain suggestions at new or experimental phase.

HCP-private hub to search and discuss and solicit second opinions specifically for tests and procedures. 




