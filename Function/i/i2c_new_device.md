# Function: <code>i2c_new_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct i2c_client * i2c_new_device(struct i2c_adapter * adap, const struct i2c_board_info * info)
```

```json
{
  "name": "i2c_new_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585645984,
      "name": "i2c_new_device",
      "external": true,
      "loc": "drivers/i2c/i2c-core.c:1035",
      "file": "drivers/i2c/i2c-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/i2c/i2c-core.c:i2c_new_dummy",
        "drivers/i2c/i2c-core.c:i2c_new_probed_device",
        "drivers/i2c/i2c-core.c:i2c_sysfs_new_device",
        "drivers/i2c/i2c-core.c:acpi_i2c_add_device",
        "drivers/i2c/i2c-core.c:i2c_register_adapter",
        "drivers/i2c/i2c-core.c:i2c_do_add_adapter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585645984,
      "name": "i2c_new_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 560
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
struct i2c_client * i2c_new_device(struct i2c_adapter * adap, const struct i2c_board_info * info)
```

```json
{
  "name": "i2c_new_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586042480,
      "name": "i2c_new_device",
      "external": true,
      "loc": "drivers/i2c/i2c-core.c:1160",
      "file": "drivers/i2c/i2c-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/i2c/i2c-core.c:i2c_new_probed_device",
        "drivers/i2c/i2c-core.c:i2c_register_adapter",
        "drivers/i2c/i2c-core.c:i2c_do_add_adapter",
        "drivers/i2c/i2c-core.c:i2c_sysfs_new_device",
        "drivers/i2c/i2c-core.c:i2c_new_dummy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586042480,
      "name": "i2c_new_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 570
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
struct i2c_client * i2c_new_device(struct i2c_adapter * adap, const struct i2c_board_info * info)
```

```json
{
  "name": "i2c_new_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586239984,
      "name": "i2c_new_device",
      "external": true,
      "loc": "drivers/i2c/i2c-core.c:1297",
      "file": "drivers/i2c/i2c-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/i2c/i2c-core.c:i2c_new_probed_device",
        "drivers/i2c/i2c-core.c:i2c_register_adapter",
        "drivers/i2c/i2c-core.c:i2c_do_add_adapter",
        "drivers/i2c/i2c-core.c:i2c_sysfs_new_device",
        "drivers/i2c/i2c-core.c:i2c_new_dummy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586239984,
      "name": "i2c_new_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 570
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
struct i2c_client * i2c_new_device(struct i2c_adapter * adap, const struct i2c_board_info * info)
```

```json
{
  "name": "i2c_new_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586318944,
      "name": "i2c_new_device",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:725",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/i2c/i2c-core-base.c:i2c_new_probed_device",
        "drivers/i2c/i2c-core-base.c:i2c_detect",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_sysfs_new_device",
        "drivers/i2c/i2c-core-base.c:i2c_new_dummy",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586318944,
      "name": "i2c_new_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 823
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
struct i2c_client * i2c_new_device(struct i2c_adapter * adap, const struct i2c_board_info * info)
```

```json
{
  "name": "i2c_new_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586782640,
      "name": "i2c_new_device",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:736",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/i2c/i2c-core-base.c:i2c_new_probed_device",
        "drivers/i2c/i2c-core-base.c:i2c_detect",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_sysfs_new_device",
        "drivers/i2c/i2c-core-base.c:i2c_new_dummy",
        "drivers/i2c/i2c-core-smbus.c:i2c_setup_smbus_alert",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586782640,
      "name": "i2c_new_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 868
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
struct i2c_client * i2c_new_device(struct i2c_adapter * adap, const struct i2c_board_info * info)
```

```json
{
  "name": "i2c_new_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587055568,
      "name": "i2c_new_device",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:717",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/i2c/i2c-core-base.c:i2c_new_probed_device",
        "drivers/i2c/i2c-core-base.c:i2c_detect",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_sysfs_new_device",
        "drivers/i2c/i2c-core-base.c:i2c_new_dummy",
        "drivers/i2c/i2c-core-smbus.c:i2c_setup_smbus_alert",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587055568,
      "name": "i2c_new_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 864
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
struct i2c_client * i2c_new_device(struct i2c_adapter * adap, const struct i2c_board_info * info)
```

```json
{
  "name": "i2c_new_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587215664,
      "name": "i2c_new_device",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:729",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/htc-i2cpld.c:htcpld_core_probe",
        "drivers/i2c/i2c-core-base.c:i2c_new_probed_device",
        "drivers/i2c/i2c-core-base.c:i2c_detect",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_sysfs_new_device",
        "drivers/i2c/i2c-core-base.c:i2c_new_dummy",
        "drivers/i2c/i2c-core-smbus.c:i2c_setup_smbus_alert",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587215664,
      "name": "i2c_new_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 848
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
struct i2c_client * i2c_new_device(struct i2c_adapter * adap, const struct i2c_board_info * info)
```

```json
{
  "name": "i2c_new_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587484874,
      "name": "i2c_new_device",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:818",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:i2c_new_probed_device",
        "drivers/i2c/i2c-core-base.c:i2c_detect",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter"
      ],
      "caller_func": [
        "drivers/mfd/htc-i2cpld.c:htcpld_setup_chips",
        "drivers/i2c/i2c-core-smbus.c:i2c_setup_smbus_alert",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587482656,
      "name": "i2c_new_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
struct i2c_client * i2c_new_device(struct i2c_adapter * adap, const struct i2c_board_info * info)
```

```json
{
  "name": "i2c_new_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587688138,
      "name": "i2c_new_device",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:823",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:i2c_new_probed_device",
        "drivers/i2c/i2c-core-base.c:i2c_detect",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter"
      ],
      "caller_func": [
        "drivers/mfd/htc-i2cpld.c:htcpld_setup_chips",
        "drivers/i2c/i2c-core-smbus.c:i2c_setup_smbus_alert",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587685920,
      "name": "i2c_new_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
struct i2c_client * i2c_new_device(struct i2c_adapter * adap, const struct i2c_board_info * info)
```

```json
{
  "name": "i2c_new_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336500848700,
      "name": "i2c_new_device",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:823",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:i2c_new_probed_device",
        "drivers/i2c/i2c-core-base.c:i2c_detect",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter"
      ],
      "caller_func": [
        "drivers/mfd/htc-i2cpld.c:htcpld_setup_chips",
        "drivers/i2c/i2c-core-smbus.c:i2c_setup_smbus_alert",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device",
        "drivers/i2c/i2c-core-of.c:of_i2c_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500845872,
      "name": "i2c_new_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
struct i2c_client * i2c_new_device(struct i2c_adapter * adap, const struct i2c_board_info * info)
```

```json
{
  "name": "i2c_new_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3233365780,
      "name": "i2c_new_device",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:823",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:i2c_new_probed_device",
        "drivers/i2c/i2c-core-base.c:i2c_detect",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter"
      ],
      "caller_func": [
        "drivers/mfd/htc-i2cpld.c:htcpld_setup_chips",
        "drivers/i2c/i2c-core-smbus.c:i2c_setup_smbus_alert",
        "drivers/i2c/i2c-core-of.c:of_i2c_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233362948,
      "name": "i2c_new_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
struct i2c_client * i2c_new_device(struct i2c_adapter * adap, const struct i2c_board_info * info)
```

```json
{
  "name": "i2c_new_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055294312924,
      "name": "i2c_new_device",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:823",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:i2c_new_probed_device",
        "drivers/i2c/i2c-core-base.c:i2c_detect",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter"
      ],
      "caller_func": [
        "drivers/mfd/htc-i2cpld.c:htcpld_setup_chips",
        "drivers/i2c/i2c-core-smbus.c:i2c_setup_smbus_alert",
        "drivers/i2c/i2c-core-of.c:of_i2c_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294309088,
      "name": "i2c_new_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
struct i2c_client * i2c_new_device(struct i2c_adapter * adap, const struct i2c_board_info * info)
```

```json
{
  "name": "i2c_new_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277652718,
      "name": "i2c_new_device",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:823",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:i2c_new_probed_device",
        "drivers/i2c/i2c-core-base.c:i2c_detect",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter"
      ],
      "caller_func": [
        "drivers/mfd/htc-i2cpld.c:htcpld_setup_chips",
        "drivers/i2c/i2c-core-smbus.c:i2c_setup_smbus_alert",
        "drivers/i2c/i2c-core-of.c:of_i2c_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277650108,
      "name": "i2c_new_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
struct i2c_client * i2c_new_device(struct i2c_adapter * adap, const struct i2c_board_info * info)
```

```json
{
  "name": "i2c_new_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587639386,
      "name": "i2c_new_device",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:823",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:i2c_new_probed_device",
        "drivers/i2c/i2c-core-base.c:i2c_detect",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter"
      ],
      "caller_func": [
        "drivers/mfd/htc-i2cpld.c:htcpld_setup_chips",
        "drivers/i2c/i2c-core-smbus.c:i2c_setup_smbus_alert",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587637168,
      "name": "i2c_new_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
struct i2c_client * i2c_new_device(struct i2c_adapter * adap, const struct i2c_board_info * info)
```

```json
{
  "name": "i2c_new_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587750586,
      "name": "i2c_new_device",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:823",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:i2c_new_probed_device",
        "drivers/i2c/i2c-core-base.c:i2c_detect",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter"
      ],
      "caller_func": [
        "drivers/mfd/htc-i2cpld.c:htcpld_setup_chips",
        "drivers/i2c/i2c-core-smbus.c:i2c_setup_smbus_alert",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587748368,
      "name": "i2c_new_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
struct i2c_client * i2c_new_device(struct i2c_adapter * adap, const struct i2c_board_info * info)
```
</details>
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
struct i2c_client * i2c_new_device(struct i2c_adapter * adap, const struct i2c_board_info * info)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
struct i2c_client * i2c_new_device(struct i2c_adapter * adap, const struct i2c_board_info * info)
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
