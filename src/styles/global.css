/* =========================================================
  LIKE A GHOST THEME - Dark and Light modes with glow effects
  Refactor: adds RGB vars for bulletproof rgba() usage
  ========================================================= */

/* Avoid color pop on first paint */

:root{
  --bg:#0b0b0c;
  --fg:#f5f6f8;
  --muted:#9aa0a6;
  --card:#141416;
  --accent:#c9f31d;
  --mono: ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, "Liberation Mono", "JetBrains Mono", monospace;
  --sans: Inter, system-ui, -apple-system, Segoe UI, Roboto, Noto Sans, Ubuntu, Cantarell, "Helvetica Neue", Arial, "Noto Color Emoji", "Apple Color Emoji", "Segoe UI Emoji", sans-serif;
}
*{box-sizing:border-box}
html,body{height:100%}
body{
  margin:0;
  background:var(--bg);
  color:var(--fg);
  font-family:var(--sans);
  line-height:1.55;
}
.wrap{display:grid;min-height:100%;place-items:center;padding:4rem 1.5rem}
main{max-width:900px;width:100%}
h1{font-size:clamp(2.2rem,4vw,3rem);letter-spacing:.5px;margin:.25rem 0 1rem}
.sub{color:var(--muted);margin-top:-.5rem}
.grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(200px,1fr));gap:1rem;margin:2rem 0}
.card{
  display:flex;align-items:center;justify-content:center;
  border-radius:1rem;padding:1.25rem 1rem;background:var(--card);
  text-decoration:none;color:var(--fg);border:1px solid #1f1f22;
  transition:transform .12s ease, border-color .12s ease;
}
.card:hover{transform:translateY(-2px);border-color:var(--accent)}
footer{opacity:.8;margin-top:2rem;font-family:var(--mono);font-size:.9rem}
a{color:var(--fg)}

html.theme-ready * {
    transition: background-color 200ms ease, color 200ms ease, text-shadow 200ms ease;
}

.theme-toggle {
    position: fixed;
    inset: 16px 16px auto auto;
    /* top-right */
    padding: 10px 12px;
    font-size: 18px;
    line-height: 1;
    border-radius: 999px;
    border: 1px solid var(--border-color);
    background: var(--code-bg);
    color: var(--text-color);
    cursor: pointer;
    box-shadow: 0 2px 12px rgba(var(--text-rgb), 0.08);
}

.theme-toggle:hover {
    filter: brightness(1.05);
}

.theme-toggle:active {
    transform: translateY(1px);
}

/* ---------------------------
   DARK MODE - Ghostly white on black
   --------------------------- */
.dark-mode {
    /* Colors */
    --bg-color: #000;
    --text-color: #f5f6f8;
    --text-rgb: 245, 246, 248;
    /* <- NEW */
    --link-color: #e6e7ea;

    --code-bg: #0c0c0c;
    --code-text: #f2f2f2;

    --border-rgb: 255, 255, 255;
    /* <- NEW */
    --border-color: rgba(var(--border-rgb), 0.08);
}

/* ---------------------------
   LIGHT MODE - Black on white
   --------------------------- */
.light-mode {
    /* Colors */
    --bg-color: #fefefe;
    --text-color: #0a0a0a;
    --text-rgb: 10, 10, 10;
    /* <- NEW */
    --link-color: #222;

    --code-bg: #f3f3f3;
    --code-text: #111;

    --border-rgb: 0, 0, 0;
    /* <- NEW */
    --border-color: rgba(var(--border-rgb), 0.08);
}

/* ---------------------------
   BASE STYLES
   --------------------------- */
body {
    background: var(--bg-color);
    color: var(--text-color);
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
    line-height: 1.6;
    margin: 0;
    padding: 20px;
}

/* Text with glow effect */
p,
li,
span {
    text-shadow:
        0 0 0.6px currentColor,
        0 0 6px rgba(var(--text-rgb), 0.12);
}

/* Headings with stronger glow */
h1,
h2,
h3,
h4,
h5,
h6 {
    text-shadow:
        0 0 0.8px currentColor,
        0 0 8px rgba(var(--text-rgb), 0.16);
    margin-top: 1.5em;
    margin-bottom: 0.5em;
}

/* Links */
a {
    color: var(--link-color);
    text-decoration: underline;
    text-underline-offset: 2px;
}

/* Code blocks */
pre,
code {
    background: var(--code-bg);
    color: var(--code-text);
    padding: 2px 6px;
    border-radius: 8px;
    font-family: "Courier New", monospace;
    text-shadow: none;
}

pre {
    padding: 16px;
    overflow-x: auto;
}

/* Tables */
table {
    border-collapse: collapse;
    width: 100%;
    margin: 1em 0;
}

th,
td {
    border: 1px solid var(--border-color);
    padding: 8px 12px;
    text-align: left;
}

th {
    font-weight: bold;
}

/* Container for content */
.container {
    max-width: 900px;
    margin: 0 auto;
}

