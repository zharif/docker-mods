# Bitwarden Secrets Manager CLI - Docker mod for code-server/openvscode-server

This mod adds the Bitwarden Secrets Manager CLI (`bws`) to code-server/openvscode-server, downloading the latest Linux musl release for the container architecture during container start.

Bitwarden currently publishes Linux CLI releases for amd64 and arm64.

Set `BWS_VERSION=<version>` to pin a specific CLI release instead of resolving the latest `bws` release at container start.

In code-server/openvscode-server docker arguments, set an environment variable `DOCKER_MODS=zharif/mods:code-server-bws`

If adding multiple mods, enter them in an array separated by `|`, such as `DOCKER_MODS=zharif/mods:code-server-bws|linuxserver/mods:code-server-zsh`
