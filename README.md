# MSFT_operations
In terms of business, an Invoice is a request submitted to Microsoft Operations for processing an purchase order or refund or expense. A typical Order-to-Cash process for businesses involves accounts receivable collection after an invoice is issued to the customer. A usual payment term of 30, 45 or 60 days is often provided for the customer to make full payment of the invoiced amount. However, many businesses face a similar problem of having customers who do not pay on time, and will have to take intervention actions to remind their customers to pay their outstanding invoices. Such intervention actions cost money and time
Invoice Payment predictions can be used to optimize payment strategies. By identifying invoices that are likely to be paid late, operations team can focus on customers who are likely to have large amounts of overdue, which in turn can lead to lower Days Sales Outstanding (DSO) and better visibility into future cash flow. An Invoice undergoes following four main  stages:
 

The above mentioned four stages can still further explained by the below diagram based on the date it has taken to process

 

By understanding the business and getting input from the operations team. Dates columns are converted mainly into below four days  
1.Received Days
2.Processing Days
3.Days to approval
4.Days to be cleared
5.Clearing days
The formula to calculate those days are mentioned below. (If nullvalue in Formula 1 Apply Formula2)
Stages	Formula1	 Formula 2
Received Days	Invoice Date – Receipt date	 Invoice Date - Submit date
Processing days	First POC assignment date - Submit date	Receipt date - Submit date 
Days_to_approval	Submit date-Posting date 	 Nil
Paid Days	Clearing date- Bline date	Clearing date - Invoice date
DaystobeCleared	Posting date - Netdue date	 Nil


