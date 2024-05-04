# Kinmat Tech Blog Admin Site Setup Guide

This guide provides step-by-step instructions on how to set up and run my blog admin site using PHP and MySQL.

## Prerequisites

Before you begin, ensure you have the following installed:

- **PHP:** Install PHP or XAMPP on your local machine. You can download it from [php.net](https://www.php.net/).
- **MySQL:** Install MySQL or use a MySQL database provided by your hosting provider.
- **Web Server:** Set up a web server like Apache or Nginx to serve PHP files.

## Setup Instructions

1. **Clone the Repository:**
   ```
   git clone https://github.com/KinmatTech/kinmatechBlog.git
   ```

2. **Navigate to the Project Directory:**
   ```
   cd blog
   ```

3. **Import the Database:**
   - Open phpMyAdmin or MySQL command line.
   - Create a new database named `kinmatblog`.
   - Import the `kinmatblog.sql` file provided in the repository to create the necessary tables.

4. **Configure Database Connection:**
   - Open `config.php` file in a text editor.
   - Update the database connection details (host, username, password) as per your MySQL configuration.

5. **Start the Web Server:**
   - Start your Apache or Nginx server.

6. **Run the Application:**
   - Open your web browser.
   - Navigate to `http://localhost/blog` (replace `localhost` with your server's hostname if needed).
   - You should see the home page of the blog admin site in localhost address.   
   
7. **Login:**
   - Use the default admin credentials (username: `admin`, password: `admin`) to log in localhost.
   
   - - Live URL: kinmatech.com.ng/blog - log in with same credentials above. 

8. **Change Default Admin Credentials:**
   - After logging in on localhost, navigate to the admin settings page.
   - Change the default admin username and password for security purposes.

## Usage

- **Dashboard:** View statistics and analytics about your blog.
- **Posts:** Create, edit, and delete blog posts.
- **Categories:** Manage post categories.
- **Comments:** View and moderate comments on your blog posts.
- **Users:** Manage user accounts and permissions. (Coming soon...) i.e. Not yet integrated.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or submit a pull request.