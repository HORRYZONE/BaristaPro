<h1 align="center">
   BaristaPro
</h1>
<br>
<p align="center">
  <img src="path/to/your/logo.png" alt="BaristaPro Logo" width="200"/>
</p>
<p align="center">
  <img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" alt="DIVIDER GIF" />
</p>

<br>

## 👋 Hello, BaristaPro!<br>
Welcome to the BaristaPro Project GitHub! We are excited to share our application designed for coffee lovers and professionals alike.

<hr>

## Description

BaristaPro is a cutting-edge application that provides users with a comprehensive toolset to explore coffee recipes, track brewing techniques, and enhance their coffee-making skills. 

## App Functionality

- **Recipe Database**: Access a vast collection of coffee recipes from around the world.
- **Brew Timer**: Utilize a built-in timer for various brewing methods to ensure perfect extraction.
- **Personalized Coffee Journal**: Keep track of your favorite recipes, brewing methods, and tasting notes.
- **Community Sharing**: Share your favorite recipes and brewing tips with other users.
- **Tutorials and Guides**: Learn from expert baristas through video tutorials and step-by-step guides.

Feel free to contribute to BaristaPro and help us make it even better!

## 2.Requirement Analysis

### i. Data Storage for CRUD Operations:
The app will utilize **Firebase Real-Time Database** for storing user profiles, training modules, booking information, and community forum posts. Firebase ensures real-time synchronization, allowing users to always see the latest data.

#### CRUD Operations:
- **Create**: Users can create profiles, submit training modules, book sessions, and post in the forum.
- **Read**: Users can view available training modules, expert profiles, community discussions, and their booking history.
- **Update**: Users can update their profiles, modify bookings, and edit forum contributions.
- **Delete**: Users can delete their profiles, cancel bookings, or remove forum posts.

#### Data Structure:
- **Users Collection**: Stores user profiles and their data.
- **Trainers Collection**: Stores information about trainers.
- **Training Modules Collection**: Stores available training content.
- **Bookings Collection**: Stores booking details and history.
- **Forum Collection**: Stores forum threads and discussions.

The data structure is designed to optimize for efficient data retrieval and management.

### ii. Packages and Plugins:

#### Essential Flutter Packages:
- **firebase_core**: Initializes Firebase within the app.
- **firebase_auth**: Manages user authentication for secure login and signup processes.
- **cloud_firestore**: Facilitates CRUD operations with Firestore.
- **provider**: Implements state management for a reactive UI.
- **intl**: For formatting dates and times, particularly useful for scheduling.
- **flutter_calendar**: Provides a visual interface for booking and scheduling sessions.
- **flutter_slidable**: Enables swipeable list items for booking and forum interactions.
- **google_fonts**: Provides custom typography to enhance the app's visual aesthetics.
- **flutter/material.dart**: For building responsive layouts and utilizing Material widgets like buttons, cards, and dialogs.

#### Integration Assessment:
Evaluate the performance of these packages to ensure the app remains responsive and efficient, especially on lower-end Android devices.

#### Back-End Framework:
- Firebase serves as the back-end solution, handling authentication, data storage, and real-time synchronization.
- Flutter is used for front-end development, building a responsive UI optimized for Android devices.

---

## ii. Compatibility with Chosen Platform

### a. Android Compatibility:
- The app will be optimized for Android devices, ensuring it works across various screen sizes and resolutions.
- **Material Design** principles will be followed to create a visually appealing and intuitive user interface.

### b. Platform-Specific Features:
- **Push Notifications**: Implement **Firebase Cloud Messaging (FCM)** to notify users about upcoming training sessions, new forum posts, or messages from trainers.
- **Location Services**: Use Flutter's **location** package to help users find nearby coffee shops offering workshops or freelance opportunities.
- **Google Maps Integration**: Display nearby locations with **google_maps_flutter** to enhance the user experience.

### c. Testing:
- Conduct extensive testing across a range of Android devices to identify and resolve any compatibility issues.
- Ensure the app's performance remains optimal on lower-end devices through Firebase Performance Monitoring.

## iii. Sequence Diagram & Screen Navigational Flow

