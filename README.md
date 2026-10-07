### Hi, I'm Sam 👋

I'm a front-end developer in Birmingham, UK. I design interfaces in Figma and build them in **React and TypeScript**, and I care about the details people notice: accessible forms, keyboard focus, and loading and error states that make sense.

Since January 2025 I've designed, built and launched **[Aurnet](https://aurnet.co.uk)**, a church management platform, on my own:

- **Web dashboard:** Next.js and React, 95+ pages on a shared Tailwind component library
- **Mobile app:** React Native (Expo), 240+ screens, live on the Apple App Store
- **API:** NestJS and PostgreSQL, with Stripe payments, real-time chat, video rooms and push notifications

Aurnet's source is private, but I've pulled some of it out to share 👇

---

### 📌 Featured

**[aurnet-ui-kit](https://github.com/Okoyesam10/aurnet-ui-kit)**: the components behind Aurnet's dashboard (Modal, KPI strip, panels, section headers) as a standalone React + TypeScript + Tailwind project with Vitest and React Testing Library tests. The README walks through a focus bug I fixed in the Modal and the regression test that stops it coming back.

---

### 🛠 What I work with

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React Native](https://img.shields.io/badge/React_Native-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Expo](https://img.shields.io/badge/Expo-000020?style=flat-square&logo=expo&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![TanStack Query](https://img.shields.io/badge/TanStack_Query-FF4154?style=flat-square&logo=reactquery&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white)
![Jest](https://img.shields.io/badge/Jest-C21325?style=flat-square&logo=jest&logoColor=white)
![Testing Library](https://img.shields.io/badge/Testing_Library-E33332?style=flat-square&logo=testinglibrary&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

---

### 🧠 Things I learned the hard way

- **A modal that kept stealing focus.** Typing in a form inside a dialog kicked the cursor out after every keystroke. An inline `onClose` arrow was a new function on each render, so the focus-trap effect kept re-running. I fixed it by keeping `onClose` in a ref. [Write-up and test →](https://github.com/Okoyesam10/aurnet-ui-kit#the-bug-worth-reading-modal-focus)
- **iOS notifications that silently did nothing.** I wanted pushes to look like a messaging app, with the church logo as the avatar. It failed for days with no error at all. The cause was one missing `NSUserActivityTypes` entry in the Info.plist.
- **One church must never see another's data.** In a multi-tenant app, every query is scoped per church and every write is atomic. A missed filter isn't a bug, it's a breach.

---

### 🎓 Background

BSc Computer Science (2:1), Birmingham City University · IBM Front-End Developer Certification · previously Front-End Developer at Order Group

### 📫 Get in touch

[LinkedIn](https://linkedin.com/in/samokoye) · [aurnet.co.uk](https://aurnet.co.uk) · okoyesam10@outlook.com
