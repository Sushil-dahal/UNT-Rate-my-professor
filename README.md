
# 🎓 UNT Rater

<div align="center">
  <img src="https://img.shields.io/badge/React-18.3.1-61DAFB?style=for-the-badge&logo=react&logoColor=white" alt="React" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/Vite-6.3.5-646CFF?style=for-the-badge&logo=vite&logoColor=white" alt="Vite" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="Tailwind CSS" />
</div>

<p align="center">
  <strong>A modern, professional professor rating platform for the University of North Texas</strong>
</p>

<p align="center">
  <a href="#-features">Features</a> •
  <a href="##demo">Demo</a> •
  <a href="##installation">Installation</a> •
  <a href="##usage">Usage</a> •
  <a href="##tech-stack">Tech Stack</a> •
  <a href="##contributing">Contributing</a>
</p>

---

## 📖 About

UNT Rater is a sleek, student-focused web application that allows University of North Texas students to browse, rate, and review professors across all departments. Built with modern web technologies and a clean, professional design aesthetic, it offers an intuitive platform that enables students to make informed decisions about their courses and professors.

**Original Design**: Based on the [Figma design]
## ✨ Features

### 🔍 **Professor Discovery**
- **Advanced Search**: Search professors by name, department, or course code
- **Smart Filtering**: Filter by department, rating threshold, and more
- **Department Browse**: Explore professors organized by academic departments
- **Detailed Profiles**: View professor ratings, reviews, office locations, and courses taught

### 👥 **Student Community**
- **UNT Student Authentication**: Secure sign-up with UNT email verification
- **Anonymous Reviews**: Rate and review professors while maintaining anonymity
- **Top Rated Lists**: Discover highly-rated professors across campus
- **Course Information**: View popular courses and professor assignments

### 📊 **Department Insights**
- **Department Statistics**: Average ratings, professor counts, and review totals
- **Popular Courses**: See trending courses within each department
- **Visual Organization**: Color-coded department cards with intuitive icons

### 🎨 **Modern Design**
- **Professional UI**: Clean, Uber-inspired design without flashy elements
- **Responsive Layout**: Optimized for desktop, tablet, and mobile devices
- **Consistent Branding**: UNT green and orange color scheme throughout
- **Accessibility**: Built with accessibility best practices in mind

## 🚀 Demo

### Home Page
- Hero section with search functionality
- Top-rated professors showcase
- Clean navigation and UNT branding

### Browse Professors
- Advanced filtering system
- Professor cards with ratings and tags
- Real-time search results

### Departments
- Visual department overview
- Statistics and popular courses
- Interactive department cards

### Add Professor
- Comprehensive form for adding new professors
- Guidelines and validation
- Community contribution features

## 🛠️ Installation

### Prerequisites
- **Node.js** (v18.0.0 or higher)
- **npm** or **yarn**

### Quick Start

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/unt-rater.git
   cd unt-rater
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm run dev
   ```

4. **Open your browser**
   ```
   http://localhost:3000
   ```

### Build for Production

```bash
npm run build
```

The built files will be in the `dist/` directory, ready for deployment to any static hosting service.

## 🎯 Usage

### Development

- **Hot Reload**: Changes are automatically reflected in the browser
- **TypeScript**: Full type safety and IntelliSense support
- **Component Development**: Modular architecture for easy maintenance

### Deployment

This project is optimized for deployment on:
- **Vercel** (Recommended)
- **Netlify**
- **GitHub Pages**
- Any static hosting service

## 🏗️ Tech Stack

### Frontend Framework
- **React 18.3.1** - Modern React with hooks and concurrent features
- **TypeScript** - Type-safe development
- **Vite 6.3.5** - Lightning-fast build tool with HMR

### UI & Styling
- **Tailwind CSS** - Utility-first CSS framework
- **Radix UI** - Accessible, unstyled UI primitives
- **shadcn/ui** - Beautiful, reusable components
- **Lucide React** - Beautiful & consistent icon library

### Routing & Navigation
- **React Router DOM** - Declarative routing for React

### Form Handling
- **React Hook Form** - Performant, flexible forms

### Development Tools
- **SWC** - Fast TypeScript/JavaScript compiler
- **CSS Variables** - Dynamic theming support

## 📁 Project Structure

```
src/
├── components/
│   ├── ui/                    # Reusable UI components (shadcn/ui)
│   ├── figma/                 # Figma-specific components
│   ├── home.tsx              # Landing page
│   ├── browseprofessors.tsx   # Professor search & browse
│   ├── departments.tsx       # Department overview
│   ├── addprofessor.tsx      # Add new professor form
│   ├── signin.tsx            # Student authentication
│   └── signup.tsx            # Student registration
├── styles/
│   ├── globals.css           # Global styles and CSS variables
│   └── index.css            # Tailwind CSS imports
├── guidelines/
│   └── Guidelines.md         # Design system guidelines
├── App.tsx                   # Main application component
├── main.tsx                  # Application entry point
└── vite.config.ts           # Vite configuration
```

## 🎨 Design System

### Color Palette
- **Primary**: UNT Green (`#16a34a`)
- **Secondary**: UNT Orange (`#fb923c`)
- **Neutral**: Gray scale for text and backgrounds

### Typography
- **System Fonts**: Native font stack for optimal performance
- **Hierarchy**: Consistent heading and body text styles

### Components
- **Buttons**: Primary, secondary, and ghost variants
- **Cards**: Consistent spacing and shadow patterns
- **Forms**: Accessible inputs with proper validation states

## 🔮 Roadmap

- [ ] **Backend Integration**
  - User authentication system
  - Professor and review database
  - Real-time data updates

- [ ] **Enhanced Features**
  - Review moderation system
  - Professor comparison tool
  - Course scheduling integration
  - Mobile app development

- [ ] **Analytics & Insights**
  - Review sentiment analysis
  - Department performance metrics
  - Student engagement tracking

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **Fork the repository**
2. **Create a feature branch**
   ```bash
   git checkout -b feature/amazing-feature
   ```
3. **Commit your changes**
   ```bash
   git commit -m 'Add amazing feature'
   ```
4. **Push to the branch**
   ```bash
   git push origin feature/amazing-feature
   ```
5. **Open a Pull Request**

### Development Guidelines
- Follow the existing code style and conventions
- Maintain the professional design aesthetic
- Ensure TypeScript type safety
- Test your changes across different screen sizes
- Update documentation as needed

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **shadcn/ui** - Beautiful component library used under [MIT license](https://github.com/shadcn-ui/ui/blob/main/LICENSE.md)
- **Unsplash** - Photos used under [Unsplash license](https://unsplash.com/license)
- **University of North Texas** - Inspiration and branding
- **Figma Community** - Original design inspiration

## 📞 Support

If you have any questions or need help with the project:

- 📧 **Email**: dahalsushil987@gmail.com
- 🐛 **Issues**: [GitHub Issues](https://github.com/Sushil-dahal/UNT-Rater/issues)
- 💬 **Discussions**: [GitHub Discussions](https://github.com/Sushil-dahal/UNT-Rater/discussions/1)

---

<p align="center">
  <strong>Built by Quadra Tech</strong><br>
  For the UNT student community
</p>
  
