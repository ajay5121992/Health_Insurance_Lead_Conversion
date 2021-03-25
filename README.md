# Health_Insurance_Lead_Conversion
Converting the leads for health insurance company which basically helps the lead team to target right customer in order to achieve maximum and optimum sale target



Problem Description:-

Your Client FinMan is a financial services company that provides various financial services like loan, investment funds, insurance etc. to its customers. FinMan wishes to cross-sell health insurance to the existing customers who may or may not hold insurance policies with the company.

The company recommend health insurance to it's customers based on their profile once these customers land on the website. Customers might browse the recommended health insurance policy and consequently fill up a form to apply. When these customers fill-up the form, their Response towards the policy is considered positive and they are classified as a lead.

Once these leads are acquired, the sales advisors approach them to convert and thus the company can sell proposed health insurance to these leads in a more efficient manner.
Now the company needs your help in building a model to predict whether the person will be interested in their proposed Health plan/policy given the information about:

Demographics (city, age, region etc.),
Information regarding holding policies of the customer,
Recommended Policy Information




Data Dictionary of historical data:-


ID---Unique Identifier for a row

City_Code---Code for the City of the customers

Region_Code---Code for the Region of the customers

Accomodation_Type---Customer Owns or Rents the house

Reco_Insurance_Type---Joint or Individual type for the recommended insurance  

Upper_Age---Maximum age of the customer 

Lower _Age---Minimum age of the customer

Is_Spouse---If the customers are married to each other (in case of joint insurance) 

Health_Indicator---Encoded values for health of the customer

Holding_Policy_Duration---Duration(in years) of holding policy(policy that cust has already subscribed to with the cmp)

Holding_Policy_Type---Type of holding policy

Reco_Policy_Cat---Encoded value for recommended health insurance

Reco_Policy_Premium---Annual Premium (INR) for the recommended health insurance

Response (Target)	

0 : Customer did not show interest in the recommended policy,

1 : Customer showed interest in the recommended policy
