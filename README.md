# Knowlegde Plus

This project is a PHP-based Learning Management System (LMS) designed to facilitate online learning by providing a platform where teachers can create and manage video course playlists, students can access, like, and comment on courses, and the platform is overseen by a master admin. Guests can also explore available courses.

## Table of Contents
- [Features](#features)
- [Technology Stack](#technology-stack)
- [Database Structure](#database-structure)
- [Installation](#installation)
- [Usage](#usage)

## Features

- **Master Admin Role**: Manages the entire platform, including overseeing teacher and student activities.
- **Teacher Role**: Create and manage course playlists, including uploading videos and course descriptions.
- **Student Role**: Access courses, like content, and leave comments on course materials.
- **Guest Role**: Explore available courses without needing to sign up.
- **User Management**: Secure user authentication and management.

## Technology Stack

- **Backend**: PHP
- **Frontend**: HTML, CSS, JavaScript
- **Database**: MySQL

## Database Structure

The LMS uses the following database tables:

- **users**: Stores user information, including roles (master admin, teacher, student).
- **tutors**: Stores information related to teachers.
- **playlist**: Stores details of course playlists.
- **content**: Stores course content, including video links and descriptions.
- **comments**: Stores user comments on course content.
- **likes**: Stores likes on course content.
- **bookmark**: Stores bookmarks by users on playlists.
- **contact**: Stores contact messages from users.

### Installation
**Clone the repository:**
git clone https://github.com/your-username/lms.git
cd lms

**Set up the database:**
    1. Create a MySQL database named course_db.
    2. Import the provided SQL dump into your MySQL database using phpMyAdmin or the MySQL command line.

**Configure the environment:**
Update the database connection settings in the config.php file.


**Run the application:**
Host the application on a local or remote server supporting PHP.

### Usage
Admin: Log in using the master admin credentials and manage the platform.
Teacher: Log in using teacher credentials to create and manage course content.
Student: Log in to access and interact with course content.
Guest: Browse available courses without logging in.


### SQL Dump

```sql
-- SQL Dump created with phpMyAdmin version 5.2.0
-- Database: `course_db`
-- Tables: `users`, `tutors`, `playlist`, `content`, `comments`, `likes`, `bookmark`, `contact`

-- See the provided SQL dump in the project repository for the full structure.





