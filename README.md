# Aegis Creation

A modern, dark-mode-first AI technology blog built with Astro.

## 🚀 Project Overview

Aegis Creation is a cutting-edge tech blog focused on artificial intelligence, machine learning, and emerging technologies. Built for performance, SEO, and monetization readiness.

## ✨ Features

- **Dark Mode First**: Modern dark theme optimized for readability
- **SEO Optimized**: Built-in meta tags, Open Graph, structured data
- **Blazing Fast**: Static site generation with Astro
- **Monetization Ready**: Ad placements, affiliate sections, newsletter integration
- **Cloudflare Deployment**: Optimized for Cloudflare Pages
- **Extensible Architecture**: Easy to add new features and content

## 🛠️ Tech Stack

- **Framework**: Astro
- **Styling**: CSS with custom properties
- **Deployment**: Cloudflare Pages
- **Content**: Markdown/MDX

## 📁 Project Structure

```
/
├── public/
│   └── favicon.svg
├── src/
│   ├── components/
│   │   ├── Header.astro
│   │   ├── Footer.astro
│   │   ├── BlogCard.astro
│   │   ├── Newsletter.astro
│   │   └── AdPlacement.astro
│   ├── layouts/
│   │   ├── BaseLayout.astro
│   │   └── BlogPost.astro
│   ├── pages/
│   │   ├── index.astro
│   │   ├── blog/
│   │   │   └── index.astro
│   │   └── posts/
│   ├── styles/
│   │   └── global.css
│   └── content/
│       └── blog/
└── package.json
```

## 🚀 Quick Start

```bash
# Install dependencies
npm install

# Start development server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview
```

## 📝 Adding Content

Create new blog posts in `src/content/blog/` as Markdown files:

```markdown
---
title: "Your Post Title"
description: "Post description for SEO"
pubDate: 2025-01-15
author: "Aegis"
tags: ["AI", "Technology"]
---

Your content here...
```

## 🌐 Deployment

This project is configured for Cloudflare Pages:

1. Connect your GitHub repo to Cloudflare Pages
2. Set build command: `npm run build`
3. Set output directory: `dist`
4. Deploy

## 💰 Monetization

The template includes ready-to-use sections for:

- **Display Ads**: Strategic ad placement components
- **Affiliate Links**: Product recommendation sections
- **Newsletter**: Email capture for audience building
- **Sponsored Content**: Dedicated sponsored post layouts

## 🤖 Built by Aegis

This blog is maintained and extended by Aegis, an AI development system working alongside William.

## 📄 License

MIT License - Feel free to use and modify.

---

*Aegis Creation - Where AI Meets Innovation*