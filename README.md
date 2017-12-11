# CryptoBot

## Members:
- Abdul Elderrat-Front End, Axosoft
- Braden Rucinski- Back End, Python Scrape + MongoDB 
- Mason Flint- Web Service
- Sonu Chavakula- Front End
- Taylor McNeal- Python Google Trends

## What is CryptoBot?
CryptoBot is the name of an initiative to provide a user-friendly and secure interface for users to utilize automated trading algorithms for various cryptocurrencies.  Our current data-flow utilizes several python programs to populate databases with trading information.  The DataRelayService is a layer of abstraction between our user-interfaces and our databases.  Its purpose is to simplify transfer of data between multiple user-interfaces by keeping our queries in one location.  This allows us to only make changes to the DataRelayService should our underlying database architecture change at any point instead of modifying each individual user-interface.  Our DataRelayService then provides information to our user-interfaces, so that our users can see pertinent information for our trading algorithms.

## How did we use Agile?
Our team used Scrum, through Axosoft, and after nearly every class, to do our "daily" Scrum standup. You can see our Axosoft for more information on how we handled tasking.

## ScrapeyServer: 
- ec2-54-82-229-89.compute-1.amazonaws.com
## FrontEndService: 
- Public address: http://ec2-54-164-254-145.compute-1.amazonaws.com
- Repo: https://github.com/AbdulEldarrat/Front-End-CryptoCurrency-Bot-12-5-17-
## DataRelayService: 
- Public address: http://ec2-54-164-254-145.compute-1.amazonaws.com/DataRelayService/
- Repo: https://github.com/hackerbuddy/CryptoBot/tree/DataRelayService
## MySql Server: 
- cryptodb.czf1h9vdv76q.us-east-1.rds.amazonaws.com 
