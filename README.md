# Microsoft Azure Cloud Services: 

**Problem:**
The project requirement involved creating a web interface to manage user databases and blob storage containers using Microsoft Azure services. This included implementing CRUD (Create, Read, Update, Delete) operations for user management in a NoSQL database and file management in blob storage. The task also included setting up resources in the Azure portal, such as databases for user management and blob storage for file management. Additionally, Azure Functions were required to serve as HTTP trigger endpoints for handling CRUD operations.

For user management, CRUD operations included viewing user details, adding users, removing users, and updating user information. For blob storage file management, operations included viewing containers, adding containers, deleting containers, and managing files within containers (viewing, adding, deleting). Furthermore, there was a need to update a CSV file with metadata whenever files were uploaded or deleted, requiring the use of additional functions.

Subsequently, a frontend application was to be developed to provide a user interface for accessing and utilizing these functionalities. The application was expected to begin with a login page, followed by the ability for authenticated users to switch between user management and database management sections to perform their respective operations using HTTP requests and responses from the defined endpoints.

**Resolution:**
To address these requirements, the project proceeded with the following steps:
1. **Azure Resource Setup:** In the Azure portal, a resource group was created containing necessary resources such as NoSQL databases for user management and blob storage for file management.
2. **Azure Functions Development:** Azure Functions were developed to serve as HTTP trigger endpoints for handling CRUD operations for both user management and blob storage file management. These functions were designed to interact with the respective Azure services to perform the required operations.
3. **CSV File Update Function:** An additional Azure Function was created to update a CSV file with metadata whenever files were uploaded or deleted in the blob storage containers.
4. **React Frontend Implementation:** A React-based frontend application was developed to provide a user-friendly interface for accessing the CRUD functionalities. The application included a login page for authentication and separate sections for user management and database management, allowing users to perform operations through HTTP requests to the Azure Functions endpoints.

By following this approach, the project successfully met the requirements of managing user databases and blob storage containers using Microsoft Azure services. The combination of Azure Functions for backend logic and a React frontend for user interaction provided a comprehensive solution for effective database and file management through a web interface. 


(**Note:** Due to organization's confidentiality, the project code and screenshots cannot be uploaded to GitHub.)
