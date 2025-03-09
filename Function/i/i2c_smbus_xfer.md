# Function: <code>i2c_smbus_xfer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
s32 i2c_smbus_xfer(struct i2c_adapter * adapter, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, union i2c_smbus_data * data)
```

```json
{
  "name": "i2c_smbus_xfer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585637296,
      "name": "i2c_smbus_xfer",
      "external": true,
      "loc": "drivers/i2c/i2c-core.c:3022",
      "file": "drivers/i2c/i2c-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core.c:i2c_default_probe",
        "drivers/i2c/i2c-core.c:i2c_default_probe",
        "drivers/i2c/i2c-core.c:i2c_probe_func_quick_read",
        "drivers/i2c/i2c-core.c:i2c_smbus_read_byte",
        "drivers/i2c/i2c-core.c:i2c_smbus_read_byte_data",
        "drivers/i2c/i2c-core.c:i2c_smbus_read_word_data",
        "drivers/i2c/i2c-core.c:i2c_smbus_read_block_data",
        "drivers/i2c/i2c-core.c:i2c_smbus_write_block_data",
        "drivers/i2c/i2c-core.c:i2c_smbus_read_i2c_block_data",
        "drivers/i2c/i2c-core.c:i2c_smbus_write_i2c_block_data",
        "drivers/i2c/i2c-core.c:acpi_i2c_space_handler",
        "drivers/i2c/i2c-core.c:acpi_i2c_space_handler",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585637296,
      "name": "i2c_smbus_xfer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 826
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
s32 i2c_smbus_xfer(struct i2c_adapter * adapter, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, union i2c_smbus_data * data)
```

```json
{
  "name": "i2c_smbus_xfer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586036512,
      "name": "i2c_smbus_xfer",
      "external": true,
      "loc": "drivers/i2c/i2c-core.c:3227",
      "file": "drivers/i2c/i2c-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core.c:i2c_smbus_write_i2c_block_data",
        "drivers/i2c/i2c-core.c:i2c_smbus_read_i2c_block_data",
        "drivers/i2c/i2c-core.c:i2c_smbus_write_block_data",
        "drivers/i2c/i2c-core.c:i2c_smbus_read_block_data",
        "drivers/i2c/i2c-core.c:i2c_smbus_read_word_data",
        "drivers/i2c/i2c-core.c:i2c_smbus_read_byte_data",
        "drivers/i2c/i2c-core.c:i2c_smbus_read_byte",
        "drivers/i2c/i2c-core.c:i2c_probe_func_quick_read",
        "drivers/i2c/i2c-core.c:i2c_default_probe",
        "drivers/i2c/i2c-core.c:i2c_default_probe",
        "drivers/i2c/i2c-core.c:acpi_i2c_space_handler",
        "drivers/i2c/i2c-core.c:acpi_i2c_space_handler",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586036512,
      "name": "i2c_smbus_xfer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 822
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
s32 i2c_smbus_xfer(struct i2c_adapter * adapter, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, union i2c_smbus_data * data)
```

```json
{
  "name": "i2c_smbus_xfer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586233952,
      "name": "i2c_smbus_xfer",
      "external": true,
      "loc": "drivers/i2c/i2c-core.c:3515",
      "file": "drivers/i2c/i2c-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/i2c/i2c-core.c:i2c_smbus_write_i2c_block_data",
        "drivers/i2c/i2c-core.c:i2c_smbus_read_i2c_block_data",
        "drivers/i2c/i2c-core.c:i2c_smbus_write_block_data",
        "drivers/i2c/i2c-core.c:i2c_smbus_read_block_data",
        "drivers/i2c/i2c-core.c:i2c_smbus_read_word_data",
        "drivers/i2c/i2c-core.c:i2c_smbus_read_byte_data",
        "drivers/i2c/i2c-core.c:i2c_smbus_read_byte",
        "drivers/i2c/i2c-core.c:i2c_probe_func_quick_read",
        "drivers/i2c/i2c-core.c:i2c_default_probe",
        "drivers/i2c/i2c-core.c:i2c_default_probe",
        "drivers/i2c/i2c-core.c:i2c_acpi_space_handler",
        "drivers/i2c/i2c-core.c:i2c_acpi_space_handler",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586233952,
      "name": "i2c_smbus_xfer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 822
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
s32 i2c_smbus_xfer(struct i2c_adapter * adapter, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, union i2c_smbus_data * data)
```

```json
{
  "name": "i2c_smbus_xfer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586328176,
      "name": "i2c_smbus_xfer",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:482",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/i2c/i2c-core-base.c:i2c_probe_func_quick_read",
        "drivers/i2c/i2c-core-base.c:i2c_default_probe",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_i2c_block_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_block_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_block_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_word_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_word_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_byte_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_byte_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_byte",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_byte",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586328176,
      "name": "i2c_smbus_xfer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 798
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
s32 i2c_smbus_xfer(struct i2c_adapter * adapter, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, union i2c_smbus_data * data)
```

```json
{
  "name": "i2c_smbus_xfer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586792048,
      "name": "i2c_smbus_xfer",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:484",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/i2c/i2c-core-base.c:i2c_probe_func_quick_read",
        "drivers/i2c/i2c-core-base.c:i2c_default_probe",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_i2c_block_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_block_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_block_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_word_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_word_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_byte_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_byte_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_byte",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_byte",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586792048,
      "name": "i2c_smbus_xfer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 830
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
s32 i2c_smbus_xfer(struct i2c_adapter * adapter, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, union i2c_smbus_data * data)
```

```json
{
  "name": "i2c_smbus_xfer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587065296,
      "name": "i2c_smbus_xfer",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:527",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/i2c/i2c-core-base.c:i2c_probe_func_quick_read",
        "drivers/i2c/i2c-core-base.c:i2c_default_probe",
        "drivers/i2c/i2c-core-base.c:i2c_get_device_id",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_i2c_block_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_block_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_block_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_word_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_word_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_byte_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_byte_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_byte",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_byte",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587065296,
      "name": "i2c_smbus_xfer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 819
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
s32 i2c_smbus_xfer(struct i2c_adapter * adapter, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, union i2c_smbus_data * data)
```

```json
{
  "name": "i2c_smbus_xfer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587226080,
      "name": "i2c_smbus_xfer",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:527",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/i2c/i2c-core-base.c:i2c_probe_func_quick_read",
        "drivers/i2c/i2c-core-base.c:i2c_default_probe",
        "drivers/i2c/i2c-core-base.c:i2c_get_device_id",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_i2c_block_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_block_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_block_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_word_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_word_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_byte_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_byte_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_byte",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_byte",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587226080,
      "name": "i2c_smbus_xfer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
s32 i2c_smbus_xfer(struct i2c_adapter * adapter, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, union i2c_smbus_data * data)
```

```json
{
  "name": "i2c_smbus_xfer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587492784,
      "name": "i2c_smbus_xfer",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:525",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/i2c/i2c-core-base.c:i2c_probe_func_quick_read",
        "drivers/i2c/i2c-core-base.c:i2c_default_probe",
        "drivers/i2c/i2c-core-base.c:i2c_default_probe",
        "drivers/i2c/i2c-core-base.c:i2c_default_probe",
        "drivers/i2c/i2c-core-base.c:i2c_get_device_id",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_i2c_block_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_block_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_block_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_word_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_word_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_byte_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_byte_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_byte",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_byte",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587492784,
      "name": "i2c_smbus_xfer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 237
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
s32 i2c_smbus_xfer(struct i2c_adapter * adapter, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, union i2c_smbus_data * data)
```

```json
{
  "name": "i2c_smbus_xfer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587695952,
      "name": "i2c_smbus_xfer",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:525",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/i2c/i2c-core-base.c:i2c_probe_func_quick_read",
        "drivers/i2c/i2c-core-base.c:i2c_default_probe",
        "drivers/i2c/i2c-core-base.c:i2c_default_probe",
        "drivers/i2c/i2c-core-base.c:i2c_default_probe",
        "drivers/i2c/i2c-core-base.c:i2c_get_device_id",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_i2c_block_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_block_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_block_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_word_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_word_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_byte_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_byte_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_byte",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_byte",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587695952,
      "name": "i2c_smbus_xfer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 237
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
s32 i2c_smbus_xfer(struct i2c_adapter * adapter, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, union i2c_smbus_data * data)
```

```json
{
  "name": "i2c_smbus_xfer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588564368,
      "name": "i2c_smbus_xfer",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:532",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/i2c/i2c-core-base.c:i2c_probe_func_quick_read",
        "drivers/i2c/i2c-core-base.c:i2c_default_probe",
        "drivers/i2c/i2c-core-base.c:i2c_default_probe",
        "drivers/i2c/i2c-core-base.c:i2c_default_probe",
        "drivers/i2c/i2c-core-base.c:i2c_get_device_id",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_i2c_block_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_block_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_block_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_word_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_byte_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_byte",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_byte",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588564368,
      "name": "i2c_smbus_xfer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 237
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
s32 i2c_smbus_xfer(struct i2c_adapter * adapter, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, union i2c_smbus_data * data)
```

```json
{
  "name": "i2c_smbus_xfer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588589008,
      "name": "i2c_smbus_xfer",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:532",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/i2c/i2c-core-base.c:i2c_probe_func_quick_read",
        "drivers/i2c/i2c-core-base.c:i2c_default_probe",
        "drivers/i2c/i2c-core-base.c:i2c_default_probe",
        "drivers/i2c/i2c-core-base.c:i2c_default_probe",
        "drivers/i2c/i2c-core-base.c:i2c_get_device_id",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_i2c_block_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_block_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_block_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_word_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_byte_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_byte",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_byte",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588589008,
      "name": "i2c_smbus_xfer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 237
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
s32 i2c_smbus_xfer(struct i2c_adapter * adapter, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, union i2c_smbus_data * data)
```

```json
{
  "name": "i2c_smbus_xfer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588473104,
      "name": "i2c_smbus_xfer",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:526",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/i2c/i2c-core-base.c:i2c_probe_func_quick_read",
        "drivers/i2c/i2c-core-base.c:i2c_default_probe",
        "drivers/i2c/i2c-core-base.c:i2c_default_probe",
        "drivers/i2c/i2c-core-base.c:i2c_default_probe",
        "drivers/i2c/i2c-core-base.c:i2c_get_device_id",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_i2c_block_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_block_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_block_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_word_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_byte_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_byte",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_byte",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588473104,
      "name": "i2c_smbus_xfer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 237
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
s32 i2c_smbus_xfer(struct i2c_adapter * adapter, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, union i2c_smbus_data * data)
```

```json
{
  "name": "i2c_smbus_xfer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589141312,
      "name": "i2c_smbus_xfer",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:534",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/i2c/i2c-core-base.c:i2c_probe_func_quick_read",
        "drivers/i2c/i2c-core-base.c:i2c_default_probe",
        "drivers/i2c/i2c-core-base.c:i2c_default_probe",
        "drivers/i2c/i2c-core-base.c:i2c_default_probe",
        "drivers/i2c/i2c-core-base.c:i2c_get_device_id",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_i2c_block_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_block_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_block_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_word_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_byte_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_byte",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_byte",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589141312,
      "name": "i2c_smbus_xfer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 237
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
s32 i2c_smbus_xfer(struct i2c_adapter * adapter, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, union i2c_smbus_data * data)
```

```json
{
  "name": "i2c_smbus_xfer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590592784,
      "name": "i2c_smbus_xfer",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:535",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/i2c/i2c-core-base.c:i2c_probe_func_quick_read",
        "drivers/i2c/i2c-core-base.c:i2c_default_probe",
        "drivers/i2c/i2c-core-base.c:i2c_default_probe",
        "drivers/i2c/i2c-core-base.c:i2c_default_probe",
        "drivers/i2c/i2c-core-base.c:i2c_get_device_id",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_i2c_block_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_block_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_block_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_word_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_byte_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_byte",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_byte",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590592784,
      "name": "i2c_smbus_xfer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 253
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
s32 i2c_smbus_xfer(struct i2c_adapter * adapter, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, union i2c_smbus_data * data)
```

```json
{
  "name": "i2c_smbus_xfer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592251648,
      "name": "i2c_smbus_xfer",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:535",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/i2c/i2c-core-base.c:i2c_probe_func_quick_read",
        "drivers/i2c/i2c-core-base.c:i2c_default_probe",
        "drivers/i2c/i2c-core-base.c:i2c_get_device_id",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_i2c_block_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_block_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_block_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_word_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_byte_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_byte",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_byte",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592251648,
      "name": "i2c_smbus_xfer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 258
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
s32 i2c_smbus_xfer(struct i2c_adapter * adapter, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, union i2c_smbus_data * data)
```

```json
{
  "name": "i2c_smbus_xfer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592676896,
      "name": "i2c_smbus_xfer",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:535",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/i2c/i2c-core-base.c:i2c_probe_func_quick_read",
        "drivers/i2c/i2c-core-base.c:i2c_default_probe",
        "drivers/i2c/i2c-core-base.c:i2c_get_device_id",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_i2c_block_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_block_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_block_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_word_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_byte_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_byte",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_byte",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592676896,
      "name": "i2c_smbus_xfer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 258
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
s32 i2c_smbus_xfer(struct i2c_adapter * adapter, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, union i2c_smbus_data * data)
```

```json
{
  "name": "i2c_smbus_xfer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593422320,
      "name": "i2c_smbus_xfer",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:535",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/i2c/i2c-core-base.c:i2c_probe_func_quick_read",
        "drivers/i2c/i2c-core-base.c:i2c_default_probe",
        "drivers/i2c/i2c-core-base.c:i2c_get_device_id",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_i2c_block_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_block_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_block_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_word_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_byte_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_byte",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_byte",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593422320,
      "name": "i2c_smbus_xfer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
    }
  ]
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
s32 i2c_smbus_xfer(struct i2c_adapter * adapter, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, union i2c_smbus_data * data)
```

```json
{
  "name": "i2c_smbus_xfer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336500857136,
      "name": "i2c_smbus_xfer",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:525",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_probe_func_quick_read",
        "drivers/i2c/i2c-core-base.c:i2c_default_probe",
        "drivers/i2c/i2c-core-base.c:i2c_default_probe",
        "drivers/i2c/i2c-core-base.c:i2c_get_device_id",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_i2c_block_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_block_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_block_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_word_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_word_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_byte_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_byte_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_byte",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_byte",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500857136,
      "name": "i2c_smbus_xfer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
s32 i2c_smbus_xfer(struct i2c_adapter * adapter, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, union i2c_smbus_data * data)
```

```json
{
  "name": "i2c_smbus_xfer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3233373012,
      "name": "i2c_smbus_xfer",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:525",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_probe_func_quick_read",
        "drivers/i2c/i2c-core-base.c:i2c_default_probe",
        "drivers/i2c/i2c-core-base.c:i2c_default_probe",
        "drivers/i2c/i2c-core-base.c:i2c_get_device_id",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_i2c_block_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_block_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_block_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_word_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_word_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_byte_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_byte_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_byte",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_byte",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233373012,
      "name": "i2c_smbus_xfer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
s32 i2c_smbus_xfer(struct i2c_adapter * adapter, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, union i2c_smbus_data * data)
```

```json
{
  "name": "i2c_smbus_xfer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055294323440,
      "name": "i2c_smbus_xfer",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:525",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_probe_func_quick_read",
        "drivers/i2c/i2c-core-base.c:i2c_default_probe",
        "drivers/i2c/i2c-core-base.c:i2c_default_probe",
        "drivers/i2c/i2c-core-base.c:i2c_get_device_id",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_i2c_block_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_block_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_block_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_word_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_word_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_byte_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_byte_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_byte",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_byte",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294323440,
      "name": "i2c_smbus_xfer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 392
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
s32 i2c_smbus_xfer(struct i2c_adapter * adapter, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, union i2c_smbus_data * data)
```

```json
{
  "name": "i2c_smbus_xfer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277659180,
      "name": "i2c_smbus_xfer",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:525",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_probe_func_quick_read",
        "drivers/i2c/i2c-core-base.c:i2c_default_probe",
        "drivers/i2c/i2c-core-base.c:i2c_default_probe",
        "drivers/i2c/i2c-core-base.c:i2c_get_device_id",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_i2c_block_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_block_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_block_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_word_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_word_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_byte_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_byte_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_byte",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_byte",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277659180,
      "name": "i2c_smbus_xfer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
s32 i2c_smbus_xfer(struct i2c_adapter * adapter, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, union i2c_smbus_data * data)
```

```json
{
  "name": "i2c_smbus_xfer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587647200,
      "name": "i2c_smbus_xfer",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:525",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/i2c/i2c-core-base.c:i2c_probe_func_quick_read",
        "drivers/i2c/i2c-core-base.c:i2c_default_probe",
        "drivers/i2c/i2c-core-base.c:i2c_default_probe",
        "drivers/i2c/i2c-core-base.c:i2c_default_probe",
        "drivers/i2c/i2c-core-base.c:i2c_get_device_id",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_i2c_block_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_block_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_block_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_word_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_word_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_byte_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_byte_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_byte",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_byte",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587647200,
      "name": "i2c_smbus_xfer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 237
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
s32 i2c_smbus_xfer(struct i2c_adapter * adapter, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, union i2c_smbus_data * data)
```

```json
{
  "name": "i2c_smbus_xfer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587758480,
      "name": "i2c_smbus_xfer",
      "external": true,
      "loc": "drivers/i2c/i2c-core-smbus.c:525",
      "file": "drivers/i2c/i2c-core-smbus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe",
        "drivers/i2c/i2c-core-base.c:i2c_probe_func_quick_read",
        "drivers/i2c/i2c-core-base.c:i2c_default_probe",
        "drivers/i2c/i2c-core-base.c:i2c_default_probe",
        "drivers/i2c/i2c-core-base.c:i2c_default_probe",
        "drivers/i2c/i2c-core-base.c:i2c_get_device_id",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_i2c_block_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_block_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_block_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_word_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_word_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_byte_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_byte_data",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_write_byte",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_byte",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_smbus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587758480,
      "name": "i2c_smbus_xfer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 237
    }
  ]
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ➖</summary>

```c
s32 i2c_smbus_xfer(struct i2c_adapter * adapter, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, union i2c_smbus_data * data)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
s32 i2c_smbus_xfer(struct i2c_adapter * adapter, u16 addr, short unsigned int flags, char read_write, u8 command, int protocol, union i2c_smbus_data * data)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
