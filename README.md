# Tabish Mehdi - Professional Portfolio Website

A modern, responsive portfolio website built with React and Tailwind CSS, showcasing the professional journey, skills, and projects of Tabish Mehdi, a GenAI Engineer with 11+ years of IT experience.

## 🌟 Features

- **Single Page Application** - Smooth scrolling navigation between sections
- **Fully Responsive** - Optimized for mobile, tablet, and desktop devices
- **Modern Design** - Corporate blue color scheme with professional aesthetics
- **Interactive Elements** - Hover effects, animations, and smooth transitions
- **Contact Form** - Functional contact form with validation
- **No Build Required** - Runs directly in browser with CDN dependencies

## 📑 Sections

1. **Hero** - Eye-catching introduction with animated background
2. **About** - Professional bio and career highlights
3. **Skills** - Categorized technical and soft skills
4. **Experience** - Timeline of professional work history
5. **Projects** - Showcase of featured projects with live demos
6. **Education** - Academic background and certifications
7. **Testimonials** - Client and colleague recommendations
8. **Blog** - Placeholder for future articles
9. **Contact** - Contact form and social media links
10. **Footer** - Quick links and copyright information

## 🛠️ Technologies Used

- **React 18** - UI library (via CDN)
- **Tailwind CSS** - Utility-first CSS framework (via CDN)
- **Babel** - JavaScript compiler for JSX support
- **Font Awesome** - Icon library
- **Google Fonts** - Inter font family

## 🚀 Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- Internet connection (for CDN resources)

### Running the Portfolio

1. **Clone or download** this repository
2. **Open `index.html`** in your web browser
3. That's it! No build process or server required.

```bash
# Simply open the file
open index.html  # macOS
start index.html # Windows
xdg-open index.html # Linux
```

## 📁 Project Structure

```
portfolio/
├── index.html          # Main HTML file with all React components
└── README.md           # This file
```

## 🎨 Customization

### Updating Personal Information

The portfolio content is embedded in the `index.html` file. To customize:

1. **Open `index.html`** in a code editor
2. **Search for the content** you want to modify (e.g., "Tabish Mehdi", project descriptions, etc.)
3. **Edit the text** directly in the React components
4. **Save and refresh** your browser

### Key Areas to Customize

- **Personal Details**: Name, email, location, social links
- **Bio**: About section content
- **Skills**: Add/remove skills in the skillCategories array
- **Experience**: Update work history in the experiences array
- **Projects**: Modify project details, images, and links
- **Education**: Update degrees and certifications
- **Testimonials**: Add client testimonials

### Changing Colors

The color scheme is defined in the Tailwind config within `index.html`:

```javascript
tailwind.config = {
    theme: {
        extend: {
            colors: {
                primary: '#1e40af',    // Deep blue
                secondary: '#3b82f6',  // Medium blue
                accent: '#0ea5e9',     // Sky blue
            }
        }
    }
}
```

## 🌐 Deployment

### Option 1: GitHub Pages

1. Create a GitHub repository
2. Upload `index.html` to the repository
3. Go to Settings > Pages
4. Select the main branch and save
5. Your portfolio will be live at `https://yourusername.github.io/repository-name`

### Option 2: Netlify

1. Sign up at [Netlify](https://netlify.com)
2. Drag and drop the folder containing `index.html`
3. Your site will be live instantly

### Option 3: Vercel

1. Install Vercel CLI: `npm i -g vercel`
2. Run `vercel` in the project directory
3. Follow the prompts to deploy

### Option 4: Traditional Hosting

Upload `index.html` to any web hosting service via FTP or file manager.

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## 🤝 Contributing

This is a personal portfolio website. If you'd like to suggest improvements or report issues, feel free to:

1. Fork the repository
2. Create a feature branch
3. Submit a pull request

## 📄 License

This project is open source and available for personal and commercial use.

## 📧 Contact

- **Name**: Tabish Mehdi
- **Email**: tabish@example.com
- **LinkedIn**: [linkedin.com/in/tabishmehdi](https://linkedin.com)
- **GitHub**: [github.com/tabishmehdi](https://github.com)

## 🙏 Acknowledgments

- [React](https://reactjs.org/) - A JavaScript library for building user interfaces
- [Tailwind CSS](https://tailwindcss.com/) - A utility-first CSS framework
- [Font Awesome](https://fontawesome.com/) - The internet's icon library
- [Unsplash](https://unsplash.com/) - Beautiful free images

---

**Built with ❤️ by Tabish Mehdi**