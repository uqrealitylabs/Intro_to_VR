## Project Setup guide
************************************************************************************************************************

Hello Everyone! Welcome to the first workshop. As part of the workshop there are a few dependencies and software
installations that need to be completed. This setup guide is intended to guide you through it.

The following are the major dependencies for the project:
1. Unity Hub
2. Unity Editor version 2020.3.31f1
3. VR Builder asset

For testing your project with Oculus devices which will be the VR headset of our choice, the following pre-requisites
will be necessary:
1. Oculus device needs to be in Developer mode. Documentation on doing this can be found here:
https://developer.oculus.com/documentation/native/android/mobile-device-setup/
2. Oculus Link needs to be set up to debug and playtest your changes in the device. 

## Dependency installation
************************************************************************************************************************

### Unity Hub setup:
1. Go to the [Download Unity](https://unity.com/download) page on the Unity website.
2. Select Download Unity Hub.
3. Open the installer file.
4. Follow the instructions in the Unity Hub setup window.

### Unity Editor installation
1. In Unity Hub, click on Install Editor
![Step 1](./images/Unity%202020.3.31f1%20Installation/Step%201.png)
2. Go to Archive and click on "download archive"
![Step 2](./images/Unity%202020.3.31f1%20Installation/Step%202.png)
3. From the list shown go to 2020.X tab and install the 2020.3.31f1 version. Note: As long as it is 2020.3.X version,
it should be fine. The fix-pack versions aren't as crucial, but try to not keep it too faraway from version 31 of the fix-pack version.
![Step 3](./images/Unity%202020.3.31f1%20Installation/Step%203.png)
4. Check the Android and Windows Build Support options. Optionally, you can check the WebGL build support option if you
plan to create games that can be published to the Unity Asset Store or to the wider Unity Community.
![Step 4a](./images/Unity%202020.3.31f1%20Installation/Step4a.png)
![Step 4b](./images/Unity%202020.3.31f1%20Installation/Step4b.png)
5. Read through the license and agreements and proceed with the rest of the steps.

### VR Builder installation
1. Go to the [VR Builder](https://assetstore.unity.com/packages/tools/visual-scripting/vr-builder-open-source-toolkit-for-vr-creation-201913)
asset link. Click on "Add to my Assets" highlighted by the red circle. Make sure you are logged in or signed up to Unity,
either by clicking the button highlighted by the blue circle or on page redirection on pressing "Add to my Assets"
![Step1](./images/VR%20Builder%20Installation/Step%201.png)
2. Create a New project by clicking on the New Project button.
3. As part of this step make sure to select the correct editor version, the 3D template and the name that you prefer
(Note: Don't choose the VR template, it starts creating conflict issues with VR builder)
![Step2](./images/VR%20Builder%20Installation/Step%202.png)
4. Once the project opens, go to Windows > Package Manager to open the Unity Package Manager.
5. Make sure to change the listed packages to be "My Assets", select on VR Builder, click on Download and then Import.
Accept any prompts that come up and choose "Fix All" for any error correction prompts.
![Step3](./images/VR%20Builder%20Installation/Step%203.png)

That should complete installation, we will continue with the VR project setup in the workshop. See you there!