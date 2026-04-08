<div align="center">

# 🌟 Nesrine Derouiche - Portfolio

[![Live Demo](https://img.shields.io/badge/Live-Demo-brightgreen?style=for-the-badge&logo=vercel&logoColor=white)](https://nesrine-derouiche.is-a.dev)
[![GitHub](https://img.shields.io/badge/GitHub-nesrine_derouiche-181717?style=for-the-badge&logo=github)](https://github.com/nesrine-derouiche)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin)](https://linkedin.com/in/nesrine-derouiche)
[![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)](#license)

**A modern, responsive portfolio showcasing software & mobile engineering projects**

[View Live Demo](https://nesrine-derouiche.is-a.dev) · [Report Bug](https://github.com/nesrine77/portfolio/issues) · [Request Feature](https://github.com/nesrine77/portfolio/issues)

</div>

---

## 📸 Preview

<div align="center">

### 🌞 Light Theme
<img src="public/assets/demo/portfolio-light.png" alt="Portfolio Light Theme" width="800"/>

### 🌙 Dark Theme
<img src="public/assets/demo/portfolio-dark.png" alt="Portfolio Dark Theme" width="800"/>

</div>

---

## ✨ Features

🎨 **Modern & Responsive Design**
- Fully responsive across all devices
- Smooth animations and transitions
- Light/Dark theme toggle
- Professional UI/UX with shadcn/ui components

🚀 **Performance Optimized**
- Lightning-fast load times with Vite
- Optimized images and assets
- Code splitting and lazy loading
- SEO-friendly structure

📱 **Complete Portfolio Sections**
- Hero section with social links
- About me with specializations
- Skills categorized by technology
- Professional experience timeline
- Featured projects showcase
- Certifications & achievements
- Contact form integration
- Footer with quick navigation

🎯 **Interactive Elements**
- Smooth scroll navigation
- Project filtering by category
- Expandable certification cards
- Hover effects and animations
- Interactive skill badges

---

## 🛠️ Tech Stack

### Core Technologies

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)

### UI Components & Libraries

- **shadcn/ui** - High-quality UI components
- **Radix UI** - Unstyled, accessible component primitives
- **Lucide React** - Beautiful icon library
- **Embla Carousel** - Lightweight carousel library
- **React Query** - Powerful data synchronization

### Development Tools

- **ESLint** - Code linting
- **Vitest** - Unit testing framework
- **PostCSS** - CSS transformations
- **date-fns** - Date utility library

---

## 🚀 Getting Started

### Prerequisites

- **Node.js** (v16 or higher)
- **npm** or **bun** package manager

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/nesrine77/portfolio.git
   cd portfolio
   ```

2. **Install dependencies**
   ```bash
   npm install
   # or
   bun install
   ```

3. **Start the development server**
   ```bash
   npm run dev
   # or
   bun dev
   ```

4. **Open your browser**
   ```
   Navigate to http://localhost:5173
   ```

### Build for Production

```bash
# Build the project
npm run build

# Preview production build
npm run preview
```

---

## 📁 Project Structure

```
portfolio/
├── public/                 # Static assets
├── src/
│   ├── assets/            # (Moved to public/assets)
│   ├── components/        # React components
│   │   ├── sections/      # Page sections (Hero, About, Skills, etc.)
│   │   ├── ui/           # Reusable UI components (shadcn/ui)
│   │   ├── Navigation.tsx
│   │   ├── NavLink.tsx
│   │   └── ThemeProvider.tsx
│   ├── hooks/            # Custom React hooks
│   ├── lib/              # Utility functions
│   ├── pages/            # Page components
│   ├── test/             # Test files
│   ├── App.tsx           # Main app component
│   ├── main.tsx          # Entry point
│   └── index.css         # Global styles
├── components.json       # shadcn/ui configuration
├── tailwind.config.ts    # Tailwind CSS configuration
├── tsconfig.json         # TypeScript configuration
├── vite.config.ts        # Vite configuration
└── package.json          # Project dependencies
```

---

## 🎨 Customization

### Theme Colors

Edit the theme colors in `tailwind.config.ts`:

```typescript
theme: {
  extend: {
    colors: {
      primary: {...},
      secondary: {...},
      accent: {...}
    }
  }
}
```

### Content Updates

- **Personal Info**: Update `src/components/sections/Hero.tsx`
- **Skills**: Modify `src/components/sections/Skills.tsx`
- **Projects**: Edit `src/components/sections/Projects.tsx`
- **Experience**: Update `src/components/sections/Experience.tsx`
- **Certifications**: Modify `src/components/sections/Certifications.tsx`

### Adding Components

Use shadcn/ui CLI to add new components:

```bash
npx shadcn-ui@latest add [component-name]
```

---

## 📊 Sections Overview

| Section | Description |
|---------|-------------|
| **Hero** | Introduction with profile image, social links, and CTAs |
| **About** | Professional background and specializations |
| **Skills** | Categorized technical skills with tags |
| **Experience** | Professional work experience timeline |
| **Projects** | Featured projects with filtering capabilities |
| **Certifications** | Achievements and certifications showcase |
| **Contact** | Contact information and social links |
| **Footer** | Quick navigation and copyright |

---

## 🧪 Testing

Run the test suite:

```bash
# Run tests once
npm run test

# Run tests in watch mode
npm run test:watch
```

---

## 📦 Deployment

### Deploy to Vercel

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/nesrine77/portfolio)

1. Push your code to GitHub
2. Import your repository on Vercel
3. Configure build settings:
   - **Build Command**: `npm run build`
   - **Output Directory**: `dist`
4. Deploy!

### Deploy to Netlify

1. Build the project: `npm run build`
2. Drag and drop the `dist` folder to [Netlify](https://app.netlify.com/drop)

### Deploy to GitHub Pages

```bash
npm run build
# Deploy the dist folder to gh-pages branch
```

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 👤 Author

**Nesrine Derouiche**

- 🌐 Website: [nesrine-derouiche.is-a.dev](https://nesrine-derouiche.is-a.dev)
- 💼 LinkedIn: [@nesrine-derouiche](https://linkedin.com/in/nesrine-derouiche)
- 🐙 GitHub: [@nesrine-derouiche](https://github.com/nesrine-derouiche)
- 📧 Email: [nesrine.derouiche15@gmail.com](mailto:nesrine.derouiche15@gmail.com)

---

## 🙏 Acknowledgments

- [shadcn/ui](https://ui.shadcn.com/) - For the beautiful component library
- [Radix UI](https://www.radix-ui.com/) - For accessible primitives
- [Lucide Icons](https://lucide.dev/) - For the icon library
- [Vercel](https://vercel.com/) - For hosting and deployment

---

## 📈 Project Stats

![GitHub stars](https://img.shields.io/github/stars/nesrine77/portfolio?style=social)
![GitHub forks](https://img.shields.io/github/forks/nesrine77/portfolio?style=social)
![GitHub watchers](https://img.shields.io/github/watchers/nesrine77/portfolio?style=social)

---

<div align="center">

**Made with ❤️ by Nesrine Derouiche**

⭐ Star this repository if you find it helpful!

</div>
