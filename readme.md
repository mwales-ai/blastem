# BlastEm

## Build instructions (for Ubuntu)

```
sudo apt-get install -y libsdl2-dev libglew-dev libgtk-3-dev pkg-config
make
```

# What's new to this fork

This fork has improvements for debugging and tooling to help facilitate
ROM hacking.

## Sprite Identification

The blastem VDP plane debugger now shows individual planes and highlights
where the sprites are located on the screen.  Clicking a sprite on the screen
will reveal the details of the sprite such as VRAM location, sprite size, and
where it's memory was DMA transferred from (if in DMA transfer history ring
buffer).

