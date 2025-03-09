# 🏛️ E-Governance

A web-based platform that allows citizens to report issues by selecting their state and district. Government officials can access a dedicated portal to view issues specific to their state and update their status.

## ✨ Features

### 🧑‍🤝‍🧑 Citizen Portal  
- 📝 Citizens can submit issues with details like title, description, state, and district.  
- 📂 Issues are stored in a database for retrieval by government officials.  

### 🏢 Government Official Portal  
- 👀 Officials can view issues relevant to their state only.  
- ✅ Officials can mark issues as **Accepted**, **Done**, or **Rejected**.  

## 💻 Tech Stack

- **Frontend:** 🌐 HTML, 🎨 CSS, ⚡ JavaScript  
- **Backend:** 🛠️ Node.js, 🚀 Express.js  
- **Database:** 🗄️ MongoDB  

## 🔗 API Endpoints

### 🧑‍💻 Citizen Side  
- `POST /issues` - ✍️ Submit a new issue.  
- `GET /issues/:state` - 📜 Get issues by state.  

### 🏛️ Government Official Side  
- `GET /official/issues` - 🔍 Fetch issues assigned to the logged-in official's state.  
- `PATCH /official/issues/:id` - ✅ Update issue status (**Accepted, Done, Rejected**).  

## 🚀 Future Enhancements

- 🔐 Add authentication for citizens and officials.  
- 📩 Implement email notifications for status updates.  
- 🎨 Improve UI/UX for better user experience.  
