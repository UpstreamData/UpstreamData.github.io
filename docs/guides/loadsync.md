# LoadSync™ Guide

LoadSync™ is the building management software for your loadcenter. For hardware setup and UPS connections, see the [Loadcenter Guide](initial-setup.md#loadsynctm-setup).

LoadSync™ can be accessed remotely with the remote access web UI.  Please [contact us](contact.md) for the login.

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

You may need to enable the routes on the Tailscale web admin panel.
To enable them, click the `...` dropdown next to a unit, select `Edit route settings...`, and ensure the route is enabled under `Subnet routes`.

!!! info "More Information"
    For a detailed walkthrough, see the [Tailscale Quickstart Guide](https://tailscale.com/docs/how-to/quickstart).

## Fleet Manager

*Coming soon.*
