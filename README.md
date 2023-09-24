# LibraHub 📚
LibraHub is a comprehensive library management system designed to automate library operations and enhance efficiency. This web-based system can be accessed from anywhere with an internet connection.

## Features

- 📝 Add and manage students and books
- 📚 Check out and return books
- ⏰ Track overdue books and fines
- 📊 Generate reports
- 🔒 Manage security features such as CAPTCHA verification and password encryption

 


## New Features

This extended version of LibraHub introduces an exciting feature for report generation. Librarians can now generate reports on various aspects of the library, including the most popular books, the most active students, and overdue books.

## Installation 💻

To install LibraHub, you'll need:

- 🌐 A web server with PHP and MySQL installed (Preferred XAMP)
- 💼 Basic Knowledge of PHP and Sql.

After setting up the necessary software, download the LibraHub code from [GitHub](https://github.com/ravithemore/LibraHub). Extract the code to a directory on your Local Machine. 
### Step 1: Place Files
1. Copy the LibraHub source code to your computer's web server folder (usually located at `C:\xampp\htdocs`).

### Step 2: Start XAMPP
2. Open the XAMPP Control Panel and start both the Apache and MySQL services.

### Step 3: Access Database Server
3. In your web browser, enter this link: [http://localhost/phpmyadmin/]. This will open the database server page.

### Step 4: Create Database
4. Create a new, empty database named "library." Select the "library" database and import the SQL file provided with the source code.

### Step 5: Configure Settings
5. Review the configuration files in the "includes" folders. Make sure to update the username and password according to your database settings.

### Step 6: Access LibraHub
6. In your web browser, go to [http://localhost/foldername-in-htdocs-directory/]. You should see the login page.

### Step 7: Log In
7. Use any credentials from the database to log in. The password for all accounts is set to "Test@123."

That's it! You're ready to start using LibraHub to manage your library efficiently. Enjoy! 🚀


Configure LibraHub by opening the `config/database.php` file and entering your database connection information. Then, open the `config/app.php` file and enter the URL of your LibraHub installation.

To create an administrator account, visit `/admin/setup` in your web browser.

## Usage 🪴

Once you have created an administrator account, start using LibraHub to manage your library:

- To add a new student or book, go to the Students or Books page and click the "Add New" button.
- For checking out or returning a book, visit the Circulation page and select the student and book.
- To track overdue books and fines, navigate to the Overdue Books page.
- To generate a report, access the Reports page and select the report you need.

## Security Features 🔐

LibraHub prioritizes your data's security with:

- 🔐 CAPTCHA verification to prevent spam bots
- 🔑 Password encryption to protect user passwords
- 🚪 Session management to prevent unauthorized access

### Support 💌

If you need assistance with LibraHub, please visit the [LibraHub GitHub repository](https://github.com/ravithemore/LibraHub).

### License 🪪

LibraHub is licensed under the MIT License.

### Contributing 💁‍♂️

If you'd like to contribute to LibraHub, fork the GitHub repository and create a pull request.

### Conclusion 👍

LibraHub is a complete library management system that empowers libraries to automate operations and boost efficiency. It's easy to install, user-friendly, and packed with security features to safeguard your data.
