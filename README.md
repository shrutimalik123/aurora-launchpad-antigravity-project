# 🚀 Aurora Launchpad

A stunning, modern landing page built with React, Vite, and Tailwind CSS v4. Features beautiful animations, glassmorphism effects, and a premium dark theme design.

![Aurora Launchpad](https://img.shields.io/badge/React-19.2.0-61dafb?style=for-the-badge&logo=react)
![Vite](https://img.shields.io/badge/Vite-7.2.2-646cff?style=for-the-badge&logo=vite)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-4.1.17-38bdf8?style=for-the-badge&logo=tailwindcss)

## ✨ Features

- 🎨 **Premium Design** - Modern dark theme with vibrant accent colors and smooth gradients
- 🌊 **Smooth Animations** - Powered by Framer Motion for fluid, engaging interactions
- 💎 **Glassmorphism UI** - Beautiful frosted glass effects and backdrop blur
- 📱 **Fully Responsive** - Optimized for all screen sizes
- ⚡ **Lightning Fast** - Built with Vite for instant hot module replacement
- 🎯 **Interactive Elements** - Smooth scroll navigation and hover effects

## 🛠️ Tech Stack

- **React 19.2.0** - Latest React with modern features
- **Vite 7.2.2** - Next-generation frontend tooling
- **Tailwind CSS 4.1.17** - Utility-first CSS framework
- **Framer Motion 12.23.24** - Production-ready animation library
- **PostCSS & Autoprefixer** - CSS processing and vendor prefixing

## 🚀 Getting Started

### Prerequisites

- Node.js (v18 or higher recommended)
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone <your-repo-url>
cd aurora-launchpad
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

4. Open your browser and navigate to `http://localhost:5173` (or the port shown in your terminal)

## 📜 Available Scripts

- `npm run dev` - Start development server with hot reload
- `npm run build` - Build for production
- `npm run preview` - Preview production build locally
- `npm run lint` - Run ESLint to check code quality

## 🎨 Customization

### Colors

The color scheme is defined in `tailwind.config.js`:

```javascript
colors: {
  background: '#0D0D0D',  // Main background
  accent: '#00FFFF',       // Cyan accent
  secondary: '#A793FF',    // Purple secondary
}
```

### Fonts

The project uses **Inter** from Google Fonts. You can change this in `tailwind.config.js`:

```javascript
fontFamily: {
  sans: ['Inter', 'sans-serif'],
}
```

## 📁 Project Structure

```
aurora-launchpad/
├── src/
│   ├── components/
│   │   ├── Header.jsx      # Navigation header
│   │   ├── Hero.jsx        # Hero section with CTA
│   │   └── Features.jsx    # Features showcase
│   ├── App.jsx             # Main app component
│   ├── index.css           # Global styles & Tailwind imports
│   └── main.jsx            # App entry point
├── public/                 # Static assets
├── index.html              # HTML template
├── tailwind.config.js      # Tailwind configuration
├── postcss.config.js       # PostCSS configuration
├── vite.config.js          # Vite configuration
└── package.json            # Dependencies & scripts
```

## 🎯 Key Components

### Hero Section
- Eye-catching headline with gradient text
- Animated call-to-action card
- Smooth scroll to features on button click
- Background gradient effects

### Features Section
- Grid layout showcasing key features
- Staggered animation on scroll
- Icon-based feature cards
- Hover effects for interactivity

## 🐛 Troubleshooting

### PostCSS/Tailwind Issues

If you encounter PostCSS errors, ensure you have `@tailwindcss/postcss` installed:

```bash
npm install -D @tailwindcss/postcss
```

The `postcss.config.js` should use:
```javascript
'@tailwindcss/postcss': {}
```

### Port Already in Use

If port 5173 is busy, Vite will automatically try the next available port (5174, 5175, etc.)

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the issues page.

## 👨‍💻 Author

Built with ❤️ using modern web technologies

---

**Happy Coding!** 🚀✨
