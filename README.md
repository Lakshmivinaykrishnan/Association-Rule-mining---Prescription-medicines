#  Association Rule Mining on Prescription Data

##  Research Question

**What are the most common and clinically significant prescription combinations among patients based on historical prescription data?**

##  Project Overview

This project uses association rule mining to identify the most frequent and meaningful patterns in prescription data. The goal is to analyze historical records to uncover how certain medications are commonly prescribed together.

By applying market basket analysis techniques such as the Apriori algorithm and evaluating metrics like **support**, **confidence**, and **lift**, we can:

- Discover frequent itemsets of drugs.
- Understand clinically relevant co-prescription behaviors.
- Suggest opportunities to improve drug prescribing practices.

##  Contents

-  Import the dataset with prescription records, clean it, and prepare it for analysis
-  Explanation of Market Basket  
-  Transaction Example 
-  Transform the records using the TransactionEncoder from the mlxtend library 
 - apriori()  to identify frequent itemsets in the dataset
 - association_rules()  to generate the association rules
-  Association Rules Table  
-  Top Three Rules
-  Visualization
-  Significance of Support, Lift, and Confidence  
-  Practical Significance of Findings  
-  Course of Action  

## 🛠️ Technologies Used

- Python
- Pandas
- mlxtend (for Apriori and association rules)
- Jupyter Notebook
