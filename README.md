# Gemini Chatbot Clone

This project is a clone of the Gemini chatbot interface. It features a sleek and modern UI with light and dark modes, responsive design, and a simulated message generation feature. The chatbot provides an interactive user experience with typing effects, suggestions, and dynamic content loading.

## Features

- **Light/Dark Mode**: Toggle between light and dark themes, with colors dynamically changing based on the user's selection.
- **Responsive Design**: Optimized for mobile and desktop devices, ensuring a smooth experience across various screen sizes.
- **Message Interaction**: Users can send messages, receive API-generated responses, and copy messages.
- **Typing Effect**: API responses are shown with a typing effect for a more natural chat experience.
- **Local Storage**: Chats are saved and restored across sessions using local storage, allowing users to view previous chats.

## Installation

To use this project locally, follow these steps:

1. **Clone the repository**

    ```bash
    git clone https://github.com/yourusername/gemini-chatbot-clone.git
    ```

2. **Navigate into the project directory**

    ```bash
    cd gemini-chatbot-clone
    ```

3. **Open index.html in your browser**

   No installation required for the frontend. Simply open the `index.html` file in your browser to start using the chatbot.

## Files Overview

### 1. `index.html`

The HTML file that provides the structure of the chatbot interface. It includes the markup for the chat window, message display area, input form, and buttons for theme toggling and deleting chats.

- **Main Chat Area**: Displays messages from the user and chatbot.
- **Suggestions List**: Displays predefined message suggestions the user can click.
- **Typing Input Area**: Allows the user to type messages and send them.
- **Theme Toggle**: Switches between light and dark mode.
- **Delete Chat Button**: Clears the chat history.

### 2. `script.js`

The JavaScript file responsible for the following functionality:

- Handling user input and generating API responses.
- Managing the UI state (loading, errors, etc.).
- Storing and retrieving chat history from `localStorage`.
- Implementing the typing effect for chatbot responses.
- Adding functionality for copying messages and deleting chat history.

### 3. `style.css`

The CSS file styles the chatbot interface. It handles:

- **Light/dark mode** color schemes using CSS variables.
- Layouts for the chat window, input field, and suggestions.
- Typing effect and message transitions.
- Responsive adjustments for different screen sizes.

## Technologies Used

- **HTML** for structuring the content.
- **CSS** for styling, including responsive design and theme support.
- **JavaScript** for interactivity, API integration, and DOM manipulation.

## Future Improvements

- **API Integration**: Replace the mock response with real API calls to generate dynamic content (currently uses a placeholder response).
- **User Authentication**: Add user authentication to save chat history across different devices.
- **Voice Support**: Add speech-to-text and text-to-speech functionality for voice-based interactions.

## Contributing

1. **Fork the repository**.
2. **Create a new branch** (e.g., `git checkout -b feature-name`).
3. **Make your changes and commit them** (`git commit -am 'Add new feature'`).
4. **Push to the branch** (`git push origin feature-name`).
5. **Create a new pull request**.
