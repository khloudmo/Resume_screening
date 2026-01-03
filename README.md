# Resume Screening using NLP

This project uses **NLP and Transformers** to automatically screen resumes and match them with job descriptions.

##  Features
- Extracts text from PDF resumes
- Cleans and preprocesses text
- Generates semantic embeddings using SentenceTransformer (`all-mpnet-base-v2`)
- Calculates cosine similarity between resume and job descriptions
- Displays top 10 matching jobs with score and estimated seniority level
- Extracts technical skills automatically

## Tech Stack
- Python
- Pandas, NumPy, scikit-learn
- Sentence Transformers
- PyPDF2

## Example Result

 Top Matching Jobs for Your Resume:
--------------------------------------------------------------------------------------------------
 Lionbridge Internet Assessor
   Match Score: 45.73%  |  Level: Entry
   Description: The team at Lionbridge Technologies with solution
centres in 25 countries worldwide is recruiting part-time self-employed
workers who are fluent speakers in Armenian and English who are based in
Armenia to join its team of Internet Assessor.
The ...
----------------------------------------------------------------------------------------------------
 Internet Assessor
   Match Score: 44.73%  |  Level: Entry
   Description: The team at Lionbridge Technologies is currently
recruiting self-employed workers who are based in Armenia to join its
team of Internet Assessor. The main aim of the work is to improve a

search engines results for all web users worldwide. The work...
