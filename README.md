Frontend:
Responsive web application built using React.
Dashboard to display portfolio metrics and overall value.
Form to add or edit stock details (e.g., stock name, ticker, quantity, and buy price).
Table or list view displaying current stock holdings with edit and delete options.
Real-time updates to reflect portfolio changes dynamically.
Backend:
Built using Java with Spring Boot.
Exposes RESTful APIs for:
Adding a new stock.
Updating existing stock details.
Deleting a stock.
Fetching all stocks and calculating the total portfolio value.
Proper exception handling and meaningful HTTP status codes.
JPA and Hibernate for seamless database interactions.
Database:
MySQL is used as the relational database.
Schema designed to store stock details with fields like stock name, ticker, quantity, and buy price.
Relations can be extended for future features (e.g., user management and portfolios).
Real-Time Data Integration:
Integrates with a free stock price API (e.g., Alpha Vantage, Yahoo Finance, Finnhub) to fetch live stock prices.
Dynamically calculates the total portfolio value based on fetched prices.
Technologies Used
Frontend: React, Axios, Bootstrap or Tailwind CSS.
Backend: Java, Spring Boot, JPA, Hibernate.
Database: MySQL.
APIs: Alpha Vantage or any free stock price API for real-time data.
Tools: Maven, MySQL Workbench, Visual Studio Code.
