**Summary:**  
I set up an AWS EC2 instance with a Flask web application. The project required establishing a SQLite3 database, installing an Apache web server using `mod_wsgi`, and starting an EC2 machine with the Ubuntu Server 24.04 LTS AMI.  

The application has a user registration screen that gathers and saves personal data, such as email, first and last names, passwords, and usernames. The user is taken to a profile page with the information they have submitted after registering. In order to obtain user information using stored credentials, a login page was also put into place.  

## Key Steps:

**EC2 Instance Setup:**
- Launched a free-tier EC2 instance on AWS.
- Configured security groups to allow HTTP and SSH traffic.
- Connected to the instance using a key pair.

**Web Server Configuration:**
- Installed Apache, mod_wsgi, Python3, and Flask.
- Verified the setup by testing the Flask app deployment.

**Database Configuration:**
- Set up SQLite3 and created a users table to store registration details.

**Web Application Implementation:**
- Designed interactive HTML pages for registration and login.
- Integrated Flask routes to handle user data storage and retrieval.

**Deployment and Testing:**
- Deployed the application on the EC2 instance.
- Tested functionalities, including registration, login, and profile display.
