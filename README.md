# Shirley in the Kitchen

A beautiful, responsive website showcasing the culinary creations of Chef Shirley Jarrett.

## About

**Chef: Shirley Jarrett**  
**Cuisine: Italian & American Comfort Food**

This website features authentic Italian traditions and comforting American favorites, all made from scratch with love. Every recipe is crafted to bring family and friends together around the table.

## Features

- **Hero Section**: Welcoming introduction with stunning imagery
- **About Section**: Learn about Chef Shirley Jarrett and her culinary philosophy
- **Recipes Section**: Featured recipes with beautiful presentation
- **Contact Form**: Reach out to Shirley directly
- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Smooth Navigation**: Easy-to-use navigation with smooth scrolling

## File Structure

```
├── index.html          # Main HTML file
├── styles.css          # Styling and responsive design
├── script.js           # Interactive features
├── images/             # Image directory
│   ├── hero-dish.jpg
│   ├── shirley-portrait.jpg
│   ├── recipe-1.jpg
│   ├── recipe-2.jpg
│   └── recipe-3.jpg
└── README.md          # This file
```

## Getting Started

1. Clone or download this repository
2. Add your images to the `images/` folder:
   - `hero-dish.jpg` - A signature dish for the hero section
   - `shirley-portrait.jpg` - A portrait of Chef Shirley
   - `recipe-1.jpg`, `recipe-2.jpg`, `recipe-3.jpg` - Featured recipe images
3. Open `index.html` in a web browser

## Customization

### Update Content
- Edit `index.html` to change text, recipe names, and links
- Modify `styles.css` to change colors and fonts

### Colors (Can be changed in styles.css)
- Primary: #8B4513 (Saddle Brown)
- Secondary: #D2691E (Chocolate)
- Accent: #F4A460 (Sandy Brown)

### Add Recipes
Add new recipe cards by duplicating the recipe-card div in the recipes section:

```html
<div class="recipe-card">
    <img src="images/recipe-new.jpg" alt="Recipe Name">
    <h3>Recipe Name</h3>
    <p>Recipe description here.</p>
    <a href="#">View Recipe</a>
</div>
```

## Technologies Used

- HTML5
- CSS3
- JavaScript (Vanilla)
- Responsive Design

## License

This website is created for Chef Shirley Jarrett.

---

*Made with ❤️ by Shirley Jarrett*
