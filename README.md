**Frontend:**
Responsive web application built using React.
Dashboard to display portfolio metrics and overall value.
Form to add or edit stock details (e.g., stock name, ticker, quantity, and buy price).
Table or list view displaying current stock holdings with edit and delete options.
Real-time updates to reflect portfolio changes dynamically.

**Backend:**
Built using Java with Spring Boot.
Exposes RESTful APIs for:
Adding a new stock.
Updating existing stock details.
Deleting a stock.
Fetching all stocks and calculating the total portfolio value.
Proper exception handling and meaningful HTTP status codes.
JPA and Hibernate for seamless database interactions.

**Database:**
MySQL is used as the relational database.
Schema designed to store stock details with fields like stock name, ticker, quantity, and buy price.
Relations can be extended for future features (e.g., user management and portfolios).


**Setup and Installation Guide**
Backend Setup:
Prerequisites:
Install Java 8 or later.
Install Maven.
Ensure MySQL is installed and running.
Steps:
Clone the backend repository:

git clone <backend-repo-url>

Navigate to the backend folder:

cd backend

**Configure MySQL connection in application.properties:**

spring.datasource.url=jdbc:mysql://localhost:3306/portfolio_db
spring.datasource.username=<your-username>
spring.datasource.password=<your-password>
spring.jpa.hibernate.ddl-auto=update

Start the backend server:

mvn spring-boot:run
APIs will be available at http://localhost:8080.

**Frontend Setup:**
Prerequisites:
Install Node.js and npm.

Steps:
Clone the frontend repository:

git clone <frontend-repo-url>

Navigate to the frontend folder:

cd frontend

Install dependencies:

npm install

Start the development server:

npm start

The frontend will be available at http://localhost:3000.

**Database Setup:**
Steps:
Open MySQL Workbench.
Create a database:

CREATE DATABASE portfolio_db;

The application will automatically create the required tables when it starts.

**How to Use**
1 Start the backend server (mvn spring-boot:run).
2 Start the frontend application (npm start).
3 Access the web app at http://localhost:3000.
4 Use the form to add stock details (stock name, ticker, quantity, and buy price).
5 View, edit, or delete stocks from the portfolio table.
6 The dashboard will display real-time metrics, including total portfolio value.
