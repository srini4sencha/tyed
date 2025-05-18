# Static Blog Website

This is a simple static blog website built with Bootstrap (via CDN), React (via CDN), and `react-markdown` (via CDN).  
It loads blog data from a local JSON file and displays them as responsive cards. On clicking a card, the full blog post opens.

## Features
- Uses Bootstrap 5 for responsive layout via CDN
- Uses React and ReactDOM via CDN
- Uses `react-markdown` via CDN for Markdown rendering
- Blog data is loaded from a static JSON file in the repo
- Clean card layout for blogs
- Click a card to view full blog post

## How to Use

1. Clone or download this repo.
2. Place your blogs in `blogs.json` (see format below).
3. Open `index.html` in your browser.

## `blogs.json` format

```json
[
  {
    "date": "2025-05-18",
    "title": "My First Blog",
    "content": "# Hello World\nThis is my first blog post written in **Markdown**!"
  },
  {
    "date": "2025-05-17",
    "title": "Another Post",
    "content": "React is awesome! \n\n- Uses CDN\n- Easy to setup"
  }
]
```