# ARfps

## Building
*Below are the instructions on how to build the project.*

### Required software
In order to build the project yourself, you need to have [Unity](https://unity3d.com/) installed.

### Downloading the source files
Download the latest released source files from [here](https://github.com/joemama2021/ARfps).

Alternatively, download the source using git:
```
git clone https://github.com/joemama2021/ARfps.git <directory> 
```

### Compiling into APK
Decompress the files if downloaded the ZIP or tarball version.

Create a folder named "apk" in the root of the project.
Open the project folder in Unity:
* go to `File` –> `Build Settings...`
* if the selected platform is not Android, select it and hit the `Switch Platform` button
* set build system to `Gradle`
	
* to build a **release build**:
  * go to `File` –> `Build Settings...`
  * (recommended) set compression method to `LZ4HC`
	
* hit `Build`
* choose a name for the APK file and save it inside the `apk` folder

Now the APK file can be transferred to an android device and install it.

Alternatively, instead of `Build`, connect an Android device with a USB cable to the computer, go to *Developer Options*
in your phone settings, enable *USB Debugging* and set *USB Configuration* to `MTP`. In the *Build Settings* window, set
*Run Device* to your device and hit `Build and Run`. This will do the same as `Build` in addition to installing the
game to the selected device.

*Note: If the device can not be detected by Unity, try restarting Unity while the device is already
physically connected to the computer.*

## How to play
To start playing hit the *Play* button in the main menu. Enemies will begin appearing in the space around you. Move
the phone around to find them, line them up with the aim dot and tap the screen to shoot them. For every enemy killed,
you get points. Destroying the capsules floating around you, gives you more bullets. Defeat all enemies to advance to the
next level. The game is over when player runs out of bullets or health.
