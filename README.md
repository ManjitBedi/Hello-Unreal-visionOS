I am using this project as hack space to try out using the Unreal Engine with visionOS.

The project is built with Unreal Engine 5.5 from Github (the main branch) and not the Epic Launcher. 

Some notes:

- add the Open XR visionOS plug-in
- check platform has visionOS
- add plist entitlements
- add team ID for Xcode
- create C++ class
- Disable MobileMultiview and InstancedStereo

  This explained in more detail here: [Unreal Engine & visionOS guide](https://dev.epicgames.com/community/learning/tutorials/1JWr/unreal-engine-apple-vision-pro-quick-start-guide)
