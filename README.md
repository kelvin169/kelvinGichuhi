# Kelvin Mwaniki — Portfolio Website

> Personal portfolio and engineering blog for a Firmware & Industrial Automation Engineer based in Nairobi, Kenya.

**Live site:** [kelvinmwaniki.github.io](https://kelvinGichuhi.github.io)

---

## About

This is the source code for my personal portfolio website. It serves as a central hub for:

- My professional background and technical skill set.
- Blog posts documenting real firmware and automation projects
- Links to my open-source work on GitHub

Built as a single, dependency-free HTML file — no frameworks, no build step.

---

## Features

- **About Me** — Bio, skills, and tech stack across Firmware, Industrial Automation, and tooling
- **Blog** — Engineering write-ups covering embedded systems, PLC programming, Modbus, CAN Bus, and more
- **GitHub integration** — Every blog post links back to the relevant repository
- **Responsive design** — Works cleanly on mobile, tablet, and desktop
- **Zero dependencies** — Pure HTML, CSS, and vanilla JS; loads instantly

---

## Tech Stack

| Layer | Technology |
|---|---|
| Markup | HTML5 |
| Styling | CSS3 (custom properties, grid, flexbox) |
| Fonts | Google Fonts — DM Serif Display, DM Sans, DM Mono |
| Hosting | GitHub Pages |

---

## Project Structure

```
/
└── index.html       # Entire site — single file
└── README.md        # You are here
```

---

## Running Locally

No build tools needed. Just clone and open:

```bash
git clone https://github.com/kelvinmwaniki/kelvinmwaniki.github.io.git
cd kelvinmwaniki.github.io
open index.html
```

Or serve it with Python for a local dev server:

```bash
python3 -m http.server 8000
# Visit http://localhost:8000
```

---

## Deploying to GitHub Pages

1. Create a repository named `kelvinmwaniki.github.io`
2. Push `index.html` and `README.md` to the `main` branch
3. Go to **Settings → Pages → Source → Deploy from branch → main**
4. Your site will be live at `https://kelvinmwaniki.github.io` within a few minutes

---

## Adding a Blog Post

Each blog post is a card in the `#blog` section of `index.html`. To add a new post, copy this block and update the fields:

```html
<a href="LINK_TO_POST_OR_REPO" class="blog-card">
  <span class="blog-badge">CATEGORY</span>
  <div class="blog-title">Your Post Title Here</div>
  <div class="blog-excerpt">
    A short description of what the post covers.
  </div>
  <div class="blog-meta">
    <span>📅 Month Year</span>
    <span>⏱ X min read</span>
  </div>
</a>
```

**Suggested categories:** `Firmware` · `Embedded` · `PLC` · `Automation` · `RTOS` · `Protocols`

---

## Blog Topics Covered

- Real-Time Motor Control with STM32 and FreeRTOS
- Modbus RTU from Scratch over RS-485
- Ladder Logic vs Structured Text (IEC 61131-3)
- CAN Bus on ESP32 with the TWAI peripheral
- *(More coming — follow along!)*

---

## Contact

- **Email:** kelvinmwaniki8@gmail.com
- **GitHub:** [@kelvinmwaniki](https://github.com/kelvin169)
- **LinkedIn:** [linkedin.com/in/kelvinmwaniki](https://linkedin.com/in/kelvinmwaniki)

---

## License

This portfolio's **design and code** are open for reference and inspiration. Feel free to fork and adapt for your own use. Blog content and written articles are © Kelvin Mwaniki — please don't republish without permission.

---

*Built and maintained by Kelvin Mwaniki · Nairobi, Kenya 🇰🇪*
