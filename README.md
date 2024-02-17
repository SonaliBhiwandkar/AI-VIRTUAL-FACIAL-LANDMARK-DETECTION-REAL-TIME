# AI-VIRTUAL-FACIAL-LANDMARK-DETECTION-REAL-TIME

The AI Virtual Facial Landmark Detection Real Time application is a cutting-edge real-time facial landmark detection tool built using React.js and TensorFlow.js. It enables users to visualize their facial landmarks in real-time through their webcam feed, providing an interactive and intuitive experience.

With this application, users can explore and observe the precise locations of facial landmarks such as eyes, nose, mouth, and contours, as detected by state-of-the-art machine learning models. The application leverages the power of TensorFlow.js to seamlessly integrate advanced facial landmark detection capabilities into a user-friendly web interface.

**Key features** of the AI Virtual Facial Landmark Detection Real Time application include:

- **Real-time Detection:** View facial landmarks in real-time directly from your webcam feed.
- **Web-Based Interface:** Access the application easily through any web browser without the need for additional installations.
- **React.js Integration:** Built using React.js for a modular, efficient, and scalable front-end development experience.
- **TensorFlow.js Models:** Utilizes TensorFlow.js for loading and running state-of-the-art facial landmark detection models.
- **User-Friendly Experience:** Simple and intuitive interface makes it easy for users to interact with and understand the detected facial landmarks.

Whether you're curious about the capabilities of machine learning models or simply interested in exploring your own facial landmarks, the AI Virtual Facial Landmark Detection Real Time application offers a fascinating and educational experience.

## Technologies Used

- **React:** A JavaScript library for building user interfaces.
- **TensorFlow.js:** A JavaScript library for training and deploying machine learning models in the browser and on Node.js.
- **react-webcam:** A React component for accessing the device camera.
- **CSS:** Styling for the user interface components.

## Installation

To run the application locally, follow these steps:

1. Clone the repository to your local machine:

    ```bash
    git clone https://github.com/SonaliBhiwandkar/AI-VIRTUAL-FACIAL-LANDMARK-DETECTION-REAL-TIME.git
    ```

2. Navigate to the project directory:

    ```bash
    cd AI-VIRTUAL-FACIAL-LANDMARK-DETECTION-REAL-TIME
    ```

3. Install dependencies using npm or yarn:

    ```bash
    npm install
    # or
    yarn install
    ```

4. Start the development server:

    ```bash
    npm start
    # or
    yarn start
    ```

5. Open your web browser and go to `http://localhost:3000` to view the application.

## Usage

Once the application is running, grant access to your webcam when prompted. You should see your webcam feed with facial landmarks overlaid in real-time.

## Code Overview

### `App.js`

The main component of the application, `App.js`, handles the setup of the webcam feed, loading of the facemesh detection model, and real-time detection of facial landmarks.

The code in `App.js` utilizes React hooks such as `useRef` and `useEffect` for managing references and side effects respectively. It also leverages TensorFlow.js for loading and running the facemesh detection model.

### `utilities.js`

This file contains utility functions, including the `drawMesh` function used to draw facial landmarks on the canvas.

## Versions

### Version 1.0 (Old Model)

The initial version of the application utilized an older version of the facemesh detection model provided by TensorFlow.js.

### Version 2.0 (New Model)

The updated version of the application now utilizes the latest face landmarks detection model from TensorFlow.js, offering improved accuracy and performance.

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT). See the [LICENSE](LICENSE) file for details.

## Contact

For any inquiries or feedback, please contact Sonali Bhiwandkar at sonali.bhiwandkar@gmail.com.
