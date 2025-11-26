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

<img width="1765" height="738" alt="Screenshot 2025-11-26 010337" src="https://github.com/user-attachments/assets/4cc0791a-566d-4a77-9f19-a2686053b82f" />

<img width="1918" height="871" alt="Screenshot 2025-11-26 161702" src="https://github.com/user-attachments/assets/073ed66c-c799-46ab-a813-9c70faa61b9e" />

<img width="1918" height="873" alt="Screenshot 2025-11-26 161722" src="https://github.com/user-attachments/assets/c0ce628f-bd89-43ce-bc67-ef34cae26c2c" />

<img width="1918" height="864" alt="Screenshot 2025-11-26 161747" src="https://github.com/user-attachments/assets/4b5e5924-3f9b-4327-a084-4f1ac31c5109" />

🧠 Future Improvements (Optional)

Integrate OpenAI API for real summaries

Deploy Django backend on Render/Heroku

Add voice input

Multi-location comparison logic

👤 Author

Yadneshwar Thorat



