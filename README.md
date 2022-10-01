## ER DIAGRAM OF BANK MANAGEMENT
### ER diagram is known as Entity-Relationship diagram. It is used to analyze to structure of the Database. It shows relationships between entities and their attributes. An ER model provides a means of communication. 

ER diagram of Bank has the following description : 
 
- Bank have Customer.
- Banks are identified by a name, code, branch name.
- Customers are identified by name, cust-id,account type.
- Customer can have one or more accounts.
- Accounts are identified by account_no., account name.
- Customer can avail loans.
- Savings and current are the account types
- Debit card are identified by card no , cvv , expire date and holder name.
- Atm transaction are indetified by Transaction id,account no.
- Atm info are identified by Transaction id and bank name.

![er](https://raw.githubusercontent.com/stutimongia2024/OOPs_Training/main/Bank_Stuti.png)

### Entities and their Attributes are : 

- Bank Entity : Attributes of Bank Entity are Bank Name,IFSC Code and Branch name. 
Code is Primary Key for Bank Entity.
- Customer Entity : Attributes of Customer Entity are Customer_id, Name, account_type. 
Customer_id is Primary Key for Customer Entity.
- Account Entity : Attributes of Account Entity are account_no., account name. 
- Account_number is Primary Key for Account Entity.
- savings and current have one attribute account type.
- Debit card: Attributs of debit card are card no, cvv, exp date,holder name
- Atm transaction : Attributes of Atm transaction are Transaction id,account no.
- Atm info : Attibutes of Atm info are Transaction id and bank name
