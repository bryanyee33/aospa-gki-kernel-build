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
- Use KSU Metamodules.
- Support for other KSU Managers has been deprecated.

<p>&nbsp;</p>

Credits to Adithya R - [ghostrider_reborn](https://github.com/ghostrider-reborn)
[kernel-source](https://github.com/pa-gr/android_kernel_xiaomi_sm8450)

Credits to simonpunk - [susfs4ksu](https://gitlab.com/simonpunk/susfs4ksu)
