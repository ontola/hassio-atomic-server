# Atomic Server Home Assistant Add-on

This repository packages Atomic Server as a Home Assistant add-on.

## Installation

1. Open Home Assistant.
2. Go to **Settings** > **Add-ons** > **Add-on Store**.
3. Open the overflow menu and choose **Repositories**.
4. Add this repository URL:

   ```text
   https://github.com/atomicdata-dev/hassio-atomic-server
   ```

5. Install **Atomic Server**.

The add-on uses the prebuilt Raspberry Pi 5 image:

```text
docker.io/joepmeneer/atomic-server:raspberry-pi-5
```

## Access

By default the add-on maps Atomic Server to:

```text
http://homeassistant.local:9883/
```

For clipboard support and other browser APIs, serve Atomic Server through HTTPS on a real local domain.
