---
layout: post
title: "Trading Reports"
subtitle: "Track your trading and get some statistics!"
date: 2024-05-24
description: 
image: /assets/images/trade-reports/1.png
author: Mario Canalella
tags: 
  - Software
---
A simple REST service written in Go that take news every day for the next day from an API and return to Telegram.

Click [here](https://github.com/marcanalella/economic-calendar-bot) for try the demo.
- email: test@test.com
- password: test

This program, developed using Go and React, allows users to input their trade information and performs statistical analysis on the collected data. Here's a brief overview of its components and functionality:

# Backend: Go
- REST API: The backend is implemented in Go, providing a RESTful API to handle trade data. It manages CRUD operations (Create, Read, Update, Delete) for trades.
- Data Storage: It uses a database (PostgreSQL) to store trade details, such as the trade date, type (buy/sell), asset, quantity, price, and any relevant notes.
- Statistical Calculations: The Go backend performs various statistical analyses on the trades, such as total number of trades, average trade value, and total profit/loss.
- Performance Metrics: Metrics like win/loss ratio, average return per trade, and maximum drawdown.

# Frontend: React
- User Interface: The frontend is built using React, providing an intuitive and responsive UI for users to interact with the application.
- Trade Entry: Users can add new trades through a form, specifying details like asset, trade type, quantity, and price.
- Data Visualization: The application displays trade data and statistical analysis results using charts and graphs (Chart.js), making it easier to interpret the data.
- Dashboard: A dashboard offers a comprehensive view of the user's trading activity, showcasing key metrics and visualizations at a glance.

# Key Features
- User Authentication: Secure login and registration system to ensure that each user's data is private and protected.
- Responsive Design: Ensures a seamless experience across different devices, including desktops, tablets, and smartphones.
- Add Trade: A user logs in and enters a new trade via the frontend form.
- Store Trade: The trade data is sent to the Go backend via an API request and stored in the database.
- Calculate Statistics: The backend calculates updated statistics based on the new trade data.
- Update UI: The frontend retrieves the updated statistics and displays them, providing the user with immediate feedback on their trading performance.

This program combines the robustness of Go for backend processing with the flexibility and rich user experience of React, creating a powerful tool for traders to manage and analyze their trading activities.


![Placeholder1](/assets/images/trade-reports/1.png)
&nbsp;
![Placeholder2](/assets/images/trade-reports/2.png)
&nbsp;
![Placeholder3](/assets/images/trade-reports/3.png)
&nbsp;
![Placeholder4](/assets/images/trade-reports/4.png)
&nbsp;
&nbsp;
&nbsp;


> If you are interested, contact me! 😊
>