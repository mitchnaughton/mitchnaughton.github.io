# Dr. Mitch Naughton - Academic Website

A sleek, professional academic website showcasing research, publications, and contact information.

## Features

- **Responsive Design**: Works beautifully on desktop, tablet, and mobile devices
- **Modern Aesthetic**: Clean, professional design with elegant typography
- **Fast Loading**: Pure HTML/CSS/JS with no dependencies
- **SEO Optimized**: Proper meta tags and semantic HTML
- **Accessible**: Following web accessibility best practices

## Pages

1. **Home (index.html)**: 
   - About section with biography
   - Research focus areas
   - Selected publications
   - Contact information

2. **Resources (resources.html)**:
   - Research tools and methodologies
   - Open science practices
   - Student resources
   - Collaboration opportunities
   - External resources and links

## Hosting on GitHub Pages (Free Forever)

Follow these steps to host your website for free on GitHub Pages:

### Step 1: Create a GitHub Account
1. Go to [github.com](https://github.com)
2. Sign up for a free account if you don't have one

### Step 2: Create a New Repository
1. Click the "+" icon in the top right and select "New repository"
2. Name your repository: `yourusername.github.io` (replace `yourusername` with your actual GitHub username)
   - Example: If your username is `mitchnaughton`, name it `mitchnaughton.github.io`
3. Set the repository to **Public**
4. Check "Add a README file"
5. Click "Create repository"

### Step 3: Upload Your Website Files
1. In your repository, click "Add file" → "Upload files"
2. Upload both `index.html` and `resources.html`
3. Click "Commit changes"

### Step 4: Enable GitHub Pages
1. Go to your repository settings (click "Settings" tab)
2. Scroll down to "Pages" in the left sidebar
3. Under "Source", select "Deploy from a branch"
4. Under "Branch", select "main" and "/ (root)"
5. Click "Save"

### Step 5: Access Your Website
Your website will be live at: `https://yourusername.github.io`

**Note**: It may take a few minutes for the site to go live after initial setup.

## Custom Domain (Optional)

If you want to use your own domain name:

1. Purchase a domain from a registrar (e.g., Namecheap, Google Domains)
2. In your repository, create a file named `CNAME` containing your domain name (e.g., `mitchnaughton.com`)
3. Configure your domain's DNS settings:
   - Add an A record pointing to GitHub's IPs:
     - 185.199.108.153
     - 185.199.109.153
     - 185.199.110.153
     - 185.199.111.153
   - Or add a CNAME record pointing to `yourusername.github.io`
4. In repository settings → Pages, add your custom domain

## Updating Your Website

To update content:

1. Edit the HTML files on your computer
2. Go to your GitHub repository
3. Click on the file you want to update
4. Click the pencil icon (Edit this file)
5. Make your changes
6. Scroll down and click "Commit changes"

Your site will automatically update within a few minutes.

## Customization Tips

### Updating Publications
Edit the `index.html` file and locate the `<section id="publications">` section. Add new publications following this format:

```html
<div class="publication">
    <div class="publication-title">Your Publication Title</div>
    <div class="publication-authors">Author names</div>
    <div class="publication-journal">Journal Name, Year</div>
    <a href="URL" class="publication-link" target="_blank">View Publication →</a>
</div>
```

### Changing Colors
In the `<style>` section of both HTML files, modify the CSS variables:

```css
:root {
    --primary: #1a1a1a;      /* Main text color */
    --secondary: #4a4a4a;    /* Secondary text */
    --accent: #2d5a6b;       /* Links and accents */
    --light: #f8f8f8;        /* Background highlights */
    --white: #ffffff;        /* Main background */
    --border: #e0e0e0;       /* Borders */
}
```

### Adding New Sections
Copy an existing `<section>` block and modify the content to suit your needs.

## Technical Details

- **Framework**: Pure HTML5, CSS3, and vanilla JavaScript
- **Fonts**: Google Fonts (Cormorant Garamond and Work Sans)
- **Browser Support**: All modern browsers (Chrome, Firefox, Safari, Edge)
- **No Build Process**: No compilation or dependencies required

## Support

For academic inquiries, research collaboration, or student supervision:
- University Email: mitch.naughton@newcastle.edu.au

For consultancy services, speaking engagements, or professional services:
- Email: naughtonmitch@gmail.com

For technical issues with the website, consult GitHub Pages documentation or web development resources.

## License

This website template is free to use and modify for personal academic purposes.

---

**Last Updated**: February 2026
