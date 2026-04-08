# Rimjhim Singh - Portfolio

A modern, responsive personal portfolio website built with **HTML5** and **Tailwind CSS**. Features a sleek, NextJS-style aesthetic with smooth animations and a professional design.

## Features

✨ **Modern Design**
- Clean, minimal aesthetic with gradient accents
- Smooth animations and transitions
- Glass-morphism effects
- Fully responsive (mobile, tablet, desktop)

📱 **Sections**
- Hero section with call-to-action
- About section with statistics
- Featured projects showcase
- Skills & expertise breakdown
- Contact form
- Responsive navigation

🚀 **Technologies**
- HTML5
- Tailwind CSS (via CDN)
- Vanilla JavaScript
- Google Fonts (Inter)

## Setup & Deployment

### Local Setup
1. Clone the repository:
```bash
git clone https://github.com/rimjhim/rimjhim-portfolio.git
cd rimjhim-portfolio
```

2. Open `index.html` in your browser or use a live server:
```bash
# Using Python 3
python -m http.server 8000

# Using Node.js (http-server)
npx http-server
```

Then navigate to `http://localhost:8000`

### GitHub Pages Deployment

1. Push to GitHub:
```bash
git add .
git commit -m "Initial portfolio commit"
git push origin main
```

2. Enable GitHub Pages:
   - Go to your repository settings
   - Navigate to "Pages" section
   - Select "Deploy from a branch"
   - Choose "main" branch and save

3. Your portfolio will be live at: `https://rimjhim.github.io/rimjhim-portfolio/`

## Customization

### Update Profile Image
1. Replace `public/profile.jpg` with your own image
2. Recommended size: 500x600px
3. Format: JPG or PNG

### Update Content
Edit `index.html` to customize:
- Name and title
- About section text
- Projects (add your own or remove)
- Skills and expertise
- Contact information
- Social media links

### Modify Colors
Update the gradient colors in the CSS:
- Primary gradient: `from-purple-600 to-blue-600`
- Secondary colors: Adjust Tailwind color utilities

## File Structure

```
rimjhim-portfolio/
├── index.html          # Main portfolio file
├── public/
│   └── profile.jpg     # Your profile image
├── README.md           # This file
└── .gitignore          # Git ignore file
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

This portfolio template is free to use and modify for personal projects.

## Contact

For questions or support, reach out via the contact form on the portfolio.

---

**Built with ✨ by Rimjhim Singh**
