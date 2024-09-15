# Real-Time AI Gesture Recognition with TensorFlow.js + React.js + Fingerpose


## Overview

This is a **real-time AI-powered gesture recognition** application built using **React.js**, **TensorFlow.js**, and **Fingerpose**. The application uses a webcam to detect hand gestures such as the 'Victory' and 'Thumbs Up' gestures. The detected gestures are then visually represented by emojis.

- **Technologies**: TensorFlow.js, Handpose Model, React.js, Fingerpose
- **Features**:
  - Real-time hand gesture detection using a webcam
  - Gesture recognition and emoji display
  - Easy integration and customization
  
## Features

- **Handpose Integration**: This project integrates the Handpose model from TensorFlow.js to detect hand landmarks in real-time.
- **Gesture Recognition**: Recognizes two gestures out-of-the-box: 'Victory' and 'Thumbs Up' using the Fingerpose library.
- **Emoji Display**: Displays the corresponding emoji when a recognized gesture is detected.
- **Seamless UI/UX**: Simple yet visually appealing UI built with React.js and styled using Bootstrap.

## Demo

You can access the **live demo** of this application [here](https://drive.google.com/file/d/1twlprmVeYGwJDdAGD68wa91WgWFsptPV/view?usp=share_link).

## Screenshots

Here are some screenshots of the app in action:

<img width="1728" alt="Screenshot 2024-09-15 at 13 15 39" src="https://github.com/user-attachments/assets/57701ca4-123a-4442-9630-6dea6052d9f2"> <br> <br>


<img width="1728" alt="CV05" src="https://github.com/user-attachments/assets/081c2dce-e2b6-4802-b2ff-d0df53ca0502">


## Project Structure

```
.
├── public/
│   ├── favicon.ico
│   ├── index.html
│   ├── manifest.json
│   └── robots.txt
├── src/
│   ├── App.css
│   ├── App.js
│   ├── index.css
│   ├── index.js
│   ├── utilities.js
│   ├── thumbs_up.png
│   └── victory.png
├── package.json
└── README.md
```

## Installation and Setup

To get started with this project, follow the instructions below:

### Prerequisites

Make sure you have the following installed on your system:
- Node.js
- npm or Yarn

### Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/Pahinithi/Real-Time-Gesture-Recognition-with-Computer-Vision
   ```

2. **Navigate to the project directory**:

   ```bash
   cd Real-Time-AI-Gesture-Recognition
   ```

3. **Install the dependencies**:

   ```bash
   npm install
   ```

   or

   ```bash
   yarn install
   ```

### Running the Application

To start the development server, use the following command:

```bash
npm start
```

This will launch the app on `http://localhost:3000` in your browser.

### Deployment

For deployment, you can build the optimized production version:

```bash
npm run build
```

The output will be generated in the `build/` folder.

## Usage

1. Once the application is running, it will automatically detect the hand when in view of the webcam.
2. Recognized gestures ('Victory' or 'Thumbs Up') will trigger an emoji to appear over the video feed.

## File Descriptions

- **App.js**: Main React component handling the webcam feed, hand detection, and emoji display.
- **utilities.js**: Contains the `drawHand` function to draw the hand landmarks on the canvas.
- **index.html**: HTML template for the application.
- **App.css**: Styling for the application.
  
## Customizing the Application

To add new gestures:
1. Use the **Fingerpose** library to create and estimate new gestures. You can refer to the [Fingerpose documentation](https://github.com/andypotato/fingerpose) for more information.
2. Update the **gesture handling section** in `App.js` to include the new gestures and their corresponding images.

## Future Enhancements

- Add more gestures for recognition.
- Improve gesture accuracy and performance.
- Implement additional AI-based interactions for enhanced user experience.

## Technologies Used

- **React.js**: Frontend framework for building the user interface.
- **TensorFlow.js**: Library for real-time hand pose estimation.
- **Fingerpose**: Gesture recognition library.
- **Webcam.js**: Webcam integration for capturing video.
- **Bootstrap**: For styling the UI components.

## License

This project is licensed under the MIT License. 

## Contact

For any questions or support, please contact:

- **Name**: Pahirathan Nithilan
- **Email**: [nithilan32@gmail.com](mailto:nithilan32@gmail.com)
- **GitHub**: [Pahinithi](https://github.com/Pahinithi)
