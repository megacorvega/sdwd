# sdwd

This script is meant to be used with the [stable-diffusion-webui-docker](https://github.com/AbdBarho/stable-diffusion-webui-docker) repository.

## Instructions

1. Download the `sdops` script and place it on the top level of the `stable-diffusion-webui-docker` folder.
2. Run `chmod +x sdops` so that the script can be used.
3. Run `./sdops` to start the script.

> **Warning**
> The user running this script must be a part of the docker group in order for restarting and stopping containers to work with non-root permissions.
