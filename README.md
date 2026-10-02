# Silog X — Blade Ball Script

A feature-packed Blade Ball script with Auto Parry, Spam systems, ESP, Immortal/Desync systems, Auto Play, Ability exploits, FastFlag presets, and multiple customization options.

## ⚔️ Combat

### Auto Parry
- Auto Parry
- Adjustable Accuracy: 1–100%
- Custom Auto Parry Keybind
- Animation Fix
- Parry Boost
- Humanizer / Random Parry Accuracy
- Humanizer Minimum Accuracy
- Humanizer Maximum Accuracy
- Ping-aware parry calculations
- Curved-ball detection
- Target-based ball detection
- Training Ball support
- Multiple parry execution methods
- Safe Mode

### Parry Curve Directions
- Camera
- Random
- Accelerated
- Backwards
- Slow
- High
- Left
- Right
- Straight
- Random Target
- Forward
- Up
- Down

### Special Ball / Ability Detection
- Infinity Detection
- Death Slash Detection
- Time Hole Detection
- Slashes of Fury Detection
- Forcefield Detection
- Phantom Detection
- Singularity Detection
- Dribble Detection
- Pull Detection
- Pulse Detection
- Tornado Detection
- Anti Hell Hook

### Slashes of Fury
- Detection toggle
- Adjustable maximum parry count
- Adjustable parry delay

### Lobby Auto Parry
- Lobby Auto Parry
- Adjustable Accuracy
- Lobby Animation Fix

### Auto Spam Parry
- Auto Spam Parry
- Adjustable Spam Reach
- Self Arm
- Adjustable Parry Threshold
- Animation Fix
- Speed / Distance-based spam detection internally
- Ping-aware spam calculations
- Automatic spam activation based on ball/player distance

### Manual Spam Parry
- Manual Spam mode
- Floating SPAM UI
- Custom keybind
- Animation Fix
- CPS Mode
- Adjustable CPS
- Up to 2000 CPS
- Burst-style parry execution
- Mobile CPS limiting/support

### Trigger Bot
- Trigger Bot
- Detects balls targeting the local player
- Floating Trigger Bot UI
- Custom keybind
- Animation Fix
- Infinity Detection option

## 📊 Spam / Performance Tracking
- Live Loop RPS counter
- Spam accumulator display
- Target RPS setting
- Reset accumulator button
- Burst-based spam system
- High-speed direct parry execution

The Settings tab includes the spam controls, parry method, curve settings, Safe Mode, animation settings, FPS boost, configuration reset, cache clearing, and unload controls.

## 🎯 Parry Boost
- Parry Boost engine
- Pre-Click Multiplier
- Distance timing adjustment
- Time-based parry mode
- Distance-based parry mode
- Adjustable Time Mode Window
- Hit Sound
- Multiple hit sound choices:
  - UwU
  - Medal
  - Piu
  - Keyboard
  - Pop
  - Ding
- Built-in parry lock to prevent repeated normal firing
- Ping-aware timing

The Parry Boost UI exposes Distance/Time modes, timing controls, hit sounds, and the pre-click multiplier.

## 💥 Spam Boost / Burst System
- Triggerbot Burst
- No-cooldown triggerbot burst mode
- Adjustable Triggerbot Burst Count
- Manual Spam Burst
- Adjustable Manual Spam Burst Count
- Manual Spam Speed
- Auto Spam Burst
- Adjustable Auto Spam Burst Count
- Direct parry-hook burst execution
- High-speed clash/spam mode
- Burst firing on top of the normal spam loop

The script explicitly separates Triggerbot Burst, Manual Spam Burst, and Auto Spam Burst controls.

## 👁️ ESP / Visuals

### Player ESP
- Player ESP
- Always-on-top player highlighting
- Distance ESP
- Displays player distance
- Rainbow ESP

### Ball ESP
- Ball ESP
- Ball highlighting
- Ball distance display
- Ball Speed Tracker
- Current ball speed
- Peak ball speed tracking
- Rainbow-compatible ball visuals

### Ability ESP
- Ability ESP
- Ability icon
- Ability name
- Live cooldown display
- Ready / Passive / cooldown state
- Guardian Angel usage count

### Winstreak Spoofer
- Winstreak Spoofer
- Custom winstreak value
- Draggable winstreak interface
- Apply custom streak
- Value 0 can hide the display
- Re-applies display during character lifecycle

The ESP section contains Player ESP, Distance ESP, Rainbow ESP, Ball ESP, Ball Speed Tracker, Ability ESP, and the Winstreak Spoofer.

## 📢 Kill Announcer
- Custom Win Message
- Custom Kill Message
- Editable win text
- Editable kill text
- Automatically keeps the custom text applied to the announcer UI

The Kill Announcer directly provides separate editable Win and Kill message fields.

## 🛡️ Immortal Systems

### Silog X Semi Immortal
- Semi Immortal / desync system
- Floating draggable control panel
- Smart Desync
- Automatic panel arming
- Ball classification system
- Slow / Medium / Fast ball classes
- Class-specific response behavior
- Curve-ball detection
- Curve Boost
- Miss Boost
- ETA / lead-window handling
- Separate hold times for Slow, Medium, and Fast threats
- Tunable oscillation settings
- Tunable sweep range
- Tunable speed thresholds
- Tunable curve turn detection
- Persistent tuning settings
- Long-duration desync holds

### Semi Immortal Tuning
- Oscillation Radius
- Oscillation Height
- Velocity Spike
- Smart Desync
- Sweep Range
- Slow Class Cap
- Fast Class Floor
- Lead Window
- Hold Slow
- Hold Medium
- Hold Fast
- Curve Turn
- Curve Boost
- Miss Boost

