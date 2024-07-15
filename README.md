
# 🚀 React + Vite Firebase Hosting Template

Welcome to the React + Vite Firebase Hosting Template! This project is designed to get you up and running with a blazing fast React application using Vite and Firebase for seamless deployment. Enjoy a smooth development experience with instant hot-reloads, optimized builds, and easy deployment to Firebase Hosting.

## ✨ Features

- **Vite**: Super fast build tool that leverages native ES modules for instant hot module replacement and fast production builds.
- **React**: A JavaScript library for building user interfaces, developed by Facebook.
- **Firebase Hosting**: Production-grade web content hosting for developers, offering fast and secure hosting with a global CDN.

## 📦 Getting Started

### Prerequisites

Make sure you have the following installed:

- [Node.js](https://nodejs.org/) (version 14 or later)
- [Firebase CLI](https://firebase.google.com/docs/cli)

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/react-vite-firebase-template.git
    cd react-vite-firebase-template
    ```

2. Install dependencies:
    ```sh
    npm install
    ```

3. Start the development server:
    ```sh
    npm run dev
    ```

Your app should now be running on [http://localhost:3000](http://localhost:3000).

## 🚀 Deployment to Firebase Hosting

Deploying your app to Firebase Hosting is a breeze. Follow these simple steps:

1. **Login to Firebase**:
    ```sh
    firebase login
    ```

2. **Initialize Firebase in your project**:
    ```sh
    firebase init
    ```

    - Select `Hosting` from the list.
    - Choose an existing project or create a new one.
    - Set the public directory to `dist`.
    - Configure as a single-page app (yes).

3. **Build the project**:
    ```sh
    npm run build
    ```

4. **Deploy to Firebase**:
    ```sh
    firebase deploy
    ```

And that's it! Your app is now live on Firebase Hosting.

## 🌐 Viewing Your Live Project

After deployment, you can view your live project by visiting the URL provided by Firebase Hosting. It will look something like this:

[react-ssr-example.web.app](https://react-ssr-example.web.app/)
