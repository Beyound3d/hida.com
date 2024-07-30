# Hida.com - Social Media Application📲
Hida.com is a full-stack social media application built using the MERN stack (MongoDB, Express.js, React.js, and Node.js). This project is designed to provide users with a platform to share posts, like, comment, and interact with other users in a social media environment.

**Features**
- User authentication and authorization
- Create, read, update, and delete posts
- Like and unlike posts
- Comment on posts
- User profiles with the ability to upload profile pictures
- Real-time notifications for likes and comments
**Technologies Used**
1. MongoDB: Database for storing user data, posts, comments, and likes
2. Express.js: Backend framework to build the server and handle API requests
3. React.js: Frontend library to build the user interface
4. Node.js: JavaScript runtime for building the backend server


## 🗃️Installation
Clone the repository


```
git clone https://github.com/beyound3d/hida.com.git
```

```
cd hida.com
```

Install server dependencies

```
cd server
```

```
npm install
```

Install client dependencies

```
cd ../client
```

```
npm install
```

***Set up environment variables**:

Create a .env file in the root directory of the server and add the following:

```
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
```


**Run the application**:

Open two terminals:

Terminal 1: Run the server

```cd server
```

```
npm start
```


Terminal 2: Run the client

```
cd client
```

```
npm start
```


**Access the application**:

Open your browser and go to http://localhost:3000

# 📂Project Structure
- server/: Contains the backend code
 |  models/: Mongoose models for MongoDB
 |  routes/: API routes
 |  middleware/: Custom middleware functions
 |  controllers/: Functions to handle API requests
- client/: Contains the frontend code
 |  src/components/: React components
 |  src/pages/: React pages
 |  src/redux/: Redux setup for state management
 |  src/styles/: CSS styles

## 🫱🏽‍🫲🏻Contributing
Fork the repository:
1. Create your feature branch (git checkout -b feature/yourFeature)
2. Commit your changes (git commit -m 'Add some feature')
3. Push to the branch (git push origin feature/yourFeature)
4. Open a pull request

## 📑License
This project is licensed under the MIT License.

## 💫Acknowledgements
Thanks to the developers and contributors of the MERN stack and its libraries.

**Contact**:
For any inquiries or issues, please contact us at support@hida.com.

## 😎Learning Outcomes from Hida🤓:
 - backend installation of node and backend packages
 - backend configuartion and middleware setup
 - mongodb registering, installation and setup
 - data modelling and ERD diagram
 - authentication and authorization in node
 - user Router Setup
 - Backend Data Add and demo
 - frontent insatllation and setup
 - react Redux ff Architecture and react Router
