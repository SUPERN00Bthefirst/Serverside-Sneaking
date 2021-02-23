![Project icon](https://github.com/SUPERN00Bthefirst/Serverside-Sneaking/raw/main/src/main/resources/assets/serversidesneaking/icon.png)
<br>
# Serverside Sneaking Fix
![GitHub license](https://img.shields.io/github/license/SUPERN00Bthefirst/Serverside-Sneaking.svg)
![GitHub issues](https://img.shields.io/github/issues/SUPERN00Bthefirst/Serverside-Sneaking.svg)
![GitHub tag](https://img.shields.io/github/tag/SUPERN00Bthefirst/Serverside-Sneaking.svg?include_prereleases)
<br>A fork of a Minecraft Fabric mod ([Original](https://github.com/bytzo/mc-202202)) to fix [MC-202202](https://bugs.mojang.com/browse/MC-202202) and bring back support for serverside sneaking to minecraft 1.16.

## WARNING: 
This mod is strictly disallowed on servers like hypixel<br> 
as it modifies how the game interatcts with the server, DO NOT USE ON HYPIXEL!


## License

MIT License

## Copyright

Copyright © 2021 Bytzo

## Building from source

If you would like to compile a custom build of this mod from the latest sources, you'll want
to start here.

#### Prerequisites

You will need to install JDK 8 (or newer, see below) in order to build this. You can either install this through
a package manager such as [Chocolatey](https://chocolatey.org/) on Windows or [SDKMAN!](https://sdkman.io/) on other
platforms. If you'd prefer to not use a package manager, you can always grab the installers or packages directly from
[AdoptOpenJDK](https://adoptopenjdk.net/).

On Windows, the Oracle JDK/JRE builds should be avoided where possible due to their poor quality. Always prefer using
the open-source builds from AdoptOpenJDK when possible.

#### Compiling

Navigate to the directory you've cloned this repository and launch a build with Gradle using `gradlew build` (Windows)
or `./gradlew build` (macOS/Linux). If you are not using the Gradle wrapper, simply replace `gradlew` with `gradle`
or the path to it.

The initial setup may take a few minutes. After Gradle has finished building everything, you can find the resulting
artifacts in `build/libs`.
