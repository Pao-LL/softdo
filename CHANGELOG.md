# Changelog

## [1.7.0] - 2026-10-15

### Added

- **Today / Later buckets**: Split tasks into today's work and long-term/later items.
- **Move between lists**: Hover or right-click a task to send it to the other list.


## [1.6.3] - 2026-02-06

### Fixed

- **Always on Top**: Fixed pin feature sometimes failing by re-applying on window focus
- **Delete Button**: Now shows delete button for completed tasks on hover
- **Notification System**: Fixed notifications not triggering for due tasks

### Added

- **Sound Alerts**: System beep sound for all task reminders
- **Dialog Alerts**: Popup dialog for urgent "due now" notifications
- **Notification Check**: Startup check for Windows notification permissions
- **Reminder Timing**: Notifications at 1 hour before, 5 minutes before, and due time

## [1.2.6] - 2026-01-25

### Changed

- **UI Polish**: Unified button styles with Apple-like squircle rounding (`rounded-[18px]`).
- **Time Picker**: Improved layout spacing and button visibility.
- **Animations**: Fixed "teleporting" empty state animation; improved "Clear All" transition.
- **Calendar**: Fixed alignment issues and 18:00 preset visibility.
- **Layout**: Fixed layout shift caused by scrollbar appearance.

## [1.2.5] - 2026-01-25

### Added

- **Rename Task**: Hover over a task to see the edit (pencil) button. Click to edit in-place.

## [1.2.4] - 2026-01-25

### Fixed

- Critical startup crash due to missing `checkForUpdates` function.
- Version comparison logic to handle 'v' prefix.

## [1.2.3] - 2026-01-24

### Added

- Auto-update check on launch.

### Fixed

- White background on Tray icon (switched to PNG).

## [1.2.0-1.2.2]

- Initial Release & Bug fixes.
