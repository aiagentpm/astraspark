# Astra Spark

A minimal, professional landing page for Astra Spark - productivity tools that feel light.

## Features

- Clean, modern design with smooth animations
- Responsive navigation with mobile hamburger menu
- Contact form with validation
- SEO optimized with Open Graph and Twitter Card meta tags
- Accessible design with ARIA labels and semantic HTML
- Smooth scrolling and section transitions

## Design Guide

The design uses a carefully curated color palette:
- **Tangerine**: `#FF8A5C`
- **Mint**: `#A8E6CF`
- **Cream**: `#FFFBF5`
- **Charcoal**: `#2A2D34`

Typography: Outfit font family (weights: 300, 400, 500)

## Local Development

Simply open `astra-spark-minimal.html` in your web browser. No build process required.

## Deployment

### Cloudflare Pages

The repository is already set up on GitHub at: **https://github.com/aiagentpm/astraspark**

To deploy to Cloudflare Pages:

1. Log in to [Cloudflare Dashboard](https://dash.cloudflare.com/)
2. Go to **Pages** → **Create a project**
3. Click **Connect to Git**
4. Select **GitHub** and authorize Cloudflare to access your repositories
5. Select the `astraspark` repository
6. Configure build settings:
   - **Project name**: `astraspark` (or your preferred name)
   - **Production branch**: `main`
   - **Framework preset**: None
   - **Build command**: (leave empty)
   - **Build output directory**: `/` (root)
7. Click **Save and Deploy**

Your site will be live at `https://astraspark.pages.dev` (or your custom project name)

**Note**: The `_headers` file is included for security headers. Cloudflare Pages will automatically apply these headers to all responses.

### Custom Domain

1. In Cloudflare Pages, go to your project
2. Click **Custom domains**
3. Add your domain and follow the DNS configuration instructions

## File Structure

```
.
├── astra-spark-minimal.html  # Main HTML file
├── README.md                  # This file
├── .gitignore                # Git ignore file
└── _headers                   # Cloudflare Pages security headers
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

© 2024 Astra Spark. All rights reserved.

