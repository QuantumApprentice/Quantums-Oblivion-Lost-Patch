# Quantums-Oblivion-Lost-Patch


*Update!
This new version corresponds to the v1.04 release of Oblivion Lost.
V1.04 has a butchered pipboy.msg file.
This patch includes a fixed version which replaces the version found in Patch001.dat of Oblivion Lost v1.04.
These should work with any older save files you have and prevent most crashes,
but I make no guarantees about broken quests.
I definitely would try installing this if town maps are crashing on you.

# Installation
Download the patch from here:
https://www.moddb.com/mods/quantums-oblivion-lost-patch

To install just copy the Patch002.dat file into the same folder as
patch000.dat and patch001.dat.
Right next to the executable, over-writing any existing Patch002.dat.

(If you want to preserve an existing Patch002.dat and know what you're doing, 
you can rename this file to Patch003.dat, which will apply the fixes but 
leave the russian translation found in the Patch002.dat file that comes with v1.04)

That's it, that's all you have to do.
Congratulations! Now you're updated to the most recent patch.
Hope you enjoy the game fixes, I'm going to call it "Quantum's Oblivion Lost Patch"
when I upload it...what do you think? Too showy? or just right?


### I fixed 5 specific things in this patch:
1) Most of the crashes were caused by the "anomalies" scattered around the map.
   After a few weeks, (randomly selected for each one when you first enter a map),
   an anomaly will attempt to spawn an "Artifact" on the little glowing lines that
   randomly pop up directly over an anomalies location,
   (hint you need perception >=(rnd(6,8)) for this to happen).
   The type of artifact spawned is based on the type of anomaly.
   Patch001.dat had a version of the script that would attempt to spawn
   an artifact into one of these objects even if that object wasn't actually there,
   because the script is actually a spot on the ground,
   and spawns the anomaly only if you've interacted with it with high perception.
   Patch000.dat had a version that checked if the Anomaly had spawned first...
   ...so that's the one I included in the patch.

2) Several scripts were incorrectly assigning karma,
   which was causing the engine to access and stomp
   memory more or less randomly.
   I just fixed the assignment.

3) Several of the scripts on the CNPP end boss map 
   which don't trigger at the right time, and Strelok's
   weird walking issue have also been fixed.

4) And finally, the one map that Warlockracy could not get to,
   the one map preventing him from finishing this mod,
   the Enclave Detention center, now expands to the end of the hall
   where you can ride the elevator down to Mnemonics for the final quest.

5) Oblivion Lost release v1.04 has a butchered pipboy.msg file located in
   its patch001.dat file which wasn't there in the v1.03 release. This caused a
   bug where opening the pipboy froze the game in place, and prevented you
   from doing anything except exit.
   I fixed it and added it to this version of Patch002.dat.


