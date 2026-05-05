# Virpil CDT VMAX Throttle + Cadet Aeromax-R - Sub's Currated Bindings

> [!WARNING]
> THESE BINDINGS REQUIRE JOYSTICK GREMLIN!

> [!NOTE]
> My binds are now open source. I need contributers to assist with small updates when a patch drops. DM me on discord if you are interested. <https://github.com/SubliminalsTV/Subs-Curated-Bindings>

## Navigation

- [Install Videos](#instalation-video-guides)
- [Known Issues](#known-issues)
- [Functions](#functions)
  - [Freelook](#freelook)
  - [Eye Tracker Targeting](#eye-tracker-targeting)
  - [Flip Trigger](#flip-trigger)
  - [Opional Throttle Module](#optional-throttle-module)
- [Text To Speach & Audio Files](#adding-text-to-speach--audio-files)
- [Trouble Shooting](#troubleshooting)
- [Binding Charts](#binding-charts---no-more-adobe)

## Instalation Video Guides

At the time of making these video guides I had not yet distributed Virpil Binds. These guides have little to do with the joysticks themselves so these videos are just fine to demonstrate how to set them up regardless of what sticks you use.

### vJoy Install Video

vJoy Install Video - <https://youtu.be/ugjgKPf1-rk?si=nWBojuAKDvjGu3LO>
> [!WARNING]
> Check 3rd video for vJoy settings!

### HIDHide Install Video

HIDHide Install Video - <https://youtu.be/PyL156AywYQ?si=4XSdzWdzmITRkMPi>
> [!WARNING]
> Check 3rd video for HIDHide settings!

### Joystick Gremlin

Loading Enhanced Binds - <https://youtu.be/mc-ozIogrpI?si=WuwMqg0S-G922i10>
> [!WARNING]
> Assumes you have vJoy, HIDHide, and JG installed!

## Known Issues

- MFD Binds do not import properly into Star Citizen, this is a bug. They also have to be cleared manually to remove them. So you will need to add them manually, but hopefully they should stick after that.
- I have attached an image with the binds that need to be added. They are all physical modifier binds.
- Please contribute to the issue council report. <https://issue-council.robertsspaceindustries.com/projects/STAR-CITIZEN/issues/STARC-133477>

## Functions

### Freelook

To use freelook. Go into 3rd person (up on `L-Bottom-4-Way-Hat`). Now press and hold the `Modifier` button in. Now you are free to look around using the `R-Ministick` Click and HOLD in on the `L-Bottom-4-Way-Hat` to reset view.

### Eye Tracker Targeting

The main way I Target in Star Citizen is via an Eye Tracker. This adds to immersion and is a lot easier than using the native binds. Just look at the target, press a button and then they are locked. There are two eye trackers I recommend.

- Tobii Eye Tracker is next generation head and eye tracking. Unlock unique features that deepen your level of immersion in your favorite games including Star Citizen, Microsoft Flight Simulator, DCS, and more.

  - For more info and 5% off visit <https://tobii.subliminal.gg> "Purchases using the link and code `subliminal` at checkout support the curration of these binds."

- For a more budget friendly alternative check out Beam Eye Tracker. It is software only, and does require you to use your own webcam. It has some limitations like playing in a dark room or seeing through your glasses. But if you have a webcam and want to try eye tracking this is a MUST HAVE. There is a free trail on steam. Or you can buy it directly from beam.

  - For more info visit <https://beam.eyeware.tech/?via=subliminal> "Purchases using the link and purchasing through Beam directly support the curration of these binds."

### Flip Trigger

The flip trigger functions as a Missile Operator Mode switch and fire function

- To activate just pull the tigger down and you instantly switch to missile op mode. Pull in on the flip trigger to fire and when you are ready to go back to guns just flip the trigger back up. When you do this JG will preform a macro funtion to release `button 3` and press `button 123` since the AeroMax does not press a button when the trigger is flipped up. `button 123` is a dummy button made to set the operator mode to guns.

### Optional Throttle Module

- If you have purchased the optional Throttle module you will need to manually bind things to it in Star Citizen. I recommend putting it on the left side of the Aermomax-R and using it for mining and salvaging operations like mining laser power and salvage beam spacing. Joystick gremlin should already have this axis mapped if not map the axis to the first available vjoy 2 axis and then bind it game. If you went with 2 of these modules do the same for it and bind what you wish. If you do not have the module I have not bound anything to it so you should be good to go.

## Adding Text to Speach & Audio Files

To ensure joystick gremlin and Star Citizen modes are synced I prefer to have JG use TTS or play a sound clip when I switch modes. By default I have included TTS prompts. If you prefer audio files I have some included in the download.

### Adding Audio Files

- In the upper right hand corner of JG, you can select which mode you would like to edit. In the `SCM Mode`, `Aux Mode`, and `NAV Mode`, the VMAX Throttle `Button 21` cycles Master Modes and `Button 23` cycles in and out of Mining/Salvage Modes (Auxiliary). To add the audio files you will need to add an action for `Play Sound` to audibly confirm when JG changes Modes.

- To add the provided audio files, click `Button 21` then look towards the bottom of the action panel underneath the last action. Click the remap drop down and select `play sound`. Then click the `Add` button next to it. Clicking the pencil button will allow you to use windows explorer to tell JG where to find the audio files.

- There are multiple options for what audio files you can use and of course you could use your own. The audio files I provide are either voices from "Computer" aka/LCARS from Star Trek or HAL9000. And HAL9000 has two variations of dialogue.

- The Salvage and Mining audio files are for those who only mine OR salvage and want to hear a more personalized message. Auxillary is for those who mine and salvage. (This has no effect on the binds or game.)

- Simply load the .wave audio file for the corresponding mode. To know which one to use just read whatever I have in the Cycle Modes long press box inside JG.

- Remember to do this for `button 21`and `button 22` in `SCM Mode`, `Aux Mode`, and `NAV Mode` for the VMAX Throttle only

> [!WARNING]  
> You must save the JG profile after making changes to avoid having to repeat this every time JG or your PC restarts. It is a good practice to `Save As` and not overright my original JG file incase you may need to reload that working one in the future.

> [!WARNING]  
> Best Practices: You must have text or at least a `space` in the TTS box or else it will cause issues with JG. And the audio files must be linked properly, if you move them later not only will they not play but JG has issues when you have broken links in these fields.

### Removing Text To Speech when cycling modes

There are multiple ways to remove text to speech if you prefer not to hear it.

- The easiest way is to reduce the volume in `Windows Volume Mixer`if you prefer not to mess with JG at all.

- If you would like to remove it from JG, In the upper right hand corner of JG, you can select which mode you would like to edit. In the `SCM Mode`, `Aux Mode`, and `NAV Mode`, the VMAX Throttle `Button 21` cycles Master Modes and `Button 23` cycles in and out of Mining/Salvage Modes (Auxiliary). To remove TTS you can just click the `X` on this box.

- Remember to do this for `button 21` and `button 23` in `SCM Mode`, `Aux Mode`, and `NAV Mode` for the VMAX Throttle only

> [!WARNING]  
> You must save the JG profile after making changes to avoid having to repeat this every time JG or your PC restarts. It is a good practice to `Save As` and not overright my original JG file incase you may need to reload that working one in the future.

## Troubleshooting

Common Enhanced bind issues and their fixes can be found in the FAQ In Discord

- <https://discord.com/channels/303670222097874945/1297919077062279209>

Common Joystick/Star Citizen related issues and their fixes can be found here

- <https://discord.com/channels/303670222097874945/1154143410215731201>

> [!TIP]  
> If you have an issue not found in either of the FAQs, please take a screenshot of JG, HIDHide, vJoy, and USB Game Controllers and create a post in the "#Enhanced-binds-support" forum on discord. Please mention a @PeripheralExpert to ensure we get a ping ASAP - <https://discord.com/channels/303670222097874945/1006954369800998992>

## Binding charts - NO MORE ADOBE!!!

I have finally escaped Adobe's firm grasp and now moved the the free, fully featured alternative, Affinity. [https://www.affinity.studio/get-affinity](https://www.affinity.studio/get-affinity)
Affinty is now FREE!! Meaning anyone can open the .af files and edit them.

### Printer Friendly Binding Chart

- The chart labled `[Print]` has a white backgound to conserve ink for people who would like to print it.

- PRO TIP: If you have the paid version of adobe acrobat you can open the PNG file inside it and select the "Poster" option in the print settings and change the scale from %100 to 30% and it will spplit the chart into two pages with 1 stick on each page. For other programs just remember that scalled down to 30% its small enough to fit each stick on its own page.
