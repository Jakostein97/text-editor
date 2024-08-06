# Just Another Text Editor

## Description

Tech Talk Text Editor is a web-based text editor application designed to function both online and offline. It is built with modern web technologies, leveraging IndexedDB for offline data storage and Service Workers for a seamless user experience. The application can be installed as a Progressive Web App (PWA) and offers functionality such as auto-saving content and bundling JavaScript files using Webpack.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [License](#license)

## Installation

[GitHub Repo](https://github.com/Jakostein97/text-editor)

1. Clone the repository:
```
git clone https://github.com/yourusername/text-editor.git
cd text-editor
```
2. Install dependencies:
```
npm install
```
3. Start the application:
```
npm run start
```
This will start both the backend and the frontend servers.

## Usage

1. Open the Text Editor:
Open the application in your web browser. The IndexedDB database storage is created immediately.
2. Enter and Save Content:
Enter your content in the text editor. The content will be saved automatically when you click off the DOM window.
3. Reopen the Application:
Upon reopening the application, the previously saved content will be retrieved from IndexedDB.
4. Install as Desktop App:
Click on the Install button to download the web application as an icon on your desktop.

![Web App Screenshot](assets/images/Screenshot%202024-08-06%20192631.png)

## License

This project is licensed under the MIT License.