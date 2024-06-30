# Summer Heat Waves Mobile Alert System

## Overview
The Summer Heat Waves Mobile Alert System is designed to predict heatwaves using machine learning and send alerts to mobile devices. The project utilizes a RandomForestClassifier for predicting heatwaves based on input data. The input must be a 2D array in the format `[[year, month, day, temperature]]`. The project includes a Jupyter Notebook (`.ipynb`) file for the code and a data file (`data.csv`) for training and testing the model. A Telegram bot is used to send mobile alerts, but the alert system can be customized by modifying the `SendMobileAlert()` function in the code.

## Features
- **Heatwave Prediction:** Uses RandomForestClassifier to predict heatwaves based on historical data.
- **Mobile Alerts:** Sends alerts to mobile devices via SMS or through any social media platform.
- **Customizable Alert System:** The alert system can be modified by changing the `SendMobileAlert()` function in the code.

## Model
The project employs a RandomForestClassifier, a robust and versatile machine learning model suitable for classification tasks. The model is trained on historical weather data to predict potential heatwaves.

## Dataset
The dataset (`data.csv`) contains historical weather data, including the year, month, day, and temperature. This data is used to train and test the RandomForestClassifier.

## Requirements
To run this project, you will need the following:
- Python 3.x
- Jupyter Notebook
- pandas
- scikit-learn
- python-telegram-bot

You can install the necessary packages using pip:
```bash
pip install jupyterlab pandas scikit-learn python-telegram-bot
```
## Usage
### 1. Clone the repository
```bash
git clone https://github.com/Naveen-369/MLLearningOdyssey.git
cd MLLearningOdyssey/Summer_Heat_Waves_Mobile_ALert_System/
```
### 2. Run the Jupyter Notebook
→ The data source is readyly present in the folder `Summer_Heat_Waves_Mobile_ALert_System` along with the python file in `.ipynb` formate.

→ Open the Jupyter Notebook and run the cells to execute the code.
```bash
jupyter notebook heatwave_alert_system.ipynb
```
### 3. Modify the Alert System
I have used telegram Bot API to check the mobile integration of the alert system, If you want to use a different alert system, modify the `SendMobileAlert()` function in the code.

## Project Structure
- **SHWaveDetection.ipynb :** Jupyter Notebook containing the code for training the model, predicting heatwaves and a module to send alerts via a telegram bot.
- **Data.csv :** CSV file containing historical weather data used for training and testing the model.

## Telegram Bot Setup
To set up the Telegram bot for sending mobile alerts:

1. Create a Telegram bot and get the API token. Refer to the Telegram Bot API documentation for detailed instructions.
2. Replace the placeholder token in the heatwave_alert_system.ipynb file with your actual Telegram bot API token.
3. Run the notebook to start receiving alerts via Telegram.

## Contributing
Contributions are welcome! Please submit a pull request or open an issue to discuss improvements, bug fixes, or new features.

## License
This project is licensed under the MIT License. See the `LICENSE` file in the root directory for more details.

## Acknowledgements
- [jbrownlee](https://github.com/jbrownlee) listed the dataset used for training this model in his public repository `Datasets` .
- [BotFather](https://telegram.me/BotFather), an telegram bot that makes it easy to create a bot which is used for testing the alert system.
