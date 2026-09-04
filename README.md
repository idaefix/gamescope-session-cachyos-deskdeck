This fork is mostly a personal setup and learning attempt. Any relevant suggestion or advise is greatly welcome.
This project aims at:
- Making the CachyOS gamescope session more store-agnostic while retaining the advantages of the Steam ecosystem, with dynamic support for alternative frontends.
- Enabling seamless switching between a UWSM-managed wayland session and gamescope to gracefully handle relevant process-trees start/stop while retaining consistent background functionalities of pc game launchers.
- Providing a simple and lightweight switcher for gaming frontends and sessions.

TO DO:
- [ ] Wrap Steam, Heroic, gamescope-session and DE/WE session in uwsm-managed systemd units. Quite straight forward IMO.
- [ ] Expand steamos-session-select functionality and session type support. We'll start with adding 'custom' argument option, might write some smarter logic around the overall process if I get inspired.
- [ ] Clear and clean the gamescope-session bootup logic, add custom and dynamic client options via steam-launcher. Much obscure code for me to digest here before I make assumptions.
- [ ] Provide session-specific global launch arguments and env variables for frontends and games. Session-specific uwsm env files might already do that ?
- [ ] Write a simple wayland GUI selector with mouse, keyboard and gamepad support for switching gamescope gaming frontends and sessions. A dmenu-compatible setup feels easiest, interested in eventually writing a light QuickShell or Godot component for my learning endeavours though.
- [ ] Pray I get to this point and that it doesn't break.
