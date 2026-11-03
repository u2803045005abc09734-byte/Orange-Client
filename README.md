# Orange Client

A standalone Fabric client project targeting Minecraft 1.21.11 and Java 21.

## Source

The complete Gradle source project is stored in [`orange-client-source.zip`](orange-client-source.zip). The GitHub Actions workflow extracts it and builds the Fabric mod JAR.

## Build

Pushes to `main` and manual workflow dispatch run the build in GitHub Actions. Download the `orange-client-jar` artifact from the workflow run's **Artifacts** section.

## Compatibility

- Minecraft 1.21.11
- Fabric Loader 0.18.4
- Java 21

Build status and runtime behavior must be verified by the CI run and in-game testing; a successful compile alone does not prove every feature works as intended.
