# Aigis Over Will

> Release preparation: the three ZIP files have not been uploaded yet. Download and one-click links below will become available after release `v1.0.0` is published.

Play as Aigis from Persona 3 Reload / Episode Aigis in Metaphor: ReFantazio. Three separate Reloaded-II mods are collected here; the voice and outfit add-ons require the base model mod.

## Downloads

| Mod | Description | Download |
| --- | --- | --- |
| Aigis Over Will | Aigis model replacement with field and battle support, movement transitions and the Episode Aigis field sprint. | [ZIP](https://github.com/WizraRobinet/Aigis-Over-Will/releases/download/v1.0.0/Aigis-Over-Will.zip) |
| English Voices | Optional English overworld and battle voice replacement, with matched volume and combo-finisher routing. | [ZIP](https://github.com/WizraRobinet/Aigis-Over-Will/releases/download/v1.0.0/Aigis-English-Voices.zip) |
| Episode Aigis Combat Gear | Optional Combat Gear outfit replacing the protagonist Gekkoukan High School Uniform in the overworld and battles. | [ZIP](https://github.com/WizraRobinet/Aigis-Over-Will/releases/download/v1.0.0/Aigis-Combat-Gear.zip) |

For one-click installation, visit the [installation page](https://wizrarobinet.github.io/Aigis-Over-Will/). GitHub README pages may filter custom `r2:` links.

## Requirements and installation

1. Install [Reloaded-II](https://github.com/Reloaded-Project/Reloaded-II/releases/latest) and add your Windows PC copy of Metaphor: ReFantazio.
2. Install the base model mod, then optionally the voice and Combat Gear add-ons. Use the installation page buttons, or extract each ZIP into a separate folder under Reloaded-II's `Mods` directory.
3. Allow Reloaded-II to install required dependencies. For Combat Gear, also install [Metaphor Toolkit](https://github.com/RyoTune/MF.Toolkit) and [Costume Framework](https://github.com/RyoTune/MF.CostumeFramework); all dependency IDs are listed in each ModConfig.json.
4. Enable the selected mods under Metaphor and launch the game through Reloaded-II. English voice replacements are intended for English game audio.
5. For Combat Gear, equip the protagonist's **Gekkoukan High School Uniform** DLC outfit. The corresponding Metaphor DLC must be available on your account. Reload the area if the old field appearance is cached.

The base mod requires CRI FileSystem Hook and Metaphor Essentials. Voices additionally require Ryo. Combat Gear requires `MF.CostumeFramework.Reloaded`, `MF.Toolkit.Reloaded`, SigScan and Reloaded Hooks. Dependency download metadata is included where available; missing dependencies must be installed separately.

To uninstall, disable the add-ons and base mod in Reloaded-II, then remove their mod folders. The original game archives and saves are not replaced.

## Compatibility and current status

Other protagonist model, costume, animation or voice replacements can conflict. This mod targets the Windows Steam release used during development; exact compatibility with other builds is unverified. Models, voices and Combat Gear have been tested by the creator in game during development. The latest sprint replacement passed offline validation and preview, but still needs an in-game check. Dark facial shading patches have been reported in some scenes and remain unresolved. Facial lip sync and all story presentation elements are not fully replaced. This is an initial community release, not a claim that every scene or game version is tested.

If the game crashes, disable Combat Gear and voices first, test the base mod, then disable the base mod to check for a mod conflict. Restart the launcher and game after replacing files. Combat Gear diagnostics are written to `CombatGear.log` inside that add-on's folder.

## Credits

Aigis, Persona 3 Reload, Episode Aigis and Metaphor: ReFantazio, including source art, animations and recorded voices: ATLUS / SEGA and their credited contributors. This is an unofficial fan project with no affiliation or endorsement. These assets are not covered by a new open-source license.

Mod direction and testing: Wizra. Conversion, retargeting, hooks and packaging developed with OpenAI Codex assistance. No synthetic Aigis speech was generated. Tools include Reloaded-II, Metaphor Essentials, CRI FileSystem Hook, Ryo, Metaphor Toolkit, Costume Framework, Blender, BlenderToolsForGFS, FModel/CUE4Parse, VGAudio and vgmstream. Third-party tools and dependencies remain subject to their own licenses and are not bundled here.
