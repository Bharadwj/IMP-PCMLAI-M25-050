# Datasheet Template

As far as you can, complete the model datasheet. If you have got the data from the internet, you may not have all the information you need, but make sure you include all the information you do have. 

## Motivation

- For what purpose was the dataset created? 
-The dataset was created with the intent of providing the scientific community with dataset that closely resemble the legtimate financial dataset without exploiting the individual financial details. 

- Who created the dataset (e.g., which team, research group) and on behalf of which entity (e.g., company, institution, organization)? Who funded the creation of the dataset?
-The dataset simulator was created by Edgar Alonso Lopez-Rojas, Ahmad Elmir and Stefan Axelsson for 28th European Modeling and Simulation Symposium 2016 (EMSS 2016). 
Reference: https://www.researchgate.net/publication/313138956_PAYSIM_A_FINANCIAL_MOBILE_MONEY_SIMULATOR_FOR_FRAUD_DETECTION
 
## Composition

- What do the instances that comprise the dataset represent (e.g., documents, photos, people, countries)? 

-The dataset contains synthetic information around financial transactions for eg: Type of transactions, Account debited and credited etc.

- How many instances of each type are there? 
- Is there any missing data?
-The dataset doesn't contain any missing data due to the very basic nature of the dataset, since most of the financial dataset constrainted are defined to avoid any NULL data. For example a Credit card can't be issued to person without Name and a valid ID or Date of Birth.  
- Does the dataset contain data that might be considered confidential (e.g., data that is protected by legal privilege or by    doctor–patient confidentiality, data that includes the content of individuals’ non-public communications)?
-The dataset doesn't contain any confidential data. The dataset is generated from a random simulator and is generated in fashion to mimic the real world data. 

## Collection process

- How was the data acquired? 
-The dataset is acquired from the Paysim simulator and is scaled down to be manageable for the current project requirement and can be uploaded to GIT. 
- If the data is a sample of a larger subset, what was the sampling strategy? 
-The dataset is a sample of a larger subset, but no specific sampling strategy was deployed. Since the full dataset doesn't contain any duplicate and null values also the data was evenly distributed in the original dataset hence no specific sub-sampling was required.
- Over what time frame was the data collected?
-The data is synthetic data and is generated to mimic the real world data. It can be generated in real time to 

## Preprocessing/cleaning/labelling

- Was any preprocessing/cleaning/labeling of the data done (e.g., discretization or bucketing, tokenization, part-of-speech tagging, SIFT feature extraction, removal of instances, processing of missing values)? If so, please provide a description. If not, you may skip the remaining questions in this section. 
-Column 

- Was the “raw” data saved in addition to the preprocessed/cleaned/labeled data (e.g., to support unanticipated future uses)? 
 
## Uses

- What other tasks could the dataset be used for? 
-The dataset is specifically generated(by PaySim simulator)for detecting the fradulent transactions and may not be useful for any other application, however with some data-preprocessing (Adding customer name) and pruning we can use this dataset for other financial models too.
- Is there anything about the composition of the dataset or the way it was collected and preprocessed/cleaned/labeled that might impact future uses? For example, is there anything that a dataset consumer might need to know to avoid uses that could result in unfair treatment of individuals or groups (e.g., stereotyping, quality of service issues) or other risks or harms (e.g., legal risks, financial harms)? If so, please provide a description. Is there anything a dataset consumer could do to mitigate these risks or harms? 
- Are there tasks for which the dataset should not be used? If so, please provide a description.
-The dataset doesn't contain any NULL and duplicate value due to the financial nature of the dataset. Also the dataset doesn't contain any demographic information that can result in unfair treatment of individuals or groups. 

## Distribution

- How has the dataset already been distributed? 
-The dataset is taken from the PaySim simulator reffered in above section.
- Is it subject to any copyright or other intellectual property (IP) license, and/or under applicable terms of use (ToU)?  
-The dataset is available in Public forum and the authors are credited in the above section.

## Maintenance

- Who maintains the dataset?
The dataset is generated from the simulator reffered above. 

