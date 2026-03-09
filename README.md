#📊 Project Overview
This project automates the extraction and analysis of pharmaceutical safety data to support Competitive Intelligence and Market Access strategies. By connecting directly to the openFDA API, the pipeline standardizes global drug nomenclature and segments patient data across 76 countries.

#🛠️ Methodology & Technical Stack
This project follows a professional ETL (Extract, Transform, Load) workflow:

Extraction (Python/API): Automated ingestion of 5,000+ clinical records using requests and pagination logic (skip/limit).

Data Governance (Fuzzy Matching): Utilized the thefuzz library (Levenshtein Distance) to reconcile Brand vs. Generic names (e.g., Yervoy vs. Ipilimumab), ensuring 100% data integrity in volume reporting.

Strategic Segmentation: Developed business logic to categorize products into Therapeutic Areas (TAs) such as Oncology and Immunology.

Business Intelligence (Power BI): Engineered a dashboard using DAX to visualize market share and patient demographics (Pediatric, Adult, Geriatric).

#📂 Data Source & Attribution
This project utilizes public data provided by the U.S. Food and Drug Administration (FDA).

Source: openFDA Adverse Event API

Database: FDA Adverse Event Reporting System (FAERS)

Dataset Scope: 5,000+ records filtered by Oncology-related indications (malignant neoplasm).

Geographic Reach: Global reports spanning 76 countries.

Attribution: Data provided by the U.S. Food and Drug Administration (https://open.fda.gov).

#⚠️ Disclaimer: This project is for data analytics and portfolio purposes only. An adverse event report does not prove causality, and the data has not been medically validated.
