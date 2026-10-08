# Soweto Fresh Bakery Website — Part 2

This version continues the earlier Soweto Fresh Bakery website and is built to address the Part 2 brief: external CSS, CSS reset/base styling, typography, Flexbox/Grid layouts, visual styling, pseudo-classes, and responsive breakpoints.

## Pages
- `index.html` — Home
- `about.html` — About Us
- `products.html` — Products with category filters
- `gallery.html` — Real food-photo gallery
- `services.html` — Services
- `contact.html` — Contact/enquiry form
- `style.css` — External stylesheet used by every page
- `script.js` — Mobile menu, product filtering, form interaction

## Responsive design
- Desktop layout: 3-column product/content grids.
- Tablet breakpoint: 900px.
- Mobile breakpoint: 620px.
- Relative sizing uses `clamp()`, `%`, `min()`, grid and flexible containers.
- Includes keyboard focus styles and reduced-motion support.

## Real image sources
The website uses free-to-use Unsplash photographs. The images are loaded from Unsplash URLs so the site can use real photography rather than placeholders.

Sources:
1. Bread: https://unsplash.com/photos/close-up-photography-of-baked-breads-TXByQcOMPlE
2. Bakery bread display: https://unsplash.com/photos/freshly-baked-bread-displayed-in-a-bakery-Wl0cGdbfRf4
3. Muffins: https://unsplash.com/photos/a-bunch-of-muffins-sitting-on-top-of-a-table-eKTL0qUbyPA
4. White sprinkle cupcake: https://unsplash.com/photos/a-cupcake-with-white-frosting-and-sprinkles-YiUE_7o3agw
5. Chocolate cupcake: https://unsplash.com/photos/a-chocolate-cupcake-with-chocolate-frosting-on-a-black-background-zB7r9P22rJw
6. Chocolate/white cake: https://unsplash.com/photos/brown-and-white-cake-on-yellow-plate-zc-9KfWkJvw
7. Strawberry cake: https://unsplash.com/photos/a-cake-with-white-frosting-and-strawberries-on-top-y6BYMYP3vD4

## Note for submission
The image files are loaded from the internet, so the photographs will appear when the site is opened while connected to the internet. If your lecturer requires the website to work completely offline, download the referenced Unsplash images into an `images` folder and replace the image URLs in the HTML with local paths such as `images/cake.jpg`.
