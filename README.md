# Secrets Project - Lisper

This project, inspired by "The Complete 2023 Web Development Bootcamp by Angela Yu," is the Secrets project, akin to the Whisper app, allowing users to reveal their deepest, darkest secrets anonymously. The project involves the use of the Secrets API, enabling users to access random secrets, and the following procedure:

![image](https://github.com/riju951/SecretsProject_Lisper_The-Complete-2023-Web-Development-Bootcamp/assets/82694741/9878378d-6300-4b40-9748-1249c0a71d99)

![image](https://github.com/riju951/SecretsProject_Lisper_The-Complete-2023-Web-Development-Bootcamp/assets/82694741/2d9878ec-9581-452a-8be1-313f92e1633d)

## Procedure

To run the Secrets project, follow these steps:

1. **Import Express and Axios:** Import the necessary libraries, such as Express and Axios.

2. **Create Express App:** Create an Express app and set the port number for server hosting.

3. **Utilize Static Files:** Use the public folder to serve static files for the application.

4. **Render Index Page:** When a user visits the home page, render the `index.ejs` file.

5. **Fetch and Display Secrets:** Use Axios to retrieve a random secret and pass it to `index.ejs` for display, including the secret content and the username of the secret.

6. **Start the Server:** Listen on the predefined port and start the server. Upon refreshing, different secrets will be revealed.

The Secrets project relies on the above steps for its functionality.

## Project Structure

The structure of the project folders is as follows:

```
Secrets_Project_Lisper/
├── public/
│   └── styles/
│       └── style.css
├── views/
│   └── index.ejs
├── index.js
├── package.json
└── README.md
```

## How to Download and Run Locally

To execute this project locally, perform the following steps:

1. **Clone the Repository:** Use Git to clone the repository to your local machine:

   ```bash
   git clone <repository_URL>
   ```

2. **Install Dependencies:** Navigate into the project directory and install the necessary dependencies using npm:

   ```bash
   cd Secrets_Project_Lisper/
   npm install
   ```

3. **Start the Server:** Run the server using Node.js:

   ```bash
   node index.js
   ```

Upon successful setup, visit the home page to view and reveal secrets anonymously.


