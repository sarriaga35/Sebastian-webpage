# Sebastián Arriaga - Professional Portfolio Website

Personal portfolio website showcasing professional experience as an Electrical Engineer specializing in Industrial Automation & Control Systems.

## 🚀 Quick Start

This is a static HTML website built with Tailwind CSS (via CDN). No build process required - simply open `index.html` in a browser.

### Local Development

1. Clone the repository:
   ```bash
   git clone https://github.com/sarriaga35/Sebastian-webpage.git
   cd Sebastian-webpage
   ```

2. Open `index.html` in your web browser

## 📁 Project Structure

```
Sebastian-website/
├── index.html              # Main landing page
├── plc-projects.html       # PLC programming use cases
├── scada.html              # SCADA & Node-RED projects
├── it-ot.html              # IT/OT secure telemetry architecture
├── testing.html            # FAT, SAT & Commissioning methodology
├── README.md               # This file
└── .gitignore              # Git ignore rules
```

## 🛠️ Tech Stack

- **HTML5** - Semantic markup
- **Tailwind CSS** - Utility-first CSS framework (via CDN)
- **Vanilla JavaScript** - Interactive components (HMI simulator)
- **SVG Icons** - Inline SVG icons for performance

## 🌐 Deployment

### Cloudflare Pages

This website is configured for automatic deployment via Cloudflare Pages connected to GitHub:

1. Connect your GitHub repository to Cloudflare Pages
2. Set build command to empty (static site)
3. Set output directory to `/` (root)
4. Deploy automatically on push to main branch

### Manual Deployment

Simply upload the HTML files to any static hosting service:
- Netlify
- Vercel
- GitHub Pages
- Any web server

## 📝 Content Sections

- **About** - Professional summary and expertise
- **Expertise** - Portfolio categories with detailed use cases
- **PLC Programming** - Ladder Logic and Structured Text projects
- **SCADA & HMI** - Ignition integration and Node-RED dashboards
- **IT/OT Networks** - Secure telemetry and VPN architectures
- **Testing & Commissioning** - FAT/SAT methodologies

## 🎨 Customization

### Color Scheme

The site uses a custom industrial color theme defined in Tailwind config:

```javascript
colors: {
    industrial: {
        900: '#0f172a',  // Dark slate background
        800: '#1e293b',  // Secondary background
        700: '#334155',  // Borders
        accent: '#3b82f6', // Blue accent
        safe: '#22c55e',    // Green accent
    }
}
```

### Adding New Projects

1. Create a new HTML file following the template of `plc-projects.html`
2. Add a link card in the `index.html` expertise section
3. Ensure consistent navigation and styling

## 📧 Contact

- Email: [Add your email]
- LinkedIn: [Add your LinkedIn profile]
- GitHub: https://github.com/sarriaga35

## 📄 License

© 2026 Sebastián Arriaga. All rights reserved.

---

**Note:** This website uses Tailwind CSS via CDN for development convenience. For production, consider using a build process with npm and the Tailwind CLI for optimized CSS.
