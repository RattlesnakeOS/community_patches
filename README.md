## Overview
These are optional patches provided by the community that can be applied to the RattlesnakeOS build process. Both patches and shell scripts are supported. 

## How do I add these patches to my builds?
You can read more about custom patches in the [customization section of the rattlesnakeos-stack FAQ](https://github.com/dan-v/rattlesnakeos-stack#customizations). 

## Patch Compatibility

Currently, only the following patches have been updated and confirmed to be working in Android 11.0.

* `00001-global-internet-permission-toggle.patch` - this patch adds an additional global network permission.
* `00002-round-icon.patch` - show round icons in launcher, quick setting tiles.
* `00003-enable-volte-wifi-calling.patch` - enable VoLTE/4G and WiFi calling (only sargo/bonito and sunfish).
* `00004-use-cloudflare-dns.patch` - fallback to Cloudflare DNS instead of Google DNS.
* `00005-2-button-navigation.patch` - add back 2-button navigation.

## Submitting Community Patches
Rules for submitting a patch:
* Patches should have a number and name describing patch (e.g. 00002-description-of-patch.patch)
* Patches should be fully tested with a build using latest version of rattlesnakeos-stack
* Patches need to assume it is going to be applied from the <b>root of the AOSP build directory</b>. You can look at existing patches to get an idea of how that looks.
