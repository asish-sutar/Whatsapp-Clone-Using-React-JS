# WhatsApp Clone

## Project Overview

This project is a WhatsApp clone developed using React and Firebase. It aims to replicate some of the key features of the popular messaging application WhatsApp. The clone includes functionalities such as real-time messaging, user authentication, and the ability to send messages and images.

## Technologies Used

- **React**: The project is built using the React library, allowing for the creation of a dynamic and interactive user interface.

- **Firebase**: Firebase is utilized for both authentication and real-time data storage. The project makes use of Firebase Authentication for user sign-in, and Firebase Firestore for storing and retrieving chat messages.

- **Material-UI**: Material-UI components are employed for the design and layout of the user interface, providing a clean and responsive user experience.

## Features

1. **Authentication**: Users can sign in using their Google accounts, ensuring a secure and personalized experience.

2. **Real-time Messaging**: The application supports real-time messaging, allowing users to send and receive messages instantly.

3. **Image Upload**: Users can upload images in addition to text messages, enhancing the communication experience.

4. **Contact List and Chats**: The sidebar displays a list of users, and clicking on a user opens a chat window for communication.

5. **Responsive Design**: The application is designed to be responsive, ensuring a seamless experience across different devices and screen sizes.

## Project Structure

- **`Chat.js`**: Component handling the chat functionality, including sending and receiving messages.

- **`Main.js`**: Main component displaying the application's landing page and information.

- **`Navbar.js`**: Navigation bar component containing user information and logout functionality.

- **`PhoneSignin.js`**: Component for phone number-based authentication, allowing users to receive and verify OTP.

- **`Sidebar.js`**: Sidebar component displaying the list of users for initiating new chats.

- **`Signin.js`**: Component for Google account-based authentication, providing an overview of the application and sign-in options.

- **`firebase/setup.js`**: Firebase configuration and initialization file.

## How to Run the Project

1. Clone the repository: `git clone <repository-url>`
2. Install dependencies: `npm install`
3. Set up Firebase: Replace the Firebase configuration in `firebase/setup.js` with your own credentials.
4. Run the application: `npm start`
