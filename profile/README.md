<p align="center">
  <img src="/assets/tonalflex-logo.png" alt="Logotype" width="450"/>
</p>

---

**TonalFlex** is an open-source platform for running professional audio plugins on embedded hardware — portable, flexible, and fully remote-controllable.

Powered by [Elk Audio OS](https://github.com/elk-audio), TonalFlex transforms devices like the Raspberry Pi 4 into low-latency, headless DSP units capable of running multi-channel chains of VST3 plugins.

TonalFlex is a complete bundle of applications and plugins that transform your embedded hardware into a fully featured **Pro Audio System**.

Remote control everything wirelessly from your phone, tablet, or computer - or via **MIDI** over Bluetooth or USB.

---

## Key Features

- 🎛 **One Plugin Codebase**  
  Write your audio plugins using JUCE and run them anywhere — cross-compile for embedded Linux, or build desktop formats like VST3, AU, AAX, and LV2 for macOS, Windows, and Linux.

- 📱 **Unified UI**  
  Design your plugin interfaces using modern web tools _(e.g. TypeScript, Vue, Vite)_. UIs run directly in desktop builds via JUCE WebView, and can also be packaged as `npm` micro frontends for use in the browser-based TonalFlex remote control UI — the same GUI code runs everywhere!

- 🕹️ **Remote Control**  
  Control your rig over Wi-Fi or Bluetooth — no screen required. MIDI controlling is supported over USB and Bluetooth.

- 🛠 **Fully Open Source**  
  Fork it. Hack it. Extend it. TonalFlex is built to be modified.

---

## 🚀 DIY - Getting Started

### 1. **Install ElkOS on RaspberryPi 4**

Follow the official [Elk Audio OS](https://github.com/elk-audio/elk-pi) instructions.

### 2. **Install TonalFlex Bundle**

Follow the [Tonalflex Bundle](https://github.com/tonalflex/tonalflex-bundle.git) instructions.

---

## 🧪 Develop Your Own Plugins

Tonalflex provide a custom JUCE template for writing your own compatible plugins — see the [tonalflex-plugin-template](https://github.com/tonalflex/tonalflex-plugin-template).

Once you have written your plugin, you will need to fork and add your plugins to the following repositores:

- [tonalflex-ui](https://github.com/tonalflex/tonalflex-ui)
- [tonalflex-bundle](https://github.com/tonalflex/tonalflex-bundle)

After that, you can pull your personal fork of the [tonalflex-bundle](https://github.com/tonalflex/tonalflex-bundle) to your embedded device running ElkOS in order to use your own plugins.

---
