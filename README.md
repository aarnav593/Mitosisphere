# Mitosisphere Website

🧬 **Professional biology education platform** - Expert-designed resources for advanced biology competitions and education.

## Features

- **Modern Design**: Beautiful gradient animations, DNA helix visuals, and cell division effects
- **Responsive**: Fully responsive design that works on all devices
- **SEO Optimized**: Comprehensive meta tags, structured data, and sitemap
- **Google Analytics**: Integrated tracking with GA4
- **Smooth Animations**: Typing effects, carousel, snowflakes (seasonal), and scroll-snap sections
- **Performance**: Built with Astro for optimal performance and fast loading times

## 📁 Project Structure

```
/
├── public/
│   ├── Staff_Photos/     # Team member photos
│   ├── partners/         # Partner organization logos
│   ├── favicon.png       # Site favicon
│   ├── logo.png          # Mitosisphere logo
│   ├── robots.txt        # Search engine directives
│   └── CNAME             # Custom domain configuration
├── src/
│   ├── layouts/
│   │   └── Layout.astro  # Main layout with SEO, fonts, and styles
│   └── pages/
│       └── index.astro   # Homepage with all sections
├── astro.config.mjs      # Astro configuration
├── package.json          # Dependencies and scripts
└── tsconfig.json         # TypeScript configuration
```

## 🎨 Design Features

- **Color Palette**: Purple (#9A50D8), Blue (#3FB8D3), Indigo (#6A6AD4)
- **Typography**: Epilogue for body text, JetBrains Mono for logo
- **Animations**: DNA helix rotation, cell division, gradient shifts, snowfall effects
- **Sections**:
  - Hero with typing animation
  - Stats with count-up animation
  - Initiatives carousel (4-second auto-rotation)
  - Competitions showcase with LaTeX formulas
  - Partners display
  - Team grid with leadership tiers

## 📊 SEO Features

- Meta descriptions and keywords
- Open Graph tags for social media
- Twitter Card tags
- Structured data (Schema.org EducationalOrganization)
- Sitemap generation
- Robots.txt configuration

## 🌐 Deployment

The site is configured for deployment to:
- **Domain**: mitosisphere.org (configured in CNAME)
- **Build Command**: `npm run build`
- **Output Directory**: `dist/`

## 📝 Content Management

### Adding Team Members

Team members are displayed in a flexible grid that auto-expands. To add a new member:

1. Add their photo to `public/Staff_Photos/Staff photos/`
2. Update the team section in `src/pages/index.astro` with their information

### Updating Stats

Current stats (as of Dec 2025):
- 1000+ competition participants from 19 countries
- 553+ Discord community members

Update these in the Stats section of `index.astro`.

### Managing Initiatives

The initiatives carousel auto-rotates every 4 seconds. Each initiative card includes:
- Icon emoji
- Title
- Status badge (Active/Coming Soon/Available Now)
- Description
- Optional CTA button

## 🎯 Key Sections

1. **Hero**: Eye-catching introduction with DNA helix animation
2. **Stats**: Dynamic counter animation showing community reach
3. **Initiatives**: Carousel showcasing programs (Competitions, USABO Guide, BioBlitz, etc.)
4. **Competitions**: p+q series details with LaTeX formulas
5. **Partners**: Partner organization logos with hover effects
6. **Team**: Leadership and team member grid

## 🔗 Important Links

- **Discord**: https://discord.gg/Sq3nTXyS6D
- **Staff Application**: https://forms.gle/jePabrYs13KvFSqt9
- **Competition Registration**: https://forms.gle/7oaq31kiAhSstxwY6
- **BioBlitz Mailing List**: https://bioblitz.net/emailList.html
- **Mentorship Application**: https://docs.google.com/forms/d/e/1FAIpQLSeNus46S6bVyhOg34M5q6AKYT6MIoIsTjNDT9EixfXXbRxBCw/viewform

## 📄 License

© 2025 Mitosisphere. All Rights Reserved.

---

**Multiplying Success, One Division at a Time.** 🧬
