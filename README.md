# SecondRide Documentation

This repository contains the official documentation for SecondRide.

## Live Documentation

Visit our live documentation at: **https://docs.second-ride.de**

## Local Development

### Setup
```bash
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

### Development Server
```bash
mkdocs serve
```
Opens at: http://localhost:8000

### Build Static Site
```bash
mkdocs build
```
Generates static files in `site/` directory.

## File Structure

```
docs/                   # Documentation content
├── index.md           # Homepage
├── guides/            # User guides
├── api/               # API documentation
├── faq/              # Frequently asked questions
└── ...
mkdocs.yml            # MkDocs configuration
requirements.txt      # Python dependencies
```

## Contributing

We welcome contributions to improve our documentation:

1. **Fork** this repository
2. **Edit** `.md` files in the `docs/` folder
3. **Preview** changes locally with `mkdocs serve`
4. **Submit** a pull request with your improvements

Changes to the main branch are automatically deployed to the live site.

## Support

For questions about SecondRide or this documentation:
- Browse the [FAQ section](https://docs.second-ride.de/faq/)
- Check our [User Guides](https://docs.second-ride.de/guides/)
- Contact support through the SecondRide platform

- 
