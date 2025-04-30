# ProStore - Next.js E-commerce Platform

A modern and feature-rich e-commerce platform built with Next.js. ProStore is designed to deliver a seamless shopping experience with dynamic product displays, interactive features, and a responsive design.

<img src="./screenshot.png">

## Features

- **Product Carousel**: Showcases featured products in an interactive carousel.
- **Latest Products**: Displays the newest arrivals with a customizable limit.
- **View All Products**: Includes a button to navigate to the full product catalog.
- **Deal Countdown** : Highlights limited-time deals with a countdown timer.
- **Icon Boxes**: Displays key benefits or features (e.g., free shipping, easy returns).
- **Dynamic Data Fetching**: Uses server-side actions to fetch the latest and featured products.
- **Responsive Design**: Fully optimized for desktop, tablet, and mobile devices.

## Technologies Used

- **Next.js**: Framework for server-side rendering and static site generation.
- **React**: Component-based UI development.
- **Tailwind CSS**: For modern and responsive styling.
- **Custom API Integration**: Fetches product data dynamically.

## How to Use

- Clone the repository.
- Install dependencies using `npm install`.
- Run the development server with `npm run dev`.
- Open http://localhost:3000 in your browser to explore the platform.
- Customize components and styles to fit your e-commerce needs.

```
npx prisma studio
npx tsx ./db/seed
npx prisma migrate dev --name init
npx prisma generate
npx prisma init
npm i -D prisma @prisma/client
```

```
npx prisma generate
npx prisma migrate dev --name add-cart
```
