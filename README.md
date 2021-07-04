# ecommerceBackend

Built by Michael Rao

This is the backend of an e-commerce application that allows API calls to be made to view, add, update, and delete retail data in a SQL database. A product demonstration video can be found here:

<a href="https://drive.google.com/file/d/1XLTE-P_x4_QwD-ZsxVF1qbHvuZgi5ZKM/view?usp=sharing" target="_blank">Video Walkthrough</a>

# Technologies Used

    - node.js
    - Express.js
    - SQL
    - Postman for testing

# Description

This application allows users view and make changes to retail product data in a SQL database. Users can view, add, update, and delete information, including products, categories, and tags, from the database using API endpoints accessible via any testing tool, such as Postman or Insomnia.

# Setup/Installation Requirements

Clone this repository to VS code. Open an integrated terminal from the ecommercerbackend folder, and follow the below instructions: - open the mysql shell in the terminal and credentialize - create the schema from the mysql shell by entering "source db/schema.sql" - use the database by entering "use ecommerce_db" - quit the mysql shell - seed the database by entering "npm run seed" - start the server by entering "npm run start" - make calls to any and all endpoints using Postman or Insomnia

# Known Bugs

There are no known bugs at this time.

# License

<a href="https://choosealicense.com/licenses/mit/" target="_blank">MIT</a>

# Contact Information

Michael Rao jmichaelrao@gmail.com
