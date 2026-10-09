# Ubuntu Server Baseline

Applies a basic Ubuntu server baseline, installs administration packages,
enables unattended upgrades, and enforces public-key-only SSH authentication.
It disables cloud-init SSH password authentication and removes its generated
sshd drop-in so it cannot override the main SSH daemon configuration.

No role variables are required.
