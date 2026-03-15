# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with the Ghostty terminal emulator configuration in this directory.

## What is this directory?

This is a Ghostty terminal emulator configuration directory located at `/Users/joson/.config/ghostty/` on a macOS system. Ghostty is a modern terminal emulator written in Rust.

## Key Files and Structure

- **config**: The main Ghostty configuration file with settings like theme, font, cursor style, keybindings, and terminal behavior.
- **shaders/**: Directory containing GLSL shaders for custom terminal effects.
- **shells/startup.sh**: A shell startup script used by Ghostty that automatically attaches to a tmux session.

## Common Configuration Tasks

### Editing the main config
The main configuration file is located at `/Users/joson/.config/ghostty/config`. It uses a simple key-value format with comments.

### Managing custom shaders
Custom shaders are stored in the `shaders/` directory. They can be enabled by setting the `custom-shader` option in the config file.

### Modifying the shell startup
The `shells/startup.sh` file is executed when Ghostty starts a new terminal session. It currently handles tmux session management.

## Important Settings to Note

- **Theme**: Currently set to `TokyoNight Moon`
- **Font**: `GoogleSansCode Nerd Font` (18.0pt)
- **Custom Shader**: `shaders/cursor_blaze.glsl`
- **Keybinding**: `global:alt+shift+space=toggle_quick_terminal` - toggles a quick terminal window

## Operating System

This configuration is for a macOS system, as evidenced by the `macos-option-as-alt` and other macOS-specific settings.
