# Function: <code>i2c_new_client_device</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
struct i2c_client * i2c_new_client_device(struct i2c_adapter * adap, const struct i2c_board_info * info)
```

```json
{
  "name": "i2c_new_client_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "i2c_new_client_device",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:727",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_new_probed_device",
        "drivers/i2c/i2c-core-base.c:i2c_detect",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_sysfs_new_device",
        "drivers/i2c/i2c-core-base.c:i2c_new_dummy_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587486297,
      "name": "i2c_new_client_device.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    },
    {
      "addr": 18446744071587482016,
      "name": "i2c_new_client_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 634
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
struct i2c_client * i2c_new_client_device(struct i2c_adapter * adap, const struct i2c_board_info * info)
```

```json
{
  "name": "i2c_new_client_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "i2c_new_client_device",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:732",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_new_probed_device",
        "drivers/i2c/i2c-core-base.c:i2c_detect",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_sysfs_new_device",
        "drivers/i2c/i2c-core-base.c:i2c_new_dummy_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587689496,
      "name": "i2c_new_client_device.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    },
    {
      "addr": 18446744071587685280,
      "name": "i2c_new_client_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 634
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
struct i2c_client * i2c_new_client_device(struct i2c_adapter * adap, const struct i2c_board_info * info)
```

```json
{
  "name": "i2c_new_client_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "i2c_new_client_device",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:742",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/htc-i2cpld.c:htcpld_register_chip_i2c",
        "drivers/i2c/i2c-core-base.c:i2c_new_scanned_device",
        "drivers/i2c/i2c-core-base.c:i2c_detect_address",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/i2c/i2c-core-base.c:new_device_store",
        "drivers/i2c/i2c-core-base.c:i2c_new_ancillary_device",
        "drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device",
        "drivers/i2c/i2c-core-smbus.c:i2c_new_smbus_alert_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588557747,
      "name": "i2c_new_client_device.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    },
    {
      "addr": 18446744071588553104,
      "name": "i2c_new_client_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 634
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
struct i2c_client * i2c_new_client_device(struct i2c_adapter * adap, const struct i2c_board_info * info)
```

```json
{
  "name": "i2c_new_client_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "i2c_new_client_device",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:870",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/htc-i2cpld.c:htcpld_register_chip_i2c",
        "drivers/i2c/i2c-core-base.c:i2c_new_scanned_device",
        "drivers/i2c/i2c-core-base.c:i2c_detect_address",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/i2c/i2c-core-base.c:new_device_store",
        "drivers/i2c/i2c-core-base.c:i2c_new_ancillary_device",
        "drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device",
        "drivers/i2c/i2c-core-smbus.c:i2c_new_smbus_alert_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591578176,
      "name": "i2c_new_client_device.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
    },
    {
      "addr": 18446744071588578512,
      "name": "i2c_new_client_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 674
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
struct i2c_client * i2c_new_client_device(struct i2c_adapter * adap, const struct i2c_board_info * info)
```

```json
{
  "name": "i2c_new_client_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "i2c_new_client_device",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:914",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/htc-i2cpld.c:htcpld_register_chip_i2c",
        "drivers/i2c/i2c-core-base.c:i2c_new_scanned_device",
        "drivers/i2c/i2c-core-base.c:i2c_detect_address",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/i2c/i2c-core-base.c:new_device_store",
        "drivers/i2c/i2c-core-base.c:i2c_new_ancillary_device",
        "drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device",
        "drivers/i2c/i2c-core-smbus.c:i2c_new_smbus_alert_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591521104,
      "name": "i2c_new_client_device.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
    },
    {
      "addr": 18446744071588462144,
      "name": "i2c_new_client_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 696
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
struct i2c_client * i2c_new_client_device(struct i2c_adapter * adap, const struct i2c_board_info * info)
```

```json
{
  "name": "i2c_new_client_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "i2c_new_client_device",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:915",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/htc-i2cpld.c:htcpld_register_chip_i2c",
        "drivers/i2c/i2c-core-base.c:i2c_new_scanned_device",
        "drivers/i2c/i2c-core-base.c:i2c_detect_address",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/i2c/i2c-core-base.c:new_device_store",
        "drivers/i2c/i2c-core-base.c:i2c_new_ancillary_device",
        "drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device",
        "drivers/i2c/i2c-core-smbus.c:i2c_new_smbus_alert_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592630325,
      "name": "i2c_new_client_device.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
    },
    {
      "addr": 18446744071589130240,
      "name": "i2c_new_client_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 693
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
struct i2c_client * i2c_new_client_device(struct i2c_adapter * adap, const struct i2c_board_info * info)
```

```json
{
  "name": "i2c_new_client_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "i2c_new_client_device",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:916",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/htc-i2cpld.c:htcpld_register_chip_i2c",
        "drivers/i2c/i2c-core-base.c:i2c_new_scanned_device",
        "drivers/i2c/i2c-core-base.c:i2c_detect_address",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/i2c/i2c-core-base.c:new_device_store",
        "drivers/i2c/i2c-core-base.c:i2c_new_ancillary_device",
        "drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device",
        "drivers/i2c/i2c-core-smbus.c:i2c_setup_smbus_alert",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device_by_fwnode",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594513883,
      "name": "i2c_new_client_device.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
    },
    {
      "addr": 18446744071590579632,
      "name": "i2c_new_client_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 704
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
struct i2c_client * i2c_new_client_device(struct i2c_adapter * adap, const struct i2c_board_info * info)
```

```json
{
  "name": "i2c_new_client_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592236848,
      "name": "i2c_new_client_device",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:917",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_new_scanned_device",
        "drivers/i2c/i2c-core-base.c:i2c_detect_address",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/i2c/i2c-core-base.c:new_device_store",
        "drivers/i2c/i2c-core-base.c:i2c_new_ancillary_device",
        "drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device",
        "drivers/i2c/i2c-core-smbus.c:i2c_setup_smbus_alert",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device_by_fwnode",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592236848,
      "name": "i2c_new_client_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 814
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
struct i2c_client * i2c_new_client_device(struct i2c_adapter * adap, const struct i2c_board_info * info)
```

```json
{
  "name": "i2c_new_client_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592661952,
      "name": "i2c_new_client_device",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:932",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_new_scanned_device",
        "drivers/i2c/i2c-core-base.c:i2c_detect_address",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/i2c/i2c-core-base.c:new_device_store",
        "drivers/i2c/i2c-core-base.c:i2c_new_ancillary_device",
        "drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device",
        "drivers/i2c/i2c-core-smbus.c:i2c_setup_smbus_alert",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device_by_fwnode",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592661952,
      "name": "i2c_new_client_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 802
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
struct i2c_client * i2c_new_client_device(struct i2c_adapter * adap, const struct i2c_board_info * info)
```

```json
{
  "name": "i2c_new_client_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593407152,
      "name": "i2c_new_client_device",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:935",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpu/drm/drm_encoder_slave.c:drm_i2c_encoder_init",
        "drivers/i2c/i2c-core-base.c:i2c_new_scanned_device",
        "drivers/i2c/i2c-core-base.c:i2c_detect_address",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/i2c/i2c-core-base.c:new_device_store",
        "drivers/i2c/i2c-core-base.c:i2c_new_ancillary_device",
        "drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device",
        "drivers/i2c/i2c-core-smbus.c:i2c_setup_smbus_alert",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device_by_fwnode",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593407152,
      "name": "i2c_new_client_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 893
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct i2c_client * i2c_new_client_device(struct i2c_adapter * adap, const struct i2c_board_info * info)
```

```json
{
  "name": "i2c_new_client_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500845176,
      "name": "i2c_new_client_device",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:732",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_new_probed_device",
        "drivers/i2c/i2c-core-base.c:i2c_detect",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_sysfs_new_device",
        "drivers/i2c/i2c-core-base.c:i2c_new_ancillary_device",
        "drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device",
        "drivers/i2c/i2c-core-base.c:i2c_new_dummy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500845176,
      "name": "i2c_new_client_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 692
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct i2c_client * i2c_new_client_device(struct i2c_adapter * adap, const struct i2c_board_info * info)
```

```json
{
  "name": "i2c_new_client_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233362312,
      "name": "i2c_new_client_device",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:732",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_new_probed_device",
        "drivers/i2c/i2c-core-base.c:i2c_detect",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_sysfs_new_device",
        "drivers/i2c/i2c-core-base.c:i2c_new_dummy_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233362312,
      "name": "i2c_new_client_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 636
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct i2c_client * i2c_new_client_device(struct i2c_adapter * adap, const struct i2c_board_info * info)
```

```json
{
  "name": "i2c_new_client_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294308208,
      "name": "i2c_new_client_device",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:732",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_new_probed_device",
        "drivers/i2c/i2c-core-base.c:i2c_detect",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_sysfs_new_device",
        "drivers/i2c/i2c-core-base.c:i2c_new_dummy_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294308208,
      "name": "i2c_new_client_device",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct i2c_client * i2c_new_client_device(struct i2c_adapter * adap, const struct i2c_board_info * info)
```

```json
{
  "name": "i2c_new_client_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277649510,
      "name": "i2c_new_client_device",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:732",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_new_probed_device",
        "drivers/i2c/i2c-core-base.c:i2c_detect",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_sysfs_new_device",
        "drivers/i2c/i2c-core-base.c:i2c_new_dummy_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277649510,
      "name": "i2c_new_client_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 598
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
struct i2c_client * i2c_new_client_device(struct i2c_adapter * adap, const struct i2c_board_info * info)
```

```json
{
  "name": "i2c_new_client_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "i2c_new_client_device",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:732",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_new_probed_device",
        "drivers/i2c/i2c-core-base.c:i2c_detect",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_sysfs_new_device",
        "drivers/i2c/i2c-core-base.c:i2c_new_dummy_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587640744,
      "name": "i2c_new_client_device.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    },
    {
      "addr": 18446744071587636528,
      "name": "i2c_new_client_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 634
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
struct i2c_client * i2c_new_client_device(struct i2c_adapter * adap, const struct i2c_board_info * info)
```

```json
{
  "name": "i2c_new_client_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "i2c_new_client_device",
      "external": true,
      "loc": "drivers/i2c/i2c-core-base.c:732",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_new_probed_device",
        "drivers/i2c/i2c-core-base.c:i2c_detect",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_sysfs_new_device",
        "drivers/i2c/i2c-core-base.c:i2c_new_dummy_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587751944,
      "name": "i2c_new_client_device.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    },
    {
      "addr": 18446744071587747728,
      "name": "i2c_new_client_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 634
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
<details>
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
struct i2c_client * i2c_new_client_device(struct i2c_adapter * adap, const struct i2c_board_info * info)
```
</details>
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
struct i2c_client * i2c_new_client_device(struct i2c_adapter * adap, const struct i2c_board_info * info)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
struct i2c_client * i2c_new_client_device(struct i2c_adapter * adap, const struct i2c_board_info * info)
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
