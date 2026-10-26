# YakType for macOS

YakType is a native macOS dictation app for turning speech into text in your
current workflow. Start a workflow with its keyboard shortcut, record from a
microphone or system audio, and let the configured speech and text-processing
providers prepare the result. Completed live dictation can be inserted into the
focused app; tasks and transcripts are also available in History.

This repository hosts the direct-download macOS releases and the Sparkle update
feed. It contains release metadata, not the application source code.

## Requirements

- macOS 26 or later for the current stable release.
- Microphone permission when recording from a microphone.
- Screen Recording permission when using system audio.
- Accessibility permission for inserting text into another app.
- Speech Recognition permission when using Apple's System Speech provider.

YakType may also need network access and provider credentials for the services
configured in a workflow.

## Install

1. Download the latest `YakType-*.dmg` from [GitHub Releases](https://github.com/yaktypeinput-bit/yaktypeinput-macos/releases).
2. Open the DMG and drag YakType to Applications.
3. Launch YakType and follow the setup steps to grant the permissions needed by
   your audio source and workflow.

## Updates

YakType checks the stable update feed at:

`https://raw.githubusercontent.com/yaktypeinput-bit/yaktypeinput-macos/main/appcast.xml`

The feed points to signed release assets hosted on GitHub. Release notes are
shown with each update and on the corresponding GitHub Release page.
