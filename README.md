# 📌 Customer Relationship Management System

A Java-based web application designed to manage customer information, leads, users, interactions, and business activities efficiently. The system provides centralized customer data management, user authentication, OTP verification, customer and lead management, search functionality, dashboards, database connectivity, and an organized platform for improving customer relationship management.

---

## 📌 Project Overview

The **Customer Relationship Management (CRM) System** is a Java-based web application developed to simplify and organize the process of managing customer relationships and business activities.

In traditional systems, customer information may be maintained using spreadsheets, documents, or multiple separate applications. Managing information through these methods can result in data duplication, difficulty in searching records, increased manual work, and inefficient customer management.

The proposed **CRM System** provides a centralized platform for managing customer information, leads, users, and business-related activities.

The system allows authorized users to register, log in, manage customer records, manage leads, search information, and access important CRM data through a web-based interface.

The application uses **Java Servlets, JSP, JDBC, MySQL, Maven, Apache Tomcat, HTML, CSS, JavaScript, and Bootstrap** to provide a structured and user-friendly CRM platform.

The project is designed as an academic application and can be further extended with advanced analytics, artificial intelligence, predictive lead scoring, customer recommendations, and intelligent chatbot functionality.

---

## 🎯 Project Objectives

The main objective of this project is to develop a centralized and efficient **Customer Relationship Management System**.

### Major Objectives

- Develop a centralized platform for managing customer information.
- Simplify customer data management.
- Provide efficient lead management.
- Reduce manual data management.
- Provide quick access to customer records.
- Improve organization of customer information.
- Provide secure user authentication.
- Implement OTP-based verification.
- Provide search functionality for customer information.
- Maintain customer and business data in a structured database.
- Provide a user-friendly web interface.
- Improve efficiency in managing customer relationships.
- Provide a foundation for future intelligent CRM features.

---

## 🚀 Key Features

The CRM System provides the following major features:

- 👤 **User Registration**
- 🔐 **User Login**
- 🚪 **User Logout**
- 🔑 **OTP Verification**
- 🛡️ **User Authentication**
- 🔄 **Session Management**
- 👥 **Customer Management**
- 📋 **Lead Management**
- 🔎 **Customer Search**
- 👤 **User Management**
- 📊 **Dashboard**
- 💼 **Business Activity Management**
- 🗄️ **Centralized Database Management**
- 📱 **Responsive Web Interface**
- 🔗 **MySQL Database Connectivity**

---

## 👥 User Roles

The system provides different functionalities based on the type of user.

### 👨‍💼 Admin

The **Admin** manages the overall CRM system and user-related information.

#### Admin Capabilities

- Access Admin Dashboard
- Manage users
- View registered users
- Manage customer information
- Manage leads
- View CRM information
- Monitor business activities
- Access system information
- Manage application records

---

### 👤 User

Users can access the CRM functionality provided by the system.

#### User Capabilities

- Register an account
- Login to the system
- Logout from the system
- Access dashboard
- View customer information
- Add customer information
- Update customer information
- Search customer records
- Manage leads
- View business-related information
- Access CRM features according to permissions

---

## 🔐 Authentication and Authorization

Authentication is an important part of the CRM System.

The application verifies users before allowing access to protected functionality.

### Authentication Features

- User registration
- User login
- Logout functionality
- Session management
- OTP verification
- Protected pages
- Authentication-based access
- User validation

The authentication module helps ensure that only **authorized users** can access the appropriate application features.

---

## 👥 Customer Management

The **Customer Management Module** is one of the primary components of the CRM System.

It allows users to maintain customer information in a centralized database.

### Customer Management Features

- Add customer records
- View customer information
- Update customer information
- Search customer records
- Maintain customer details
- Access customer information through the dashboard
- Store customer information in MySQL

The centralized customer database makes it easier to retrieve and manage customer information.

---

## 📋 Lead Management

The **Lead Management Module** helps users maintain information about potential customers.

A **lead** represents a potential customer or business opportunity that may be converted into an actual customer.

### Lead Management Features

- Add leads
- View lead information
- Update lead information
- Search leads
- Maintain lead records
- Track potential customers
- Organize lead information

The module helps users maintain lead-related information in an organized manner.

---

## 🔎 Customer Search

