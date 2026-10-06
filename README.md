# Drone Project

A simple drone game made in Unreal Engine 5 with Blueprints, created for an internship with the Dutch Marine Corps (Nederlandse Mariniers).

You start as a drone on a landing craft next to a small island. Fly to the island, pick up the military caps with the drone's claw, and bring them back to the ship.

## Requirements

- Windows
- Unreal Engine 5.8
- Git with Git LFS (the project's assets are stored with LFS)

## Getting the project

```powershell
git lfs install
git clone <repository-url>
```

## How to start the game

1. Open `DroneProject.uproject` in Unreal Engine 5.8.
2. If an "Untitled" or "NewMap" window appears, click **Cancel**.
3. In the Content Browser, go to `Content/Drone` and open **mainlevel**.
4. Press **Play** (the green play button at the top).

You spawn as the drone on the ship automatically.

## Controls

| Key | Action |
|-----|--------|
| W / S | Fly forward / backward |
| A / D | Fly left / right |
| Q / E | Turn left / right |
| Space | Fly up |
| Ctrl | Fly down |
| C | Switch camera (first person / third person) |
| F | Open / close the claw (pick up / drop a cap) |

## How to play

1. Fly from the ship to the island.
2. Hover above a cap so it is right under the claw.
3. Press **F** to close the claw and pick up the cap.
4. Fly back to the ship.
5. Press **F** again to open the claw and drop the cap on the deck.

## Assets used

- **Drone Scavenger** by LUZ Studio
- **Military Hat** pack
- **Free WWII Landing Craft Type 2** by PixelForgeESP (Fab)

The island, water and materials were made in Unreal Engine.
