# Docker Swarm

Installs Docker and GlusterFS prerequisites, initializes a Docker Swarm, and
joins manager and worker nodes. Set `swarm_name` to the cluster name. Inventory
groups must use `<swarm_name>_Manager` for managers and `<swarm_name>_Swarm` for
workers.

Run this role against all nodes in one intended cluster at the same time.