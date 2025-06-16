# Sky Sheng - Personal Website

A clean, professional personal website showcasing my work in data science, AI application, AI ethics, and animal welfare science. Built with Jekyll and inspired by modern academic website design.

## 🌟 Features

- **Clean, minimal design** inspired by [Rida Qadri's website](https://ridaqadri.net/)
- **Responsive layout** that works on all devices
- **Academic focus** with sections for research, projects, speaking, and contact
- **Year-organized content** for talks and presentations
- **Professional typography** using Google Fonts (Crimson Text + Source Sans Pro)
- **Fast loading** and optimized for GitHub Pages

## 🚀 Quick Start

### Prerequisites
- Ruby 2.5+ and Bundler
- Git

### Local Development

1. **Clone the repository**
   ```bash
   git clone https://github.com/skysheng7/skysheng7.github.io.git
   cd skysheng7.github.io
   ```

2. **Install dependencies**
   ```bash
   bundle install
   ```

3. **Run locally**
   ```bash
   bundle exec jekyll serve
   ```

4. **View in browser**
   Open `http://localhost:4000` in your browser

### GitHub Pages Deployment

This site is configured to deploy automatically to GitHub Pages when you push to the main branch.

1. **Create a new repository** named `yourusername.github.io`
2. **Push your code** to the main branch
3. **Enable GitHub Pages** in repository settings (source: Deploy from a branch, branch: main)
4. **Your site will be live** at `https://yourusername.github.io`

## 📁 Project Structure

```
├── _config.yml           # Jekyll configuration
├── _layouts/
│   └── default.html      # Main layout template
├── assets/
│   └── css/
│       └── main.css      # Custom styles
├── index.html            # Homepage
├── research.html         # Research & publications page
├── projects.html         # Projects & open source work
├── speaking.html         # Talks & presentations
├── contact.html          # Contact information
├── Gemfile              # Ruby dependencies
└── README.md            # This file
```

## 🎨 Customization

### Adding Your Photo
Replace the placeholder in `index.html`:
```html
<!-- Replace this div with your professional photo -->
<div style="width: 300px; height: 400px; background-color: #f0f0f0; border-radius: 4px; display: flex; align-items: center; justify-content: center; color: #888;">
    Professional Photo
</div>

<!-- With this: -->
<img src="assets/images/your-photo.jpg" alt="Your Name" class="hero-image">
```

### Updating Content
- **Personal information**: Edit `_config.yml`
- **Homepage bio**: Edit `index.html`
- **Publications**: Edit `research.html`
- **Projects**: Edit `projects.html`
- **Talks**: Edit `speaking.html`
- **Contact**: Edit `contact.html`

### Styling
- **Colors & fonts**: Edit `assets/css/main.css`
- **Layout**: Modify `_layouts/default.html`

## 🔧 Configuration

Key settings in `_config.yml`:
```yaml
title: "Your Name"
description: "Your Title | Your Institution"
url: "https://yourusername.github.io"
author:
  name: "Your Full Name"
  email: "your.email@domain.com"
  # Update social links
```

## 📱 Responsive Design

The site is fully responsive with breakpoints at:
- **Desktop**: 1000px+ (full layout)
- **Tablet**: 768px-999px (stacked hero section)
- **Mobile**: <768px (single column, smaller fonts)

## 🎯 SEO & Performance

- Semantic HTML structure
- Optimized meta tags
- Fast-loading Google Fonts
- Compressed CSS
- Mobile-friendly design
- Clean URLs

## 🤝 Contributing

This is a personal website template, but if you find bugs or have suggestions for improvements, feel free to:
1. Fork the repository
2. Create a feature branch
3. Submit a pull request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- Design inspiration from [Rida Qadri's website](https://ridaqadri.net/)
- Built with [Jekyll](https://jekyllrb.com/) and [GitHub Pages](https://pages.github.com/)
- Typography by [Google Fonts](https://fonts.google.com/)

## 📧 Contact

If you have questions about this template or want to discuss collaboration:
- **Email**: skysheng7@gmail.com
- **LinkedIn**: [sky-sheng](https://www.linkedin.com/in/sky-sheng)
- **GitHub**: [skysheng7](https://github.com/skysheng7)

---

*Built with ❤️ for the open science community* 