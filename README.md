# Hunter Quest — Native Android

A free, native Android Studio project built with Kotlin + Jetpack Compose.

## Features
- E → D → C → B → A → S ranks
- 10% compound difficulty per rank
- Daily quest tracking for push-ups, sit-ups, squats and running
- XP, level and streak
- Theme selector
- Offline/local app operation
- Dark neon HUD-inspired interface

## Build
1. Open this folder in Android Studio.
2. Let Gradle sync.
3. Connect an Android phone or start an emulator.
4. Run `app`.

No paid API or server is required.

## Notes
The current project is a functional prototype. The "UNLOCK NEXT RANK (DEMO)" button is intentionally exposed for testing. In a production release, rank promotion should be tied to the 30-day completion rules and persistence should be moved to DataStore/Room.
