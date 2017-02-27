```
Disclaimer: 

This is a very early-stage script which is still very project-specific.
Use at your own risks and MODIFY it to your needs.
```

# After Effects Timeline exporter

The script is an Adobe After Effects plugin exporting a simple animation timeline
to GreenSock TimelineMax Javascript format.

# Installation

1. Copy the `.jsx` file in the Plugins folder  
   [How to install AE plugins](https://helpx.adobe.com/after-effects/using/plug-ins.html)
2. Start or re-start AE
3. Check _Timeline Exporter_ is listed in _File > Scripts_

# Usage

1. Create a new AE composition
2. Animate image elements with keyframes
3. Select the layers you want to export from bottom to top (selection order is important)
4. Run the plugin _(File > Scripts > TimelineMax Exporter.jsx)_
5. Pick a scene name and validate
6. Pick a JS file name when prompted (add extension)

## Supported features

- Position, rotation and scale animation
- Parent layer (1 level only)

# Compatibility table

| AE version | status |
| ---------- | ------ |
| CS6        | ?      |
| CC-2014    |        |
| CC         | ?      |

