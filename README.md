# Lunchly Reservation Lookup System

Lunchly is a mock customer reservation lookup system for a restaurant. It allows users to manage customer information, view customer details, add new customers, search for customers, and make reservations.

## Installation and Setup

1. Clone the project repository and navigate to the project folder.
2. Install the required dependencies by running the command: 
   ```
   npm install
   ```
3. Create a PostgreSQL database named "lunchly".
4. Import the sample data from the `data.sql` file provided in the project directory into the "lunchly" database.
5. Start the server using nodemon by running the command:
   ```
   nodemon -e js,html,css
   ```

## Usage

- Access the Lunchly application at `http://localhost:3001` in your web browser.
- The homepage displays a list of customers. Clicking on a customer's name will take you to their detail page.
- On the customer detail page, you can view the customer's reservations.
- To add a new customer, click on the "Add Customer" link and fill in the required information in the provided form.
- To search for a customer, click on the "Search" link and enter the customer's first name in the search form.
- Editing customer information can be done by clicking the "Edit" link on the customer detail page.
- Reservations can be made by clicking the "Add Reservation" button on the customer detail page and providing the required details.

## Project Structure

The Lunchly project has the following main components:

- `app.js`: The application object that can be imported from other files/tests.
- `routes.js`: Defines the routes for the web interface, including handling customer-related actions and reservations.
- `server.js`: Contains the functionality to start the server and is the file that is run to start the application.
- `templates/`: Contains templates rendered with the Nunjucks library, used for rendering HTML pages.

## Technologies Used

- Express.js
- Nunjucks
- PostgreSQL
