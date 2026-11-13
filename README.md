# Divya Mahajan: personal website

**Live site: https://divu112311.github.io**

Divya Mahajan is an AI, product and technology leader, advisor and speaker in San Francisco. She advises startups and organizations on AI-driven consumer products and digital innovation, and has more than a decade of experience in product and software engineering across retail, financial services and telecom.

## What's on the site

- **Photos** from talks and startup events, in a rotating carousel
- **About:** experience leading AI and product initiatives at Peet's Coffee, Hexaware and British Telecom
- **Talks & community:** speaker at Plug and Play and the Brazilian Chamber of Commerce, startup mentor at swissnex, AI product instructor at Product Gym, and hackathon judge
- **Projects:** Corduroy AI (built v1, 2 pilot customers), DoughJo (Bolt Hackathon) and Midnight Mile (recognized at the Google Maps Hackathon)

## Connect

- LinkedIn: https://www.linkedin.com/in/divyamahajan11
- Substack: https://divyamahajan.substack.com
- X: https://x.com/divya_mahajan11
- GitHub: https://github.com/divu112311

## How it's built

A single static page (`index.html`) with inline CSS and a little JavaScript for the photo carousel, hosted for free on GitHub Pages. There's no build step.

- `index.html`: the whole site
- `photos/`: carousel images. To change a photo, replace the file and keep the name; to add one, drop it in and add a matching `<figure class="slide">` line in `index.html`.

Every push to `main` goes live within about a minute.

To preview locally:

```bash
python -m http.server 8765
```

Then open http://localhost:8765.
