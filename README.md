# bmi
# BMI Tracker App 📊

A multi-language Flutter application for calculating and tracking BMI metrics with Firebase integration.

## Screens
![BMI_login](https://github.com/user-attachments/assets/e5ee07ca-e864-4566-9546-60868c92b180)
![BMI_Register](https://github.com/user-attachments/assets/6feb40b8-fe07-45b9-9fc2-c95d591e0305)
![BMI_home-1](https://github.com/user-attachments/assets/c59e08d0-1a8a-48d4-a2f7-3ec3a79d764d)
![BMI_home-2](https://github.com/user-attachments/assets/e72b9511-910b-40f2-9403-762bfb3c9082)
![BMI_Profile](https://github.com/user-attachments/assets/2506d13e-9f16-4da0-a453-8f515003d1f7)
![BMI_History](https://github.com/user-attachments/assets/611c6df8-c24a-4230-a7c6-4f62aa0cf69d)

## BMI Diagramme de sequence
![BMI Diagramme de sequence](https://github.com/user-attachments/assets/cd9f25bc-0f39-44ef-bcc9-39657ef81881)

## Features ✨
- **BMI Calculation**: Instant BMI computation using weight/height inputs
- **Multi-language Support**: English/French/Arabic localization
- **Firebase Integration**:
    - User authentication (Login/Register)
    - Cloud Firestore for BMI history storage
- **History Tracking**: View previous BMI measurements with timestamps
- **User Profile**: Email display and quick access to history
- **Responsive UI**: Adaptive layout for various screen sizes

## Prerequisites 📋
- **Dart SDK** (>=2.19.6)
- **Flutter Framework** (>=3.7.0)
- **Android Studio** (or VS Code with Flutter extension)
- **Git Version Control**
- **Firebase Account** (for backend services)

## Installation 🛠️

### Firebase Setup
1. Create Firebase project at [console.firebase.google.com](https://console.firebase.google.com/)
2. Enable Authentication (Email/Password) and Firestore Database
3. Add Android/iOS apps and download `google-services.json`/`GoogleService-Info.plist`
4. Place config files in respective platform folders

### Local Setup

#git clone https://github.com/your-username/bmi_tracker_app.git
#cd bmi_tracker_app
#flutter pub get
#flutter run

## Usage 🚀
1-Registration: Create new account via Register screen
2-BMI Calculation:
**Enter weight (kg) and height (cm)**
**Tap "Calculate" to get BMI result**
3-History Tracking:
**View previous calculations with dates**
**BMI categories indicated by color coding**
4-Language Switching:
**Use dropdown to select preferred language**

## Development Commands 💻
# Run in debug mode
flutter run

# Generate localization files
flutter gen-l10n

# Run tests
flutter test

# Build APK
flutter build apk --release