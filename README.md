# 🌍 Travel Journal Web Application

A full-stack **Travel Journal** web application that allows users to document, manage, and visualize their travel experiences. Users can create entries with descriptions, locations, and images, then explore them through an interactive interface and map view.

---

## 🚀 Features

- 👤 User authentication system  
- 📝 Create, view, and manage travel entries  
- 🗺️ Interactive map for travel locations  
- 🖼️ Image support for journal posts  
- 📱 Responsive UI design  
- ⚡ Fast client rendering with Vite + React  
- 🧠 Schema validation using Zod  
- 📦 MongoDB database integration  

---

## 🛠️ Tech Stack

### Frontend
- React + TypeScript  
- Vite  
- TailwindCSS  
- Radix UI  
- React Query  

### Backend
- Node.js + Express  
- MongoDB + Mongoose  
- Passport Authentication  

### Other Tools
- Zod validation  
- dotenv configuration  
- Vercel deployment  

---

## 📂 Project Structure

```
Travel-Journal/
│
├── client/              # Frontend React application
├── server/              # Backend Express API
├── shared/              # Shared types and schemas
├── script/              # Setup and utility scripts
├── attached_assets/     # Images and static assets
└── package.json
```

---

## ⚙️ Installation & Setup

### 1. Clone Repository
```
git clone https://github.com/yourusername/travel-journal.git
cd travel-journal
```

### 2. Install Dependencies
```
npm install
```

### 3. Environment Variables

Create a `.env` file in the root folder:

```
MONGODB_URI=your_mongodb_connection_string
SESSION_SECRET=your_secret_key
NODE_ENV=development
```

---

### 4. Run Development Mode

Start backend server:
```
npm run dev
```

Start frontend client:
```
npm run dev:client
```

---

## 🧪 Utility Scripts

| Command | Description |
|--------|-------------|
npm run test:db | Test MongoDB connection |
npm run setup | Initial setup script |
npm run add-samples | Insert sample travel entries |
npm run check-db | Inspect database data |
npm run create-johndoe | Create demo user |

---

## 🏗️ Production Build

```
npm run build
npm start
```

---

## ☁️ Deployment (Vercel)

Project already contains deployment configuration files:

```
vercel.json
server/vercel-handler.ts
script/vercel-build.js
```

Deployment Steps:
1. Push repository to GitHub  
2. Import project into Vercel  
3. Add environment variables  
4. Deploy  

---

## 🔐 Security Notes

Current authentication setup is simplified for development.

For production deployment, recommended improvements:

- Hash passwords using bcrypt  
- Implement JWT or secure session storage  
- Add rate limiting middleware  
- Validate user inputs strictly  

---

## 📸 Included Assets

Preloaded resources are located inside:

```
attached_assets/
```

Contains:
- Sample travel images  
- UI illustrations  
- Map resources  

---

## 📜 License

MIT License — free to use, modify, and distribute.
