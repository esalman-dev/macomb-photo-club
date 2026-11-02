# Macomb Photo Club Website

A multi-page website for a fictional online photography club, hand-coded in HTML, CSS, and JavaScript as a Web Design course project at Macomb Community College.

**Live site:** https://esalman-dev.github.io/macomb-photo-club/

## Pages

| Page | What it does |
|---|---|
| `index.html` | Home page with club introduction, social share buttons, and contact link |
| `rules.html` | Contest rules, file requirements, and voting rules |
| `categories.html` | Descriptions of the three contest categories |
| `submit.html` | Photo submission form (name, email, category, description, file upload) |
| `vote.html` | Monthly finalists and a voting form |
| `gallery.html` | Gallery of past winners in a flexbox grid |
| `chat.html` | Embedded live chat room (Minnit) |

## Features

- One shared stylesheet (`picstyle.css`) for a consistent look across every page
- Header navigation that highlights the current page
- Reusable sidebar and footer navigation loaded from external JavaScript files in `js/`
- HTML forms for photo submissions and voting
- Descriptive `alt` text on every image for screen readers
- SEO meta tags (description, keywords, robots) on every page, plus a `sitemap.xml`

## Notes

The club, members, and contest entries are fictional. Images in `images/` are placeholders.

## Running it

No build step. Open `index.html` in a browser, or view the live site above.
