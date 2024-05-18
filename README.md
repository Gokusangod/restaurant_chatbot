# Bestos Chatbot

## Overview

Bestos Chatbot is an advanced, interactive chatbot designed to assist users with inquiries related to a restaurant, including checking table availability, making reservations, viewing the menu, and placing orders. It leverages Natural Language Processing (NLP) to understand and respond to user queries in real-time.

## Features

- **Real-time Responses**: Get instant answers to your questions about the restaurant.
- **Multi-intent Handling**: Capable of understanding various types of inquiries including greetings, safety protocols, opening hours, and more.
- **Order Processing**: Easily place orders for food items through the chatbot.
- **Customizable**: Extend and modify the chatbot to fit specific needs and functionalities.
- **Easy Integration**: Simple to integrate with web interfaces using HTTP requests.

## Installation

### Prerequisites

- Python 3.x
- pip
- ngrok account for tunneling (optional)

### Steps

1. Clone the repository:
    ```sh
    git clone https://github.com/your-username/bestos-chatbot.git
    ```
2. Navigate to the project directory:
    ```sh
    cd bestos-chatbot
    ```
3. Install the required dependencies:
    ```sh
    pip install -r requirements.txt
    ```

## Usage

### Running the Server

1. **Start the server:**
    ```sh
    python server.py
    ```

2. **Optional: Start ngrok for tunneling:**
    ```sh
    ngrok http 8000
    ```

### Interacting with the Chatbot

You can interact with the chatbot through a web interface. Here’s how to use it:

1. **Access the Web Interface:**
   - Open your browser and navigate to `http://127.0.0.1:8000` or the ngrok URL if you are using ngrok.

2. **Send a Message:**
   - Type your message into the input box and press Enter.
   - The chatbot will respond based on the input provided.

### Example Commands

- **Greeting:**
  - "Hello!"
  - "Good morning!"

- **COVID-19 Safety Measures:**
  - "What are your COVID-19 safety protocols?"

- **Opening Hours:**
  - "What time are you open?"

- **Table Availability:**
  - "Are there any tables available right now?"

- **Making Reservations:**
  - "I want to reserve a table for two."

- **Ordering Food:**
  - "I'd like to order a pizza."

## Project Structure

- `server.py`: Main server script for running the chatbot.
- `styles.css`: CSS file for styling the web interface.
- `index.html`: HTML file for the web interface.
- `script.js`: JavaScript file for client-side interactions.
- `requirements.txt`: List of dependencies required for the project.

## Contributing

We welcome contributions from the community! If you have suggestions, bug reports, or would like to contribute code, please open an issue or create a pull request.

### Steps to Contribute

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature/your-feature`).
6. Open a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- Thanks to the open-source community for their invaluable contributions and support.

