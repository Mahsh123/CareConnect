# CareConnect Frontend

## 📋 Overview
The **CareConnect Frontend** is a mobile application built with **React Native** to streamline communication between nurses and patients. It enables nurses to receive real-time updates on patient requests, with details such as room numbers, request content, and urgency levels. This enhances patient care by ensuring prompt responses to critical needs.

---

## ✨ Features
- 📱 **Real-Time Notifications**: Instantly notify nurses of patient requests.
- 🛖 **Request Prioritization**: Sort and display requests based on urgency.
- 🏥 **Room Details**: Show patient room numbers alongside requests.
- 🎨 **User-Friendly Interface**: Responsive design for a seamless user experience.

---

## 🛠️ Tech Stack
- **React Native**: Framework for building cross-platform mobile apps.
- **Redux/Context API**: For state management.
- **Firebase**: For notifications and real-time database.
- **Axios**: For API communication.
- **React Navigation**: For smooth screen navigation.

---

## 🛠️ Installation and Setup

### Prerequisites
- **Node.js** (>= 14.x)
- **npm** or **yarn**
- React Native CLI
- Android Studio (for Android emulator) / Xcode (for iOS emulator)

### Steps

1. **Clone the Repository**
   ```bash
   git clone https://github.com/Mahsh123/CareConnect-App.git
   cd CareConnect-App/frontend
   ```

2. **Install Dependencies**
   ```bash
   npm install
   ```

3. **Set Up Environment Variables**
   Create a `.env` file in the root directory and add:
   ```env
   API_URL=https://your-backend-api-url.com
   FIREBASE_API_KEY=your-firebase-api-key
   ```

4. **Run the Application**
   - For Android:
     ```bash
     npx react-native run-android
     ```
   - For iOS:
     ```bash
     npx react-native run-ios
     ```

---

## 📂 Folder Structure
```plaintext
frontend/
├── src/
│   ├── components/      # Reusable UI components
│   ├── screens/         # App screens
│   ├── services/        # API communication
│   ├── utils/           # Helper functions
│   └── styles/          # Shared styles
├── App.js               # Entry point of the app
├── package.json         # Project metadata and dependencies
├── .env                 # Environment variables
└── README.md            # Project documentation
```

---

## 📱 Key Libraries Used
- **React Native**: Cross-platform mobile app development.
- **Redux/Context API**: For global state management.
- **Axios**: API integration for backend communication.
- **Firebase**: Real-time database and notification services.
- **React Navigation**: Screen navigation.

---

## 🌟 Contributing
We welcome contributions! To contribute:
1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add new feature"
   ```
4. Push to your branch:
   ```bash
   git push origin feature-name
   ```
5. Submit a pull request.

---

## 🖍️ License
This project is licensed under the **MIT License**. See the `LICENSE` file for more details.

---

## 🛠️ Author
**Muhammed Mahshook Ali P**  
Feel free to connect on [LinkedIn](https://www.linkedin.com/in/your-linkedin-profile/)!
