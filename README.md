# Gothic Engine Patches
A collection of engine patches implemented using Union.

Explanation of the folders:
- `/` (root) - These are fully working and tested patches, which are safe to use.
- `experiments/` - Contains various experimental patches for stuff like restoring cut features. They are not tested and WILL have side effects.
- `old/` - Contains previously made fixes, which I have since found issues with or don't like how they are done. You can use them but they might have unintended side effects.
- `useful/` - Contains useful stuff mainly for Spacer. Changing lightmap resolution or disabling LoD generation for worlds.

| Patch | Affected games | Integrated in Union | Integrated in Archolos 2.0 | Description |
|-------|-------|-------|-------|-------|
| classic_climbing_fix | Only Gothic II Classic |  ❌ | ❌ | Fixes problems with climbing in G2 Classic |
| mover_collision_fix | Gothic and Gothic Sequel |  ❌ | ❌ | Fixes gates getting stuck when closing/opening (Imported from G2) |
| mover_sound_update_fix | All |  ❌ | ✔️ | Fixes sound not moving together with movers |
| parser_null_fix | All |  ❌ | ❌ | Fixes issue with smalltalk, among other things. |
| smalltalk_interrupt_on_footstep_fix | Gothic and Gothic Sequel |  ❌ | ❌ | Fixes voicelines being terminated incorrectly (Imported from G2) |
| spacer_lighttrace | Gothic 1 Spacer |  ❌ | ❌ | Changes light compilation behaviour to match Gothic 2 |
| spacer_mrm_bbox | Gothic 1 Spacer |  ❌ | ❌ | Changes mesh compilation behaviour to match Gothic 2 |
| spell_transform_equipweapon_fix | All |  ❌ | ✔️ | Stops the hero's weapons being changed after ending a transformation spell |
| spell_transform_reset_enemy | All |  ❌ | ✔️ | Fixes monsters attacking the invisible hero while transformed |
| watchfight_dodge_fix | Gothic II Classic and Gothic II Gold |  ❌ | ✔️ | Fixes NPCs strafing sideways infinitely while watching a fight |
