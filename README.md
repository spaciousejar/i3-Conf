# This is my i3 Configuration

This configuration file is tailored for the i3 window manager, offering a highly customizable and efficient way to manage windows on your desktop.

**Key Features:**

* **Layout Management:** i3 supports various layout options, including tiling, floating, and tabbed layouts. This configuration is optimized for a tiling layout, ensuring maximum screen space utilization and minimal window overlap.
* **Keyboard Focus:** i3 is designed to be highly keyboard-centric, enabling quick and efficient navigation and management of windows using keyboard shortcuts.
* **Customization:** This configuration includes a range of customizations, including custom keybindings, font settings, and color schemes, to create a unique and personalized desktop environment.

**Keybindings:**

* **Applications:**
	+ `super + Return`: Open terminal (alacritty)
	+ `super + shift + Return`: Open floating terminal
	+ `super + alt + Return`: Open fullscreen terminal
	+ `super + shift + F`: Open file manager (thunar)
	+ `super + shift + E`: Open text editor (geany)
	+ `super + shift + W`: Open web browser (firefox)
* **Menu and Applets:**
	+ `super`: Open application launcher
	+ `alt + F1`: Open application launcher
	+ `super + N`: Open network manager applet
	+ `super + M`: Open music applet
	+ `super + X`: Open powermenu applet
	+ `super + S`: Open screenshots applet
	+ `super + R`: Open apps as root applet
	+ `super + T`: Open theme applet only in premium
	+ `super + W`: Open window applet
* **Hardware Keys:**
	+ `Print`: Take screenshot
	+ `ctrl + Print`: Take screenshot in 5 seconds delay
	+ `shift + Print`: Take screenshot in 10 seconds delay
	+ `ctrl + shift + Print`: Take screenshot of currently focused window
	+ `super + Print`: Take screenshot of selected area
	+ `XF86AudioRaiseVolume`: Increase volume
	+ `XF86AudioLowerVolume`: Decrease volume
	+ `XF86AudioMute`: Toggle mute speakers
	+ `XF86AudioMicMute`: Toggle mute microphone
	+ `XF86Audio + Next/Prev/Play/Stop`: Media controls (MPD)
	+ `XF86MonBrightnessUp`: Increase display brightness
	+ `XF86MonBrightnessDown`: Decrease display brightness
* **Workspaces:**
	+ `super + 1..10`: Switch to respective workspace
	+ `super + shift + 1..10`: Move focused container to respective workspace
	+ `super + ctrl + Left/Right`: Move a container to the next/previous workspace
	+ `super + B`: Switch workspaces back-and-forth
	+ `super + shift + B`: Move container to workspace back-and-forth
* **Window Management:**
	+ `super + C/Q`: Close focued window
	+ `super + H/V`: Split in horizontal/vertical orientation
	+ `super + shift + S`: Set stacking layout
	+ `super + shift + T`: Set tabbed layout
	+ `super + shift + D`: Set default layout
	+ `super + shift + L`: Toggle between stacking/tabbed/split
	+ `super + shift + V`: Toggle between horizontal/vertical
	+ `super + shift + O`: Sticky floating windows
	+ `super + F`: Toggle fullscreen
	+ `super + Space`: Toggle floating/tiling
	+ `super + shift + Space`: Toggles focus between floating/tiling containers
	+ `super + Left/Right/Up/Down`: Sets focus to the nearest container in the given direction
	+ `super + shift + Left/Right/Up/Down`: Move focused window in the given direction
	+ `super + Y`: Changing border style
	+ `super + A`: Sets focus to the parent container
	+ `super + D`: Sets focus to the child container
	+ `super + Tab`: Automatically sets focus to the adjacent container
	+ `super + alt + C`: Move floating container to the center of all outputs
	+ `super + alt + P`: Move floating container to the current position of the cursor
	+ `super + alt + Left/Right/Up/Down`: Resizing containers/windows
	+ `super + Minus`: Make the currently focused window a scratchpad
	+ `super + shift + Minus`: Show the first scratchpad window
	+ `super + shift + R`: Toggle Resize mode
	+ `super + shift + M`: Toggle Resize mode
	+ `super + shift + G`: Toggle Gaps mode
* **Window Manager:**
	+ `ctrl + shift + R`: Restart i3wm
	+ `super + shift + C`: Reload i3wm
	+ `super + shift + Q`: Quit i3wm
* **Misc Keys:**
	+ `ctrl + alt + V`: Open vim in terminal
	+ `ctrl + alt + R`: Open ranger in terminal
	+ `ctrl + alt + H`: Open htop in terminal
	+ `ctrl + alt + M`: Open ncmpcpp with album art in terminal
	+ `ctrl + alt + L`: Trigger lockscreen
	+ `super + P`: Run colorpicker

**Customization:**

* **Colors:** The color scheme in this configuration is designed for visual appeal and ease on the eyes. It includes a range of colors for different elements, such as the background, foreground, and accents.
* **Fonts:** The font used in this configuration is the JetBrainsMono Nerd Font, known for its high customizability and readability.
* **Layout:** The layout is optimized for a tiling layout, prioritizing screen space maximization and window overlap minimization.
