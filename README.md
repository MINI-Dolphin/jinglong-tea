# 景龙茶叶 JingLong Tea

[![Deploy to GitHub Pages](https://github.com/YOUR_USERNAME/jinglong-tea/actions/workflows/deploy.yml/badge.svg)](https://github.com/YOUR_USERNAME/jinglong-tea/actions/workflows/deploy.yml)

Premium Pu-erh Tea from Yunnan, China

## 🌐 Live Site

- **GitHub Pages**: https://YOUR_USERNAME.github.io/jinglong-tea
- **Custom Domain**: https://jinglonghao.dpdns.org

## 📋 Setup Instructions

### 1. Create GitHub Repository
1. Go to https://github.com/new
2. Repository name: `jinglong-tea`
3. Make it **Public**
4. Click "Create repository"

### 2. Push Code to GitHub
```bash
git remote add origin https://github.com/YOUR_USERNAME/jinglong-tea.git
git branch -M main
git push -u origin main
```

### 3. Enable GitHub Pages
1. Go to repository **Settings**
2. Click **Pages** in the left sidebar
3. Under "Build and deployment", select **Source: GitHub Actions**
4. The workflow will automatically deploy your site

### 4. Configure Custom Domain (DigitalPlat)
1. Go to https://dash.domain.digitalplat.org
2. Find your domain `jinglonghao.dpdns.org`
3. Add CNAME record:
   - Type: CNAME
   - Host: `jinglonghao`
   - Value: `YOUR_USERNAME.github.io`
4. Wait for DNS propagation (5-30 minutes)

## 🎨 Website Features

- **Hero Section**: Full-screen banner with brand slogan
- **About**: Company story with statistics
- **Products**: 6 Pu-erh tea products with pricing
- **Heritage**: Brand timeline and philosophy
- **Brewing Guide**: Step-by-step brewing instructions
- **Testimonials**: Customer reviews
- **Contact**: Contact form and information

## 📝 Customization

To customize the website:
1. Edit `index.html` for content changes
2. Modify images in `images/` folder
3. Update `CNAME` file if using different custom domain

## 📄 License

© 2024 JingLong Tea Factory. All rights reserved.
