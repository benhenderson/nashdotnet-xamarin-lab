Nash.NET Xamarin Lab
====================

## Goals

* Xamarin primer
* Review development tools
* iOS and/or Android Hello World labs

## Xamarin Primer

Slides ...

## Review Development Tools

With luck, everyone has already installed Xamarin iOS and/or Xamarin Android. If not, grab them here: http://xamarin.com/download.

For Android development, you'll also need to create an Android emulator. Follow these steps to get a performant emulator:

**Install Android 4.2.2 (API 17)**

1. Xamarin Studio > Open AVD Manager
2. AVD Manager > Tools > Manager SDK
3. Under Android 4.2.2 (API 17) select:

- SDK Platform
- Intel x86 Atom System Image

**Install Intel HAXM**

- http://software.intel.com/en-us/articles/intel-hardware-accelerated-execution-manager
- May require BOIS tweak to enable virtualization

**Create a New Emulator**

1. Xamarin Studio > Open AVD Manager
2. Select New and enter the following options:

- AVD Name: JellyBean - 4.2.2
- Device: Galaxy Nexus (4.65", 720 x 1280: xhdpi)
- Target: Android 4.2.2 - API Level 17
- CPU: Intel Atom (x86)
- Keyboard: [x] Hardware keyboard present
- Skin: [ ] Display a skin with hardware controls
- Front Camera: Webcam0
- Back Camera: None
- Emulation Options: [ ] Snapshot [x] Use Host GPU

##Introduction Labs

iOS 
* Hello iOS - http://docs.xamarin.com/guides/ios/getting_started/hello,_world
* Multi-Screened Applications - http://docs.xamarin.com/guides/ios/getting_started/hello%2C_mvc

Android
* Hello Android - http://docs.xamarin.com/guides/android/getting_started/hello%2C_world
* Hello, Multiscreen Applications - http://docs.xamarin.com/guides/android/getting_started/hello%2C_multi-screen_applications


