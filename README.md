# Mailbox Alarm downloads

Signed Android releases of Mailbox Alarm, a GPS app with multiple pins, tasks and events. Each reminder has its own alarm sound, distance, entry or exit rule, and schedule.

[Android releases](https://github.com/NamielusXR/mailbox-alarm-downloads/releases/latest)

APK filenames include their version, such as `mailbox-alarm-1.1.1.apk`. This repository contains the public APKs, checksums, and the version manifest read by **Settings > App updates**. Public APKs contain no preset personal mailbox location. Tap **Add reminder** or hold on the map to choose a pin on a new installation. Updates preserve reminders already saved on the phone; the old mailbox becomes a 50 m task.

If you use a never-edited, preconfigured 1.0.0 or 1.0.1 edition, install the preset APK from the [private project](https://github.com/NamielusXR/mailbox-alarm/releases/latest) to retain the original fallback pin. Version 1.0.2 already saved its preset locally and can update directly through Settings. Do not uninstall for an update; that removes saved reminders and settings.

## Install and update

1. Download the versioned APK from Releases and open it on Android 8 or newer.
2. Allow installation from your browser or Files app when Android asks, then install.
3. Tap **Add reminder**, choose a Place, Task or Event, name it and choose its map location.
4. Set its distance (5–5,000 meters), entry/exit condition, once-only or repeat alert, weekdays, optional date/time window, alarm sound and vibration, then save. Preview the sound and start reminders with precise location and notifications enabled.
5. In Settings, view live GPS accuracy and set up lock-screen alarms and battery access.
6. For later releases, use **Settings > App updates > Check for updates**, then **Download** and **Install**. Android still asks you to confirm installation.

Edit reminders with the pencil on their card, pause them individually, complete and reopen tasks, or reset a used once-only alert. Classic alarm, Bright chime and Slow pulse are included. Overnight schedules are supported, and overlapping alarms play in order. Pins, schedules and pending reminders are saved on the phone.

A 5 m entry pin needs a fresh GPS reading with estimated accuracy of ±5 m or better. For each-visit alerts it rearms at 10 m from the pin. GPS cannot reliably distinguish getting inside a parked car from being near it or at a neighboring house; the accuracy value is an estimate. A car Bluetooth connection would be a better condition for detecting actual car use. This version uses GPS conditions.

The app verifies update checksums, versions, and signing certificates before installation. APKs use the same signing certificate as the original release. GPS reminders work offline; maps and app update downloads need internet. No GPS readings, pin coordinates, tasks or schedules are sent with update requests. There is no app account or analytics.

Copyright NamielusXR. Distributed under the MIT license.
