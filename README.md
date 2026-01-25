# Personal Portfolio Website

A modern, responsive personal portfolio website perfect for showcasing your work on LinkedIn, CV, or any professional platform.

## Features

- ✨ Modern and clean design
- 📱 Fully responsive (works on all devices)
- 🎨 Beautiful gradient hero section
- 📊 Skills section with animated progress bars
- 💼 Projects showcase
- 📝 Experience timeline
- 📧 Contact form
- 🚀 Smooth scrolling and animations
- 🌐 Social media links

## How to Use

### 1. Customize Your Information

Open `index.html` and update the following sections:

#### Navigation & Hero Section
- Replace "Your Name" with your actual name
- Update "Your Profession/Role" with your title
- Add your personal description

#### Social Links
Update the social media links in the hero section:
```html
<a href="YOUR_LINKEDIN_URL" target="_blank">
<a href="YOUR_GITHUB_URL" target="_blank">
<a href="YOUR_TWITTER_URL" target="_blank">
<a href="mailto:YOUR_EMAIL" target="_blank">
```

#### About Section
- Replace the placeholder text with your actual bio
- Update the statistics (Projects, Experience, Clients)

#### Skills Section
- Update skill names and percentages
- Add or remove skills as needed
- Modify skill categories if required

#### Projects Section
- Replace project names and descriptions
- Update technologies used
- Add links to live demos and GitHub repositories
- Add or remove project cards

#### Experience Section
- Update job titles, company names, and dates
- Add your responsibilities and achievements
- Add or remove timeline items

#### Contact Section
- Update email, phone, and location
- The contact form is ready to use (you'll need to add backend integration for it to actually send emails)

### 2. Add Your Photo

Replace the placeholder icon in the hero section:
- Option 1: Add an `<img>` tag with your photo
- Option 2: Use a service like [Imgur](https://imgur.com) or [Cloudinary](https://cloudinary.com) to host your image

Example:
```html
<div class="hero-image">
    <img src="path-to-your-photo.jpg" alt="Your Name" style="width: 300px; height: 300px; border-radius: 50%; object-fit: cover;">
</div>
```

### 3. Customize Colors

In `styles.css`, you can change the color scheme by modifying the CSS variables at the top:

```css
:root {
    --primary-color: #6366f1;    /* Main color */
    --secondary-color: #8b5cf6;  /* Secondary color */
    --text-color: #1f2937;       /* Text color */
    /* ... */
}
```

### 4. Deploy Your Portfolio

#### Option 1: GitHub Pages (Free)
1. Create a GitHub repository
2. Upload all files
3. Go to Settings > Pages
4. Select main branch and save
5. Your site will be live at `https://yourusername.github.io/repository-name`

#### Option 2: Netlify (Free)
1. Go to [Netlify](https://www.netlify.com)
2. Drag and drop your folder
3. Your site will be live instantly

#### Option 3: Vercel (Free)
1. Go to [Vercel](https://vercel.com)
2. Import your project
3. Deploy with one click

## File Structure

```
my-portfolio/
│
├── index.html      # Main HTML file
├── styles.css      # All styling
├── script.js       # JavaScript functionality
└── README.md       # This file
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Tips for Best Results

1. **Use High-Quality Images**: For project screenshots and your profile photo
2. **Keep It Updated**: Regularly update your projects and experience
3. **Test on Mobile**: Make sure everything looks good on phones and tablets
4. **Optimize Performance**: Compress images before uploading
5. **Add Real Projects**: Showcase your best work with live demos

## Need Help?

If you need to customize anything further or have questions, feel free to modify the code. The structure is simple and easy to understand.

## License

Feel free to use this portfolio template for your personal or commercial projects!

---

**Good luck with your portfolio! 🚀**

