# Ong Eng Wei - Programmer Resume

An ATS-friendly resume website built with clean HTML and CSS.

## Features

- **ATS-Optimized**: Uses semantic HTML with proper heading hierarchy and clear text content
- **Responsive Design**: Works on all devices (desktop, tablet, mobile)
- **Print-Ready**: Optimized print styles for PDF export
- **Clean Layout**: Professional design with easy-to-read typography
- **Fast Loading**: No external dependencies, pure HTML/CSS

## Deployment to GitHub Pages

### Option 1: Using GitHub Web Interface

1. Create a new repository on GitHub (e.g., `your-username.github.io` or `resume`)
2. Upload `index.html`, `styles.css`, and `README.md`
3. Go to Settings > Pages
4. Select `main` branch as source
5. Click Save
6. Your site will be available at `https://your-username.github.io/resume/`

### Option 2: Using Git Command Line

```bash
# Initialize git repository
git init

# Add all files
git add .

# Commit files
git commit -m "Initial commit: ATS-friendly resume"

# Add remote repository
git remote add origin https://github.com/your-username/resume.git

# Push to GitHub
git branch -M main
git push -u origin main
```

Then enable GitHub Pages in repository settings.

## Customization

### Updating Content

Edit `index.html` to update your information:
- Contact details in the `<header>` section
- Professional summary
- Skills
- Work experience
- Education

### Changing Colors

Edit `styles.css` to customize the color scheme:
- Primary color: `#2c3e50`
- Accent color: `#3498db`
- Green highlights: `#16a085`

### Adding Sections

You can add additional sections like:
- Certifications
- Projects
- Publications
- Awards

## Local Development

Simply open `index.html` in your web browser to preview locally.

## ATS Tips

This resume is optimized for Applicant Tracking Systems:
- Uses standard section headings (Experience, Education, Skills)
- Semantic HTML structure
- No tables or complex layouts
- Clear, readable fonts
- Proper heading hierarchy (H1, H2, H3, H4)
- Keywords naturally integrated

## License

Feel free to use this template for your own resume.
