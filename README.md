# Waydroid

Waydroid is a container-based approach to boot a full Android system on a regular GNU/Linux system like Ubuntu.

## Overview

Waydroid uses Linux namespaces \(user, pid, uts, net, mount, ipc\) to run a full Android system in a container and provide Android applications on any GNU/Linux-based platform.

The Android inside the container has direct access to needed hardwares.

The Android runtime environment ships with a minimal customized Android system image based on the [LineageOS](https://lineageos.org/). The used image is currently based on Android 10

## Index

####      Development:

[Compile Waydroid - Lineage OS based images](development/compile-waydroid-lineage-os-based-images.md)

####      Usage

[Install and Run Android Applications](usage/install-and-run-android-applications.md)

## Reporting bugs

If you have found an issue with Waydroid, please [file a bug](https://github.com/Waydroid/waydroid/issues/new).

## Get in Touch

If you want to get in contact with the developers please feel free to join the _WayDroid_ groups in [Matrix](https://matrix.to/#/#waydroid:connolly.tech) or [Telegram](https://t.me/WayDroid).

