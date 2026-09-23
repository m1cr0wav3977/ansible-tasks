# GlusterFS

Formats and mounts a data volume, configures a replicated GlusterFS volume, and
mounts it at `/data/docker`. Set `device_path` when the data device is not the
default `/dev/xvdb`; `directory_name` optionally creates a child directory
under `/data/docker`.

Run this role against every member of the intended GlusterFS cluster.