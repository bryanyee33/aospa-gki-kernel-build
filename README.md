# aospa-gki-kernel-build
## Differences from stock AOSPA kernel
- Added KSU (GKI)
- Added SUSFS
- Added Westwood TCP (set as default)
- Built with latest Clang
- Allow for usage of Magic Mount

### SUSFS Usage
- To use SUSFS, you will have to manually modify the provided module to fit your requirements.
- You may use [this](https://github.com/sidex15/ksu_module_susfs) module instead if you are unsure of what to modify. Use the v1.5.2 releases.

### Magic Mount
- To switch to Magic Mount, switch to one of the following KSU managers:

  [KernelSU Next](https://github.com/rifsxd/KernelSU-Next)

  [5ec1cff](https://github.com/5ec1cff/KernelSU)

  [backslashxx](https://github.com/backslashxx/KernelSU)

  [armv7a](https://github.com/armv7a/KernelSU/releases)

  To switch back, install the official KernelSU manager. Make sure to uninstall any previous KSU managers before installing a new one.

- You will have to delete /data/adb/modules, /data/adb/modules_update, /data/adb/ksu/modules.img, /data/adb/ksu/modules_update.img to switch between them.

<p>&nbsp;</p>

Credits to Adithya R - [ghostrider_reborn](https://github.com/ghostrider-reborn)
[kernel-source](https://github.com/pa-gr/android_kernel_xiaomi_sm8450)

Credits to simonpunk - [susfs4ksu](https://gitlab.com/simonpunk/susfs4ksu)