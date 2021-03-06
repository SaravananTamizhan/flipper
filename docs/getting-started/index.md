---
id: index
title: Desktop App
---

Flipper helps you debug Android and iOS apps running in an emulator/simulator or connected physical development devices. Flipper consists of two parts:

- The desktop app
- The native mobile SDKs for Android and iOS

To use Flipper, you need to add the mobile SDK to your app. If you are using React Native 0.62 or higher, this is largely done automatically for you.

---

The desktop part of Flipper doesn't need any particular setup. Simply download the latest build for [Mac](https://www.facebook.com/fbflipper/public/mac), [Linux](https://www.facebook.com/fbflipper/public/linux) or [Windows](https://www.facebook.com/fbflipper/public/windows) and launch it. In order to work properly, Flipper requires a working installation of the Android and (if where applicable) iOS development tools on your system, as well as the [OpenSSL](https://www.openssl.org) binary on your `$PATH`.

Once you start Flipper and launch an emulator/simulator or connect a device, you will already be able to see the device logs in Flipper. To see app specific data, you need to integrate our native SDKs with your app.

![Logs plugin](/docs/assets/initial.png)