The CRM System provides search functionality to help users quickly find customer information.

Instead of manually checking multiple records, users can search for the required customer information.

### Benefits

- ⚡ Faster information retrieval
- 🔍 Reduced manual searching
- 📈 Improved accessibility
- 📁 Better organization
- ⏱️ Increased user productivity

---

## 👤 User Management

The **User Management Module** provides functionality for managing users registered within the system.

The administrator can access user-related information and manage users according to the application's requirements.

### User Management Features

- View users
- Manage user information
- Access registered user details
- Maintain user records
- Control access to CRM functionality

---

## 📊 Dashboard

The **Dashboard** acts as the central interface of the CRM System.

It provides users with quick access to major CRM modules and important information.

### Dashboard Information

The dashboard can provide access to:

- Customer information
- Lead information
- User information
- Business activities
- CRM statistics
- Application modules

The dashboard improves navigation and provides a centralized view of the CRM application.

---

## 🗄️ Database Management

The CRM System uses **MySQL** as the relational database management system.

The database is used to store and manage application information.

### Database Information

The database can contain information related to:

- Users
- Customers
- Leads
- Business activities
- Authentication
- OTP verification
- Other CRM-related information

**JDBC** is used to establish communication between the Java application and the MySQL database.

---

## ⚙️ Technology Stack

| Technology | Purpose |
|---|---|
| **Java** | Backend application development |
| **Java Servlets** | Request processing and server-side logic |
| **JSP** | Dynamic web page development |
| **JDBC** | Database connectivity |
| **MySQL** | Database management |
| **Maven** | Build and dependency management |
| **Apache Tomcat** | Web application server |
| **HTML** | Web page structure |
| **CSS** | User interface styling |
| **JavaScript** | Client-side functionality |
| **Bootstrap** | Responsive user interface |

---

## 🏗️ System Architecture

The CRM System follows a Java web application architecture.

```text
                    User
                      │
                      ▼
                Web Browser
                      │
                      ▼
                JSP / HTML / CSS
                      │
                      ▼
                Java Servlets
                      │
                      ▼
                    JDBC
                      │
                      ▼
                   MySQL
                      │
                      ▼
               Database Records
````

### Working Process

1. The user interacts with the web application.
2. JSP pages provide the user interface.
3. User requests are sent to Java Servlets.
4. Servlets process the requested operation.
5. JDBC establishes communication with MySQL.
6. Required information is retrieved or stored.
7. The response is returned to the web interface.
8. The user can view the requested information.

---

## 📂 Project Structure

```text
CRMSystem/
│
├── src/
│   └── main/
│       ├── java/
│       │   └── ...
│       │
│       └── webapp/
│           ├── WEB-INF/
│           ├── css/
│           ├── js/
│           ├── signup.jsp
│           ├── success.jsp
│           ├── users.jsp
│           ├── verifyOTP.jsp
│           └── other JSP files
│
├── pom.xml
├── .gitignore
└── README.md
```

---

## 🔄 System Workflow

```text
                         User
                           │
                           ▼
                  Registration / Login
                           │
                           ▼
                    Authentication
                           │
                           ▼
                       Dashboard
                           │
          ┌────────────────┼────────────────┐
          │                │                │
          ▼                ▼                ▼
      Customers          Leads           Users
          │                │                │
          ▼                ▼                ▼
   Add / View /      Add / View /      View / Manage
     Update /          Update /
      Search            Search
          │                │                │
          └────────────────┼────────────────┘
                           │
                           ▼
                  Business Activities
                           │
                           ▼
                   Centralized Data
                           │
                           ▼
                         MySQL
```

---

## 🔁 Customer Management Workflow

```text
User
 │
 ▼
Login
 │
 ▼
Dashboard
 │
 ▼
Customer Management
 │
 ├── Add Customer
 ├── View Customer
 ├── Update Customer
 └── Search Customer
 │
 ▼
MySQL Database
```

---

## 🔁 Lead Management Workflow

```text
User
 │
 ▼
Dashboard
 │
 ▼
Lead Management
 │
 ├── Add Lead
 ├── View Lead
 ├── Update Lead
 └── Search Lead
 │
 ▼
MySQL Database
```

---

## 🔁 Authentication Workflow

```text
User
 │
 ▼
Registration
 │
 ▼
