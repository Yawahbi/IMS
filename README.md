# IMS

IMS Project is the online Platform integrated with Clover API and Wordpress WooCommerce API.

## TO-DO

- [ ] send email notifcation when stock is low
- [ ] Customize notifications based on category or item
- [ ] add open field box for notes when updating inventory items
- [ ] Create Low Inventory Reports
- [ ] Send report of all items with low inventory based on threshold

## Bugs

- [ ] INVENTORY PRICE INCORRECT decimal point is off for all pricing values
- [ Solved ] Search filter doesn't actually filter, all results return regardless of query.

## Updates

1. 31, May 2022
    - Init the Project
    - Installed Express Web Framework
    - Installed nodemon (a tool that detects any changes and starts the node server for us)
    - Added a routes dir, it contains a index file that handles the routes of the website.
    - Added the start.js to the script collection in package.json file.
    - Created Views dir, added a form.pug static template
    - install pug to integrate it with express framework
    - Added views configurations in the app.js

2. 04, June 2022
    - Installed Body parser (to parse the form data in the middleware before approaching to the handler)

3. 13, June 2022
    - Installed npm install dotenv --save
    - Installed mongoose

4. 14, June 2022
    - Added Http Security
    - Static Files reference
    - Theme Implemented and Views Folder Adjusted

5. 15, June 2022
    - Bcryptjs installed for Password encryption

6. 16, June 2022
    - Express Session installed

7. 20, June 2022
    - Installed OpenAPI SDK
    - Installed Toastify Library to show toasts.

8. 22, June 2022
    - Completed the Update CRUD

9. Local Environment Setup
    - Install the MongoDb Locally on your System.
    - In the .env file, you'll find the local connection for the DB, Session Secret Key, Clover Read, Write and Merchant Keys to be used anywhere in the Project.

10. 02, July 2022
    - Installed Kendo Grid UI for the data presentation
