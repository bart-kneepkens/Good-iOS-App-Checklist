# Good-App-Checklist
An opinionated list of features that every good iOS app should have. (Apps to be published in the App Store, that is)

### 1. Localized for release regions
- All user-facing text should be translated in the primary locales of the regions you intend to release to
- All text should work in a locale's default layout direction, also supporting right-to-left layouts
- If the app has clocks, they should respect the user's region's default clock format (12h or 24h clocks)
- If the app has a calendar, they should respsect the user's iOS preferred calendar type

### 2. Accessibility
- User-facing text should use dynamic fonts sizing. (percentage)
- User-facing text should have proper accessibility labels set (if applicable)

### 3. GDPR Compliant
- If the app will be released in a EU state member country and has a sign-in, the app should comply to GDPR

### 4. Support platform-specific UX patterns
- Swipe to go back (iOS)
- Haptic feedback (iOS)
- Date pickers

### 5. Support dark / low contrast modes
User expect apps to respect the OS-wide dark mode. 

### 6. Has a framerate of at least 60 fps
Try to stay above 60fps throughout the runtime of the application. Anything lower may look sluggish.

### 7. Somewhat usable without internet connection
Don't introduce banners or block the entire UI when there is no internet connection. Instead, implement caches or offline first so the user isn't restricted that much

### 8. Backwards compatibilty with persisted data
On every app update, make sure that changes in the persisted data are handled correctly.

### 9. Non-interruptive user flows
Alerts and popups should be used sparingly, as they require immediate user attention and a call to action.
