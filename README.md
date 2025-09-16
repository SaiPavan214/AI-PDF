# 📚 AI-PDF Notes Taker

A full-stack web application that allows users to upload PDFs, automatically generate concise structured notes, and ask intelligent Q&A over the document using Generative AI.

---

## 🌐 Live Demo

🔗 [https://ai-pdf-eight.vercel.app/](https://ai-pdf-eight.vercel.app/)

## ✨ Features

- ✅ Upload PDFs and extract text automatically
- ✅ Generate concise, structured notes using Generative AI
- ✅ Ask contextual questions (Q&A) over the uploaded PDF
- ✅ Modern, responsive UI with Tailwind CSS
- ✅ Semantic understanding via embeddings + RAG pipeline
- ✅ Deployed with easy scalability in mind

---

## 🚀 Tech Stack

| Technology    | Role                           |
| ------------- | ------------------------------ |
| Next.js       | React-based frontend framework |
| React         | Interactive UI components      |
| Node.js       | Backend runtime (API routes)   |
| OpenAI API    | LLM for summarization & Q&A    |
| Tailwind CSS  | Styling and responsive UI      |
| Vercel/Render | Deployment                     |

---

## 📁 Project Structure

AI-PDF-Notes-Taker/
│
├── public/ # Static assets (logos, icons)
├── src/ # Source code
│ ├── pages/ # Next.js pages (routes, API endpoints)
│ ├── components/ # Reusable UI components
│ ├── utils/ # Helper functions (PDF parsing, chunking)
│ └── styles/ # Global styles
├── .env # Environment variables (excluded from Git)
├── .env.example # Sample config template
├── package.json
└── README.md

---

## ⚙️ Setup Instructions

### 1. Clone the repository

```bash
git clone https://github.com/SaiPavan214/AI-PDF.git
cd AI-PDF
```

2. Install dependencies
   npm install

3. Configure environment variables

Create a .env file in the root directory with:

OPENAI_API_KEY=your_openai_api_key

# Optional:

# GEMINI_API_KEY=your_google_generative_ai_key

➡️ On Vercel/Render:
Go to your project → Settings → Environment Variables → Add the same variables above.

4. Run the development server
   npm run dev

The app will be available at:
🔗 http://localhost:3000

5. Access the deployed app

✅ Live deployment:
🔗 https://ai-pdf-eight.vercel.app

📌 Future Improvements

🗂 Save uploaded PDFs and generated notes in a database (Postgres/MongoDB)

📱 Enhance mobile responsiveness

📊 Add vector DB (Pinecone/Weaviate) for faster retrieval

🔍 Advanced search inside notes

🧾 Export notes to PDF/Markdown

🛡 Security

Environment variables protect sensitive API keys.

🚫 Never commit your .env file.

✅ Instead, share a .env.example for configuration reference.

🤝 Contributions

Pull requests are welcome!
If you find bugs or have ideas for improvements, feel free to open an issue or PR.

📄 License

This project is licensed under the MIT License
.

👨‍💻 Author

Made with ❤️ by Sai Pavan
