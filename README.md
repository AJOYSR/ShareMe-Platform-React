# ShareMe-Platform-React
ShareMe is a photo and pin sharing app built with React, TailwindCSS, Material-UI, and Sanity. It allows users to upload, download, comment, and save photos and pins, and features user authentication, user profiles, and a search bar.

# ShareMe
ShareMe is a photo and pin sharing app that allows users to upload, download, comment, and save photos and pins. It also includes features like user authentication, user profiles, and a search bar.

# Features of ShareMe
Google Sign-In and Verification
To sign in with Google, click the "Sign in with Google" button on the login page. You will be prompted to enter your Google credentials. Once you have successfully signed in, you will be redirected to the home page.

## Home Page
The home page displays a list of pins and photos that have been uploaded by users. You can click on a pin or photo to view it in more detail. You can also search for pins and photos using the search bar.

##  Pin and Photo Detail Page
The pin and photo detail page displays the selected pin or photo in more detail. You can download the image, leave a comment, or save the pin or photo for later. You can also view the user's profile by clicking on their name.

## Profile Page
The profile page displays the user's profile information, including their name, profile picture, and a list of their uploaded pins and photos. You can click on a pin or photo to view it in more detail.

## reate Pin Page
The create pin page allows users to create a new pin. Users can upload an image and enter a description for the pin.

## Commenting and Saving Pins and Photos
Users can leave comments on pins and photos. They can also save pins and photos for later by clicking on the "Save" button.

## Search Bar
The search bar allows users to search for pins and photos based on keywords.

## Technologies Used
ShareMe is built using the following technologies:

* React
* TailwindCss (desinging)
* Material-UI
* Sanity (for backend)

## Conclusion
ShareMe is a simple photo and pin sharing app with basic features. Users can upload and view photos and pins, create new pins, and interact with other users through comments and saves. The app also features user authentication using Firebase, user profiles using Material-UI, and image hosting using Cloudinary.
## Screenshots

![App Screenshot](https://i.ibb.co/cgtn4B4/shareme.png)


# Clone the project

```javascript
git@github.com:AJOYSR/ShareMe-Platform-React.git
```


## Prerequisites
Before starting with the application, the following technologies need to be installed on your system:

* Node.js (v14 or above)


## Installation

1. Clone the repository:

    ```bash
   git@github.com:AJOYSR/ShareMe-Platform-React.git
    ```

2. Navigate to the project directory:

    ```bash
    cd shareme-platform-react
    ```

3. Install dependencies:

    ```bash
    npm install
    ```

4. Create a `.env` file in the root directory with the following contents:

    ```bash
    SANITY_STUDIO_PROJECT_URL=<your-sanity-project-url>
    SANITY_STUDIO_PREVIEW_SECRET=<your-sanity-preview-secret>
    ```

5. Start the Sanity Studio server:

    ```bash
    npm run start:sanity
    ```

6. In a new terminal window, start the Vite development server:

    ```bash
    npm run start:app
    ```

7. Navigate to `http://localhost:3000` in your web browser to view the app.

## Dependencies

This app uses the following dependencies:

- "@sanity/client": "^2.7.1"
- "@tailwindcss/forms": "^0.4.0"
- "@tailwindcss/typography": "^0.4.1"
- "firebase": "^9.4.1"
- "react": "^17.0.2"
- "react-dom": "^17.0.2"
- "react-router-dom": "^5.3.0"
- "vite": "^2.6.4"
## Installing Sanity CLI

To install Sanity CLI, follow these steps:

1. Install Node.js and npm on your computer.

2. Open a terminal or command prompt.

3. Run the following command to install the Sanity CLI globally:

    ```bash
    npm install -g @sanity/cli
    ```

4. Verify that the installation was successful by running the following command:

    ```bash
    sanity --version
    ```

    If you see the version number of Sanity CLI printed to the console, then the installation was successful.

## Running ShareMe-Platform-React with Sanity and Vite

To run the ShareMe-Platform-React app with Sanity and Vite, follow these steps:

1. Clone the repository and navigate to the root directory of the project.

2. Install the project dependencies by running the following command:

    ```bash
    npm install
    ```

3. Start the Sanity Studio by running the following command:

    ```bash
    sanity start
    ```

    This will start the Sanity Studio at `http://localhost:3333`.

4. In a separate terminal, start the Vite development server by running the following command:

    ```bash
    npm run dev
    ```

    This will start the Vite development server at `http://localhost:3000`.

5. Open your web browser and navigate to `http://localhost:3000` to view the ShareMe-Platform-React app.

6. To sign in to the app using Google Sign-In, you'll need to create a Google API Key and enable the Google Sign-In API. Once you have done this, create a `.env` file in the root directory of the project and add the following line:

    ```bash
    REACT_APP_GOOGLE_API_KEY=<your Google API key>
    ```

    Replace `<your Google API key>` with your actual Google API Key.

7. You should now be able to sign in to the app using Google Sign-In and start using the photo and pin sharing features.

