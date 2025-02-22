## Full Stack Development I: Building Modern Web Applications

### Architecture:
In this full stack project, I utilized Express HTML, JavaScript, and a single-page application (SPA) to showcase various aspects of frontend development. The frontend was built with a combination of HTML and JavaScript. JavaScript handled website routes, controllers, and models, and the main application file exported the Express application. The SPA, which operates solely on a single page, focuses on providing admin functions for easy website maintenance and updates. The Express pages utilize Handlebars views and HTML pages. The backend employed a NoSQL MongoDB database to store information such as trip details and user login data. NoSQL does not rely on a schema, making it easier for users to store and modify data.

### Functionality:
The primary distinction between JSON and JavaScript lies in their purposes: JSON is mainly used for data storage and cannot include functions, while JavaScript objects can include functions. JavaScript objects are exclusive to JavaScript, whereas JSON can be used by various programming languages. JavaScript can convert JSON data due to their similar structure. JSON is used to transmit data from the server backend to the frontend. To improve functionality, I refactored code by moving duplicated HTML code to components that could be dynamically loaded from the database and updating pages accordingly. Handlebars partials were created for the header and footer, allowing them to be easily included in files.

### Testing:
The API endpoints in this application validate users and authorize them to modify information in the database. These endpoints work in conjunction with data-related methods such as GET, POST, PUT, and DELETE. Implementing security measures for these endpoints is crucial to prevent unauthorized users from accessing the database and its contents.

### Reflection:
This course has significantly contributed to my professional development. Balancing a part-time job with school has been challenging, but this class has deepened my understanding of frontend and backend development. It has also broadened my perspective on potential career paths as I approach graduation in two months. The most valuable skill I have gained is a comprehensive understanding of how different code components interconnect to create a finished product.
