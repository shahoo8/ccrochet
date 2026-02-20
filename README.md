# 🧶 Cozy Crochet Website

A fully functional, animated, and responsive crochet business website with a cute, modern design.

## ✨ Features

- **Animated Home Page** with floating elements and smooth transitions
- **Automatic Product Slider** that stops when clicked
- **Responsive Design** works on all devices
- **Order Page** redirects to Instagram DMs
- **Contact Page** with Instagram, TikTok, email, and phone
- **Designs Gallery** with product listings and prices
- **Mobile-Friendly Navigation** with hamburger menu

## 📁 Files Included

- `index.html` - Home page with hero section and product slider
- `designs.html` - Product gallery with prices
- `order.html` - Order page with Instagram redirect
- `contact.html` - Contact information and social links
- `styles.css` - All styling and animations
- `script.js` - Interactive functionality

## 🎨 How to Customize

### 1. Add Your Product Photos

Replace the placeholder divs in the slider with actual images:

**In index.html**, find the slider section and replace:
```html
<div class="slide-placeholder">
    <i class="fas fa-image"></i>
    <p>Upload your product photo</p>
</div>
```

With:
```html
<img src="images/product1.jpg" alt="Product Name" style="width: 100%; height: 100%; object-fit: cover;">
```

### 2. Update Social Media Links

**In order.html** (line 54):
```html
<a href="https://www.instagram.com/YOUR_USERNAME/" target="_blank" class="instagram-btn">
```

**In contact.html**:
- Line 54: Instagram link
- Line 64: TikTok link
- Line 74: Email address
- Line 84: Phone number

**In script.js** (line 138):
```javascript
const instagramURL = 'https://www.instagram.com/direct/YOUR_USERNAME/';
```

### 3. Update Product Information

**In index.html** - Edit slider products (lines 48-67):
```html
<div class="slide active" data-name="Your Product Name" data-price="$XX">
```

**In designs.html** - Edit product cards:
- Product names (h3 tags)
- Descriptions (p tags with class "design-description")
- Prices (p tags with class "design-price")

### 4. Change Colors

**In styles.css** (lines 9-14), modify the color variables:
```css
:root {
    --primary: #ff6b9d;        /* Main pink color */
    --secondary: #c44569;      /* Darker pink */
    --accent: #ffa07a;         /* Coral accent */
    --light: #fff5f7;          /* Light background */
    --dark: #2d3436;           /* Text color */
}
```

### 5. Update Business Name

Replace "Cozy Crochet" throughout all HTML files with your business name.

## 🚀 How to Use

1. **Open the website**: Double-click `index.html` to open in your browser
2. **Upload photos**: Create an `images` folder and add your product photos
3. **Customize content**: Edit the HTML files with your information
4. **Test on mobile**: Use browser dev tools to test responsive design

## 📱 Responsive Breakpoints

- Desktop: 1200px and above
- Tablet: 768px - 1199px
- Mobile: Below 768px

## 🎯 Slider Features

- **Auto-slides** every 3 seconds
- **Click on slide** to stop auto-sliding
- **Manual controls** with prev/next buttons
- **Product info** updates automatically

## 💡 Tips

- Use high-quality product photos (recommended: 800x800px)
- Keep product names short and catchy
- Update contact information before going live
- Test all links before publishing
- Consider adding more products to the designs page

## 🌐 Publishing Your Website

### Option 1: GitHub Pages (Free)
1. Create a GitHub account
2. Create a new repository
3. Upload all files
4. Enable GitHub Pages in settings

### Option 2: Netlify (Free)
1. Create a Netlify account
2. Drag and drop your folder
3. Get instant live URL

### Option 3: Custom Domain
1. Purchase a domain (e.g., GoDaddy, Namecheap)
2. Use hosting service (e.g., Bluehost, HostGator)
3. Upload files via FTP

## 📞 Support

For questions or customization help, refer to the code comments in each file.

---

Made with 💕 for your crochet business!
"# crochet" 
"# ccrochet" 
