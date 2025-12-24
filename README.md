# Spanish & Portuguese Butchery - Website

A professional, modern website design for Spanish & Portuguese Butchery in Sydney, NSW.

## Features

### 🎨 Design Elements
- **Modern, Clean Layout**: Professional design with a classic red and gold color scheme reflecting Spanish/Portuguese heritage
- **Responsive Design**: Fully responsive layout that works on all devices (desktop, tablet, mobile)
- **Smooth Animations**: Subtle animations and transitions for better user experience
- **Professional Typography**: Using Lora serif font for headings and Poppins for body text

### 📄 Sections

1. **Navigation Bar** - Sticky navigation with smooth scrolling
2. **Hero Section** - Eye-catching banner with call-to-action button
3. **About Us** - Company information and values
4. **Products/Specialties** - Grid showcase of services and products
5. **Contact Section** - Contact information and inquiry form
6. **Footer** - Copyright and social media links

## Color Scheme

- **Primary Red**: #8B0000 (Deep red, traditional color)
- **Secondary Gold**: #FFD700 (Accent and highlights)
- **Accent Red**: #C41E3A (Complementary red)
- **Dark Background**: #1a1a1a (Text and backgrounds)
- **Light Background**: #f5f5f5 (Content areas)

## Getting Started

### Files Included
- `index.html` - Main website structure
- `styles.css` - Complete styling and responsive design
- `script.js` - Interactive features and animations

### How to Use
1. Open `index.html` in a web browser
2. All styling is contained in `styles.css`
3. Interactive features are handled by `script.js`

### Customization Tips

#### Update Business Information
In `index.html`, modify:
- Phone number (line 124)
- Email address (line 127)
- Business hours (line 130-133)
- Location details (line 120-121)

#### Modify Contact Form
Edit the form action or add backend integration for email handling.

#### Add Images
Replace `.placeholder-image` divs with actual images:
```html
<img src="your-image.jpg" alt="Description" class="about-image">
```

#### Change Color Scheme
Update CSS variables in `styles.css` `:root` selector:
```css
:root {
    --primary-color: #your-color;
    --secondary-color: #your-color;
    /* ... */
}
```

## Responsive Breakpoints

- **Desktop**: Full layout
- **Tablet (768px and below)**: Adjusted grid layout, smaller fonts
- **Mobile (480px and below)**: Single column layout, optimized for touch

## Features Implemented

✅ Sticky Navigation Menu  
✅ Smooth Page Scrolling  
✅ Responsive Grid Layouts  
✅ Form Validation Ready  
✅ Intersection Observer for Animations  
✅ Mobile-Friendly Design  
✅ SEO-Friendly Structure  
✅ Parallax Effects  
✅ Hover Animations  
✅ Social Media Integration  

## Browser Support

- Chrome/Edge (Latest)
- Firefox (Latest)
- Safari (Latest)
- Mobile browsers

## Next Steps

1. **Add Real Images**: Replace placeholder images with actual shop photos
2. **Set Up Email**: Configure form submission to receive inquiries
3. **Add Products Database**: Create a product listing/catalog page
4. **Integrate Social Media**: Add Instagram, Facebook feeds
5. **Add Reviews Section**: Customer testimonials
6. **Implement Online Ordering**: E-commerce functionality (optional)
7. **Add Blog/News**: Latest offers and butchery tips
8. **SEO Optimization**: Meta tags, structured data, sitemap

## Contact Integration

To make the contact form functional, you can:
- Use Formspree (free service)
- Use Netlify Forms (if hosting there)
- Set up backend API endpoint
- Use email service like SendGrid

Example with Formspree:
```html
<form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
```

---

**Design Created**: December 24, 2025  
**For**: Spanish & Portuguese Butchery, Sydney NSW
