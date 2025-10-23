# Builder for luckfox pico

This is builder for luckfox cross compile.

## Files

All files are copied from `luckfox-pico`.

```bash
git clone https://github.com/LuckfoxTECH/luckfox-pico.git

# or

git clone https://gitee.com/LuckfoxTECH/luckfox-pico.git
```

- `toolchain`, copied from `<path to luckfox-pico>/tools/linux/toolchain`
- `prebuilt/lib` `prebuilt/usr/lib`, copied from `<path to luckfox-pico>/sysdrv/source/buildroot/buildroot-2023.02.6/output/target`
  also cloud be copied from target system

## CMake

```bash
cmake -DCMAKE_TOOLCHAIN_FILE=/workspace/toolchain.cmake ..
```
