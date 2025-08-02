# Gemini Voice & Screen Chat 🚀

A real-time, conversational AI application that uses Google's latest Gemini model. It allows for natural voice conversations and can see your screen to provide contextual help and answers.

![Demo GIF](https://placehold.co/600x400/282c34/white?text=Your+Application+Screenshot+Here)
*(A GIF or screenshot of the application in action is highly recommended!)*

---

### ✨ Features

*   **Real-time Audio Chat:** Engage in low-latency, real-time voice conversations with the Gemini model.
*   **Live Screen Sharing:** Allow the AI to view your screen, enabling it to understand context and answer questions about what you're seeing.
*   **Automatic API Key Rotation:** If one API key reaches its usage limit, the application automatically switches to the next available key from your list.
*   **Simple UI:** A clean and intuitive user interface built with Python's native Tkinter library.

### 🛠️ Installation

1.  First, ensure you have [Python](https://www.python.org/downloads/) (version 3.9 or newer) installed on your system.
2.  On the main page of this repository, click the green `<> Code` button and select **Download ZIP**.
3.  Extract the downloaded ZIP file to a location of your choice.
4.  Open a terminal or Command Prompt and navigate into the extracted folder.
5.  Run the following command to install all the necessary libraries:
    ```bash
    pip install -r requirements.txt
    ```

### ▶️ How to Use

1.  In the main project folder, create a new text file and name it `api.txt`.
2.  Inside `api.txt`, paste your Google AI Studio API keys. Each key must be on a new line. For example:
    ```
    AIzaSyBkvUpuaure.........
    AIzaSyDQLsC2IAjA.........
    AIzaSyDR4pGXCBNQ.........
    ```
3.  **Important:** Rename the main Python script from `ai_studio_code (2).py` to something simple, like `app.py`.
4.  Now, run the application from your terminal with the following command:
    ```bash
    python app.py
    ```
5.  The application window will open. You can now start talking, or type your message in the input box and press Enter!

---

### 📜 License

This project is licensed under the **MIT License**. See the `LICENSE` file for more details.

### ❤️ Support My Work

If you find this project useful and want to support its future development, please consider becoming a sponsor. Your support is greatly appreciated and helps motivate me to build more open-source tools for everyone.

*(Your sponsor link will be added here later)*
