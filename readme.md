[![Typing SVG](https://readme-typing-svg.demolab.com/?font=Fira+Code&size=24&pause=1000&color=38BDF8&center=true&vCenter=true&width=600&lines=Hi+%F0%9F%91%8B%2C+I'm+Khalid+Hasan+Meskat;Junior+Frontend+Developer;I+build+with+React%2C+Next.js+%26+Tailwind)](https://git.io/typing-svg)

---

## 👨‍💻 About Me

I'm a Junior Frontend Developer who enjoys building clean, responsive, high-performance web interfaces. I love working with **React**, **Next.js**, and **Tailwind CSS**, and I'm always exploring new tools to improve my workflow.  
Currently, I'm expanding into backend development with **Node.js** and **Express**, building a Notes API to round out my full-stack skills. Feel free to reach out if you want to talk about **web development**, open-source, or cool tech ideas!

---

## 🛠️ Tech Stack

### **Frontend**

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js)
![Tailwind CSS](https://img.shields.io/badge/TailwindCSS-38BDF8?style=for-the-badge&logo=tailwindcss)
![DaisyUI](https://img.shields.io/badge/DaisyUI-1AD1A5?style=for-the-badge&logo=daisyui)

### **Backend (Learning)**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js)
![Express](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb)

### **Tools & Others**

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git)
![VS Code](https://img.shields.io/badge/VSCode-007ACC?style=for-the-badge&logo=visual-studio-code)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite)

---

## 🌐 Connect With Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/khalidhasanmeskat/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github)](https://github.com/khalidhasan-m)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail)](mailto:khalidhasanmeskat@gmail.com)

---

## 📊 GitHub Stats

|                                                   GitHub Stats                                                   |                                                   Most Used Languages                                                   |
| :--------------------------------------------------------------------------------------------------------------: | :---------------------------------------------------------------------------------------------------------------------: |
| ![GitHub stats](https://github-readme-stats.vercel.app/api?username=khalidhasan-m&show_icons=true&theme=default) | ![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=khalidhasan-m&layout=compact&theme=default) |

---

![Profile views](https://komarev.com/ghpvc/?username=khalidhasan-m&style=flat-square)

---

# 🌍 Wanderlust Frontend

A modern **Next.js** frontend for the **Wanderlust** travel platform — browse destinations, manage bookings, and authenticate securely with Better Auth.

**Live Site:** [wanderlust-seven-gules.vercel.app](https://wanderlust-seven-gules.vercel.app)

---

## Table of Contents

- [About the Project](#about-the-project)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Environment Variables](#environment-variables)
- [Local Development Setup](#local-development-setup)
- [Project Structure](#project-structure)
- [Deployment](#deployment)
- [Backend](#backend)
- [How to Contribute](#how-to-contribute)
- [License](#license)
- [Contact](#contact)

---

## About the Project

Wanderlust Frontend is the client application for the Wanderlust travel platform. It gives users a responsive interface to explore destinations, view details, book trips, and manage their own bookings, with secure authentication handled by Better Auth.

---

## ✨ Features

- 🔐 Secure authentication with Better Auth
- 🌍 Browse travel destinations
- 📍 View destination details
- 🧳 Book travel destinations
- 📖 Manage personal bookings
- ✏️ Create, update, and delete destinations (authorized users)
- 📱 Fully responsive design
- ⚡ Fast navigation with Next.js App Router

---

## 🛠️ Tech Stack

- **Framework:** Next.js (App Router)
- **Library:** React
- **Styling:** Tailwind CSS
- **Authentication:** Better Auth
- **UI Components:** HeroUI
- **Image Optimization:** Next.js Image Component

---

## 📦 Environment Variables

Create a `.env.local` file in the project root:

| Variable              | Description                 |
| --------------------- | --------------------------- |
| `NEXT_PUBLIC_API_URL` | Backend API URL             |
| `BETTER_AUTH_URL`     | Better Auth application URL |

Example for local development:

```env
NEXT_PUBLIC_API_URL=http://localhost:5050
BETTER_AUTH_URL=http://localhost:3000
```

---

## 🚀 Local Development Setup

1. Clone the repository:

```bash
git clone https://github.com/khalidhasan-m/<repo-name>.git
cd <repo-name>
```

2. Install dependencies:

```bash
npm install
```

3. Add the environment variables shown above to `.env.local`.

4. Run the development server:

```bash
npm run dev
```

5. Open [http://localhost:3000](http://localhost:3000) in your browser.

---

## 📁 Project Structure

```text
├── app/                     # App Router pages and layouts
├── components/              # Reusable UI components
├── lib/                     # Authentication and utility functions
├── public/                  # Static assets
├── .env.local               # Environment variables
├── .gitignore                # Ignored files and folders
├── package.json             # Project dependencies
└── README.md                # Project documentation
```

---

## ☁️ Deployment

This project is optimized for deployment on **Vercel**.

1. Push the project to GitHub.
2. Import the repository into Vercel.
3. Configure the environment variables listed above.
4. Deploy the project.

Make sure `NEXT_PUBLIC_API_URL` points to your deployed backend server.

---

## 🔗 Backend

This frontend communicates with the **Wanderlust Backend Server** through REST APIs for:

- User authentication
- Destination management
- Booking management
- User profile retrieval

---

## How to Contribute (Optional)

- Fork the project
- Create a branch (`git checkout -b feature/AmazingFeature`)
- Commit your changes (`git commit -m 'Add some AmazingFeature'`)
- Push the branch (`git push origin feature/AmazingFeature`)
- Open a Pull Request

---

## License

This project is intended for educational and personal portfolio purposes.

---

## Contact

- **Live Site:** [wanderlust-seven-gules.vercel.app](https://wanderlust-seven-gules.vercel.app)
- **Email:** [khalidhasanmeskat@gmail.com](mailto:khalidhasanmeskat@gmail.com)
- **Resume:** [View Resume](https://docs.google.com/document/d/1a1Eu3D0ISeeP26XASMMZITUgY1raITydvXa4MmCKLuI/edit?usp=sharing)


<div align="center">

# 👋 Hi, I'm Khalid Hasan Meskat

### 🚀 Frontend Developer | React • Next.js • Tailwind CSS

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=24&pause=1000&color=38BDF8&center=true&vCenter=true&width=700&lines=Frontend+Developer;React+%7C+Next.js+%7C+Tailwind+CSS;Building+Modern+Responsive+Web+Applications;Always+Learning+New+Technologies;Open+to+Collaboration+%F0%9F%9A%80" alt="Typing SVG" />

<br>

<img src="https://komarev.com/ghpvc/?username=khalidhasan-m&label=Profile%20Views&color=0ea5e9&style=for-the-badge" />

</div>

---

<div align="center">

## 👨‍💻 About Me

</div>

Hi! I'm **Khalid Hasan Meskat**, a passionate **Frontend Developer** from **Bangladesh 🇧🇩**.

I enjoy creating **modern, responsive, and user-friendly web applications** with clean UI and smooth user experiences.

I'm passionate about writing clean code, learning new technologies, and turning creative ideas into real-world applications.

Currently, I'm expanding my skills in backend development with **Node.js**, **Express.js**, and **MongoDB** to become a Full Stack Developer.

- 🌱 Currently learning **Node.js, Express.js & MongoDB**
- 💻 Building full-stack web applications
- 🚀 Love React, Next.js & Tailwind CSS
- 🎯 Goal: Become a Professional Full Stack Developer
- 🤝 Open to Open Source Collaboration
- 💬 Ask me about **React, Next.js, Tailwind CSS**
- ⚡ Fun fact: I enjoy turning coffee ☕ into code.

---

<div align="center">

## 🚀 Current Focus

</div>

```text
🌍 Building Modern Web Applications
📚 Learning Backend Development
⚡ Improving Problem Solving Skills
🎨 Creating Beautiful UI/UX
🚀 Looking for Frontend Developer Opportunities
```

---

<div align="center">

## 🛠 Tech Stack

</div>

### 🎨 Frontend

<p align="left">

<img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white"/>

<img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white"/>

<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"/>

<img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB"/>

<img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs"/>

<img src="https://img.shields.io/badge/Tailwind_CSS-38BDF8?style=for-the-badge&logo=tailwindcss&logoColor=white"/>

<img src="https://img.shields.io/badge/DaisyUI-5A0EF8?style=for-the-badge&logo=daisyui&logoColor=white"/>

</p>

---

### ⚙ Backend

<p align="left">

<img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white"/>

<img src="https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express"/>

<img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white"/>

</p>

---

### 🧰 Tools

<p align="left">

<img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"/>

<img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github"/>

<img src="https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white"/>

<img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white"/>

<img src="https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel"/>

<img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white"/>

<img src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white"/>

</p>

---

<div align="center">

## 📚 Currently Learning

</div>

```text
✅ HTML5
✅ CSS3
✅ JavaScript (ES6+)
✅ React
✅ Next.js
✅ Tailwind CSS
✅ Git & GitHub
🟡 Node.js
🟡 Express.js
🟡 MongoDB
🔜 TypeScript
🔜 Docker
🔜 AWS
```

---

<div align="center">

## ☕ Fun Facts

</div>

- 🌙 I enjoy coding late at night.
- 🎨 I love creating beautiful and responsive user interfaces.
- 📖 I believe learning never stops.
- 🚀 Every project teaches something new.
- ⭐ I love contributing to open-source projects.
- ☕ Coffee + Music + Code = Perfect Day.

---