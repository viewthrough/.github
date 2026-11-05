# Viewthrough

Viewthrough connects creator posts to app installs, trials and revenue — UGC attribution for indie app developers. [viewthrough.app](https://viewthrough.app)

## SDKs

Only the money events — install, app open, onboarding, paywall, checkout — batched and offline-safe. Revenue comes from RevenueCat. One rule: call `identify` with the same user id you give RevenueCat.

| Platform | Repository | Install |
|---|---|---|
| iOS (Swift) | [viewthrough-ios-sdk](https://github.com/viewthrough/viewthrough-ios-sdk) | Swift Package Manager, or drop in [Viewthrough.swift](https://viewthrough.app/sdk/Viewthrough.swift) |
| Android (Kotlin) | [viewthrough-android-sdk](https://github.com/viewthrough/viewthrough-android-sdk) | drop in [Viewthrough.kt](https://viewthrough.app/sdk/Viewthrough.kt) |
| Flutter (Dart) | [viewthrough-flutter](https://github.com/viewthrough/viewthrough-flutter) | drop in [viewthrough.dart](https://viewthrough.app/sdk/viewthrough.dart) |
| React Native / Expo / Web | [viewthrough-react-native](https://github.com/viewthrough/viewthrough-react-native) | `npm install @viewthrough/sdk` |

Docs: [viewthrough.app/docs/sdk](https://viewthrough.app/docs/sdk) — including the HTTP API for any other platform.

## MCP server

Ask Claude, Cursor or ChatGPT how last week went, straight from your data: [viewthrough.app/docs/mcp](https://viewthrough.app/docs/mcp)
