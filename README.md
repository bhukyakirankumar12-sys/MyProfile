# Personal Portfolio Website - Kiran Kumar Bhukya

A modern, responsive single-page portfolio website showcasing my experience as a Technical Lead and Full Stack .NET Developer with AI-Augmented Engineering expertise.

## 🚀 Features

- **Fully Responsive Design** - Works seamlessly on desktop, tablet, and mobile devices
- **Sticky Navigation** - Easy navigation with smooth scrolling
- **Modern UI/UX** - Built with TailwindCSS for a clean, professional look
- **Smooth Animations** - Fade-in and slide-in animations for enhanced user experience
- **Single Page Application** - All sections accessible via navigation tabs or scroll
- **AI & GenAI Section** - Highlights experience with RAG systems, LangChain, Qdrant, and more
- **Contact Form** - Integrated contact form with mailto functionality

## 📁 File Structure

```
MyProfile/
├── index.html          # Main HTML file
├── css/
│   └── style.css       # Custom CSS styles and animations
├── js/
│   └── main.js         # JavaScript for interactivity
├── assets/
│   ├── profile-photo.jpg  # Your profile photo (add your image)
│   └── resume.pdf         # Your resume PDF (add your resume)
└── README.md           # This file
```

## 🛠️ Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Custom styles and animations
- **JavaScript (ES6+)** - Interactive features
- **TailwindCSS** - Utility-first CSS framework (via CDN)
- **Font Awesome** - Icons
- **Google Fonts** - Inter & Poppins fonts

## 📋 Sections

1. **Hero Section** - Name, title, download resume button, social links
2. **About Me** - Professional background summary
3. **Skills** - Grouped skills with icons (Backend, Frontend, Database, Cloud, Messaging, AI & ML)
4. **Experience Timeline** - Work history with detailed responsibilities
5. **Projects** - Showcase of key projects including AI RAG Chatbot System
6. **AI & GenAI Exposure** - Detailed AI tool usage and RAG system experience
7. **Contact** - Contact form and information

## 🚀 Deployment to GitHub Pages

### Method 1: Using GitHub Web Interface

1. **Create a GitHub Repository**
   - Go to [GitHub](https://github.com) and create a new repository
   - Name it `your-username.github.io` (replace `your-username` with your GitHub username)
   - Make it public

2. **Upload Files**
   - Click "Uploading an existing file"
   - Drag and drop all files from your local `MyProfile` folder
   - Commit the changes

3. **Enable GitHub Pages**
   - Go to repository Settings
   - Scroll to "Pages" section
   - Under "Source", select "Deploy from a branch"
   - Choose "main" branch and "/ (root)" folder
   - Click "Save"

4. **Access Your Site**
   - Your site will be available at `https://your-username.github.io`
   - It may take a few minutes to go live

### Method 2: Using Git Command Line

```bash
# Initialize git repository
git init

# Add all files
git add .

# Commit files
git commit -m "Initial commit: Portfolio website"

# Add remote repository (replace with your repo URL)
git remote add origin https://github.com/your-username/your-username.github.io.git

# Push to GitHub
git branch -M main
git push -u origin main
```

Then enable GitHub Pages in repository Settings > Pages.

## 📝 Customization

### Update Personal Information

1. **Profile Photo**: 
   - Replace `assets/profile-photo.jpg` with your photo
   - Recommended: 400x400px, square aspect ratio

2. **Resume**:
   - Replace `assets/resume.pdf` with your resume
   - Update the download link in `index.html` if needed

3. **Contact Information**:
   - Update email, phone, and social media links in `index.html`
   - Search for `kiran.bhukya@example.com` and replace with your email
   - Update LinkedIn and GitHub URLs

4. **Social Links**:
   - Find the social icon links in the Hero section
   - Update `href` attributes with your actual profile URLs

### Color Scheme

The website uses an indigo-purple gradient theme. To change colors:
- Edit TailwindCSS classes in `index.html`
- Modify gradient colors in `css/style.css`

### Content Updates

- **About Section**: Edit the paragraph text in the About Me section
- **Experience**: Update job titles, companies, and dates in the Experience Timeline
- **Projects**: Modify project cards with your actual projects
- **Skills**: Add or remove skill badges as needed

## 🔧 Local Development

1. **Clone or Download** this repository
2. **Open** `index.html` in a web browser
3. **Make Changes** to HTML, CSS, or JS files
4. **Refresh** browser to see updates

No build process required - it's pure HTML, CSS, and JavaScript!

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🎨 Features in Detail

### Smooth Scrolling
- Clicking navigation links smoothly scrolls to sections
- Active section highlighting in navigation

### Animations
- Fade-in animations on scroll
- Hover effects on cards and buttons
- Smooth transitions throughout

### Responsive Design
- Mobile-first approach
- Hamburger menu for mobile devices
- Optimized layouts for all screen sizes

### Contact Form
- Currently uses `mailto:` functionality
- Can be upgraded to EmailJS for actual email sending
- Form validation included

## 🔄 Future Enhancements

- [ ] Integrate EmailJS for contact form
- [ ] Add dark mode toggle
- [ ] Add blog section
- [ ] Add testimonials section
- [ ] Add analytics tracking
- [ ] Optimize images with WebP format
- [ ] Add PWA capabilities

## 📄 License

This portfolio template is free to use and modify for personal use.

## 👤 Author

**Kiran Kumar Bhukya**
- Technical Lead | Full Stack .NET Developer
- AI-Augmented Engineering Specialist
- 13+ years of experience

## 🙏 Acknowledgments

- TailwindCSS for the utility-first CSS framework
- Font Awesome for beautiful icons
- Google Fonts for typography

---

**Note**: Remember to replace placeholder content (email, phone, social links, profile photo, resume) with your actual information before deploying!
