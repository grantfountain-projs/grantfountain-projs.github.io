# Portfolio Website

A clean, professional portfolio website showcasing your QA automation and software development projects.

## Quick Start - Deployment to GitHub Pages

### Step 1: Customize Your Content

Before deploying, update these items in `index.html`:

**Required Changes:**
1. **Line 50:** Replace `your.email@example.com` with your actual email
2. **Line 51:** Replace `https://linkedin.com/in/yourprofile` with your LinkedIn URL
3. **Line 52:** Replace `https://github.com/yourusername` with your GitHub profile URL
4. **Line 86:** Update Fantasy Football GitHub link (replace `yourusername`)
5. **Line 103:** Update WolfCafe GitHub link (replace `yourusername`)
6. **Line 118:** Verify OpenDI GitHub link is correct

**Optional Changes:**
- Update the header gradient colors (line 21-22 in HTML, or edit CSS variables in style.css)
- Modify project descriptions if needed
- Add or remove skills based on what you want to emphasize

### Step 2: Create GitHub Repository

1. Go to [GitHub.com](https://github.com) and create a new repository
2. Name it: `yourusername.github.io` (replace `yourusername` with your actual GitHub username)
   - Example: If your username is `grantsmith`, name it `grantsmith.github.io`
3. Make it **Public**
4. Don't initialize with README (we already have files)
5. Click "Create repository"

### Step 3: Push Your Files to GitHub

Open your terminal and navigate to the portfolio folder:

```bash
cd /path/to/portfolio

# Initialize git (if not already done)
git init

# Add all files
git add .

# Commit
git commit -m "Initial portfolio website"

# Add your GitHub repository as remote
git remote add origin https://github.com/yourusername/yourusername.github.io.git

# Push to GitHub
git branch -M main
git push -u origin main
```

### Step 4: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click "Settings" (top right)
3. Click "Pages" in the left sidebar
4. Under "Source", select "Deploy from a branch"
5. Under "Branch", select **main** and **/ (root)**
6. Click "Save"

### Step 5: Access Your Live Site

Your portfolio will be live at: `https://yourusername.github.io`

GitHub Pages typically takes 1-5 minutes to deploy. Once it's live, you can share this link on:
- Your resume
- LinkedIn profile
- Job applications
- Email signature

## File Structure

```
portfolio/
├── index.html          # Main HTML file with all content
├── style.css           # All styling and responsive design
├── script.js           # Navigation and smooth scrolling
└── README.md           # This file
```

## Customization Tips

### Colors
To change the color scheme, edit these CSS variables in `style.css` (lines 9-16):

```css
--primary-color: #2563eb;      /* Main blue color */
--secondary-color: #1e40af;    /* Darker blue for hovers */
--text-color: #1f2937;         /* Main text color */
```

### Adding More Projects
Copy the project div structure in `index.html` (around lines 72-121) and paste it below the existing projects.

### Sections Order
The sections appear in this order:
1. About
2. Projects
3. Experience
4. Skills
5. Contact

To reorder, just move the `<section>` blocks in the HTML.

## Mobile Responsive

The site is fully responsive and looks great on:
- Desktop (1920px+)
- Laptop (1024px - 1920px)
- Tablet (768px - 1024px)
- Mobile (320px - 768px)

## Browser Support

Works on all modern browsers:
- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers

## Troubleshooting

**Site not showing up after 5 minutes?**
- Check that your repository is named exactly `yourusername.github.io`
- Verify GitHub Pages is enabled in Settings → Pages
- Make sure the branch is set to "main" and folder is "/ (root)"
- Try hard-refreshing your browser (Ctrl+Shift+R or Cmd+Shift+R)

**Navigation not working?**
- Make sure `script.js` is in the same folder as `index.html`
- Check browser console for any JavaScript errors

**Styling looks broken?**
- Verify `style.css` is in the same folder as `index.html`
- Check that the `<link>` tag in HTML points to the correct file

## Future Updates

When you want to update your portfolio:

1. Edit the files locally
2. Commit changes: `git add . && git commit -m "Update portfolio"`
3. Push to GitHub: `git push`
4. GitHub Pages will automatically rebuild (1-2 minutes)

## Next Steps

After deploying this portfolio:
1. Start building your gym tracker project to practice React
2. Once comfortable with React, rebuild this portfolio in React
3. Add more projects as you complete them
4. Keep your GitHub repositories updated and public

---

**Remember:** This is your professional website. Keep it updated as you build new projects and gain new skills!
