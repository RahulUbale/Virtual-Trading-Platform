# Virtual-Trading-Platform
Developed a secure, microservices-based trading platform in Java 8 with Angular UI, integrating NSE and BSE APIs, Google authentication, WebSockets for market data streaming, Kafka integration, and MySQL for position data storage. Achieved high scalability, real-time trading, and efficient portfolio management.

# Introduction
Microservices based trading platform allows users to trade equities on secondary market using NSE and BSE API. The platform displays latest market data and provides a portfolio manager for end users. User Interface, developed in Angular uses Google authentication for Single Sign On and market data is streamed using websockets. UI makes secure calls to Spring Boot Rest API using Google token. In the backend, Kafka is used to integrate with market data provider and MySql database for positions.
The Virtual Trading Platform is an application that allows users to trade equities on the secondary market using NSE and BSE API. Virtual Trading Platform provides facilities for stock changes including price, volume, and displays all in the portfolio. The application displays latest market data and provides a portfolio manager for end users. VTP also allows users to buy, sell and hold the stocks and automate processing of market data. It can be used as the main component of a sophisticated trading system..
For all this a lot of API’s is used for the ease of user. API allows two applications to talk to each other and then the application interprets that data and presents the user with the information the user wanted in a readable way.
For the login of users into this trading platform we use the google authentication API, which allows users to signup with google account. This platform is based on microservices and it tends to independency of all services .This platform is rapid and frequent due to this technique .
For the User Interface, a platform developed in Angular uses google authentication for single sign on and market data is streamed using websockets. UI makes secure calls to Spring Boot Rest API using Google token. In the backend, Kafka is used to integrate with market data provider and MySql database for positions

# Purpose
We need risk-free platform where anyone can experiment new strategies without the fear of losing money which is not the case in real market. There are very few platforms which give opportunity to Real-time actual stock market data to experiment. To start in the real share market, you need to have a Demat and a Trading account. For this, you need to have a savings account, Pan Card, ID proof. And of course, you would require real money. Virtual Trading Platform which gives user chance to learn trade in the Stock Exchange in India. Your money is not at stake as virtual money is used. Users are free to take the risk; a platform which gives Real-time actual stock market data to experiment.
Also, no need to have an actual Demat and a Trading account, just an google account or sign-in is required.

# Technology Used
## BACK END
Spring Boot Hibernate.
MYSQL for storage of data.
## FRONT END
Angular
JSP
Bootstrap
Platform:
Web Development: J2EE Spring Boot, Angular, MySql, Google OAuth2
Tools/API: Kafka, Kite API, GNews API

# USE Cases
![image](https://github.com/RahulUbale/Virtual-Trading-Platform/assets/68568128/58c03590-b1b0-45db-8a2f-00072055595f)

# High Level Design
1.Microservices architecture allows developers to create separate components of an application through building an application from a combination of small services
2.Tries to focus on building single function module with well define interface and operation.

# System Diagram
![image](https://github.com/RahulUbale/Virtual-Trading-Platform/assets/68568128/9599e2c5-3966-42e4-a28d-3e08dd8ce87c)

![image](https://github.com/RahulUbale/Virtual-Trading-Platform/assets/68568128/7be9a88d-2772-4c50-9803-44191f3825b3)

# ER Diagram
![image](https://github.com/RahulUbale/Virtual-Trading-Platform/assets/68568128/e1f7c14a-4792-4484-b04c-59cfe981525f)
![image](https://github.com/RahulUbale/Virtual-Trading-Platform/assets/68568128/832625ba-34ef-4c99-877f-6bf4d36f8b5c)
![image](https://github.com/RahulUbale/Virtual-Trading-Platform/assets/68568128/57366f17-7a5f-4193-98b8-89f4f6f3e031)
![image](https://github.com/RahulUbale/Virtual-Trading-Platform/assets/68568128/5bc17242-6e00-4282-94d4-ebd47e3cacbe)

# Interfaces

## Sign in with google
![image](https://github.com/RahulUbale/Virtual-Trading-Platform/assets/68568128/5bcaed38-c41e-45e1-bfa3-5ac03e7f3729)

## Sign up 
![image](https://github.com/RahulUbale/Virtual-Trading-Platform/assets/68568128/89effb6e-73dc-4f5c-bdfe-519dfe64f138)

## User Home Page
![image](https://github.com/RahulUbale/Virtual-Trading-Platform/assets/68568128/64c9ce22-991e-4e10-b973-6112818a2a76)

## Company Search Page
![image](https://github.com/RahulUbale/Virtual-Trading-Platform/assets/68568128/16a751ae-b969-48d7-8c37-618c08f6fa18)
![image](https://github.com/RahulUbale/Virtual-Trading-Platform/assets/68568128/5d17a60f-aac6-4e31-9775-f186f2646ce4)


## Company Quote Page
![image](https://github.com/RahulUbale/Virtual-Trading-Platform/assets/68568128/ef7a85b0-1be9-4453-8fff-f3d6c313253a)

## Buy
![image](https://github.com/RahulUbale/Virtual-Trading-Platform/assets/68568128/ba6b9fed-f383-4800-b3a4-e63f2edd7ace)

## Sell
![image](https://github.com/RahulUbale/Virtual-Trading-Platform/assets/68568128/10e33f48-a408-4b48-bb52-e8528cef3aa6)

## Transactions
![image](https://github.com/RahulUbale/Virtual-Trading-Platform/assets/68568128/e78b7f15-d788-4812-bfcc-d50ab15f2444)

## Portfolio
![image](https://github.com/RahulUbale/Virtual-Trading-Platform/assets/68568128/82c0f177-21de-4970-8e4b-8c9014b31393)

# FUTURE SCOPE 
We will be providing alert wish-list to users to track stocks and get notified on WhatsApp whenever price reaches the level they wish.We will be allowing users derivatives trading.

# Code:
 ### https://github.com/RahulUbale/UserMicroservice
 ### https://github.com/RahulUbale/TradingPlatform

# Contribution 
Rahul Suresh Ubale
Sharayu Ubale
Swapnali Ubale
Shailesh Balwant Patil
Sameer Ghunakikar






















