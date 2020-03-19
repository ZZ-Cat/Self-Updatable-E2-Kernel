# Self Updatable E2 Kernel
![GNU Affero GPL v3](https://www.gnu.org/graphics/agplv3-with-text-162x68.png)


![DRM Free](https://static.fsf.org/dbd/label/DRM-free%20label%20120.en.png)


### Written & Developed by:
[![](https://sourcerer.io/fame/ZZ-Cat/ZZ-Cat/Self-Updatable-E2-Kernel/images/0)](https://sourcerer.io/fame/ZZ-Cat/ZZ-Cat/Self-Updatable-E2-Kernel/links/0)[![](https://sourcerer.io/fame/ZZ-Cat/ZZ-Cat/Self-Updatable-E2-Kernel/images/1)](https://sourcerer.io/fame/ZZ-Cat/ZZ-Cat/Self-Updatable-E2-Kernel/links/1)[![](https://sourcerer.io/fame/ZZ-Cat/ZZ-Cat/Self-Updatable-E2-Kernel/images/2)](https://sourcerer.io/fame/ZZ-Cat/ZZ-Cat/Self-Updatable-E2-Kernel/links/2)[![](https://sourcerer.io/fame/ZZ-Cat/ZZ-Cat/Self-Updatable-E2-Kernel/images/3)](https://sourcerer.io/fame/ZZ-Cat/ZZ-Cat/Self-Updatable-E2-Kernel/links/3)[![](https://sourcerer.io/fame/ZZ-Cat/ZZ-Cat/Self-Updatable-E2-Kernel/images/4)](https://sourcerer.io/fame/ZZ-Cat/ZZ-Cat/Self-Updatable-E2-Kernel/links/4)[![](https://sourcerer.io/fame/ZZ-Cat/ZZ-Cat/Self-Updatable-E2-Kernel/images/5)](https://sourcerer.io/fame/ZZ-Cat/ZZ-Cat/Self-Updatable-E2-Kernel/links/5)[![](https://sourcerer.io/fame/ZZ-Cat/ZZ-Cat/Self-Updatable-E2-Kernel/images/6)](https://sourcerer.io/fame/ZZ-Cat/ZZ-Cat/Self-Updatable-E2-Kernel/links/6)[![](https://sourcerer.io/fame/ZZ-Cat/ZZ-Cat/Self-Updatable-E2-Kernel/images/7)](https://sourcerer.io/fame/ZZ-Cat/ZZ-Cat/Self-Updatable-E2-Kernel/links/7)


## Description:
 A self updating Expression 2 script for Garrys Mod.

 Currently, it's janky & incomplete. Starting with version 0.1.0-a0.1.0; this kernel will be tested, debugged & updated as time marches on.
 The idea with this script is, as the name suggests, it will self update a script that is linked to it.
 How this happens is by way of contacting my GitHub server for the latest version of the linked Expression 2 Script (henceforth abbreviated to "E2"),
 downloading the new code, updating the locally saved file(s) & resetting the E2. Thus, running the new code.
 The kernel uses Expresison 2's "autoupdate" feature to aid in automatically updating the E2 whenever it is spawned in-game.

 This project has come about because a lot of people are moving their E2 projects over to GitHub, & as they do that, a lot of their stuff spams the chat
 with update notifications ranging from "Current version is up to date" to "a new version is available" & everything in between.
 If you have a dupe that has a lot of E2s on it, such as a standard RLC 2.0 locomotive, you will know what I mean by this.
 Another reason for this project is, I find it tedious to manually update literally every E2 in my dupes, whenever a new update for one or more E2s are
 released.

 So, the idea is to simplify & streamline the update process, all the while having minimal impact on the running of the E2.

 With all of that being said & done (& given the nature of Expression 2), currently there is no way to automatically update the kernel itself.
 As new updates to the kernel are released, you will be required to manually update your E2s accordingly until further notice.
 This is not the case with an E2 that is linked to this kernel. The kernel will automatically update that E2 as new updates to that E2 are released.

 For a list of known bugs, temporary workarounds & what's being done to quash those bugs, view the [errata](https://github.com/ZZ-Cat/Self-Updatable-E2-Kernel/blob/Seed/ERRATA.md) for details.

## Requirements:
 * [Garrys Mod](https://bit.ly/33r6TAI)
 * [Wiremod](https://bit.ly/2TZ43A0)

## How to obtain & install:
 1. Download this repository, by clicking "Download Zip" under "Clone or Download", & save the zip file in an accessible directory.
 2. Extract everything from the zip file.
 3. **Backup your files before expediting this step.** Copy the 'expression2' folder to this directory -> 'steamapps/common/GarrysMod/garrysmod/data', & overwrite the existing folder(s) & file(s) with the same name(s).
 4. In your Expression 2 Editor, click the "Update" button & everything should be there.
    - The kernel will be located in the "Self-Updatable Kernel" folder, inside Expression 2's main directory.
    - The self-updating project file will be located in the "mySelfUpdatableE2" folder, inside Expression 2's "e2shared" folder. Remember, **this is the file that gets automatically updated.**

## Quick Start Guide:
Before you go gung ho, with spawning E2s all willy-nilly, **read & follow these instructions accordingly.**
 1. Open up Garrys Mod's Expression 2 Editor & navigate to the 'main.txt' file, that's located within the 'mySelfUpdatableE2' folder, in your 'e2shared' folder.
 2. For a quick "proof of concept" demonstration, highlight the version numbers on line 8 & roll the current version backward by a number of your choosing.
 3. Comment out the "Hello World" chat print function on line 13.
 3. Hit 'Ctrl + S' to save the file. Close the file, once you have done this.
 4. Navigate to the 'main.txt' file in the 'Self-Updatable Kernel' folder, located in the main 'expression2' directory, & open it.
 5. Close the editor & spawn the 'Self-Updatable Kernel' in a location of your choosing in-game.
 6. Observe the automatic update notifications, as they pop up; alerting you when an automatic update is in progress.
 7. Observe the "Hello, world." message in the in-game chat, when it pops up. This means that the update process has completed & the E2 has been reset. Thus, running the updated User App.
 8. At your option, you can verify the updated code by simply reopening the 'main.txt' file, located in the 'mySelfUpdatableE2' folder, in your 'e2shared' folder.
    - Note how the semantic version numbers & the "Hello, world." chat print function has been updated & uncommented, respectively.
 9. That's it. Fanito!

## How to use the kernel with your project:
 [COMING SOON]

## Contributing to this Software:
This software is free software; & I welcome your contributions & ideas for this Expression 2 kernel. If you are a developer & would like to contribute to this software's development, consider forking this software, adding in your work & submitting a pull request. Just bare with me, as I am not always around the internet to respond to everyone's requests straight away.
