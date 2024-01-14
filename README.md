# File Sharing Application

This is a simple file sharing application built with Node.js, Express, and MongoDB. It allows users to upload files, optionally protect them with a password, and share a link to download the files. The number of times a file has been downloaded is tracked.

## Features

- File upload with optional password protection
- File download with password verification (if password-protected)
- Download count tracking

## Technologies Used

- Node.js
- Express
- MongoDB (with Mongoose)
- Multer (for handling file uploads)
- bcrypt (for password hashing)

## Setup

1.  Clone the repository.
2.  Install dependencies with the following commands:
    bash

          npm init -y npm i express mongoose multer ejs bcryptjs dotenv npm i --save-dev nodemon

3.  Add the following script to your `package.json` file:

```json
"scripts": {
  "devStart": "nodemon server.js"
}
```

4. Set up your environment variables in a .env file in the root directory. You will need:
   DATABASE_URL: Your MongoDB connection string
   PORT: The port you want the server to run on

5. Run the server with npm run devStart.

bash

    npm run devStart.

## Usage

- To upload a file, go to the home page, select a file, optionally enter a password, and click "Share".
- After uploading, you will be given a link to share for others to download the file.
- If a file is password-protected, the correct password must be entered to download the file.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

```

```
