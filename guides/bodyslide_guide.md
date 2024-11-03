# How to build Outfits in Bodyslide for Licentia NEXT

With this process you can change your character's body preset, add new armors, and change outfit features if they are supported.
These are the general steps to run Bodyslide for **Licentia NEXT**:
1. Create an Empty Mod for Outputs
2. Run Bodyslide
3. Select your respective Outfits and Preset
4. Batch Build Outfits to the Output Mod

---

## Step 1. Create an Empty Mod

Scroll to the bottom of the Mod Organizer 2 Window, and right click in the blank space under Overwrite.
There will be a list of options available, select Create Empty Mod.

<img src="/images/guides_images/bodyslide_guide/1_empty_mod.png" alt="Create Empty Mods" style="width:70%; height:auto;">

You will now be prompted to name your custom mod, this can be named however you want.

> [!TIP]
> Adding '[NoDelete]' before the name will make the mod not be removed upon updating the list.
> Upon updating the mod will be deactivated and moved to the bottom of the last separator, and you can simply move it into place and enable it.

<img src="/images/guides_images/bodyslide_guide/2_create_mod.png" alt="Name Custom Mod" style="width:70%; height:auto;">

The new empty mod you made will be created under the 'Bodyslide Outputs' Separator, as long as your custom mod is below _Licentia NEXT Bodyslide Output_ your changes will override default outfits.

## Step 2. Run Bodyslide

Once you have created your Output mod head over to the Top Right of MO2 to the launch section. Open the dropdown and select BodySlide x64, then run the program.

<img src="/images/guides_images/bodyslide_guide/3_run_bodyslide.png" alt="Name Custom Mod" style="width:70%; height:auto;">

Upon opening the program you will be prompted to select the respective game and Game Data Path.

> [!WARNING]
> By default SkyrimSE will have it's data checking the default Steam Installation Directory.
> This will cause BodySlide to not access the files properly and you will see errors with textures, missing files, etc.

In your Licentia NEXT Installation folder there will be a folder named Stock Game. Inside the folder you can 'Right Click' /Data, and choose 'Copy as Path'.
Paste your Installation Path in the Game Data path for Skyrim SE.

