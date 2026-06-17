<div align="center">
  <img src="https://github.com/sxyazi/yazi/blob/main/assets/logo.png?raw=true" alt="Yazi logo" width="20%">
</div>

<h3 align="center">
  <a href="https://monokai.pro/">Monokai Pro</a> Flavor for <a href="https://github.com/sxyazi/yazi">Yazi</a>
</h3>

## 👀 Preview

*PREVIEW COMING SOON*

## 🎨 Installation
### Using package manager (recommended)

```sh
ya pkg add devert/monokai-pro
```

### Manual install

Clone into your Yazi flavors directory:

```sh
# Linux/macOS
git clone https://github.com/devert/monokai-pro.yazi.git ~/.config/yazi/flavors/monokai-pro.yazi

# Windows
git clone https://github.com/devert/monokai-pro.yazi.git %AppData%\yazi\config\flavors\monokai-pro.yazi
```

## Usage

Add the flavor to your `~/.config/yazi/theme.toml`. Currently only supports *dark* mode.

```toml
[flavor]
dark = "monokai-pro"
```

Make sure your `theme.toml` doesn't contain anything other than `[flavor]`, unless you want to override certain styles of this flavor. User overrides in `theme.toml` are merged on top of the flavor and take precedence, so you can tweak individual colors without forking.

See the [Yazi flavor documentation](https://yazi-rs.github.io/docs/flavors/overview) for more details.

## Credits

- [Monokai Pro](https://monokai.pro/) by [Wimer Hazenberg](https://github.com/Monokai)
- [Yazi](https://github.com/sxyazi/yazi) and its [flavor spec](https://yazi-rs.github.io/docs/flavors/overview).

## License

See [LICENSE](LICENSE) for the flavor itself and [LICENSE-tmtheme](LICENSE-tmtheme) for the bundled tmTheme.
