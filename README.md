# MANDI-MITRA-AI-PROJECT
AI-powered purchasing assistant for India's street food vendors. Helps track daily expenses and provides insights for smarter buying decisions. Built with React &amp; Supabase. 🇮🇳🤖

Mandi Mitra AI 🇮🇳🤖

An AI-powered purchasing assistant for India's street food vendors.

Built with React, Supabase, and a passion for empowering small businesses.

Key Features • Tech Stack • Getting Started • Screenshots

🎯 The Problem Street food vendors are the backbone of India's vibrant culinary culture. However, they often operate on thin margins and face daily challenges in managing their finances. A significant, often overlooked, aspect is the daily procurement of raw materials from local markets (mandis). Lacking easy-to-use tools, they struggle with:

Manual Tracking: Inconsistent or non-existent records of daily expenses. No Financial Insight: Difficulty in understanding spending patterns, identifying price fluctuations, or calculating profitability. Inefficient Purchasing: Making purchasing decisions based on gut feeling rather than data, leading to potential losses. ✨ The Solution: Mandi Mitra AI Mandi Mitra AI (meaning Market Friend AI) is a hyper-focused, mobile-first web application designed to be the digital companion for these vendors. It replaces manual guesswork with a simple, intuitive interface for logging purchases and an AI assistant that provides actionable insights.

Our goal is to empower vendors to make smarter purchasing decisions, track their expenses effortlessly, and ultimately increase their profitability, all through a tool that is accessible and easy to use.

🚀 Key Features 🔐 Secure Authentication: Simple and secure email/password signup and login, powered by Supabase Auth. 📊 Insightful Dashboard: A clean, at-a-glance overview of key financial metrics like total spending and top purchases. ✍ Effortless Transaction Logging: A streamlined CRUD interface to quickly add, view, edit, and delete daily mandi purchases. 🤖 AI-Powered Assistant: An integrated chatbot that analyzes a user's personal purchase data to answer questions like: "How much did I spend on tomatoes last week?" "What is my most expensive purchase?" "Suggest ways to optimize my spending." 👤 Personalized Profiles: Users can manage their personal information and upload a profile avatar for a personalized experience, using Supabase Storage for secure file handling. 📱 Fully Responsive: A beautiful, modern UI that works flawlessly on any device, from a small smartphone to a desktop. 💨 Modern & Fast: Built with Vite for a lightning-fast development experience and a highly optimized production build. 🛠 Tech Stack This project leverages a modern, robust, and scalable technology stack.

Frontend: React (with TypeScript), Vite Backend & Database: Supabase (PostgreSQL, Auth, Storage) Styling: Tailwind CSS State Management: Zustand Animations & UI: Framer Motion, Lucide React, React Hot Toast Routing: React Router DOM 📸 Screenshots Click to view application screenshots ⚙ Getting Started To get a local copy up and running, follow these simple steps.

Prerequisites Node.js (v18 or later) npm or yarn A free Supabase account Installation & Setup Clone the repository:

git clone https://github.com/MANDI-MITRA-AI/MANDI-MITRA-AI-PROJECT.git cd MANDI-MITRA-AI-PROJECT

npm install

Create a Supabase project. In the Supabase dashboard, go to Project Settings > API. Create a file named .env in the root of your project. Copy the Project URL and anon (public) key into your .env file:

In the Supabase dashboard, go to the SQL Editor. Copy the contents of the SQL files from the /supabase/migrations directory in this project. Execute the SQL queries to create the necessary tables (users, transactions) and storage policies. Run the development server:

npm run dev The application should now be running on https://bolt-diy-6-1754683931682.netlify.app/.

Sign in method:-

1) press the button get started.
2) enter your name, email and set up password.
3) authenticate your email by verifying it upon pressing the link sent to your email.
4) come back to the sign in page and put your email and password to go to your personal dashboard.

Contributing Contributions, issues, and feature requests are welcome! Feel free to check the issues page.

📜 License This project is licensed under the MIT License. See the LICENSE file for details.
