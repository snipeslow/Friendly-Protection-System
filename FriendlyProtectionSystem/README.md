# Instructions
***This is built for FX Layers using Write Defaults On. There are no instructions for avatars that use Write Defaults Off.***

***Failure to follow steps will lead to unintended effects.***

***Avatar Dynamics must be enabled on both parties to work***

- *Step 1,* drag prefab into the root of your avatar. Do not put it in any other bones or objects other than the GameObject that has your Avatar Descriptor. It should be "Avatar/FriendlyProtectionSystem"

- *Step 1.1,* Assign the left and right hand bones to the contact receivers and contact senders

- *Step 2,* Copy the FX Layers EXACTLY as they are in the example to your FX Layer. Failure to do so will mark everyone as friendly, therefore preventing you from hurting you. Do not check or uncheck anything.

- *Step 3,* Copy the parameter from the example parameter file. This is to allow you have the parameter for the next step.

- *Step 3.1,* Copy the menu toggle from the example menu file. This is to allow you to toggle and reset the Friendly Protection System.

- *Step 4,* Make an animation clip that switches out your particles for versions that disable "Send Collision Messages"

- *Step 4.1,* Add a visual indicator for others to see that you're friendly to that animation clip too.

- *Step 4.2,* Replace "FriendlyProtectionSystem_Enabled" in the "FriendlyProtectionSystem_Core" layer with your animation clip.

- Toggle on the protection system to disable friendly fire on fist bump, Toggle off to reset it for everyone. If your avatar is reloaded for any reason, it will be toggled off.

**\- From, Snipeslow/SirMasters**