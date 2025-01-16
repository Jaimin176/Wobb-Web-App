# Wobb-Web-App

# Steps to Extract Files and Run the React.js Project

## Extract the ZIP File:
1. Locate the ZIP file on your computer.
2. Right-click on it and choose **Extract All...** or use your preferred unzipping tool (e.g., WinRAR, 7-Zip).
3. Choose a destination folder where the files will be extracted.

## Find the React.js Code (wobbclient):
1. Inside the extracted folder, locate the directory named `wobbclient` or equivalent that contains the React.js project files.
2. This folder should contain files like `package.json`, `src`, and `public`.

## Open the Terminal at wobbclient Path:
1. Navigate to the `wobbclient` folder in your file explorer.
2. **Option 1 (Windows):**
   - In the `wobbclient` folder, type `cmd` in the address bar and press **Enter**. This opens Command Prompt in the current directory.
3. **Option 2 (VS Code):**
   - Open Visual Studio Code.
   - Go to `File > Open Folder`, select the `wobbclient` folder, and click **Open**.
   - Then open the terminal in VS Code (`Ctrl + ~`).

## Install Dependencies:
1. In the terminal, type the following command:
   ```bash
   npm i
   ```
   This command will install all the required dependencies listed in the `package.json` file.
2. Wait until all modules are downloaded and installed.

## Start the Development Server:
1. After the installation is complete, type the following command to start the development server:
   ```bash
   npm start
   ```
2. This will start a development server, and you’ll see a message like:
   ```
   Compiled successfully!
   You can now view your app in the browser at http://localhost:3000
   ```

## Open the Site in Your Browser:
1. If your default browser doesn’t open automatically, manually open your browser and navigate to:
   ```
   http://localhost:3000
   ```

## View and Interact with Your Application:
1. Your React.js application should now be running, and you can interact with it on the browser.

## Troubleshooting:
### If `npm` is not recognized:
1. Ensure that Node.js is installed on your system.
2. Verify by typing:
   ```bash
   node -v
   npm -v
   ```

### If dependencies fail to install:
1. Check the `package.json` file for any issues.
2. Run:
   ```bash
   npm cache clean --force
   npm i
   ```

### If the development server doesn’t start:
1. Check for errors in the terminal.
2. Ensure no other process is running on port `3000`. You can terminate processes using:
   ```bash
   npx kill-port 3000
   
