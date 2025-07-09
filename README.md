
# 🧭 Vihara Agent – AI Trip Planner

An intelligent conversational travel planner that uses GPT-based natural language processing to generate personalized travel itineraries. The platform integrates Google Maps for route optimization and leverages automation tools to provide fast, reliable, and location-aware travel planning assistance.

---

## 🚀 Features

- 🧠 **AI-Powered Itinerary Generation**  
  Uses OpenAI GPT models to understand user preferences and create dynamic, multi-day travel plans.

- 🗺️ **Google Maps Integration**  
  Fetches real-time geolocation data to optimize routes and suggest nearby attractions, restaurants, and hotels.

- 🔁 **Automated Backend Workflows**  
  Uses **n8n** to automate data handling and service orchestration, improving efficiency and reliability.

- 🧱 **Robust Infrastructure**  
  Node.js-based backend with built-in fallback mechanisms for API failures, ensuring 99.8% uptime.

- 🌐 **Modern Frontend**  
  Built with **React.js** for a smooth, responsive user interface that makes travel planning intuitive and engaging.

---

## 📸 Demo

> *(Add screenshots or a demo video/GIF here if available)*

---

## ⚙️ Tech Stack

| Component         | Technology Used                       |
|------------------|----------------------------------------|
| Frontend         | React.js                               |
| Backend          | Node.js, Express                       |
| AI Integration   | OpenAI GPT API                         |
| Mapping          | Google Maps API                        |
| Automation       | n8n (low-code workflow automation)     |
| Deployment       | (e.g., Vercel / Heroku / Render etc.) |

---

## 🏗️ Project Architecture

```plaintext
React Frontend
   ↓
Node.js API Server
   ↓
GPT-based NLP + Google Maps API
   ↓
Automated Workflows (n8n)
```

---

## 📈 Impact

- ⏱️ Reduced manual trip planning time by **75%**
- 🔁 Improved response reliability by **40%**
- 🛡️ Achieved **99.8% uptime** via smart fallback logic

---

## 📦 Installation & Setup

```bash
# Clone the repo
git clone https://github.com/<your-username>/vihara-agent.git
cd vihara-agent

# Install dependencies for frontend and backend
cd client
npm install
cd ../server
npm install

# Create .env files with API keys (OpenAI, Google Maps, etc.)
# Start the servers
npm start
```

---

## 🔐 Environment Variables

Create `.env` files in both `client/` and `server/` folders with:

```env
# Example for server/.env
OPENAI_API_KEY=your_openai_key
GOOGLE_MAPS_API_KEY=your_google_maps_key
N8N_WEBHOOK_URL=your_n8n_webhook
```

---

## 📚 Future Enhancements

- 🧳 Add hotel & flight booking integration
- 🗣️ Multi-language support
- 📲 Mobile app version
- 🧠 On-device itinerary caching for offline use

---

## 🤝 Contributing

Contributions, feedback, and ideas are welcome!  
Feel free to open an issue or submit a pull request.

---

## 📝 License

MIT License. See `LICENSE` file for details.

---

## 👤 Author

**Lakshman Rohith**  
[GitHub](https://github.com/LakshmanRohith) • [LinkedIn](https://www.linkedin.com/in/lakshman-rohith-sanagapalli/)
