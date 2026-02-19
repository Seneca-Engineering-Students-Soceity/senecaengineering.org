# senecaengineering.org

Official website for the Seneca Engineering Students Society, built with MkDocs.

## Prerequisites

- Python 3.x
- pip

## Installation

1. Clone the repository:
```bash
   git clone https://github.com/seneca-engineering-students-soceity/your-repo-name.git
   cd your-repo-name
```

2. Install MkDocs:
```bash
   pip install mkdocs
```

3. (Optional) Install the Material theme:
```bash
   pip install mkdocs-material
```

## Running Locally
```bash
mkdocs serve
```

Visit `http://127.0.0.1:8000` in your browser.

## Project Structure
```
.
├── docs/               # All markdown content goes here
│   └── index.md        # Home page
└── mkdocs.yml          # Site configuration
```

## Adding Content

Simply create `.md` files inside the `docs/` folder and add them to the `nav` section in `mkdocs.yml`:
```yaml
nav:
  - Home: index.md
  - New Page: new-page.md
```

## Deployment

This site is deployed via GitHub Pages. To deploy:
```bash
mkdocs gh-deploy
```

This builds the site and pushes it to the `gh-pages` branch automatically.

## Contributing

1. Fork the repository
2. Create a new branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -m 'Add some feature'`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Open a Pull Request

## License

This project is maintained by the Seneca Engineering Students Society.
