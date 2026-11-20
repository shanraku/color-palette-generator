# Color Palette Generator

A free, privacy-friendly color toolkit for everyone. Generate palettes, explore color values, check text contrast, and export your colors — directly in your browser.

## Features

- Generate harmonious random palettes
- Edit individual colors and lock colors while generating
- Copy HEX, RGB, and HSL values
- Create and preview CSS gradients
- Check WCAG-style text/background contrast ratios
- Export palettes as CSS variables and JSON
- Responsive interface with dark/light theme
- No account, backend, API key, or upload required

## Run locally

Open `index.html` in a modern browser, or start a local server:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Privacy

All palette generation and calculations happen locally in your browser. This application does not upload your colors.

## Accessibility

The contrast checker reports the calculated contrast ratio and whether it meets WCAG 2.2 AA text contrast thresholds (4.5:1 for normal text and 3:1 for large text). It is a helpful check, not a full accessibility audit.

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md). Report security concerns using [SECURITY.md](SECURITY.md).

## License

MIT. See [LICENSE](LICENSE).
