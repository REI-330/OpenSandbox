# Console i18n screenshots for #2907

Screenshots used in the pull request description for the Developer Console English/Simplified Chinese switcher. They are kept on this separate branch so the pull request itself stays code-only.

- `before-*` — `ee94e8ae` (upstream main), English only, no language switcher.
- `after-*-en` / `after-*-zh` — `agent/console-i18n`, English default and Simplified Chinese selected.

Viewport 1440x900, light theme, production build (`npm run build`). The pages need a BFF, so a local mock BFF with fixed English sample data rendered them; only the UI copy changes between captures.