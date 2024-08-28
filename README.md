# API Authentication Example with Express and Secrets API

## Overview
- ONE OF THE PROJECT IN UDEMY "The Complete 2024 Web Development Bootcamp"
- This project demonstrates how to interact with an API using various authentication methods, including no authentication, basic authentication, API key authentication, and bearer token authentication. It uses the Secrets API (https://secrets-api.appbrewery.com/) to fetch data.

## Features
- **No Authentication**: Fetches random secrets without any authentication.
- **Basic Authentication**: Fetches secrets from a specific page using basic authentication.
- **API Key Authentication**: Filters secrets based on a score using an API key.
- **Bearer Token Authentication**: Retrieves a secret by ID using a bearer token.

## Technologies:
- **Node.js**
- **Express.js**
- **Axios**
- **EJS**
- **Secrets API**

## Getting Started

### Prerequisites
- Node.js
- npm (Node Package Manager)

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/J-Maica/-Project-API-Auth

2. **Install dependencies:**
   - npm install

3. **Open the index.js file and fill in the authentication details:**
   const yourUsername = "your-username";
   const yourPassword = "your-password";
   const yourAPIKey = "your-api-key";
   const yourBearerToken = "your-bearer-token";
   _View documentation for more information regarding the use of API_ 
     
4. **Start the server:**
   - node index.js
   - open web browser: http://localhost:3000
  
## Preview   
   - Display the result of every API call based on the selected API Authentication process
![Screenshot 2024-08-28 191159](https://github.com/user-attachments/assets/431c3542-9a57-4ded-8a66-c0931d71bc1a)
![Screenshot 2024-08-28 191151](https://github.com/user-attachments/assets/5dc3387c-b2d2-4144-a51f-f210dec9ca58)
![Screenshot 2024-08-28 191137](https://github.com/user-attachments/assets/6e6de053-28c1-49df-922b-111ed47549fd)
![Screenshot 2024-08-28 191206](https://github.com/user-attachments/assets/8f189f93-d595-43ff-ad96-b2a8594889fc)


## License
This project is for educational purposes and is based on content from the Udemy course "The Complete 2024 Web Development Bootcamp".
