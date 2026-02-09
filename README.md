# Flowers Shop

An e-commerce web application for browsing and purchasing flower arrangements online. Built with vanilla JavaScript and integrated with Contentful CMS for product management.

## Features

- **Product Catalog** - Responsive grid layout displaying flower products with images, titles, and prices
- **Shopping Cart** - Slide-out cart panel with add/remove items, quantity adjustment, and total calculation
- **Persistent Cart** - Cart state saved to localStorage so it persists across page reloads
- **CMS Integration** - Products managed through Contentful headless CMS
- **Responsive Design** - CSS Grid with auto-fit layout that adapts to all screen sizes

## Tech Stack

- HTML5, CSS3, Vanilla JavaScript (ES6+)
- [Contentful](https://www.contentful.com/) - Headless CMS for product data
- [Font Awesome](https://fontawesome.com/) - Icons
- [Google Fonts](https://fonts.google.com/) - Lato font family
- GitHub Pages with Jekyll for hosting

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/theronindev/SimSim-Flowers-Shop.git
   ```
2. Open `index.html` in your browser, or use a local development server:
   ```bash
   npx serve .
   ```

## Project Structure

```
├── index.html       # Main HTML page
├── app.js           # Application logic (cart, products, Contentful client)
├── style.css        # Stylesheet with CSS Grid and custom properties
├── products.json    # Fallback product data
├── images/          # Product images, logo, and hero background
└── _config.yml      # Jekyll configuration for GitHub Pages
```

## License

This project is open source.
