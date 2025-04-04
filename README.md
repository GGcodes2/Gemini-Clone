
# 🌟 Gemini Clone

A React-based frontend application that integrates with Google's **Gemini API** to simulate conversational AI functionality — built as a Gemini-powered chatbot clone.

## ✨ Features

- Uses **Google's Generative Language API (Gemini)**
- Handles text prompts with responses powered by `gemini-pro` or `gemini-1.5-pro`
- Responsive UI for chat-like interaction
- Environment variable support for secure API key handling
- Modular and clean React component structure

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/gemini-clone.git
cd gemini-clone
```

### 2. Install dependencies

```bash
npm install
```

### 3. Set up your API key

Create a `.env` file in the root directory and add your Gemini API key:

```
VITE_GEMINI_API_KEY=your_api_key_here
```

Make sure the `.env` file is in your `.gitignore`.

---

## 💡 Usage

Start the development server:

```bash
npm run dev
```

Open your browser and go to:

```
http://localhost:5173
```

Type a prompt and watch Gemini generate a response!

---

## 🛠️ Technologies Used

- [React](https://react.dev/)
- [Vite](https://vitejs.dev/)
- [Google Generative AI SDK](https://www.npmjs.com/package/@google/generative-ai)

---

## ⚠️ Notes

- Rate limits apply. Free tier for Gemini 1.5 Pro is **2 requests/minute**.
- If you hit quota errors (`429`), try switching to `gemini-pro` or enable billing to increase quota.
- Keep your API key **secure** and never expose it in public repos.

---

## 📸 Screenshots

> _Add screenshots here if you have UI/UX visuals_

---

## 📄 License

This project is licensed under the MIT License.

---

## 🙌 Credits

- [Google Generative Language API](https://ai.google.dev/)
- Built by [Your Name](https://github.com/your-username)

---
