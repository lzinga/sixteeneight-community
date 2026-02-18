## [v2026.02.17.1607]
### ♻️ Refactor
- Improved backup and export to use a .zip file format instead of pure JSON (still uses JSON internally, but makes it easier to manage)
- Updated button styles and phase indicator colors for consistency across the app

### ✨ Features
- Enhanced stats page with cleaner calendar switching and improved error handling for ratings and sessions
- Added "What's New" prompt after app updates so you know what changed
- Enhanced missed fast catch-up with improved UI and state management


### 🐛 Bug Fixes
- Fixed missed fasts from being stuck in a popup loop. You can now properly skip or add missed fasts
- Fixed streak calculator to include active fasting sessions (while fasting it would incorrectly show a broken streak)
- Fixed various minor UI glitches in calendar and progress components

### 📝 Other
- Removed community section from settings page

## [v2026.02.12.0832]
### ✨ Features
- Add display Y-axis labels in weight chart when sharing
- Add option to save stats image locally instead of through share menu
- Add Reddit community link and button to feedback page
- Add fasting end time calculation in fast schedule editor
  
### ♻️ Refactor
- Improve layout and padding in FastCompleteCelebrationPage for better responsiveness
- Improve weight menu from being blocked by keyboard/three button navigation bar
- Updated "Timer" button in the navigation bar to be "Home" instead
  
### 🐛 Bug Fixes
- Update support email address to reflect new domain
- Preserve user modifications when converting preset plans to custom


## [v2026.02.09.1627]
- Reverted community features to prepare for production release. Community backend needs a bit more work before prime time
- All local options will still work as expected
