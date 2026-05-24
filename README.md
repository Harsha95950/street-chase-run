# Street Chase Runner 🏃‍♂️

A 3D endless runner game built with Three.js where you play as a clever street thief escaping from police through a vibrant urban environment.

## Features

### Core Gameplay
- **Endless runner** with 3-lane switching, jumping, sliding, and dodging
- **Police chase system** - police officer continuously chases you, getting closer when you hit obstacles
- **Smooth character animations** - running, jumping, sliding, and lane switching

### Obstacles
- Cars (various colors)
- Buses
- Auto rickshaws
- Motorcycles
- Road barriers (jump over)
- Traffic cones (jump over)
- Construction gates (slide under)
- Street vendor carts
- Construction zones
- Potholes

### Collectibles & Power-ups
- **Coins** - scattered in patterns (lines, arcs, clusters)
- **Treasure Chests** - contain coins, character cards, and gems
- **Power-ups:**
  - 👻 Invisibility - become invisible to police
  - ⬆️ Super Jump - higher jumps over obstacles
  - ⚡ Speed Boost - temporary fast sprint
  - 🧲 Magnet - attract coins automatically
  - 🛡️ Shield - protect from one collision

### Characters (unlock with 12 cards each)
- **Street Thief** - Default runner
- **Street Hacker** - +20% coin magnet range
- **Parkour Expert** - +30% jump height
- **Bike Messenger** - +15% speed boost duration
- **Masked Thief** - +25% invisibility duration
- **Night Runner** - +20% score at night

### Environment
- Procedurally generated city streets with buildings, sidewalks, and road markings
- Day/night cycle with dynamic lighting
- Street lights that activate at night
- Trees and urban decorations

### Progression
- Score and distance tracking with personal best records
- Daily missions with coin rewards
- Character unlock system via card collection
- Increasing difficulty over time
- Persistent save data (localStorage)

### Audio
- Synthesized sound effects for all actions
- Background music loop
- Police siren sounds

## Controls

### Keyboard
- **←/A** - Move left
- **→/D** - Move right
- **↑/W/Space** - Jump
- **↓/S** - Slide
- **Escape/P** - Pause

### Mobile (Touch)
- **Swipe Left** - Move left
- **Swipe Right** - Move right
- **Swipe Up** - Jump
- **Swipe Down** - Slide
- **Tap** - Jump

## How to Play

1. Open `index.html` in a modern web browser
2. Click **PLAY** to start running
3. Dodge obstacles by switching lanes, jumping, or sliding
4. Collect coins and treasure chests
5. Grab power-ups for special abilities
6. Don't let the police catch you!

## Tech Stack
- **Three.js** (r128) - 3D rendering
- **Web Audio API** - Sound effects and music
- **Vanilla JavaScript** - Game logic
- **CSS3** - UI and animations
- **LocalStorage** - Save data persistence

## Browser Support
- Chrome (recommended)
- Firefox
- Safari
- Edge
- Mobile browsers with WebGL support

## License
MIT
