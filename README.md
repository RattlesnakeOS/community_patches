## Overview
These are optional patches provided by the community that can be applied to the RattlesnakeOS build process. There are two options on how to use these:
* If you want all the patches here (and additional ones that may be added in future), then just pass this repository as is to the build tool (e.g. --repo-patches https://github.com/RattlesnakeOS/community_patches.git)
* If you want to pick and choose patches from this repo, you can fork this repository and update the `manifest` file to only include the patches you'd like then pass in your forked repository (e.g. (e.g. --repo-patches https://github.com/yourrepo/community_patches.git).

## Submitting Patches
Rules for submitting a patch:
* Patches should have a number and name describing patch (e.g. 00002-description-of-patch.patch)
* Patches should be fully tested with a build using latest version of rattlesnakeos-stack
* Patches need to assume it is going to be applied from the <b>root of the AOSP build directory</b>. You can look at existing patches to get an idea of how that looks.
* Full patch filename should be added to the `manifest` file
