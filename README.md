# Custom-Omarchy-Config

A small collection of configuration snippets for locking and statusbar setups used with Hyprland/Wayland environments.

Repository structure

- `hyprlock/` — contains `hyprlock.conf` (main lock configuration). Use this to configure the locker (colors, fonts, layout, etc.).
- `Original/` — a copy of the original `hyprlock.conf` kept for reference.
- `waybar/` — contains `config.jsonc` and `style.css` for Waybar (status bar) layout and styling.

Quick usage

1. Hyprlock
- Choose the configuration you want from `hyprlock/` (or `Original/` as a base).
- Place the chosen `hyprlock.conf` in your Hyprland locker's expected location (example path may be `~/.config/hyprlock/hyprlock.conf` or where your lock program reads it).
- Restart or reload your lock/locker service as required by your setup.

2. Waybar
- Copy `waybar/config.jsonc` and `waybar/style.css` into your Waybar configuration directory (commonly `~/.config/waybar/`).
- Restart Waybar to apply the changes (e.g., `pkill waybar && waybar &`).

Notes

- These files are intended as examples and starting points. Tweak fonts, colors, module order, and modules to match your system and preferences.
- This repo does not include binaries or installers — only config files.

Contributing

Feel free to open issues or submit pull requests with improvements, alternative layouts, or notes about compatibility with specific Hyprland/Waybar versions.

License

No license specified. If you want this repo licensed, add a `LICENSE` file.
