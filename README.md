###### This template is also available for [Forge](https://github.com/L3g7/ForgeMixin).

### Why use this template?
- Gradle 6.9.1 for faster building and better IntelliJ IDEA support
- Mixin support

### How to use
1. run `gradlew setupDecompWorkspace`
2. run `gradlew idea`
3. run `gradlew genIntellijRuns`
4. open the generated `.ipr` file in IntelliJ IDEA
5. The [Minecraft Dev](https://mcdev.io/) IntellJ plugin is recommended, but not required

### Rebranding
1. update `refmap` in `example_addon.mixins.json`
2. rename `example_addon.mixins.json`
3. update `gradle.properties`
4. update `MIXIN_CONFIG` in the `MixinLoader` class
