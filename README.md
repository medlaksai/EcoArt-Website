# EcoArt

A modern, fast and fully accessible website for **EcoArt**, a company that promotes and sells eco-friendly handcrafted objects made from recycled materials (wood, fabric, glass, plastic).

Built by the **Nexora** team using only **HTML and native CSS** (no frameworks).

🎨 **Design:** [EcoArt on Figma](https://www.figma.com/design/tLNIp7wckVe6EDuT6GVawm/EcoArt?node-id=1-617&t=hMilM6htDew26fiZ-0)
🌐 **Live site:** _add your Vercel / GitHub Pages link here_

---

## Pages

| Page | File | Description |
|------|------|-------------|
| Home | `index.html` | Presents EcoArt, new products and company values |
| Catalogue | `produits.html` | List of recycled products by material |
| Services | `services.html` | DIY workshops and a booking form |
| Artisans | `artisans.html` | The people who make the objects |
| Impact | `impact.html` | Ecological figures (e.g. kilos of waste recycled) |
| Contact | `contact.html` | Contact form _(if your team has 6 members)_ |

---

## Tech Stack

- **HTML5**: semantic markup
- **CSS3 (native)**: CSS Grid, Flexbox, CSS variables (`:root`), media queries
- **Git & GitHub**: feature branches, Git Flow, code reviews
- **Figma**: wireframes, mockups, design system and interactive prototype
- **Deployment**: Vercel or GitHub Pages

---

## Project Structure

```
EcoArt/
├── index.html
├── produits.html
├── services.html
├── artisans.html
├── impact.html
├── contact.html
├── css/
│   ├── variables.css     # Design tokens (colors, fonts, spacing)
│   ├── style.css         # Base and component styles (mobile-first)
│   └── responsive.css    # Media queries for larger screens
├── assets/
│   ├── images/
│   └── icons/
└── README.md
```

---

## CSS Approach

### Native CSS only
All CSS is written by hand: no Tailwind, no Bootstrap.

### Design tokens
Shared design values live in `css/variables.css`:

```css
:root {
  --primary-color: /* ... */;
  --font-main: /* ... */;
  --spacing-md: /* ... */;
}
```

### Mobile-first
Base styles target phones. Larger screens are handled with `min-width` media queries:

| Device | Breakpoint |
|--------|-----------|
| Mobile | Up to 767px (base styles, no media query) |
| Tablet | `@media (min-width: 768px)` |
| Laptop | `@media (min-width: 1024px)` |
| Large screen | `@media (min-width: 1280px)` |

---

## Accessibility

- Semantic HTML (`header`, `nav`, `main`, `section`, `footer`)
- Full keyboard navigation (Tab order, visible focus states)
- Sufficient color contrast
- Labeled form fields in the booking and contact forms
- Descriptive `alt` text on images

---

## Getting Started

```bash
git clone https://github.com/your-org/ecoart.git
cd ecoart
```

No build step is needed. Open `index.html` in your browser, or use the **Live Server** extension in VS Code.

---

## Git Workflow

We use Git Flow with feature branches.

```bash
# Create your branch
git switch -c feature/your-feature-name

# Commit your work
git add .
git commit -m "Add products grid"

# Push it so teammates can see it
git push -u origin feature/your-feature-name
```

Then open a **Pull Request** and ask a teammate to review it before merging.

**Branch naming:** `feature/setup-[name]`, `feature/produits-page`, `feature/impact-cards`, etc.

---

## Validation

- HTML and CSS validated with the [W3C Validator](https://validator.w3.org/)
- Accessibility audit: keyboard test and color contrast check

---

## Bonus Features _(optional)_

- [ ] One page or component rewritten in Tailwind CSS or Bootstrap for comparison
- [ ] Dark mode using CSS variables
- [ ] CSS micro-animations

---

## Team

| Name | Role | Pages |
|------|------|-------|
| _Name_ | _e.g. Designer / Developer_ | _e.g. index.html_ |
| _Name_ | | |
| _Name_ | | |
| _Name_ | | |
| _Name_ | | |

---

## Credits

Project by **Nexora** for **EcoArt**.
