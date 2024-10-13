# Website Project

## Overview
This project is a dynamic website developed using **PHP** and **SQL** databases, including **MySQL**, **MariaDB**, and **SQL Server**. The site is built with relational tables to efficiently manage user data and posts, providing a seamless user interaction through PHP scripts.

## Database Structure
The project uses a database named `website` that contains the following tables:

- **users**: Stores user information with the following columns:
  - `id`: Unique user identifier (Primary Key)
  - `email`: User's email address
  - `login`: Username for logging in
  - `password`: Hashed password for authentication

- **posts**: Stores posts with the following columns:
  - `title`: Post title
  - `main_text`: Main content of the post

## Features
- User authentication and management through the `users` table.
- Post management using the `posts` table.
- The website dynamically interacts with the SQL databases via PHP, ensuring smooth content and data handling.

## Requirements
- **PHP** 7.4 or higher
- **MySQL**, **MariaDB**, or **SQL Server**
- Web server (e.g., **Apache**, **Nginx**) with PHP support

## Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/z4ng1ew/SQL_PHP_proj
