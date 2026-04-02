# 🚀 Digital Agency Website

## 🎯 Overview

This Digital Agency website is a professional, modern landing page designed to showcase digital services and help businesses attract clients. It features a clean design, intuitive navigation, and multiple sections to highlight services, expertise, and latest news/blogs.
A modern, responsive digital agency website showcasing services, team expertise, and business solutions. Built with pure HTML and CSS for fast performance and lightweight delivery.


**Repository:** [https://github.com/Ahammad204/Digital-Agency.git](https://github.com/Ahammad204/Digital-Agency.git)

---

## 🌐 Live Demo

Once deployed to GitHub Pages, your site will be live at:

**Live Link:** [https://ahammad204.github.io/Digital-Agency/](https://ahammad204.github.io/Digital-Agency/)


**See [Setup for GitHub Pages](#setup-for-github-pages) section for deployment instructions.**


## 📋 Table of Contents

- [Overview](#overview)
- [Live Demo](#live-demo)
- [Features](#features)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Setup for GitHub Pages](#setup-for-github-pages)
- [Customization](#customization)
- [Browser Compatibility](#browser-compatibility)
- [Contributing](#contributing)
- [Author](#author)
- [License](#license)

---


---

## ✨ Features

### 🎨 **Hero Banner Section**
- Eye-catching full-screen banner with background image and overlay
- Prominent call-to-action buttons ("Discover Me" & "Hire Us Now")
- Professional headline and descriptive text

### 🔧 **Services Showcase**
- Grid-based service display with 4 service cards
- Service icons for visual appeal
- Detailed service descriptions
- CEO/Director testimonial section
- "More Details" button for engagement

### 📞 **Free Consultation Section**
- Phone call icon with contact number
- Quick appointment booking call-to-action
- Eye-catching brown background for emphasis

### 📝 **Blog & News Section**
- Modern card layout with image, title, and description
- Multiple blog cards for latest updates
- Professional spacing and typography

### 🧭 **Navigation**
- Fixed header with logo and navigation menu
- Menu items: Home, Services, About, Contact
- Professional gray color scheme

### 📱 **Responsive Design**
- Mobile-friendly viewport settings
- Flexible layouts using CSS Flexbox
- Clean, semantic HTML structure

---

## 📂 Project Structure

```
Digital-Agency/
├── index.html              # Main HTML file
├── style.css               # Stylesheet
├── README.md               # Project documentation (this file)
└── asset/
    ├── icons/              # Service icons (bar-chart.png, phone-call.png, etc.)
    ├── image/              # Images (background.jpg, blog-1.jpg, author.jpg, footer-bg.png)
    └── logo/               # Logo assets (logo.png)
```

---

## 🛠️ Installation

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- No server or build tools required!

### Steps

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Ahammad204/Digital-Agency.git
   cd Digital-Agency
   ```

2. **Open in browser:**
   - Double-click `index.html` **OR**
   - Right-click and select "Open with" → Choose your browser

3. **Alternative - Use a local server (optional):**
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Python 2
   python -m SimpleHTTPServer 8000
   
   # Using Node.js (with http-server package)
   npx http-server
   ```
   Then open `http://localhost:8000` in your browser.

---

## 🚀 Setup for GitHub Pages (Live Link)

GitHub Pages automatically deploys your website from your repository. Follow these steps to make your site live:

### Option 1: Automatic Deployment (Recommended)

1. **Push code to GitHub:**
   ```bash
   git add .
   git commit -m "Initial commit"
   git push origin main
   ```

2. **Enable GitHub Pages:**
   - Go to your repository on GitHub
   - Click **Settings** → **Pages** (left sidebar)
   - Under "Source," select **Deploy from a branch**
   - Choose branch: **main** (or **master**)
   - Select folder: **/ (root)**
   - Click **Save**

3. **Wait for deployment:**
   - GitHub will build and deploy your site (usually takes 1-2 minutes)
   - You'll see a green checkmark when complete
   - Your site will be live at: `https://yourusername.github.io/Digital-Agency`

### Option 2: Using GitHub Actions (For More Control)

1. Create `.github/workflows/deploy.yml` in your repo:
   ```yaml
   name: Deploy to GitHub Pages
   on:
     push:
       branches: [main]
   jobs:
     deploy:
       runs-on: ubuntu-latest
       steps:
         - uses: actions/checkout@v2
         - name: Deploy
           uses: peaceiris/actions-gh-pages@v3
           with:
             github_token: ${{ secrets.GITHUB_TOKEN }}
             publish_dir: ./
   ```

2. Push and GitHub will automatically deploy on every push to main branch.

### Verify Deployment

After enabling GitHub Pages:
- Check the **Deployments** section in your GitHub repository
- Your live URL will be visible there
- Share `https://yourusername.github.io/Digital-Agency` with clients and partners!

---

## 🎨 Customization

### Changing Colors
Edit `style.css` and modify these color values:
- **Primary color (Red):** Change `color: red;` to your desired color
- **Background color:** Modify `background-color` properties
- **Text colors:** Update `color: antiquewhite;` sections

**Example:**
```css
.primary {
    color: #007bff;  /* Change from red to blue */
}
```

### Updating Content
Edit `index.html` to change:
- **Company name & title:** Change `<title>` and `<h1>` tags
- **Navigation menu:** Update menu items in `<ul><li>` elements
- **Services:** Modify service boxes and descriptions
- **Contact number:** Update in appointment section
- **Blog posts:** Add/remove card elements

### Replacing Images
1. Add new images to `asset/image/` or `asset/icons/`
2. Update image paths in HTML:
   ```html
   <img src="./asset/image/your-image.jpg" alt="Description">
   ```

### Adding a Footer
Uncomment the footer section in `index.html` and add content:
```html
<footer>
    <p>&copy; 2024 Digital Agency. All rights reserved.</p>
</footer>
```

---

## 🌐 Browser Compatibility

| Browser | Support |
|---------|---------|
| Chrome | ✅ Full Support |
| Firefox | ✅ Full Support |
| Safari | ✅ Full Support |
| Edge | ✅ Full Support |
| IE 11 | ⚠️ Limited (Flexbox may not work perfectly) |

---

## 📖 How to Use

1. **Navigate the site:** Use the menu bar to jump between sections
2. **Call-to-action buttons:** "Discover Me" and "Hire Us Now" buttons engage visitors
3. **Contact:** Use the "Make Appointment" button to trigger contact flows
4. **Share:** Once live on GitHub Pages, share your URL with clients and potential partners

---

## 🤝 Contributing

Contributions are welcome! Here's how to help:

1. **Fork the repository**
   ```bash
   git clone https://github.com/Ahammad204/Digital-Agency.git
   cd Digital-Agency
   ```

2. **Create a feature branch:**
   ```bash
   git checkout -b feature/amazing-feature
   ```

3. **Make your changes** and commit:
   ```bash
   git add .
   git commit -m "Add amazing feature"
   ```

4. **Push to branch:**
   ```bash
   git push origin feature/amazing-feature
   ```

5. **Open a Pull Request** on GitHub

---

## ✍️ Author

**Ahammad** - Digital Agency Developer

- GitHub: [@Ahammad204](https://github.com/Ahammad204)
- Repository: [Digital-Agency](https://github.com/Ahammad204/Digital-Agency)

---

## 📄 License

This project is licensed under the **MIT License** - feel free to use it for personal and commercial projects.

You are free to:
- ✅ Use the code
- ✅ Modify the code
- ✅ Distribute the code
- ✅ Use for commercial purposes

---

## 🆘 Support & Issues

If you encounter any issues:

1. Check that all image files exist in `asset/` folder
2. Verify file paths in HTML match your folder structure
3. Clear browser cache (Ctrl+Shift+Delete / Cmd+Shift+Delete)
4. Try a different browser
5. Open an issue on [GitHub Issues](https://github.com/Ahammad204/Digital-Agency/issues)

---

## 🎯 Next Steps

- [ ] Deploy to GitHub Pages
- [ ] Add interactive features with JavaScript
- [ ] Improve mobile responsiveness
- [ ] Add contact form functionality
- [ ] Integrate with email service
- [ ] Add analytics tracking
- [ ] SEO optimization
- [ ] Performance optimization

---

## 📱 Quick Links

- **Live Website:** `https://yourusername.github.io/Digital-Agency` (After GitHub Pages setup)
- **GitHub Repository:** [https://github.com/Ahammad204/Digital-Agency.git](https://github.com/Ahammad204/Digital-Agency.git)
- **Report Issues:** [GitHub Issues](https://github.com/Ahammad204/Digital-Agency/issues)

---

**Made with ❤️ by Ahammad**

Last updated: April 2, 2026
