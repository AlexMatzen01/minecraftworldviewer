# Minecraft World Viewer

A polished, browser-only Minecraft Java Edition world explorer.

## Features
- Anvil region parsing with chunk map and heightmap terrain shading.
- Player browser for playerdata files with coordinates and raw NBT.
- Recursive NBT inspector for chunks, players, and POIs.
- POI region parsing with search and category filters.
- Pan, zoom, hover inspection, chunk selection, and JSON export.
- World metadata from level.dat.
- Drag-and-drop loading.
- No runtime dependencies and no world upload backend.
- GitHub Pages workflow included.

## Run
Open index.html in a modern browser, or serve the repository as a static site. Choose the root of a Java Edition world with Open world folder.

The project uses browser File APIs and Web Streams, so world data stays on the user's device.