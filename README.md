# ☕ Desert Club: Coffee Shop Website

A multi-page website for **Desert Club**, a fictional neighborhood café whose tagline is *"Quiet Morning, Bold Coffee."* It has a homepage, separate menus for coffee, non-coffee drinks and baked goods, an About Us page, a Contact Us form, and login and sign-up pages. It is built with plain **HTML, CSS and JavaScript**, so there is no build step and no server.

Created as a group project for **Web Fundamentals** at Sunway University.

## Demo
Project Video Walkthrough (-)

## Pages

| Page | File | Description |
| --- | --- | --- |
| Home | `index.html` | Hero banner, café introduction, menu shortcuts, customer reviews and footer with contact details |
| Coffee menu | `coffeemenu.html` | Classic coffees (Americano, Latte Love, Spice me' Up!, Mocha Nior), specialty drinks (Starburst, Oceanee, Midnight Float) and fresh beans |
| Non-coffee drinks | `non-coffee menu.html` | Matcha Latte, Mixed-Berries Smoothie, Hot Chocolate and Honey Lemon |
| Food menu | `foodmenu.html` | Customer favourites, sweet treats (CinnaSwirl, Lemon Lush, Morning Melt, Strawbella) and baked delights (Dark Desire, Golden Orchard Crunch and more) |
| About Us | `about_us.html` | Introduction to the site and the team behind it |
| Contact Us | `contact us.html` | Enquiry form (name, email, message) with a confirmation message |
| Login | `Login.html` | Email and password login |
| Sign Up | `Sign_up.html` | Account creation form |
| Styles | `style2.css` | Shared stylesheet |

Prices are in Malaysian Ringgit (RM 9 to RM 18).

## Features

- Seven linked pages with shared styling.
- Slide-out navigation menu and a popup overlay, both written in vanilla JavaScript.
- Responsive layout that adapts to different screen sizes.
- Menu cards with a photo, description and price.
- Customer review section on the homepage.
- Contact form that shows a success message on submit.
- Sign up and log in demo that stores the account in the browser's `localStorage`, with validation messages.

## Tech stack

- HTML5
- CSS3
- Vanilla JavaScript

## Project structure

The HTML files expect images in an `img/` folder and the stylesheet in a `css/` folder:

```
Coffee_Shop/
├── index.html
├── coffeemenu.html
├── non-coffee menu.html
├── foodmenu.html
├── about_us.html
├── contact us.html
├── Login.html
├── Sign_up.html
├── css/
│   └── style2.css
├── img/
│   ├── logo.jpeg, backgrounds, banners ...
│   ├── drink photos  (Americano.jpg, Latte Love.jpg, matcha latte.jpg ...)
│   ├── food photos   (CinnaSwirl.jpg, Dark Desire.jpg, Strawbella.jpg ...)
│   └── review and team photos (brad.jpg, david.jpg ...)
└── README.md
```

> **Note:** in the uploaded copy of the project, all the images and `style2.css` sit in the same folder as the HTML files. Either move them into `img/` and `css/` as shown, or update the paths in the HTML and CSS. Otherwise the pages will show without images or styling.

## How login works

This is a front-end demo only. **Sign Up** saves the email and password to the browser's `localStorage`. **Login** compares what you type against that saved entry. There is no backend, so:

- accounts exist only in the browser where they were created;
- passwords are stored as plain text, so don't use a real password;
- the login success redirect is not wired to a page yet.

## Known issues

- The "Reset it here" link on the login page points to `pw_reset.html`, which is not in the project.
- The "Login" link in the homepage's top bar points to `aboutus.html` instead of `Login.html`.
- `about_us.html` references team photos (`wanyin.jpeg`, `sean.jpeg`) that are not included.
- Login success does not redirect anywhere yet.
- The contact form shows a confirmation but does not send the message anywhere.

## Team

Sunway University, Bachelor of Information Technology students:

| Name | Contribution |
| --- | --- |
| Gloria Lim Su Jane | Non-Coffee menu layout, structure of the other menu pages, logo design |
| Beh Jo Ee | Homepage, integration of all pages, CSS consistency |
| Teo Wan Yin | Menu section design, About Us page, Contact Us page, viewport and responsive fixes |
| Loy Zhou Swyen | Login page, Sign Up page, password reset page |

## License

Developed as an academic project. Add a license here if you plan to open-source it.
