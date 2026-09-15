# Premium Developer Portfolio Website

A premium, single-page, fully responsive dark-mode portfolio website highlighting technical capabilities, professional expertise, and career progression.

## 🚀 Features

- **Premium UI/UX Theme**: Built around a deep slate-gray layout (`#0B0F19`) featuring subtle glassmorphic styling, neon gradient text highlights, and glowing accents.
- **Glassmorphic Navigation Header**: A sticky navbar with backdrop-blur effects and an animated, responsive mobile dropdown menu.
- **Interactive Channels Grid**: A grid of contact cards for direct connections (WhatsApp, GitHub, LinkedIn, and Email).
- **Visual Timeline**: A glowing vertical experience timeline charting roles, achievements, and tech stacks.
- **Interactive Skills Grid**: Categorized tags for programming languages, platforms/tools, and methodologies.
- **Micro-Animations**: Scroll-reveal animations driven by a lightweight Intersection Observer, magnetic hover effects on buttons, and smooth custom transitions.
- **Zero-Dependency Icons**: Inline vector SVGs for all social and technical indicators to ensure instant loading and 100% rendering reliability.

## 📂 File Structure

```text
portfolio/
├── index.html        # Main webpage containing all HTML structure, Tailwind configurations, and vanilla JavaScript logic
├── profile.jpg       # Local profile photograph (referenced in the Hero section wrapper)
└── README.md         # Project documentation (this file)
```

## 🛠️ How to Deploy & Customize

### 1. Run Locally
Simply double-click the `index.html` file to open it in any modern web browser, or launch a simple local development server (e.g., Live Server in VS Code, or python `python -m http.server 8000`).

### 2. Update Personal Details & Links
Open `index.html` in a text editor to update your details:
- **Name**: Search for current name headers (e.g., `Kumareshan Balaraja`) and replace them with your name.
- **WhatsApp Link**: Search for the WhatsApp link and replace the number (e.g., `https://wa.me/YOUR_PHONE_NUMBER`).
- **GitHub Link**: Search for the GitHub link and replace the username (e.g., `https://github.com/YOUR_GITHUB_USERNAME`).
- **LinkedIn Link**: Search for the LinkedIn link and replace the username (e.g., `https://www.linkedin.com/in/YOUR_LINKEDIN_USERNAME`).
- **Email**: Search for the email string and replace it with your email (e.g., `YOUR_EMAIL@example.com`).

### 3. Change Profile Photo
To change the avatar, replace the `profile.jpg` file in this directory with your own photo. Ensure the filename matches `profile.jpg` exactly.
