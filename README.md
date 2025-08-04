# next-e-commerce

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
![JavaScript](https://img.shields.io/badge/language-JavaScript-F7DF1E.svg?style=flat&logo=javascript&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-black?style=flat&logo=next.js&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat&logo=firebase&logoColor=black)

## Description

`next-e-commerce` is a modern, responsive e-commerce website example built with Next.js and powered by Firebase. This project was developed as a personal 1-week self-challenge to demonstrate a full-stack e-commerce application, focusing on rapid development and integration of popular web technologies. It showcases how to leverage Next.js for a performant frontend and Firebase for a robust, scalable backend, covering essential e-commerce functionalities from product display to user authentication.

## Features

*   **Product Catalog:** Browse a comprehensive list of products with detailed information.
*   **Product Details Page:** View individual product details, images, and descriptions.
*   **Shopping Cart Management:** Add, remove, and update quantities of items in your cart.
*   **User Authentication:** Secure user registration, login, and logout functionalities using Firebase Authentication.
*   **Firebase Backend:** Utilizes Firebase Firestore for database operations and data storage.
*   **Responsive Design:** Optimized for various screen sizes, from mobile to desktop.
*   **Client-Side Routing:** Seamless page transitions powered by Next.js.
*   **Form Validation:** Robust form handling and validation using React Hook Form and Yup.

## Tech Stack

This project is built using a powerful combination of modern web technologies:

*   **Frontend Framework:** [Next.js](https://nextjs.org/) (v9.5.3)
*   **UI Library:** [React](https://reactjs.org/) (v16.13.1)
*   **Backend-as-a-Service (BaaS):** [Firebase](https://firebase.google.com/) (v7.23.0)
    *   Firestore for database
    *   Authentication for user management
*   **Styling:** [Sass](https://sass-lang.com/) (v1.26.12)
*   **Form Management:** [React Hook Form](https://react-hook-form.com/) (v6.9.2)
*   **Schema Validation:** [Yup](https://github.com/jquense/yup) (v0.29.3)
*   **Date Utilities:** [date-fns](https://date-fns.org/) (v2.16.1)
*   **JavaScript**

## Installation

To get a local copy up and running, follow these simple steps.

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/your-username/next-e-commerce.git
    ```
    (Replace `your-username` with the actual GitHub username if this project is hosted elsewhere, or remove if it's a template.)

2.  **Navigate into the project directory:**
    ```bash
    cd next-e-commerce
    ```

3.  **Install dependencies:**
    This project uses `npm` for package management.
    ```bash
    npm install
    # or if you prefer yarn
    # yarn install
    ```

4.  **Firebase Configuration:**
    This project relies on Firebase for its backend. You will need to set up your own Firebase project and configure the credentials.
    *   Go to the [Firebase Console](https://console.firebase.google.com/).
    *   Create a new project.
    *   Add a web app to your project.
    *   Copy your Firebase configuration object.
    *   Create a `.env.local` file in the root of your project and add your Firebase credentials:

    ```
    NEXT_PUBLIC_FIREBASE_API_KEY=YOUR_API_KEY
    NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=YOUR_AUTH_DOMAIN
    NEXT_PUBLIC_FIREBASE_PROJECT_ID=YOUR_PROJECT_ID
    NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET=YOUR_STORAGE_BUCKET
    NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID=YOUR_MESSAGING_SENDER_ID
    NEXT_PUBLIC_FIREBASE_APP_ID=YOUR_APP_ID
    NEXT_PUBLIC_FIREBASE_MEASUREMENT_ID=YOUR_MEASUREMENT_ID
    ```
    Ensure you enable Firebase Authentication (Email/Password provider) and Firestore Database in your Firebase project.

## Usage

Once the dependencies are installed and Firebase is configured, you can run the application:

1.  **Run in development mode:**
    ```bash
    npm run dev
    # or
    # yarn dev
    ```
    This will start the development server at `http://localhost:3000`. The app will automatically reload if you change any of the source files.

2.  **Build for production:**
    ```bash
    npm run build
    # or
    # yarn build
    ```
    This command creates an optimized production build of your application.

3.  **Start production server:**
    ```bash
    npm run start
    # or
    # yarn start
    ```
    This command starts a Next.js production server. Make sure you have run `npm run build` first.

## Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".

1.  Fork the Project
2.  Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3.  Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4.  Push to the Branch (`git push origin feature/AmazingFeature`)
5.  Open a Pull Request

## License

This project is licensed under the **GNU General Public License v3.0**. See the `LICENSE` file for more details.
