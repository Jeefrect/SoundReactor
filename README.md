# SoundReactor

**SoundReactor** is a CarX mod that connects your system audio to objects in the game.  
Visualize music and sounds through keyshapes, emission, lights, and object rotation.

![Preview](https://raw.githubusercontent.com/Jeefrect/SoundReactor/refs/heads/main/docs/img/BrowserPreview_tmp.gif)

## Features

- Capture system audio (loopback) directly in-game.
- Bind **Low / Mid / High frequencies** or overall **Volume** to supported object parameters.
- Support for **keyshapes (blendshapes), emission, light intensity, and Transform rotation**.
- Configure rotation independently for the **X, Y, and Z axes**.
- Adjust individual Transform multipliers and interpolation for each axis.
- Apply global Transform interpolation to all active rotation bindings.
- Work with Kino objects from both cars and scenes.
- Select supported map objects directly in the scene with a visual hover indicator.
- Save bindings and selected scene objects in presets.
- View an optimized real-time audio waveform while capture is active.
- Organized object and component menus with active-binding indicators.
- Language switching (**EN/RU/JP**).
- Debug panel with real-time volume and frequency values.

## Requirements

- **CarX Drift Racing Online** (moddable version).
- **KSL Loader** (ZML is not supported).

## How to use

More detailed usage documentation is available [**here**](https://github.com/Jeefrect/SoundReactor/blob/main/docs/Documentation.md).

1. Add Kino objects to your car or scene, or use the scene selection mode to select a supported map object.
2. Enable audio capture in the SoundReactor UI.
3. Open one of the object lists:
   - **Car Kino objects**
   - **Scene Kino objects**
   - **Selected scene objects**
4. Open an object and choose a supported component:
   - **Keyshapes**
   - **Emission**
   - **Lights**
   - **Transform**
5. Assign an audio source to the parameter:
   - **Lows** — bass frequencies from 0 to 350 Hz.
   - **Mids** — frequencies from 350 to 1800 Hz.
   - **Highs** — frequencies above 1800 Hz.
   - **Volume** — overall loudness.
6. For Transform rotation, configure the X, Y, and Z axes independently and adjust their multiplier and interpolation strength.
7. Save your setup in a preset. Selected scene objects and their bindings will be restored when the preset and scene are loaded again.

Clicking an already selected audio source again removes that binding.

Instructions for creating Kino objects are available [**here**](https://github.com/Jeefrect/SoundReactor/blob/main/docs/how-to-make.md). It is easy!

## Installation

1. Download the latest release of **SoundReactor**.
2. Extract the `SoundReactor` folder into your CarX KSL mods folder.
3. Restart the game.

## Community

- Join the [Discord server](https://discord.gg/M7kFncsZCy) for support, feedback, test objects, and updates.
- Report bugs and suggest features through GitHub Issues.

## Examples

- Make headlights flash on bass beats.
- Animate neon emission with treble spikes.
- Deform body panels in sync with overall volume.
- Create sound-responsive subwoofers.
- Rotate scene decorations or Kino objects to the rhythm of music.
- Smooth sound-reactive movement with individual and global interpolation.
