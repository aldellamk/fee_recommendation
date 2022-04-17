### Analysis for Fee Recommendation Data

Concept:
This analysis is used for looking the quality of the dataset before it will be used for modelling. 
So, here will be only included the EDA summary for this dataset. 
The target for the next modelling is `Profcoll_Fee`, it used for the baseline recommendation price for the next record data that we user will have.

Meaning for each feature on the Dataset:
- `Profcoll_Fee` : Paid fee to the employee for each record
- `NTF` : Fund that was given to a customer for a loan
- `OSP` : Current outstanding principal had by a customer for a loan, when the asset are going to reposses
- `DPD_Beginning` : DPD loan when the asset are going to reposses
- `AMT_LLP_Beginning`: Amount provision based on DPD beginning 
- `AMT_LLP_Projection`: Amount provision based on projection DPD (the next 30 days based on the DPD beginning) 
- `Price_List`: The current price list of the product 
- `OS_LC`: Current outstanding late charge had by a customer for a loan, when the asset are going to reposses
