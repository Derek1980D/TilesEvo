# TilesEvo

An incremental tile-based resource management game where strategic placement and prestige mechanics drive endless progression. Build generators, expand your space, and reset to unlock new possibilities.

🎮 **[Play Now](https://derek1980d.github.io/tilesEvo/)** - Live version on GitHub Pages

## Game Vision

TilesEvo is an incremental game that combines spatial management with resource generation. You start with limited space and resources, expanding your grid by claiming new tiles. Each tile can become a resource generator, producing goods that fuel further expansion. As you progress, prestige layers unlock new mechanics, generators, and strategic depth.

**Core Loop:**
1. Place tiles to expand your grid
2. Convert tiles into resource generators
3. Harvest resources to afford more tiles
4. Reset with prestige bonuses to unlock new content
5. Repeat with increasing complexity

## Features

### Current (v0.1 - Foundation)
- ✅ 16×16 grid system with click-to-place mechanics
- ✅ Resource management (limited starting resources)
- ✅ Tile placement costs (strategic planning required)
- ✅ Live UI showing grid state, tile count, resource balance

### Planned (v0.2 - Core Mechanics)
- 🚧 Tile types (empty, basic generator, etc.)
- 🚧 Resource generators (convert placed tiles into production)
- 🚧 Multiple resource types (wood, stone, metal, etc.)
- 🚧 Production system (passive generation over time)
- 🚧 Upgrade mechanics (enhance generator output)

### Planned (v0.3 - Expansion & Strategy)
- 📋 Advanced tile types (rare generators, special effects)
- 📋 Generator combinations (adjacency bonuses)
- 📋 Worker/automation systems
- 📋 Skill tree or tech tree unlocks

### Planned (v0.4 - Prestige System)
- 📋 Prestige mechanics (reset for permanent bonuses)
- 📋 Prestige upgrades (passive multipliers, expanded grid)
- 📋 Meta progression (new content unlocks per prestige)
- 📋 Prestige layers (multiple reset trees)

### Planned (v0.5 - Advanced Systems)
- 📋 Trading/markets
- 📋 Complex recipes and crafting
- 📋 Event systems
- 📋 Endgame content and challenges

### Planned (v0.6 - Polish & Balance)
- 📋 Save/load system (localStorage)
- 📋 Settings & accessibility
- 📋 Performance optimization
- 📋 Balance adjustments based on playtesting

## How to Play

### Current Build
1. **Place Tiles**: Click empty grid cells to expand your space (costs 1 resource per tile)
2. **Remove Tiles**: Right-click to remove tiles and refund resources
3. **Manage Resources**: Watch your resource count in the top-left UI
4. **Strategic Placement**: Plan your grid layout—space is limited!

### Future Gameplay
- Select a placed tile to convert it into a resource generator
- Each generator type produces different resources at different rates
- Combine generators strategically for adjacency bonuses
- Harvest resources to afford more tiles and upgrades
- Prestige to reset and unlock new generators and mechanics

## Technical Details

### Architecture
- **Vanilla JavaScript** - No frameworks or external dependencies
- **HTML5 Canvas** - Efficient 2D rendering at 60fps
- **Modular design** - Easy to add new systems incrementally

### Game State Structure
```javascript
// Grid state
grid[row][col] = 0 // empty, 1 = filled

// Stats
stats = {
  tiles: number,           // Placed tiles count
  resources: number,       // Current resources
  // Future additions:
  // generators: {...},
  // production: {...},
  // prestige: {...}
}
```

### Key Systems (Roadmap)
1. **Grid System** ✅ (implemented)
2. **Placement Mechanics** ✅ (implemented)
3. **Resource System** ✅ (basic version)
4. **Generator System** 🚧 (next priority)
5. **Production Engine** 📋 (future)
6. **Upgrade System** 📋 (future)
7. **Prestige System** 📋 (future)
8. **Save/Load** 📋 (future)

## Development Roadmap

### Phase 1: Foundation ✅
- [x] Grid rendering and interaction
- [x] Basic resource management
- [ ] Playtesting & balance feedback

### Phase 2: Core Loop 🚧
- [ ] Tile type system (basic generator)
- [ ] Resource generation mechanics
- [ ] Production display
- [ ] Playtesting & iteration

### Phase 3: Depth 📋
- [ ] Multiple resource types
- [ ] Advanced tile types
- [ ] Upgrade system
- [ ] Adjacency mechanics

### Phase 4: Prestige 📋
- [ ] Prestige mechanics & UI
- [ ] Prestige upgrades
- [ ] New content unlocks

### Phase 5: Polish 📋
- [ ] Save/load system
- [ ] Settings and accessibility
- [ ] Balance refinement
- [ ] Performance optimization

## Contributing

Found a bug? Have a suggestion? Create an issue or pull request!

## Thanks

Special thanks to Katara for the support and inspiration!

---

**Current Status:** Tech Demo v0.1 - Grid foundation ready for playtesting
**Last Updated:** 2026-07-16
