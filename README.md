# Bahria Town Karachi Properties

A modern Real Estate web application built with **Next.js 16.2.6**, **TypeScript**, and **Tailwind CSS**. This platform allows users to browse, buy, rent, and publish properties in Bahria Town Karachi.

---

## Features

* Property Listings
* Property Details Page
* Buy, Rent & Installment Properties
* Property Request Form
* Property Publishing Form
* Featured Properties Section
* Popular Precincts Section
* Responsive Design
* Dynamic Property Routes
* TypeScript Support
* Tailwind CSS Styling

---

## Tech Stack

* Next.js 16
* TypeScript
* Tailwind CSS
* React
* App Router

---

## Project Structure

```bash
project-root/
│
├── README.md
├── package.json
├── package-lock.json
├── next.config.ts
├── tsconfig.json
├── tailwind.config.ts
├── postcss.config.mjs
├── eslint.config.mjs
├── .gitignore
│
├── public/
│   ├── favicon.ico
│   │
│   └── images/
│       ├── logo/
│       │   └── btk.png
│       │
│       ├── properties/
│       │   ├── property-1.jpg
│       │   ├── property-2.jpg
│       │   └── property-3.jpg
│       │
│       ├── precincts/
│       │   ├── precinct-1.jpg
│       │   ├── precinct-29.jpg
│       │   └── precinct-33.jpg
│       │
│       └── banners/
│           ├── hero-banner.jpg
│           └── contact-banner.jpg
│
└── src/
    │
    ├── app/
    │   ├── layout.tsx
    │   ├── page.tsx
    │   ├── globals.css
    │   │
    │   ├── about/
    │   │   └── page.tsx
    │   │
    │   ├── blog/
    │   │   └── page.tsx
    │   │
    │   ├── contact/
    │   │   └── page.tsx
    │   │
    │   ├── rent/
    │   │   └── page.tsx
    │   │
    │   ├── sale/
    │   │   └── page.tsx
    │   │
    │   ├── installments/
    │   │   └── page.tsx
    │   │
    │   ├── guest-house/
    │   │   └── page.tsx
    │   │
    │   ├── request-property/
    │   │   └── page.tsx
    │   │
    │   ├── publish-property/
    │   │   └── page.tsx
    │   │
    │   └── property/
    │       └── [slug]/
    │           └── page.tsx
    │
    ├── components/
    │   │
    │   ├── layout/
    │   │   ├── Navbar.tsx
    │   │   ├── Footer.tsx
    │   │   └── MobileMenu.tsx
    │   │
    │   ├── property/
    │   │   ├── PropertyCard.tsx
    │   │   ├── PropertyDetail.tsx
    │   │   ├── FeaturedProperties.tsx
    │   │   ├── SimilarProperties.tsx
    │   │   └── PropertyGallery.tsx
    │   │
    │   ├── forms/
    │   │   ├── RequestPropertyForm.tsx
    │   │   └── PublishPropertyForm.tsx
    │   │
    │   ├── sections/
    │   │   ├── HeroSection.tsx
    │   │   ├── PopularPrecincts.tsx
    │   │   ├── WhyChooseUs.tsx
    │   │   ├── Testimonials.tsx
    │   │   └── CTASection.tsx
    │   │
    │   └── ui/
    │       ├── Button.tsx
    │       ├── Input.tsx
    │       ├── Select.tsx
    │       ├── Modal.tsx
    │       ├── Badge.tsx
    │       └── Loader.tsx
    │
    ├── data/
    │   ├── properties.ts
    │   ├── similar-properties.ts
    │   ├── nav-items.ts
    │   └── precincts.ts
    │
    ├── types/
    │   ├── property.ts
    │   ├── navigation.ts
    │   └── index.ts
    │
    ├── hooks/
    │   ├── useDropdown.ts
    │   ├── usePropertyFilter.ts
    │   └── useModal.ts
    │
    ├── lib/
    │   ├── utils.ts
    │   ├── helpers.ts
    │   ├── validations.ts
    │   ├── formatPrice.ts
    │   └── slugify.ts
    │
    ├── constants/
    │   ├── routes.ts
    │   ├── metadata.ts
    │   └── config.ts
    │
    └── styles/
        ├── forms.css
        ├── animations.css
        └── utilities.css
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/btk-properties.git
```

Navigate to the project folder:

```bash
cd btk-properties
```

Install dependencies:

```bash
npm install
```

Run development server:

```bash
npm run dev
```

Open:

```bash
http://localhost:3000
```

---

## Available Pages

| Page                   | Route             |
| ---------------------- | ----------------- |
| Home                   | /                 |
| About                  | /about            |
| Blog                   | /blog             |
| Contact                | /contact          |
| Rent Properties        | /rent             |
| Sale Properties        | /sale             |
| Installment Properties | /installments     |
| Guest House            | /guest-house      |
| Request Property       | /request-property |
| Publish Property       | /publish-property |
| Property Details       | /property/[slug]  |

---

## Future Improvements

* Salesforce Integration
* Property Search & Filters
* Authentication System
* Admin Dashboard
* Property Image Gallery
* WhatsApp Integration
* Property Comparison
* Favorite Properties
* Blog Management System

---

## Author

Developed using Next.js, TypeScript, and Tailwind CSS for Bahria Town Karachi Real Estate Platform.
