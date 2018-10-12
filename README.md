## Overview
These are optional patches (both patches and shell scripts are supported) provided by the community that can be applied to the RattlesnakeOS build process. I wouldn't recommend using this repository directly as additional patches could be put in here in the future that you may not want. Instead, I recommend forking this repository and update your `manifest` file to only include the patches you'd like then pass in your forked repository to rattlesnakeos-stack (e.g. --repo-patches https://github.com/yourrepo/community_patches.git).

## Required Patch Repo Structure
* You can put patch files anywhere in the repo as long as they have a .patch extension
* You can put shell scripts anywhere in the repo as long as they have a .sh extension
* Any patches and shell scripts you want to include in the build should have their full filename added to the `manifest` file at the root of the repository (one per line).

## Submitting Community Patches
Rules for submitting a patch:
* Patches should have a number and name describing patch (e.g. 00002-description-of-patch.patch)
* Patches should be fully tested with a build using latest version of rattlesnakeos-stack
* Patches need to assume it is going to be applied from the <b>root of the AOSP build directory</b>. You can look at existing patches to get an idea of how that looks.
* Full patch filename should be added to the `manifest` file
