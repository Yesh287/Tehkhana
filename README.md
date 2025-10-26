# 🌩️ Tehkhanā – Cloud File Storage

A **secure, scalable file-storage web app** for teams to upload, organize, and share files in real-time.  
Built with **Next.js**, **Tailwind CSS**, **Appwrite**, and **ShadCN/UI**.

> “Tehkhanā” (meaning *vault*) is your personal digital locker — authenticated, real-time, and collaborative.

---

### 🔗 Live Demo  
➡️ [tehkhana.onrender.com/sign-in](https://tehkhana.onrender.com/sign-in)

### 💻 Repository  
📦 [GitHub Repo](https://github.com/Yesh287/Tehkhana/tree/main)

---

## 🚀 Features

- 🔒 **JWT / OAuth Authentication** for secure login  
- 👥 **Role-Based Access Control** (Admin, Editor, Viewer)  
- ⚡ **Real-Time File Sync** with Appwrite Realtime DB  
- 🗃️ **File Upload, Preview & Delete** functionality  
- 🧾 **RESTful APIs Integration** for CRUD operations  
- 🎨 **Modern UI/UX** using Tailwind CSS + ShadCN components  

---

## 🧠 Tech Stack

| Layer | Technology |
|-------|-------------|
| **Frontend** | Next.js 14, Tailwind CSS, ShadCN/UI |
| **Backend** | Appwrite SDK, REST APIs |
| **Auth** | JWT / OAuth2 |
| **Database** | Appwrite Realtime Database |
| **Hosting** | Render |

---

## ⚙️ Setup Instructions

bash
# 1️⃣ Clone the repo
git clone https://github.com/Yesh287/Tehkhana.git
cd Tehkhana

# 2️⃣ Install dependencies
npm install

# 3️⃣ Configure environment variables
# Create a .env.local file with:
NEXT_PUBLIC_APPWRITE_ENDPOINT=<your_appwrite_endpoint>
NEXT_PUBLIC_APPWRITE_PROJECT_ID=<your_project_id>

# 4️⃣ Start the development server
npm run dev
App will run at http://localhost:3000

Folder Structure
Tehkhana/
├── app/            # Next.js App Router (auth & dashboard)
├── components/     # UI Components
├── lib/            # Appwrite client config
├── public/         # Static assets
├── styles/         # Tailwind configs
└── README.md


📈 Future Enhancements

🗂️ Folder hierarchy and nested storage

🔒 End-to-end encryption for files

🧾 Activity logs for user actions

🌙 Dark mode toggle

Good Day!


