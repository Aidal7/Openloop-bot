# OpenLoop Sentry Node bot

## Description
This script automates registration, network or node operations for OpenLoop Sentry Node.

## Features
- **Automated node interaction**
- **Automatic account registration**
- **Multi account**
- **Proxy support**

## Prerequisites
- [Node.js](https://nodejs.org/) (version 12 or higher)

## Installation

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/recitativonika/openloop-node-bot.git
   ```
2. Navigate to the project directory:
   ```bash
   cd openloop-node-bot
   ```
3. Install the necessary dependencies:
   ```bash
   npm install
   ```

## Usage
1. Register OpenLoop Sentry Node account first, if you don't have you can register in the extension [here](https://chromewebstore.google.com/detail/openloopso-sentry-node-ex/effapmdildnpkiaeghlkicpfflpiambm) or you can put email and password that you desire in to automatically register, check next part to do that.
2. Set and Modify `user.txt` with your account data. If you don't have account, you can just put email and password that you want to register and it will automatically register account for you. Put the data in `user.txt` with format like this:
   ```bash
   email1,password1,proxy1
   email2,password2,proxy2
   ```
   if you dont want to use proxy, you don't need to put the proxy.
3. After put data in `user.txt`, run this script
    ```bash
    node setup.js
    ```
   This script will automatically register account if you don't have account .The setup script will automatically fill and save the needed data to the `data.txt`, it will look like this:
    ```bash
    email1,token1,proxy1
    email2,token2,proxy2
    ```
   if you not use proxy when registering account and want to use proxy when run the bot, you can add it manually or rerun setup.js with proxy enabled
4. Run the script:
   ```bash
   node index.js
   ```

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Note
This script only for testing purpose, using this script might violates ToS and may get your account permanently banned.

My reff code if you want to use :) : 
```bash
ol36e88d4f
```
