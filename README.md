# Suvio Maven Repository

Public binary Maven repository for Suvio plugin SDK artifacts.

Use this repository from Gradle:

```kotlin
pluginManagement {
    repositories {
        maven("https://raw.githubusercontent.com/SuvioMedia/suvio-maven/main/")
        gradlePluginPortal()
        mavenCentral()
    }
}

dependencyResolutionManagement {
    repositories {
        maven("https://raw.githubusercontent.com/SuvioMedia/suvio-maven/main/")
        mavenCentral()
    }
}
```

Available SDK version:

```text
0.1.0
```
