Overall goal:
- Game programming in Win32
- Simple complete games (pong, tetris etc.)
- Simple Win32 level editor (create content for the games)

Maybe ideas:
- Text mode engine debugging UI (for selecting various test screens and tools)

# Todo
- Controller and keyboard input
- Audio support
- Add logging
- Mouse input
- Draw API: lines
- Draw API: rectangles, polygons
- Draw API: alpha blending
- Draw API: circles
- Draw API: Add test screen drawing various shapes
- Move stuff from ProgramContext down into EngineState
- Move quit with escape into game.cpp
- Add engine and game init functions
- Bug: ignore keyboard key/mouse buttons if window not focused
- Window: Borderless full screen
- Window: Render at lower resolution and upscale it to fit screen
- Draw API: Per vertex colors, interpolate color between vertices
- Draw API: Textures
- Debugging: print file name from LOG macros
- Measure frame delta
- Font support
- Text Mode UI prototype
- [!] Write Blackjack game
- CPU Profiling
- Measure render API, see if things can be optimized (e.g. less loops, SIMD, less memory allocations etc.)
- DLL based hot reloading
- Asset system (store audio, images, fonts, etc.)
- [!] Write Tetris game
- Collisions
- [!] Write Pong game
- Camera
- Enemy AI
- [!] Write Zelda Dungeon game
- Draw API: Polygons (triangle strips, triangle fans)

# Doing
- Create window and draw to it

# Done
