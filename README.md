# Brew Haven Coffee Shop ☕

A multi-page static website for a fictional coffee shop, built collaboratively as a Git Flow practice project.

## Team Members

| Name | Branch | Responsibility |
|---|---|---|
| Vijay | `feature/home-page` | Home page (`index.html`), PR review/merge, deployment |
| Arthi | `feature/about-page` | About page (`about.html`) |
| Arivisam | `feature/contact-page` | Contact page (`contact.html`) |
| Mohammed | `feature/css-readme` | Styling (`styles.css`), documentation (`README.md`) |

## Git Flow Workflow

This project follows a simplified Git Flow branching model:

- **`main`** — production-ready code, deployed to GitHub Pages.
- **`develop`** — integration branch where all feature branches are merged before release.
- **`feature/*`** — individual work branches created off `develop`, one per page/task.

**Working process:**
1. Clone the repository.
2. Checkout `develop` and pull the latest changes.
3. Create a feature branch off `develop`: `git checkout -b feature/your-feature`.
4. Commit and push work to your feature branch.
5. Open a Pull Request into `develop` (not `main`).
6. After review and merge, `develop` is periodically merged into `main` for deployment.

## Website Pages

- **Home (`index.html`)** — Navigation bar, hero banner, featured coffee section, footer.
- **About (`about.html`)** — Our Story, Our Mission, Why Choose Us, Opening Hours.
- **Contact (`contact.html`)** — Contact form, address, phone, email, map placeholder, business hours.
- **Shared (`styles.css`)** — Consistent coffee-inspired theme (brown / cream / dark gray), responsive navigation, and reusable styles for buttons, forms, cards, and tables across all pages.

## How to Run the Project

No build tools or dependencies required — this is a static HTML/CSS site.

1. Clone the repository:
```bash
   git clone <repository-url>
   cd brew-haven-coffee-shop
```
2. Open `index.html` directly in your browser, **or** serve it locally:
```bash
   python -m http.server 8000
```
   then visit `http://localhost:8000`.

## Deployment

The site is deployed via **GitHub Pages** from the `main` branch. Live link: _add once deployed by Vijay_.