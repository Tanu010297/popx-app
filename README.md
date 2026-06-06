# PopX App

A pixel-perfect React implementation of the PopX mobile app UI — built as a qualifier task for an internship assignment.

## 🔗 Live Demo

[Hosted on Vercel](#) <!-- Replace with your Vercel URL after deployment -->

## 📱 Screens

| Screen | Route | Description |
|--------|-------|-------------|
| Landing | `/` | Welcome screen with two CTA buttons |
| Login | `/login` | Email + password sign in form |
| Create Account | `/create-account` | Registration form with 5 fields + agency toggle |
| Account Settings | `/account-settings` | User profile and bio display |

## 🛠 Tech Stack

- **React 18** — UI library
- **React Router v6** — client-side routing
- **CSS Modules** — per-screen stylesheets
- **Rubik** — Google Font used throughout

## 🚀 Getting Started

```bash
# Install dependencies
npm install

# Start development server
npm start

# Build for production
npm run build
```

## 📁 Project Structure

```
src/
├── pages/
│   ├── LandingScreen.js / .css
│   ├── LoginScreen.js / .css
│   ├── CreateAccountScreen.js / .css
│   └── AccountSettingsScreen.js / .css
├── App.js          # Router setup
├── index.js        # Entry point
└── index.css       # Global styles & design tokens
```

## 🎨 Design

Faithfully implemented from the Adobe XD design:
[View Design](https://xd.adobe.com/view/b68eea25-003d-4a5d-8fdd-d463eeb20b32-e3dd)

## 📦 Deployment

Deploy to Vercel in one command:

```bash
npx vercel --prod
```
