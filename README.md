# 🍼 Sanjeevani Foods Website

A beautiful, minimal website for Sanjeevani Foods - showcasing homemade, nutritious, and healthy food for babies, made with mother's love.

## 🌟 Features

- **Responsive Design**: Works perfectly on all devices (desktop, tablet, mobile)
- **Warm & Maternal Theme**: Soft colors and loving design aesthetic
- **Smooth Animations**: Gentle, engaging animations throughout
- **Clean & Minimal**: Easy to navigate with a focus on content
- **SEO Optimized**: Proper meta tags and semantic HTML
- **Fast Loading**: No dependencies except Google Fonts

## 🎨 Design Theme

The website embodies:
- 💗 Mother's love and care
- 🏠 Homemade goodness
- 👶 Baby-focused nutrition
- 🌱 Natural and organic feel
- ✨ Clean and trustworthy presentation

## 📁 File Structure

```
Website/
├── index.html          # Main HTML file
├── style.css           # All styling and animations
└── README.md          # This file
```

## 🚀 Hosting on GitHub Pages

### Step 1: Create a GitHub Repository

1. Go to [GitHub](https://github.com) and sign in
2. Click on "New Repository" (green button)
3. Name your repository (e.g., `sanjeevani-foods`)
4. Make it public
5. Click "Create repository"

### Step 2: Upload Files

**Option A: Using Git Command Line**

```bash
# Navigate to your website folder
cd "d:\Harish\Website"

# Initialize git repository
git init

# Add all files
git add .

# Commit files
git commit -m "Initial commit: Sanjeevani Foods website"

# Add your GitHub repository as remote
git remote add origin https://github.com/YOUR_USERNAME/sanjeevani-foods.git

# Push to GitHub
git branch -M main
git push -u origin main
```

**Option B: Using GitHub Web Interface**

1. In your new repository, click "uploading an existing file"
2. Drag and drop `index.html`, `style.css`, and `README.md`
3. Click "Commit changes"

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click on "Settings" tab
3. Scroll down to "Pages" in the left sidebar
4. Under "Source", select "main" branch
5. Click "Save"
6. Your website will be live at: `https://YOUR_USERNAME.github.io/sanjeevani-foods/`

### Step 4: Custom Domain (Optional)

To use `sanjeevanifood.co.in` domain:

1. In GitHub Pages settings, add your custom domain
2. In your domain registrar (where you bought the domain):
   - Add a CNAME record pointing to `YOUR_USERNAME.github.io`
   - Or add A records pointing to GitHub Pages IPs:
     - 185.199.108.153
     - 185.199.109.153
     - 185.199.110.153
     - 185.199.111.153
3. Wait for DNS propagation (can take up to 24-48 hours)

## 🎯 Sections Overview

1. **Hero Section**: Welcoming introduction with tagline
2. **About**: Story and promises
3. **Products**: Six categories of baby food offerings
4. **Benefits**: Six key reasons to choose Sanjeevani Foods
5. **Testimonials**: Happy parent reviews
6. **Contact**: Ways to get in touch

## 🛠️ Customization

### Changing Colors

Edit the CSS variables in `style.css`:

```css
:root {
    --primary-color: #FF9A9E;      /* Main brand color */
    --secondary-color: #FAD0C4;    /* Secondary accents */
    --accent-color: #FFC3A0;       /* Call-to-action buttons */
    /* ... more colors */
}
```

### Updating Content

Edit the HTML in `index.html`:
- Update text directly in the HTML tags
- Change contact information in the contact section
- Modify product cards, testimonials, or any other content

### Adding Images

1. Create an `images` folder in your website directory
2. Add your images there
3. Reference them in HTML: `<img src="images/your-image.jpg" alt="Description">`

## 📱 Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## 🎨 Fonts Used

- **Quicksand**: Primary font (clean and friendly)
- **Caveat**: Accent font (handwritten, personal touch)

Both fonts are loaded from Google Fonts, no local installation needed.

## 📄 License

This website is created for Sanjeevani Foods. All rights reserved.

## 💡 Tips for Success

1. **Keep Content Fresh**: Update testimonials and product offerings regularly
2. **Add Real Images**: Replace emoji icons with actual food photos when available
3. **Social Media**: Add social media links in the footer
4. **Analytics**: Consider adding Google Analytics to track visitors
5. **Contact Form**: You can add a contact form using services like Formspree or Netlify Forms

## 🤝 Support

For questions or support with this website:
- Email: info@sanjeevanifood.co.in
- Website: [sanjeevanifood.co.in](https://sanjeevanifood.co.in)

## 📝 Notes

- No build process required - just HTML, CSS, and vanilla JavaScript
- No external dependencies except Google Fonts
- Fast, lightweight, and SEO-friendly
- Perfect for GitHub Pages hosting

---

Made with 💗 for the little ones | © 2026 Sanjeevani Foods
