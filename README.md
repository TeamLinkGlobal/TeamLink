🌐 Frontend – TeamLink

This is the frontend interface for **TeamLink**, built with *React* and *Tailwind CSS*. It communicates with the backend via API to deliver a seamless user experience.

---

📁 Project Structure


/web-app
├── public/
├── src/
│   ├── components/
│   ├── pages/
│   ├── services/      # API calls
│   └── App.jsx
├── tailwind.config.js
├── package.json
└── .env


---

🚀 Getting Started

1. Clone the Repo

bash
git clone https://github.com/your-org/project-name.git
cd project-name/web-app


2. Install Dependencies

bash
npm install


3. Set Up Environment Variables

Create a `.env` file:


VITE_API_BASE_URL=http://localhost:8000/api


(If using Vite. Use `REACT_APP_...` for Create React App.)

4. Run the App

bash
npm run dev   # or npm start if CRA


---

🧰 Tech Stack

- React  
- Tailwind CSS  
- Axios (for API calls)  
- Vite or Create React App

---

🔗 API Integration

The frontend connects to Django backend through RESTful APIs.  
Ensure the backend server is running on the correct port.

Example API call:

js
axios.get(${import.meta.env.VITE_API_BASE_URL}/posts)
```

---

🤝 Contributing
