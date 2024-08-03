# Postman API Tests

![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![Swagger](https://img.shields.io/badge/-Swagger-%23Clojure?style=for-the-badge&logo=swagger&logoColor=white)
![Trello](https://img.shields.io/badge/Trello-%23026AA7.svg?style=for-the-badge&logo=Trello&logoColor=white)
[![Newman](https://img.shields.io/badge/tested%20with-Newman-FF6C37.svg)](https://github.com/postmanlabs/newman)

### This is a test project for **Back-End Test Automation** March 2024 Course @ SoftUni

---

## Overview

This repository contains Postman collections and reports generated by Newman for the Postman collections. These reports provide detailed information about the test runs and can be useful for debugging and analysis.

## Prerequisites

- [Postman](https://www.postman.com/downloads/)
- [Newman](https://learning.postman.com/docs/collections/using-newman-cli/installing-running-newman/)
- [Trello](https://api.trello.com)

## Installation and Usage

### Postman

**Postman** is a popular tool used to test APIs by making HTTP requests to various endpoints. To use Postman:

1. Download and install Postman from the [official website](https://www.postman.com/downloads/).
2. Open Postman and create a new request by selecting the HTTP method and entering the endpoint URL.
3. Add necessary headers, parameters, and body data.
4. Click on the "Send" button to make the request and view the response.

### Automation Scripts
To further enhance the API testing process, I write automation scripts that can be executed within Postman. These scripts help in setting up pre-conditions, validating responses, and managing dynamic data. To use automation scripts:

1. Open Postman and navigate to the collection or request where you want to add the script.
2. Go to the Pre-request Script or Tests tab.
3. Write or paste the automation script.
4. Save and run the collection or request to see the script in action.

### Newman

**Newman** is a command-line collection runner for Postman. It allows you to run and test Postman collections directly from the command line. To install and use Newman:

1. Install Node.js from the [official website](https://nodejs.org/).
2. Install Newman using npm:

   ```sh
   npm install -g newman
   ```
3. Run a Postman collection using Newman:

   ```sh
   newman run path/to/your/collection.json
   ```

- You can also generate HTML reports:

  ```sh
  newman run path/to/your/collection.json -r htmlextra
  ```

### Swagger
**Swagger** is an open-source tool that helps you design, build, document, and consume RESTful web services. To use Swagger:

- Access the Swagger UI by navigating to the Swagger endpoint URL, typically provided by the API you are testing.
- Use the Swagger UI to explore and interact with the API endpoints.
- View the detailed API documentation, including the available endpoints, request parameters, and response formats.

## Content
- Trello API Postman Collection & Newman Report
- IdeaCenter API Postman Collection
- Story Spoil API Postman Collection
- Foody API Postman Collection
- Revue Crafters API Postman Collection

## Contributing
Contributions are welcome! If you have any improvements or bug fixes, feel free to open a pull request.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Contact
For any questions or suggestions, please reach out to me or open an issue in the repository.
