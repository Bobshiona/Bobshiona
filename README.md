## I make the Mac do more work.

Fast native software, graphics engines, networking, and tools I actually use. Short feedback loops. Details worth sweating.

### Horizon 1.8.9

A Minecraft 1.8.9 client built in **Rust and Apple Metal**.

- Protocol 47 networking with encryption, compression, and Microsoft sign-in.
- All 198 block IDs and 2,557 blockstate variants loaded from the player's own game jar.
- Tick-accurate movement checked against an official vanilla server. Stair collisions compared across 52,488 neighbour configurations.
- Native Retina rendering, threaded chunk meshing, interpolated players, armor, and asynchronous skin/cape textures.
- User-driven combat, block interaction, and inventory windows verified against vanilla. Remaining parity work is in progress.

[Explore the source and verification details →](https://github.com/Bobshiona/horizon-1.8.9)

<img src="https://raw.githubusercontent.com/Bobshiona/horizon-1.8.9/main/docs/media/189/blocks.png" alt="Native Metal client rendering the Minecraft block registry" width="100%">

<img src="https://raw.githubusercontent.com/Bobshiona/horizon-1.8.9/main/docs/media/189/entities.png" alt="Player and block entities in the native client" width="49%"> <img src="https://raw.githubusercontent.com/Bobshiona/horizon-1.8.9/main/docs/media/189/block-entities.png" alt="Chests and a sign rendered with the original game assets" width="49%">

**Working stack** · Rust · Apple Metal · Swift · Next.js · Python · local AI workflows
