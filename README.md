# Rounded Window Corners

Fork of [flexagoon/rounded-window-corners](https://github.com/flexagoon/rounded-window-corners),
which continues [yilozt/rounded-window-corners](https://github.com/yilozt/rounded-window-corners).

## What this fork updates

- Adds GNOME Shell 50 support
- Hardens `metaWindow`, overview, and workspace-switch handling to avoid null-reference crashes
- Improves overview shadow and workspace-switch safety on newer GNOME Shell versions
- Fixes leaked transient shadow bindings that could contribute to long-session memory or VRAM growth
