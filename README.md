# unraid-tailscale
![License](https://img.shields.io/github/license/wjr1985/unraid-tailscale)
![GitHub commit activity](https://img.shields.io/github/commit-activity/y/wjr1985/unraid-tailscale)

This is a fork of https://github.com/deasmi/unraid-tailscale. It's highly recommended to use the [Tailscale plugin for Unraid](https://forums.unraid.net/topic/136889-plugin-tailscale/), but I'm still going to try to keep this image updated for folks who still use it (like me).

The Docker image can be found here https://hub.docker.com/repository/docker/wjr1985/unraid-tailscale/general - the tag for each image is the same as the version specified by Tailscale.

Right now all new images are released manually - I try to keep up to date with the latest version, however I can fall behind sometimes. If it's been a few days since a new version has been released by Tailscale and this image hasn't been updated, feel free to file an issue.

Original README below:

---------

Docker build files for tailscale on unraid

This is intentended to provide access to the unraid server itself over tailscale and does not act as a VPN gateway.
It is possible to get this working using UP_FLAGS however as this was never the intention for this container I cannot provide
support for this usage.

## Optional Env Vars

- `UP_FLAGS` &ndash; Pass flags to the `tailscale up` command run on start-up
Please note that support cannot be provided for the use of UP_FLAGS


