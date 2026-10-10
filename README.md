# scoop-bucket

[Scoop](https://scoop.sh) bucket for [FluentVoice Pro](https://github.com/nickotmazgin/fluentvoice-pro), a free, open-source text-to-speech tray app for Windows 11/10.

```powershell
scoop bucket add nickotmazgin https://github.com/nickotmazgin/scoop-bucket
scoop install nickotmazgin/fluentvoicepro
```

Installs the official portable release from GitHub (SHA-256 verified) and adds a Start menu shortcut and the `fluentvoicepro` command. Update with `scoop update fluentvoicepro`, remove with `scoop uninstall fluentvoicepro`. Settings and offline voices stay in `%USERPROFILE%\.fluentvoice`.

Prefer automatic updates without Scoop? FluentVoice Pro is also in the [Microsoft Store](https://apps.microsoft.com/detail/9N293MJ0MD9F) (`winget install 9N293MJ0MD9F --source msstore`).

The manifests in this bucket are MIT-licensed (see [LICENSE](LICENSE)). FluentVoice Pro itself is MIT with bundled third-party components; see its [licence notes](https://github.com/nickotmazgin/fluentvoice-pro/blob/main/THIRD_PARTY_NOTICES.md).
