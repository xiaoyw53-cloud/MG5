# MG5
## Devlog
### A NavMesh is useful when characters need to find paths around obstacles. I would use it for a click-to-move game like League of Legends. Physics-based movement makes more sense for a platformer where jumping, gravity, and collisions are central to gameplay.
### The loop checks every bird in the _birds array each frame. Vector3.Distance measures the distance between the current bird and the player. If that distance is less than or equal to _interactDistance, the code calls RunAway(). Every bird within that range will flee from the player.

## Open-Source Assets
- [Quirky animal 3D models](https://assetstore.unity.com/packages/3d/characters/animals/quirky-series-free-animals-pack-178235)
- [Mountain fantasy environment models](https://www.fab.com/listings/60487a72-3f20-4bb2-aa78-247ed1582656)
