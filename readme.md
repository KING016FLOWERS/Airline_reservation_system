# Airline Reservation System

## Overview

The Airline Reservation System is a web-based application designed to allow users to book, manage, and view their flight reservations. It is built using **HTML**, **CSS**, **JavaScript**, **Bootstrap** for the front-end, and **PHP** with **MySQL** for the back-end. The application is deployed on an **AWS EC2** instance, providing scalability and reliability.

## Features

- **User Registration & Authentication**: Secure user registration and login.
- **Flight Search**: Search for available flights by origin, destination, and date.
- **Flight Booking**: Book flights and choose seats.
- **Booking Management**: View and manage flight reservations.
- **Admin Panel**: Manage flight schedules and bookings.
- **Responsive Design**: Optimized for both desktop and mobile devices using Bootstrap.
- **Cloud Deployment**: Hosted on AWS EC2 for high availability.

## Technologies Used

### Front-End:
- **HTML5**: For structuring web pages.
- **CSS3**: For styling and layout.
- **JavaScript**: For dynamic interactions and validations.
- **Bootstrap**: For responsive and mobile-first design.

### Back-End:
- **PHP**: Server-side programming for handling business logic.
- **MySQL**: Database for storing flight and user data.

### Deployment:
- **AWS EC2**: Deployed on an EC2 instance with Ubuntu.

## Prerequisites

Before you begin, ensure you have the following:
- An AWS EC2 instance running Ubuntu or any preferred Linux distribution.
- Apache, PHP, and MySQL installed on the instance.
- Security group configured to allow HTTP/HTTPS traffic.

## Installation and Setup

### Step 1: Launch EC2 Instance
- Create an EC2 instance from the AWS Console.
- Ensure security groups allow inbound traffic on ports 80 (HTTP) and 443 (HTTPS).

### Step 2: Install Apache, PHP, and MySQL
Connect to your EC2 instance via SSH and run the following commands:

```bash
# Update package list
sudo apt update

# Install Apache
sudo apt install apache2

# Install PHP
sudo apt install php libapache2-mod-php php-mysql

# Install MySQL
sudo apt install mysql-server
