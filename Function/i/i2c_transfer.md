# Function: <code>i2c_transfer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int i2c_transfer(struct i2c_adapter * adap, struct i2c_msg * msgs, int num)
```

```json
{
  "name": "i2c_transfer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585635568,
      "name": "i2c_transfer",
      "external": true,
      "loc": "drivers/i2c/i2c-core.c:2225",
      "file": "drivers/i2c/i2c-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_read",
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_gather_write",
        "drivers/mfd/tps65912-i2c.c:tps65912_i2c_read",
        "drivers/i2c/i2c-core.c:i2c_master_send",
        "drivers/i2c/i2c-core.c:i2c_master_recv",
        "drivers/i2c/i2c-core.c:i2c_smbus_xfer_emulated",
        "drivers/i2c/i2c-core.c:i2c_smbus_xfer_emulated",
        "drivers/i2c/i2c-core.c:i2c_smbus_xfer_emulated",
        "drivers/i2c/i2c-core.c:acpi_gsb_i2c_read_bytes",
        "drivers/i2c/i2c-core.c:acpi_i2c_space_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585635568,
      "name": "i2c_transfer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
int i2c_transfer(struct i2c_adapter * adap, struct i2c_msg * msgs, int num)
```

```json
{
  "name": "i2c_transfer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586034816,
      "name": "i2c_transfer",
      "external": true,
      "loc": "drivers/i2c/i2c-core.c:2430",
      "file": "drivers/i2c/i2c-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_read",
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_gather_write",
        "drivers/i2c/i2c-core.c:i2c_smbus_xfer_emulated",
        "drivers/i2c/i2c-core.c:i2c_smbus_xfer_emulated",
        "drivers/i2c/i2c-core.c:i2c_smbus_xfer_emulated",
        "drivers/i2c/i2c-core.c:i2c_master_recv",
        "drivers/i2c/i2c-core.c:i2c_master_send",
        "drivers/i2c/i2c-core.c:acpi_i2c_space_handler",
        "drivers/i2c/i2c-core.c:acpi_gsb_i2c_read_bytes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586034816,
      "name": "i2c_transfer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
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
int i2c_transfer(struct i2c_adapter * adap, struct i2c_msg * msgs, int num)
```

```json
{
  "name": "i2c_transfer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586232256,
      "name": "i2c_transfer",
      "external": true,
      "loc": "drivers/i2c/i2c-core.c:2716",
      "file": "drivers/i2c/i2c-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_read",
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_gather_write",
        "drivers/i2c/i2c-core.c:i2c_smbus_xfer_emulated",
        "drivers/i2c/i2c-core.c:i2c_smbus_xfer_emulated",
        "drivers/i2c/i2c-core.c:i2c_smbus_xfer_emulated",
        "drivers/i2c/i2c-core.c:i2c_master_recv",
        "drivers/i2c/i2c-core.c:i2c_master_send",
        "drivers/i2c/i2c-core.c:i2c_acpi_space_handler",
        "drivers/i2c/i2c-core.c:acpi_gsb_i2c_read_bytes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586232256,
      "name": "i2c_transfer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 185
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
int i2c_transfer(struct i2c_adapter * adap, struct i2c_msg * msgs, int num)
```

```json
{
  "name": "i2c_transfer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586318368,
      "name": "i2c_transfer",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:1902",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_read",
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_gather_write",
        "drivers/i2c/i2c-core-base.c:i2c_master_recv",
        "drivers/i2c/i2c-core-base.c:i2c_master_send",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_xfer_emulated",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_xfer_emulated",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586318368,
      "name": "i2c_transfer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
int i2c_transfer(struct i2c_adapter * adap, struct i2c_msg * msgs, int num)
```

```json
{
  "name": "i2c_transfer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586782032,
      "name": "i2c_transfer",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:1926",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_read",
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_gather_write",
        "drivers/i2c/i2c-core-base.c:i2c_master_recv",
        "drivers/i2c/i2c-core-base.c:i2c_master_send",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_xfer_emulated",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_xfer_emulated",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586782032,
      "name": "i2c_transfer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
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
int i2c_transfer(struct i2c_adapter * adap, struct i2c_msg * msgs, int num)
```

```json
{
  "name": "i2c_transfer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587054960,
      "name": "i2c_transfer",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:1909",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_read",
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_gather_write",
        "drivers/i2c/i2c-core-base.c:i2c_transfer_buffer_flags",
        "drivers/i2c/i2c-core-smbus.c:i2c_smbus_xfer_emulated",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587054960,
      "name": "i2c_transfer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 207
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
int i2c_transfer(struct i2c_adapter * adap, struct i2c_msg * msgs, int num)
```

```json
{
  "name": "i2c_transfer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587215088,
      "name": "i2c_transfer",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:1920",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_read",
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_gather_write",
        "drivers/i2c/i2c-core-base.c:i2c_transfer_buffer_flags",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587215088,
      "name": "i2c_transfer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 207
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
int i2c_transfer(struct i2c_adapter * adap, struct i2c_msg * msgs, int num)
```

```json
{
  "name": "i2c_transfer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587480752,
      "name": "i2c_transfer",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:2018",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_read",
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_gather_write",
        "drivers/i2c/i2c-core-base.c:i2c_transfer_buffer_flags",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587480752,
      "name": "i2c_transfer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 263
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
int i2c_transfer(struct i2c_adapter * adap, struct i2c_msg * msgs, int num)
```

```json
{
  "name": "i2c_transfer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587684016,
      "name": "i2c_transfer",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:2023",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_read",
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_gather_write",
        "drivers/i2c/i2c-core-base.c:i2c_transfer_buffer_flags",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587684016,
      "name": "i2c_transfer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 263
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int i2c_transfer(struct i2c_adapter * adap, struct i2c_msg * msgs, int num)
```

```json
{
  "name": "i2c_transfer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588552544,
      "name": "i2c_transfer",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:1953",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_read",
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_gather_write",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_execute_command",
        "drivers/i2c/i2c-core-base.c:i2c_transfer_buffer_flags",
        "drivers/i2c/i2c-core-acpi.c:acpi_gsb_i2c_write_bytes",
        "drivers/i2c/i2c-core-acpi.c:acpi_gsb_i2c_read_bytes",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_rdwr",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_rdwr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588552544,
      "name": "i2c_transfer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 263
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int i2c_transfer(struct i2c_adapter * adap, struct i2c_msg * msgs, int num)
```

```json
{
  "name": "i2c_transfer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588577968,
      "name": "i2c_transfer",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:2083",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_read",
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_gather_write",
        "drivers/mfd/da9063-i2c.c:da9063_get_device_type",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_execute_command",
        "drivers/i2c/i2c-core-base.c:i2c_transfer_buffer_flags",
        "drivers/i2c/i2c-core-acpi.c:acpi_gsb_i2c_write_bytes",
        "drivers/i2c/i2c-core-acpi.c:acpi_gsb_i2c_read_bytes",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_rdwr",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_rdwr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588577968,
      "name": "i2c_transfer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 263
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int i2c_transfer(struct i2c_adapter * adap, struct i2c_msg * msgs, int num)
```

```json
{
  "name": "i2c_transfer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588461584,
      "name": "i2c_transfer",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:2143",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_read",
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_gather_write",
        "drivers/mfd/da9063-i2c.c:da9063_i2c_probe",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_execute_command",
        "drivers/i2c/i2c-core-base.c:i2c_transfer_buffer_flags",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler",
        "drivers/i2c/i2c-core-acpi.c:acpi_gsb_i2c_read_bytes",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_rdwr",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_rdwr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588461584,
      "name": "i2c_transfer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 263
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int i2c_transfer(struct i2c_adapter * adap, struct i2c_msg * msgs, int num)
```

```json
{
  "name": "i2c_transfer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589129680,
      "name": "i2c_transfer",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:2144",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_read",
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_gather_write",
        "drivers/mfd/da9063-i2c.c:da9063_i2c_probe",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_execute_command",
        "drivers/i2c/i2c-core-base.c:i2c_transfer_buffer_flags",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler",
        "drivers/i2c/i2c-core-acpi.c:acpi_gsb_i2c_read_bytes",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_rdwr",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_rdwr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589129680,
      "name": "i2c_transfer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int i2c_transfer(struct i2c_adapter * adap, struct i2c_msg * msgs, int num)
```

```json
{
  "name": "i2c_transfer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590579024,
      "name": "i2c_transfer",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:2147",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_read",
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_gather_write",
        "drivers/mfd/da9063-i2c.c:da9063_i2c_probe",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_execute_command",
        "drivers/i2c/i2c-core-base.c:i2c_transfer_buffer_flags",
        "drivers/i2c/i2c-core-acpi.c:acpi_gsb_i2c_write_bytes",
        "drivers/i2c/i2c-core-acpi.c:acpi_gsb_i2c_read_bytes",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_rdwr",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_rdwr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590579024,
      "name": "i2c_transfer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int i2c_transfer(struct i2c_adapter * adap, struct i2c_msg * msgs, int num)
```

```json
{
  "name": "i2c_transfer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592236160,
      "name": "i2c_transfer",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:2141",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_read",
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_gather_write",
        "drivers/mfd/da9063-i2c.c:da9063_i2c_probe",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_execute_command",
        "drivers/i2c/i2c-core-base.c:i2c_transfer_buffer_flags",
        "drivers/i2c/i2c-core-acpi.c:acpi_gsb_i2c_write_bytes",
        "drivers/i2c/i2c-core-acpi.c:acpi_gsb_i2c_read_bytes",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_rdwr",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_rdwr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592236160,
      "name": "i2c_transfer",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int i2c_transfer(struct i2c_adapter * adap, struct i2c_msg * msgs, int num)
```

```json
{
  "name": "i2c_transfer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592661264,
      "name": "i2c_transfer",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:2254",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_read",
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_gather_write",
        "drivers/mfd/da9063-i2c.c:da9063_i2c_probe",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_execute_command",
        "drivers/i2c/i2c-core-base.c:i2c_transfer_buffer_flags",
        "drivers/i2c/i2c-core-acpi.c:acpi_gsb_i2c_write_bytes",
        "drivers/i2c/i2c-core-acpi.c:acpi_gsb_i2c_read_bytes",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_rdwr",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_rdwr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592661264,
      "name": "i2c_transfer",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int i2c_transfer(struct i2c_adapter * adap, struct i2c_msg * msgs, int num)
```

```json
{
  "name": "i2c_transfer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593406448,
      "name": "i2c_transfer",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:2272",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_read",
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_gather_write",
        "drivers/mfd/da9063-i2c.c:da9063_i2c_probe",
        "drivers/gpu/drm/drm_edid.c:drm_do_probe_ddc_edid",
        "drivers/input/touchscreen/elants_i2c.c:elants_i2c_execute_command",
        "drivers/i2c/i2c-core-base.c:i2c_transfer_buffer_flags",
        "drivers/i2c/i2c-core-acpi.c:acpi_gsb_i2c_write_bytes",
        "drivers/i2c/i2c-core-acpi.c:acpi_gsb_i2c_read_bytes",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_rdwr",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_rdwr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593406448,
      "name": "i2c_transfer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 273
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
int i2c_transfer(struct i2c_adapter * adap, struct i2c_msg * msgs, int num)
```

```json
{
  "name": "i2c_transfer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336500844464,
      "name": "i2c_transfer",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:2023",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_read",
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_gather_write",
        "drivers/i2c/i2c-core-base.c:i2c_transfer_buffer_flags",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500844464,
      "name": "i2c_transfer",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int i2c_transfer(struct i2c_adapter * adap, struct i2c_msg * msgs, int num)
```

```json
{
  "name": "i2c_transfer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3233359908,
      "name": "i2c_transfer",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:2023",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_read",
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_gather_write",
        "drivers/rtc/rtc-pcf8523.c:pcf8523_rtc_set_time",
        "drivers/rtc/rtc-pcf8523.c:pcf8523_rtc_read_time",
        "drivers/rtc/rtc-pcf8523.c:pcf8523_write",
        "drivers/rtc/rtc-pcf8523.c:pcf8523_read",
        "drivers/i2c/i2c-core-base.c:i2c_transfer_buffer_flags",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_rdwr",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_rdwr",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_rdwr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233359908,
      "name": "i2c_transfer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 328
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
int i2c_transfer(struct i2c_adapter * adap, struct i2c_msg * msgs, int num)
```

```json
{
  "name": "i2c_transfer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055294305920,
      "name": "i2c_transfer",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:2023",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_read",
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_gather_write",
        "drivers/i2c/i2c-core-base.c:i2c_transfer_buffer_flags",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_rdwr",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_rdwr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294305920,
      "name": "i2c_transfer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 404
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
int i2c_transfer(struct i2c_adapter * adap, struct i2c_msg * msgs, int num)
```

```json
{
  "name": "i2c_transfer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277647942,
      "name": "i2c_transfer",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:2023",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_read",
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_gather_write",
        "drivers/i2c/i2c-core-base.c:i2c_transfer_buffer_flags",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_rdwr",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_rdwr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277647942,
      "name": "i2c_transfer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
int i2c_transfer(struct i2c_adapter * adap, struct i2c_msg * msgs, int num)
```

```json
{
  "name": "i2c_transfer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587635264,
      "name": "i2c_transfer",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:2023",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_read",
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_gather_write",
        "drivers/i2c/i2c-core-base.c:i2c_transfer_buffer_flags",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587635264,
      "name": "i2c_transfer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 263
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
int i2c_transfer(struct i2c_adapter * adap, struct i2c_msg * msgs, int num)
```

```json
{
  "name": "i2c_transfer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587746464,
      "name": "i2c_transfer",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:2023",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_read",
        "drivers/base/regmap/regmap-i2c.c:regmap_i2c_gather_write",
        "drivers/i2c/i2c-core-base.c:i2c_transfer_buffer_flags",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587746464,
      "name": "i2c_transfer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 263
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
int i2c_transfer(struct i2c_adapter * adap, struct i2c_msg * msgs, int num)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
int i2c_transfer(struct i2c_adapter * adap, struct i2c_msg * msgs, int num)
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
