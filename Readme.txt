Madmod is a large overhaul mod that aims to make the game a much better experience. It affects both the gameplay and visuals and also greatly extends the length of the main campaign. Starting a new game is required for all changes of this mod to properly take effect. This mod is most likely to be incompatible with other mod manager mods and does not affect the dlc.

\Initial release changes/
-Small 3d items like dropped weapons or empty clips will never despawn. This will inevitably cause strange things to happen but I haven't had it cause crashes so that's good. Loading a save will despawn them and fix the issue. 
-Increased amount of EDF control for all sectors to force players to partake in many more guerrilla activities per sector and makes the overall game a much longer experience.
-Npcs on the same team can not damage each other. Prevents horde’s from accidentally killing their own people during combat. Players can still kill npcs.
-Major improvements to the way explosions are handled. Explosions will blast away any structure with ease including those pesky steel beams.
-Tweaks to alert_level.xtbl. To lose alert level either hide for a minute or drive far away from the crime scene.
-Removed bullet push force on ragdolls to add more variety to the ways they fall down after death.
-Increased the max number of simultaneous projectiles that can be in the world at once to 127.
-Increased distance at which the game will convert civilians to guerrilla members.
-Increased the cost of upgrades to compensate for the increase in spawned salvage.
-Nerfed EDF flyers. Players can shoot the wings off with ease to take them down.
-Increased distance at which blood splat and bullet hole decals can be drawn.
-Removed player flinch and landing animations to improve movement handling.
-Removed ability for npcs to remove remote charges attached to them.
-Added collision physics to small 3d items which did not have them.
-Replaced most death and knockdown animations with ragdoll physics.
-Increased vehicle vertical fov to 75. Excludes tanks and walkers.
-Tweaked a lot of weapons to fire as fast as you click.
-Fix Reconstructor not being selectable in ammo crates.
-Increased satellite artillery cam vertical fov to 75.
-Change all crosshairs to the one the sniper uses.
-Npcs in vehicles are immune to explosion damage.
-Player melee attacks will always ragdoll npcs.
-Removed player collision damage from debris.
-Removed player sequential damage reduction.
-Added ability to skip all startup screens.
-Removed EDF reinforcements spawn delay.
-Remove low health desaturation effect.
-Increased repair radius and distance.
-Tweaks to rfg_stress_controls.xtbl.
-Increased courier chase distance.
-Increased player movement speed.
-Increased npc weapon burst size.
-Increased size of blood decals.
-Maybe increased lod distances.
-All structures spawn salvage.
-Removed melee auto targeting.
-Removed salvage pickup delay.
-Increased player hit points.
-Improved npc vs npc combat.
-Remove player reload delay.
-More powerful sledgehammer.
-Increased max ammo to 999.
-Tweaks to difficulty.xtbl.
-Bullets damage structures.
-Increased traffic density.
-Remove player fall damage.
-Adjust vehicle handling.
-Removed weapon overheat.
-Removed fog near clip.
-Removed weapon recoil.
-Reduced bullet spread.
-More aggressive npcs.
-Remove camera shake.
-Better npc aim.

\Changelog v0.11b/
-Slightly decreased the Reconstructor repair range to fix vfx being rendered a little too far ahead. This is separate from the repair radius which is still the same.
-Increased the maximum number of remote charges that the final upgrade allows you to place from 12 to 99.
-Hopefully replaced all death animations with ragdoll physics for real this time.
-Attempted to increase Reconstructor repair rate to as high as possible.
-Added the upgrades.xtbl entry to modinfo.xml. Very important fix.
-Added some forgotten initial changes to the top changelog.
-Maybe unlock the Reconstructor for the start.
-Sledgehammer skins cost no salvage.
-Increased nano dissolve radius.

\Changelog v0.12b/
-Increase the amount of EDF control in the Dust sector by 160. This change unfortunately will only take effect with a new game.
-Fix issues with some weapons like the Grinder not firing along with a few other potential issues.
-Satellite artillery should fire as fast as you click. Has not been tested to confirm yet.
-Prevent npcs from fading out when very close to the player's view.
-Reduce damage multiplier for vehicles that player is currently in.
-Increase npc incline/decline blend tree distance.
-Increase alert level decay rate when hiding.
-Removed vehicle camera auto centering.
-Increase cost of upgrades a bit more.

\v0.13b info/
Fully play tested sectors Parker, Dust, Badlands, Oasis, and the Freefire zone.

\Changelog v0.13b/
-Increased the amount of EDF control in the Badlands by 35 and Oasis by 135. Only takes effect with a new game.
-Slightly increased the rate at which the player can throw remote charges by changing two animations.
-Fixed npcs firing all gauss rifle rounds at once.
-Increased cost of upgrades slightly more.

\Changelog v0.9b/
-Increase distance at which EDF will spot the player with a threatening weapon. Will become hostile when player is seen carrying them for long enough.
-Increase amount of EDF control in Eos by 410. This will be the last time a change like this is needed. Only takes effect with a new game.
-Add modmanager config options. Vehicle fov, satellite artillery cam fov, melee auto-targeting, and vehicle cam auto-centering.
-Improve overall visual quality by reducing ambient lighting brightness to make shadows and shaded objects darker.
-Increase max speed of all vehicles. Be aware that the faster you go the worse the vehicle will handle.
-Reduce size of blood decals. They are still fairly large with this change.
-Tweaks to rfg_stress_controls.xtbl again.

\Changelog v0.9.1/
-Add salvage, proxy mines, and remote charges to world objects that will never auto despawn.
-Prevent guerrilla squads from spawning with sledgehammer in early stages of the game.
-Increase speed of EDF flyers and remove body tilting to improve handling for ai.
-Reduce frequency at which player ragdolls when standing on moving vehicles.
-Better collision physics for salvage. Can now stack on top each other.
-Restore original ai max firing distances to fix potential ai bugs.
-Restore original ai burst sizes to fix potential ai bugs.
-Increased guerrilla reinforcements spawn density.
-Removed guerrilla reinforcements spawn delay.
-Increase cost of upgrades a little bit more.
-Restore player sequential damage factor.
-Make ammo boxes invulnerable.
-Optimize lod_properties.xtbl.
-Adjust game difficulty.

\Issues/
-The never despawning props feature will eventually cause very bizarre issues to occur. When this happens, save game and load that save you just made to fix the issues. 
-Some guerrilla activities are locked behind missions so if you are unable to get sector control to zero then try completing the missions.
-Player animations not working on classic RFG until you change weapons.
