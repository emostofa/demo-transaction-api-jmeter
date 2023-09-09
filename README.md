# demo-transaction-api-jmeter
Testing API using Jmeter

## Tools used 
- Apache JMeter

## JMX file is created from the following Scenario:- 

- Admin creates an agent and a customer
- Deposit 2000 tk to an agent from the system account (fromAc: SYSTEM)
- Deposit 1000 tk to the customer from the agent account
- Check the balance from the customer account
- Withdraw 500 tk from customer account
- Payment of 200 tk from the customer account (Merchant account: 01686606905)

## To generate a report and run the test from CLI on the CMD or PowerShell- 

Open the cmd on the bin folder of the Apache-Jmeter

Write this command- 
jmeter -o -t [JMX file name] -e -o [Reports folder name]


## Html Report Screenshot:-
![screencapture-file-C-Users-emonr-Downloads-Compressed-apache-jmeter-5-6-2-apache-jmeter-5-6-2-bin-Reports-api-index-html-2023-09-09-13_01_42](https://github.com/emostofa/demo-transaction-api-jmeter/assets/58488817/a96d2376-6834-4da6-ac3e-c1ae1ab038cb)
