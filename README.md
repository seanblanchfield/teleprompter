# Teleprompter App

A professional teleprompter application designed for full-screen presentation delivery. Built with HTML, CSS, and JavaScript, this app is optimized for use on a large screen or monitor while being controlled discretely from presentation remotes like the Logitech R400.

## 🚀 [Try the Live Demo](https://seanblanchfield.github.io/teleprompter)

## Presentation Setup

This teleprompter is designed to be used:
- **Full-screen mode** in your browser (press F11)
- **From a distance** - reading text displayed on a large screen or monitor
- **With presentation remotes** - control speed, font size, and playback without touching the computer
- **Hands-free operation** - deliver your speech naturally while making discrete adjustments from your pocket

The keybindings are specifically mapped to common presentation remote controls, allowing seamless operation during live presentations, video recording, or public speaking.

## Features

- **Script Upload**: Upload your own `.md` or `.txt` files with localStorage caching
- **Dynamic Font Sizing**: 16px to 144px with automatic margin adjustment
- **Speed Control**: Font-size adaptive speed scaling
- **Fast Forward/Rewind**: Long-press controls for quick navigation
- **Reading Line**: Visual guide that scales with font size
- **Professional Controls**: Comprehensive keyboard shortcuts
- **Touch Screen Support**: On-screen D-pad and drag scrolling for mobile devices

## Keyboard Controls

### Presentation Remote Compatible
These controls work with popular presentation remotes like the Logitech R400:

- **F5** - Start playing (standard presentation start key)
- **ESC** - Stop/pause (standard presentation exit key)
- **Page Up/Down** - Adjust speed (tap) / Rewind/Fast Forward (hold)
- **Period (.)** - Cycle through font sizes (16px → 144px for distance viewing)

### Additional Keyboard Controls
- **Space** - Toggle play/pause
- **R** - Reset to beginning and clear uploaded script from cache
- **← →** - Adjust font size (+/- 2px)
- **↑ ↓** - Adjust speed (tap) / Rewind/Fast Forward (hold)
- **H** - Hide/show controls

## Touch Screen Controls

For touch screen devices, an on-screen D-pad appears automatically:

- **▲ (Up)** - Decrease speed (tap) / Rewind (hold)
- **▼ (Down)** - Increase speed (tap) / Fast Forward (hold)
- **◀ (Left)** - Decrease font size
- **▶ (Right)** - Increase font size
- **▶/⏸ (Center)** - Play/pause toggle
- **Drag scrolling** - Touch and drag the script content to manually scroll

### Remote Control Usage
With a Logitech R400 or similar presentation remote:
1. **Black screen button** → ESC (pause/stop)
2. **Start presentation** → F5 (play)
3. **Next slide** → Page Down (increase speed or fast forward)
4. **Previous slide** → Page Up (decrease speed or rewind)
5. **Laser pointer** → Period (cycle font sizes for optimal distance viewing)

## Usage

1. Open `index.html` in your web browser and press **F11** for full-screen mode
2. Click **"Upload Script"** to select your own `.md` or `.txt` file (cached in localStorage)
3. Position yourself at your desired distance from the screen
4. Use your presentation remote or keyboard controls to operate the teleprompter
5. Adjust font size with the period key for optimal readability at your distance
6. Control playback speed discretely during your presentation
7. Press **R** to reset and clear your uploaded script from cache

## Script Management

- **Upload your own scripts**: Use the "Upload Script" button to load `.md` or `.txt` files
- **localStorage caching**: Your uploaded script is automatically saved and persists across sessions
- **Markdown support**: Full formatting including headers, bold, italic text
- **Reset functionality**: Press **R** to clear cached script and return to default content
- **Font optimization**: Font sizes automatically adjust margins for optimal viewing
- **Speed scaling**: Reading speed scales with font size for natural flow

## Deployment

This app works great as a GitHub Pages site or any static web hosting service.

## License

MIT License - Feel free to use and modify for your projects.