Enter User Information
 │
 ▼
OTP Verification
 │
 ▼
Account Verification
 │
 ▼
Login
 │
 ▼
Authentication
 │
 ▼
Dashboard
```

---

## 🛠️ Requirements

The following software is required to run the project:

* **JDK 17 or above**
* **IntelliJ IDEA**
* **Apache Tomcat**
* **MySQL**
* **Maven**
* **Web Browser**

---

## 🔮 Future Enhancements

### 🤖 AI-Powered Customer Recommendations

Machine learning can be integrated to analyze customer information and provide personalized recommendations.

Possible applications include:

* Customer segmentation
* Customer behavior analysis
* Product recommendations
* Customer retention prediction
* Personalized customer suggestions

### 🎯 Predictive Lead Scoring

Machine learning can be used to predict the likelihood of a lead becoming a customer.

The system could analyze:

* Lead information
* Customer history
* Previous interactions
* Engagement
* Business activities

and assign a probability score to each lead.

### 📊 Advanced Analytics

Future versions can include advanced dashboards for analyzing:

* Customer growth
* Lead conversion rates
* Customer activity
* Lead performance
* Business trends
* Monthly and yearly statistics

### 💬 AI Chatbot

An AI-powered chatbot can be integrated into the CRM system.

The chatbot could help users:

* Search customer information
* Answer CRM-related questions
* Navigate the system
* Retrieve business information
* Provide application assistance

### 📧 Notification System

Future versions can support:

* Email notifications
* SMS notifications
* Customer reminders
* Lead follow-up reminders
* Business activity notifications
* System alerts

---

## 📌 Project Status

| Feature                         | Status                |
| ------------------------------- | --------------------- |
| **Project Setup**               | ✅ Implemented         |
| **Maven Configuration**         | ✅ Implemented         |
| **Database Connectivity**       | ✅ Implemented         |
| **User Registration**           | ✅ Implemented         |
| **Login System**                | ✅ Implemented         |
| **Logout**                      | ✅ Implemented         |
| **Authentication**              | ✅ Implemented         |
| **OTP Verification**            | ✅ Implemented         |
| **User Management**             | ✅ Implemented         |
| **Customer Management**         | ✅ Implemented         |
| **Customer Search**             | ✅ Implemented         |
| **Lead Management**             | ✅ Implemented         |
| **Dashboard**                   | ✅ Implemented         |
| **JSP Interface**               | ✅ Implemented         |
| **Servlet Backend**             | ✅ Implemented         |
| **JDBC Connectivity**           | ✅ Implemented         |
| **MySQL Database**              | ✅ Implemented         |
| **AI Customer Recommendations** | 🔄 Future Enhancement |
| **Predictive Lead Scoring**     | 🔄 Future Enhancement |
| **Advanced Analytics**          | 🔄 Future Enhancement |
| **AI Chatbot**                  | 🔄 Future Enhancement |
| **Cloud Deployment**            | 🔄 Future Enhancement |

---

### Recommended Screenshots

* Login Page
* Registration Page
* OTP Verification Page
* Success Page
* Admin Dashboard
* User Dashboard
* Customer Management Page
* Customer Details Page
* Customer Search Page
* Lead Management Page
* User Management Page
---

## 📚 Learning Outcomes

This project provides practical experience in:

* **Java Programming**
* **Object-Oriented Programming**
* **Java Servlets**
* **JSP**
* **JDBC**
* **MySQL**
* **Maven**
* **Apache Tomcat**
* **Web Application Development**
* **Database Management**
* **CRUD Operations**
* **Authentication**
* **Session Management**
* **OTP Verification**
* **Git and GitHub**
* **Client-Server Architecture**

---

## 👩‍💻 Author

### Nandhana Biju

**MCA Student**

**Skills:**
Java | JSP | Servlets | JDBC | MySQL | Maven | HTML | CSS | JavaScript | Bootstrap | Git & GitHub

---

## 📚 Project Type

**Academic Project**

The **Customer Relationship Management System** is developed as an academic project to demonstrate the practical implementation of Java web development, database management, authentication, customer management, lead management, and business process automation.

The project provides a foundation for future integration of **artificial intelligence, predictive analytics, intelligent recommendations, chatbot functionality, and advanced customer relationship management features.**

---

