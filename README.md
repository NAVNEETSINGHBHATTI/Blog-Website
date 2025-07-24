# 📝 Blog Website

A blog website is an online platform where individuals or organizations can publish articles, thoughts, or updates, typically in a chronological format. Built using React, a blog website becomes highly interactive and efficient, allowing seamless navigation, dynamic content updates, and reusable components.

---

## 🔧 Tech Stack

**Frontend:**

- React.js
- Redux Toolkit (for state management)
- Tailwind CSS / CSS Modules
- React Router DOM
- React-hook-form

**Backend:**

- Node.js
- Appwrite (for image storage or authentication) 

**Other Tools:**

- Git & GitHub
- Vite (for frontend setup)

---

## 🔥 Key Features

- 📄 **Dynamic Individual Post Pages**  
  Each blog post has its own dedicated page displaying the full content, author, and timestamp.

- ✍️ **Create & Edit Blog Posts**  
  Authenticated users can create new posts and update their own existing content through a rich text editor or form-based UI.

- 🔁 **Client-Side Routing with React Router**  
  Enables seamless navigation between pages (Home, Post, Create, Edit, etc.) without full page reloads, enhancing performance and user experience.

- 📷 **Image Upload & Display**  
  Users can upload images to enhance their blog posts. These are stored securely (via Appwrite or cloud storage service).

- 📱 **Responsive Design**  
  Fully responsive layout optimized for desktop, tablet, and mobile screens using Tailwind CSS (or any styling approach used).

- 🔐 **Authentication & Authorization**  
  Only authenticated users can write or edit blog posts, ensuring content integrity and security.

---

## 📥 **Getting Started**

To run the project locally, you will need **Node.js** and **Git** installed on your machine.

### 🛠 Installation and Setup Instructions

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/blog-website.git

2. Set the Frontend and Backend:

   ```bash
      cd server
        npm install
        touch .env
        # Add your environment variables (PORT, MONGO_URI,Appwrite_Url etc.)
        npm run dev

