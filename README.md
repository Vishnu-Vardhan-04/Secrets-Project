# Secrets-Project

A Node.js + Express web app that fetches and displays secrets from the App Brewery Secrets API. The project demonstrates No Authentication API request, Axios integration, EJS templating, and server-side rendering with Express.

# 🚀 Features
Fetches secret data from a third-party API

Uses Axios for API communication

Uses No Authentication and fetches random secret from the secrets api websitr

Renders dynamic content using EJS

Built with Node.js and Express.js

##Optional

I have used No Authentication just to show but for security we can
#1. Basic Authentication :
Basic Authentication in an API is a simple method where the client sends a Base64-encoded string containing the username:password in the request header. It looks like this:

Authorization: Basic base64(username:password)

##2. API key Authorisation :
API Key Authorization is a method where a unique key (API key) is sent with each request to identify and authenticate the client. The key is usually passed in the request header or as a query parameter, like:

Authorization: Bearer YOUR_API_KEY

##3. Token Based Authentication :
Token-Based Authentication is a method where the client logs in once (usually with username and password) and receives a token (like a JWT - JSON Web Token). This token is then sent with each API request in the header:

Authorization: Bearer YOUR_TOKEN

The server verifies the token's validity and grants access without needing to resend login credentials, making it more secure and scalable for stateless applications.

##🛠️ Tech Stack

Node.js
Express.js
Axios
EJS (Embedded JavaScript Templates)

##📦 Installation

Clone the repo
git clone https://github.com/yourusername/secrets-project.git
cd secrets-project

Install dependencies
npm install

 Run the app
node index.js

##🔐 Secrets API Info

Base URL: https://secrets-api.appbrewery.com/

Authentication: API key via header
Example:
Authorization: Bearer YOUR_API_KEY

Endpoints:
GET /secrets – list all secrets (with optional filtering/pagination)
GET /secrets/:id – get secret by ID

##🧑‍💻 Author
Vishnu Vardhan

##📝 License
This project is licensed under the MIT License.
