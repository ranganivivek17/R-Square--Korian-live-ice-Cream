# R Square - Korean Live Ice Cream Website

A modern, responsive website for R Square Korean Ice Cream restaurant featuring their complete menu with Korean Live Ice Cream, Pockets, and Bubble Drinks.

## 🌟 Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI/UX**: Clean, attractive design with smooth animations
- **Complete Menu**: All menu items from the original R Square menu
- **Interactive Elements**: Hover effects, smooth scrolling, and form validation
- **Contact Form**: Functional contact form with validation
- **Mobile Menu**: Hamburger menu for mobile devices
- **Smooth Animations**: Scroll-triggered animations and loading effects

## 📋 Menu Sections

### 1. Korean Live Ice Cream
- **Fruit Flavors** (₹69 each):
  - Mango, Kachi Keri, Watermelon, Guava Masala
  - Strawberry, Pineapple, Green Apple

- **Classic Flavors**:
  - Butter Scotch, Rajbhog (₹99)
  - Kesar Pista, Mava Malai, Chocolate, Rasmalai (₹120)

### 2. Pockets
- Chilli Garlic Pops (15 PC) - ₹80
- Veggie Sticks (7 PC) - ₹90
- Cheese Chilli Corn (3 PC) - ₹85
- Mexican Beans (3 PC) - ₹90

### 3. Bubble Drinks
- Heart Chocolate, Strawberry, Mango (₹120)
- Cranberry, Passion Fruit (₹130)
- Lychee (₹140)
- Pina Colada, Pineapple (₹150)
- Green Apple (₹160)
- Lemon Ice Tea, Blueberry, Mix Fruit (₹170)

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- No additional software required

### Installation
1. Download or clone the project files
2. Open `index.html` in your web browser
3. The website will load automatically

### File Structure
```
r-square-website/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and responsive design
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## 🎨 Design Features

### Color Scheme
- **Primary Orange**: #ff6b35 (R Square brand color)
- **Secondary Orange**: #f7931e
- **Text Colors**: #333 (dark), #666 (medium)
- **Background**: White and light gray (#f8f9fa)

### Typography
- **Font Family**: Poppins (Google Fonts)
- **Weights**: 300, 400, 600, 700

### Responsive Breakpoints
- **Desktop**: 1200px and above
- **Tablet**: 768px - 1199px
- **Mobile**: Below 768px

## 🔧 Customization

### Changing Colors
Edit the CSS variables in `styles.css`:
```css
:root {
    --primary-color: #ff6b35;
    --secondary-color: #f7931e;
    --text-dark: #333;
    --text-medium: #666;
}
```

### Adding Menu Items
To add new menu items, follow this structure in `index.html`:
```html
<div class="menu-item">
    <div class="item-image">
        <img src="path-to-image.jpg" alt="Item Name">
    </div>
    <div class="item-details">
        <h4>ITEM NAME</h4>
        <p class="description">Description (optional)</p>
        <p class="price">₹Price</p>
    </div>
</div>
```

### Modifying Contact Information
Update the contact details in the contact section of `index.html`:
```html
<div class="contact-item">
    <i class="fas fa-phone"></i>
    <div>
        <h4>Phone</h4>
        <p>+91 98765 43210</p>
    </div>
</div>
```

## 📱 Mobile Features

- **Hamburger Menu**: Toggle navigation on mobile devices
- **Touch-Friendly**: Large buttons and touch targets
- **Optimized Images**: Responsive images that scale properly
- **Smooth Scrolling**: Native smooth scrolling behavior

## 🌐 Browser Support

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## 📞 Contact Form

The contact form includes:
- **Validation**: Email format and required field validation
- **Success/Error Messages**: User-friendly notifications
- **Loading States**: Visual feedback during submission
- **Auto-reset**: Form clears after successful submission

## 🎯 Performance Features

- **Optimized Images**: Using Unsplash CDN for fast loading
- **Minimal JavaScript**: Efficient code with no external dependencies
- **CSS Animations**: Hardware-accelerated animations
- **Lazy Loading**: Images load as they come into view

## 🔄 Updates and Maintenance

### Adding New Sections
1. Create new section in `index.html`
2. Add corresponding styles in `styles.css`
3. Include any JavaScript functionality in `script.js`

### Updating Menu Prices
Simply edit the price values in the HTML file. The styling will automatically adjust.

### Changing Images
Replace the image URLs in the `src` attributes with your own image paths.

## 📄 License

This project is created for R Square Korean Ice Cream. Feel free to modify and use for your business.

## 🤝 Support

For any questions or support, please contact:
- Email: info@rsquare.com
- Phone: +91 98765 43210

---

**R Square Korean Ice Cream** - Experience the finest Korean Live Ice Cream & Delicious Pockets! 🍦✨
