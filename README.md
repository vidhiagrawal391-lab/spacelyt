# Faren - Architecture & Interior Design Template

A static multi-page HTML template for architecture, interior design, and real estate websites. The project includes prebuilt pages, reusable components, animations, and a PHP contact form handler.

## Project Structure

- `index.html` - Main homepage for the template.
- `index2 .html` - Alternate homepage file (note the filename contains a space).
- `about.html`, `about-2.html` - About pages.
- `blog.html`, `blog-grid.html`, `blog-grid-sidebar.html`, `blog-details.html` - Blog pages.
- `project.html`, `project-details.html` - Project listing and detail pages.
- `service.html`, `service-details.html`, `service-details_2.html`, `service-details_3.html`, `service-details_4.html` - Service pages.
- `contact.html` - Contact page with form submission.
- `mail.php` - PHP form handler for contact submissions.
- `assets/` - Static assets folder with CSS, JavaScript, fonts, and images.

## Key Features

- Responsive layout built with Bootstrap.
- Multiple homepage variations for architecture, interior, hospitality, real estate, landscape, and industrial design.
- Rich UI interactions powered by JavaScript libraries such as Swiper, GSAP, Isotope, Magnific Popup, Nice Select, and more.
- Contact form processing via `mail.php`.
- Uses Google Fonts and FontAwesome icons.

## Local Setup

This is a static website, so no build step is required.

### Recommended: PHP built-in server

From the project root:

```powershell
cd C:\laragon\www\spacelyt
php -S localhost:8000
```

Then open:

```
http://localhost:8000
```

### Alternative: Static server

If you only need to view pages and do not require contact form submission, you can serve the site with any static server.

Examples:

- VS Code Live Server extension
- `npx serve .`
- `python -m http.server 8000` (if Python is installed)

> Note: The contact form requires `mail.php` and a PHP-enabled server. Without PHP, the form will not send email.

## Contact Form Configuration

The form posts to `mail.php` and currently sends all messages to:

- `themeholy@gmail.com`

Update the `$recipient` value in `mail.php` to use your own destination email address.

## Notes

- There is no package manager configuration (`package.json`) or build pipeline present.
- The site depends on the assets under `assets/css/` and `assets/js/`.
- Some pages are one-page and some are multipage variants.

## Open Pages

Recommended entry points:

- `index.html`
- `contact.html`
- `project.html`
- `blog-grid.html`

If you want, I can also add a simple project overview section or list the most important page routes in more detail.