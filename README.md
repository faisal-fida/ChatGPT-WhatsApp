# ChatGPT-WhatsApp Integration

This project demonstrates the integration of ChatGPT with WhatsApp using Python and Selenium. It automates the process of sending questions to ChatGPT and retrieving responses to be sent back on WhatsApp.

## Features

- **Automated Browser Interaction**: Utilizes `undetected_chromedriver` to handle browser automation, ensuring it bypasses bot detection.
- **Multi-Page Synchronization**: Simultaneous interaction with ChatGPT and WhatsApp Web.
- **Dynamic Content Handling**: Waits for new messages and handles real-time communication.

## Setup

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/faisal-fida/ChatGPT-WhatsApp.git
    cd ChatGPT-WhatsApp
    ```
2. **Install Dependencies**:
    ```bash
    pip install -r requirements.txt
    ```
3. **Run the Notebook**:
    Open `chatgpt_WhatsApp.ipynb` in Jupyter Notebook and execute.

## Key Components

- **Browser Initialization**: Sets up incognito mode and initializes two browser instances for ChatGPT and WhatsApp.
- **Question Sending**: Detects new messages on WhatsApp, sends them to ChatGPT, and retrieves the response.
- **Answer Sending**: Sends the retrieved ChatGPT response back to WhatsApp.

## Challenges

- **Bot Detection**: Overcame issues with browser bot detection using `undetected_chromedriver`.
- **Synchronization**: Managed to synchronize between two browser instances effectively.
- **Timeout Handling**: Implemented timeout handling to ensure smooth operation even in case of delays.

## Solutions

- **Efficient Browser Management**: Utilized Selenium's WebDriverWait to handle dynamic content loading.
- **Error Handling**: Incorporated try-finally blocks to handle exceptions and ensure reliability.
- **Real-time Communication**: Achieved real-time question-answer flow between WhatsApp and ChatGPT.

## Conclusion

This project showcases the potential of integrating AI with messaging platforms, providing a scalable solution for automated communication. It addresses various complexities and challenges with efficient solutions, making it a robust and reliable system.

For more details, please refer to the [source code](https://github.com/faisal-fida/ChatGPT-WhatsApp/blob/main/chatgpt_WhatsApp.ipynb).
