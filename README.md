🏡 Real Estate Analysis Chatbot

🚀 Full Stack Developer Assignment – SigmaValue (2025)

👉 Live Demo:
🔗 https://realestate-chat-frontend.vercel.app/

A fully interactive Real Estate Chatbot built using React (frontend) and Django (backend). It analyzes real estate data (Excel-based), provides insights, visual trends, and allows users to download filtered data.

📌 Assignment Objective

Build a web-based chatbot that:
✔ Accepts real estate-based queries
✔ Filters & analyzes data from an Excel file
✔ Returns:

📊 Natural language analysis

📈 Demand trend charts

📋 Filtered data table
✔ Supports bonus features like Data Download & Chat UI

🏗 Tech Stack
Layer	Technology
Frontend	React (Vite) + Bootstrap + Recharts
Backend	Django + Python
Database	Excel-based dataset
Deployment	Vercel (Frontend), Local backend
Other	Axios, XLSX, File-Saver
✨ Features
🔍 Chatbot Features

Natural language response (Mock LLM)

Supports queries like:

“Give me analysis of Wakad”

“Compare Ambegaon Budruk and Aundh demand trends”

“Show price growth for Akurdi in last 3 years”

Fully conversational UI 

📈 Analytics

✔ Demand trend line chart
✔ Summary insights with market recommendations
✔ Filtered data with search capability
✔ Excel download button

🎨 Modern UI Features

Animated gradient background

Glassmorphism chat card

Typing bubble animation

Mobile responsive UI

“Ask another query” button

"Search while in Table"

"Download the Specific Queries Content"

📂 Folder Structure
real_estate_chatbot/
│── backend/
│   ├── realestate/
│   ├── api/
│   │   ├── views.py
│   │   ├── urls.py
│   │   ├── analysis.py
│   ├── manage.py
│   ├── Sample_data.xlsx
│
│── frontend/
│   ├── src/
│   │   ├── Chat.jsx
│   │   ├── ChartDisplay.jsx
│   │   ├── TableDisplay.jsx
│   │   ├── App.css
│   │   ├── main.jsx
│   ├── index.html
│   ├── package.json
│
└── README.md

🚀 Setup Instructions
📦 Backend (Django)
cd backend
python -m venv venv
venv\Scripts\activate   
pip install django pandas openpyxl
python manage.py runserver


📌 Make sure Sample_data.xlsx is inside the backend folder.

🎨 Frontend (React)
cd frontend
npm install
npm run dev

🔗 API Endpoint
Method	Endpoint	Description
POST	/api/analyze/	Analyzes the user query

Request body:

{
  "query": "Give me analysis of Wakad"
}

📸 Screenshots

<img width="1919" height="863" alt="Screenshot 2025-11-26 162517" src="https://github.com/user-attachments/assets/495583ad-6119-4e0c-b038-512d82cd2343" />

<img width="1896" height="870" alt="Screenshot 2025-11-26 162545" src="https://github.com/user-attachments/assets/c662f5da-53dc-4826-ac53-37bea8dd4614" />

<img width="1899" height="870" alt="Screenshot 2025-11-26 162610" src="https://github.com/user-attachments/assets/681094e0-ec50-416d-8334-4d0867487a9d" />

<img width="1905" height="871" alt="Screenshot 2025-11-26 162640" src="https://github.com/user-attachments/assets/0b009394-b6c8-45fb-be5e-91c62cc4c01d" />

<img width="1897" height="834" alt="Screenshot 2025-11-26 162722" src="https://github.com/user-attachments/assets/d9afe175-3f47-4006-a889-c39ab02d6d50" />

🧠 Future Improvements (Optional)

Integrate OpenAI API for real summaries

Deploy Django backend on Render/Heroku

Add voice input

Multi-location comparison logic

👤 Author

Yadneshwar Thorat



