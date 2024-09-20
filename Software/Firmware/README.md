# Firmware

```
The macropad is actually a custom keyboard, using KMK firmware
```

- Firmware: [KMK](https://github.com/KMKfw/kmk_firmware)
- KMK GUI: [POG](https://github.com/JanLunge/pog)

I've oped for KMK because it's much simpler to run the experiments, you can edit the layout on the fly and test different key combinations, which helped me during the development

Now that I'm done making modifications, I'll probably switch to a firmware that doesn't use CircuitPython for more stability. CircuitPython mounts a local drive (which is why it's easy to update), but that's prone to corruption and is not as fast as other firmwares like QMK.

There's a backup of my firmware in this folder... but setting it up from scratch is very easy, just follow POG's tutorials.

![POG](https://github.com/JanLunge/pog/blob/main/demo/pog-screenshot.png?raw=true)