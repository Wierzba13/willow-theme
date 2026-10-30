# Change Log

All notable changes to the "willow-theme" extension will be documented in this file.

## [1.0.0] - 2026-10-30

### Added
- **Modern VS Code Compatibility**: Raised engine requirement to `^1.85.0` with full support for modern workbench features.
- **Bracket Pair Colorization**: Native multi-color bracket highlighting (`editorBracketHighlight.foreground1-6`) and guide lines matching the Willow palette (green, cyan, purple, gold, blue, pink).
- **Command Center**: Styled title bar search and action center (`commandCenter.*`).
- **Sticky Scroll**: Added custom styling for sticky scope headers in both code editor and tree views (`editorStickyScroll.*`, `tree.stickyScrollBackground`).
- **Activity Bar Top Layout**: Full support for modern top-aligned activity bar (`activityBarTop.*`).
- **Multi-Level Indent Guides**: Added support for modern indent guide levels 1 through 6 (`editorIndentGuide.background1-6`, `editorIndentGuide.activeBackground1-6`).
- **Inlay Hints**: Custom colors for inline parameter and type hints (`editorInlayHint.*`).
- **AI & Chat Components**: Styling for chat windows, inline chat, and interactive sessions (`chat.*`, `inlineChat.*`).
- **Modern Diff Editor**: Highlighting for inline changes, gutters, and unchanged code collapse regions.
- **Testing & Keybindings**: Distinct colors for test status icons (`testing.*`) and keyboard shortcut badges (`keybindingLabel.*`).
- **Semantic Token Colors**: Expanded `semanticTokenColors` for classes, interfaces, types, functions, methods, parameters, properties, decorators, and variables across modern TypeScript, Python, Rust, and C#.
- **JSON Schema Validation**: Added `$schema` reference for instant validation and IntelliSense in theme definitions.
- **Marketplace Metadata**: Added MIT License, repository links, and gallery dark banner styling.

### Fixed
- Fixed critical contrast issue with notification toasts (`notifications.foreground`), changing text color to bright white (`#ffffff`) for optimal readability against dark backgrounds.
- Updated `.vscodeignore` to exclude development artifacts and `.vsix` packages.

---

## [0.0.1] - 2021-05-19
- Initial release.
