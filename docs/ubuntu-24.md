## Installing on Ubuntu 24.04

Ubuntu 24.04 [introduced restrictions](https://discourse.ubuntu.com/t/ubuntu-24-04-lts-noble-numbat-release-notes/39890) for unprivileged user namespaces that prevents Electron-based apps from running without an appropriate apparmor profile.

## Solution 1 (recommended)

Install Moss using the .deb file. This will create an appropriate apparmor profile under the hood for you and you don't need to bother about it.

## Solution 2

If you don't want to use the .deb file but the AppImage, then you will need to create an apparmor profile yourself that points to the location of the AppImage. Follow the instructions below, replacing the Moss version wherever necessary with the actual moss version that you're trying to use.

1. Put the Moss AppImage somewhere and give it executable permission, e.g.
```shell
sudo mkdir -p /opt/moss
sudo mv org.lightningrodlabs.moss-0.12-0.12.[replace with correct version number].AppImage /opt/moss/
sudo chown -R $(whoami) /opt/moss
chmod +x /opt/moss/org.lightningrodlabs.moss-0.12-0.12.[replace with correct version number].AppImage
```

2. Create a new profile
```shell
sudo nano /etc/apparmor.d/org.lightningrodlabs.moss-0.12
```

3. Add the following content
```
# AppArmor policy for Moss
# ###AUTHOR###
# ###COPYRIGHT###
# ###COMMENT###

abi <abi/4.0>,
#include <tunables/global>

# No template variables specified

/opt/moss/org.lightningrodlabs.moss-0.12-0.12.[replace with correct version number].AppImage flags=(unconfined) {
  userns,

# No abstractions specified

# No policy groups specified

# No read paths specified

# No write paths specified
}
```

4. Reload the apparmor service
```shell
sudo systemctl reload apparmor.service
```