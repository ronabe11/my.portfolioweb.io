**review link** https://ronabe11.github.io/my.portfolioweb.io/

🌐 Developer Portfolio – README

A modern, animated, and responsive Developer Portfolio Website built with HTML, Tailwind CSS, and vanilla JavaScript.
This portfolio showcases professional experience, skills, selected projects, and an interactive contact section—designed with a clean glass-morphism style and smooth UI animations.

🚀 Features
✨ Fully Responsive UI

Designed to look great on all devices—mobile, tablet, and desktop.

🎨 Modern Visual Design

Glassmorphism cards

Gradient highlights

Smooth hover effects and glowing components

Stylish hero section with animated background shapes

🛠️ Project Filtering

Users can filter displayed projects by category:

All

Web

Mobile

💬 Interactive Contact Form

A demo form that:

Captures form data locally

Displays a success message

Scrolls intelligently when triggered via project buttons

📁 Animated Components

Page sections reveal nicely on scroll using IntersectionObserver.

🔄 Theme Glow Toggle

A small glow effect toggle to adjust UI intensity.

🧱 Tech Stack
Technology	Purpose
HTML5	Core website structure
Tailwind CSS (CDN)	Utility-first styling
JavaScript (Vanilla)	Filtering, modal previews, form handling
LocalStorage	Temporary storage for demo messages
SVG Icons	Clean and scalable icons for social links
📂 Project Structure
├── Index-2.html      # Main portfolio file (uploaded)
├── assets/           # (Optional) for future images or scripts
└── README.md         # Project documentation

📸 Sections Included
1️⃣ Hero Section

Introduction

Dynamic code preview card

Quick stats (Years, Projects, Awards)

2️⃣ Selected Work

3 customizable project cards

Preview modal

"Work with me" project type auto-fill

3️⃣ About Me

Personal description

Experience timeline with years and roles

4️⃣ Skills

Frontend, Backend, Tooling categories

Progress bars for proficiency

5️⃣ Contact

Demo contact form

Auto-selected options based on project clicked

Local storage save

6️⃣ Footer

Social icons

Year auto-update

📥 How to Use / Modify
🔧 Run Locally

Download the project

Open Index-2.html in any browser

Everything works without installation (CDN-based)

📝 Editing Text

Look for the following areas in the HTML:

Developer Name

Roles & headings

Project descriptions

Social media links

🎨 Customizing Colors

Colors are stored under the :root variable:

:root {
  --bg: #0b1020;
  --bg-soft: #121936;
  --card: rgba(255,255,255,0.06);
  --text: #e8ecff;
  --primary: #7c8cff;
  --accent: #66e4c6;
}


Modify these to create your own theme.

📦 Deployment

You can deploy this site using:

🌐 GitHub Pages

Push your repo

Go to Settings ➝ Pages

Choose main branch → root

Save

☁️ Netlify

Drag & drop the folder

Deploy instantly

⚡ Vercel

Import your GitHub repo

Automatic build (no config needed)

🤝 Contributing

Feel free to fork the project and create pull requests for enhancements.

📜 License

This project is free to use and customize for personal portfolio purposes.
