# UE4 Cardboard VR demo project

This project is a public demo of the plugin "*[UE4 Cardboard VR](https://unrealengine.com/marketplace/cardboard-vr)*" for Unreal Engine 4.
Specifically, this is a porting to Unreal Engine 4 of the official new Google Cardboard SDK [native mobile demo](https://github.com/googlevr/cardboard), for iOS and Android.

*MARKETPLACE: <https://unrealengine.com/marketplace/cardboard-vr>*

**ATTENTION: a copy of the plugin is required to use this project.**

[UE4 Cardboard VR](https://unrealengine.com/marketplace/cardboard-vr) is an Unreal Engine 4 plugin to support [Google Cardboard VR headsets](https://arvr.google.com/cardboard/) on iOS and Android mobile platforms, integrating the new official Google Cardboard SDK.

*NOTE: this product is not made by, or affiliated with, Google Inc in any way.*

[![Integration of the official Google Cardboard SDK for iOS and Android](https://cdn1.epicgames.com/ue/product/Screenshot/1officialSDKhouse-1920x1080-6b177cb1a1c209ce2621d1ba3c9df7f4.png?resize=1&w=300)](https://unrealengine.com/marketplace/cardboard-vr)
[![Enable the plugin and your app is ready to run on Google Cardboard viewers](https://cdn1.epicgames.com/ue/product/Screenshot/screenshot-02-1920x1080-a68211c3d56b6571a35bc5776f78660a.png?resize=1&w=300)](https://unrealengine.com/marketplace/cardboard-vr)
[![Ready-to-use customizable native UI overlay to toggle and configure the stereo mode](https://cdn1.epicgames.com/ue/product/Screenshot/screenshot-03-1920x1080-aebc5bf737219b772aec8fa801986e8e.png?resize=1&w=300)](https://unrealengine.com/marketplace/cardboard-vr)

## Links

Marketplace: <https://unrealengine.com/marketplace/cardboard-vr>

Documentation: <https://www.unamedia.com/ue4-cardboard/api/>

Support thread: <https://forums.unrealengine.com/unreal-engine/marketplace/1849407-cardboard-vr-google-cardboard-vr-headsets-on-ios-and-android-integrating-the-official-google-sdk>

## UE4 Cardboard VR - plugin

[UE4 Cardboard VR](https://unrealengine.com/marketplace/cardboard-vr) is an Unreal Engine 4 plugin to run UE4 mobile VR projects on iOS and Android devices using [Google Cardboard](https://arvr.google.com/cardboard/) viewers. The plugin integrates the new official [Google Cardboard SDK](https://github.com/googlevr/cardboard).

Simply enabling the plugin is enough to start building and running your mobile VR experience on any Google Cardboard supported mobile device and viewer.

For a complete setup, more advanced options and important technical notes, please read the [documentation](https://www.unamedia.com/ue4-cardboard/api/).

### Features

- head tracking;
- stereoscopic rendering;
- user interaction via the viewer button;
- native, customizable, UI overlay to allow the user to:
  - enable/disable the stereoscopic mode;
  - scan the QR code to automatically configure the parameters of its Google Cardboard viewer.
- all the features are available from both Blueprints and C++.

## Demo project

This demo project is a porting to Unreal Engine 4 of the official new Google Cardboard SDK [native mobile demo](https://github.com/googlevr/cardboard), for iOS and Android.

Thanks to the automatic *native overlay* feature provided out-of-the-box by the *UE4 Cardboard VR* plugin, the UE4 app can works both in stereo mode and in non-stereo mode, without requiring any change to the project code.

Screenshot from the official Google Cardboard SDK demo app:

![The official Google demo app](docs/cb-google-600.png)

Screenshots of the ported Unreal Engine 4 version, based on the *UE4 Cardboard VR* plugin:

![The UE4 version of the demo](docs/cb-ue4-600.png)

![The UE4 demo running in non-stereo mode](docs/cb-ue4-nostereo-600.png)
