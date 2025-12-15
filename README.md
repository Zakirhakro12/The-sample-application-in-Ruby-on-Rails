# README

HOW TO RUN THE PROJECT

1. Install Ruby if it is not already installed.

2. Install Bundler:
   gem install bundler

3. Open the terminal and navigate to the project directory:
   cd store

4. Install project dependencies:
   bundle install

5. Database setup:
   The database and migrations are already included in the project.
   If the database is already created, you can directly start the Rails
   development server.

   (Optional – only if required)
   bin/rails db:create
   bin/rails db:migrate

6. Start the Rails development server:
   bin/rails server

   Note: If port 3000 is already in use, you can specify another port:
   bin/rails server -p 3001

7. Open the application in the browser:
   http://127.0.0.1:3000/

--------------------------------------------------
LOGIN CREDENTIALS

To access authenticated features (such as creating, editing, or deleting
products), use the following credentials:

Email: you@example.org  
Password: example

--------------------------------------------------
HOW TO RUN THE TESTS

1. Make sure you are in the project directory:
   cd store

2. Run the test suite:
   bin/rails test