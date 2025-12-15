# README

# Rails E-commerce Application (Store)

A sample **Ruby on Rails e-commerce application** developed for academic purposes.
The project demonstrates core Rails features including authentication, product
management, image uploads, background jobs, and automated testing.

---

## Overview

The application allows authenticated users to manage products in a simple store
environment. It includes product listings with images, inventory tracking, email
notifications, and test coverage.

---

## Versions

- **Ruby:** 3.4.x
- **Rails:** 8.1.x

---

## System Dependencies

Ensure the following are installed:

- Ruby (3.4.x recommended)
- Bundler
- SQLite3
- Node.js (for asset handling)

---

## Configuration

Install Bundler (if not already installed):

```bash
gem install bundler
```

Navigate to the project directory:

```bash
cd store
```

Install dependencies:

```bash
bundle install
```

---

## Database Setup

The database configuration and migrations are already included.

If the database is not created, run:

```bash
bin/rails db:create
bin/rails db:migrate
```

If the database already exists, you can proceed directly to running the server.

---

## Running the Application

Start the Rails development server:

```bash
bin/rails server
```

If port `3000` is in use:

```bash
bin/rails server -p 3001
```

Open the application in your browser:

```
http://127.0.0.1:3000/
```

---

## Login Credentials

Use the following credentials to access authenticated features:

- **Email:** you@example.org
- **Password:** example

---

## Running the Test Suite

To run all tests:

```bash
bin/rails test
```

---

## Features

- User authentication (login / logout)
- Product CRUD operations
- Image uploads using Active Storage
- Inventory tracking
- Email notifications for back-in-stock products
- Automated test coverage

---

## Services

- **Active Storage** – Image uploads
- **Action Mailer** – Email notifications

---

## Notes

- The project was developed and tested in a **Linux environment (Ubuntu / WSL)**.
- This reflects the standard production environment for Ruby on Rails applications.
- Windows-native execution may require additional configuration.
- This project is intended for **educational purposes**.

---
