## Overview
These are optional patches provided by the community that can be applied to the RattlesnakeOS build process. Both patches and shell scripts are supported. 

## How do I add these patches to my builds?
You can read more about custom patches in the [customization section of the rattlesnakeos-stack FAQ](https://github.com/dan-v/rattlesnakeos-stack#customizations). 

## Submitting Community Patches
Rules for submitting a patch:
* Patches should have a number and name describing patch (e.g. 00002-description-of-patch.patch)
* Patches should be fully tested with a build using latest version of rattlesnakeos-stack
* Patches need to assume it is going to be applied from the <b>root of the AOSP build directory</b>. You can look at existing patches to get an idea of how that looks.
