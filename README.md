# Spotify Clone Project

## How to Setup & Run this Project

### Install Node.js (Ignore If Already Installed)
1. Visit the official Node.js website: [Node.js Download](https://nodejs.org/en/download/)
2. Download the Node.js installer.
3. Run the installer.
4. Follow the prompts in the installer.

**First Run Backend then Frontend & Admin**

### Steps To Setup Backend Of The Project
1. Open the project folder in VS Code.
2. Open Integrated Terminal:
    - Right-click on `spotify-backend` > Select “Open In Integrated Terminal”.
3. Type `npm install` and press Enter. Wait for the installation to be completed (requires Internet).
4. Setup Cloudinary for file storage:
    - Create an account and login to: [Cloudinary](https://cloudinary.com/)
    - Go to Dashboard.
    - Copy and paste the Cloud Name, API Key, and Secret Key in the `.env` file.
5. Setup MongoDB:
    - Open this link: [MongoDB](https://www.mongodb.com/)
    - Sign up on the website.
    - Click on the New Project option.
    - After creating the project, go to the Database section & build a database.
    - Select M0 & your region & create the database.
    - Setup username & password & create the user (do not use the ‘@’ symbol in the password).
    - Click on Finish & Close.
    - Whitelist IP `0.0.0.0` & click on Add Entry.
    - Click on Connect.
    - Select Compass option.
    - Copy the connection string.
    - Paste it in the `.env` file and replace the password with the one you set previously. Save the changes.
6. To run the backend, use `npm run server` in the integrated terminal.

### Steps To Run Frontend Of The Project
1. Right-click on `spotify-clone` > Select “Open In Integrated Terminal”.
2. Type `npm install` and press Enter. Wait for the installation to be completed (requires Internet).
3. After installation, you will see the `node_modules` folder in the sidebar.
4. Type `npm run dev` in the terminal.
5. You will see the ‘localhost’ link in the terminal. Open that link in the browser.

### Steps To Run Admin Panel Of The Project
1. Right-click on `spotify-admin` > Select “Open In Integrated Terminal”.
2. Type `npm install` and press Enter. Wait for the installation to be completed (requires Internet).
3. After installation, you will see the `node_modules` folder in the sidebar.
4. Type `npm run dev` in the terminal.
5. You will see the ‘localhost’ link in the terminal. Open that link in the browser.