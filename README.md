# bmi
# BMI Tracker App 📊

A multi-language Flutter application for calculating and tracking BMI metrics with Firebase integration.

## Screens
![BMI_login](![BMI_login](https://github.com/user-attachments/assets/62948e7f-1abb-4f74-bb44-01852f0319b1))
![BMI_Register](![BMI_Register](https://github.com/user-attachments/assets/5d1998f9-c8f7-4ada-9818-26452624a2f7)
)
![BMI_home-1](![BMI_home-1](https://github.com/user-attachments/assets/fd4e8b93-cebb-41f7-9782-fec0b5874fb1)
)
![BMI_home-2](![BMI_home-2](https://github.com/user-attachments/assets/a8173d2a-d433-43e0-b4c4-fcdfd8bd069d)
)
![BMI_Profile](![BMI_Profile](https://github.com/user-attachments/assets/871e5f9b-796e-4cbe-a900-d6bea0919f7a)
)
![BMI_History](![BMI_History](https://github.com/user-attachments/assets/704335aa-a08b-4bfd-acf9-b9882923a1d7)
)

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
