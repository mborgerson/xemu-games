These options may be passed to xemu as command line arguments to change
startup behavior.

| Argument | Action |
|----------|--------|
| `-full-screen` | Launch in full screen |
| `-dvd_path <iso>` | Load disc image `<iso>` |
| `-snapshot` | Discard any writes to the HDD image after exit |
| `-config_path <config>` | Use `<config>` as config file (usually xemu.ini) |

## Advanced

Extra command line arguments are passed as QEMU launch arguments. See [QEMU
documentation](https://www.qemu.org/documentation/) for specifics.
