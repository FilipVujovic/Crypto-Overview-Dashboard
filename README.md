# Crypto-Overview-Dashboard
This is a Spring API developed as an internship project in Levi9.

The API serves as a overview dashboard for different cryptocurrencies. 
The data source for the API is the Coin Cap API (https://docs.coincap.io).

I worked on the security service which was implemented using Spring Security & JWT authentication. 
Implemented in the application are 2 roles : Admin & User. 

The admin can adjust the threshold of certain cryptocurrencies which should trigger a notification to the user
if the price of that currency exceeds that threshold. 

The user can simply view currencies and manipulate the data with the help of implemented filters. 

The data service which is responsible for all handling of the data was developed by @Naffets (https://github.com/Naffets) & @jasna11 (https://github.com/jasna11). 

