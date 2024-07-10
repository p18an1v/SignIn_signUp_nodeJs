
## Technologies Used
- **Frontend:** React, Vite
- **Backend:** Node.js, Express
- **Database:** MongoDB
- **Authentication:** JWT, bcrypt
- **Other:** dotenv, Mongoose, crypto

## Getting Started

### Prerequisites
- Node.js
- npm
- MongoDB

### Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/p18an1v/SignIn_signUp_nodeJss
   cd your-repo-name
Install dependencies:

sh
Copy code
npm install
Set up environment variables:
Create a .env file in the root directory and add the following:

sh
Copy code
MONGODB_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
PORT=8000
Start the development server:

sh
Copy code
npm run dev
API Endpoints
Register
URL: http://localhost:8000/api/auth/register
Method: POST
Body:
json
Copy code
{
  "firstName": "",
  "lastName": "",
  "username": "",
  "phoneNumber": "",
  "email":"",
  "password": ""
}
Verify OTP
URL: http://localhost:8000/api/auth/verify-otp
Method: POST
Body:
json
Copy code
{
  "email": "",
  "otp": ""
}
Login
URL: http://localhost:8000/api/auth/login
Method: POST
Body:
json
Copy code
{
  "email": "",
  "password": ""
}
Usage
Explain how to use your application. Include any relevant screenshots or examples.

Contributing
Fork the repository
Create a new branch: git checkout -b feature/your-feature-name
Commit your changes: git commit -m 'Add some feature'
Push to the branch: git push origin feature/your-feature-name
Open a pull request
License
This project is licensed under the MIT License - see the LICENSE file for details.


You can save this content in a file named `README.md` in the root directory of your project. This file will provide a comprehensive overview of your project, making it easier for others (and yourself) to understand and contribute.





