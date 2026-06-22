ADMIN TEST (Angular)
Name: admin
Email: admin@travlr.com
Password: admin123

ADMIN TEST (Express)
Name: admin
Email: admin@gmail.com
Password: admin

CUSTOMER TEST(Express)
Email: test3@gmail.com
Password:test3

Admin access is controlled through the user role field in MongoDB.

Users can be granted admin privileges by updating the user document:

role: "admin"

Standard users use:
role: "customer"

--------------------------------------------------------
## Project Structure

/travlr        -> Express customer-facing application + API  
/travlr/app_admin  -> Angular administrator SPA


## Running the Customer-Facing Express Application

From the project root:

cd travlr
npm install
npm start

Runs on:
http://localhost:3000


## Running the Angular Admin SPA

Open a second terminal:

cd travlr/app_admin
npm install
ng serve

Runs on:
http://localhost:4200
