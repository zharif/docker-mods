# Talosctl - Docker mod for code-server/openvscode-server

This mod adds the talosctl binary to code-server/openvscode-server, downloading the latest release for the container architecture during container start.

In code-server/openvscode-server docker arguments, set an environment variable `DOCKER_MODS=zharif/mods:code-server-talosctl`

If adding multiple mods, enter them in an array separated by `|`, such as `DOCKER_MODS=zharif/mods:code-server-talosctl|linuxserver/mods:code-server-zsh`
