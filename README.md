# MasalaBazar

MasalaBazar is a lightweight web application for browsing and purchasing spices, masalas, and related grocery products.

The software is intended to be developed with the browser's native technologies:

- Base HTML5 for page structure and content
- Traditional CSS for layout, styling, and responsive behavior
- Vanilla JavaScript for interactions and application logic

No frontend framework or build system is required. The project should remain easy to open, understand, and run directly in a browser.

## Planned Features

- Product catalogue with images, descriptions, prices, and availability
- Product search and category filtering
- Product details view
- Shopping cart with quantity controls
- Order summary and checkout flow
- Customer login or registration, if required
- Mobile-friendly layout
- Basic form validation and user feedback

## Suggested Project Structure

```text
masalabazar/
├── index.html              # Main entry page
├── pages/                  # Additional HTML pages
├── css/
│   ├── style.css           # Main stylesheet
│   └── responsive.css      # Optional responsive rules
├── js/
│   ├── app.js              # Application startup and shared logic
│   ├── products.js         # Product data and catalogue behavior
│   └── cart.js             # Shopping cart behavior
├── images/                 # Product and interface images
└── README.md
```

The structure may be adjusted as the application grows, but HTML, CSS, and JavaScript should remain separated wherever practical.

## Running Locally

1. Download or clone this repository.
2. Open `index.html` in a modern web browser.
3. For more reliable local development, serve the folder with a simple static server and open the provided local URL.

Example using Python:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000` in a browser.

## Development Guidelines

- Use semantic HTML elements such as `header`, `nav`, `main`, `section`, and `footer`.
- Keep presentation rules in CSS rather than inline styles.
- Keep JavaScript in external files rather than inline event handlers.
- Use clear, descriptive class and variable names.
- Build reusable product cards, buttons, and form components with plain HTML/CSS.
- Validate user input and display clear error messages.
- Add useful `alt` text to product images.
- Check the interface on both desktop and mobile screen sizes.
- Avoid introducing frameworks unless the project requirements change.

## Browser Support

The application should support current versions of Chrome, Edge, Firefox, and Safari. JavaScript should use widely supported browser APIs and degrade gracefully when a feature is unavailable.

## Data and Backend

The initial version can use local JavaScript data or static JSON for products and cart demonstrations. A backend, database, authentication, payment processing, and order management can be connected later when those requirements are finalized.

## Status

This project is currently in the initial setup stage. Features, page designs, product data, and backend integration are still to be defined.

## License

No license has been selected yet.
