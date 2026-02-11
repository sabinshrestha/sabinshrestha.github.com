# Dev Blog — GitHub Pages

A minimal, dark-themed blog built with static HTML and CSS. No frameworks, no Jekyll — just clean files deployed on GitHub Pages.

## Structure

```
├── index.html                        # Home / profile page with blog listing
├── style.css                         # Shared stylesheet
├── .nojekyll                         # Tells GitHub to skip Jekyll processing
├── README.md                         # This file
└── posts/
    └── github-achievements.html      # Blog post: All the GitHub Achievements
```

## Setup

1. Fork or clone this repo
2. Replace `yourusername` with your actual GitHub username in `index.html` and the post files
3. Customize the profile section in `index.html` with your name, bio, and links
4. Go to **Settings → Pages → Deploy from branch** and select `main`
5. Your site will be live at `https://yourusername.github.io`

## Adding New Posts

1. Create a new `.html` file inside the `posts/` folder (copy an existing post as a template)
2. Add a new post card to `index.html` linking to your new post
3. Commit and push — GitHub Pages deploys automatically

## Customization

- **Colors**: Edit CSS variables in `:root` at the top of `style.css`
- **Fonts**: Change the Google Fonts import in the `<head>` of each HTML file
- **Layout**: The max content width is controlled by `--max-width` in `style.css`

## Tech

- Pure HTML + CSS + vanilla JS
- Google Fonts (Outfit + JetBrains Mono)
- No build step, no dependencies
- Responsive by default

## License

Do whatever you want with it. No attribution needed.
