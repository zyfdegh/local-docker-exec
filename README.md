[![Go Report](https://goreportcard.com/badge/github.com/zyfdegh/local-docker-exec)](https://goreportcard.com/report/github.com/zyfdegh/local-docker-exec)

# local-docker-exec
Connect to local docker daemon or swarm. Run command 'sh' in container.

Screenshot:

![Mdviewer logo](https://raw.githubusercontent.com/zyfdegh/local-docker-exec/master/raw/screenshot-01.png)

# Precondition
To run this programme, a TLS enabled docker daemon is required with port binded.

# Params

**ContainerId:** name or ID of container. For docker daemon, support containers created by daemon. For swarm, support containers created by all daemons in cluster.

# Version
Support docker 1.11.x with API version 1.23

Note that docker 1.12 has merged swarm into daemon, not test so far.

# Related
[remote-docker-exec][https://github.com/zyfdegh/remote-docker-exec.git]: Connect to docker daemon or swarm with TLS. Run command 'sh' in container.

# LICENSE
MIT
