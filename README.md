# Client Portal — Project Updates, File Sharing & AI Insights

📁 A secure, multi-tenant platform for agencies & freelancers to share project progress, milestones, and files with clients — with AI-powered productivity features.

---

## ✨ Features
- Authentication with roles: Admin, Team, Client
- Clients see only their own projects & updates
- Timeline of project milestones & status
- Upload & download project files securely
- Comment & ask questions per project
- Email notifications (optional)

---

## 🤖 AI Features
- Estimated project completion dates based on milestone progress
- AI-generated professional status updates
- Summarized project activity & risks
- Risk detection: highlights projects that may miss deadlines

---

## 🛠️ Tech Stack
| Layer              | Technology |
|--------------------|------------|
| **Frontend**       | React, TailwindCSS |
| **Backend**        | Node.js, Express |
| **Database**       | MongoDB |
| **File Storage**   | Local / S3-ready |
| **Authentication** | JWT |
| **AI/NLP**         | OpenAI GPT API (or local models) |
| **Notifications**  | Email via SendGrid/Mailgun (optional) |

---

## 🚀 Setup
### Clone & Install
```bash
git clone https://github.com/ahmed-cmyk/client-portal.git
cd client-portal
````

### Backend

```bash
cd backend
npm install
cp .env.example .env
npm run dev
```

### Frontend

```bash
cd frontend
npm install
npm start
```

Frontend: [http://localhost:3000](http://localhost:3000)
Backend: [http://localhost:5000](http://localhost:5000)

---

## 🌐 Environment Variables

Create a `.env` file in `backend/` with:

```
MONGODB_URI=mongodb_connection_string
JWT_SECRET=your_jwt_secret
OPENAI_API_KEY=your_openai_key
EMAIL_API_KEY=optional_sendgrid_or_mailgun_key
```

---

## 📋 AI Features Usage

✅ AI estimates are generated automatically on the project detail view.
✅ Click *"Draft Status Update"* to auto-generate a professional update.
✅ Risk level badges appear on the dashboard based on progress patterns.

---

## 🧪 Testing

*TODO: Write tests for backend & frontend components.*

---

## 📄 License

MIT

---

## 📬 Contact

Built by [Ahmed Ikram](https://github.com/ahmed-cmyk) — feel free to reach out!
