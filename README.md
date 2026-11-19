# jchucomponents-maven

Maven repository with the Kotlin Multiplatform artifacts of
[jchucomponents](https://github.com/Jeluchu/jchucomponents), used while Maven Central is unavailable.

```kotlin
// settings.gradle.kts
dependencyResolutionManagement {
    repositories {
        maven("https://raw.githubusercontent.com/jeluchu/jchucomponents-maven/main")
    }
}
```

Coordinates are the same as on Maven Central: `io.github.jeluchu:jchucomponents-<module>:<version>`.
