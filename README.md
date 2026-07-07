# om_mappings

Deobfuscation mappings for the game Opus Magnum.

Obfuscated names are unstable between game versions; they are mapped to (hopefully) stable intermediary names using [matcher](https://github.com/QuintessentialOM/matcher). Intermediary names are then mapped to human-readable names.

Intermediary mappings files are named `mappings_<branch>_<date>[_<optional description>]_<mvid>.json`, where `branch` represents the steam game version branch (default, community edition, previous, etc.), `date` is the release date of the update, and `mvid` is the MVID (module version id) that uniquely identifies the game assembly. (This is because, for some reason, Opus Magnum does not actually have any version numbers.)
