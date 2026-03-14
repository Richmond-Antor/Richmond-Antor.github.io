# Richmond Antor Biswas - Portfolio Website

A clean, professional portfolio website showcasing my work in Machine Learning, Data Science, and AI Engineering.

## 🌟 Features

- **Responsive Design** - Works perfectly on desktop, tablet, and mobile
- **Dark/Light Mode** - Toggle between themes with your preference saved
- **Modern UI** - Clean, professional design with smooth animations
- **Fast Loading** - Optimized performance
- **SEO Friendly** - Proper meta tags and semantic HTML

## 🚀 Quick Start - Deploying to GitHub Pages

### Step 1: Create a New Repository

1. Go to [GitHub](https://github.com) and log in
2. Click the **"+"** icon in the top right corner
3. Select **"New repository"**
4. **IMPORTANT**: Name it exactly `Richmond-Antor.github.io` (replace with your GitHub username)
5. Make it **Public**
6. Click **"Create repository"**

### Step 2: Upload Your Files

**Option A: Using GitHub Web Interface (Easiest)**

1. In your new repository, click **"uploading an existing file"**
2. Drag and drop ALL files from the `portfolio-site` folder:
   - `index.html`
   - `projects.html`
   - `css/` folder
   - `js/` folder
   - `assets/` folder (with your profile image)
3. Add a commit message: "Initial portfolio upload"
4. Click **"Commit changes"**

**Option B: Using Git Command Line**

```bash
# Navigate to the portfolio-site folder
cd portfolio-site

# Initialize git (if not already)
git init

# Add all files
git add .

# Commit
git commit -m "Initial portfolio upload"

# Add remote (replace with your repo URL)
git remote add origin https://github.com/Richmond-Antor/Richmond-Antor.github.io.git

# Push to GitHub
git branch -M main
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **Settings** (top right)
3. Click **Pages** in the left sidebar
4. Under **"Source"**, select **"Deploy from a branch"**
5. Under **"Branch"**, select **"main"** and **"/ (root)"**
6. Click **Save**

### Step 4: Access Your Live Site

Your portfolio will be live at: `https://Richmond-Antor.github.io`

**Note**: It may take 5-10 minutes for the site to go live after the first deployment.

## 📝 Customizing Your Portfolio

### Adding Your Projects

1. Open `projects.html` in a text editor
2. Find the placeholder project cards (marked with comments)
3. Replace the placeholder information with your actual project details:
   - Project title
   - Description
   - Technologies used
   - Metrics/achievements
   - GitHub repository link
   - Live demo link (if available)

Example:
```html
<h3 class="project-title">Your Project Name</h3>
<p class="project-description">Your project description here...</p>
<span class="tech-tag">Python</span>
<span class="tech-tag">TensorFlow</span>
<a href="https://github.com/your-username/your-repo" class="project-link">View Code</a>
```

### Updating Contact Information

1. Open `index.html`
2. Scroll to the **Contact Section** (near the bottom)
3. Verify/update:
   - Email address
   - Phone number
   - LinkedIn URL
   - GitHub URL

### Changing Colors/Theme

1. Open `css/styles.css`
2. Find the `:root` section at the top
3. Modify the color variables:
   - `--color-accent` - Main accent color (currently green)
   - `--color-bg-primary` - Background color
   - `--color-text-primary` - Text color

### Adding a Resume/CV Download

1. Add your resume PDF to the `assets/` folder (e.g., `resume.pdf`)
2. In `index.html`, find the hero CTA buttons
3. Add a new button:
```html
<a href="assets/resume.pdf" download class="btn btn-secondary">Download Resume</a>
```

## 📂 Project Structure

```
portfolio-site/
├── index.html              # Home page
├── projects.html           # Projects showcase page
├── css/
│   └── styles.css         # Main stylesheet
├── js/
│   └── script.js          # JavaScript functionality
└── assets/
    └── images/
        └── profile.jpg    # Your profile photo
```

## 🎨 Technologies Used

- HTML5
- CSS3 (with CSS Variables)
- Vanilla JavaScript
- Google Fonts (Libre Baskerville & Work Sans)

## 🔧 Troubleshooting

**Site not showing up?**
- Make sure the repository name is exactly `your-username.github.io`
- Check that GitHub Pages is enabled in Settings → Pages
- Wait 5-10 minutes after first deployment

**Images not loading?**
- Verify image paths are correct
- Make sure `profile.jpg` is in `assets/images/` folder
- Check file names match exactly (case-sensitive)

**Dark mode not working?**
- Clear your browser cache
- Check that `script.js` is loading (check browser console)

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## 📄 License

Feel free to use this template for your own portfolio! Attribution appreciated but not required.

## 🤝 Connect

- **LinkedIn**: [richmond-antor-biswas](https://linkedin.com/in/richmond-antor-biswas-3a5733287)
- **GitHub**: [Richmond-Antor](https://github.com/Richmond-Antor)
- **Email**: antorgm2@gmail.com

---

**Built with ❤️ for showcasing AI and Data Science work**
