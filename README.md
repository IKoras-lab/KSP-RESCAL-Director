# KSP-RESCAL-Director
A comprehensive Orbital Resonance Calculator for KSP 1 with built in mod support.

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

- INTRO -

I have spent a few days making a more Robust HTML based Resonant Orbit calculator for KSP and currently with support for The Outer Planets mod and The Kcalbeloh System mod. I have gone looking but can't find one I need.
Current version is beta: V8-2       

- I will update it frequently until the math-math's so to speak and it's easy to use.
This whole calculator came about because I didn't catch my error in how my ksp handles Ap/Pe altitudes.. I had 30 relay satellites I realized would de-sync within 50 years in game and didn't want to have to manually convert every input and output to use the existing online calculators. So I added all the features I'd want from a resonant orbit calculator to handle mods and scales. with the precision to maintain orbital periods down to an accuracy of .01s

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

- FEATURES -

- I have included support toggles for scale incase you are using scale a changing mod.
- I have included a Datum toggle depending on if your version of ksp calculates Ap/Pe as and ASL based ALT or of it uses the raw CoG distances that the wiki would show you. 
- I added extra look-up panels for celestial bodies so you don't need to juggle tabs.
- I modified a code for a graphic plotter to work for the calculator.
- I Have started to implement Radio recommendations based on the calculated orbit (big WIP)
- I have all the stats set to update when making input changes or switching between distances  with a backup "Calculate" button to catch any edge cases where the stats don't update correctly.

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

- CAVEATS -

- I am still making changes to the Results, and Antenna sections, along with some names and other features. like estimated delta-V for the Dive/Soar-Circularization burns (so you can know how much delta v to design you satellites for.  I am releasing this now because the math seems accurate enough to use now
- Some of the displayed unit types and level of precision is a little funky as I'm not that fluent with html and needed help from A.I for the style and plotter sections and am still getting things perfect/learning.
- If i have failed to credit anyone, let me know and I will add it.

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

- FUTURE PLANS -

Once I have reached a final version that Handles all the math correctly & will need help to verify the Celestial Body Information I have compiled for accuracy. If everything checks out, adding other planet or system mods is as easy and amending the CBI list with names and values and adding a selection toggle at the top like the existing mods.

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

- here is the github: https://github.com/IKoras-lab/KSP-RESCAL-Director
- and the live site address: https://ikoras-lab.github.io/KSP-RESCAL-Director/
