# Problem Statement:
- Classify 20 different types of cancer based on genome data (data related to the structure and function of an organism's genome).
- Classify multiple types of cancers.
- Enhance early detection strategies.

# About Data:
- Genetic Variation Features:
    - Includes genomic coordinates, variant classifications, allele information, and variant types.
- Clinical and Lifestyle Information:
    - Encompasses clinical data such as days to death, smoking habits, weight, alcohol history, and BMI.
- Demographic and Sample Specifics:
    - Covers demographic details like gender and ethnicity, along with sample identification data like project ID and sample barcodes.

# Techniques:
- Data cleaning using regex
- Data Preprocessing
- Feature engineering and selection
- cross validation and hyperparameter tuning


#Approach:
- Cleaned vast amount of data using regex. 
- Constantly interacted with NIH to get more understanding of the data which helped forming it for model building.
- Performed data preprocessing and feature engineering.
- To improve the score, compared several models, implemented cross validation stategy, hyperparameter tuning.
- Deployed the model seamlessly using AzureML for easy access and utilization. Users can conveniently access predictions by simply filling in their details on the website.**
