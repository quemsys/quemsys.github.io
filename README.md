# QUEM Systems International - Company Website

A modern, professional website for QUEM Systems International, built with static HTML and Tailwind CSS.

## 🚀 Features

- **Modern Design**: Clean, professional design with gradient accents
- **Fully Responsive**: Works seamlessly on desktop, tablet, and mobile devices
- **Fast Loading**: Static HTML with CDN-based Tailwind CSS for optimal performance
- **SEO Friendly**: Proper meta tags and semantic HTML structure
- **Accessible**: Well-structured navigation and content

## 📋 Sections

1. **Hero Section**: Eye-catching introduction with company tagline
2. **About Section**: Company mission, approach, and core values
3. **Services Section**: Detailed overview of services offered
4. **Technology Stack**: Technologies and tools used
5. **Contact Section**: Contact form and company information
6. **Footer**: Quick links and social media connections

## 🛠️ Technologies Used

- **HTML5**: Semantic markup
- **Tailwind CSS**: Utility-first CSS framework (via CDN)
- **Font Awesome**: Icons library
- **Google Fonts**: Inter font family
- **Vanilla JavaScript**: For interactivity (mobile menu, smooth scrolling, form handling)

## 📦 Deployment to GitHub Pages

### Option 1: Deploy via GitHub Pages (Recommended)

1. **Create a new repository** on GitHub (e.g., `quem-systems-website`)

2. **Push your code to GitHub**:
   ```bash
   git init
   git add .
   git commit -m "Initial commit: QUEM Systems website"
   git branch -M main
   git remote add origin https://github.com/yourusername/quem-systems-website.git
   git push -u origin main
   ```

3. **Enable GitHub Pages**:
   - Go to your repository on GitHub
   - Click on **Settings**
   - Scroll down to **Pages** section
   - Under **Source**, select `main` branch
   - Select `/ (root)` folder
   - Click **Save**
   - Your site will be available at: `https://yourusername.github.io/quem-systems-website/`

### Option 2: Use GitHub Actions (Optional)

You can also set up a custom domain or use GitHub Actions for more advanced deployment workflows.

## 🎨 Customization

### Colors

The website uses a purple gradient theme. To customize colors, modify the gradient classes in the HTML:

- Hero gradient: `gradient-bg` class
- Text gradient: `text-gradient` class
- Accent color: Purple (`purple-600`, `purple-400`)

### Content

Update the content in `index.html`:
- Company information in the About section
- Services descriptions in the Services section
- Contact information in the Contact section
- Footer links and social media URLs

### Contact Form

The contact form currently shows an alert on submission. To integrate with a backend service:

1. Replace the form submission handler in the JavaScript section
2. Use a service like Formspree, Netlify Forms, or your own backend API
3. Update the form action and method attributes

Example with Formspree:
```html
<form action="https://formspree.io/f/your-form-id" method="POST">
```

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📄 License

This project is proprietary and belongs to QUEM Systems International.

## 👥 Contact

For questions or support, please contact QUEM Systems International through the contact form on the website.

---

**QUEM Systems International** - Turning Software Systems into Intelligent Systems
