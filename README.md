  # Transferre
Native macOS MTP file transfer app built for VoiceOver accessibility.

# Transferre

A native macOS app for transferring files between your Mac and Android devices over MTP, built with accessibility at its core.

## What It Does

Transferre gives Mac users a straightforward way to browse and transfer files to and from Android phones and other MTP devices, including the HIMS SensePlayer. It is designed from the ground up to work properly with VoiceOver, so blind and low vision users can manage their device files without fighting an inaccessible interface.

## Why It Exists

Android file transfer on macOS has always been an afterthought. Google's official app is abandoned, most alternatives are Electron-based with poor accessibility, and the options that do work with VoiceOver tend to cost money just to transfer files in both directions. For SensePlayer users and others who rely on MTP to load content onto their devices, this is a real problem.

Transferre is a free, lightweight, native SwiftUI app that treats accessibility as a first-class requirement, not a feature to add later. It was built by a blind developer who got tired of the workarounds.

## Features

- Browse your Mac and Android device side by side
- Transfer files between Mac and device using familiar keyboard shortcuts
- Full VoiceOver support with meaningful labels and logical navigation order
- Works with the HIMS SensePlayer, Android phones, and other MTP devices
- No third-party dependencies required — everything is bundled
- Universal binary supporting both Apple Silicon and Intel Macs
- Free, forever

## Requirements

- macOS 15 or later
- An Android or MTP device connected via USB with MTP or file transfer mode enabled

## Installation

Download the latest release from the Releases page, open the DMG, and drag Transferre to your Applications folder. No additional software or package managers required.

## Usage

Connect your device via USB. For Android phones, select File Transfer or MTP mode on the device when prompted. Launch Transferre and your device will appear automatically. Use the left panel to navigate your Mac and the right panel to navigate your device. Press Command C to copy, Command V to paste to the destination, and Option V to move.

## Distribution

Transferre is signed and notarized for direct distribution outside the Mac App Store.

## License

MIT

## Author

Izzie G
