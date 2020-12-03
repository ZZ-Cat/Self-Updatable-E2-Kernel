# Self Updatable E2

![DRM Free](https://static.fsf.org/dbd/label/DRM-free%20label%20120.en.png)

[Keep it that way](https://www.defectivebydesign.org/what_is_drm_digital_restrictions_management)



### Written & Developed by:
[Cassandra "ZZ Cat" Robinson](https://bit.ly/ZZCatOnFacebook)
[![](https://sourcerer.io/fame/ZZ-Cat/ZZ-Cat/Self-Updatable-E2-Kernel/images/0)](https://sourcerer.io/fame/ZZ-Cat/ZZ-Cat/Self-Updatable-E2-Kernel/links/0)[![](https://sourcerer.io/fame/ZZ-Cat/ZZ-Cat/Self-Updatable-E2-Kernel/images/1)](https://sourcerer.io/fame/ZZ-Cat/ZZ-Cat/Self-Updatable-E2-Kernel/links/1)[![](https://sourcerer.io/fame/ZZ-Cat/ZZ-Cat/Self-Updatable-E2-Kernel/images/2)](https://sourcerer.io/fame/ZZ-Cat/ZZ-Cat/Self-Updatable-E2-Kernel/links/2)[![](https://sourcerer.io/fame/ZZ-Cat/ZZ-Cat/Self-Updatable-E2-Kernel/images/3)](https://sourcerer.io/fame/ZZ-Cat/ZZ-Cat/Self-Updatable-E2-Kernel/links/3)[![](https://sourcerer.io/fame/ZZ-Cat/ZZ-Cat/Self-Updatable-E2-Kernel/images/4)](https://sourcerer.io/fame/ZZ-Cat/ZZ-Cat/Self-Updatable-E2-Kernel/links/4)[![](https://sourcerer.io/fame/ZZ-Cat/ZZ-Cat/Self-Updatable-E2-Kernel/images/5)](https://sourcerer.io/fame/ZZ-Cat/ZZ-Cat/Self-Updatable-E2-Kernel/links/5)[![](https://sourcerer.io/fame/ZZ-Cat/ZZ-Cat/Self-Updatable-E2-Kernel/images/6)](https://sourcerer.io/fame/ZZ-Cat/ZZ-Cat/Self-Updatable-E2-Kernel/links/6)[![](https://sourcerer.io/fame/ZZ-Cat/ZZ-Cat/Self-Updatable-E2-Kernel/images/7)](https://sourcerer.io/fame/ZZ-Cat/ZZ-Cat/Self-Updatable-E2-Kernel/links/7)



## Description:
 A self updating Expression 2 script for Garrys Mod.

 As the name suggests, this Expression 2 script (known simply as an "E2") automatically updates a linked user-created script (known as the "User App").

 How this works is, the E2 contacts a GitHub server for the latest versions of both the E2 & the User App.
 When a new version of the User App is released, the E2 automatically downloads the new script from a separate GitHub server & saves it to a local directory.
 Once the updating process is completed, the E2 can be safely reloaded.

 This project has come about because a lot of people are moving their E2 projects over to GitHub, & as they do that, a lot of their E2s usually spams the chat with update notifications ranging from "Current version is up to date" to "a new version is available, go to this link" & everything in between.
 If you have a dupe that has a lot of E2s on it, such as a standard RLC 2.0 locomotive, you will know what I mean by this.
 Another reason for this project is, I find it tedious to manually update every E2 in my saved files, whenever a new update for one or more E2s are released.

 A lot of that tedium can be eliminated, by automating & streamlining the update process. Simply zap your E2 with the Tool Gun & you're away laughing.

 **A word of advice about the E2 itself:** Due to the nature of Expression 2, there is currently no way to automate the installation & update processes of this E2.
 The Self-Updatable E2 is designed to automatically update the User App. Not the E2 itself.
 You __will__ be required to manually install this E2 & keep it updated, whenever new updates are released.

## Errata:
 For a list of known bugs & temporary workarounds, view the [errata](https://github.com/ZZ-Cat/Self-Updatable-E2-Kernel/blob/Seed/ERRATA.md) for details.

## Requirements:
 * An active internet connection.
   - This is only required to setup a valid Steam account; downloading-&-installing of Garrys Mod, Garrys Mod Addons; & automatic updates from this E2's GitHub servers. However, it is not essential to run Garrys Mod. This E2 can run without an internet connection, as it is entirely free from DRM.
 * [A valid Steam account](https://store.steampowered.com/about/)
 * [Garrys Mod](https://store.steampowered.com/app/4000/Garrys_Mod/)
 * [Wiremod](https://steamcommunity.com/sharedfiles/filedetails/?id=160250458)
 * [Advanced Duplicator 2](https://steamcommunity.com/sharedfiles/filedetails/?id=773402917)

## How to obtain & install:
 1. Download this repository, by clicking "Download Zip" under "Clone or Download", & save the zip file in an accessible directory.
 2. Extract everything from the zip file.
 3. **Backup your files before expediting this step.** Copy the 'expression2' folder to this directory -> 'steamapps/common/GarrysMod/garrysmod/data', & overwrite the existing folder(s) & file(s) with the same name(s).
 4. Fire up Garrys Mod & start a new sandbox session.
 5. In your Expression 2 Editor, click the "Update" button & everything should be there.
    - The kernel will be located in the "Self-Updatable Kernel" folder, inside Expression 2's main directory. It is called 'main.txt'.
    - The User App will be located in the "mySelfUpdatableE2" folder, inside Expression 2's "e2shared" folder. This is also called 'main.txt'. Remember, **this is the file that gets automatically updated.**

## Quick Start Guide:
Before you go gung ho, with spawning E2s all willy-nilly, **read & follow these instructions accordingly.**
 1. Open up Garrys Mod's Expression 2 Editor & navigate to the 'main.txt' file, that's located within the 'mySelfUpdatableE2' folder, in your 'e2shared' folder.
 2. For a quick "proof of concept" demonstration, highlight the version numbers on line 31 & roll the current version backward by a number of your choosing.
 3. Comment out the "Hello World" chat print function on line 36.
 3. Hit 'Ctrl + S' to save the file. Close the file, once you have done this.
 4. Navigate to the 'main.txt' file in the 'Self-Updatable Kernel' folder, located in the main 'expression2' directory, & open it.
 5. Close the editor & spawn the 'Self-Updatable Kernel' in a location of your choosing in-game.
 6. Observe the automatic update notifications, as they pop up; alerting you when the automatic update is complete.
 7. Observe the "Hello, world." message in the in-game chat, when it pops up. This means the User App has been updated.
 8. At your option, you can verify the updated code by simply reopening the 'main.txt' file, located in the 'mySelfUpdatableE2' folder, in your 'e2shared' folder.
    - Note how the semantic version numbers & the "Hello, world." chat print function has been updated & uncommented, respectively.
 9. That's it. Fanito!

## Duplicating this E2 using Advanced Duplicator 2:
 This E2 & the User App are designed to be 100% compatible with the Advanced Duplicator 2 tool. You can safely duplicate this E2 in the same way you would with any other model or contraption.
 Better yet, if you have this E2 saved as a dupe, you don't need to update the dupe at all. Simply spawn the dupe like normal, & this E2 will automatically update itself with any changes that are made to it (this also includes any updates to the User App).

## Contributing to this Software:
I welcome your contributions & ideas for this E2. If you are a developer & would like to contribute to this software's development, consider submitting a pull request. Bare with me, as I am not always around the internet to respond to everyone's requests straight away.

## Software License:
![GNU Affero GPL v3](https://www.gnu.org/graphics/agplv3-with-text-162x68.png)

Self Updatable E2. Copyright © 2020, Cassandra "ZZ Cat" Robinson.
