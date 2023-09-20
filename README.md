# Retail-Transactions-Project


Requirement: 

For a Retail Store the Reward points need to be calculated based on the following criteria: 
If Transaction Amount is 0-50: No reward points 
If Transaction Amount is 51-100: 1 reward point per rupee 
If the Transaction Amount is above 100: 2 reward points to be added per rupee 
Perform create, delete, update and read operations for the the users and transactions. 
We should be able to fetch the data based on UserID, Mobile Number, Email on to the postman 
Monthly Report must be generated for the User with the Total Transactions, Total Amount and Total Reward Points 

Implementation: 

As per the requirement provided, I am able to create the users and also generate the transactions through postman 

I am able the fetch the Transaction Amount from the generated transactions and calculate the Reward Points as per the given criteria in the requirement and display it on the console. 

I have implemented the Read, Update and Delete operations for the transactions by following the REST API Guidelines. 

I have generated Open API(Swagger) for the developed Spring Boot Application. 

I have returned only the required fields in the response body of postman in the JSON format. 

I have calculated the sum of reward points of all the Transactions for a given particular User by using the userID and display the Total Number of Reward Points along with the User Details in the Response Body of postman. 

I have calculated the sum of reward points of all the Transactions for a given particular User by using the Mobile Number and also Email Address and display the Total Number of Reward Points along with the User Details on the response body of postman. 

I have calculated the total reward points of a customer on monthly basis and display monthly report as the response body of postman 

Card Making has been implemented by using regular expression. 

Added total transaction amount also when trying to fetch data with ID, Mobile Number, Email. 

Added the total transaction amount and total number of transactions in the response body of postman for the Monthly Report of a customer. 
