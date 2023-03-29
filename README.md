# Movie REST API

This is a simple RESTful API built only using Node.js that allows users to retrieve, create, update, and delete movie records. The API uses the following HTTP methods to perform these operations:

- GET: retrieve movie records
- POST: create a new movie record
- PUT: update an existing movie record
- DELETE: delete an existing movie record

## Installation

To get started with the API, first clone the repository and install the dependencies:

git clone https://github.com/azaryan01/movie-api.git
cd movie-api
npm install

To start the API server, run the following command:
npm start


| **Endpoint** | **HTTP Method** | **Description**                           |
|--------------|-----------------|-------------------------------------------|
| /movies      | GET             | Retrieve a list of all movies in database |
| /movies/:id  | GET             | Retrieve a movie by ID                    |
| /movies      | POST            | Create a new movie record                 |
| /movies/:id  | PUT             | Update an existing movie record by ID     |
| /movies/:id  | DELETE          | Delete a movie record by ID               |


By default, the API will run on port 3000. You can change the port by setting the `PORT` environment variable.

Once the server is running, you can use the Thunder VS Code extension to test the API. The extension provides a user-friendly interface for sending HTTP requests to the API and viewing the responses.

To use the Thunder extension, open the `Thunder` tab in VS Code, and click the `+ New Request` button. This will open a new tab where you can enter the details of your request, such as the HTTP method, URL, headers, and body. Once you've entered the details, click the `Send Request` button to send the request to the API.

The Thunder extension will display the response from the API, including the HTTP status code, headers, and body. You can use this information to verify that the API is working as expected.