[![GitHub release](https://img.shields.io/github/release/alganthe/ganthe_ACE3medical_vr.svg)](https://github.com/alganthe/ganthe_ACE3medical_vr/releases)

This mission is a training / debug mission for ACE3 medical - Rewrite

By default there's 4 "pads" aka spawning points for patients, use the terminals next to them (ACE interaction) to spawn / despawn patients with specific damage inflicted to them.

If debug is enabled via mission parameters use the self interaction called "Toggle medical debug info" while looking at a patient.

This mission is MP compatible, you can
- Add more pads by adding a single line to initPlayerLocal.sqf `[terminalName, spawnAreaName] call derp_fnc_actions;` for each new pad.
- More medic units by just placing the unit and make it a medic via EDEN attributes.
- By default the system is set to advanced, feel free to switch it back to basic by editing the mission.

This mission is what I use to write the user documentation for the medical system.
