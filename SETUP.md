# Portfolio Setup Guide 🚀

Welcome to your personal portfolio project! This guide will help you get started and customize the portfolio to reflect your personal information and projects.

## 📋 Quick Setup Checklist

### Step 1: Personal Information ✏️
Edit the following files to add your personal details:

**In `index.html`:**
- [ ] Update your name in the navigation and home section
- [ ] Replace the bio/introduction text
- [ ] Update contact information (email, phone, location)
- [ ] Modify social media links
- [ ] Update education details in the about section
- [ ] Replace experience information

**In `about.html`:**
- [ ] Update detailed about information
- [ ] Modify education timeline
- [ ] Update interests and hobbies
- [ ] Replace personal information section

**In `projects.html`:**
- [ ] Replace sample projects with your actual projects
- [ ] Update project descriptions and features
- [ ] Modify technology stacks used
- [ ] Update project links and demos

### Step 2: Images 📸
Add your images to the `/images/` folder:

- [ ] **profile.jpg** - Your professional profile picture (400x400px)
- [ ] **project1.jpg** - E-Commerce Website screenshot
- [ ] **project2.jpg** - Student Management System screenshot
- [ ] **project3.jpg** - Weather App screenshot
- [ ] **project4.jpg** - Portfolio Website screenshot
- [ ] **project5.jpg** - Task Manager screenshot
- [ ] **project6.jpg** - Calculator App screenshot

### Step 3: Customization 🎨

**Colors (in `css/style.css`):**
- Primary color: `#2563eb` (blue)
- Secondary color: `#7c3aed` (purple)
- Background: `#f8fafc` (light gray)
- Text: `#1e293b` (dark)

**Fonts:**
- Currently using "Poppins" from Google Fonts
- To change: update the font import and CSS font-family

### Step 4: Content Updates 📝

**Skills Section:**
- Update programming languages you know
- Modify web development technologies
- Add/remove tools and frameworks

**Projects Section:**
- Replace with your actual projects
- Update project descriptions
- Add real GitHub/demo links
- Modify technology tags

**Experience Section:**
- Add your internships
- Include work experience
- Update education details

### Step 5: Links and Contact 🔗

**Social Media Links:**
Update the href attributes in all social link elements:
```html
<a href="https://github.com/yourusername" class="social-link">
<a href="https://linkedin.com/in/yourprofile" class="social-link">
<a href="mailto:your.email@domain.com" class="social-link">
```

**Project Links:**
Update project demo and GitHub links:
```html
<a href="https://your-project-demo.com" class="project-link">
<a href="https://github.com/yourusername/project-repo" class="project-link">
```

### Step 6: Testing 🧪

Test your portfolio:
- [ ] Check all links work correctly
- [ ] Test responsive design on mobile
- [ ] Verify contact form functionality
- [ ] Test navigation between pages
- [ ] Check image loading
- [ ] Validate HTML/CSS

### Step 7: Deployment 🌐

Choose a deployment platform:

**GitHub Pages (Free):**
1. Push code to GitHub repository
2. Go to repository Settings → Pages
3. Select source branch (main)
4. Your site: `https://username.github.io/repository-name`

**Netlify (Free):**
1. Create Netlify account
2. Connect GitHub repository
3. Auto-deploy on commits

**Vercel (Free):**
1. Install Vercel CLI: `npm i -g vercel`
2. Run `vercel` in project directory
3. Follow prompts

## 🛠️ Customization Tips

### Adding New Projects
1. Copy existing project card structure
2. Update image, title, description
3. Modify technology tags
4. Add to appropriate category filter

### Changing Color Scheme
1. Define CSS custom properties for colors
2. Update throughout stylesheet
3. Test contrast for accessibility

### Adding New Sections
1. Create HTML structure
2. Add corresponding CSS styles
3. Update navigation if needed
4. Test responsive design

### Performance Optimization
- Compress images before uploading
- Minify CSS/JS for production
- Use WebP format for images
- Enable browser caching

## 📱 Mobile Optimization

The portfolio is already mobile-responsive, but you can:
- Test on actual devices
- Adjust breakpoints if needed
- Optimize touch interactions
- Ensure text is readable

## 🔧 Common Customizations

**Adding a Blog Section:**
1. Create `blog.html`
2. Add navigation link
3. Style blog posts
4. Consider using a static site generator

**Dark Mode Toggle:**
1. Add toggle button
2. Define dark theme CSS
3. Use JavaScript to switch themes
4. Store preference in localStorage

**Multi-language Support:**
1. Create language files
2. Add language switcher
3. Implement translation logic
4. Update all text content

## ❓ Troubleshooting

**Images not loading:**
- Check file paths are correct
- Ensure images are in `/images/` folder
- Verify image file names match HTML

**Styles not applying:**
- Check CSS file is linked correctly
- Verify CSS syntax
- Clear browser cache

**Layout issues on mobile:**
- Test on actual devices
- Use browser developer tools
- Check viewport meta tag

## 📞 Need Help?

If you encounter issues:
1. Check browser console for errors
2. Validate HTML/CSS syntax
3. Test in different browsers
4. Refer to documentation
5. Contact for support: naomi.yadav@email.com

## 🎯 Final Tips

- Keep content updated regularly
- Add new projects as you complete them
- Optimize for search engines (SEO)
- Get feedback from peers
- Monitor website analytics
- Backup your code regularly

Good luck with your portfolio! 🌟

---

**Remember:** This portfolio represents you professionally, so make sure all information is accurate and up-to-date. Take time to craft compelling project descriptions and highlight your best work.
