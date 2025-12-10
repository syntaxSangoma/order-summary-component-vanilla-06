# Order Summary Component (Vanilla Web)

A clean, responsive Order Summary card component built using vanilla HTML and CSS. This small component demonstrates a compact purchase summary UI with a hero illustration, plan details, and primary/cancel actions.

![Order Summary Component](./images/active-states.jpg)

## Key Features & Benefits

- **Mobile-first & Responsive:** Designed for small screens first with a desktop breakpoint at `992px`.
- **Simple Markup:** Uses semantic HTML and a focused class structure (`.order-summary-card`, `.order-summary-card__bouquet`, etc.).
- **Customizable Styles:** Uses CSS custom properties in `style.css` for colors, typography, and shadows.
- **Accessible:** Keyboard-focusable controls and semantic elements for better accessibility.
- **No Dependencies:** Vanilla HTML and CSS — drop the files into any project and open `index.html`.

## Visual Overview

- Hero illustration: `./images/illustration-hero.svg`
- Active/state preview: `./images/active-states.jpg` (used above)
- Icon shown in plan: `./images/icon-music.svg`

## Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge).
- A text editor or IDE to edit `index.html` and `style.css` (e.g., VS Code).
- (Optional) A local server for consistent asset loading (e.g., `python -m http.server`).

## Installation & Setup

1. **Clone or download this repository**:

```bash
git clone https://github.com/syntaxSangoma/order-summary-component-vanilla-06.git
```

```bash
cd order-summary-component-vanilla-06
```

2. **Open the project**:

- Double-click `index.html` to open in your browser, or
- Serve the folder for consistent asset loading (recommended)

## Usage & Customization

The layout is simple — edit `index.html` and `style.css` to customize content or visuals.

- Change the hero image: replace `./images/illustration-hero.svg`.
- Update the plan name and price in the markup:
  - Plan title: `.order-summary-card__bouquet-title` (e.g., "Annual Plan")
  - Price: `.order-summary-card__bouquet-price` (e.g., "$59.99/year")
- Replace the plan icon: `./images/icon-music.svg`.
- Button text is in `index.html`: `.order-summary-card__pay-button` and `.order-summary-card__cancel-button`.

Example: to change the plan price, edit the `.order-summary-card__bouquet-price` element in `index.html`.

## Styling & Configuration Options

Most visual settings are exposed as CSS variables at the top of `style.css` under `:root`. Useful variables you can tweak:

- **Colors:** `--MAIN-BG`, `--CARD-BG`, `--TITLE-CLR`, `--DESCRIPTION-CLR`, `--PAY-BUTTON-BG`, `--CHANGE-LINK-CLR`.
- **Shadows:** `--CARD-SHADOW`, `--BUTTON-SHADOW`.
- **Typography:** `--FF` (font family), `--TITLE-MOB`, `--DESCRIPTION-MOB`, `--BUTTON-SHARED`.

To change the look globally, edit these variables or adjust the mobile/desktop font variables.

## Accessibility Notes

- Buttons and links are keyboard-focusable. You can enhance focus visibility by adding `:focus` styles in `style.css`.
- Images include `alt` attributes; decorative images use offscreen captions for screen-readers.

## Contributing

Contributions are welcome. Suggested flow:

1. Fork the repository.
2. Create a descriptive branch (e.g., `feature/dark-mode`).
3. Make small, focused commits.
4. Push to your fork and open a pull request.

## License

License not specified.

## Acknowledgments

- Google Fonts for the `Red Hat Display` font used in `style.css`.
