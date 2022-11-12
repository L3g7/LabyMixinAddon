### Why use this template?
- Gradle 6.9.1 for faster building
- Mixin support

### How to use
- run `gradlew setupDecompWorkspace`
- run `gradlew idea`
- run `gradlew genIntellijRuns`
- open the project in IntelliJ IDEA
- The [Minecraft Dev](https://mcdev.io/) IntellJ plugin is recommended, but not required

### Configuration 
1. rename `example_addon.mixins.json`
2. update `gradle.properties`
3. update `MIXIN_CONFIG` in the `MixinLoader` class