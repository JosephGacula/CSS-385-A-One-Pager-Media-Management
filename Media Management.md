# Media Management in Vibrant Edge

## Media in Similar Games

For the games my group is specifically taking inspiration from (Mega Man X and Gunvolt), most interactable assets directly related to gameplay are pixel art. This includes the sprites of the playable characters, level terrain, enemies, items, etc. Environment art is also usually pixel art depending on the game.

Where story is relevant, cutscenes are done either in-game with the sprites being animated. This usually applies to small interactions such as a boss introduction or a level intro. For more important story-related events, still frames drawn like a comic will often appear with effects. During levels, character portraits with different expressions will appear with voiced-over text to create banter within the level, acting as exposition and character moments. There is usually no traditional video.

Music is straightforward, playing in the background and changing in different contexts—generally fast-paced.

## Strategies for Integration

In terms of story, to help convey it, we’d probably use the drawn-still and in-game cutscene strategy. Important events such as exposition in the beginning or defeating an important boss could be drawn and conveyed like a motion comic. This way, more detail can be conveyed without having to spend time on animation. If we have time, some simple sprite animation could be done for smaller events. Pros include taking less time to create and conveying more detail/expression, while cons include not showing exactly what’s happening and increasing file size.

In terms of interactive assets, terrain would most likely be pre-made assets from the Unity Asset Store, preferably in a pixel art style. For characters and enemies, we are going to attempt creating the sprite sheets on our own to convey the character designs that we came up with. Enemy sprites would be relatively limited due to being stationary or having few actions. For the player character, there would have to be more sprites made. We would also make any items in a similar manner. Pros include having access to an editable sprite sheet for specific animations when we want them; cons include having to create the assets ourselves.

Music will also be created on our own end and will be static depending on the scene, meaning it won’t change based on factors like the number of enemies present or the amount of health the player has.

## Integration Approach

For pre-drawn stills, an art software such as Photoshop or Clip Studio will be used to create the assets. In Unity, these can then be inserted as UI canvas objects and would play procedurally as the player clicks through their own scene.

For in-game sprites, a tilemap system will be used for any terrain to make creating levels easier. A software such as Aseprite will be used to create character assets, which will then be assembled into a sprite sheet to create animations. We will implement tricks like anime-style hover-dashing to avoid having to animate an entire run cycle.

Music will be made in a software like FL Studio or GarageBand and will play when a scene is loaded.
