# Humanities Data and Mapping Environments (HDME) - a spatial humanities workshop at the [European Summer University in Digital Humanities](https://esudh.github.io) 2025 (Besançon, France) 

## Overview

This workshop introduces participants to digital mapping environments and humanities data curation, designed for beginners who want to explore spatial dimensions in their research.

## Website Features

- **Jekyll Minimal Theme**: Official GitHub Pages minimal theme
- **Responsive Design**: Optimized for desktop, tablet, and mobile devices
- **ESU 2025 Branding**: Features the official ESU 2025 logo
- **Clean Typography**: Academic-focused design with enhanced readability
- **Structured Content**: 
  - Workshop Overview with highlighted introduction
  - Pre-workshop preparation information
  - Detailed 20-session agenda across two weeks

## Technical Details

- **Jekyll**: Static site generator with GitHub Pages integration
- **Theme**: `jekyll-theme-minimal` (official GitHub Pages theme)
- **Styling**: Custom SCSS extending the minimal theme
- **Markdown**: Content written in Markdown with YAML front matter
- **Logo**: ESU 2025 JPG logo integration in sidebar

## Local Development

To run this site locally:

1. **Prerequisites**: Ruby 2.7+ and Bundler
2. **Install dependencies**: `bundle install`
3. **Serve locally**: `bundle exec jekyll serve`
4. **View site**: Visit `http://localhost:4000`

## GitHub Pages Deployment

This site is configured for automatic GitHub Pages deployment:

1. Push files to your GitHub repository
2. Go to **Settings** → **Pages** in your repository
3. Select **Deploy from a branch** and choose your main branch
4. GitHub will automatically build and deploy your site

## Site Structure

```
├── _config.yml          # Jekyll configuration with minimal theme
├── Gemfile              # Ruby dependencies for GitHub Pages
├── assets/
│   ├── css/
│   │   └── style.scss   # Custom SCSS extending minimal theme
│   ├── images/
│   │   └── LogoESU2025.jpg  # ESU 2025 logo
│   └── js/
│       └── scale.fix.js     # Responsive scaling fix
├── index.md             # Main workshop content page
└── README.md            # This documentation
```

## Theme Features

The minimal theme provides:

- **Sidebar Navigation**: Logo, title, description, and optional links
- **Clean Layout**: Focus on content with minimal distractions  
- **Mobile Responsive**: Sidebar converts to header on mobile devices
- **Typography**: Professional fonts optimized for readability
- **GitHub Integration**: Optional repository links and download buttons

## Customizations

Custom enhancements include:

- **Logo Styling**: Rounded corners and subtle shadow
- **Typography**: Enhanced heading hierarchy and colors
- **Workshop Layout**: Special styling for workshop overview section
- **Responsive Improvements**: Better mobile experience
- **Print Styles**: Optimized for printing/PDF generation

## Workshop Content

**Week 1**: Foundations and Data Creation (Sessions 1-10)
- Critical review of spatial humanities projects
- Data creation and acquisition techniques  
- Basic querying and normalization

**Week 2**: Visualization and Advanced Techniques (Sessions 11-20)
- Static site development
- Advanced visualization and storytelling
- GIS software and historical mapping

## Credits

This site was created based on the [Jekyll Slate](https://pages-themes.github.io/slate/) theme customized with Claude Sonnet 4.
The logo is from [ESUDH 2025](https://esudh.github.io). 

