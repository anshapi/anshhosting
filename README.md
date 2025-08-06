# 📁 File Hosting Web App

A simple Express.js-based file hosting and uploading web server. Users can upload files (up to 20MB), and receive a public URL to access the uploaded file.

> ✅ Hosted using Node.js + Express  
> 🚀 Supports file uploads via `/upload` endpoint  
> 🌐 Uploaded files accessible via `/uploads/<filename>`  
> 🧠 Built with ❤️ by [anshapi of TG](https://t.me/anshapi)

---

## 🚧 Features

- Upload any type of file up to **20MB**
- Automatically generates public download link
- Auto-creates `/uploads` directory if not present
- Static files served from `public/`
- CORS enabled (ready for frontend integration)

---

## 📦 Tech Stack

- [Node.js](https://nodejs.org/)
- [Express.js](https://expressjs.com/)
- [Multer](https://github.com/expressjs/multer) for file uploads
- [CORS](https://developer.mozilla.org/en-US/docs/Web/HTTP/CORS)

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/file-hosting-app.git
cd file-hosting-app
