# X_AI_Ships - Cosmoteer AI Core Mod

A Cosmoteer mod that enhances ships with AI cores that can operate nearby parts autonomously.

## Features

- **AI Cores**: Multiple sizes of AI cores that operate parts within a 2-tile radius
- **Crew Replacement**: AI cores can replace crew requirements for compatible parts
- **Multi-Core Support**: Multiple AI cores can work together for parts requiring more crew
- **Mod Compatibility**: Supports vanilla parts and several popular mods

## AI Core Types

### Single Core (1x1)
- **Capacity**: Replaces 1 crew member
- **Range**: Facing the designated part
- **Requirements**: Control Room Large + Sensor Array
- **Cost**: 15,000 credits

### Large Core (4x4)
- **Capacity**: Replaces 2 crew members
- **Range**: BuffArea = [-6, -6, 16, 16]
- **Requirements**: Single AI Core
- **Cost**: 300,000 credits

### Behemoth Core (7x7)
- **Capacity**: Replaces 8 crew members
- **Range**: BuffArea = [-14, -14, 35, 35]
- **Requirements**: Large AI Core
- **Cost**: 1,500,000 credits

## Compatible Mods

### Vanilla Parts
- All crewed weapons (laser blasters, cannons, missile launchers, etc.)
- Resource collectors
- Sensor arrays
- Tractor beam emitters
- Control rooms
- And many more!

### Mod Support
- **Laser Emporium**: Full automation support for all weapons
- **General Munitions**: Support for machine guns, mortars, and artillery
- **Modular Missiles**: Compatibility with missile systems
- **Federation Ships**: Broken since 0.30.0 update.
- **Galactic Allegiance**: All components before update. GA needs to be updated
- **Starforge**: All components

## Installation

1. Download the mod files
2. Place them in your Cosmoteer mods directory:
   - **Windows**: `%USERPROFILE%\Saved Games\Cosmoteer\[SteamID]\Mods\`
   - **Linux**: `~/.local/share/Cosmoteer/[SteamID]/Mods/`
   - **Mac**: `~/Library/Application Support/Cosmoteer/[SteamID]/Mods/`
3. Enable the mod in Cosmoteer's mod manager
4. Start a new game or load an existing save

## How To Add Working AI Parts Yourself
1. Follow 'how to make compatible.txt'
2. Add the files and test your local version the best you can. When You are sure nothing is crashing, create a pull request with your updated files. I will review when I am able. Good Luck!

## Development

This mod is inspired by Aephix's AI Core mod and maintains compatibility with supported mods. If you find any compatibility issues, please report them.

### File Structure
```
X_AI_Ships/
├── mod.rules                 # Main mod configuration
├── automation_components_*/   # Automation logic for different mods
├── single_core/              # 1x1 AI core
├── large_core/               # 4x4 AI core
├── behemeth_core/            # 7x7 AI core
├── strings/                  # Localization files
└── logo.png                  # Mod logo
```

## Contributing

Contributions are welcome! Please feel free to:
- Report bugs or compatibility issues
- Suggest new features
- Submit pull requests for improvements
- Help with mod compatibility testing

## License

This mod is provided as-is for the Cosmoteer community. Feel free to use, modify, and distribute as needed. Just give a callout to Aephix and myself if you use this mod's files for your own project.

## Credits

- **Original Inspiration**: Aephix's AI Core mod
- **Development**: aredja2

## Version History

- **v1.0.0**: Initial release with vanilla part support
- **v1.1.0**: Added Laser Emporium compatibility
- **v1.2.0**: Enhanced General Munitions support
- **v1.3.0**: Improved multi-core functionality and bug fixes 