# 64 bit Toolchain

Intended host: 64 bit Linux (img_generic-builder)
Intended target: 64 bit Linux

## Compilers

Apparently GCC toolchains aren't just available for download, so we default to using what we can install from official repositories. To see what this evaluates to, please refer to [the builder image](https://github.com/eons-dev/img_generic-builder).

## How To Use

Use this toolchain with `ebbs . -b cpp --toolchain x86_64`.
Please refer to the [ebbs documentation](https://github.com/eons-dev/bin_ebbs) for more info.