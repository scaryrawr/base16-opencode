# opencode-base16-themes

A collection of [base16](https://github.com/tinted-theming/home) and base24 themes for [opencode](https://opencode.ai), auto-generated and always up to date.

## Installation

To install all themes for opencode, simply clone this repository into your opencode config directory:

```sh
mkdir -p ~/.config/opencode
cd ~/.config/opencode
git clone https://github.com/scaryrawr/base16-opencode
```

Or, copy/symlink the `themes/*.json` files into `~/.config/opencode/themes`.

## Usage

After cloning, restart opencode or use `/theme` to select a theme.

## How it works

- Themes are generated from base16/base24 schemes using [base16-builder-go](https://github.com/tinted-theming/base16-builder-go) and custom templates for opencode.
- A GitHub Actions workflow keeps themes up to date automatically.

## Contributing

- Add or update templates in `templates/`
- Open a PR to add new schemes or improve templates

## Automation

- On template or workflow changes, or every Saturday, the workflow will regenerate all themes and open a PR if there are updates.

## License

MIT
