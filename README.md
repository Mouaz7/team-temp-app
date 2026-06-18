# 📊 Team Temp App – Next-Gen Employee Survey Platform

> **An internal platform developed during an internship at Softhouse to revolutionize employee feedback.** 
> By replacing static forms with an interactive, AI-driven, and gamified ecosystem, Team Temp App increases engagement and simplifies data analysis for management.

⚠️ **Confidentiality Notice:** 
This project was developed during a Software Engineering internship at Softhouse. Due to strict internal company policies and confidentiality agreements, **no source code is included or shared in this repository**. This page serves exclusively as a visual, architectural, and process-oriented portfolio to demonstrate the system's design and my specific contributions.

---

## 🎥 System Demonstration

Experience the platform in action. The video below showcases the core user flows, including passwordless login, survey interaction, and administrative tools.

**[▶ Watch the Full System Demo](https://docs.google.com/videos/d/1tlkbaIDito2X7pxVhLmHRwy75HIBwpiT8owr4qwkQQA/edit?usp=sharing)**

---

## 🚀 The Value Proposition

Traditional surveys often suffer from low response rates and time-consuming manual analysis. Team Temp App solves this by introducing:

* **Frictionless Access:** Secure, passwordless login via Google Workspace across Web and Mobile.
* **Gamified Engagement:** Employees unlock achievements and build streaks by participating, transforming a chore into a rewarding experience.
* **AI-Powered Insights:** Google Gemini AI assists managers in crafting effective surveys and automatically summarizes free-text feedback.
* **Targeted Delivery:** Smart notifications reach employees directly via email and Slack.

---

## 🧩 System Architecture & Tech Stack

The system is built as a highly scalable monorepo, utilizing a modern, type-safe stack across all clients and backend services.

| Layer | Component | Technology | Description |
| :--- | :--- | :--- | :--- |
| **Frontend** | User & Admin Portals | React 19, Vite, Tailwind CSS | High-performance web clients with React Query for state management. |
| **Mobile** | Mobile App | React Native, Expo | Cross-platform application mirroring the web experience natively. |
| **Backend** | Central API | Express 5, Bun | RESTful API structured in a strict 4-layer architecture (Routes, Controllers, Services, Repositories). |
| **Data** | Database & ORM | MongoDB, Prisma | Schema-driven data storage ensuring end-to-end TypeScript safety. |
| **Security** | Authentication & RBAC | Better-Auth, Google OAuth | Secure session management with strict Role-Based Access Control. |
| **Services** | Integrations | Gemini AI, Cloudinary, Qlik | Specialized services for generative AI, media hosting, and data visualization. |

---

## 👨‍💻 My Role & Contributions

As a Software Engineering Intern on this project, I took ownership of core backend infrastructure and security, ensuring a stable foundation for the entire application. My key contributions included:

* **Authentication & Security:** Designed and implemented the passwordless Google OAuth flow using Better-Auth, securing endpoints across all three client applications.
* **Backend API Development:** Built robust API routes and controllers, enforcing strict data validation using Zod.
* **System Integration:** Resolved complex session management challenges across different environments, including setting up dedicated bypass endpoints for automated CI testing.
* **Documentation:** Authored comprehensive setup guides and maintained the OpenAPI specifications.

---

## ⚙️ Development Methodology

The project was driven by professional software engineering standards to ensure high quality and reliable delivery:

* **Agile Framework:** Executed in two-week Scrum sprints with continuous backlog refinement and bi-weekly stakeholder demos.
* **CI/CD Pipeline:** Fully automated testing and deployment pipelines hosted on Google Cloud. No code was merged without passing all quality gates.
* **Automated Testing:** Implemented a comprehensive test pyramid featuring unit tests (Bun), integration tests, and End-to-End testing (Cypress) for critical user paths.
* **Strict Code Quality:** Enforced through ESLint, Prettier, and mandatory peer code reviews via Bitbucket pull requests.

---

## 📸 Visual Documentation

*(Images are located in the `/images` folder)*

* **🏠 Dashboard:** Displays available surveys, active streaks, and gamification progress.
* **📝 Survey Interface:** Highlights dynamic question types and conditional logic branching.
* **📊 Analytics Panel:** Visualizes real-time response rates and AI-generated text summaries.
* **🏢 Branch Management:** Demonstrates role-based access control for local office administration.

---

© 2026 Team Temp App – A Softhouse Internship Project 💼
