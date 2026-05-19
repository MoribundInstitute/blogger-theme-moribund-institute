# CSS Modules

The Blogger theme CSS is split into small modules so people can reuse only the pieces they need.

## Required base

Most modules expect:

- `00-tokens.css`
- `01-reset-base.css`
- `02-typography-links.css`

## Component modules

- `04-header.css` controls the main Blogger header.
- `07-catalog-mega-dropdown.css` controls the catalog mega menu.
- `10-side-panels.css` controls the Browse and Contents panels.
- `18-footer.css` controls the terminal footer.

## Blogger note

Blogger does not automatically assemble these files. For Blogger import, use `css/full-theme.css` or paste the relevant modules into the theme XML inside `<b:skin><![CDATA[ ... ]]></b:skin>`.
