## Next

- **Improvement**: `<Scope>` now accepts either an array or a string on the `href` prop
- **Deprecation**: `<Scope>` prop `hrefs` is deprecated pending removal in v3

## Version 2.1.4 (2026-07-10)

- **Improvement**: Use `currentTarget` for getting `<link>` element in loaded hrefs callback
- **BugFix**: Race condition for loaded hrefs state updater
- **Dev**: Added PNPM workspaces for demos

## Version 2.1.3 (2026-07-08)

- **Improvement**: Fallback for the `crypto` module to allow package use in non-https contexts
