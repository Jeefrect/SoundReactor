# Sound Reactor – Documentation  

Connect your audio device sounds to custom objects in the game.  

At the moment, the mod works with **Kino objects** that have either **blendshapes** (key shapes in blender) or **emission** enabled.  
If the object has one of these components, you can link audio values to the blendshape weights or the emission intensity.  

---

## How to use the mod  

### 1. Add a Kino object  
Add a Kino object to your car or scene as you normally do, for example a **subwoofer**.  

### 2. Open Sound Reactor in KSL  
Go to the Sound Reactor mod tab in **KSL**.  
You will see the list of Kino objects available.  

### 3. Component detection  
- If the object has **blendshapes**, they will be displayed in the list.  
- If the object has **emission enabled**, emission intensity will be available for binding.  

### 4. Binding audio  
For each parameter, you can choose which audio value will control it:  
- **Low** – 0–350 Hz (bass frequencies)  
- **Mid** – 350–1800 Hz (vocal range)  
- **High** – 1800 Hz and above (high-pitched sounds)  
- **Just Volume** – overall audio device volume, without frequency separation  

When the music is playing, the mod will adjust blendshape weights or emission intensity in real time.  

---

## Presets  
- The **Debug tab** contains the preset system.  
- Presets can be **created, loaded, switched, and deleted**.  
- Preset files are named like `SRPreset_1.json`, `SRPreset_2.json`, etc.  
- When you select a preset, it automatically loads all stored bindings.  
- Any change to audio bindings is automatically saved into the currently active preset.  

---

## Requirements  
- [KSL](https://github.com/trbflxr/ksl) must be installed.  
- It is recommended to restart the game after installing the mod from the ModDB tab.  
