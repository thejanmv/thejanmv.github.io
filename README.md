# Menura's Portfolio Website

A modern, responsive portfolio website showcasing AI/Data projects, skills, and CV.

## Features

✨ **Modern Design**: Clean and professional UI with smooth animations
📱 **Fully Responsive**: Works seamlessly on desktop, tablet, and mobile devices
🎨 **Interactive Elements**: Hover effects, smooth scrolling, and animations
📂 **GitHub Integration**: Automatically fetches and displays your latest GitHub projects
💼 **CV Section**: Detailed curriculum vitae with education, experience, and certifications
📧 **Contact Section**: Easy-to-find contact information with social links

## Sections

1. **Home/Hero**: Eye-catching introduction with call-to-action buttons
2. **About**: Personal introduction and key highlights
3. **Skills**: Organized showcase of technical skills and technologies
4. **Projects**: Dynamically loaded from GitHub repositories
5. **CV**: Professional resume with education, experience, and certifications
6. **Contact**: Contact information and social media links

## Customization Guide

### Personal Information

**Contact Details** (already updated):
- Email: vishmiththejan@gmail.com
- Location: Melbourne, Australia
- GitHub and LinkedIn links verified

**Hero Section** (`index.html` lines 34-36):
- Update your title/subtitle
- Modify the description

**About Section** (`index.html` lines 54-56):
- Write your own bio (3 paragraphs provided)

### Skills

Update your skills in the Skills section (`index.html` lines 85-122):
- Programming Languages
- Web Development
- Database & Tools
- Other Skills

### CV/Resume

**Education** (`index.html` lines 152-159):
- Update degree, university name, dates, and coursework

**Experience** (`index.html` lines 165-176):
- Add your work experience with company names and responsibilities

**Certifications** (`index.html` lines 182-188):
- List your certifications and achievements

**CV PDF** (already configured):
- CV PDF file: `Menura-SoftwareEngineer-AI-Data.pdf`
- "View Full CV" button opens PDF in a new tab
- PDF accessible directly from the CV section

### GitHub Projects

Projects are automatically fetched from your GitHub profile (`thejanmv`). The script:
- Fetches your 6 most recent repositories
- Filters out forked repos
- Sorts by star count
- Displays project name, description, language, stars, and forks

To customize the number of projects or filtering, edit `script.js` (lines 71-78).

### Profile Information

- **Name:** Menura
- **Title:** Software Engineer - AI/Data Specialist
- **Location:** Melbourne, Australia
- **Email:** vishmiththejan@gmail.com
- **Specialization:** Artificial Intelligence, Machine Learning, Data Engineering

### Colors & Styling

Update the color scheme in `style.css` (lines 4-16):
```css
:root {
    --primary-color: #2563eb;     /* Main brand color */
    --secondary-color: #1e40af;   /* Secondary brand color */
    --accent-color: #3b82f6;      /* Accent color */
    /* ... other colors */
}
```

### Hero Background

Change the gradient background in `style.css` (line 134):
```css
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
```

## File Structure

```
thejanmv.github.io/
├── index.html       # Main HTML file
├── style.css        # Stylesheet with all styling
├── script.js        # JavaScript for interactivity and GitHub API
└── README.md        # This file
```

## GitHub Pages Deployment

This site is ready to deploy on GitHub Pages:

1. Push all files to your repository
2. Go to repository Settings
3. Navigate to Pages section
4. Select main branch as source
5. Your site will be live at `https://thejanmv.github.io`

**Note:** Make sure the `Menura-SoftwareEngineer-AI-Data.pdf` file is in the repository root for the CV link to work.

## Technologies Used

- HTML5
- CSS3 (with CSS Grid and Flexbox)
- Vanilla JavaScript
- Font Awesome Icons
- GitHub REST API

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Customization Tips

1. **Add more projects**: The script automatically loads from GitHub
2. **Add a blog section**: Create a new section following the existing pattern
3. **Add testimonials**: Create a testimonials section with quotes
4. **Add a contact form**: Integrate with FormSpree, Netlify Forms, or similar
5. **Add analytics**: Integrate Google Analytics by adding the tracking code

## License

Feel free to use this template for your own portfolio!

---

Built with ❤️ by Menura