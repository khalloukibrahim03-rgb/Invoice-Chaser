# Invoice Chaser

A lightweight, responsive invoice follow-up workspace that helps freelancers and small businesses track invoices, see what is overdue, and prepare polite payment reminders.

## Features

- Add and edit invoices with client details, invoice number, amount, currency, and due date.
- Track unpaid, overdue, and paid invoices.
- View summary totals for outstanding, overdue, and collected amounts.
- Search invoices by client, invoice number, or email.
- Prepare reminder messages with configurable tone, situation, offer, and language.
- Copy reminder text for manual use in email or WhatsApp.
- Record payments, including partial payments.
- Print an invoice or save it as a PDF.
- Export and restore invoice data using a text backup.
- English, French, and Arabic interface options.
- Responsive layout, dark mode support, and installable PWA assets.

## Important privacy and functionality notes

- Invoice data is stored in the browser on the device being used. It is not synchronized to a server.
- Create and keep backups before clearing browser data or moving to another device.
- Reminder messages are prepared for you to copy and send. The app does not automatically send emails or WhatsApp messages.
- This repository contains a static front-end app; it does not include a hosted backend or user accounts.

## Run locally

Because this is a static web app, you can serve the repository folder with any local static HTTP server. For example, with Python installed:

```bash
python -m http.server 8000
```

Then open [http://localhost:8000](http://localhost:8000) in your browser.

You can also deploy the static files to a static hosting provider. Keep `index.html`, `manifest.webmanifest`, `icon.svg`, and `sw.js` together at the site root.

## Project files

- `index.html` — application interface and client-side logic.
- `manifest.webmanifest` — Progressive Web App metadata.
- `icon.svg` — application icon.
- `sw.js` — service worker.

## Status

This is a portfolio/demo project. Review it and test it with sample data before relying on it for real business records.

## License

No license has been specified yet. All rights reserved by the repository owner unless a license is added.
