Help Assistance App
This is an Android application built using **Java**, **Firebase Cloud Firestore**, and **Firebase Authentication**. The app allows users to sign in using their **Google Account** and stores/retrieves data securely from **Cloud Firestore**.

🚀 Features
- 🔐 Google Sign-In Authentication 
- ☁️ Cloud Firestore Database Integration 
- 📱 Clean Android UI (Jetpack / XML based)
- 📤 Add, update, read, and delete data from Firestore  
- 🔄 Real-time data updates  
- 📂 Organized project structure for easy maintenance

🛠️ Tech Stack

| Technology | Used For |
|-----------|----------|
| **Java** | Android development |
| **Firebase Authentication** | Google Login |
| **Cloud Firestore** | Storing user data |
| **Android Studio** | Development environment |
| **Gradle (KTS)** | Build system |

📦 Project Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/your-repo-name.git
Open in Android Studio

2️⃣ Open in Android Studio
Select Open an Existing Project
Choose this project folder

3️⃣ Add Your Firebase Files
Add the file:
app/google-services.json
from your Firebase console.

4️⃣ Enable Firebase Services
In Firebase Console:
Enable Authentication → Google Sign-In
Enable Firestore Database

🔑 How Login Works

The app uses FirebaseAuth with Google Sign-In.

When a user signs in, Firebase returns their:
Name
Email

User details get stored in Firestore.

📚 Firestore Structure Example
users/
   userId/
      name: "John Doe"
      email: "john@gmail.com"
      created_at: 2025-11-25

▶️ Running the App

Connect Android device / emulator

Click Run ▶ in Android Studio
