# Han Bao - Personal Website

A minimalist and elegant personal academic homepage built with [Astro](https://astro.build).

## 🎨 Design

- **Color Scheme**: Notre Dame inspired (Navy Blue #0c2340, Gold #c99700)
- **Typography**: Inter (sans-serif) + Source Serif 4 (serif)
- **Style**: Clean, minimalist, modern academic look

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

## 📁 Project Structure

```
astro-website/
├── public/
│   ├── favicon.svg
│   ├── self.jpeg          # Profile photo
│   ├── autobench-v.png    # Paper thumbnail
│   ├── trust.png          # Paper thumbnail
│   └── ND.png             # Notre Dame logo
├── src/
│   ├── layouts/
│   │   └── Layout.astro   # Base layout
│   └── pages/
│       └── index.astro    # Homepage
├── astro.config.mjs
├── package.json
└── tsconfig.json
```

## 📝 Sections

- **Hero**: Name, title, location, profile photo
- **About**: Research interests & PhD seeking announcement
- **Publications**: Preprints with thumbnails
- **Experience**: Research internships
- **Contact**: Email, Google Scholar, LinkedIn
- **Visitor Map**: ClustrMaps integration

## 🔧 Deployment

This site is designed to be deployed on GitHub Pages. Build output goes to `dist/` folder.

## 📄 License

MIT

