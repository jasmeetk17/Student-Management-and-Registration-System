Student Management and Registration System
This project is a Student Management and Registration System developed in Python. It provides functionalities for managing student information, registration, login authentication, and administrative tasks. Below are the details of the libraries used and the functions available in the system.

Libraries Used
tkinter: Used for creating the graphical user interface (GUI) components.
PIL: Provides functionalities for image processing and manipulation.
sqlite3: Utilized for managing the lightweight database.
os: Offers portable ways of handling operating system functionalities.
smtplib: Enables connection to an SMTP server for sending email messages.
email.mime: Provides classes to create multipart email messages.
threading: Facilitates multi-threading capabilities.
Functions
Database Management
init_database: Initializes the SQLite database.
check_id_already_exists: Checks if a given student ID already exists in the database.
check_valid_password: Validates the provided password for a given student ID.
add_data: Adds new student data to the database.
fetch_student_data: Retrieves student data based on a given query.
User Interface
confirmation_box: Displays a confirmation message box.
message_box: Displays a general message box.
draw_student_card: Generates a student card with provided data and image.
student_card_page: Displays the student card page.
welcome_page: Displays the welcome page with options to navigate to different sections.
Email Communication
sendemail_to_student: Sends an email to a student with the provided message and subject.
User Authentication
forget_password_page: Displays the password recovery page.
student_login_page: Handles student login functionalities.
admin_login_page: Handles admin login functionalities.
Dashboard Functionalities
student_dashboard: Displays the student dashboard with options to manage data, view student card, etc.
admin_dashboard: Displays the admin dashboard with options to manage students, send announcements, etc.
Additional Pages and Utilities
security_page: Displays the security page for password change.
edit_data_page: Displays the page for editing student data.
delete_account_page: Displays the page for deleting a student account.
find_student_page: Displays the page for finding a student's data.
announcement_page: Displays the page for sending announcements to students.
add_account_page: Displays the page for adding a new student account.
How to Use
Clone the repository from the provided link.
Ensure all necessary libraries are installed.
Run the main Python file to start the application.
Navigate through different pages for registration, login, dashboard, etc.
Follow the on-screen instructions for each functionality.
Contribution
Contributions to the project are welcome. Feel free to fork the repository, make improvements, and submit pull requests.

License
This project is licensed under the MIT License.

Acknowledgments
Special thanks to the @tkinterhub(https://www.facebook.com/profile.php?id=100082985064588&_rdc=2&_rdr) for creating and helping to making this project.
