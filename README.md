<h1 align="center">G Soma Shekar | Portfolio</h1>

<p align="center">
  <strong>Personal portfolio of a Computer Science graduate focused on Python, data science, and machine learning</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Next.js-16-black?style=for-the-badge&logo=next.js" alt="Next.js 16">
  <img src="https://img.shields.io/badge/React-Frontend-blue?style=for-the-badge&logo=react" alt="React">
  <img src="https://img.shields.io/badge/Tailwind_CSS-Styling-38B2AC?style=for-the-badge&logo=tailwind-css" alt="Tailwind CSS">
  <img src="https://img.shields.io/badge/Deployed_on-Vercel-black?style=for-the-badge&logo=vercel" alt="Vercel">
</p>

<p align="center">
  <a href="#about-me">About</a> •
  <a href="#live-demo">Live Demo</a> •
  <a href="#features">Features</a> •
  <a href="#projects">Projects</a> •
  <a href="#skills">Skills</a> •
  <a href="#getting-started">Getting Started</a> •
  <a href="#deployment">Deployment</a> •
  <a href="#contact">Contact</a>
</p>

---

## About Me

I'm a Computer Science and Engineering graduate with a strong interest in Python programming, data science, machine learning, and emerging technologies. I enjoy building practical projects, analysing data, solving problems, and exploring innovative solutions through technology. I'm passionate about continuous learning and eager to apply my skills to real-world challenges while growing as a technology professional.

📍 Hyderabad, Telangana, India

---

## Live Demo

