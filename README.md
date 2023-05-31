# Demo Transaction API Testing Using JMeter

## Summary
- This project basically based on the demo transaction API. Here I'm doing load testing on each request of this transaction API using JMeter software.

## Technology Used
- Apache Jmeter
- Visual Studio Code

## Server API URL: 
-  https://dmoney.roadtocareer.net/

## How to Run
1. Install & Run JMeter software
2. Download this "demo-transaction-api-jmeter.jmx" file
3. Save this .jmx file into apache "bin" folder
4. Run "ApacheJMeter.jar"
5. And finally open "demo-transaction-api-jmeter.jmx", then click on the "start" button


## This testing is based on the following sceneries

1. Admin creates an agent and a customer
2. Deposit 2000 tk to agent from system account (fromAc: SYSTEM)
3. Deposit 1000 tk to customer from agent account
4. Check balance from customer account
5. Withdraw 500 tk from customer account
6. Payment 200 tk from customer account (Merchant account: 01686606905)
7. Assert expected customer balance

## JMeter HTML Report
![jmeter html report](https://github.com/PranabPaulJoy/demo-transaction-api-jmeter/assets/127541697/d3ba13ce-d77a-41ed-b0d3-27217ab7b7c5)

## API Requests in JMeter
![image](https://github.com/PranabPaulJoy/demo-transaction-api-jmeter/assets/127541697/5bb167b5-7f4b-4017-89ce-ed11733c19f2)

## JMeter Summary Report
![image](https://github.com/PranabPaulJoy/demo-transaction-api-jmeter/assets/127541697/1943c56b-c863-4053-be05-235f99395ea0)

## JMeter Result in Table Report
![image](https://github.com/PranabPaulJoy/demo-transaction-api-jmeter/assets/127541697/32972706-0983-452b-acbf-a3f2458ef405)