The script's own UI description identifies the Semi Immortal system as a hardened desync engine with separate Slow/Medium/Fast responses, curve handling, miss handling, and configurable hold durations.

### EclipseImmortal
- EclipseImmortal
- Angle-based desync
- Adjustable Angle
- Adjustable Height
- Adjustable Depth
- Adjustable Square Radius
- Speed Bypass

### Silog X v2
- Alternate immortal/desync system
- Orbit-style positioning
- Configurable Radius
- Configurable Height
- Visualizer
- Custom Visualizer Color
- Automatic conflict prevention between immortal systems
- Built-in visual position marker

The script contains three separate immortal systems and automatically stops the others when one is enabled. 

## 🔓 Silog X Unlock All
- Unlock All system
- Sword switching
- Explosion / kill-effect switching
- Sword model application
- Sword animation application
- Sword FX / slash effect application
- Custom Sword / Explosion name input
- Apply / Equip Everything button
- Automatically re-equips after respawn
- Custom FX replacement support

The Unlock All section accepts a sword/explosion name, applies the selected model/animation/FX, and re-equips it after respawn. 

## 📡 FPS & Ping
- FPS & Ping overlay
- Live FPS counter
- Live Ping counter
- Mobile-sized overlay layout
- Desktop-sized overlay layout
- Color-coded FPS status
- Color-coded Ping status
- Draggable overlay

The dedicated Ping Checker overlay displays live FPS and ping and can be dragged around the screen.

## ⚙️ Animation System
- Automatic Grab Parry animation
- Sword-specific parry animation detection
- Animation caching
- Animation Fix
- Spam animation handling
- Animation rate control
- Max animation rate up to 240 FPS
- Spam FE mode
- Animation cleanup after successful parry
- Animation synchronization with parry systems

## 🧰 Utilities / Maintenance
- FPS Boost
- Reset Config
- Clear Cache
- Unload Script
- Persistent settings
- Automatic settings loading
- Automatic settings saving
- Configuration stored in `Silog XSetting.json`

The script saves and loads configuration data from a local JSON settings file and includes Reset Config, Clear Cache, and Unload controls. 

## 💀 Blatant Features

### Movement
- Infinite Jump

### Camera
- Field of View toggle
- Adjustable FOV
- FOV range: 40–120

### Player Follow
- Player Follow
- Selectable player target
- Walk mode
- Teleport mode
- Adjustable Walk Distance
- Adjustable Teleport Distance
- Adjustable Teleport Interval
- Automatically refreshes player list

### Cosmetics
- Korblox
- Headless
- Character respawn support for both cosmetics

### Abilities
- Ability Exploit
- Thunder Dash No Cooldown
- Super Jump No Cooldown
- Dash No Cooldown
- Cooldown Protection
- Automatic ability button activation while parry is on cooldown

### Target Lock
- Target Lock
- Select specific target player
- Auto Switch
- Target Highlight
- Locks parry targeting to selected player
- Automatically falls back to another player when needed

### Auto Play
- Auto Play
- Anti AFK
- Optional Jumping
- Auto Vote
- Ball-distance control
- Speed multiplier
- Transversing control
- Movement Direction
- Offset Factor
- Movement Duration
- Generation Threshold
- Jump Chance
- Double Jump Chance
- Curved movement behavior
- Speed-scaled movement around the ball

The Blatant tab contains the movement, camera, follow, cosmetics, ability, target lock, and Auto Play systems listed above.

## 🚩 FastFlags

### FastFlag Preset Categories
- Blade Ball
- FPS / Frame Rate
- Network / Ping
- Graphics / Rendering
- Shadows / Lighting
- Textures / Materials
- Physics / Simulation
- Animations
- Telemetry / Analytics
- UI / Menu
- Client Fixes

### FastFlag Controls
- Toggle individual categories
- Category descriptions
- Apply Selected Categories
- Apply ALL Categories
- Reset Selected to Default
- Automatic skipped-flag handling
- Respawn reminder
- Warning for potentially conflicting flag combinations

### Total FastFlags
- **374 FastFlags** across all categories

The script contains 374 flags distributed across 11 preset categories. 

## 🖥️ UI / Quality-of-Life
- Dark themed interface
- Resizable main window
- Main UI toggle keybind
- Multiple organized tabs
- Floating draggable utilities
- Toggle notifications
- Mobile-aware behavior
- Separate floating SPAM UI
- Separate Trigger Bot UI
- Ball statistics overlay
- Client statistics overlay
- FPS / Ping monitoring
- Persistent configuration

### Main Tabs
- Combat
- Settings
- Silog X
- ESP
- Immortal
- Parry Boost
- Spam Boost
- Blatant
- FastFlags

## 🔧 Engine / Technical Features
- Advanced parry remote hooking
- Automatic parry-function discovery
- Automatic remote discovery
- Token generation / refresh
- Multiple fallback parry execution systems
- Server-time-based token handling
- Ping smoothing and caching
- Dynamic ball velocity analysis
- Curved trajectory analysis
- Screen-position tracking
- Mouse / cursor target tracking
- Mobile center-screen parry targeting
- Automatic remote rescanning
- Remote re-hooking when new remotes appear
- Character / ball / runtime cache management
- Automatic cleanup on unload
- Multiple fallback systems for parry execution

The script also verifies executor support before starting and stops with an unsupported-executor notification when required functions are unavailable. 
