# PCEX-Redeemer

Welcome to the Redeemer Bot! This application automates the process of redeeming codes from a Telegram group and submitting them on the PCEX website. Follow the steps below to set up and run the bot.

## What You Need

Before running the bot, ensure you have the following:

1. **Telegram Account**: You need a Telegram account to use this bot.
2. **License Key**: A valid license key is required to activate the bot. Contact me on [Telegram](https://t.me/Ali_Abbas_01) to get one.
3. **Google Chrome**: The bot uses Google Chrome to interact with the PCEX website. Make sure Chrome is installed on your computer.
4. **Environment File (.env)**: A file containing your API credentials and login details.
## How It Works

To begin using the script, ensure that it is running continuously, as it needs to remain active in order to redeem the code. After validating your key and logging in, the script will continuously monitor for eligible codes to redeem. As long as the script is running, it will automatically redeem any new codes it detects, ensuring you never miss an opportunity. Here's a step-by-step overview of the process:

1. **Starting the Script:**  
   When you launch the script, you will be prompted to enter your valid license key. This key is used to authenticate your session and ensure proper access.

2. **Authentication via Telegram:**  
   After entering the license key, the script will communicate with Telegram to send a one-time authentication code. This code serves as a security measure to verify your identity.

3. **Login & Code Redemption:**  
   Once the script detects the authentication code from Telegram, it will automatically launch the Chrome browser, **log in to your account using the <mark>.env file stored on your computer</mark>**, and proceed with redeeming the code.

4. **Ending the Session:**  
   After the redemption process is completed, the Chrome window will close, marking the end of the transaction.

### Important Notes:
- **Keep the script running** to ensure continuous code redemption.
- Ensure that the Telegram authentication process completes successfully before relying on the script for automatic redemptions.

By following these steps, you'll be able to redeem codes seamlessly without needing to manually intervene, as long as the script is running in the background.

## Setup Instructions

### 1. Install Google Chrome

Download and install Google Chrome from [here](https://www.google.com/chrome/).

### 2. Prepare the .env File

The bot requires a `.env` file to store your credentials safely. Follow these steps:

1. Create a file named `.env` in the same folder where the `.exe` file is located.
2. Open it using any text editor (e.g., Notepad, VS Code).
3. Copy and paste the following content into the file:
 ```
   API_ID=your_telegram_api_id
   API_HASH=your_telegram_api_hash
   PHONE_NUMBER=your_telegram_phone_number in this format +97312345678
   PCEX_USERNAME=your_pcex_email
   PCEX_PASSWORD=your_pcex_password
   ```

4. Replace the placeholders with your actual credentials:
- `your_telegram_api_id` and `your_telegram_api_hash`: Obtain these from [my.telegram.org](https://my.telegram.org/apps) by creating a new app. *(Note: No need to fill the URL field.)*

### 3. Run the Redeemer Bot

- Double-click the `redeemer.exe` file to start the bot.
- When prompted, enter your **license key** and press **Enter**.
- If the license key is valid, the bot will start running.

## Troubleshooting

If you encounter any issues, please contact me on [Telegram](https://t.me/Ali_Abbas_01).

## Disclaimer

- This bot is for **personal use only**. Do not share your credentials or license key with others.
- The bot relies on the structure of the PCEX website. If the website changes, the bot may stop working and require an update.

Thank you for using the Redeemer Bot! If you have any questions or need help, feel free to reach out.

  
