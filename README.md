# Helm CLI - Docker mod for code-server/openvscode-server

This mod adds the Helm CLI (`helm`) binary and bash completion to code-server/openvscode-server, to be installed/updated during container start.

In code-server/openvscode-server docker arguments, set an environment variable `DOCKER_MODS=zharif/mods:code-server-helm`

If adding multiple mods, enter them in an array separated by `|`, such as `DOCKER_MODS=zharif/mods:code-server-helm|linuxserver/mods:code-server-zsh`
