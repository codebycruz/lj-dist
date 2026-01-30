# lj-dist

This repository serves to provide up to date builds of LuaJIT as a binary and static library containing development headers for common platforms. They can then be used by something to link to and use lua, especially useful for creation of single executable applications. This was made for the [lpm](https://github.com/codebycruz/lpm) project.

## Supported Platforms

Here's a table of supported platforms and download links to the `luajit` binary.

| Platform    | Architecture            | libc          | Download                                                                                                       |
| ----------- | ----------------------- | ------------- | -------------------------------------------------------------------------------------------------------------- |
| **Linux**   | x86-64                  | glibc (2.35+) | [✅ Download](https://github.com/codebycruz/lj-dist/releases/latest/download/luajit-linux-x86-64-gnu.tar.gz)   |
| **Linux**   | aarch64 (ARM64)         | glibc (2.35+) | [✅ Download](https://github.com/codebycruz/lj-dist/releases/latest/download/luajit-linux-aarch64-gnu.tar.gz)  |
| **Linux**   | aarch64 (ARM64)         | musl          | [✅ Download](https://github.com/codebycruz/lj-dist/releases/latest/download/luajit-linux-aarch64-musl.tar.gz) |
| **Windows** | x86-64                  | -             | [✅ Download](https://github.com/codebycruz/lj-dist/releases/latest/download/luajit-windows-x86-64-gnu.tar.gz) |
| **macOS**   | x86-64 (Intel)          | -             | ❌ Not yet supported                                                                                           |
| **macOS**   | aarch64 (Apple Silicon) | -             | ❌ Not yet supported                                                                                           |

If you need to get the library instead, check out the [release](https://github.com/codebycruz/lj-dist/releases/latest) page manually and download the corresponding `libluajit`, although you would usually do this programmatically.

## Download

The latest builds are always available both as Github Actions artifacts, or in the latest release.
