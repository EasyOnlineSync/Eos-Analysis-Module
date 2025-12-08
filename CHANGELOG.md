# Changelog
All notable changes to this extension will be documented here.

## v0.1
- Failure

## v0.2
- Failed to load

## v0.3
- Loaded, failed to send URL

## v0.4
- Loaded, no failures when sending

## v0.5
- Failed to send data to host

## v0.6
- Fatal error, unable to load

## v0.7
- Failure with 'service worker'

## v0.8
- Fixed 'service worker' errors, sending normalized

## v0.9
- Added 'title' to sending via NativeMessaging

## v1.0 – Thursday, November 20, 2025 (week 47)
- Loaded with all plugins
- Icons loaded
- Hosts loaded
- No errors, finalized

## v2.0.0 – Monday, December 8, 2025, week 50
- All plugins loaded and functional
- New permissions added to the Manifest
- Bugs fixed
- Host working correctly
- Changes to the host, adding file "type" when uploading
- All files tested and corrected
- No errors

### New Features
- **Settings Page (Options Page)**
  - Interface with tabs: Files, Sites/Plugins, and About.
  - Save and reset preferences.
  - Visual feedback when saving or resetting.

- **Language Support (i18n)**
  - Added translation files for all extension texts.
  - Labels, buttons, titles, and messages now adapt to the user’s language.
  - `de – Deutsch`
  - `en – English`
  - `es – Español`
  - `fr – Français`
  - `ja – 日本語`
  - `ko – 한국어`
  - `pt-BR – Português (Brasil)`
  - `zh_CN  – 中文 (简体)`
  - `zh-TW – 中文 (繁體)`
- **File Interception for Native Program Download**
  - Supported file types:
    - `.exe`
    - `.zip`
    - `.rar`
    - `.msi`
    - `.7z`
    - `.iso`
    - `.apk`
    - `.dmg`
  - Intercepted files are sent to the native program for downloading.

- **New Site Plugins**
  - **anitube.news**
  - **animesonlinecc.to**
  - **xvideos.com**
