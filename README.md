# `ncat` - Docker mod for openssh-server

This mod adds `ncat` to openssh-server, to be installed/updated during container start.

In openssh-server docker arguments, set an environment variable `DOCKER_MODS=ruok5/lsio-mods:openssh-server-ncat`

If adding multiple mods, enter them in an array separated by `|`, such as `DOCKER_MODS=linuxserver/mods:openssh-server-openssh-client|ruok5/lsio-mods:openssh-server-ncat`