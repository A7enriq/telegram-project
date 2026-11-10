Telegram Bot Media Project
Introduction
This project is a Telegram bot developed using Python and the TeleBot library. It allows users to send and receive media files through Telegram.
Features
Display a media menu using the /media command.
Send a local photo from the project folder.
Send a local PDF document.
Send an online photo using an image URL.
Use inline keyboard buttons to select media options.
Technologies
Python
TeleBot (pyTelegramBotAPI)
Telegram Bot API
Project Structure
project/ ├── main.py ├── base.py └── media/ ├── photo.jpg └── document.pdf 
How to Run
Install the required library: pip install pyTelegramBotAPI 
Configure your Telegram bot token in base.py.
Place the photo and PDF files inside the media folder.
Run the Python file: python main.py 
Open your Telegram bot and send /media.
Usage
After sending /media, the bot displays three buttons:
Local Photo Upload
Local Document Upload
Online Photo Upload
Select one of the buttons to receive the corresponding media.
Author
Python Programming Student
