### Objective

Your assignment is to implement an Employee synchronization REST API using C# and .Net.

### Brief

The parent company Planet Mini Golf LLC has 10 different courses across the country. The IT dev team has a requirement to create a web and mobile application where all the employees within the organization can assign different roles for individual mini golf courses. Each course has its own Employee database and is updated by the HR application periodically, for the web application to consume/update the data it has to be in a single database which will be synchronized daily by the REST API developed. 

### Tasks

-   Implement assignment using:
    -   Language: **C#**
    -   Framework: **.Net**
-   Implement a REST API which would sync the employees and return the modified employees as JSON or XML based on the `Content-Type` header
-   Implement a custom user model which would have the "UniqueID" field from the master databases. 
-   Implement a contact model. Each contact should have an Alias , email address, UniqueID (your custom user model), phone number and status
    -   Choose the data type for each field that makes the most sense
-   Allow the endpoint to be authenticated with the API using username, password and can be used to manually triggered. 
-   Implement REST endpoints for the /contacts resource
    -   No authentication required
    -   Allows only GET operations
    -   Make the Contacts resource searchable with query parameters
    -   Implement the typical CRUD operations for this resource    
    -   Implement API tests for all endpoints

### Evaluation Criteria

-   **C#** best practices
-   If you are using a framework make sure best practices are followed for models, configuration and tests
-   Write API tests for all implemented endpoints
-   The API should be efficient to sync a large dataset of > 50,000 each time invoked. 

Please organize, design, test and document your code as if it were
going into production - then create a new branch with syntax "yourName-release" and push your changes to the same branch. After you have pushed your code, you may submit the assignment on the assignment page.

All the best and happy coding,

The Troon Golf Team
