# X_AI_Ships - Cosmoteer AI Core Mod

A Cosmoteer mod that enhances ships with AI cores that can operate nearby parts autonomously.

## Features

- **AI Cores**: Multiple sizes of AI cores that operate parts within a 2-tile radius
- **Crew Replacement**: AI cores can replace crew requirements for compatible parts
- **Multi-Core Support**: Multiple AI cores can work together for parts requiring more crew
- **Seamless Integration**: Works with existing ship designs without requiring redesigns
- **Mod Compatibility**: Supports vanilla parts and many popular mods

## AI Core Types

### Single Core (1x1)
- **Capacity**: Replaces 1 crew member
- **Range**: 2-tile radius
- **Requirements**: Control Room Large + Sensor Array
- **Cost**: 15,000 credits

### Large Core (4x4)
- **Capacity**: Replaces 4 crew members
- **Range**: 2-tile radius
- **Requirements**: Single AI Core
- **Cost**: 300,000 credits

### Behemoth Core (7x7)
- **Capacity**: Replaces 8 crew members
- **Range**: 2-tile radius
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
- **Federation Ships**: Bridge automation
- **Galactic Allegiance**: Enhanced automation features
- **Starforge**: Specialized automation components

## Installation

1. Download the mod files
2. Place them in your Cosmoteer mods directory:
   - **Windows**: `%USERPROFILE%\Saved Games\Cosmoteer\[SteamID]\Mods\`
   - **Linux**: `~/.local/share/Cosmoteer/[SteamID]/Mods/`
   - **Mac**: `~/Library/Application Support/Cosmoteer/[SteamID]/Mods/`
3. Enable the mod in Cosmoteer's mod manager
4. Start a new game or load an existing save

## How It Works

AI cores use a buff system to detect nearby parts and automatically provide crew functionality. When an AI core is placed within 2 tiles of a compatible part:

1. The AI core applies an `Aredja2AITerminal` buff to nearby parts
2. Compatible parts detect this buff and reduce their crew requirements
3. Multiple AI cores can stack to handle parts requiring more crew
4. The system works seamlessly with existing ship designs

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

This mod is provided as-is for the Cosmoteer community. Feel free to use, modify, and distribute as needed.

## Credits

- **Original Inspiration**: Aephix's AI Core mod
- **Development**: Jared Hale
- **Community Support**: Cosmoteer modding community

## Version History

- **v1.0.0**: Initial release with vanilla part support
- **v1.1.0**: Added Laser Emporium compatibility
- **v1.2.0**: Enhanced General Munitions support
- **v1.3.0**: Improved multi-core functionality and bug fixes 