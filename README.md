<div style="border-radius: 40px; border: #5E5772 solid; padding: 12px; background-color: #3383; font-size: 150%; text-align: left;">

<h3 align="center"><font color='#300000'>TELCO CHURN ANALYSIS</font></h3>

<h4 align="left"><font color='#30000' size=5%>To Do :</font></h4>
    
<li> Cleaning dataset for classification</li>
    
<li> Some analysis and statistics</li>
    
<li> ML, ANN
    
    

<h3 align="left"><font color='#300000' size=5%>ABOUT DATA:</font></h3>

The Telco customer churn data contains information about a fictional telco company that provided home phone and Internet services to 7043 customers in California in Q3. It indicates which customers have left, stayed, or signed up for their service. Multiple important demographics are included for each customer, as well as a Satisfaction Score, Churn Score, and Customer Lifetime Value (CLTV) index.

For more details, see the dataset description in https://community.ibm.com/community/user/businessanalytics/blogs/steven-macko/2019/07/11/telco-customer-churn-1113, even though the dataset used here is an older (and reduced) version. 
    

<div style="border-radius: 10px; overflow: hidden; text-align: left;">
    <img src="https://miro.medium.com/v2/resize:fit:1000/1*n_0BmJJ8nRLLTI_POtfCBg.png" alt="Churn" width="900"></div>
</div>

## Features

**customerID:** Unique customer identifier.

**gender:** Customer's gender .

**SeniorCitizen:** Indicates if the customer is 65 or older: Yes, No

**Partner:** Indicates if customer has a partner .

**Dependents:** Indicates if the customer lives with any dependents: Yes, No. Dependents could be children, parents, grandparents, etc.

**tenure:** Number of months with the company.

**PhoneService:** Indicates if the customer subscribes to home phone service with the company: Yes, No

**MultipleLines:** Indicates if the customer subscribes to multiple telephone lines with the company: Yes, No

**InternetService:** Indicates if the customer subscribes to Internet service with the company: No, DSL, Fiber Optic, Cable.

**OnlineSecurity:** Indicates if the customer subscribes to an additional online security service provided by the company: Yes, No

**OnlineBackup:** Indicates if the customer subscribes to an additional online backup service provided by the company: Yes, No

**DeviceProtection:** Indicates if the customer subscribes to an additional device protection plan for their Internet equipment provided by the company: Yes, No

**TechSupport:** Indicates if the customer subscribes to an additional technical support plan from the company with reduced wait times: Yes, No

**StreamingTV:** Indicates if the customer uses their Internet service to stream television programing from a third party provider: Yes, No. The company does not charge an additional fee for this service.

**StreamingMovies:** Indicates if the customer uses their Internet service to stream movies from a third party provider: Yes, No. The company does not charge an additional fee for this service.

**Contract:** Indicates the customer’s current contract type: Month-to-Month, One Year, Two Year.

**PaperlessBilling:** Indicates if the customer has chosen paperless billing: Yes, No

**PaymentMethod:** Indicates how the customer pays their bill: Bank Withdrawal, Credit Card, Mailed Check

**MonthlyCharges:** Indicates the customer’s current total monthly charge for all their services from the company.

**TotalCharges:** Indicates the customer’s total charges, calculated to the end of the quarter specified above.

**Churn:** Yes = the customer left the company this quarter. No = the customer remained with the company. Directly related to Churn Value.
