# **Library Management System Flask**

## **About**

A Library Management Web Application built for the Flask hiring test of AereleTech.It Allows a librarian to track books and their quantity, members, and transactions.
(Built with Flask, MySQL)

# Functionality 🛠️
The application covers the following key functionalities:

# Index Page
**1.Reports**

**2,Books**

**3.Members**

**4.Transaction**

![Screenshot (907)](https://github.com/siva3010/Library-management-system-project/assets/109328049/62b1db02-3f8b-4179-8e08-fad71084a1e8)

# Database Tables 🗄️
**Report** This table stores information about various User and Book Report. Each Book is identified by a unique Book_id.

![Screenshot (908)](https://github.com/siva3010/Library-management-system-project/assets/109328049/0db03754-4ec9-47aa-baac-07f127b72f94)

# Book Views 👀
The application provides easy-to-use views for the following:

**1.Add new Books.**

**2.Edit existing Book details.**

**3.View the list Book with their respective information.**

![Screenshot (909)](https://github.com/siva3010/Library-management-system-project/assets/109328049/ed891086-4c3d-4d92-9741-a487657c8e58)

# Member page

**1.Add new Member.**

**2.Edit existing Member details.**

**3.View the list of Member with their respective information.**

![Screenshot (910)](https://github.com/siva3010/Library-management-system-project/assets/109328049/7ce7042f-b698-4465-a295-29f64c494c56)

# Transaction Page
Add new Transaction to record the transfer of Book between Users.
Edit existing movement details if necessary.
View the list of Book movements with relevant information.

![Screenshot (911)](https://github.com/siva3010/Library-management-system-project/assets/109328049/6a42d5e1-6d67-4ae2-aa9a-b589ac3eaf2c)

# Report 📊
The application generates a comprehensive report that displays the balance quantity of each Book in each Members. The report is presented in a grid view with the following columns.
**Report**Find the book details and high paying books

![Screenshot (908)](https://github.com/siva3010/Library-management-system-project/assets/109328049/0db03754-4ec9-47aa-baac-07f127b72f94)


# Search Book Page
Tha application search Books Using Book Title and Auther.

![Screenshot (912)](https://github.com/siva3010/Library-management-system-project/assets/109328049/f4537a3d-2cda-44d5-ac15-c27f5cb7449a)

## **Getting Started**

1. Install requirements
   ```sh
   pip install -r requirements.txt
   ```
2. Setup MySQL and replace host, user, password values in `setupDB.py`, `app.py` and `test.py` as required </br></br>
3. Create Database and Tables using `setupDB.py`
   ```sh
    cd utils
    python setupDB.py
    cd ..
   ```
4. Run app
   ```sh
   python app.py
   ```
**Note: Ensure you have Python and Flask installed on your system before starting the application.**

*Access the application in your web browser by visiting

# Conclusion 🎯
Congratulations! You have explored the amazing features of the **Library Management System Web Application**. 🎉  🏬🚛

With the ability to add, edit, and view book details, as well as Members, you have complete control over your Library data. 🛍️🏢🚚📝🔄

#### Happy LibMS! 🚀💼🏬📊
