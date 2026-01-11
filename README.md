# Java MVC Contact Management System

A desktop-based CRUD application built with Java Swing, implementing the Model-View-Controller (MVC) design pattern for clean, scalable code architecture. This project serves as a demonstration of decoupled UI and business logic in a Java environment.

## Engineering Highlights

* **MVC Architecture:** Strict separation of concerns between data logic (models), UI (views), and business logic (controllers) to facilitate easier maintenance and testing.
* **Security & Validation:** Implemented advanced Regex-based email validation and mandatory field checks to ensure high data integrity.
* **DAO Design Pattern:** Utilizes the Data Access Object (DAO) pattern to abstract and encapsulate all access to the data source.
* **Session Management:** Includes a secure Login/Registration system with session-handling to protect user-specific contact data.
* **CSV Integration:** Built a custom CSVExporter utility for data portability, allowing users to export contact lists for external use.

## Tech Stack

* **Language:** Java 8+
* **UI Framework:** Java Swing / AWT
* **Design Patterns:** Model-View-Controller (MVC), Data Access Object (DAO)
* **Utility:** CSV Export, Regular Expressions (Regex)



---

## Installation and Usage

1. Clone the Repository:
   ```bash
   git clone [https://github.com/greglinv/Java-MVC-Contact-Manager.git](https://github.com/greglinv/Java-MVC-Contact-Manager.git)
2. Compile the Project: From the root directory, compile the Java files:
   ```bash
   javac main/Main.java
3. Run the Application:
   ```bash
   java main/Main
4. Getting Started: Launch the app, register a new user account, and begin managing your secure contact list.   
