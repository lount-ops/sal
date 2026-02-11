## README for shitass.life

Hugo website utilizing hello-4s3ti for theme duty.

## Project Structure

```code
sal/
├── content/             # Markdown content files
│   ├── _index.md        # Home page content
├── themes/
│   └── hugo_theme-hello-4s3ti/       # hello-friend-ng based theme
│       ├── layouts/     # HTML templates, shortcodes, posts, Etc...
│       │   ├── _default/
│       │   │   └── baseof.html
|       |   |   |__ list.html
|       |   |   |__ single.html
│       │   ├── partials/
│       │   │   ├── header.html
│       │   │   └── footer.html
|       |   |   |__ categories.html
|       |   |   |__ favicons.html
|       |   |   |__ head.html
|       |   |   |__ javascript.html
|       |   |   |__ lastmod.html
|       |   |   |__ ...
│       │   ├── posts/
│       │   │   └── single.html
│       │   └── index.html
│       └── assets/
│           └── css/
│               └── main.css
├── hugo.yaml            # Hugo configuration
├── hugo.css             # CSS configuration

```

## Prerequisites

- [Hugo Extended](https://gohugo.io/installation/) (v0.112.0(?) or higher, working on v0.155.0)
- Hugo Apt repo; ```deb [arch=amd64 signed-by=/etc/apt/keyrings/hugo.gpg] https://hugo-apt.8hob.io latest main```
- [Node.js](https://nodejs.org/) (v16 or higher, currently on Debian 12, w/ node.js v18.20.4)
- npm or yarn

## Setup

1. Run the development server:

```zsh
hugo server -D
```

1. Visit `http://localhost:1313` in your browser

## Build for Production

```zsh
hugo --minify
```

When the Hugo server runs it will place production files that it generates, in the `public/` directory.

## Customization

### Navigation

Update menu items in `hugo.toml`:

```toml
[[menu.main]]
  name = "Home"
  url = "/"
  weight = 1
```

### Images

Images added inline via markdown.

### Content


## Pages

## Features

- ✅ Responsive design (mobile, tablet, desktop)
- ✅ CSS for styling
- ✅ Clean, modern aesthetic
- ✅ Mobile-friendly navigation
- ✅ Fast(ish) performance

## Adding New Pages

1. Create a new markdown file in `content/`:

```zsh
hugo new about.md
```

## Support

For Hugo documentation, visit: [GoHugo](https://gohugo.io/documentation/)
For [Hello-4s3ti](https://github.com/coolapso/hugo-theme-hello-4s3ti/tree/master/layouts)

## License

MIT License - feel free to use and modify for your needs.
2026 - shitass.life
