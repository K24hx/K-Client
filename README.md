
# K CLIENT

Private Bleachhack skid by K24h.
Works on Fabric 1.19 and above (Probably 1.18 too, didn't test it).


## Installation
### For normal people

Download the .jar file you can find in the releases. Then put the file into your mods folder.

### For (1000 IQ) developers

Download the branch with the version you want to work on.  
Start A Command Prompt/Terminal in the main folder.  
Generate the needed files for your preferred IDE.  

***Eclipse***

  On Windows:
  > gradlew genSources eclipse
  
  On Linux:
  > chmod +x ./gradlew  
  >./gradlew genSources eclipse

  Start a new workspace in eclipse.
  Click File > Import... > Gradle > Gradle Project.
  Select the Main folder.
  
***IntelliJ***

  On Windows:
  > gradlew genIdeaWorkspace
  
  On Linux:
  > chmod +x ./gradlew  
  >./gradlew genIdeaWorkspace

  In idea click File > Open.
  Select build.gradle in the main folder.
  Select Open as Project.

***Other IDE's***

  Use [this link](https://fabricmc.net/wiki/tutorial:setup) for more information.
  It should be pretty similar to the eclipse and idea setup.
  
  
## Recommended Mods

Here are some fabric mods that will make your life better

### [Multiconnect](https://github.com/Earthcomputer/multiconnect) or [ViaFabric](https://github.com/ViaVersion/ViaFabric)
Mods that allows you to connect to any 1.8-1.18 server from a 1.18 (or above) client.

### [Baritone](https://github.com/cabaletta/baritone)
Baritone is a Minecraft AI that allows you to automate tasks such as walking, mining or building.

### [Sodium](https://www.curseforge.com/minecraft/mc-mods/sodium), [Lithium](https://www.curseforge.com/minecraft/mc-mods/lithium) and [Phosphor](https://www.curseforge.com/minecraft/mc-mods/phosphor)
These mods fix a lot of weird shit produced by Mojang and make your performance better.

## License

The BleachHack [license terms](https://github.com/BleachDev/BleachHack/blob/master/LICENSE).
