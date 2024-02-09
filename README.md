# tailscale-snap2
A Snap port of Tailscale.

This is a port of Tailscale to the Snap store. The snapcraft.yaml is based on the one by sergiusens, found here: https://github.com/sergiusens/tailscale 

I also used AI to fix some of the snapcraft.yaml, because I am inexperienced with building Snaps.
Updates to the version of tailscale should not be needed because this version of Tailscale has a built-in updater, so theoretically, it should be fine.
The version of Tailscale this snap comes with is 1.58.2, which is much newer compared to the older snap by seriusens, which has 1.22.1.
To install, invoke the command "sudo snap install --edge tailscale-snap2 --devmode"

Note: To use the Tailscale CLI, you must invoke the command "tailscale-snap2" instead of just "tailscale"

<a href="https://snapcraft.io/tailscale-snap2">
  <img alt="Get it from the Snap Store" src="https://snapcraft.io/static/images/badges/en/snap-store-black.svg" />
</a>
