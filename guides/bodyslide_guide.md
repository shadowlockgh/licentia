# How to build Outfits in Bodyslide for Licentia NEXT

With this process you can change your character's body preset, modify the body of new armors mods, and more.
These are the general steps to run Bodyslide for **Licentia NEXT**:
1. Create an Empty Mod for Outputs
2. Run Bodyslide
3. Select your respective Outfits and Preset
4. Batch Build Outfits to the Output Mod

---

## Step 1. Create an Empty Mod

Scroll to the bottom of the Mod Organizer 2 Window, and right click in the blank space under Overwrite.
There will be a list of options available, select Create Empty Mod.

<img src="/images/guides_images/bodyslide_guide/1_empty_mod.png" alt="Create Empty Mods" style="width:20%; height:20%;">

You will now be prompted to name your custom mod, this can be named however you want.

> [!TIP]
> Adding `[NoDelete]` before the name will make the mod not be removed upon updating the list.
> Upon updating the mod will be deactivated and moved to the bottom of the last separator, and you can simply move it into place and enable it.

<img src="/images/guides_images/bodyslide_guide/2_create_mod.png" alt="Name Custom Mod" style="width:25%; height:auto;">

The new empty mod you made will be created under the `Bodyslide Outputs` Separator, as long as your custom mod is below _Licentia NEXT Bodyslide Output_ your changes will override default outfits.

## Step 2. Run Bodyslide

Once you have created your Output mod head over to the Top Right of MO2 to the launch section. Open the dropdown and select BodySlide x64, then run the program.

<img src="/images/guides_images/bodyslide_guide/3_run_bodyslide.png" alt="Run Bodyslide" style="width:70%; height:auto;">

Upon opening the program for the first time you will be prompted to select the respective game and Game Data Path.

> [!WARNING]
> By default SkyrimSE will have it's data checking the default Steam Installation Directory.
> This will cause BodySlide to not access the files properly and you will see errors with textures, missing files, etc.

In your Licentia NEXT Installation folder there will be a folder named Stock Game. Inside the folder you can `Right Click` /Data, and choose `Copy as Path`.
Paste your Installation Path in the Game Data path for Skyrim SE, then hit OK to continue to the main interface.

## Step 3. Select your respective Outfits and Preset

On the top right of the interface there will be two search bars for Filter Groups and Filter Outfits, select the search icon for Filter Groups and select Choose Groups.

<img src="/images/guides_images/bodyslide_guide/4_choose_groups.png" alt="Select Groups" style="width:50%; height:auto;">

> [!NOTE]
> In the Outfit/Body dropdown list you will have two main sets of body types, 3BBB/3BA/CBBE for Female and HIMBO for Male.
> You will need to select the respective groups for which body you want to build, since you cannot build Male and Female simultaneously due to different presets.

A list will open with various groups to choose outfits for. For Female select both 3BBB and 3BA, and the related groups such DX Crimson Blood 3BA. For Male select HIMBO and it's applicable groups.


Example Group Selections for Female and Male:

<img src="/images/guides_images/bodyslide_guide/4a_group_sample.png" alt="Group Examples" style="width:30%; height:auto;"> <img src="/images/guides_images/bodyslide_guide/4a_group_sample2.png" alt="Group Examples" style="width:30%; height:auto;">

Once you have your Outfits selected, you will need to select a Preset from the dropdown at the top of the interface to build your outfits with. For Female characters the default preset the list is compiled with is `3BBB Cacophony-Varied`. For Male characters, the default preset is `Himbo-Varied`.
You can use any preset in the list or one you have downloaded, make sure you build all respective outfits to the same preset.

Default Female Presets with the List's default selected:

<img src="/images/guides_images/bodyslide_guide/4b_preset_sample.png" alt="Preset Examples" style="width:30%; height:auto;">

## Step 4. Batch Build Outfits to the Output Mod

Once you have chosen your desired outfits to build and preset, it is time to Batch Build the outfits to your output.

On the bottom left of the Interface there is the button to Batch Build, Build Morphs, and select alternatives.
Tick the checkbox for the previewed outfit path, but do not tick Build Morphs.

<img src="/images/guides_images/bodyslide_guide/5_batch_build.png" alt="Batch Build" style="width:30%; height:auto;">

- After you have ticked the checkbox next to the preview, hold `Left CTRL` and select Batch Build.
- A list of outfits will pop up, scroll through and verify everything is correct then press Build.
- File Explorer will now open in the Stock Game/Data directory. In the address bar click the root folder of your installation and open /Mods.
- Find the folder for your Empty Mod that was created earlier, for example `[NoDelete] Bodyslide Output`.

Depending on your selections an additional menu may open for choosing Output Sets. If there is conflicting outputs selected, here you can select which alternative you want to select for example Physics versions of Outfits over Non-Physics.

Make your selections then continue, and Bodyslide will convert all your selections and place them in your output.
You can now close Bodyslide.

Back in MO2 once it unlocks right click your Custom Output Mod, the error for `No Valid Game Data` should now be resolved.

Tick your Output Mod to enable it, and you will have successfully built Bodyslide Overrides.

---

If you have any questions or problems, stop by the Licentia Next Category in [Vermi's Hub Discord Server](https://discord.gg/hRCYPMpX7J) and we can help you work them out!
