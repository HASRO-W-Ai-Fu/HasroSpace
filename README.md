
```markdown
# HasroSpace – My Custom Hyprland Setup

Welcome to **HasroSpace**! This is my personalized Hyprland configuration repository, built for both productivity during the day and smooth gaming performance at night. This setup is optimized for a minimal aesthetic, smooth transitions, and a distraction-free workspace.

## 🚀 Features
- **Hyprland**: Dynamic tiling window manager optimized for performance and aesthetics.
- **Waybar**: A clean and customizable bar for system info and notifications.
- **Kitty**: Fast terminal emulator with custom settings.
- **Wallpaper**: Custom wallpaper collection for a personalized desktop environment.
- **Custom Scripts**: Includes `pipes.sh`, a terminal-based graphical animation for your terminal.

## 📥 Installation

1. **Clone the Repository**  
   Clone the repository into your `.config` directory:
   ```bash
   git clone https://github.com/HASRO-W-Ai-Fu/HasroSpace.git ~/.config/HasroSpace
   ```

2. **Run the Setup Script**  
   Navigate to the folder and execute the setup script:
   ```bash
   cd ~/.config/HasroSpace
   chmod +x install.sh
   ./install.sh
   ```

3. **Reload Hyprland**  
   After the installation, restart or reload Hyprland for the changes to take effect.

## 🖼️ Screenshots
Check out some of the visuals of my setup:

![Screenshot 1](screenshots/1.png)
![Screenshot 2](screenshots/2.png)
![Screenshot 3](screenshots/3.png)
![Screenshot 4](screenshots/4.png)
![Screenshot 5](screenshots/5.png)
![Screenshot 6](screenshots/6.png)


## 📋 Requirements
Ensure you have these tools installed:
- [Hyprland](https://github.com/hyprwm/Hyprland)
- [Waybar](https://github.com/Alexays/Waybar)
- [Kitty](https://sw.kovidgoyal.net/kitty/)

Use your package manager to install them.

## 🛠️ Customization
Feel free to modify any of the config files to suit your preferences. Each file is well-commented to help you understand and personalize it.

## 🔑 Keybindings

### Essential Keys
- `Mod` key is set to `Super` (Windows/Meta key)
- `Alt` key for alternate functions
- `Shift` key for additional operations
- `Ctrl` key for control operations

### Applications
- **Mod + Return**: Launch terminal
- **Mod + Shift + Return**: Launch terminal in floating mode
- **Mod + T**: Open file manager (Dolphin)
- **Mod + S**: Launch web browser (Firefox)
- **Mod + Shift + E**: Open VS Code
- **Mod + E**: Launch emoji picker

### Window Management
- **Mod + Q**: Close active window
- **Mod + F**: Toggle fullscreen
- **Mod + Space**: Toggle floating mode and center window
- **Mod + P**: Toggle pseudo mode
- **Alt + Tab**: Cycle through windows
- **Mod + Tab**: Change active group
- **Mod + N**: Minimize window

### Window Movement
- **Mod + Arrow Keys**: Change focus
- **Mod + Shift + Arrow Keys**: Move active window
- **Mod + Ctrl + Arrow Keys**: Resize active window
- **Mod + Alt + Arrow Keys**: Move floating window
- **Mod + Mouse Left**: Move window
- **Mod + Mouse Right**: Resize window

### Workspaces
- **Mod + (1-0)**: Switch to workspace 1-10
- **Mod + Shift + (1-8)**: Move active window to workspace 1-8
- **Mod + Shift + Equal**: Move to special workspace
- **Mod + Equal**: Toggle special workspace

### Rofi Menus
- **Mod + D**: App launcher
- **Mod + R**: Run menu
- **Mod + M**: Music control
- **Mod + L**: Power menu
- **Mod + A**: Screenshot menu

### Screenshots
- **Print**: Take screenshot now
- **Alt + Print**: Screenshot in 5s
- **Shift + Print**: Screenshot in 10s
- **Ctrl + Print**: Screenshot active window
- **Mod + Print**: Screenshot selected area

### Media Controls
- **F10/XF86AudioMute**: Toggle mute
- **F11/XF86AudioLowerVolume**: Volume down
- **F12/XF86AudioRaiseVolume**: Volume up
- **XF86AudioPlay**: Play/Pause
- **XF86AudioNext**: Next track
- **XF86AudioPrev**: Previous track

### System Controls
- **Ctrl + Alt + Delete**: Exit Hyprland
- **Ctrl + L**: Lock screen
- **Mod + B**: Toggle Waybar
- **Mod + Shift + B**: Toggle blur settings
- **Mod + Shift + G**: Toggle game mode
- **Mod + Alt + L**: Toggle layout (Master/Dwindle)
- **Mod + Alt + O**: Toggle window opacity

### Custom Scripts
- **Mod + W**: Select wallpaper
- **Mod + Shift + W**: Wallpaper effects
- **Ctrl + Alt + W**: Random wallpaper
- **Mod + Shift + M**: Online music menu
- **Mod + X**: Color picker
- **Mod + P**: Run `pipes.sh` (terminal-based graphical animation)

### Function Keys
- **XF86MonBrightnessUp**: Increase brightness
- **XF86MonBrightnessDown**: Decrease brightness
- **XF86AudioMicMute**: Toggle microphone

### Misc
- **Mod + Shift + P**: Toggle pin window
- **Mod + Shift + S**: Swap with next window

## 📜 License
This setup is shared under the MIT License. Feel free to use, modify, and share!

---

Thanks for checking out **HasroSpace**! Let me know if you have any questions or suggestions.
```

I’ve added a section for `pipes.sh` under **Custom Scripts** in the keybindings. You can customize the file further by adding other scripts you might have.
