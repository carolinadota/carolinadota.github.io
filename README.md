# Carolina Dota's Website

A modern, responsive website built with Astro - a next-generation static site generator.

## 🚀 Features

- **Modern Design**: Clean, professional layout with beautiful gradients and animations
- **Responsive**: Works perfectly on desktop, tablet, and mobile devices
- **Fast**: Built with Astro for optimal performance and SEO
- **Accessible**: Semantic HTML and proper contrast ratios
- **GitHub Pages Ready**: Configured for deployment to GitHub Pages

## 📁 Project Structure

```
├── public/                 # Static assets
│   └── favicon.svg        # Site favicon
├── src/
│   ├── components/        # Reusable Astro components
│   │   ├── Header.astro
│   │   └── Footer.astro
│   ├── layouts/           # Page layouts
│   │   └── Layout.astro
│   ├── pages/             # Pages (file-based routing)
│   │   ├── index.astro    # Homepage
│   │   ├── about.astro    # About page
│   │   └── contact.astro  # Contact page
│   └── styles/            # Global styles
│       └── global.css
├── astro.config.mjs       # Astro configuration
└── package.json           # Dependencies and scripts
```

## 🛠️ Getting Started

### Prerequisites

- Node.js (version 18 or higher)
- npm or yarn

### Installation

1. **Install dependencies:**
   ```bash
   npm install
   ```

2. **Start the development server:**
   ```bash
   npm run dev
   ```

3. **Open your browser:**
   Navigate to `http://localhost:4321` to see your website.

### Available Scripts

- `npm run dev` - Start the development server
- `npm run build` - Build the site for production
- `npm run preview` - Preview the production build locally
- `npm run astro` - Run Astro CLI commands

## 🎨 Customization

### Colors
The site uses a modern color palette with:
- Primary: `#667eea` (Purple-blue)
- Secondary: `#764ba2` (Purple)
- Background: `#f8f9fa` (Light gray)
- Text: `#333` (Dark gray)

### Typography
- Font: System UI fonts (system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto)

### Layout
- Max width: 1200px
- Responsive breakpoint: 768px
- Grid system for feature cards and contact form

## 📱 Pages

- **Homepage** (`/`): Hero section with call-to-action buttons and feature grid
- **About** (`/about`): Personal information and skills showcase
- **Contact** (`/contact`): Contact information and message form

## 🚀 Deployment

### GitHub Pages

This project is configured for GitHub Pages deployment:

1. **Build the site:**
   ```bash
   npm run build
   ```

2. **Deploy to GitHub Pages:**
   The site will be available at `https://carolinadota.github.io`

### Other Platforms

You can deploy to any static hosting service:
- Netlify
- Vercel
- Cloudflare Pages
- AWS S3 + CloudFront

## 🔧 Configuration

### Astro Config (`astro.config.mjs`)
- Site URL: `https://carolinadota.github.io`
- Base path: `/` (root)

### Package.json
- Astro version: ^4.0.0
- TypeScript support included
- Development and build scripts configured

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Feel free to submit issues and enhancement requests!

---

Built with ❤️ using [Astro](https://astro.build/)
