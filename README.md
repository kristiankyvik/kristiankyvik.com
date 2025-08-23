# kristiankyvik.com

Personal website built with Hugo static site generator.

## Prerequisites

- Hugo (install with `brew install hugo` on macOS)

## Running Locally

```bash
hugo server -D
```

The site will be available at http://localhost:1313/

- The `-D` flag includes draft posts
- Server auto-reloads on file changes
- Press Ctrl+C to stop the server

## Structure

- `content/` - Markdown content files
- `themes/sk2/` - Site theme
- `config.toml` - Site configuration
- `public/` - Generated static files (created after build)