# Module-19-Challenge
## Description
In this assignment I will be creating an application to hire fintech professionals. I will also be able to display each individual in a drop down menu list and choose how many hours to hire them for and send and make transactions with ether. Initially I will import a ethereum transaction within the application and then sign said transaction.
## Testing Transaction
Provided below are screenshots of the application and the ganache transactions made which were verified. 
Here I hire Lane for a set number of hours, it updates the wage based on the hours I want to hire Lane for and after sending the transaction you can see the validated hash.
![app testing](https://github.com/nkp1027/Module-19-Challenge/assets/133065472/584aa395-481b-4445-8003-bb13198c567b)

This transaction can actually be viewed in Ganache, it will show the address, balance and the transaction itself. This account started with 100 ether and as shown in the screenshot above, it should take away 20 ether and have 80  ether remaining in the account. This is exactly what is shown below.
![ethbalance](https://github.com/nkp1027/Module-19-Challenge/assets/133065472/0a07739e-ce8f-4f2c-8987-fad394601699)

If you would like to see the details of the transaction you can see it below in the screenshot provided from the Ganache Transaction tab.
![ethtransaction](https://github.com/nkp1027/Module-19-Challenge/assets/133065472/73291fb8-e61f-4a65-ade7-173415372814)

## Tech Used
Streamlit, Web3.py, ethereum-tester, Ganache

## Installation
-To install streamlit you must: pip install streamlit

-To install web3 you must: pip install web3==5.17

-To install etheruem tester you must: pip install eth-tester==0.5.0b3

-To install Ganache you just go to their website and install it whether you have windows or mac
