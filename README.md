# Scavenger Hunt 
This is a desktop Scavenger Hunt game for photos

## Getting Started
### System Requirements
- [Java Development Kit 7+ (JDK)](http://www.oracle.com/technetwork/java/javase/downloads/index.html)
- [Intellij IDEA](https://www.jetbrains.com/idea/)

### Build

First, clone the project
```
$ git clone https://github.com/sedara2205/scavengerHunt
```

Then, open it in Intellij and set up configurations. 


### Configuring Android

You need to have the Android SDK installed to continue.  I recommend installing the stand-alone version of the SDK instead of the ADT bundle ( which is Android SDK + Eclipse ).  You can download the -[Android SDK here](https://developer.android.com/studio).  The download can be a bit tricky to located, Scroll down and locate “DOWNLOAD FOR OTHER PLATFORMS”, then locate SDK Tools only and download the appropriate package.

### Configuring IntelliJ
Make sure you have version 13 or higher.  You can download it [here](https://www.jetbrains.com/idea/download/?section=windows).  Community edition is fine, in fact, not much of the paid version is of use to a game developer.  Download and install IntelliJ 13.x if you haven’t already.

We need to setup our JDK and Android SDK in IntelliJ.  If you haven’t already, [install and configure the Java 7 JDK](https://www.oracle.com/java/technologies/javase/upgrade.html).


Run IntelliJ.

In the welcome dialog, select Import Project

Navigate to the directory you created your project in earlier and select build.gradle from the root directory:

radle is now going to build your project… or at least try.

Gradle downloads all the required components, so this could take a while.   Or it should, but truth is, its going to explode in a horrible state of explosionness.  


Navigate to the location you installed your JDK.

 

Next click + again, and this time select Android SDK.  Select the Android SDK location and click OK.

This time you also have to pick the version:

## How to play

Once you finish buid the game, you can launch the game by running ```DesktopLauncher``` class. You can use arrowkeys to navigate around the map, and use mouse to click on the button. 

## Future Work
This game can be improved in many ways. It currently has a foundational platform that could potentially incorporate more interesting game features. For example: 

- Players can collect food and drink while walking on the map
- Players can attack enemies
- Multi-chain of story lines
