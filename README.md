```markdown
# 📝 Technical Blog Site

A modern full-stack blogging platform where users can create, edit, and view technical blogs. Built using **React + Vite + Firebase** and powered by **TinyMCE** for rich text editing. Deployed on **Vercel**.

## 🚀 Live Demo

🔗 [technical-blog-site-qigg.vercel.app](https://technical-blog-site-qigg.vercel.app)

---

## 🛠️ Tech Stack

- Frontend: React + Vite
- State Management: React Hooks (useState, useEffect)
- Rich Text Editor: TinyMCE
- Backend: Firebase Firestore
- Authentication: Firebase Auth
- Storage: Firebase Storage (for thumbnails)
- Deployment: Vercel

---

## 🔧 Features

✅ User authentication (signup/login)  
✅ Create blog posts with image + formatted text  
✅ View all blogs and individual blog pages  
✅ Blog preview before publishing  
✅ Responsive and clean UI  

---

## 🏗️ Folder Structure

```

src/
├── components/
│   ├── layout/
│   └── navbar/
├── pages/
│   ├── Home.jsx
│   ├── CreateBlog.jsx
│   └── BlogDetails.jsx
├── App.jsx
├── main.jsx
├── firebase.js
└── ...

````

---

## 🧑‍💻 Run Locally

### 1. Clone the repo
```bash
git clone https://github.com/Aditi-789/Technical-Blog-Site.git
cd Technical-Blog-Site
````

### 2. Install dependencies

```bash
npm install
```

### 3. Add environment variables

Create a `.env` file in the root with the following:

```env
VITE_FIREBASE_API_KEY=your_key
VITE_FIREBASE_AUTH_DOMAIN=your_project.firebaseapp.com
VITE_FIREBASE_PROJECT_ID=your_project_id
VITE_FIREBASE_STORAGE_BUCKET=your_bucket
VITE_FIREBASE_MESSAGING_SENDER_ID=your_id
VITE_FIREBASE_APP_ID=your_app_id
VITE_TINYMCE_API_KEY=your_tinymce_api_key
```

### 4. Start the development server

```bash
npm run dev
```

---

## 🌐 Deployment (on Vercel)

This project is deployed on **Vercel**.

### Important:

Create a file named `vercel.json` in the project root to support client-side routing:

```json
{
  "rewrites": [
    { "source": "/(.*)", "destination": "/" }
  ]
}
```

### Add the same environment variables in Vercel:

* Go to your project → Settings → Environment Variables
* Add all Firebase & TinyMCE keys from `.env`


## 👩‍💻 Author

Made with ❤️ by [**Aditi Sharma**](https://github.com/Aditi-789)
Connect on LinkedIn https://www.linkedin.com/in/aditi-sharma-509a6b257/
