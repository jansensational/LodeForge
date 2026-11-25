# Lodeforge

A dwarven underground factory game in one HTML file. Mine ore, automate with belts and machines, catch spark motes for power, research new tech, and keep the air in your sealed caverns breathable.

## Play

Open `index.html` in a browser, or play the hosted copy on GitHub Pages once it is turned on.

## Controls

| Action | Keys |
|---|---|
| Move · jump | A D · W / Space |
| Mine / place | Left mouse / right mouse |
| Select hotbar slot | 1–9 or mouse wheel |
| Rotate output | R |
| Take output · insert · deliver | E · F |
| Change recipe or pump gas | Q |
| Pack and crafting | Tab or C |
| Research | T |
| Gas view → heat view → off | G |
| Drop through a catwalk | S |

## The simulation

- **Gases:** oxygen, nitrogen, CO₂, methane, hydrogen and steam. They flow along pressure differences, settle by weight, and are invisible until you sense them up close or read a room with a Gas monitor.
- **Temperature:** heat makes gas expand and rise. Fires, air candles and vents add heat, and the rock pulls everything back toward its own temperature: permafrost near the top of the world, warm in the depths.
- **Water:** it flows, boils into steam at a boiling point set by the pressure above it (100 °C at 1 atm), condenses back as it cools, and freezes into ice below 0 °C.
- **Breathing and fire:** both use real partial pressures. Below 0.14 bar of oxygen you suffocate; above 1.6 bar it is toxic. CO₂ above 0.1 bar poisons, 4 bar crushes, and air at 60 °C or hotter scorches. Fires burn fully down to 0.17 bar of oxygen and go out near 0.12 bar.

## Saving

- The game autosaves in your browser every 20 seconds.
- In the pack (Tab), the **World file** row can:
  - **Save to file:** download your world as a `.json` file.
  - **Load from file:** open a saved world.
  - **Autosave to a file:** in Chrome or Edge, keep a file on your computer updated automatically.
