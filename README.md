

# Pharmacy Management System

## Overview

The Pharmacy Management System automates daily pharmacy operations such as inventory management, sales, and billing. It improves operational efficiency, supports scalable data management, forecasts sales trends, and generates detailed reports to assist business decisions.

---

## Objectives

* Automate pharmacy workflows for enhanced efficiency.
* Manage scalable data as inventory and transactions grow.
* Analyze and forecast sales and stock trends.
* Generate comprehensive reports for management insight.

---

## Development Tools and Setup Details

### 1. Java SE Development Kit (JDK)

* Version: 11.0.2
* Provider: Oracle
* Download: [Oracle JDK 11.0.2](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html)
* **Setup:**
  Install JDK and set `JAVA_HOME` environment variable. Add `%JAVA_HOME%\bin` to system PATH.

### 2. Apache Ant (Build Tool)

* Version: 1.10.13
* Group ID: org.apache.ant
* Artifact ID: ant-core
* Download: [Apache Ant 1.10.13](https://ant.apache.org/bindownload.cgi)
* **Setup:**
  Install and add Ant’s `bin` folder to your system PATH.

### 3. Java Swing (GUI Framework)

* Included in JDK; no separate download required.

### 4. MySQL Database

* Version: 8.0.23
* Provider: Oracle
* Download: [MySQL Community Server 8.0.23](https://dev.mysql.com/downloads/mysql/8.0.html)
* **Setup:**
  Install MySQL server, create a database, and configure user credentials.

### 5. MySQL JDBC Driver (Connector/J)

* Version: 8.0.23
* Group ID: mysql
* Artifact ID: mysql-connector-java
* Download: [MySQL Connector/J 8.0.23](https://dev.mysql.com/downloads/connector/j/)
* **Setup:**
  Add `mysql-connector-java-8.0.23.jar` to your project’s classpath.

### 6. JasperReports (Reporting Library)

* Version: 6.21.3
* Group ID: net.sf.jasperreports
* Artifact ID: jasperreports
* Download: [JasperReports 6.21.3](https://sourceforge.net/projects/jasperreports/files/jasperreports/)
* **Setup:**
  Include JasperReports `.jar` files in your project libraries.

### 7. Apache NetBeans IDE

* Version: 23
* Download: [Apache NetBeans IDE 23](https://netbeans.apache.org/download/nb23/)
* **Setup:**
  Install NetBeans and import the project.

---

## Setup Instructions

1. **Install Java JDK 11.0.2**
   Download and install from Oracle. Set `JAVA_HOME` and update PATH.

2. **Install Apache Ant 1.10.13**
   Download and add to PATH.

3. **Install MySQL Server 8.0.23**
   Create a database and user with required permissions.

4. **Add MySQL Connector/J to Project**
   Download and include the JDBC driver `.jar` file.

5. **Include JasperReports Libraries**
   Download and add `.jar` files to the project.

6. **Import Project in NetBeans IDE**
   Configure libraries and build tools.

7. **Configure Database Connection in Code**
   Example JDBC URL and credentials:
   `jdbc:mysql://localhost:3306/your_database_name`
   Username: your\_db\_username
   Password: your\_db\_password

8. **Build and Run**
   Use Apache Ant or NetBeans IDE to build and launch the application.

---

## Additional Notes

* Make sure MySQL Server is running when you start the app.
* Java Swing is part of the JDK; no extra installation is needed.
* Place JasperReports templates (`.jrxml` or `.jasper`) correctly in the project.

---

## Useful Links

| Tool/Library        | Version | Download Link                                                                                                                                |
| ------------------- | ------- | -------------------------------------------------------------------------------------------------------------------------------------------- |
| Oracle JDK          | 11.0.2  | [https://www.oracle.com/java/technologies/javase-jdk11-downloads.html](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html) |
| Apache Ant          | 1.10.13 | [https://ant.apache.org/bindownload.cgi](https://ant.apache.org/bindownload.cgi)                                                             |
| MySQL Server        | 8.0.23  | [https://dev.mysql.com/downloads/mysql/8.0.html](https://dev.mysql.com/downloads/mysql/8.0.html)                                             |
| MySQL Connector/J   | 8.0.23  | [https://dev.mysql.com/downloads/connector/j/](https://dev.mysql.com/downloads/connector/j/)                                                 |
| JasperReports       | 6.21.3  | [https://sourceforge.net/projects/jasperreports/files/jasperreports/](https://sourceforge.net/projects/jasperreports/files/jasperreports/)   |
| Apache NetBeans IDE | 23      | [https://netbeans.apache.org/download/nb23/](https://netbeans.apache.org/download/nb23/)                                                     |

