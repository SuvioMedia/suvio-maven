# Suvio Maven Repository

Public binary Maven repository for Suvio plugin SDK artifacts.

Use this repository from Gradle:

```kotlin
pluginManagement {
    repositories {
        maven("https://suviomedia.github.io/suvio-maven")
        gradlePluginPortal()
        mavenCentral()
    }
}

dependencyResolutionManagement {
    repositories {
        maven("https://suviomedia.github.io/suvio-maven")
        mavenCentral()
    }
}
```

Available SDK version:

```text
0.1.0
```
