<p align="center">
  <img src="https://raw.githubusercontent.com/am-abdulmueed/pluginstream/refs/heads/main/assets/Echo-new.png" alt="Echo Music Logo" width="140">
</p>

<h1 align="center">Echo Music Website</h1>

<p align="center">The official website for <strong>Echo Music</strong> - a free, ad-free music streaming app for Android.</p>

---

## Overview

This repository contains the source code for the Echo Music official website. Echo Music is a free, open-source music streaming application for Android that provides an ad-free experience by streaming music directly from YouTube Music.

The website serves as the official landing page for the Echo Music application, providing:
- Feature documentation and app information
- Download links and installation guides
- FAQ and support resources
- Privacy policy and terms of service

---

## Project Structure

```
Echo-Music-Site/
├── index.html              # Main landing page
├── privacy.html            # Privacy Policy
├── terms.html              # Terms of Service
├── robots.txt              # Robots configuration
├── sitemap.xml             # Sitemap
├── README.md               # This file
├── graph.png               # Open Graph image
└── assets/                 # Static assets (images, icons)
```

---

## Getting Started

### Prerequisites
- A modern web browser
- Local web server (optional, for development)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/am-abdulmueed/pluginstream-Site.git
   cd Echo-Music-Site
   ```

2. Run locally:
   
   Using Python:
   ```bash
   python -m http.server 8000
   ```
   
   Using Node.js:
   ```bash
   npx serve .
   ```
   
   Using PHP:
   ```bash
   php -S localhost:8000
   ```

3. Open in browser:
   Navigate to `http://localhost:8000`

---

## Technology Stack

| Category | Technology |
|----------|------------|
| Markup | HTML5 (Semantic markup with accessibility features) |
| Styling | CSS3 (Flexbox, Grid, CSS Variables) |
| Scripting | Vanilla JavaScript (ES6+) |
| Typography | Google Fonts (Inter, Unbounded) |
| SEO | Schema.org structured data |

---

## Browser Support

| Browser | Minimum Version |
|---------|----------------|
| Chrome/Chromium | 80+ |
| Firefox | 75+ |
| Safari | 13+ |
| Edge | 80+ |
| Mobile browsers | Latest versions |

---

## Development

### Code Standards
- Use semantic HTML5 elements for structure
- Follow BEM methodology for CSS class naming
- Write clean, commented JavaScript code
- Maintain WCAG 2.1 AA accessibility standards
- Optimize images and assets for web delivery

### Contribution Workflow
1. Fork the repository
2. Create a feature branch: `git checkout -b feature/description`
3. Make your changes and test thoroughly
4. Commit with clear messages: `git commit -m 'Add feature description'`
5. Push to your fork: `git push origin feature/description`
6. Open a Pull Request with detailed description

See [CONTRIBUTING.md](CONTRIBUTING.md) for detailed guidelines.

---

## Customization

### Branding Changes
- Update app name and meta descriptions in `index.html`
- Replace images in `assets/` directory
- Modify color scheme in `<style>` tag within `index.html` CSS variables

### Content Updates
- Edit feature descriptions in the Features section
- Update FAQ items in the FAQ section
- Modify contact information and external links

---

## Privacy

This website is designed with privacy as a core principle:

- No third-party tracking scripts
- No analytics cookies
- No personal data collection
- No external advertising networks
- Fully open source and auditable

---

## License

This project is licensed under the [MIT License](LICENSE).

Copyright (c) 2024 Echo Music

---

## Support

- **Issues**: [GitHub Issues](https://github.com/am-abdulmueed/pluginstream-Site/issues)
- **Discussions**: [GitHub Discussions](https://github.com/am-abdulmueed/pluginstream-Site/discussions)
- **Discord**: [Echo Music Discord](https://github.com/am-abdulmueed/pluginstream)

---

## Resources

- [Echo Music App Repository](https://github.com/EchoMusicApp)
- [Official Website](https://echomusic.fun)
- [Privacy Policy](https://echomusic.fun/privacy.html)
- [Terms of Service](https://echomusic.fun/terms.html)

---

*Built for the Echo Music community*
