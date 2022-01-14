# Prebuilt APKs

This is a collection of FOSS APKs, coupled with the respective Android.mk for an
easy integration in the Android build system.
These are just the official unmodified prebuilt binaries, signed by the
corresponding developers.

The included APKs are:

 * Aurora packages
   * AuroraStore: An Open Source alternative for Google Play Store (binary sourced from [here](https://gitlab.com/AuroraOSS/AuroraStore/-/releases))
   * AuroraServices: Service provider for Aurora Store (binary sourced from [here](https://gitlab.com/AuroraOSS/AuroraServices/-/releases))

To include them in your build just add their name in CUSTOM_PACKAGES (for
example in vendor/lineage/config/common.mk).

For details, have a look at:

* https://github.com/lineageos4microg/docker-lineage-cicd
* https://github.com/lineageos4microg/android_vendor_partner_gms


