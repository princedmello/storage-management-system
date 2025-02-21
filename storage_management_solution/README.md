# 📂 Storage and File Sharing Platform

> A modern web-based platform for seamless file storage and sharing, built with Next.js 15 and Appwrite.

---

## 🚀 Features

- 🔐 **User Authentication** – Secure signup, login, and logout using Appwrite authentication.
- 📤 **File Uploads** – Supports uploading various file types like documents, images, videos, and audio.
- 📂 **File Management** – View, rename, or delete uploaded files easily.
- 📥 **Download Files** – Download uploaded files anytime for offline access.
- 🔗 **File Sharing** – Share files securely with others via unique links.
- 📊 **Dashboard** – Get insights on storage usage, recent uploads, and file summary by type.
- 🔎 **Global Search** – Quickly find files and shared content.
- 📌 **Sorting Options** – Organize files by date, name, or size.
- 🎨 **Modern UI** – Clean, responsive design using TailwindCSS & ShadCN.
- 🛠 **Built with the Latest Tech** – Uses React 19, Next.js 15, and Appwrite for optimized performance.

---

## 🛠 Tech Stack

| Technology       | Description |
|-----------------|------------|
| ⚛ **React 19** | Frontend framework for building UI |
| 🚀 **Next.js 15** | Full-stack framework for React applications |
| ☁ **Appwrite** | Backend-as-a-Service (BaaS) for authentication and storage |
| 🎨 **TailwindCSS** | Utility-first CSS framework for styling |
| 🖌 **ShadCN** | UI component library for enhanced design |
| ⌨ **TypeScript** | Strongly typed JavaScript for scalability |

---

## 🎯 Installation Guide

Follow these steps to set up the project locally:

### 🔹 Prerequisites
Ensure you have the following installed:
- [Git](https://git-scm.com/downloads)
- [Node.js](https://nodejs.org/)
- npm (comes with Node.js)

### 🔹 Setup Instructions

1. **Clone the Repository**  
   ```sh
   git clone https://github.com/princedmello/storage_management_system.git
   cd storage_management_solution
   ```
2. **Install Dependencies**  
   ```sh
   npm install
   ```
3. **Set Up Environment Variables**  
   Create a `.env.local` file in the root directory and add:
   ```sh
   NEXT_PUBLIC_APPWRITE_ENDPOINT="https://cloud.appwrite.io/v1"
   NEXT_PUBLIC_APPWRITE_PROJECT=""
   NEXT_PUBLIC_APPWRITE_DATABASE=""
   NEXT_PUBLIC_APPWRITE_USERS_COLLECTION=""
   NEXT_PUBLIC_APPWRITE_FILES_COLLECTION=""
   NEXT_PUBLIC_APPWRITE_BUCKET=""
   NEXT_APPWRITE_KEY=""
   ```
   Replace the values with your Appwrite credentials.

4. **Run the Project**  
   ```sh
   npm run dev
   ```
   Open [http://localhost:3000](http://localhost:3000) in your browser.

---

## 🕸️ Code Snippets

| File                | Description |
|--------------------|------------|
| `tailwind.config.ts` | Tailwind CSS configuration |
| `globals.css`       | Global styles |
| `constants/index.ts` | App constants |
| `lib/utils.ts`      | Utility functions |
| `index.d.ts`       | Type definitions |

---

## 📜 License

This project is licensed under the **MIT License** – feel free to modify and use it for your own purposes.
