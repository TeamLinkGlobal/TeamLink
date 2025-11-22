📱 Mobile –** TeamLink**

This is the mobile app for *TeamLink*, built using *React Native* (via Expo). It connects to the backend API to provide a mobile experience for users on Android and iOS.

---

📁 Project Structure


/mobile-app
├── assets/
├── components/
├── screens/
├── App.js
├── app.json
└── .env


---

🚀 Getting Started

1. Clone the Repo

bash
git clone https://github.com/your-org/project-name.git
cd project-name/mobile-app


2. Install Dependencies

bash
npm install


3. Set Up Environment Variables

Create a `.env` file:


API_BASE_URL=http://your-backend-api/api


(Optional: Use `react-native-dotenv` to load variables.)

4. Start the App

If using Expo:

bash
npx expo start


Scan the QR code with your Expo Go app to preview on your device.

---

🧰 Tech Stack

- React Native (Expo)
- Axios for API requests
- React Navigation
- Tailwind via NativeWind (if used)

---

🔗 API Integration

The app connects to the Django backend via REST API.

Example:

js
axios.get(${process.env.API_BASE_URL}/posts)
```

---

🤝 Contributing

- Use feature branches and PRs to the mobile branch
