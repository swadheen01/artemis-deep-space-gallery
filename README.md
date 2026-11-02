# Artemis II: The Deep Space Gallery

A multi-page space flight visual journey built with standard, semantic HTML5 and modern, responsive CSS — zero JavaScript runtime dependencies, local media assets, and accessible navigational structure.

## Overview

Chronicles NASA's crewed circumlunar test flight (Artemis II) around the Moon through four interconnected modules:
* **Welcome Portal (`index.html`)**: Entry landing page introducing the lunar voyage with a floating glassmorphic hero card and glowing portal action.
* **Window Gallery (`gallery.html`)**: Curated exhibition of 14 downloadable high-resolution images across Earth, Moon, eclipse, and recovery phases styled in a responsive CSS Grid with hover zoom cards and direct download buttons.
* **Mission Trail (`mission.html`)**: Chronological flight trajectory log styled as a vertical glowing timeline, route map, modern dark-mode perspective table, and journey signals matrix.
* **Print Station (`print-request.html`)**: Interactive requisition station showcasing native HTML5 form controls, custom dark-mode styling, and client-side validation.

## Styling & Architecture (`styles.css`)

* **Design Tokens & CSS Variables**: Space palette (`#05070f`, cyan `#38bdf8`, gold `#f59e0b`), typography (`Space Grotesk`, `Outfit`).
* **Glassmorphism**: `backdrop-filter: blur(...)` across cards, navigation bar, and dialogs.
* **Layouts**: Responsive CSS Grid for gallery items, Flexbox for floating pill navbar, and CSS vertical timeline.
* **Accessibility & Semantics**: Preserves 100% of W3C standard semantic HTML5 elements (`header`, `nav`, `main`, `section`, `article`, `figure`, `figcaption`, `aside`, `footer`).

## Live Website

Once GitHub Pages is enabled:
`https://swadheen01.github.io/artemis-deep-space-gallery/`

## How to Run Locally

1. Clone or download this repository.
2. Open `index.html` in any web browser.
