# TVs Bezels for 1:1 screen based on Soqueroeu TV Backgrounds

I recommend to use pixel-art-scaling/pixel_aa.glslp shader to avoid uneven pixels (You need to use the Online updater inside Retroarch if you dont have the shader. Main menu>Online updater>Update GLSL Shaders).

# Preview

![preview](https://github.com/user-attachments/assets/1f3a08dd-739b-48fb-ae8d-6c3ce9cea149)


# General Instructions (Applying overlays)

Open 'Quick Menu' on Retroarch (Select + X buttons) > On-Screen Overlay > Overlay Preset > Choose the .cfg file for the system in use. 

Set Overlay Opacity to 1.0

# Aligning overlays for 4:3 systems (Dreamcast, Master System, Sega CD, Sega32x, Sega Genesis, SG-1000, Play Station, N64, Neo Geo).
 
Settings ->

  - Video ->
    
    - Scaling ->
      
      * Integer Scale: OFF
      * Aspect Ratio: Custom
      * X Position: 0
      * Y Position: 50
      * Width: 720
      * Height: 540

# For 8:7 Systems (Atari 2600, Atari 5200, Famicom, NES, SNES, Super Game Boy, Turbografx 16, Turbografx CD) 

Settings ->

  - Video ->

    - Scaling ->

      - Integer Scale: OFF
      - Aspect Ratio: Custom
      - X Position: 25
      - Y Position: 33
      - Width:  670
      - Height: 586 

    
# Saving changes

To save the changes after all the adjustments you need to go to 'Quick menu' > Overrides > Save Content Directory overrides. 

  *This step is per system.
