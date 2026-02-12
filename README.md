# Bianca Capretta's Personal Website

Personal portfolio website showcasing professional experience, research work, and personal projects.

**Live Site:** [www.biancacapretta.com](https://www.biancacapretta.com)

## Project Structure

This website has been stripped down to separate content from presentation, in preparation for a complete redesign.

```
.
├── content/              # Markdown files containing all website content
│   ├── config.md        # Site configuration and metadata
│   ├── home.md          # Home page content
│   ├── experience.md    # Professional experience content
│   ├── research.md      # Research projects content
│   └── projects.md      # Personal projects content
├── img/                 # Images and assets
├── index.html           # Minimal HTML placeholder for home page
├── experience.html      # Minimal HTML placeholder for experience page
├── research.html        # Minimal HTML placeholder for research page
├── projects.html        # Minimal HTML placeholder for projects page
├── CLAUDE.md            # Project context for Claude Code
├── CNAME                # Custom domain configuration
└── README.md            # This file
```

## Content Files

All website content has been extracted to readable Markdown files in the `content/` directory:

- **home.md** - Personal introduction, interests, and background
- **experience.md** - Work history from Spotify, LinkedIn, Microsoft, and more
- **research.md** - Academic research projects
- **projects.md** - Personal projects and side work
- **config.md** - Site metadata including navigation, social links, and assets

These content files are independent of any framework and can be used to rebuild the site with any modern tech stack.

## HTML Placeholders

The current HTML files are minimal placeholders with:
- Basic semantic HTML structure
- Simple inline CSS for visibility
- Comments indicating where content should be rendered
- Same filenames to maintain URL compatibility

These will be replaced during the redesign phase.

## Next Steps

The Bootstrap template has been completely removed. The next phase will involve:
1. Choosing a modern tech stack (React, Vue, Astro, etc.)
2. Setting up a new build system
3. Creating components that consume the Markdown content
4. Implementing a new, modern design

## Deployment

This site is deployed via GitHub Pages from the `master` branch.

## License

See [LICENSE](LICENSE) file for details.
