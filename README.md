# Coders_of_Bangalore_Data_Pipeline
A Python-based automated data engineering pipeline that parses unstructured Instagram metadata into structured JSON formats for categorical tech-community analysis.


# Coders of Bangalore: Unstructured Data Pipeline

### The Challenge
Faced with a 24-hour high-pressure "Sam Altman" challenge: Transform raw, messy Instagram follower data into a structured format to answer key business questions about the Bangalore tech ecosystem.

### Technical Implementation
* **Data Parsing:** Developed a robust Python script to handle inconsistent text formatting from `finaldata.txt`.
* **Feature Engineering:** Implemented logic to normalize follower/following counts (handling 'K' and 'M' suffixes) into integer values.
* **JSON Transformation:** Converted unstructured chunks into a standardized `data.json` for 100+ profiles.
* **Categorical Insights:** Identified 34 distinct tech-creator categories (e.g., Founders, Data Scientists, MLOps).

### Tech Stack
* **Language:** Python
* **Libraries:** JSON, OS 
* **Environment:** Jupyter Notebook 
### Key Metrics Extracted
- Maximum post count (Account: `bangalore_engineers_diary`).
- Maximum follower count (Account: `_anujsinghal`).
- Categorical distribution across 34 tech niches.
