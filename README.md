# Aroma E-commerce

## Project Overview
A modern and responsive e-commerce template built with **HTML**, **CSS**, and **Bootstrap 5**.  
Designed to showcase products with a clean UI and smooth navigation — perfect for portfolios or small demo stores.

### Live Demo
[Aroma E-commerce](https://mohammed-alqerem.github.io/Aroma-E-commerce/)

---

## Features
- Fully responsive layout (Bootstrap grid)
- Product listing cards with images and prices
- Hero banner / product slider
- Product detail modal or page
- Contact and subscription form (frontend only)
- Mobile-friendly navigation and footer

### UI/UX Enhancements
- Modern CSS custom properties for consistent theming
- Smooth entrance animations on page load
- Enhanced product cards with hover effects (scale, shadow lift)
- Improved navbar with scroll effects and smooth transitions
- Form focus states with visual feedback
- Footer link hover animations
- Mobile-responsive breakpoints
- Intersection Observer for scroll-triggered animations

---

## Tech Stack
- **HTML5**
- **CSS3** (with CSS Variables)
- **Bootstrap 5**
- **Vanilla JavaScript** (for scroll effects and animations)

---

## Installation & Usage
1. **Clone the repository**
   ```bash
   git clone https://github.com/mohammed-alqerem/Aroma-Ecommerce.git
   ```
2. **Open the project**
   ```bash
   cd Aroma-Ecommerce
   ```
3. **Open `index.html` in your browser**

---

## Project Structure
```
Aroma-E-commerce/
├── index.html
├── *.html (other pages)
├── assets/
│   ├── images/
│   └── src/
│       ├── css/
│       │   ├── main.css
│       │   ├── home.css
│       │   ├── media.css
│       │   └── shop/
│       └── js/
│           └── main.js
```

---

## Customization

### Color Palette
The project uses CSS custom properties in `main.css`. Modify the `--primary`, `--secondary`, and other color variables to change the theme:

```css
:root {
    --primary: #3749e8;
    --secondary: #002347;
    --accent: #c5322d;
}
```

### Animations
Animations are defined in `main.css` and include:
- `fadeInUp` - Fade in and slide up
- `fadeIn` - Simple fade in
- `slideInLeft` / `slideInRight` - Slide animations
- `scaleIn` - Scale in effect

---

## Browser Support
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

---

## License
This project is for educational and portfolio purposes.

---

## Credits
Made with Bootstrap 5 and Font Awesome
