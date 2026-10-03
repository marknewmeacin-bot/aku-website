# 🌐 AKU Website

A modern and responsive website built for **AKU (Aryabhatta Knowledge University)** using **Next.js**. The project provides a clean, structured, and user-friendly web interface for presenting university-related information and digital content.

## 🚀 Features

* 🎨 Modern and responsive user interface
* 📱 Mobile, tablet, and desktop support
* ⚡ Fast performance with Next.js
* 🧭 Easy and intuitive navigation
* 🏫 University information sections
* 📚 Academic and educational content
* 📢 Important announcements and information
* 📞 Contact and information sections
* 🖼️ Optimized images and assets
* 🔤 Optimized fonts using Next.js
* ♻️ Component-based architecture
* 🔧 Easy to maintain and extend

## 🛠️ Technologies

* **Next.js**
* **React**
* **TypeScript**
* **Tailwind CSS / CSS**
* **JavaScript**
* **HTML5**
* **Git & GitHub**

## 📂 Project Structure

```text
aku-website/
│
├── app/
│   ├── layout.tsx
│   ├── page.tsx
│   └── ...
│
├── components/
│   └── ...
│
├── public/
│   ├── images/
│   └── ...
│
├── styles/
│   └── ...
│
├── package.json
├── tsconfig.json
├── next.config.ts
├── .gitignore
└── README.md
```

> The exact structure may change as the project develops.

## 💻 Getting Started

### Prerequisites

Make sure you have the following installed:

* **Node.js**
* **npm**

You can check your versions with:

```bash
node -v
npm -v
```

## 📥 Installation

Clone the repository:

```bash
git clone https://github.com/marknewmeacin-bot/aku-website.git
```

Navigate to the project:

```bash
cd aku-website
```

Install dependencies:

```bash
npm install
```

## ▶️ Run the Development Server

Start the development server:

```bash
npm run dev
```

Open your browser and visit:

```text
http://localhost:3000
```

The website will automatically update when you make changes to the source files.

## ✏️ Development

The main homepage can be edited from:

```text
app/page.tsx
```

The main application layout can be edited from:

```text
app/layout.tsx
```

Reusable UI components can be maintained inside:

```text
components/
```

Static assets such as images can be placed inside:

```text
public/
```

## 📦 Available Scripts

### Development

```bash
npm run dev
```

Runs the application in development mode.

### Production Build

```bash
npm run build
```

Creates an optimized production build.

### Start Production Server

```bash
npm start
```

Runs the production build.

### Lint

```bash
npm run lint
```

Checks the project for code and formatting issues if configured.

## 🏗️ Build for Production

Before deploying the website, create a production build:

```bash
npm run build
```

Then start it with:

```bash
npm start
```

## 🌍 Deployment

This Next.js project can be deployed using platforms such as **Vercel** or other services that support Next.js applications.

For Vercel deployment:

1. Push the project to GitHub.
2. Sign in to Vercel.
3. Import the GitHub repository.
4. Configure environment variables if required.
5. Deploy the project.

## 🔐 Environment Variables

If the project requires environment variables, create a:

```text
.env.local
```

file.

Example:

```env
NEXT_PUBLIC_API_URL=your_api_url
```

**Do not commit `.env.local` or other files containing secrets to GitHub.**

## 📸 Screenshots

Add screenshots of your website here as the project develops.

Example:

```markdown
![AKU Website Homepage](public/images/homepage.png)
```

## 🔄 Git Workflow

After making changes:

```bash
git add .
git commit -m "Update AKU website"
git push
```

## 🎯 Project Objective

The objective of this project is to develop a modern, responsive, and maintainable university website using Next.js and modern web development practices.

## 👨‍💻 Developer

**Mark Newme**

BCA Student | Web Developer | AI Enthusiast

GitHub:
https://github.com/marknewmeacin-bot

## 📄 License

This project is developed for educational and development purposes.

---

⭐ If you find this project useful, consider giving the repository a star!
