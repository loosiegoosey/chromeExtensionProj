## Overview

Overview
The Chrome Extension Project is a simple, motivational tool for developers. Each time you open it, you'll be greeted with a motivational saying or funny image related to programming to keep you inspired and entertained as you code.

##
## Features

Features
- Randomly displays motivational sayings and funny images every time you interact with the extension.
- Easy-to-use interface.
- Lightweight and fast performance.

##
## Installation Instructions

Installation Instructions
To set up the Chrome Extension Project, follow these steps:

1. **Clone the repository**:
    ```sh
    git clone https://github.com/Nikkkidew/chromeExtensionProj.git
    ```
2. **Navigate to the project directory**:
    ```sh
    cd chromeExtensionProj
    ```
3. **Load the extension in Chrome**:
    1. Open Chrome and navigate to `chrome://extensions/`
    2. Enable 'Developer mode' by clicking the toggle switch in the top right corner.
    3. Click the 'Load unpacked' button and select the directory where you cloned the repository.

The extension is now installed and ready to use!

##
## Usage Examples

Usage Examples
1. **Open the Extension**:
    - Click on the extension icon in the Chrome toolbar.
    
2. **View Motivational Saying**:
    - Each time you click the extension icon, a new motivational image or saying will be displayed.

##
## Code Summary

Code Summary
The core functionality of the Chrome Extension Project is provided by a single JavaScript file, `popup.js`.

### Key File
- **`popup.js`**:
    - Contains an array of URLs linking to motivational sayings and funny images.
    - When the extension popup is opened, a random image or saying from the array is displayed.

### Code Sample from `popup.js`
```javascript
const motivationalSayings = [
    'https://pics.me.me/programmers-while-coding-ndianfunnypcture-com-indtan-m-indian-oindianfunnypicture-com-i-dont-35571594.png',
    'https://2.bp.blogspot.com/-IpWBrLhAB6w/XMaWK4Z5KDI/AAAAAAAAAJA/10joEkrrAYYUdQhVOeqTrIyElNkhccA7ACLcBGAs/s1600/IMG_20190427_201318_572.jpg',
    'https://i.pinimg.com/originals/de/f5/2f/def52fe41d695d8feebd2cdc194da929.png',
    'https://i.chzbgr.com/original/6349573/hB0DE8033/funny-programming-memes',
    'https://what.thedailywtf.com/assets/uplo'
];
```

##
## License

License
This project is licensed under the MIT License. You are free to use, modify, and distribute the code as you see fit.

---

For any further questions or feedback, feel free to contribute to the project or contact the repository owner. Happy coding!