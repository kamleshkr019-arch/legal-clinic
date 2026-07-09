# Legal Clinic Website

A professional legal services website for Legal Clinic with service offerings, contact information, and promotional materials.

## Features

- **Responsive Design**: Works on desktop, tablet, and mobile devices
- **Services Page**: Displays all practice areas (Corporate Law, Family Law, Criminal Defense, etc.)
- **Contact Integration**: Direct WhatsApp and email contact buttons
- **Professional Branding**: Modern design with premium flyer display
- **Promotional Materials**: Integrated business flyer image

## Contact Information

- **Phone**: +91 96979 85577
- **Email**: advrandhirjha@hotmail.com
- **WhatsApp**: Available through website buttons

## Setup & Deployment

### Local Testing
```bash
# Start a local web server
python -m http.server 8000

# Open in browser
http://localhost:8000/index.html
```

### Deploy to GitHub Pages

1. **Create a GitHub Account** (if you don't have one): https://github.com/signup

2. **Create a New Repository**:
   - Go to https://github.com/new
   - Repository name: `legal-clinic` (or your preferred name)
   - Description: "Professional legal services website"
   - Make it **Public**
   - Click "Create repository"

3. **Push to GitHub** (run these commands in the LegalClinic folder):
```bash
git remote add origin https://github.com/YOUR-USERNAME/legal-clinic.git
git branch -M main
git push -u origin main
```

4. **Enable GitHub Pages**:
   - Go to your repository settings
   - Scroll to "Pages" section
   - Select "Deploy from a branch"
   - Branch: `main`
   - Folder: `/ (root)`
   - Click "Save"

5. **Get Your Live Link**:
   - Wait ~1-2 minutes for GitHub to build the site
   - Your site will be live at: `https://YOUR-USERNAME.github.io/legal-clinic/`

## Files Structure

```
├── index.html          # Home page
├── about.html          # About page
├── services.html       # Services page
├── contact.html        # Contact page
├── css/
│   └── style.css       # Styling
├── js/
│   └── script.js       # JavaScript functionality
├── Images/
│   └── flyer.png       # Promotional flyer
└── .gitignore          # Git ignore rules
```

## License

© 2026 Legal Clinic. All rights reserved.
