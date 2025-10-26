# SYN Recruitment Video

A cinematic terminal experience that tells the story of the SYN team's response to a crisis. This is a feature being integrated into the Nexus CLI.

## Overview

The SYN recruitment video is a terminal-based cinematic experience built with Rust and `ratatui`. It creates an engaging terminal UI that tells a story through:

- Real-time system monitoring interface
- Activity log with character dialogues
- Progressive visual effects and animations
- ASCII art and emojis for visual storytelling
- Smooth character-by-character typing animations

## Features

### Terminal UI Experience

The SYN recruitment video provides a full-screen terminal interface featuring:

- **System monitoring panels** - CPU and memory metrics
- **Activity log** - Story progression with speaker tags
- **Main screen** - Character dialogues and visual elements
- **Team metrics** - Progress tracking with live statistics
- **Visual effects** - Progressive screen transitions and animations

### Story Elements

The experience tells the story of the SYN team through:

- Character dialogues shown in the activity log
- Terminal UI panels showing different system views
- Visual ASCII art and animations
- Progressive visual effects (rockets filling the screen)
- Final fade to black with SYN logo display

## Technical Details

- **Language**: Rust
- **UI Framework**: ratatui
- **System Monitoring**: sysinfo
- **Duration**: ~13-15 seconds
- **Animation**: Character-by-character typing with audio feedback

## Files

- `clients/cli/src/ui/syn_recruit/mod.rs` - Main implementation
- `clients/cli/USAGE_SYN.md` - Detailed usage guide

## Technical Implementation

### State Management

The `SynRecruitState` struct manages:
- Current scene and timing
- System metrics
- Typing animation state
- Activity log entries
- Visual effect progressions

### Rendering Pipeline

- `render_syn_recruit()` - Main entry point
- `render_normal_ui()` - Standard UI rendering
- `render_progressive_fade()` - Final screen transition
- Various panel renderers for each UI component

### Animation System

- Character-by-character typing with configurable speed
- Real-time system metrics updates
- Progressive visual effects (rocket fill, fade transitions)
- Tick-based animation for smooth movement

## Usage

This feature is currently being integrated into the Nexus CLI. Once integrated, it will be accessible as part of the terminal UI experience.

See [USAGE_SYN.md](clients/cli/USAGE_SYN.md) for detailed documentation.

## Controls

- **Q** - Exit the experience at any time
- The video runs automatically from start to completion

## Contributing

This is a feature addition to the Nexus CLI project. To contribute:

1. Review the code in `clients/cli/src/ui/syn_recruit/mod.rs`
2. Check the integration points in the main Nexus CLI
3. Submit pull requests to the main repository

## License

Licensed under both MIT and Apache 2.0 licenses, same as the Nexus CLI project.

## Related

- [Nexus Network](https://nexus.xyz/)
- [Nexus CLI](https://github.com/nexus-xyz/nexus-cli)
