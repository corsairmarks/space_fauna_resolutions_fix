# Overview

Are you tired of not being able to protect the Space Amoebas and the Tiyanki at the same time?  Then this mod is for you!

# Changes

This mod replaces the `common/resolution_categories/00_resolution_categories.txt` file that defines most of the Galactic Community
resolutions categories.  The only change is to add the tag `multiple_active_resolutions = yes` to the Space Fauna category.

## Compatibility
 
Because it replaces a core Stellaris file, this mod is inherently incompatible with any other mods that overwrite the same file.
If another mod only changes resolution categories for the Galactic Custodian/Galactic Imperium then it might be compatible with this one -
those live in a different file.  If another mod only changes the resolutions themselves, it should be compatible with this one.

This mod is not compatible with achievements because it overwrites a core Stellaris file.

### Post-Game Start

This mod can be safely added or removed from your savegame after the game has started.  It alters a single game object, but will not negitively impact your savegame.  If you remove it, your game will work normally.

## Changelog

* 1.0.0 Initial version
* 1.0.1 Flagged as compatible with Stellaris 3.0.* (no script changes)
* 1.0.2 Update README, remove extra image to keep distribution lightweight (no script changes)

## Bug Report

~~I've filed a bug report for this issue, and others have reported it in version 3.0.1 and 2.8.1. Please visit the [official forums](https://steamcommunity.com/linkfilter/?url=https://forum.paradoxplaza.com/forum/threads/stellaris-v3-0-3-dick-d281-cannot-have-space-amoeba-protection-and-tiyanki-conservation-acts-active-simultaneously.1474887/) and upvote this bug report!~~

**UPDATE:** The bug report was confirmed and added the the internal Paradox bug tracker.

## Source Code

[Hosted on Github](https://github.com/corsairmarks/space_fauna_resolutions_fix)

### Development Notes

It is best to clone this repository in a directory _other_ than `<Stellaris User's Directory>/Paradox Interactive/Stellaris/mod`, and then make a connection to the `mod` folder in this repository via a `*.mod` file's `path` property.  Also note that the README.md file exists in the `mod` directory but is symbolically linked in the root directory.