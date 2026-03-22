# Changelog

All notable changes to the Notty app are documented here.

---

## [v1.1.2] — 2026-03-22

### Added
- Global keyboard shortcut `⌘+Control+N` to toggle the panel from anywhere
- Resize grip indicator in the bottom-right corner

### Changed
- Only the bottom-right corner triggers window resize (was all 4 corners)

---

## [v1.1.1] — 2026-03-16

### Changed
- All comments and UI text translated to English

---

## [v1.1] — 2026-03-10

### Added
- CLI commands: `nt` and `notty` (aliases to the same binary)
- `nt <text>` - add a note from the terminal
- `nt list` - display all notes
- `nt clear` - clear all notes (with yes/no confirmation)
- `nt help` - show help
- Icon switches between `folder` and `folder.fill` when panel opens/closes
- Corner resize support
- Notes added via CLI instantly visible in the panel on next open

### Fixed
- Panel not opening when another app is focused
- Keyboard input blocked in borderless NSPanel
- Toggle race condition XD (panel closing and immediately reopening)
