# NextCart

A decoupled e-commerce starter kit using Drupal Commerce API and Next.js.

## Overview

NextCart is a modern, headless e-commerce solution that combines the power of Drupal Commerce on the backend with a fast, responsive Next.js frontend. This starter kit provides a foundation for building scalable, customizable e-commerce experiences.

### Tech Stack

**Backend:**
- Drupal 10
- Drupal Commerce
- Commerce API (RESTful endpoints)
- GraphQL
- JWT Authentication
- Stripe Payment Integration

**Frontend:**
- Next.js
- TypeScript
- Tailwind CSS
- Apollo Client for GraphQL
- GraphQL Codegen

## Features

- Modular and reusable architecture
- Product catalog with filtering and sorting
- Cart management (add, update, remove items)
- Checkout process with Stripe payment integration
- User authentication (JWT-based)
- SEO-friendly and performant design
- Extensible for wishlists, donation campaigns, or forums

## Project Structure

```
nextcart/
├── backend/               # Drupal Commerce backend
│   ├── web/              # Drupal core files
│   ├── composer.json     # PHP dependencies
│   └── config/           # Drupal configuration
├── frontend/             # Next.js frontend (coming soon)
│   ├── components/       # React components
│   ├── pages/            # Next.js pages
│   ├── graphql/          # GraphQL queries and schema
│   └── styles/           # CSS and Tailwind styles
└── README.md             # This file
```

## Getting Started

### Backend Setup

1. Install Drupal dependencies:
```bash
cd backend
composer install
```

2. Install Drupal via web interface or using Drush:
```bash
vendor/bin/drush site:install
vendor/bin/drush en commerce commerce_product commerce_cart commerce_checkout commerce_payment commerce_api graphql jwt
```

3. Configure Drupal Commerce, set up products, and adjust payment settings.

### Frontend Setup (Coming Soon)

The Next.js frontend will be added in upcoming commits.

## Development Roadmap

- [x] Set up Drupal 10 backend with Commerce modules
- [x] Install and configure Commerce API
- [x] Add GraphQL support
- [x] Set up Stripe payments integration
- [x] Configure JWT authentication
- [ ] Create demo content (products, variations)
- [ ] Set up Next.js frontend
- [ ] Build product listing and cart components
- [ ] Implement checkout with Stripe
- [ ] Add extensibility features
- [ ] Optimize for performance and SEO
- [ ] Create comprehensive documentation

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
