# Python3 - Docker mod for code-server/openvscode-server

This mod adds a python3 dev environment to code-server/openvscode-server, to be installed/updated during container start.

In code-server/openvscode-server docker arguments, set an environment variable `DOCKER_MODS=linuxserver/mods:code-server-python3`

If adding multiple mods, enter them in an array separated by `|`, such as `DOCKER_MODS=linuxserver/mods:code-server-python3|linuxserver/mods:code-server-mod2`
