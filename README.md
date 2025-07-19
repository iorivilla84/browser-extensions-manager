# Extension Manager

A responsive and interactive extension manager app that allows users to toggle themes (light/dark), filter extensions by state (active/inactive/all), and remove extensions from the DOM in real time. Built using HTML5, modern CSS with nesting (Sass-like), and vanilla ES6 JavaScript. Auto-deployed via Netlify.

---

## Features

- Theme toggle with persistent state using `localStorage`
- Real-time filtering by extension status: **All**, **Active**, **Inactive**
- Remove extensions dynamically with internal state update
- State preservation across interactions
- Modern ES6 modules and clean component separation
- Auto-deploy via Netlify on push to GitHub

---

## Tech Stack

- **HTML5** – Semantic markup
- **CSS (with nesting)** – Organized styles using native nesting (CSS or Sass-like)
- **JavaScript ES6** – Modular approach using `import`/`export`
- **Netlify** – Hosting and automatic CI/CD
- **GitHub** – Source control and integration with Netlify

---

## Project Structure
<pre lang="markdown"> browser-extensions-manager/
├── index.html
├── extensions.json
├── assets/
│   ├── images
├── css/
│   └── buttons.css
│   └── grid-extensions.css
│   └── layout.css
│   └── main.css
│   └── variables.css
│   ├── fonts/
│       └── fontSite.scss
├── js/
│   ├── extension-manager.js
│   ├── main.js
│   └── helpers/
│       └── eventHandlerHelper.js
├── README.md </pre>

## Deployment
This project is deployed using Netlify. Every push to the main branch triggers an automatic deployment.

---

## Future Improvements
- Add transition animations for theme and card state changes
- Store card states (active/inactive) persistently via localStorage
- Add search functionality or tag filtering
- Add accessibility improvements and keyboard support

---

## Getting Started
### Running Locally
Since ES6 modules and fetch() are used, you must run the app from a local or remote server.
You can use Live Server (VSCode extension) or run:
`npx live-server`
Open your browser at http://127.0.0.1:5500` (or as specified by Live Server).

### Installation

```bash
git clone git@github.com:iorivilla84/browser-extensions-manager.git
cd browser-extensions-manager
