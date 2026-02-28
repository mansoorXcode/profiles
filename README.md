# Pathan Mansoor Ali Khan - Portfolio

A modern, minimalist, Linktree-style personal portfolio website built for GitHub Pages.

![Portfolio Preview](https://img.shields.io/badge/Portfolio-Live-blue?style=for-the-badge)
![HTML](https://img.shields.io/badge/HTML-5-orange?style=for-the-badge&logo=html5)
![CSS](https://img.shields.io/badge/CSS-3-blue?style=for-the-badge&logo=css3)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow?style=for-the-badge&logo=javascript)

## 🌟 Features

- **Dark Theme**: Elegant black background with blue accent colors
- **Linktree-Style Layout**: Clean, centered design for easy navigation
- **Smooth Animations**: Hover effects, scroll reveals, and gradient animations
- **Responsive Design**: Optimized for both mobile and desktop
- **Multiple Versions**: Two portfolio versions - v1 (basic) & v2 (enhanced)
- **Self-Contained**: Each HTML file includes all CSS and JS for easy deployment

## 📁 Files

| File | Description |
|------|-------------|
| `index.0.0.1.html` | Portfolio v1 - Clean, minimalist design |
| `index.0.0.2.html` | Portfolio v2 - Enhanced with additional features |
| `README.md` | Project documentation |

## 📂 Sections (Both Versions)

1. **Hero** - Profile image, name, and tagline
2. **About Me** - Bio and current focus
3. **Tech Stack** - Skills with animated icons (HTML, CSS, JS, Python, Java, C)
4. **Social Links** - GitHub, LinkedIn, Instagram, LeetCode, Resume
5. **Projects** - Budget Tracker, Movie Sharing, Upcoming ML/NLP projects
6. **Footer** - Built with love message

## 🚀 Deployment

### GitHub Pages

1. Push files to a GitHub repository
2. Go to **Settings > Pages**
3. Select **Deploy from a branch**
4. Choose **main** branch and **/(root)** folder
5. Click **Save**
6. Your site will be live at `https://yourusername.github.io/repository-name`
7. Set one version as `index.html` for the default page, or access versions directly:
   - `https://yourusername.github.io/repository-name/index.0.0.1.html`
   - `https://yourusername.github.io/repository-name/index.0.0.2.html`

### Local Development

```bash
# Using Python
python -m http.server 3000

# Using Node.js
npx serve .

# Using PHP
php -S localhost:3000
```

Then open `http://localhost:3000` in your browser.

## 🎨 Customization

### Profile Image
Replace the DiceBear avatar URL with your own image:
```html
<img src="your-image-url.jpg" alt="Your Name" class="profile-img">
```

### Social Links
Update the `href` attributes in the Connect section:
```html
<a href="https://github.com/yourusername" target="_blank">GitHub</a>
```

### Colors
Modify the CSS variables in `:root`:
```css
--accent: #3b82f6;        /* Change blue accent */
--bg-primary: #0a0a0a;    /* Change background */
```

### Projects
Add or remove project cards in the Projects section:
```html
<a href="your-project-link" class="project-card">
    <div class="project-header">
        <div class="project-icon"><i class="fas fa-icon-name"></i></div>
        <div class="project-info">
            <div class="project-title">Your Project</div>
            <div class="project-tech">Tech Stack</div>
        </div>
    </div>
    <div class="project-desc">Description here</div>
</a>
```

## 📱 Responsive Breakpoints

- **Desktop**: Full layout (680px max-width container)
- **Mobile**: < 480px (adjusted padding, smaller profile image, 3-column tech grid)

## 🔧 Tech Stack

- **HTML5** - Semantic structure
- **CSS3** - Flexbox, Grid, Custom Properties, Animations
- **Vanilla JavaScript** - Intersection Observer, Event Listeners
- **Font Awesome** - Icons
- **Google Fonts** - Inter font family

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

---

**Built with ❤️ using HTML, CSS & JS**

## 👤 Contact

- **Name**: Pathan Mansoor Ali Khan
- **Role**: 2nd-year B.Tech (AI & DS) Student
- **College**: Usha Rama College of Engineering and Technology
- **Email**: mansooralikhan@example.com (update with your email)
"# Profiles" 
