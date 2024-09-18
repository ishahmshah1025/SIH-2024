# SIH-2024

## Proposed solution:
1. Infrastructure analyzed with object detection models and trained CNNs in real - time to provide information on upkeep of institute’s infrastructure quality
2.  Query based tabular data extraction models + transformers for analyzing authenticated documents to verify compliance with standard requirements/norms
3. Integration with institutional database to cross-check data with existing records
4. ML algorithms implemented to analyze trends in current + historical data, to address potential flags
5. User-friendly dashboard with customizable inspection criteria to provide flexibility
6. Automatically generated comprehensive reports include compliance status, faculty analysis, improvement suggestions for any deficiencies found and more

   ![image](https://github.com/user-attachments/assets/0d33e622-1296-4395-92d7-310ed0096e3c)

## Technology Used:

1. Image Recognition for Facility Analysis: 
YOLOv8 used to assess infrastructure by object detection 
2. NLP for Document Analysis: 
TAPAS for query based tabular extraction to verify compliance with AICTE norms, and pdfplumber for document verification 
3. Pattern Recognition:
Analyzed placement trends using Random Forest models and predict institutional compliance using XGBoost based on inspection scores
4. Frontend & Backend Development: 
Built an interface using HTML, CSS, JS and backend powered by Django, PostgreSQL for structured data, and MongoDB for unstructured data storage
