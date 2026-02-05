# LoadSync™ Guide

LoadSync™ is the building management software for your loadcenter. For hardware setup and UPS connections, see the [Loadcenter Guide](loadcenters.md#loadsync-setup).

## Tailscale Remote Access

Tailscale allows for secure, remote access to any miners on a LoadSync™ accessible subnet.

### Prerequisites

1. Visit [tailscale.com/docs/install](https://tailscale.com/docs/install) to download and install the Tailscale client on your computer or mobile device.
2. Sign up for a Tailscale account if you don't have one.

### Setup

!!! tip "Connecting Tailscale"
    1. On the LoadSync interface, navigate to the **Help Page** and select the **Tailscale** tab.
    2. If you do not see a Login QR code, click the **New Login** button to generate one.
    3. Scan the QR code with your smartphone and log in using your Tailscale account.
    4. Once authenticated, press the **Connect** button on your smartphone device.

### Verification

After connecting, the **Tailscale State** should display as "Running" and your account email will appear in the **Profile** dropdown.

You can now access miner web interfaces remotely by entering their IPs in your browser. Miner IPs can be found on the **Miners** page in LoadSync.

!!! info "More Information"
    For a detailed walkthrough, see the [Tailscale Quickstart Guide](https://tailscale.com/docs/how-to/quickstart).

## Fleet Manager

*Coming soon.*
