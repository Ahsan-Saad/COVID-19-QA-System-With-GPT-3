# COVID-19 Research Question Answering System  

### Overview  
This repository contains the implementation of a **Question Answering System** built during the COVID-19 pandemic. The system uses the **COVID-19 Open Research Dataset (CORD-19)**, a rich collection of over 1,000,000 scholarly articles, including 400,000 full-text papers, on COVID-19, SARS-CoV-2, and related coronaviruses.  

Our system was designed to help researchers, healthcare professionals, and the general public by providing authentic answers to their COVID-19-related queries. The answers were generated from credible research papers, ensuring reliability and authenticity. Additionally, the system provided references to the source research papers for transparency and further exploration. 

I worked in this project along side Prof. Dr. Ashrafuzzaman Khan, Kaysarul Anas, and Rofiqul Alam Shehab.

### Forking Reason
This project was collaboratively developed as part of our undergraduate research, with all code and commits made from a shared lab computer under one GitHub ID. As a result, my individual GitHub ID does not appear in the commit history. I have forked this repository to my personal account to showcase my team's work.

### Features  
- **Question Answering**: Users can input natural language questions related to COVID-19.  
- **Authentic Responses**: The system generates responses based on validated research papers in the CORD-19 dataset.  
- **Source Linking**: Each answer includes a citation or link to the source paper for verification.  
- **Scalable Design**: Built with modularity in mind to adapt to other scientific domains or datasets in the future.  

### Dataset  
We utilized the **CORD-19** dataset provided by the White House and a coalition of leading research groups.  
- **Details**:  
  - Over **1,000,000 scholarly articles**, including **400,000 full-text papers**.  
  - Focused on COVID-19, SARS-CoV-2, and related coronaviruses.  
- **Source**: [CORD-19 Dataset on Kaggle](https://www.kaggle.com/allen-institute-for-ai/CORD-19-research-challenge)  

### How It Works  
1. **Data Preprocessing**:  
   - Parsed and cleaned the dataset to extract relevant sections, such as abstracts and conclusions, for efficient querying.  
   - Tokenized and indexed the text for fast retrieval.  

2. **Question Answering Pipeline**:  
   - Implemented a retrieval-based model to identify relevant research papers for each query.  
   - Used a transformer-based language model (e.g., BERT) fine-tuned for question answering tasks.  
   - Extracted contextually relevant answers from the retrieved documents.  
