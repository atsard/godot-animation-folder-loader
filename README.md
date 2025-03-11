# godot-animation-folder-loader
A Godot plugin to easily load animations from folders

# Animation Folder Loader

A Godot plugin that simplifies the process of creating animations in AnimatedSprite2D nodes by loading frames from folders.

## Features

- Load multiple animations from a folder structure
- Automatically creates animations from folder names
- Recursively explores subfolders
- Configurable FPS for all loaded animations
- Automatically disables loop for all animations
- Supports PNG, JPG, and JPEG formats

## Installation

1. Download the latest release
2. Extract the `addons` folder into your project
3. Enable the plugin in Project Settings -> Plugins

## Usage

1. Select an AnimatedSprite2D node in your scene
2. Find the "Animation Folder Loader" section in the Inspector
3. Set your desired FPS (default: 24)
4. Click "Load Animation Folder" and select your root animations folder
5. The plugin will automatically create animations from your folder structure

### Example Folder Structure

animations/
├── idle/
│ ├── frame1.png
│ └── frame2.png
└── run/
├── frame1.png
└── frame2.png

Each folder containing images will become an animation with the folder's name.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
