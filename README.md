# Project Name

## Introduction
Brief introduction about the project.

## Getting Started
Follow these steps to set up and run the project on your local machine.

### Prerequisites
- [Node.js](https://nodejs.org/) installed on your machine
- [MongoDB](https://www.mongodb.com/) installed on your machine

### Installation
1. Clone or download the project on your PC.
2. Open a terminal window and navigate to the project directory.

### Setting up MongoDB

- Verify that MongoDB is installed:
  ```bash
  mongod --version
  ```
- If MongoDB is not installed, follow the installation instructions on the [MongoDB website](https://docs.mongodb.com/manual/tutorial/install-mongodb-on-windows/).

### Connecting to MongoDB
#### Mac
- Start MongoDB service:
  ```bash
  brew services start mongodb-community@6.0
  ```
  Here, put the version on your pc

#### Windows
- Start MongoDB service (replace `<path>` with the path where MongoDB is installed):
  ```bash
  net start MongoDB
  ```

### Creating Database and Collection
1. Open MongoDB Compass.
2. Click on "Create Database".
3. Enter "w3villa" as the Database Name.
4. Enter "users" as the Collection Name.
5. Click on "Create Database".


### Running the Project
1. Open a terminal window and navigate to the `backend` directory.
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the backend server:
   ```bash
   npm start
   ```
4. Open a new terminal window and navigate to the project directory.
5. Navigate to the `frontend` directory.
6. Install dependencies:
   ```bash
   npm install
   ```
7. Start the frontend server:
   ```bash
   npm start
   ```

Now you should be able to access the project in your web browser.

## Dependencies
- [express](https://www.npmjs.com/package/express)
- [bcryptjs](https://www.npmjs.com/package/bcryptjs)
- [jsonwebtoken](https://www.npmjs.com/package/jsonwebtoken)
- [cors](https://www.npmjs.com/package/cors)
- [cookie-parser](https://www.npmjs.com/package/cookie-parser)
- [body-parser](https://www.npmjs.com/package/body-parser)
- [mongoose](https://www.npmjs.com/package/mongoose)

Install these dependencies using the following command:
```bash
npm install express bcryptjs jsonwebtoken cors cookie-parser body-parser mongoose
```

## License
This project is licensed under the [MIT License](LICENSE).
