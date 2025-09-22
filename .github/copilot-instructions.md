# GitHub Copilot Instructions for Better Jump Pack (Continued)

## Mod Overview and Purpose
**Better Jump Pack (Continued)** is a mod for RimWorld that enhances the functionality of jump packs. Originally based on YAYO's mod, this continuation allows jumpers to traverse walls, destroy roofs upon landing, and take damage from these impacts. This mod aims to expand the tactical possibilities in RimWorld by introducing realistic constraints and interactions when using jump packs.

### Key Features and Systems
- **Cross-wall Jumping**: Allows jump packs to fly over walls, expanding mobility options.
- **Roof Destruction**: Jumping under a roof will result in its destruction and inflict damage on the jumper.
- **Mountain Roof Restrictions**: Jumping to or under mountain roofs is prohibited to maintain in-game consistency and balance.
- **Expansion Potential**: The mod encourages different variations and ideas to further enhance jump pack functionalities.

## Coding Patterns and Conventions
- The project predominantly uses **static classes** and **methods** for utility and helper functionalities. This pattern keeps the code organized and efficient.
- **PascalCase** is consistently used for naming classes and methods.
- Methods are primarily designed to evaluate or process game logic related to jump capabilities.

## XML Integration
- XML integration is crucial for configuring mod settings and defining custom game behavior. Unfortunately, the specified files do not currently show direct XML interactions. However, XML files would typically be used for defining items, settings, and translations associated with the jump pack.

## Harmony Patching
- The mod uses Harmony, a popular library for modifying .NET applications, to apply patches to the game's existing methods. 
- The class `HarmonyPatches` contains static methods that utilize Harmony to modify game methods critical to jump pack functionality.
- Patching is fundamental for adding new behaviors or altering existing ones without modifying the original game codebase directly.

## Suggestions for Copilot
- **Functionality Expansion**: Suggest functions that could add variations of jump pack abilities, such as increased range, reduced impact damage, or integration with other abilities.
- **XML Integration**: Recommend methods or structures to read, write, or process XML configurations to enable customization within the mod.
- **Testing and Validation**: Create unit tests for core methods to ensure functionality is robust, especially regarding necessary conditions such as roof destruction and jump restrictions.
- **Optimization and Refactoring**: Suggest code optimizations or refactoring when detecting complex logic that can be streamlined. This includes combining similar methods or extracting repeated logic into utility functions.
- **Compatibility Checks**: Introduce compatibility checks with other mods or game updates, ensuring that the mod remains stable across different game versions.

For further development ideas or to discuss potential collaboration, please contact the original mod author via the RimWorld Discord channel. Additionally, developers are encouraged to fork this repository and propose innovative ideas to enhance or expand upon the current features of the mod.
