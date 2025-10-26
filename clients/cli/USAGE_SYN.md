# SYN Recruitment Video - Usage Guide

## Overview
The SYN recruitment video is a terminal-based cinematic experience that tells the story of the SYN team's response to a crisis. 

**Note**: This feature is currently being integrated into the CLI. Once complete, it will be accessible from the main Nexus CLI interface as part of the TUI experience.

## Status
The SYN recruitment video module (`clients/cli/src/ui/syn_recruit/mod.rs`) provides:

- Real-time system monitoring interface
- Activity log with character dialogues  
- Progressive visual effects and animations
- ASCII art and emojis for visual storytelling
- Smooth character-by-character typing animations

## What You'll See

The experience includes:
- **System monitoring interface** - Real-time CPU and memory usage
- **Activity log** - Story progression through log entries
- **Main screen** - Character dialogues and visual elements
- **Team metrics** - Progress tracking and statistics

## Controls

- **Q** - Exit the experience at any time
- The video runs automatically and completes in approximately 13-15 seconds

## Story Elements

The experience tells the story through:
- Terminal UI panels showing different system views
- Character dialogues shown in the activity log
- Visual ASCII art and animations
- Progressive visual effects and transitions

## Technical Details

- Built with `ratatui` for terminal UI rendering
- Uses real system metrics for authenticity
- Features smooth character-by-character typing animations
- Includes audio feedback for user interactions

