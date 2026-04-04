# Spence Amber - Professional Portfolio

A modern, beautiful, and responsive portfolio website for **Spence Amber**, a Data Science & Software Engineering Leader.

## 🌟 Features

- **Modern Design**: Contemporary gradient-based UI with smooth animations and transitions
- **Fully Responsive**: Optimized for desktop, tablet, and mobile devices
- **Interactive Elements**: Hover effects, floating action buttons, and smooth scrolling
- **Professional Layout**: Showcase executive summary, professional experience, technical skills, and education
- **Easy Customization**: Clean HTML/CSS structure for easy modifications
- **Performance Optimized**: Fast loading and smooth user experience

## 📁 Project Structure

```
spence-amber-portfolio/
├── rosales_amber_portfolio.html    # Main standalone HTML portfolio
├── rosales_amber_index.html        # React project entry point
├── rosales_amber_package.json      # Project dependencies
├── rosales_amber_tsconfig.json     # TypeScript configuration
├── rosales_amber_vite.config.ts    # Vite build configuration
├── rosales_amber_vercel.json       # Vercel deployment config
├── rosales_amber_README.md         # This file
└── rosales_amber_portfolio_content.md  # Content outline
```

## 🎨 Design Highlights

### Color Scheme
- **Primary**: `#FF6B9D` (Pink)
- **Secondary**: `#C44569` (Rose)
- **Accent**: `#FFA502` (Orange)
- **Dark Background**: `#0F0F1E`
- **Card Background**: `#1A1A2E`

### Typography
- **Headings**: Playfair Display (serif)
- **Body**: Poppins (sans-serif)

### Animations
- Morphing image container
- Floating effect on hero image
- Smooth hover transitions on cards
- Gradient text effects
- Shimmer effect on card hover

## 🚀 Getting Started

### Option 1: Use Standalone HTML
Simply open `rosales_amber_portfolio.html` in your browser. No build process required!

### Option 2: React + Vite Setup
1. Install dependencies:
   ```bash
   npm install
   ```

2. Start development server:
   ```bash
   npm run dev
   ```

3. Build for production:
   ```bash
   npm run build
   ```

## 📝 Customization Guide

### Update Contact Information
Find and replace the following in `rosales_amber_portfolio.html`:
- Email: `spenceamber724@gmail.com`
- LinkedIn: `https://www.linkedin.com/in/ashley-jennifer-8b5b003b6/` (Update this to Spence's actual LinkedIn)

### Modify Content Sections
1. **Hero Section**: Update the headline, tagline, and status badge
2. **Executive Summary**: Update the summary paragraph
3. **Experience Cards**: Edit job titles, companies, and achievements
4. **Technical Skills**: Add or remove skill tags across various categories (Programming, Data & AI, Infrastructure & Cloud, Databases, Web & IT, Soft Skills)
5. **Education**: Update academic details
6. **Footer**: Update personal statement and links

### Change Colors
Update the CSS variables in the `:root` selector:
```css
:root {
    --primary: #FF6B9D;
    --secondary: #C44569;
    --accent: #FFA502;
    /* ... other colors ... */
}
```

### Add Profile Image
Replace the emoji placeholder (👩‍💻) in the `.img-container` div with an image tag:
```html
<img src="path/to/image.jpg" alt="Spence Amber">
```

## 🌐 Deployment

### Deploy to Vercel
1. Push your repository to GitHub
2. Connect your GitHub repo to Vercel
3. Vercel will automatically detect the `vercel.json` configuration
4. Your portfolio will be live!

### Deploy to Other Platforms
- **Netlify**: Connect your GitHub repo directly
- **GitHub Pages**: Use the standalone HTML file
- **Traditional Hosting**: Upload files via FTP

## 📱 Browser Support
- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🔧 Technologies Used
- HTML5
- CSS3 (with modern features like CSS Grid, Flexbox, Gradients)
- JavaScript (vanilla)
- React 19 (optional)
- Vite (optional build tool)
- TypeScript (optional)

## 📄 License
MIT License - Feel free to use and modify as needed.

## 💡 Tips for Best Results
1. **Add a professional photo**: Replace the emoji with a high-quality headshot
2. **Customize the color scheme**: Adjust colors to match personal branding
3. **Update all content**: Ensure all text reflects accurate professional information
4. **Test responsiveness**: Check the site on various devices
5. **Optimize images**: Use compressed images for faster loading

## 📞 Support
For questions or customization help, refer to the inline comments in the HTML file or consult the content outline in `rosales_amber_portfolio_content.md`.

---

**Created**: March 2026  
**Last Updated**: March 2026  
**Version**: 1.0.0
