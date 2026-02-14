# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.1.2] - 2026-02-14
### Added
- **AI Quiz Maker**: Increased question limit to 100.
- **AI Quiz Maker**: Expanded description textarea height (4x) for better prompt input.
- **Developer Settings**: Added `USE_EMULATOR` toggle in `firebase.ts` for easier prod/dev switching.

### Fixed
- **AI Generation**: Fixed "MAX_TOKENS" error by correcting model name and optimizing prompt.
- **Data Loading**: Added client-side sorting fallback for Quiz History to handle missing Firestore indexes gracefully.

## [0.1.1] - 2026-02-05
### Added
- **Wallet System**: Auto & Manual Star-to-Diamond Conversion, Password Protection.
- **Audio**: New reward sound effects.
- **Security**: Parent PIN for sensitive actions.

### Fixed
- Transaction history display.
- Audio player crash (migrated to SoundManager).

## [0.1.0] - 2026-01-21
### Added
- Initial release
