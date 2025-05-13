# 🌌 MythiQ – The Intelligent Mythology Chatbot

**MythiQ** is a mythology-powered AI chatbot that draws wisdom from ancient Indian scriptures like the **Mahabharata**, **Advaita Vedanta**, and **The Vedas** to provide contextual, philosophical, and life-guiding answers. It uses state-of-the-art Retrieval-Augmented Generation (RAG) architecture to understand user queries dynamically and generate insightful, source-specific responses.

---

## 🔮 Features

- ✅ **Ask Anything**: Query the bot with life questions like “What is the meaning of suffering?” or “How to overcome fear?” and get answers derived from multiple philosophical texts.
- 🧘‍♂️ **Source-Based Segmentation**: See what Advaita Vedanta, Mahabharata, and Vedas each say about your question.
- 🧠 **Memory Retention**: Remembers user conversations for up to 30 days (personalized experience).
- 🔐 **Secure Auth**: User authentication via Firebase (Google or Email/Password login).
- 💎 **Premium Support (Coming Soon)**: Upload your own books (only for premium users) and generate summaries or context-aware insights.
- 📖 **Storytelling Mode (Planned)**: Mythological story narration based on selected characters or events.
- 🌐 **Fully Cloud-Ready**: Built for scalability up to 2000+ users using Firebase and a modern LLM backend.

---

## ⚙️ Tech Stack

| Layer        | Technology                          |
|--------------|-------------------------------------|
| Frontend     | React.js + TailwindCSS + Framer Motion |
| Backend      | Node.js / FastAPI (to be selected)  |
| Auth & DB    | Firebase Auth + Firestore           |
| Vector Store | Pinecone / Chroma                   |
| LLM          | OpenAI GPT / Mistral (RAG-based)    |
| Deployment   | Vercel / Firebase Hosting / Render  |

---

## 🚀 How It Works

1. User logs in via Google or email.
2. Asks a question like _"I am depressed. What should I do?"_
3. The query is embedded into a vector and matched with scripture excerpts in the vector DB.
4. The matched passages are passed to the LLM.
5. A contextual, human-like answer is generated and segmented by source.
6. The interaction is stored for up to 30 days for memory continuity.

---

## 🧪 Project Roadmap

### ✅ Current Sprint
- [x] Firebase Auth Setup (Email + Google)
- [x] Firestore Integration (User memory, flags)
- [x] Frontend UI base + chat flow
- [x] RAG pipeline integration

### 🔜 Next Sprints
- [ ] Storytelling Mode (Myth-based narration)
- [ ] Premium Upload Feature
- [ ] Admin Dashboard for Monitoring
- [ ] Multi-language support (optional)
- [ ] Caching and Performance Optimizations

---

## 🤝 Contributing

Want to join the journey of building India's first mythology-powered life coach bot? Contributions are welcome! Please open an issue or submit a pull request.

---

## 📜 License

This project is open-sourced under the MIT License.

---

## 🙏 Acknowledgements

Inspired by ancient Indian philosophy and modern AI. Special thanks to:
- OpenAI for the LLM APIs
- Firebase for scalable auth and DB
- Pinecone/Chroma for lightning-fast semantic search

---

## ✨ Author

Made with ❤️ by [vis243](#) — aspiring AI Engineer and mythology enthusiast.
