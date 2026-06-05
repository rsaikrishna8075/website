# SSV Legal Website

This workspace now uses Formspree for the contact form, so no backend server is required.

## Contact form setup

The contact form posts directly to Formspree. It is now set to your live Formspree endpoint.

```html
<form id="contactForm" method="post" action="https://formspree.io/f/xykazbko" novalidate>
```

## How to use

1. Create a free Formspree form at https://formspree.io/
2. Copy your form endpoint ID
3. Replace `your-form-id` in `index.html`
4. Open `index.html` in your browser

## Notes

- The form uses client-side validation and sends the data to Formspree via JavaScript.
- No Node.js install is required for this site to work.
