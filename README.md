SellFlair uses the API of Amazon, Shopify, and eBay to get all the data of the stores that are integrated into the platform. This is a 
dashboard-type application that will be used for different purposes such as inventory management, ordering, invoicing, product catalog, 
etc. The store owner will authenticate and authorize its different stores. After authentication, the store owner can perform several different 
operations on the stores from our centralized platform. Since, the data models of Shopify, Amazon, and eBay are different, SellFlair has to 
make sure that the data is according to the data model of each platform when the data is being passed or fetched from our platform to 
Amazon, Shopify, and eBay.
SellFlair uses Three-Tier architecture. The Presentation layer will be the frontend of the application. The business layer will be the backend 
of the application where all of the business logic will be written. The data layer is the final layer that is used to process final data requests 
and stored in the database. SellFlair uses the SPA (single page application) for its frontend and the frontend architecture will be Clean 
Architecture. The SPA will be built using ReactJS which is a modern JavaScript framework. To make the platform fast we will use Clientside rendering. The backend server will be developed using NodeJS and few third-party APIS will be used for the data analysis. 
MongoDB/MySQL/DynamoDB/PostgreSQL will be used as a database. A shared database will be used as the data management pattern. 
The application architecture will either be Monolithic or Microservices. The Representational state transfer application protocol will be used 
to communicate with the backend server and the data will be exchanged in the form of JSON. To secure the web server unique access 
tokens will be generated and the data will be validated and sanitized before entering into the database. Serverless deployment or any 
service deployment platform will be used as a deployment pattern