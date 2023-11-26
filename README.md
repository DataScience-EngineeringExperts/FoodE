# Open Source Project: FoodE Meal Planner Algorithm

## `meal_generator.py`

### Overview
`meal_generator.py` is a Python script designed for generating personalized meal suggestions. It uses OpenAI's GPT-4 for intelligent meal planning, interfaces with MongoDB for data management, and sends notifications to Microsoft Teams.

### Key Features
- **Environment Variable Loading**: Safely loads credentials and URLs from a `.env` file.
- **MongoDB Integration**: Utilizes MongoDB for storing user data, meal suggestions, and logs.
- **OpenAI API**: Leverages the capabilities of GPT-4 for generating creative and personalized meal suggestions.
- **Custom Logging**: Implements a custom logger that stores logs in MongoDB.
- **Teams Notifications**: Sends formatted meal suggestions to a specified Microsoft Teams channel.

### Configuration
- Ensure MongoDB and OpenAI API keys are set in the `.env` file.
- Define health, diet, and caution labels to filter meal suggestions based on user preferences.

### Usage
1. Set environment variables in `.env`.
2. Run `python meal_generator.py`.
3. Meal suggestions are generated and stored in MongoDB, and notifications are sent to Microsoft Teams.

### Dependencies
- Python 3.x
- `pymongo`
- `openai`
- `requests`
- `python-dotenv`
- `json`
- `logging`
- `datetime`

### Contribution
Contributions are welcome. Please fork the repository and submit pull requests with any enhancements.
