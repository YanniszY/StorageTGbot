# StorageBot

**StorageBot** is a simple Telegram bot built with `aiogram3` that allows users to upload files and retrieve their unique Telegram file ID. This file ID can then be used by anyone to access and download the uploaded file. The bot functions as a lightweight file-sharing platform, where anyone who knows the file ID can retrieve the corresponding file.

## Features

- **File Upload**: Users can send any file directly to the bot.
- **File ID Retrieval**: The bot instantly responds with the unique ID of the uploaded file.
- **File Sharing**: Any user with the specific file ID can access and download the file, making StorageBot a convenient tool for quick sharing.

## Important Disclaimer

**StorageBot does not protect files with passwords or any other authentication methods.** If someone obtains a file ID, they will be able to download the file associated with it.

**Please do not send the following types of files to the bot:**
- Nudes or any other explicit/personal materials.
- Important documents (e.g., passports, driver's licenses, ID cards, etc.).
- Files containing confidential or sensitive data.

**StorageBot** is strictly intended for sharing public or non-sensitive files. Use it with caution!

## Installation & Usage

1. **Clone the repository**:
```sh
    git clone [https://github.com/YanniszY/StorageTGbot.git](https://github.com/YanniszY/StorageTGbot.git)
```

2. **Install dependencies**:
```sh
    pip install -r requirements.txt
```

3. **Configure the bot**:
    - Create a `.env` file in the root directory.
    - Add your bot token:
```env
      BOT_TOKEN=your_bot_token
```

4. **Run the bot**:
```sh
    python bot.py
```
