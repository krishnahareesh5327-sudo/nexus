🤖 Nexus AI – Multi-Agent Chatbot for Smarter Requirement Gathering

📌 Overview

Requirement gathering is one of the most challenging and error-prone phases of software development. Miscommunication between stakeholders, analysts, and developers often leads to unclear goals and expensive rework.
Nexus AI is a single-page, multi-agent chatbot designed to make requirement engineering faster, clearer, and smarter. With built-in AI agents, Nexus AI guides users step by step, analyzes needs, evaluates feasibility, and generates a Software Requirements Specification (SRS) automatically.
Everything — UI, styling, logic, and database integration — is combined into a single HTML file for simplicity.


✨ Features

🗨️ Chatbot Interface – Talk to Nexus AI like you would to a requirements analyst.

🌗 Light/Dark Mode – Toggle-friendly, accessible design.


🤖 Multi-Agent Flow

Clarifier Agent → asks step-by-step questions.

Analyzer Agent → structures the captured requirements.

Feasibility Agent → checks risks and constraints.

SRS Generator Agent → outputs a professional SRS draft.

🔄 Real-Time Sync – Conversations saved in Firebase Firestore.

📂 History View – Resume past sessions anytime.

⬇️ Download Option – Export full conversation as .txt.

📝 Markdown Support – Requirements displayed with headings, lists, and highlights.


🛠️ Tech Stack

HTML (single merged file with inline CSS & JavaScript)

Tailwind CSS (via CDN, inside the HTML)

Firebase Firestore (for real-time history & session storage)

JavaScript (handles multi-agent workflow logic)

🚀 Getting Started

1️⃣ Clone the Repository

git clone https://github.com/krishnahareesh5327-sudo/nexus.git

cd nexus


2️⃣ Setup Firebase

Go to Firebase Console

Create a new project

Enable Firestore Database

Copy your Firebase config snippet and replace the placeholder inside the HTML file (__firebase_config)


3️⃣ Run Nexus AI

Open the nexus.html file in your browser directly

Or use a simple local server (e.g., VS Code Live Server)



🎥 Demo Example

User: “I want a system for managing a library.”

Clarifier Agent: “Do you need book search, member management, or lending records?”

User: “Yes, all three.”

Analyzer Agent: “Requirements identified: book search, member management, lending system.”

Feasibility Agent: “All feasible, though lending records may require secure login.”

SRS Generator Agent: “Generated full SRS including functional and non-functional requirements.”



🌍 Use Cases

📱 Startups – Capture clear requirements before building products.

🏢 IT Teams – Minimize costly requirement misunderstandings.

🎓 Students & Researchers – Explore AI-driven requirement gathering.


🔮 Future Enhancements

Export SRS as PDF/Word.

Add visual requirement diagrams (UML/User stories).

Support for multi-language requirement gathering.

