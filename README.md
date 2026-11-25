# Kinaiya

A front-end prototype of an e-commerce website for games. Built as a group project using HTML, CSS, Bootstrap 5, and JavaScript. All products, prices, and contact details are sample data, and there is no backend, login, or real payment.

## Purpose

Kinaiya is an online store where visitors can browse games by category and add them to a cart.

## Live Site and Repository

- **GitHub Pages:** <!-- TODO: https://username.github.io/repository-name/ -->
- **Repository:** <!-- TODO: https://github.com/username/repository-name -->

## Pages

| Page | File | Status |
|------|------|--------|
| Homepage | `index.html` | Done |
| Categories | `categories.html` | Done |
| Contact Us | `contact-us.html` | <!-- TODO --> |
| About | `about.html` | <!-- TODO --> |
| Cart | `cart.html` | <!-- TODO --> |
| Community | `community.html` | <!-- TODO --> |

## Features

**Homepage**
- Responsive navigation bar with a cart item count
- Hero carousel with calls to action
- Genre tiles that open the Categories page with that genre selected
- Featured games with "Add to cart" buttons
- Promotional banner
- Footer with quick links, contact details, and social links

**Categories**
- Genre filter and sorting (featured, price, title)
- Live search by game title
- Results count and an empty-state message when nothing matches
- Game cards with cover image, genre, title, description, and price
- "Add to cart" with a confirmation message

**Shared**
- Mobile, tablet, and desktop layouts using the Bootstrap grid and media queries
- Skip link, labeled form fields, and visible keyboard focus
- Cart saved in the browser's `localStorage` under the key `kinaiya-cart`, stored as a list of `{ id, name, price, qty }`

## Project Structure

```
kinaiya/
├── index.html
├── categories.html
├── contact-us.html
├── about.html
├── cart.html
├── community.html
├── css/
│   └── main-style.css
├── images/
│   ├── adventure/
│   ├── fighting/
│   ├── horror/
│   ├── simulation/
│   └── survival/
└── README.md
```

JavaScript is written inside each HTML file in a `<script>` block.

## Setup

1. Download or clone the repository.
2. Open the `kinaiya` folder in Visual Studio Code.
3. Open `index.html` in a browser (or use the Live Server extension).
4. An internet connection is needed for Bootstrap and Google Fonts, which load from CDNs.

## Publishing on GitHub Pages

1. Push all files to the repository, keeping the folder structure above.
2. In the repository, go to **Settings > Pages**.
3. Under **Build and deployment**, choose the branch (e.g., `main`) and the `/ (root)` folder, then save.
4. Wait for the site to deploy, then open the published link and check navigation, images, styles, and scripts.

## Contributors

| Name | Contribution |
|------|------------------|
| <!-- TODO: Glenn Garbo ------> | Homepage and Categories |
| <!-- TODO: Bryan Galvarole --> |  Contact Us and About   |
| <!-- TODO: Ishiq Acera ------> |          Cart           |
| <!-- TODO: Arlan Bangit -----> |       Community         |

## Credits

- [Bootstrap 5.3](https://getbootstrap.com/) for the responsive grid and components
- [Google Fonts](https://fonts.google.com/): Bricolage Grotesque and DM Sans
- <!-- TODO: add any other assets, references, or permitted AI support -->
