# morefuelsmod-1.13
Early Testing! Do not use! Forge Isn't Even Stable, so why would you expect this to work?

### Contributors
* Noah Martino (personal.boredhero@gmail.com)

### Basic Setup Instructions

#### Dependencies:
* Eclipse for Java Developers
* JDK 9 or 10 (11+ will not work with this version of Minecraft/Forge)
* git command line tools OR GUI git client

#### Steps:
* cd into morefuelsmod-1.13 folder
* run command: "gradlew genEclipseRuns" or "./gradlew genEclipseRuns" (for Linux/Mac
* Open Eclipse, Import > Existing Gradle Project > Select Folder or run "gradlew eclipse" to generate the project.
* Open Project > Run/Debug Settings > Edit runClient and runServer > Environment
* Edit MOD_CLASSES to show [modid]%%[Path]; 2 times rather then the generated 4.

#### Further Notes:
* While it *IS* possible to use IntelliJ IDEA, I **strongly prefer** contributors to use Eclipse just to keep the code nice n pure since this repo has more than just the src folder.
* You can configure the amount of RAM used for script operations/build operations in gradle.properties. Default for this repo is 4 but adjust accordingly.

