# Glass Todos

A soft, rounded, minimalist Flutter to-do app featuring translucent liquid-glass effects, haptic feedback, responsive layouts, and smooth lighting animations.

## Features
- Liquid glass UI (BackdropFilter + soft borders + depth)
- Animated lighting background with floating orbs
- Haptic feedback on every interaction
- Smooth implicit animations for check/uncheck and tile appearance
- Local persistence with Hive (works offline)
- Riverpod state management
- Light & dark mode
- Clean, soft rounded minimalist design

## Getting Started

```bash
flutter pub get
flutter run
```

> Note: Hive adapter is included manually so no code generation is required for the first run.

## Architecture
- Feature-based structure under `lib/features/todos`
- Riverpod `StateNotifier` for todo list
- Reusable `GlassContainer` widget for all glass surfaces

## Extending
- Add priorities or categories
- Sync with Firebase (Auth + Firestore)
- Add swipe-to-delete with custom haptic
- More complex lighting or particle effects

## Design Notes
The glass effect is intentionally soft and layered. Lighting orbs move slowly to create a calm, premium feel without distraction.
