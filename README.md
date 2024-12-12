# FurniAR

## Description

FurniAR is an innovative Android application that brings the power of Augmented Reality (AR) to furniture shopping and interior design. With FurniAR, users can visualize furniture items in their own space before making a purchase, enhancing the shopping experience and reducing uncertainty in buying decisions.

## Features

- **AR Furniture Visualization**: Place virtual 3D models of furniture in your real-world environment.
- **User Authentication**: Secure login and registration system using Firebase Auth.
- **Product Catalog**: Browse a wide range of furniture items stored in Firebase Firestore.
- **Real-time 3D Rendering**: High-quality, real-time rendering of furniture models using Google's SceneForm and Filament engine.
- **User Profiles**: Personalized user experiences with customizable profiles.
- **Image Gallery**: View high-quality images of furniture items using Glide for efficient image loading.
- **Persistent State**: Maintain app state across configuration changes for a seamless user experience.
- **Intuitive Navigation**: Smooth in-app navigation using the Navigation component.

[Uploading Screen_recording_20241212_232737.webm…]()

## Technologies Used

- **SceneForm**: ARCore Android SDK with Google Filament as the 3D engine for AR functionality.
- **Hilt**: Dependency injection for clean and modular code architecture.
- **Coroutines**: Efficient handling of asynchronous operations, particularly for Firebase requests.
- **MVVM & StateFlow**: Architecture pattern for separating logic from views and maintaining state.
- **Navigation Component**: Single-activity architecture with multiple fragments for efficient navigation.
- **Firebase**:
  - **Auth**: User account management and authentication.
  - **Firestore**: NoSQL database for storing application data.
  - **Storage**: Cloud storage for product images, 3D models, and user profile pictures.
- **View Binding**: Efficient view inflation and management.
- **Glide**: Fast and efficient image loading library.

FurniAR leverages these cutting-edge technologies to provide a smooth, responsive, and immersive AR furniture shopping experience on Android devices.
