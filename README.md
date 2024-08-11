# Discord Music Bot
A simple and powerful Discord music bot built using Python and discord.py. This bot allows users to play music from various sources like YouTube directly in their Discord server.

## Features
• Play music from YouTube
• Queue system to manage songs
• Volume control
• Pause, resume, skip, and stop commands
• User-friendly interface with commands
## Installation
### Prerequisites
1. Python 3.8 or higher
2. A Discord bot token (You can get one from the Discord Developer Portal)
3. FFmpeg (for audio processing)
4. Steps
## Clone the repository:
```
git clone https://github.com/PrabhuPugal/Discord-Music-Bot.git
cd Discord-Music-Bot
```

## Create a virtual environment and activate it:
```
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```
## Install dependencies:
```
pip install -r requirements.txt
```
## Configure the bot: Create a .env file in the root directory and add your Discord bot token:
```
DISCORD_TOKEN=your_discord_bot_token
```
## Run the bot:
```
python bot.py
```
## Usage
Once the bot is running, you can use the following commands in your Discord server:
```
!play <song_name_or_url>: Plays a song from YouTube.
!pause: Pauses the current song.
!resume: Resumes the paused song.
!skip: Skips the current song.
!stop: Stops the music and clears the queue.
!volume <value>: Sets the volume (0-100).
```
## Contributing
Contributions are welcome! If you would like to contribute to the development of the Bank Management System, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and test thoroughly.
4. Submit a pull request with a clear description of the changes.
5. Please ensure that your code adheres to the project's coding standards and includes appropriate documentation.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.

## Contact
For questions or feedback, please reach out to me at prabhupugal01@gmail.com.
