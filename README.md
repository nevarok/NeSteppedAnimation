# NeSteppedAnimation: Stepped Animation Plugin for Unreal Engine

[Discord](https://discord.gg/VqTKJJHw) - Join the Nevarok community on Discord for discussions, support, and updates.

[Youtube](https://www.youtube.com/@nevarok) - Watch tutorials, demos, and updates on Nevarok's YouTube channel.

[Documentation](https://nevarok.com/ne-stepped-animation/index.html) - Access documentation for the NeSteppedAnimation plugin.

[Support](https://nevarok.com/ne-stepped-animation/contributing/index.html) - Find information on how to contribute and get support for the NeSteppedAnimation plugin.

## Introduction

**NeSteppedAnimation** is an Unreal Engine plugin. This plugin introduces stepped animation functionality, allowing animators to create discrete, non-interpolated keyframe transitions. The result is a stylized, choppy animation effect that enhances timing and pose clarity without smooth in-betweens. This can be particularly useful for creating unique visual styles or for applications where traditional smooth animations are not desired.

## Installation

To install the NeSteppedAnimation plugin, follow these steps:

1. **Purchase the Plugin:**
    - Visit the Unreal Engine Marketplace and search for "NeSteppedAnimation."
    - Purchase the plugin from the Marketplace.

2. **Install through Epic Games Launcher:**
    - Open the Epic Games Launcher.
    - Navigate to the Unreal Engine section and go to your Library.
    - Find the NeSteppedAnimation plugin in your Vault and click on 'Install to Engine.'
    - Select the version of Unreal Engine you are using and click "Install."

3. **Enable the Plugin:**
    - Open your project in Unreal Engine.
    - Go to `Edit` > `Plugins`.
    - In the Plugins window, search for "NeSteppedAnimation."
    - Check the box to enable the NeSteppedAnimation plugin.
    - Restart Unreal Engine to apply the changes.

## Usage

Once the plugin is installed and enabled, you can start using it in your animation blueprints.

### Creating a Stepped Animation Node

1. **Open an Animation Blueprint:**
    - Navigate to the Content Browser and open an existing Animation Blueprint or create a new one.

2. **Add the Stepped Animation Node:**
    - In the Animation Graph, right-click to open the context menu.
    - Search for `NeSteppedAnimation` and select `NeSteppedAnimation Node`.
    - Connect the `NeSteppedAnimation Node` to your animation network as desired.

### Configuring the Node

The `NeSteppedAnimation` node has several configurable properties:

- **Frames Per Second (FPS):**
    - Determines the number of frames per second for the stepped animation.
    - Lower values result in a choppier animation with more noticeable steps.

- **Delta Time Multiplier:**
    - A multiplier is applied to the delta time, allowing you to speed up or slow down the step frequency.

- **Step Root Location:**
    - If enabled, the root location will be stepped.

- **Step Root Rotation:**
    - If enabled, the root rotation will be stepped.

### Example Setup

1. **Basic Setup:**
    - Add a `NeSteppedAnimation` node in your animation blueprint.
    - Connect the node to the desired animation pose.

2. **Configure Properties:**
    - Set the `Frames Per Second` to achieve the desired stepping effect.
    - Adjust the `Delta Time Multiplier` to control the animation speed.
    - Enable or disable `Step Root Location` and `Step Root Rotation` based on your needs.

## Support

For support, please visit the [support page](ne-stepped-animation/contributing/index,md).

---
