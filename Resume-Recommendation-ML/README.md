# resume_recommendation
This project is making a resume recommendation system for particular job.

The data can be found following the link:

https://drive.google.com/drive/folders/139Kjbd1r8q931_BgBzoNo8umyYrVC48e?usp=sharing

Data include: 
job_posting.dat: including job posting that have been extract from multiple career website.
job_posting.json: a clean file of job_posting.dat
resume.rar: a file contains several resumes.

Main files:
cleaning_extracting_job_posting.ipynb: 
        This touches is the very first step of analyzing textual data, i.e., extracting data
        from unstructured text files. a data-set contains information about the job advertisements, e.g., job title, job description, start
        date, required qualifications. The task is to extract the data and transform the data to the XML and JSON format. 
        
preprocessing_resume.ipynb: 
        This touches is the next step of analyzing textual data, i.e., converting the extracted
        data into a proper format. In this task, we are trying too preprocess a set of resumes and convert them into numerical representations (which are suitable
        for input into recommender-systems/ information-retrieval algorithms)
        
resume_recommendation.ipynb:
        In this task, we will recommend the top 10 resumes that you think are the best fit
        for the first 500 job advertisements
