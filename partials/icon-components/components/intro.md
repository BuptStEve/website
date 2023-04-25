```yaml
replacements:
  - code: '60,000'
    value: '${counters.icons}'
  - code: '80+'
    value: '${counters.sets}+'
```

In addition to [SVG framework](/icon-components/svg-framework/index.md), Iconify offers native components for several popular UI frameworks. Iconify for React is one of such components.

Yet another icon component? What are advantages over other icon components?

- One syntax for over 60,000 icons from 80+ icon sets.
- Renders SVG. Many components simply render icon fonts, which look ugly. Iconify renders pixel perfect SVG.
- Loads icons on demand. No need to bundle icons, component will automatically load icon data for icons that you use from Iconify API.
