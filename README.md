# tor-relay

My Middle Tor Relay which I run on Kubernetes. You can modify `torrc.middle` and build a new image for changing tor config.

This creates a persistent volume claim of 3GB with Digitalocean block storage. `tor-relay-deploy.yml` can be modified if anything else needs to be used.