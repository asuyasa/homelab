# Tailscale
The following role:
- Installs Tailscale
- Configures Tailscale to join your network

## Required variables

`tailscale_api_key:` The API Key. This can be generated within the Tailscale admin console.

`tailscale_tailnet:`: The name of your network's tailnet.

## Other variables

`tailscale_routes:` List of IP addresses to use for your subnet routes.

`tailscale_exit_node:` Whether to use the client as an exit node.
