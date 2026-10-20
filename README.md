# Hardcore Red & Black for Sable

A community-made, OLED-friendly red-and-black theme for the [Sable Matrix client](https://github.com/SableClient/Sable).

> **Status: experimental.** Not affiliated with or endorsed by the Sable project. Appearance and compatibility have not yet been confirmed in the current Sable client.

## Palette

- Black backgrounds: `#000000`, `#080808`
- Dark red surfaces, borders, and selection states
- Blood-red primary buttons and interactive accents
- Light text for readability

## Installation

1. Download [`themes/hardcore-red-black.sable.css`](themes/hardcore-red-black.sable.css).
2. In Sable, use the **full custom / remote theme** feature if your client version supports it.
3. Supply the file or the raw CSS URL, activate the theme, and reload Sable if required.

**Raw CSS URL:**

```text
https://raw.githubusercontent.com/AnARCHIS12/sable-hardcore-red-black/main/themes/hardcore-red-black.sable.css
```

**Important:** The stylesheet intentionally uses `body.sable-remote-theme`, matching the upstream full theme format. Pasting it into a generic Quick CSS / QCSS field may not activate those rules. It is a complete theme, not a QCSS tweak.

## Origin and credits

Adapted from **Pitch Black**, originally authored by **Hannes Thöne**, published in the official [SableClient/themes](https://github.com/SableClient/themes/blob/main/themes/pitch-black.sable.css) repository.

The original theme's structure and component selectors are retained. This adaptation changes backgrounds, surface colors, accent colors, and interaction states to a red-and-black palette. All rights in upstream contributions remain with their respective holders.

## License

Licensed under **GNU Affero General Public License v3.0 (AGPL-3.0-only)**, consistent with the upstream theme repository. See [LICENSE](LICENSE).

## Contributing

Issues and pull requests for color contrast, theme compatibility, and UI refinements are welcome. Include your Sable version and screenshots where possible.
