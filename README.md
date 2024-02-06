Use Node 16+ for both FE and BE, Use Same RDS.

General Steps:

1. Database: Import the sql file provided in backend code into the database.

2: Backend:
    a. Add "DB_CONNECTION_STRING" environment variable with the mysql connection string as value
    b. Install node dependencies
    c. Execute node src/index.js
    d. Check on port 3000

3. Frontend:
    a. Edit both files in "src/environments/" add the backend URL in those files.
    b. Install node dependencies
    c. Build Frontend Code
    d. Deploy code using webserver.
