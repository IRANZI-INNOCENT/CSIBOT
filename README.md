# Hunger Coping Strategies Index (CSI) Web Application

## Description

This project is a web application that allows users to input data related to various coping strategies used by households to manage hunger. The application calculates a weighted score based on the frequency of these strategies. This can help in understanding and assessing the severity of coping strategies employed by households.

## Features

- Input fields for location, household number, and number of people in the family.
- Input fields for the frequency of different coping strategies.
- Real-time calculation of a weighted score based on input data.
- Integration with Dialogflow for chatbot interaction.

## Technologies Used

- HTML
- CSS
- JavaScript
- Dialogflow

## Getting Started

### Prerequisites

To run this project, you need a web browser and an internet connection.

### Installation

1. Clone this repository to your local machine:

    ```bash
    git clone https://github.com/your-username/hunger-csi.git
    ```

2. Navigate to the project directory:

    ```bash
    cd hunger-csi
    ```

3. Open the `index.html` file in your preferred web browser.

### Usage

1. Open `index.html` in a web browser.
2. Enter the location, household number, and number of people in the family in the provided input fields.
3. Enter the frequency (0-7) for each coping strategy based on household practices.
4. The weighted score will be calculated and displayed in real-time as you input the data.
5. Interact with the embedded chatbot for more information or assistance.


### Chatbot Integration

The web application includes a Dialogflow chatbot named **CSIBot** for user interaction. This chatbot can assist users by providing information about the Hunger Coping Strategies Index and helping with any questions related to the application.

#### How to Use the Chatbot

1. The chatbot is embedded in the web application and will appear as a chat icon in the lower right corner of the screen.
2. Click on the chat icon to open the chatbot interface.
3. The chatbot will greet you with a welcome message.
4. You can type your questions or requests in the chat input field. The chatbot can help with:
    - Explaining what the Hunger Coping Strategies Index (CSI) is.
    - Providing instructions on how to use the application.
    - Answering general questions related to hunger coping strategies.
5. The chatbot is powered by Dialogflow and uses pre-defined intents to respond to user queries.

### File Structure
### File Structure

```plaintext
hunger-csi/
├── index.html
├── README.md