/* Dark mode specific glow tweaks */
.dark-mode p,
.dark-mode li,
.dark-mode span {
    text-shadow:
        0 0 0.6px rgba(var(--text-rgb), 0.45),
        0 0 6px rgba(var(--text-rgb), 0.12);
}

.dark-mode h1,
.dark-mode h2,
.dark-mode h3,
.dark-mode h4,
.dark-mode h5,
.dark-mode h6 {
    text-shadow:
        0 0 0.8px rgba(var(--text-rgb), 0.55),
        0 0 8px rgba(var(--text-rgb), 0.16);
}

/* Light mode specific glow tweaks */
.light-mode p,
.light-mode li,
.light-mode span {
    text-shadow:
        0 0 0.6px rgba(var(--text-rgb), 0.45),
        0 0 6px rgba(var(--text-rgb), 0.12);
}

.light-mode h1,
.light-mode h2,
.light-mode h3,
.light-mode h4,
.light-mode h5,
.light-mode h6 {
    text-shadow:
        0 0 0.8px rgba(var(--text-rgb), 0.55),
        0 0 8px rgba(var(--text-rgb), 0.16);
}

/* Additional styles for website functionality */
.nav-menu {
    display: flex;
    gap: 2rem;
    margin: 2rem 0;
    padding: 1rem 0;
    border-bottom: 1px solid var(--border-color);
}

.nav-menu a {
    text-decoration: none;
    padding: 0.5rem 1rem;
    border-radius: 4px;
    transition: background-color 200ms ease;
}

.nav-menu a:hover {
    background: var(--code-bg);
}

.blog-post {
    margin: 2rem 0;
    padding: 1.5rem;
    border: 1px solid var(--border-color);
    border-radius: 8px;
}

.blog-meta {
    font-size: 0.9em;
    opacity: 0.7;
    margin-bottom: 1rem;
}

.discography-item {
    display: flex;
    gap: 1.5rem;
    margin: 2rem 0;
    padding: 1.5rem;
    border: 1px solid var(--border-color);
    border-radius: 8px;
}

.album-artwork {
    width: 150px;
    height: 150px;
    object-fit: cover;
    border-radius: 4px;
}

.album-info {
    flex: 1;
}

.track-list {
    margin-top: 1rem;
}

.track-item {
    display: flex;
    justify-content: space-between;
    padding: 0.5rem 0;
    border-bottom: 1px solid var(--border-color);
}

.form-group {
    margin: 1rem 0;
}

.form-group label {
    display: block;
    margin-bottom: 0.5rem;
    font-weight: bold;
}

.form-group input,
.form-group select,
.form-group textarea {
    width: 100%;
    padding: 0.75rem;
    border: 1px solid var(--border-color);
    border-radius: 4px;
    background: var(--code-bg);
    color: var(--text-color);
    font-family: inherit;
}

.form-group input:focus,
.form-group select:focus,
.form-group textarea:focus {
    outline: none;
    border-color: var(--link-color);
    box-shadow: 0 0 0 2px rgba(var(--text-rgb), 0.1);
}

.btn {
    padding: 0.75rem 1.5rem;
    border: 1px solid var(--border-color);
    border-radius: 4px;
    background: var(--code-bg);
    color: var(--text-color);
    cursor: pointer;
    text-decoration: none;
    display: inline-block;
    transition: all 200ms ease;
}

.btn:hover {
    filter: brightness(1.1);
    transform: translateY(-1px);
}

.btn-primary {
    background: var(--link-color);
    color: var(--bg-color);
    border-color: var(--link-color);
}

.gallery {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
    gap: 1rem;
    margin: 1rem 0;
}

.gallery img {
    width: 100%;
    height: 150px;
    object-fit: cover;
    border-radius: 4px;
    cursor: pointer;
    transition: transform 200ms ease;
}

.gallery img:hover {
    transform: scale(1.05);
}

.modal {
    display: none;
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: rgba(0, 0, 0, 0.8);
    z-index: 1000;
}

.modal.active {
    display: flex;
    align-items: center;
    justify-content: center;
}

.modal img {
    max-width: 90%;
    max-height: 90%;
    object-fit: contain;
}

.streaming-links {
    display: flex;
    flex-wrap: wrap;
    gap: 1rem;
    margin: 1rem 0;
}

.streaming-links a {
    padding: 0.5rem 1rem;
    background: var(--code-bg);
    border: 1px solid var(--border-color);
    border-radius: 4px;
    text-decoration: none;
    font-size: 0.9em;
}

.admin-panel {
    background: var(--code-bg);
    border: 1px solid var(--border-color);
    border-radius: 8px;
    padding: 2rem;
    margin: 2rem 0;
}

.admin-section {
    margin: 2rem 0;
    padding: 1.5rem;
    border: 1px solid var(--border-color);
    border-radius: 4px;
}

.visibility-badge {
    display: inline-block;
    padding: 0.25rem 0.5rem;
    border-radius: 4px;
    font-size: 0.8em;
    font-weight: bold;
}

.visibility-public {
    background: #22c55e;
    color: white;
}

.visibility-vip {
    background: #f59e0b;
    color: white;
}

.visibility-admin {
    background: #ef4444;
    color: white;
}