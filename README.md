# rrhaya Homebrew tap

Homebrew packages for [clipref](https://github.com/rrhaya/clipref).
Requires macOS.

```sh
brew install rrhaya/tap/clipref
pbe --version
brew upgrade clipref
brew uninstall clipref
```

Both `pbe` and `clipref` run the same tool. Saved files are kept after uninstalling.
If you also used the shell installer, run `command -v pbe` to check which installation your shell uses.

Formula tests use `--version` and `--help`; they do not access the clipboard.

To update the formula, download the release archive and run
clipref's `packaging/homebrew/prepare-formula.sh`. Review the generated URL and
checksum, then run `brew style`, `brew audit --strict`, `brew install`, and
`brew test` before publishing.

MIT. See [LICENSE](LICENSE).
