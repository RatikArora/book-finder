# 📚 Book Finder (Zero‑install build)

This is a minimal, deploy-ready build of Book Finder for Alex using the Open Library Search API. It runs entirely in the browser via React from a CDN—no Node.js or build step required.

**GitHub Repository:** https://github.com/RatikArora/book-finder

## How to run locally

- Open `cdn-dist/index.html` in your browser.

## Live deploy

**Live application:** https://69010bee80cec90d9ba1b532--comforting-bunny-ea232f.netlify.app/

Deploy the `cdn-dist/` folder to any static host (Netlify, Vercel, GitHub Pages). On Netlify, you can use Netlify Drop and drag the `cdn-dist` folder.

## Features

- Search by title and optionally author
- Filters: subject, language, year range
- Sorting: relevance, year ascending/descending
- Pagination using Open Library's paging
- Details modal with description and subjects
- Responsive, mobile-first UI

## Notes

- API: Open Library Search API
  - Example: https://openlibrary.org/search.json?title=harry%20potter
- Covers: https://covers.openlibrary.org/b/id/{cover_i}-M.jpg

## Working with AI (Level 1)

**ChatGPT conversation link:** https://chatgpt.com/share/69010c40-8fa4-8004-b918-56fc47d0e395

This project was built with the assistance of AI, demonstrating iterative problem-solving, API integration, and zero-install deployment strategies.
