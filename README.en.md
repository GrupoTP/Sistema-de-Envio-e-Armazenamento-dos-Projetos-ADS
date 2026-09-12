<div align="center">

### 🌐 README language

<a href="README.md">
  <img src="https://img.shields.io/badge/🇧🇷_PORTUGU%C3%8AS-clique_aqui-009c3b?style=for-the-badge" alt="Ler em Português" />
</a>
&nbsp;&nbsp;&nbsp;
<a href="README.en.md">
  <img src="https://img.shields.io/badge/🇺🇸_ENGLISH-current_version-0052cc?style=for-the-badge" alt="You are reading in English" />
</a>

</div>

---

<div align="center">

<img src="https://github.com/GrupoTP/Sistema-de-Envio-e-Armazenamento-dos-Projetos-ADS/blob/main/Senac_logo.svg.png" width="140" alt="Senac Logo" />

# 🎓 Integrative Projects Observatory

**Senac Recife College · Systems Analysis and Development Program**

*January to June 2026*

![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)
![College](https://img.shields.io/badge/College-Senac%20Recife-red?style=for-the-badge)
![Program](https://img.shields.io/badge/Program-ADS-blue?style=for-the-badge)
![Year](https://img.shields.io/badge/2026-Jan%20–%20Jun-purple?style=for-the-badge)

<sub>🌐 <a href="README.md">Leia este documento em Português</a></sub>

</div>

---

<div align="center">

<img src="https://github.com/GrupoTP/Sistema-de-Envio-e-Armazenamento-dos-Projetos-ADS/blob/main/Capa.png?raw=true" width="100%" alt="Project Cover — Integrative Projects Observatory" />

</div>

---

## 📋 Table of Contents

- [About the Project](#-about-the-project)
- [The Problem](#-the-problem)
- [The Solution — Features](#-the-solution--features)
- [System Differentials](#-system-differentials)
- [Technical Specifications and Business Rules](#-technical-specifications-and-business-rules)
  - [System Context](#system-context)
  - [Login Screen](#login-screen)
  - [User Registration Rules](#user-registration-rules)
  - [Required Registration Fields](#required-registration-fields)
  - [Optional Registration Fields](#optional-registration-fields)
  - [Email Rules](#email-rules)
  - [Profile Settings Screen](#profile-settings-screen)
  - [Resume/Portfolio Creation Screen](#resumeportfolio-creation-screen)
- [Grading System](#-grading-system)
- [ESG Impact](#-esg-impact)
- [Market](#-market)
- [Benchmark](#-benchmark)
- [Business Model](#-business-model)
- [Target Audience](#-target-audience)
- [Legislation and Compliance](#-legislation-and-compliance)
- [Technologies](#-technologies)
- [Prototype and Team](#-prototype-and-team)
- [Default Demo Credentials](#-default-demo-credentials)
- [Team](#-team)
- [Contact](#-contact)

---

## 📖 About the Project

The **Integrative Projects Observatory** is a web platform developed for **Senac Recife College**, aimed at centralizing and organizing the submission, validation, and evaluation of Integrative Projects from the **Systems Analysis and Development** program.

The system addresses the need to replace manual and decentralized processes, providing a historical project repository accessible to students — for building professional portfolios — and to professors — for structured academic evaluation.

> _"Centralized platform for submission, deadline tracking, rubric-based feedback, and portfolio generation with achievement badges."_

The platform features specific profiles for **Students**, **Professors**, and **Coordinators/Administrators**, ensuring a structured workflow from project conception to final grade, with full submission traceability.

---

## 🚨 The Problem

<div align="center">

<img src="https://github.com/GrupoTP/Sistema-de-Envio-e-Armazenamento-dos-Projetos-ADS/blob/main/Problema.png" width="100%" alt="Slide: The Problem — 4 critical bottlenecks in the current process" />

</div>

The current process for delivering and evaluating Integrative Projects presents **4 critical bottlenecks**:

| # | Bottleneck | Impact |
|:---:|---|---|
| 1 | **Fragmentation** | Information scattered across multiple channels and tools |
| 2 | **Invisibility** | Projects with no institutional visibility or organized portfolio |
| 3 | **Rework** | Processes repeated manually every semester |
| 4 | **Lack of Governance** | Absence of control, traceability, and LGPD compliance |

> _"These bottlenecks cost time, visibility, and institutional credibility."_

---

## ✨ The Solution — Features

<div align="center">

<img src="https://github.com/GrupoTP/Sistema-de-Envio-e-Armazenamento-dos-Projetos-ADS/blob/main/Funcionalidades.png" width="100%" alt="Slide: System Features" />

</div>

We addressed the bottlenecks with a complete system organized in modules:

| Module | What it delivers |
|---|---|
| 🖥️ **Dashboard** | Overview of submissions, deadlines, and real-time status |
| 📁 **Projects** | File submission (PDF/ZIP), demo video, and description |
| 👤 **Profiles** | Management of Students, Professors, and Admins with distinct permissions |
| 🔐 **Authentication** | Single login per profile, primary and secondary email |
| 📊 **Reports** | Export of deliveries and evaluation history |
| 🌐 **Public Observatory** | Showcase of approved projects accessible institutionally |

---

## 🚀 System Differentials

<div align="center">

<img src="https://github.com/GrupoTP/Sistema-de-Envio-e-Armazenamento-dos-Projetos-ADS/blob/main/Funcionalidades%20Diferenciais.png" width="100%" alt="Slide: Differential Features of the Observatory" />

</div>

The Observatory was built with original features that make it unique within the academic context of Senac Recife College:

### 🔐 Authentication and Access
- **Multiple login authentication** — institutional email (primary) **or** student-chosen email (secondary), both functional for login
- **Profile selection screen** — users who hold multiple roles (Student, Professor, Administrator, Coordinator) choose which profile to use each session
- **Profile switching** — available only for users who have more than one registered profile

### 🛡️ Administration Rules
- **Mandatory minimum of 2 Admins/Coordinators** — the system blocks actions that would reduce active administrators/coordinators below 2, preventing a total lockout
- **Admin recovery** — special mechanism to restore access if all administrative accounts are lost
- **Admin-exclusive registration screen** — only the Administrator can create new users; Professors **do not have access** to the user registration screen
- **Activate / Deactivate profiles** — the Admin can suspend a profile without deleting it, preserving all linked history and data

### ⚙️ Settings and Personalization
- **Social Name** — can be registered and modified in settings, automatically reused throughout the system
- **Two registerable phone numbers** — users can register up to 2 contact numbers in settings, each with an option to flag as WhatsApp
- **Platform usage log** — account creation date and last login date displayed automatically on the settings screen

### 🧭 Navigation and Interface
- **Universal back icon** — present on all pages of all profiles, always returning to the Home page of the current profile
- **Floating menu on all pages** — accessible on any screen, displaying a header with the Senac icon and the name of the current Panel

### 📝 Forms and Validation
- **Visual indication of required fields** — every required field has a clear, immediate visual marker visible to the user, preventing submission errors

### 🎓 Resume and Portfolio
- **Dedicated Resume/Portfolio screen** for Professors and Students
- **Real-time preview** of the resume/portfolio, updated as the user fills in the fields
- **Per-field visibility option** — each piece of resume information can be configured to appear or not to recruiters
- **Option "I authorize SENAC partner companies to contact me"** on the resume
- **Skills in AI-scannable tag format** — keywords clearly highlighted for automatic skill identification

### 📊 Evaluations
- **Option for group or individual assessment**
- **Option to add more evaluation criteria and assessments**
- **Color-coded grades** by performance range
- **Grade filter** — from best to worst performance, with color-coded mention legend

### 🤝 Projects and Partnerships
- **Option "Authorize partner companies to view this project"** on the project submission screen

---

## 📐 Technical Specifications and Business Rules

### System Context

- Only the **Administrator** can create new user profiles for Professors and Students.
- **Professors cannot register new users** in the system and, consequently, **must not have access to the user registration screen**.
- **Every required field must have a visual indicator visible to the user**, indicating that it must be filled in.

---

### Login Screen

The login screen must contain:

**Required fields:**
- Email
- Password

**Usability features:**
- Option to **show/hide password** (eye icon)
- **Profile selection** for users with multiple roles:
  - Student
  - Professor
  - Administrator
  - Coordinator
- **Profile switching is only displayed** for users who have more than one registered profile

**Error messages:**
- Invalid credentials
- Empty required fields

---

### User Registration Rules

- User registration is done **only by the Administrator**.
- The Administrator can create profiles for: **Student**, **Professor**, **Administrator**, and **Coordinator**.
- Professors **cannot create** new users and must not have access to the user registration screen.
- **There must be at least 2 Administrators/Coordinators** registered and active in the system at all times.

**Permissions by profile:**

| Profile | Permissions |
|---|---|
| **Administrator / Coordinator** | Full system access |
| **Professor** | Restricted access — no permission to register users |
| **Student** | Access only to functions permitted for their profile |

---

### Required Registration Fields

Fields required when the Administrator registers a user:

| Field | Note |
|---|---|
| **Role** | Student / Professor / Administrator / Coordinator |
| **CPF (Tax ID)** | — |
| **First Name** | — |
| **Last Name** | — |
| **Social Name** | Not required, but can be filled in and reused throughout the system |
| **Institutional Email / Primary Email** | — |
| **Student ID** | Required for Students only |
| **Profile Status** | Active / Inactive |

---

### Optional Registration Fields

The fields below can be filled in or modified later in the profile settings:

- Identity document
- Date of birth
- Phone / mobile (2 options)
- ZIP code
- Full address (street, number, complement)
- Neighborhood
- City and state
- Country
- Profile photo

---

### Email Rules

| Rule | Detail |
|---|---|
| The **primary email** is the user's institutional email | — |
| The **primary email cannot be changed** by the user themselves | Only the Administrator can change it |
| The **secondary email is not required** at registration | — |
| The **secondary email can be changed** by the user themselves | Via the profile Settings screen |

---

### Profile Settings Screen

The **Profile Settings** area must allow:

- Editing and viewing all **optional** registration fields
- Viewing all **required** registration fields
- Uploading and modifying the **profile photo** (same one used in the resume)
- Editing the **secondary email** by the user themselves
- Editing personal data (**except primary email**, which only the Administrator can change)
- Display of the main profile data:
  - Role
  - Name and Social Name
  - CPF and Identity document
  - Emails (primary and secondary)
  - **Account creation date** and **last login** (auto-generated, view only)

---

### Resume/Portfolio Creation Screen

Available for **Professors** and **Students**. The user can edit all relevant information and see in real time how the resume/portfolio will appear to a potential employer.

> **Skill keywords** must be clearly highlighted (tags, chips, or blocks), so that an AI can immediately identify the candidate's abilities.

---

#### 👤 Personal Data and Contact

| Field | Required | Shared across the account |
|---|:---:|:---:|
| Full name | ✅ | ✅ |
| Social Name | — | ✅ |
| Primary phone (mobile) + WhatsApp field (yes/no) | ✅ | ✅ |
| Gender | ✅ | ✅ |
| Secondary phone + WhatsApp field (yes/no) | — | ✅ |
| Primary email | ✅ | Exclusive to this screen |
| Secondary email | — | Exclusive to this screen |
| City / State of residence | — | — |
| LinkedIn or other professional profile | — | With visibility option on resume |
| Website | — | With visibility option on resume |
| GitHub (link) | — | With visibility option on resume |
| Portfolio (links) | — | With visibility option on resume |
| Profile photo | — | With visibility option on resume |
| Permission for companies to contact | — | Explicit authorization: Yes / No |
| Country and Nationality | ✅ | — |

---

#### 🕐 Contact Hours and Availability

- Best time to be contacted: up to **4 time slots per day** (7 days a week), with day selection and option to repeat the block for different combinations
- Willingness to relocate (Yes/No)
- Willingness to travel (Yes/No)

---

#### 🌈 Diversity

Multiple choice field with individual visibility option per item on the resume:

- LGBTQIA+
- Woman
- PwD – Person with Disability
- Black
- Mixed-race (Pardo)
- Indigenous

---

#### 💼 Type of Work Sought

**Employment type (multiple choice):** Young Apprentice · Internship · Trainee · Full-time (CLT) · Contractor (PJ) · Freelancer · Project-based · Temporary

**Work mode (multiple choice):** On-site · Hybrid · 100% Remote

**Available working hours (multiple choice):**
- Daytime
- Nighttime
- Weekends
- Monday to Friday
- From ___ to ___ from ___ to ___ *(free field: weekday + time)*

**Availability period:** free text field (e.g.: *"starting July 2026"*)

**Salary expectation** (optional, multiple choice — each option with configurable visibility):
- Stipend to cover transportation and meals
- Open to offers starting from _____
- Desired salary range: _____ to _____
- I want to gain practical experience in the field

---

#### 📝 About (Resume Summary)

Free text field with **up to 2,600 characters**, including:
- Visible character counter (used / total)
- Placeholder: *"Summarize your experience by describing and highlighting what is important in your resume and about you, with a professional focus and goals. Remember, this is a highlight field for recruiters to read and you have 2,600 characters"* — disappears when clicked to write

---

#### 1. Education Level and Academic Background

| Field | Note |
|---|---|
| Education level | High School, Technical, Undergraduate, Bachelor's, Technologist, Graduate, Post-Graduate lato/stricto sensu, Master's, Doctorate, MBA, Specialization, Adult Education (EJA), Special Education, Technical Professional Education |
| Course | Free text (e.g.: "IT Technician", "Software Engineering") |
| Educational institution | — |
| Current period or "graduated in ___" | — |
| Status | Enrolled / Completed / On Hold / Transferring |
| Expected graduation | Month/Year |
| Show on resume | Yes / No — per entry |

---

#### 2. Professional Experience and Internships

| Field | Note |
|---|---|
| Company or project | — |
| Position / role | — |
| Start and end period | — |
| Type | Internship / Non-mandatory internship / Volunteering / Extension project / Freelancer / Full-time (CLT) |
| Brief description of activities and results | — |
| Show on resume | Yes / No — per entry |

---

#### 3. Licenses and Certificates

| Field | Note |
|---|---|
| Certificate/license name | — |
| Institution / platform | — |
| Date obtained | — |
| Valid until | If applicable |
| Show on resume | Yes / No — per entry |

---

#### 4. Projects

| Field | Note |
|---|---|
| Project name | — |
| Project description | — |
| Responsibilities / role | — |
| Technologies / tools used | — |
| Result / impact | — |
| Project link | GitHub, website, video, presentation, etc. |
| Show on resume | Yes / No — per entry |

---

#### 5. Other Courses

| Field | Note |
|---|---|
| Course name | — |
| Institution / platform | e.g.: Alura, Udemy, FIAP |
| Completion date | — |
| Show on resume | Yes / No — per entry |

---

#### 6. Skills

- **Hard Skills / Technical skills:** free text fields with level selection (basic, intermediate, advanced, fluent); includes a specific "Languages / tools" field (e.g.: Python, Excel, Figma, JavaScript)
- **Soft Skills / Behavioral skills:** free text fields (e.g.: leadership, communication, teamwork)
- Each skill must be displayed in **tag/chip format**, easily scannable by AI

---

#### 7. Languages

| Field | Options |
|---|---|
| Language | Free text |
| Level | Beginner · Basic · Intermediate · Advanced · Fluent · Native |

---

## 🎨 Grading System

Grades displayed to students use **color-coded visual encoding** and a **sort filter from best to worst**, making results more intuitive and accessible to read.

| Code | Description | Range | Color |
|:---:|---|:---:|:---:|
| **AE** | Attended with Excellence | 9.5 — 10 | 🟢 GREEN |
| **O** | Outstanding | 8.0 — 9.4 | 🔵 BLUE |
| **B** | Good | 6.5 — 7.9 | 🟡 YELLOW |
| **ANS** | Not Yet Sufficient | 4.0 — 6.4 | 🟠 ORANGE |
| **I** | Insufficient | 0.0 — 3.9 | 🔴 RED |

---

## 🌱 ESG Impact

<div align="center">

<img src="https://github.com/GrupoTP/Sistema-de-Envio-e-Armazenamento-dos-Projetos-ADS/blob/main/ESG.png" width="100%" alt="Slide: ESG Impact of the Project" />

</div>

The Integrative Projects Observatory was conceived with responsibility across three dimensions:

| Dimension | Action |
|---|---|
| 🌿 **Environmental (E)** | Eliminates physical printouts and redundant emails; fully digitalizes the academic workflow |
| 🤝 **Social (S)** | Generates an official digital portfolio for students, expanding professional opportunities |
| 🏛️ **Governance (G)** | LGPD compliance, profile-based access control, and integrated audit logs |

---

## 📈 Market

<div align="center">

<img src="https://github.com/GrupoTP/Sistema-de-Envio-e-Armazenamento-dos-Projetos-ADS/blob/main/Mercado.png" width="100%" alt="Slide: Market Analysis" />

</div>

- 💰 By 2025, the market invested **US$ 340 million** in the educational technology sector
- 🌎 Brazil holds a prominent position in the **World Digital Education Ranking**
- 🏫 Senac has more than **500 units** in Brazil — making the Observatory a **highly replicable solution** at a national scale

---

## 🔍 Benchmark

<div align="center">

<img src="https://github.com/GrupoTP/Sistema-de-Envio-e-Armazenamento-dos-Projetos-ADS/blob/main/Benchmark.png" width="100%" alt="Slide: Benchmark — Why the Observatory?" />

</div>

### Why build the Observatory instead of using existing tools?

| Criterion | Google Classroom | Moodle | GitHub + Drive | ✅ **Observatory** |
|---|:---:|:---:|:---:|:---:|
| Focus on integrative projects | ❌ | ❌ | ❌ | ✅ |
| Public portfolio | ❌ | ❌ | Partial | ✅ |
| Multiple profiles with permissions | Partial | Partial | ❌ | ✅ |
| Native LGPD compliance | ❌ | ❌ | ❌ | ✅ |
| Integrated management (submission + validation + evaluation) | ❌ | Partial | ❌ | ✅ |

> _The Observatory surpasses generic tools in institutional focus, governance, and portfolio._

---

## 💼 Business Model

<div align="center">

<img src="https://github.com/GrupoTP/Sistema-de-Envio-e-Armazenamento-dos-Projetos-ADS/blob/main/Modelo%20de%20Neg%C3%B3cio.png" width="100%" alt="Slide: Business Model" />

</div>

**Value delivered to Senac:**
- Significant reduction in semester rework during evaluation processes
- Expansion potential as a **replicable product** for other units (SaaS model)

**Value delivered to Students:**
- Official and traceable portfolio linked to the institution
- Visibility to **partner companies** through the public Observatory

---

## 🎯 Target Audience

<div align="center">

<img src="https://github.com/GrupoTP/Sistema-de-Envio-e-Armazenamento-dos-Projetos-ADS/blob/main/P%C3%BAblico%20Alvo.png" width="100%" alt="Slide: Target Audience" />

</div>

> _"Transforming academic management into institutional intelligence."_

The Integrative Projects Observatory was designed for three complementary profiles within Senac Recife College:

<details>
<summary><strong>🎓 Student</strong></summary>

- Age range: 18 to 45 years
- Uploads files, adds a video link and project description
- Tracks submission approval status in real time
- Views professor feedback and final grade (with color coding and sort filter)
- Builds and shares a professional resume/portfolio with real-time preview
- Semester-based use, concentrated during submission periods

</details>

<details>
<summary><strong>👩‍🏫 Professor</strong></summary>

- Age range: 25 to 65 years
- Accesses the list of projects approved by the Coordinator/Administrator
- Evaluates by rubric: Functionality, Documentation, and Creativity (0 to 10)
- Provides detailed feedback comments
- Access to historical repository for academic reference
- **Does not have access to the user registration screen**
- Semester-based use, during the evaluation period

</details>

<details>
<summary><strong>🏛️ Coordinator / Administrator</strong></summary>

- Age range: 30 to 60 years
- Validates submissions: approves or rejects projects for evaluation
- Registers, edits, and manages student and professor profiles
- Activates and deactivates profiles without permanently deleting them
- Only one with permission to change a user's primary email
- Ensures there are always at least 2 active Administrators/Coordinators
- Continuous use, with greater intensity during submission periods

</details>

---

## ⚖️ Legislation and Compliance

The system was developed in full compliance with current Brazilian legislation:

- 🔒 **LGPD — Law No. 13.709/2018** · Protection of personal data for students and professors, with audit logs, access control, and consent for sensitive data
- 🌐 **Marco Civil da Internet — Law No. 12.965/2014** · Storage of access records and user privacy
- 🎓 **LDB — Law No. 9.394/1996** · Educational guidelines and confidentiality of academic data
- ✍️ **Copyright Law — Law No. 9.610/1998** · Protection of authorship of projects submitted by students
- 🏫 **Internal Policies of Senac Recife College** · Academic regulations and institutional IT policies

---

## 🛠️ Technologies

<div align="center">

<img src="https://github.com/GrupoTP/Sistema-de-Envio-e-Armazenamento-dos-Projetos-ADS/blob/main/Encerramento%20.png" width="100%" alt="Slide: Closing — Tech Stack" />

</div>

The platform centralizes submission, validation, and evaluation of Integrative Projects, developed with full LGPD compliance using the following technologies:

<div align="center">

![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![YouTrack](https://img.shields.io/badge/YouTrack-000000?style=for-the-badge&logo=youtrack&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

</div>

| Layer | Technology |
|---|---|
| **Backend** | PHP |
| **Frontend** | HTML + Bootstrap |
| **Database** | MySQL |
| **Project Management** | [YouTrack](https://grupotp.youtrack.cloud/projects) |
| **Design / Prototyping** | [Figma / FigmaMaker](https://www.figma.com/make/XETVIneDIARTVrgXoidrN4/OBSERVAT%C3%93RIO-DE-PROJETOS-INTEGRADORES--SENAC-?fullscreen=1&t=vf5Kz8t2XzB1XtNc-1&code-node-id=0-10) |
| **Version Control** | Git / GitHub |
| **Security** | HTTPS, profile-based authentication, LGPD compliance |

---

## 🖥️ Prototype and Team

<div align="center">

<img src="https://github.com/GrupoTP/Sistema-de-Envio-e-Armazenamento-dos-Projetos-ADS/blob/main/EquipeProtótipo.png" width="100%" alt="Slide: Team and Prototype" />

</div>

The high-fidelity prototype was developed in **FigmaMaker**, covering all main flows for each user profile.

<div align="center">

[![View Prototype on Figma](https://img.shields.io/badge/View%20Prototype%20on%20Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)](https://www.figma.com/make/XETVIneDIARTVrgXoidrN4/OBSERVAT%C3%93RIO-DE-PROJETOS-INTEGRADORES--SENAC-?fullscreen=1&t=vf5Kz8t2XzB1XtNc-1&code-node-id=0-10)

[![View Repository on GitHub](https://img.shields.io/badge/View%20Repository%20on%20GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Polyana-Fontes/Observatorio-de-Projetos-Integradores)

</div>

---

## 🔑 Default Demo Credentials

Credentials valid for [Figma / FigmaMaker](https://www.figma.com/make/XETVIneDIARTVrgXoidrN4/OBSERVAT%C3%93RIO-DE-PROJETOS-INTEGRADORES--SENAC-?fullscreen=1&t=vf5Kz8t2XzB1XtNc-1&code-node-id=0-10) and for the Integrative Projects Observatory Application — Senac Recife · 2026

> 🌐 Scheduled application: [https://grupotp.polyclub.com.br/](https://grupotp.polyclub.com.br/)

| Profile | Email | Password |
|---|---|---|
| Student | aluno@aluno | senac123 |
| Partner | parceiro@parceiro | senac123 |
| Student 2 | aluno2@aluno | senac123 |
| Professor | professor@professor | senac123 |
| Administrator | admin@admin | senac123 |

---

## 👩‍💻 Team

<div align="center">

### Polyana Fontes
**Full Stack Developer · Database Modeling · Technical Documentation**

Student of Systems Analysis and Development
Senac Recife-PE College

---

### Thayná Batista da Silva
**Project Manager / Requirements Analyst · Scrum Master**
**Product Designer · High-Fidelity Prototyping (Figma)**

Student of Systems Analysis and Development
Senac Recife-PE College · Class of 2025 · Expected graduation: 2027

</div>

---

## 📬 Contact
Want to learn more about the project or get in touch? 🤝

<div align="center">

### Polyana Fontes

<a href="https://github.com/Polyana-Fontes" target="_blank">
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
</a>

---

### Thayná Batista da Silva

  <a href="https://br.linkedin.com/in/thaynabds" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  
  <a href="https://www.instagram.com/thaynabdstec/" target="_blank">
    <img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" />
  </a>

📧 **Email:** [thaynabdstec@gmail.com](mailto:thaynabdstec@gmail.com) ✉️

📱 **Phone:** +55 (81) 97912-6121 📞

---

<div align="center">

### 👤 Thayná Batista da Silva
**Scrum Master • Product Designer • Requirements Analyst** 💼

Senac Recife-PE Faculty | Systems Analysis and Development 🎓

![TEC Card Thayná](https://github.com/thaynabds/AppMedSmart/blob/main/CapaCartão%20ThaynáBDSTEC.png)

</div>

</div>

---

## 📄 License

<div align="center">

**Copyright © 2026, Polyana Fontes; Thayná Batista da Silva — Integrative Projects Observatory. All rights reserved.**

Made with 💜 by **Thayná Batista da Silva** and **Polyana Fontes**
during the **Systems Analysis and Development** program
**Senac Recife College · 2026**

*Curricular Component: Requirements Engineering · Instructor: Sonia Gomes de Oliveira*

</div>

<div align="center">

⬆️ <a href="README.md">Back to language selector</a>

</div>
