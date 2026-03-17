# Asterweg - Under Construction

This is the GitHub Pages site for **www.asterweg.com**, a clean and minimalist under-construction landing page.

## Features

- 🎨 Clean, minimalist design with white background
- 📱 Fully responsive design (mobile-friendly)
- 📊 Subtle animated progress bar
- 🎯 Simple call-to-action button (Learn More)
- 🔗 Social media links section
- 🔤 Plus Jakarta Sans typography

## Deployment

This site is automatically deployed to GitHub Pages when changes are pushed to the `main` branch.

### Custom Domain

The site uses a custom domain configured via the `CNAME` file:
- **Domain**: `www.asterweg.com`

To set up DNS, add the following CNAME record to your domain registrar:
```
www.asterweg.com CNAME <your-github-username>.github.io
```

## File Structure

```
├── index.html           # Main landing page
├── CNAME               # Custom domain configuration
└── README.md           # This file
```

## Customization

### Update Social Links
Modify the social media links in the social-icons section:
```html
<a href="https://twitter.com/yourprofile" class="social-icon" target="_blank">𝕏</a>
```

### Change Colors
Edit the background and accent colors in the CSS:
```css
body {
    background: #ffffff;  /* Main background */
    color: #1a1a1a;       /* Text color */
}

.btn-secondary {
    border: 1px solid #1a1a1a;  /* Button border */
}
```

### Modify Typography
The site uses [Plus Jakarta Sans](https://fonts.google.com/specimen/Plus+Jakarta+Sans) from Google Fonts. To change the font, update the Google Fonts import and font-family declarations in `index.html`.

## Local Testing

Simply open `index.html` in your browser to preview the site locally.

## License

MIT - Feel free to use this template for your own under-construction page!
