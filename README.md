# C# CRUD Application with SQL Server

This is a simple **C# CRUD (Create, Read, Update, Delete) Application** that connects to a **SQL Server** database. The project allows users to perform CRUD operations and search records, providing an easy-to-use interface built with **Windows Forms**.

---

## 🔧 Features

- **Create**: Add new records to the database.
- **Read**: Display and view records from the database.
- **Update**: Modify existing records.
- **Delete**: Remove records from the database.
- **Search**: Search for records based on user input.

---

## 🛠️ Technologies Used

- **C#** for backend logic and Windows Forms UI
- **SQL Server** as the database management system
- **Visual Studio** for project development


---

## 💻 Installation

### Prerequisites

- **SQL Server** installed on your local machine or remote server. (SQL Server instance: `DESKTOP-HJO135F\SQLEXPRESS`)
- **Visual Studio** or any C# IDE that supports Windows Forms applications.

### Steps to Run the Project

1. Clone this repository to your local machine:
    ```bash
    git clone https://github.com/bhipendar14/C-
    ```

2. Open the solution file `CRUDApp.sln` in **Visual Studio**.

3. Update the **connection string** in the `App.config` file with your SQL Server database credentials:
    ```xml
    <connectionStrings>
        <add name="SQLServerConnection" 
             connectionString="Server=DESKTOP-HJO135F\SQLEXPRESS;Database=YourDatabaseName;Integrated Security=True;" 
             providerName="System.Data.SqlClient" />
    </connectionStrings>
    ```

4. Build and run the project.

5. You should be able to see the application window where you can add, view, update, and delete records.

---

## 📂 File Structure

- `CRUDApp.sln`: Solution file for the project.
- `App.config`: Configuration file to set database connection string.
- `MainForm.cs`: Main user interface and logic for CRUD operations.
- `Database.sql`: SQL script to set up the SQL Server database and tables.

---

## ⚙️ How to Use

1. **Create Records**: Enter data into the form and click the "Add" button to insert records into the SQL Server database.
2. **Read Records**: View existing records from the database displayed in a table format.
3. **Update Records**: Select a record, modify its fields, and click the "Update" button to save changes.
4. **Delete Records**: Select a record and click the "Delete" button to remove it from the database.
5. **Search Records**: Enter a search term in the search box to find specific records.

---
**Repository**: [GitHub Link](https://github.com/bhipendar14/C-)

## 💬 Contributing

Feel free to fork this project, make improvements, and submit pull requests. Contributions are always welcome!



