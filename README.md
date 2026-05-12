# PersonalPage

This repository hosts **Gabriel F. Ushijima’s** personal website and an interactive **Touring Polygons Problem (TPP)** visualizer. Everything is static front-end code you can open locally or deploy as static files.

## Personal site (`index.html`)

The main page is a single-page portfolio built with **HTML**, **Tailwind CSS** (CDN), and custom CSS variables. It includes:

- **About**, **research**, **projects**, and **contact** sections
- Light/dark **theme toggle**
- Typography via **DM Sans** and **JetBrains Mono**

Content highlights research at IME-USP (including the Touring Polygons Problem), teaching assistant work, and selected projects—with images and links where relevant.

## TPP Visualizer (`Visualizer/`)

The **`Visualizer`** folder is a self-contained web app titled **TPP Visualizer**. It lets you draw a sequence of polygons on a canvas and explore shortest visiting paths for the Touring Polygons Problem—aligned with the research described on the main site.

Implementation notes:

- **`Visualizer/index.html`** is the entry point; scripts live under **`Visualizer/js/`** (canvas logic, TPP helpers, drawing storage, settings, etc.).
- Uses **Tailwind** (CDN), **polygon-clipping** for geometric operations, and browser APIs for persisting drawings (local library, save/rename/duplicate flows).

From the personal page, the **Touring Polygons — Interactive Visualizer** project links to `Visualizer/index.html` as the demo.

## Running locally

Serve the repo root with any static file server (so module paths resolve correctly), or open `index.html` / `Visualizer/index.html` directly in the browser depending on your setup.
