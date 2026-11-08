# Changelog

## 20261108-1130

- Removed `apt_packages` and `post_install` (the `shairport-sync` AirPlay receiver) from the manifest, so the package installs on any node with no apt or root steps. Use a Sendspin client for the node's Music Assistant player instead; the code is unchanged.
