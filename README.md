
# MetaMask Signing App

This application allows users to sign a message using their MetaMask wallet and displays the `signedEK` and `signature` values. The app ensures user privacy as it does not save or store any information. All data resides on the user's browser and is wiped after use.

## Features
- Sign messages with MetaMask
- Display `signedEK` and `signature` values
- Copy values to clipboard
- No data storage; all information is wiped after the browser session ends

## Prerequisites
- Node.js installed
- MetaMask extension installed in your browser

## Instructions to Run Locally

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/metamask-signing-app.git
   cd metamask-signing-app
   ```

2. **Install Dependencies**:
   This app doesn't require additional Node.js dependencies besides `ethers`. If you haven't installed `ethers` yet, run:
   ```bash
   npm install ethers
   ```

3. **Run a Local Server**:
   You can use any static file server to run this app. For simplicity, we recommend using `http-server`.

   If you don't have `http-server` installed, you can install it globally:
   ```bash
   npm install -g http-server
   ```

   Start the server in the project directory:
   ```bash
   http-server
   ```

4. **Open the Application**:
   Open your browser and navigate to `http://localhost:8080` (or the URL provided by `http-server`).

## Security and Privacy
- The application does not save or store any user information.
- All data, including `signedEK` and `signature`, resides in the user's browser memory and is not transmitted or saved.
- The data is wiped after the browser session ends.

## Usage
1. Open the application in your browser.
2. Click the **"Sign Data"** button to sign a message with your MetaMask wallet.
3. The `signedEK` and `signature` values will be displayed on the page.
4. Use the **"Copy"** buttons to copy the values to your clipboard if needed.

## Contributing
Feel free to submit issues or pull requests if you have any improvements or bug fixes.

## License
This project is licensed under the MIT License.
