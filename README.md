
# QR Code Component — Frontend Mentor Challenge

> A simple card

## Project Notes

This project may appear straightforward at first glance, but it serves as a valuable exercise in reinforcing foundational principles of **usability** and **accessibility**—especially those that are easy to overlook when a component seems "too simple."

For instance, it’s tempting to focus solely on the visual card and forget structural semantics. However, even a minimal page like this **must include a proper heading hierarchy**. According to [WCAG 2.1 Success Criterion 1.3.1 (Info and Relationships)](https://www.w3.org/TR/WCAG21/#info-and-relationships), content structure must be conveyed programmatically—not just visually—so assistive technologies can interpret the page correctly.

Skipping a top-level heading (e.g., `<h1>Scan the QR code</h1>`) might seem harmless, but it degrades the experience for screen reader users and violates basic accessibility standards. This component, therefore, is not just about styling—it’s a reminder that **every UI element, no matter how small, carries semantic responsibility**.

In real-world applications, these "minor" details compound. What starts as a single QR card today could become part of a dashboard, an onboarding flow, or a payment confirmation screen tomorrow. Building it right **from the start** is how scalable, inclusive design begins.---

## Built with
- Angular (standalone components)
- SCSS
- Mobile-first responsive design

## How to run locally

To start a local development server, run:

```bash
ng serve
```

Once the server is running, open your browser and navigate to `http://localhost:4200/`. The application will automatically reload whenever you modify any of the source files.


## Building

To build the project run:

```bash
ng build
```

This will compile your project and store the build artifacts in the `dist/` directory. By default, the production build optimizes your application for performance and speed.

