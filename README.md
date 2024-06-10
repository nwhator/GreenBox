# GreenBox

## About GreenBox
GreenBox is an innovative solution aimed at tackling the significant environmental issue of plastic waste. By integrating smart recycling units with a user-friendly mobile app and blockchain technology, GreenBox incentivizes consumers to recycle plastic bottles. Users are rewarded with tokens for their recycling efforts, which can be tracked and redeemed through the GreenBox platform.

## Chatbot Overview
The GreenBox chatbot is designed to assist users with queries related to recycling and the GreenBox platform. Built using Python and TensorFlow, the chatbot is trained on a custom `intents.json` file to understand and respond to user inputs effectively.

## Features
- **Real-time Assistance:** Provides instant responses to user queries about recycling and GreenBox.
- **User-Friendly Interaction:** Easy-to-use interface for engaging with users.
- **Customizable:** Trained on a custom set of intents, making it adaptable to various needs.

## Prerequisites
Before running the chatbot, ensure you have the following installed:
- Python 3.7+
- TensorFlow 2.14
- NLTK
- Keras
- Other dependencies listed in `requirements.txt`

## Installation
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/greenbox-chatbot.git
   cd greenbox-chatbot
   ```

2. **Create a Virtual Environment:**
   ```bash
   python -m venv chatbot_env
   ```

3. **Activate the Virtual Environment:**
   - On Windows:
     ```bash
     chatbot_env\Scripts\activate
     ```
   - On macOS/Linux:
     ```bash
     source chatbot_env/bin/activate
     ```

4. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

5. **Download NLTK Data:**
   Open a Python shell and run the following:
   ```python
   import nltk
   nltk.download('punkt')
   nltk.download('wordnet')
   ```

## Running the Chatbot
1. **Ensure your virtual environment is activated.**

2. **Run the `chatbot.py` Script:**
   ```bash
   python chatbot.py
   ```

3. **Interact with the Chatbot:**
   - The chatbot will prompt you to enter a message.
   - Type your query and receive a response from the chatbot.

## How to Use
- **Start the Chatbot:** Follow the steps in the "Running the Chatbot" section.
- **Ask Questions:** Enter your queries related to recycling or the GreenBox platform.
- **Receive Responses:** The chatbot will provide relevant answers based on the trained intents.

## Customizing the Chatbot
1. **Edit `intents.json`:** Update or add new intents to the `intents.json` file to customize the chatbot's responses.

2. **Retrain the Model:**
   If you make changes to `intents.json`, you'll need to retrain the model:
   - Follow the steps in your training script (`train.py` or similar) to update the model.

3. **Update Dependencies:**
   Ensure any new dependencies are added to `requirements.txt` and installed in your environment.

## Troubleshooting
- **TensorFlow DLL Load Error:** If you encounter a DLL load error with TensorFlow, ensure you are using TensorFlow 2.14, as this version has been verified to work without such issues.
- **Missing NLTK Data:** Ensure you have downloaded the required NLTK data packages (`punkt` and `wordnet`).

## Contributing
We welcome contributions to improve the GreenBox chatbot. Please fork the repository and submit pull requests with your enhancements.

## License
This project is licensed under the MIT License. See the LICENSE file for details.
