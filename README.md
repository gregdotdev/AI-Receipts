# AI Receipts 🧾

An intelligent Telegram bot that automatically analyzes receipt photos using Google's Gemini AI and stores the extracted spending data in an Excel file.

## Features

- 📸 **Photo Analysis**: Send a receipt photo to the bot and get instant spending analysis
- 🤖 **AI-Powered**: Powered by Google Gemini 1.5 Flash for accurate receipt recognition
- 📊 **Data Export**: Automatically saves results to Excel format
- 👤 **User Tracking**: Records which user submitted each receipt
- ⚡ **Real-time Processing**: Fast and efficient receipt analysis

## How It Works

1. Start the bot with `/start` command
2. Send a photo of your receipt
3. The bot analyzes the receipt using Gemini AI
4. Results are automatically saved to an Excel file

## Technology Stack

- **Python 3** - Core programming language
- **python-telegram-bot** - Telegram bot framework
- **Google Gemini AI** - AI-powered receipt analysis
- **openpyxl** - Excel file handling
- **requests** - HTTP requests for image processing

## Setup

### Prerequisites

- Python 3.8+
- Telegram Bot Token (get from [@BotFather](https://t.me/BotFather))
- Google Gemini API Key

### Installation

1. Clone the repository:
```bash
git clone https://github.com/gregdotdev/AI-Receipts.git
cd AI-Receipts
```

2. Install required packages:
```bash
pip install python-telegram-bot google-generativeai openpyxl requests
```

3. Configure your credentials:
- Replace `TELEGRAM_TOKEN` with your Telegram bot token
- Replace `GEMINI_API_KEY` with your Google Gemini API key

4. Run the bot:
```bash
python botai.py
```

## Configuration

Edit the following variables in `botai.py`:

```python
TELEGRAM_TOKEN = 'your-telegram-bot-token'
GEMINI_API_KEY = 'your-gemini-api-key'
EXCEL_FILE = 'resultados.xlsx'  # Output file name
```

## Usage

1. Start a conversation with your bot on Telegram
2. Use `/start` to begin
3. Send a clear photo of a receipt
4. Wait for the AI to analyze and extract the total spending
5. Results are automatically saved to the Excel file

## Project Structure

```
AI-Receipts/
├── botai.py          # Main bot logic
├── resultados.xlsx   # Generated output file
└── README.md         # This file
```

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is open source and available under the MIT License.

## Author

Created by [Gregorio](https://github.com/gregdotdev)

## Acknowledgments

- Google Gemini AI for powerful image analysis
- python-telegram-bot community for excellent documentation

