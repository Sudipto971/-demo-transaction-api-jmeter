# Project Title: Dmoney-API-transaction Performance-Test

## What is Performance Testing:
Performance Testing is defined as a type of software testing to ensure that software applications will perform well under their expected workload.

It focuses on certain factors of a Software Program such as:
Speed – It Checks whether the response of the application is fast.
Scalability – It determines the maximum user load.
Stability – It checks if the application is stable under varying loads.

## Technology used: 
- Apache JMeter
- Vs Code
- 
### characteristics:
- Open source application – Apache JMeter is an openly available free tool & it facilitates users or developers to use the code for other development or modification purpose.
- Platform independent – It can run on any platform & also it is capable enough to check the load & performance of any server requests.
- User friendly GUI – Its user-friendly, simple & easy to understand.
- Installation – It’s easy to install on different OS.
- Record & Run: JMeter provides the facility to record the steps by using Blaze master add-on & run with any number of threads & listeners.

## How to Run:
- Install & Run JMeter software
- Download this "demo-transaction-api-jmeter.jmx" file
- Save this .jmx file into apache "bin" folder
- Run "ApacheJMeter.jar"
- And finally open "demo-transaction-api-jmeter.jmx", then click on the "start" button

## Sceneries for this testing
- Admin creates an agent and a customer
- Deposit 2000 tk to agent from system account (fromAc: SYSTEM)
- Deposit 1000 tk to customer from agent account
- Check balance from customer account
- Withdraw 500 tk from customer account
- Payment 200 tk from customer account

## JMeter HTML Report

![Dmoney load](https://github.com/Sudipto971/-demo-transaction-api-jmeter/assets/132764259/54fc00e9-22ab-47ab-b584-cd98a860c72e)



