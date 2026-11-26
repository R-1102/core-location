# Core Location

A reusable Android library designed to centralize location services, permission handling, distance calculation, and Google Maps integration.

Developed using Kotlin and Jetpack Compose, the library provides modular location functionality that can be integrated into multiple Android features without duplicating implementation logic.

## Features

- **Location Services:** Retrieve current and last known device locations using the Fused Location Provider.
- **Permission Handling:** Manage fine and coarse location permissions.
- **Google Maps Integration:** Reusable map components built with Jetpack Compose.
- **Distance Calculation:** Calculate geographical distances using the Haversine formula.
- **Coordinate Validation:** Validate geographical coordinates before processing.
- **Map Markers:** Display multiple locations and manage selected markers.
- **Camera Management:** Control map positioning, zoom, and animated transitions.
- **Distance Radius:** Visualize configurable geographical ranges around the user's location.
- **Dependency Injection:** Manage location dependencies using Koin.

## Technologies

- Kotlin
- Jetpack Compose
- Material 3
- Google Maps SDK
- Maps Compose
- Google Play Services
- Fused Location Provider
- Kotlin Coroutines
- Koin
- Gradle Kotlin DSL

## Architecture

The library follows a layered architecture inspired by Clean Architecture principles, promoting separation of concerns, modularity, maintainability, and code reusability.

| Layer | Responsibility |
|---|---|
| Presentation | Map components, permission handling, camera effects, and map state |
| Domain | Models, use cases, and repository interfaces |
| Data | Location providers and repository implementations |
| DI | Dependency configuration using Koin |

## Project Structure

```
core-location/
├── di/
└── location/
    ├── data/
    │   └── repository/
    ├── domain/
    │   ├── model/
    │   ├── repository/
    │   └── usecase/
    └── screen/
        └── component/
```


## Project Background

Developed in September 2025 as a reusable location library within a modular Android application.

My contribution focused on the independent development of the location module, including location services, map components, permission management, distance calculation, and dependency integration.
