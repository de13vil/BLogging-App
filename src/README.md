# 📝 MegaBlog

A full-featured blogging platform built using **React**, **Vite**, **Tailwind CSS**, and **Appwrite** (BaaS). It allows users to sign up, sign in, create posts with rich text editing, upload images, and manage their content — all with a responsive and elegant UI.

---

## 🚀 Features

- 🔐 Authentication (Sign Up, Sign In, Logout)
- 📝 Rich Text Editor (TinyMCE integration)
- 📸 Image Upload with Appwrite Storage
- 📄 Create, Edit, Delete Posts
- 🧑‍💼 User-specific post ownership
- 🗃️ Active/Inactive post status
- 🌗 Light/Dark mode friendly design
- 💾 Persistent storage using Appwrite Database and Storage

---

## 🛠️ Tech Stack

- **Frontend:** React, Vite, Tailwind CSS
- **State Management:** Redux Toolkit
- **Backend-as-a-Service:** Appwrite
- **Editor:** TinyMCE (Rich Text Editor)

---

## 📦 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/megablog.git
   cd megablog

2. **Install Dependencies**
-   npm i

3. **Create Environment Variables**
- VITE_APPWRITE_URL="endpoint of your project id"
- VITE_APPWRITE_PROJECT_ID=your_project_id
- VITE_APPWRITE_DATABASE_ID=your_database_id
- VITE_APPWRITE_COLLECTION_ID=your_collection_id
- VITE_APPWRITE_BUCKET_ID=your_bucket_id

5. **Start the development server**
- npm run dev