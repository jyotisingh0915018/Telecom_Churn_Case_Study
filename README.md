# Telecom Churn Case Study 
# Business Problem Overview <a name = "idea"></a>
<div class="text_component ckOutput"><p> In the telecom industry, customers are able to choose from multiple service providers and actively switch from one operator to another. In this highly competitive market, the telecommunications industry experiences an average of 15-25% annual churn rate. Given the fact that it costs 5-10 times more to acquire a new customer than to retain an existing one, customer retention has now become even more important than customer acquisition.
For many incumbent operators, retaining high profitable customers is the number one business goal.
To reduce customer churn, telecom companies need to predict which customers are at high risk of churn.
In this project, you will analyse customer-level data of a leading telecom firm, build predictive models to identify customers at high risk of churn and identify the main indicators of churn. </p>

# Understanding and Defining Churn <a name = "idea"></a>
There are two main models of payment in the telecom industry - postpaid (customers pay a monthly/annual bill after using the services) and prepaid (customers pay/recharge with a certain amount in advance and then use the services).
In the postpaid model, when customers want to switch to another operator, they usually inform the existing operator to terminate the services, and you directly know that this is an instance of churn.
However, in the prepaid model, customers who want to switch to another network can simply stop using the services without any notice, and it is hard to know whether someone has actually churned or is simply not using the services temporarily (e.g. someone may be on a trip abroad for a month or two and then intend to resume using the services again).
Thus, churn prediction is usually more critical (and non-trivial) for prepaid customers, and the term ‘churn’ should be defined carefully.  Also, prepaid is the most common model in India and southeast Asia, while postpaid is more common in Europe in North America.
This project is based on the Indian and Southeast Asian market.

# Analysis Steps: <a name = "idea"></a>

# 1. Data Preparation: <a name = "idea"></a>
The data was loaded from a CSV file named telecom_customer_churn.csv.
Descriptive statistics were computed for key variables.

# 2. Frequency Analysis: <a name = "idea"></a>
Frequencies were calculated for various customer service subscriptions to understand their distribution among customers.

# 3. Cross-tabulation: <a name = "idea"></a>
Cross-tabulation was performed to explore the relationship between churn category (churned vs. not churned), churn reason, and service subscriptions.

# 4. Findings: <a name = "idea"></a>
EDA observations: there is a considerable drop in recharge, call usage and data usage in the 8 th month.

Factors having significant impact on churn are: <a name = "idea"></a>
1. Tenure: customers with longer durable of time within company
are less likely to churn.
2. Contract type: month to month customers are more likely to
churn than longer term contract clients.
3. Payment method: people with electronic cheque are more
likely to churn in comparison with other payment modes
4. Monthly charges: highly monthly charges customers are more
likely to churn
5. Minutes of Usage: important factor affecting the churn

# 5. Recommendations : <a name = "idea"></a>
1. Provide incentives to loyal customers or high value customers i.e. stayed with the company for a longer period of time.
2. A sudden drop in local minutes might be due to the poor network or unsuitable customer plans, efforts shall be made on both the parts.
3. Encouraging customers for other payment modes than electronic cheques.
4. Routine feedback calls for customer retention
5. Various attractive offers to customers showing sudden drop in total amount spent on calls & data recharge in action phase
6. Provide better value for money by offering packages.



