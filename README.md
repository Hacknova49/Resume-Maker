# 📄 Resume Maker

**Resume Maker** is a full-stack web application that allows users to seamlessly create, customize, and download professional resumes. Built using modern technologies like React and Node.js, this app aims to simplify resume building for users of all technical backgrounds.

---
## 🖼️ Screenshots

![Screenshot1](./img/Screenshot2.png)

![Screenshot2](./img/Screenshot1.png)

![Screenshot3](./img/Screenshot3.png)

---
## 👥 Meet the Team

- **Swagata Mandal** – Lead Frontend Developer & Backend Contributor & API Integrator   
- **Sayam Barman** – Frontend Developer & UI/UX Enhancer  
- **Soham Mangal** – Lead Backend Developer 
- **Sougata Kundu** – AI Integration and Content Intelligence ( currently working on )

---
## 🚀 Features

- 🔐 **User Authentication** (Sign Up / Login)
- 📝 **Dynamic Resume Editor**
- 🎨 **Template Customization**
- 💾 **Downloadable PDF Support**
- 📦 Modular and scalable project structure

---

## 🛠️ Tech Stack

**Frontend**:
- React.js
- TypeScript
- Tailwind CSS
- Vite

**Backend**:
- Node.js
- Express.js
- MongoDB (via Mongoose)

**Tools & Libraries**:
- JWT for Authentication
- ESLint for code linting
- PDF generation utilities

---

## 📂 Project Structure

```
Resume-Maker/
├── backend/              # Backend API files
│   ├── config/          # Database config
│   ├── controllers/     # Route logic
│   ├── middleware/      # Validation/auth helpers
│   ├── models/          # Mongoose schemas
│   ├── routes/          # API endpoints
│   └── server.js        # Express server
├── frontend/            # Frontend application files
│   ├── public/          # Static files
│   ├── src/
│   │   ├── components/  # UI Components
│   │   ├── pages/       # Application pages
│   │   ├── services/    # API services
│   │   ├── context/     # React contexts
│   │   └── utils/       # Utility functions
├── TextEnhancerAI/      # AI text enhancement module
└── README.md
```

---

## 🧪 Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/Hacknova49/Resume-Maker.git
   cd Resume-Maker
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm run dev
   ```

> Note: Make sure MongoDB is running locally or provide your MongoDB URI in a `.env` file for backend functionality.

---

## ⚠️ Known Issues

- PDF generation and layout may not always be pixel-perfect.
- Resume field validations can be improved.
- More templates and export formats coming soon!

---

## 📌 To-Do / Roadmap

- [ ] Add more resume templates
- [ ] Rich text editing support
- [ ] Enhance Live preview while editing

---

## 🙌 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss your proposed change.

##Developers
Hacknova49

---

## 📄 License

This project is licensed under the MIT License.