# 🚀 Deployment Guide - UNLIMITED EXPANSION Website

## 📋 Prerequisites

- GitHub account
- Git installed on your computer
- Basic knowledge of Git commands

## 🔧 Step 1: Create GitHub Repository

1. **Go to GitHub.com** and sign in to your account
2. **Click the "+" icon** in the top right corner
3. **Select "New repository"**
4. **Repository name**: `unlimited-expansion` (or your preferred name)
5. **Description**: `Modern website for UNLIMITED EXPANSION - Creative agency in Togo`
6. **Make it Private** (recommended for business websites)
7. **Don't initialize** with README, .gitignore, or license (we already have these)
8. **Click "Create repository"**

## 🔗 Step 2: Connect Local Repository to GitHub

After creating the repository, GitHub will show you commands. Use these:

```bash
# Add the remote origin (replace YOUR_USERNAME with your GitHub username)
git remote add origin https://github.com/YOUR_USERNAME/unlimited-expansion.git

# Set the main branch (GitHub now uses 'main' by default)
git branch -M main

# Push your code to GitHub
git push -u origin main
```

## 🌐 Step 3: Enable GitHub Pages (Optional)

If you want to host the website on GitHub Pages:

1. **Go to your repository** on GitHub
2. **Click "Settings"** tab
3. **Scroll down to "Pages"** section
4. **Source**: Select "Deploy from a branch"
5. **Branch**: Select "main" and "/ (root)"
6. **Click "Save"**
7. **Wait a few minutes** for deployment
8. **Your site will be available at**: `https://YOUR_USERNAME.github.io/unlimited-expansion`

## 📱 Step 4: Custom Domain (Optional)

To use your own domain (e.g., `www.unlimited-expansion.com`):

1. **In GitHub Pages settings**, add your custom domain
2. **Update your DNS** with your domain provider:
   - Add a CNAME record pointing to `YOUR_USERNAME.github.io`
   - Or add A records pointing to GitHub's IP addresses

## 🔄 Step 5: Regular Updates

When you make changes to your website:

```bash
# Add all changes
git add .

# Commit changes with a descriptive message
git commit -m "Update: [describe your changes]"

# Push to GitHub
git push origin main
```

## 📁 Step 6: File Structure Verification

Ensure your repository has this structure:

```
unlimited-expansion/
├── index.html              # Main website file
├── README.md               # Project documentation
├── LICENSE                 # MIT License
├── .gitignore             # Git ignore rules
├── .gitattributes         # Git attributes
├── DEPLOYMENT.md          # This file
└── assets/
    └── images/            # All your images
        ├── hero-bg.jpg
        ├── a-propos.jpg
        ├── branding-identite.jpg
        ├── objets-goodies.jpg
        ├── sites-web.jpg
        ├── print-grand-format.jpg
        ├── evenementiel.jpg
        ├── agendas-papeterie.jpg
        ├── testimonial-1.jpg
        ├── testimonial-2.jpg
        ├── testimonial-3.jpg
        ├── team-ceo.jpg
        ├── team-web-new.jpg
        ├── team-design-new.jpg
        └── team-production-new.jpg
```

## 🎯 Step 7: Image Optimization

Before pushing to GitHub, optimize your images:

- **Hero background**: Max 500KB, 1920x1080px
- **Service images**: Max 200KB, 800x600px
- **Team photos**: Max 100KB, 400x400px
- **Testimonial avatars**: Max 50KB, 200x200px

Use tools like:
- [TinyPNG](https://tinypng.com/)
- [Squoosh](https://squoosh.app/)
- [ImageOptim](https://imageoptim.com/)

## 🔒 Step 8: Security Considerations

- **Keep repository private** for business websites
- **Don't commit sensitive information** (passwords, API keys)
- **Use environment variables** if adding backend functionality later
- **Regular security updates** for dependencies (if any)

## 📊 Step 9: Analytics & Monitoring

Consider adding:

- **Google Analytics** for visitor tracking
- **Google Search Console** for SEO monitoring
- **Uptime monitoring** services
- **Performance monitoring** tools

## 🚀 Step 10: Go Live!

Your website is now:
- ✅ Version controlled with Git
- ✅ Hosted on GitHub
- ✅ Ready for updates and collaboration
- ✅ Professional and modern design
- ✅ Mobile-responsive
- ✅ SEO-friendly

## 📞 Support

If you need help:
- Check the [README.md](README.md) for technical details
- Review [GitHub documentation](https://docs.github.com/)
- Contact your development team

---

**🎉 Congratulations! Your UNLIMITED EXPANSION website is now live and ready for the world!**