🚀 **[View my portfolio](https://YOUR-VERCEL-ADDRESS.vercel.app)**

---

## Features

- ✅ **Modern tech stack:** built with Next.js, React, and Tailwind CSS
- ✅ **Fully responsive:** works on phones, tablets, and desktops
- ✅ **SEO friendly:** page title and description set through the Next.js metadata API
- ✅ **Fast:** server components and optimised images
- ✅ **Data driven:** all content lives in simple files under `utils/data/`
- ✅ **Working contact form:** messages are delivered to my Gmail inbox
- ✅ **Dark theme:** gradient design with animated elements

---

## Sections

| Section | Description |
| --- | --- |
| 🦸 **Hero** | Introduction with links to my social profiles and resume |
| 👤 **About** | Short professional summary |
| 🛠️ **Skills** | Technologies I work with |
| 🚀 **Projects** | Selected projects with descriptions and GitHub links |
| 🎓 **Education** | Academic background |
| 📧 **Contact** | Contact form, email, and social links |

---

## Projects

### 1. AI-Powered Intelligent Threat Detection
**Tech:** Python, Scikit-learn, Pandas, Flask

- Automated framework that analyses network traffic, processes the data, and identifies security risks.
- Random Forest model trained with Scikit-learn to classify network threats and reduce false reports.
- Flask and HTML dashboard to track traffic metrics and display security updates.

🔗 [Source code](https://github.com/G-Soma-Shekar/AI-Powered-Threat-Intelligence-System)

### 2. Stock Prediction Models
**Tech:** Python, Machine Learning, Deep Learning, TensorFlow

- Stock price prediction models using LSTM, GRU, CNN, and Random Forest.
- Data analysis, ensemble learning, and trading simulations to explore market trends and prediction strategies.

🔗 [Source code](https://github.com/G-Soma-Shekar/Stock-Prediction-Models)

### 3. DayTodayNews: News Web Application
**Tech:** React.js, JavaScript, HTML, CSS, NewsAPI

- Responsive news app that shows real-time news across multiple categories.
- Category-based navigation and infinite scrolling for a smooth reading experience.

🔗 [Source code](https://github.com/G-Soma-Shekar/DayTodayNews)

---

## Skills

| Area | Technologies |
| --- | --- |
| **Languages** | Python, Java, C, JavaScript, SQL |
| **Machine Learning** | Machine Learning, Deep Learning, TensorFlow, Scikit-learn, LSTM, GRU, CNN, Random Forest |
| **Data** | Pandas, NumPy |
| **Web** | HTML, CSS, React.js, Flask, REST APIs |
| **Databases** | MySQL, DBMS |
| **Tools and concepts** | Git, GitHub, Object-Oriented Programming (OOP), Microsoft 365 |

---

## Education

| Qualification | Institution | Period | Score |
| --- | --- | --- | --- |
| B.Tech in Computer Science Engineering (JNTUH) | Malla Reddy College of Engineering and Technology (MRCET), Hyderabad | Nov 2022 – Apr 2026 | CGPA 7.85/10 |
| Intermediate (MPC), TSBIE | Vishwa Shanthi Junior College, Gadwal, Telangana | Jun 2020 – May 2022 | 81.4% |
| SSC, TSBSE | Vishwa Shanthi High School, Gadwal, Telangana | Mar 2020 | CGPA 10/10 |

---

## Tech Stack

| Technology | Purpose |
| --- | --- |
| **Next.js** | React framework with the App Router |
| **React** | UI components |
| **Tailwind CSS** | Utility-first styling |
| **Lottie** | Lightweight animations |
| **Nodemailer** | Sending contact form emails through Gmail |
| **Axios** | HTTP requests |
| **Vercel** | Hosting and automatic deployments |

---

## Getting Started

### Prerequisites

| Tool | Download |
| --- | --- |
| **Node.js** (LTS) | [nodejs.org](https://nodejs.org/en/download/) |
| **Git** | [git-scm.com](https://git-scm.com/downloads) |

Check your installs:

```bash
node --version
npm --version
git --version
```

### 1. Clone the repository

```bash
git clone https://github.com/G-Soma-Shekar/my-portfolio.git
cd my-portfolio
```

### 2. Install dependencies

```bash
npm install
```

### 3. Set up environment variables

```bash
cp .env.example .env
```

On Windows Command Prompt, use `copy .env.example .env` instead. Then fill in `.env` (see below).

### 4. Run the development server

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

---

## Environment Variables

Create a `.env` file in the project root:

```env
# Public address of the site (use http://localhost:3000 while developing)
NEXT_PUBLIC_APP_URL=https://YOUR-VERCEL-ADDRESS.vercel.app

# Gmail account that receives messages from the contact form
EMAIL_ADDRESS=your_email@gmail.com

# Google App Password (16 characters, not your normal Gmail password)
GMAIL_PASSKEY=your_app_password
```

| Variable | Required | Description |
| --- | --- | --- |
| `NEXT_PUBLIC_APP_URL` | Yes | Public URL of the site; the contact form posts to this address |
| `EMAIL_ADDRESS` | Yes | Gmail address that receives contact form messages |
| `GMAIL_PASSKEY` | Yes | Gmail App Password used to send the email |
| `TELEGRAM_BOT_TOKEN` | No | Optional: also forward messages to Telegram |
| `TELEGRAM_CHAT_ID` | No | Optional: Telegram chat that receives the messages |

> ⚠️ Never commit your `.env` file. It is already listed in `.gitignore`.

### Creating a Gmail App Password

1. Open your [Google Account](https://myaccount.google.com/) and turn on **2-Step Verification**.
2. Search for **App passwords** in the account search bar and open it.
3. Create a new app password and copy the 16-character code.
4. Paste it into `GMAIL_PASSKEY` without spaces.

---

## Customising the Content

All content is stored in `utils/data/`:

| File | Purpose |
| --- | --- |
| `personal-data.js` | Name, role, bio, email, location, social links, resume link |
| `projects-data.js` | Projects with descriptions, tools, and links |
| `skills.js` | Skills shown with icons |
| `educations.js` | Education entries |
| `experience.js` | Work experience entries |
| `contactsData.js` | Contact details |

Replace the profile photo by saving a new image as `public/profile.png`.

---

## Deployment

### Deploy to Vercel

1. Push this repository to GitHub.
2. Sign in at [vercel.com](https://vercel.com/) with GitHub.
3. Click **Add New → Project** and import `my-portfolio`.
4. Add the environment variables listed above.
5. Click **Deploy**.

Set `NEXT_PUBLIC_APP_URL` to the final Vercel address and redeploy once, because this value is read at build time. After that, every `git push` to `main` deploys automatically.

### Run with Docker

```bash
docker-compose up --build
```

The site is then available at [http://localhost:3000](http://localhost:3000).

---

## Troubleshooting

<details>
<summary><strong>Port 3000 is already in use</strong></summary>

Close any other terminal running `npm run dev`, or start on another port:

```bash
npx next dev -p 3001
```

</details>

<details>
<summary><strong>Environment variables are not working</strong></summary>

- Make sure `.env` is in the project root.
- Restart the dev server after changing it.
- On Vercel, add the variables in **Settings → Environment Variables** and redeploy.

</details>

<details>
<summary><strong>Profile photo shows an old image</strong></summary>

- Check that the file is saved as `public/profile.png`.
- Delete the `.next` folder, restart `npm run dev`, and hard-refresh the browser with `Ctrl + Shift + R`.

</details>

<details>
<summary><strong>Contact form is not sending emails</strong></summary>

- Confirm 2-Step Verification is on and the App Password is typed without spaces.
- Confirm `EMAIL_ADDRESS` is the same Gmail account the App Password was created for.
- Confirm `NEXT_PUBLIC_APP_URL` matches the address you are using.
- Check the terminal (or Vercel logs) for the exact error message.

</details>

---

## Contact

- 📧 Email: [gadigesomashekargss@gmail.com](mailto:gadigesomashekargss@gmail.com)
- 💼 LinkedIn: [linkedin.com/in/gadigesomashekar](https://www.linkedin.com/in/gadigesomashekar)
- 💻 GitHub: [github.com/G-Soma-Shekar](https://github.com/G-Soma-Shekar)
- 🧩 LeetCode: [leetcode.com/u/gadigesomashekar](https://leetcode.com/u/gadigesomashekar/)
- 🐦 X: [x.com/g__somashekar](https://x.com/g__somashekar)

---

## License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

---

<p align="center">© 2026 G Soma Shekar. All rights reserved.</p>
