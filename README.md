<div align="center">
  <br />
    <img src="assets/readme/hero.png" alt="Project Banner">
  <br />

  <div>
    <img src="https://img.shields.io/badge/-React_Native-black?style=for-the-badge&logoColor=white&logo=react&color=61DAFB" alt="React Native" />
    <img src="https://img.shields.io/badge/-Expo-black?style=for-the-badge&logoColor=white&logo=expo&color=000020" alt="Expo" />
    <img src="https://img.shields.io/badge/-Appwrite-black?style=for-the-badge&logoColor=white&logo=appwrite&color=F02E65" alt="Appwrite" />
    <img src="https://img.shields.io/badge/-Tailwind-black?style=for-the-badge&logoColor=white&logo=tailwindcss&color=06B6D4" alt="Tailwind" />
    <img src="https://img.shields.io/badge/-TypeScript-black?style=for-the-badge&logoColor=white&logo=typescript&color=3178C6" alt="TypeScript" />
  </div>

  <h3 align="center">Food Delivery Mobile App</h3>
</div>

## 📋 Table of Contents

- [About the Project](#about-the-project)
- [Tech Stack](#tech-stack)
- [Features](#features)
- [Installation & Setup](#installation--setup)
- [Running the Project](#running-the-project)

## About the Project

Built with React Native, TypeScript, and Tailwind CSS, this full-stack Food Delivery app features Google Authentication, dynamic search and filters, cart functionality, and smooth navigation. Powered by Appwrite for backend, database, and file storage, it delivers a responsive, scalable, and intuitive user experience with modern UI/UX best practices.

## Tech Stack

- **[Appwrite](https://appwrite.io/)**: Open-source backend-as-a-service for authentication, databases, storage, and more.
- **[Expo](https://expo.dev/)**: Open-source platform for building universal native apps with React Native.
- **[React Native](https://reactnative.dev/)**: JavaScript framework for building native mobile apps.
- **[Tailwind CSS (NativeWind)](https://www.nativewind.dev/)**: Utility-first CSS framework for React Native.
- **[TypeScript](https://www.typescriptlang.org/)**: Statically-typed superset of JavaScript for robust code.
- **[Zustand](https://github.com/pmndrs/zustand)**: Minimal, hook-based state management for React.
- **[Sentry](https://sentry.io/)**: Error tracking and performance monitoring.

## Features

- **Google Authentication**: Secure user sign-in.
- **Home Page**: Displays offers and directs to filtered results.
- **Search & Filters**: Explore food with category filters and keyword search.
- **Product Details**: View item details and add to cart.
- **Cart Functionality**: Review items and see the total price.
- **User Profile**: Manage user settings.
- **Appwrite Backend**: Handles database and file storage.

## Installation & Setup

**1. Prerequisites**

- [Node.js](https://nodejs.org/) (v18.x or later)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)
- [Expo Go](https://expo.dev/go) app on your mobile device

**2. Clone the Repository**

```bash
git clone https://github.com/your-username/food-delivery-app.git
cd food-delivery-app
```

**3. Install Dependencies**

```bash
npm install
# or
yarn install
```

**4. Set Up Environment Variables**

Create a `.env` file in the root directory and add your Appwrite credentials:

```
EXPO_PUBLIC_APPWRITE_PROJECT_ID=
EXPO_PUBLIC_APPWRITE_DATABASE_ID=
EXPO_PUBLIC_APPWRITE_STORAGE_ID=
EXPO_PUBLIC_APPWRITE_USERS_COLLECTION_ID=
EXPO_PUBLIC_APPWRITE_RESTAURANTS_COLLECTION_ID=
EXPO_PUBLIC_APPWRITE_CATEGORIES_COLLECTION_ID=
EXPO_PUBLIC_APPWRITE_PRODUCTS_COLLECTION_ID=
EXPO_PUBLIC_APPWRITE_BANNERS_COLLECTION_ID=
EXPO_PUBLIC_APPWRITE_ORDERS_COLLECTION_ID=
EXPO_PUBLIC_APPWRITE_ENDPOINT=
```

Sign up on the [Appwrite](https://appwrite.io/) dashboard to get these values.

## Running the Project

```bash
npm start
# or
yarn start
```

Scan the QR code generated in the terminal with the Expo Go app to run the application.
