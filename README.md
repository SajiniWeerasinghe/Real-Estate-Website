# 🏠 Real Estate Website

A modern, responsive real estate website built with React and Vite, featuring smooth animations, property listings, and a professional design.

## 🌟 Live Demo

🔗 **[View Live Website](https://sajiniweerasinghe.github.io/Real-Estate-Website)**

## 📱 Features

- **Responsive Design** - Works seamlessly on desktop, tablet, and mobile devices
- **Interactive Navigation** - Smooth scrolling navbar with mobile hamburger menu
- **Property Carousel** - Browse through property listings with next/prev controls
- **Smooth Animations** - Framer Motion animations for enhanced user experience
- **Modern UI** - Clean and professional design with Tailwind CSS
- **Company Stats** - Display achievements and project statistics
- **Mobile-First** - Optimized for mobile devices with touch-friendly interactions

## 🛠️ Technologies Used

### Frontend

- **React 19.1.0** - Modern JavaScript library for building user interfaces
- **Vite 7.0.4** - Fast build tool and development server
- **Tailwind CSS 3.4.17** - Utility-first CSS framework for rapid UI development
- **Framer Motion 12.23.6** - Production-ready motion library for React

### Development Tools

- **ESLint 9.30.1** - JavaScript linting utility for code quality
- **PostCSS 8.5.6** - CSS transformation tool
- **Autoprefixer 10.4.21** - CSS vendor prefixes automation

### Deployment

- **GitHub Pages** - Free static site hosting
- **gh-pages 6.3.0** - Deploy React apps to GitHub Pages

## 📂 Project Structure

```
real-estate/
├── public/
│   ├── favicon.svg
│   └── header_img.png
├── src/
│   ├── assets/
│   │   ├── images/
│   │   └── assets.js
│   ├── components/
│   │   ├── Navbar.jsx
│   │   ├── About.jsx
│   │   └── Projects.jsx
│   ├── App.jsx
│   ├── main.jsx
│   └── index.css
├── package.json
├── vite.config.js
└── tailwind.config.js
```

## 🚀 Getting Started

### Prerequisites

- Node.js (v16 or higher)
- npm or yarn package manager

### Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/SajiniWeerasinghe/Real-Estate-Website.git
   cd Real-Estate-Website
   ```

2. **Install dependencies**

   ```bash
   npm install
   ```

3. **Start development server**

   ```bash
   npm run dev
   ```

4. **Open your browser**
   Navigate to `http://localhost:5173`

## 📜 Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint for code quality
- `npm run deploy` - Deploy to GitHub Pages

## 🎨 Customization

### Colors & Styling

The website uses Tailwind CSS for styling. You can customize colors, fonts, and spacing by editing the `tailwind.config.js` file.

### Content

- Update company information in `src/components/About.jsx`
- Add/modify property listings in `src/assets/assets.js`
- Change images in the `src/assets/` directory

### Animations

Framer Motion animations can be customized in individual components. Adjust timing, transitions, and effects as needed.

## 🌐 Deployment

This project is set up for easy deployment to GitHub Pages:

1. **Build the project**

   ```bash
   npm run build
   ```

2. **Deploy to GitHub Pages**
   ```bash
   npm run deploy
   ```

The site will be available at: `https://yourusername.github.io/repository-name`

## 📱 Responsive Breakpoints

- **Mobile**: < 640px
- **Tablet**: 640px - 1024px
- **Desktop**: > 1024px

## 🤝 Contributing

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 👨‍💻 Author

**Sajini Weerasinghe**

- GitHub: [@SajiniWeerasinghe](https://github.com/SajiniWeerasinghe)

## 🙏 Acknowledgments

- React team for the amazing framework
- Tailwind CSS for the utility-first CSS framework
- Framer Motion for smooth animations
- Vite for the fast build tool

---

⭐ If you found this project helpful, please give it a star!
