# Function: <code>device_add_properties</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int device_add_properties(struct device * dev, struct property_entry * properties)
```

```json
{
  "name": "device_add_properties",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584758832,
      "name": "device_add_properties",
      "external": true,
      "loc": "drivers/base/property.c:850",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/platform.c:platform_device_register_full"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584758832,
      "name": "device_add_properties",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 657
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
int device_add_properties(struct device * dev, struct property_entry * properties)
```

```json
{
  "name": "device_add_properties",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584949056,
      "name": "device_add_properties",
      "external": true,
      "loc": "drivers/base/property.c:850",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/platform.c:platform_device_register_full",
        "drivers/firmware/efi/apple-properties.c:map_properties"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584949056,
      "name": "device_add_properties",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 657
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
int device_add_properties(struct device * dev, const struct property_entry * properties)
```

```json
{
  "name": "device_add_properties",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585034224,
      "name": "device_add_properties",
      "external": true,
      "loc": "drivers/base/property.c:889",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/platform.c:platform_device_register_full",
        "drivers/spi/spi.c:spi_new_device",
        "drivers/i2c/i2c-core-base.c:i2c_new_device",
        "drivers/firmware/efi/apple-properties.c:map_properties"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585034224,
      "name": "device_add_properties",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
int device_add_properties(struct device * dev, const struct property_entry * properties)
```

```json
{
  "name": "device_add_properties",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585457088,
      "name": "device_add_properties",
      "external": true,
      "loc": "drivers/base/property.c:931",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/platform.c:platform_device_register_full",
        "drivers/spi/spi.c:spi_new_device",
        "drivers/i2c/i2c-core-base.c:i2c_new_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585457088,
      "name": "device_add_properties",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
int device_add_properties(struct device * dev, const struct property_entry * properties)
```

```json
{
  "name": "device_add_properties",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585700848,
      "name": "device_add_properties",
      "external": true,
      "loc": "drivers/base/property.c:991",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/platform.c:platform_device_register_full",
        "drivers/spi/spi.c:spi_new_device",
        "drivers/i2c/i2c-core-base.c:i2c_new_device",
        "drivers/firmware/efi/apple-properties.c:map_properties"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585700848,
      "name": "device_add_properties",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
int device_add_properties(struct device * dev, const struct property_entry * properties)
```

```json
{
  "name": "device_add_properties",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585827744,
      "name": "device_add_properties",
      "external": true,
      "loc": "drivers/base/property.c:521",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/platform.c:platform_device_register_full",
        "drivers/spi/spi.c:spi_new_device",
        "drivers/i2c/i2c-core-base.c:i2c_new_device",
        "drivers/firmware/efi/apple-properties.c:map_properties"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585827744,
      "name": "device_add_properties",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int device_add_properties(struct device * dev, const struct property_entry * properties)
```

```json
{
  "name": "device_add_properties",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586062256,
      "name": "device_add_properties",
      "external": true,
      "loc": "drivers/base/property.c:545",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/platform.c:platform_device_register_full",
        "drivers/spi/spi.c:spi_new_device",
        "drivers/i2c/i2c-core-base.c:i2c_new_client_device",
        "drivers/firmware/efi/apple-properties.c:unmarshal_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586062256,
      "name": "device_add_properties",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int device_add_properties(struct device * dev, const struct property_entry * properties)
```

```json
{
  "name": "device_add_properties",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586210144,
      "name": "device_add_properties",
      "external": true,
      "loc": "drivers/base/property.c:545",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/platform.c:platform_device_register_full",
        "drivers/spi/spi.c:spi_new_device",
        "drivers/i2c/i2c-core-base.c:i2c_new_client_device",
        "drivers/firmware/efi/apple-properties.c:unmarshal_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586210144,
      "name": "device_add_properties",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
int device_add_properties(struct device * dev, const struct property_entry * properties)
```

```json
{
  "name": "device_add_properties",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586973680,
      "name": "device_add_properties",
      "external": true,
      "loc": "drivers/base/property.c:545",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/platform.c:platform_device_register_full",
        "drivers/spi/spi.c:spi_new_device",
        "drivers/i2c/i2c-core-base.c:i2c_new_client_device",
        "drivers/firmware/efi/apple-properties.c:unmarshal_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586973680,
      "name": "device_add_properties",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
int device_add_properties(struct device * dev, const struct property_entry * properties)
```

```json
{
  "name": "device_add_properties",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587059344,
      "name": "device_add_properties",
      "external": true,
      "loc": "drivers/base/property.c:545",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/platform.c:platform_device_register_full",
        "drivers/spi/spi.c:spi_new_device",
        "drivers/i2c/i2c-core-base.c:i2c_new_client_device",
        "drivers/firmware/efi/apple-properties.c:unmarshal_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587059344,
      "name": "device_add_properties",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
int device_add_properties(struct device * dev, const struct property_entry * properties)
```

```json
{
  "name": "device_add_properties",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586943184,
      "name": "device_add_properties",
      "external": true,
      "loc": "drivers/base/property.c:545",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/platform.c:platform_device_register_full",
        "drivers/firmware/efi/apple-properties.c:unmarshal_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586943184,
      "name": "device_add_properties",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
int device_add_properties(struct device * dev, const struct property_entry * properties)
```

```json
{
  "name": "device_add_properties",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587507504,
      "name": "device_add_properties",
      "external": true,
      "loc": "drivers/base/property.c:545",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:quirk_huawei_pcie_sva"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587507504,
      "name": "device_add_properties",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
    }
  ]
}
```
</details>
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int device_add_properties(struct device * dev, const struct property_entry * properties)
```

```json
{
  "name": "device_add_properties",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499015688,
      "name": "device_add_properties",
      "external": true,
      "loc": "drivers/base/property.c:545",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/platform.c:platform_device_register_full",
        "drivers/spi/spi.c:spi_new_device",
        "drivers/i2c/i2c-core-base.c:i2c_new_client_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499015688,
      "name": "device_add_properties",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int device_add_properties(struct device * dev, const struct property_entry * properties)
```

```json
{
  "name": "device_add_properties",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231578756,
      "name": "device_add_properties",
      "external": true,
      "loc": "drivers/base/property.c:545",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/platform.c:platform_device_register_full",
        "drivers/spi/spi.c:spi_new_device",
        "drivers/i2c/i2c-core-base.c:i2c_new_client_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231578756,
      "name": "device_add_properties",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int device_add_properties(struct device * dev, const struct property_entry * properties)
```

```json
{
  "name": "device_add_properties",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292177552,
      "name": "device_add_properties",
      "external": true,
      "loc": "drivers/base/property.c:545",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/platform.c:platform_device_register_full",
        "drivers/spi/spi.c:spi_new_device",
        "drivers/i2c/i2c-core-base.c:i2c_new_client_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292177552,
      "name": "device_add_properties",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
int device_add_properties(struct device * dev, const struct property_entry * properties)
```

```json
{
  "name": "device_add_properties",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276384198,
      "name": "device_add_properties",
      "external": true,
      "loc": "drivers/base/property.c:545",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/platform.c:platform_device_register_full",
        "drivers/spi/spi.c:spi_new_device",
        "drivers/i2c/i2c-core-base.c:i2c_new_client_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276384198,
      "name": "device_add_properties",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int device_add_properties(struct device * dev, const struct property_entry * properties)
```

```json
{
  "name": "device_add_properties",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585970352,
      "name": "device_add_properties",
      "external": true,
      "loc": "drivers/base/property.c:545",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/platform.c:platform_device_register_full",
        "drivers/spi/spi.c:spi_new_device",
        "drivers/firmware/efi/apple-properties.c:unmarshal_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585970352,
      "name": "device_add_properties",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int device_add_properties(struct device * dev, const struct property_entry * properties)
```

```json
{
  "name": "device_add_properties",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585819616,
      "name": "device_add_properties",
      "external": true,
      "loc": "drivers/base/property.c:545",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/platform.c:platform_device_register_full",
        "drivers/spi/spi.c:spi_new_device",
        "drivers/firmware/efi/apple-properties.c:unmarshal_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585819616,
      "name": "device_add_properties",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int device_add_properties(struct device * dev, const struct property_entry * properties)
```

```json
{
  "name": "device_add_properties",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586160160,
      "name": "device_add_properties",
      "external": true,
      "loc": "drivers/base/property.c:545",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/platform.c:platform_device_register_full",
        "drivers/spi/spi.c:spi_new_device",
        "drivers/i2c/i2c-core-base.c:i2c_new_client_device",
        "drivers/firmware/efi/apple-properties.c:unmarshal_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586160160,
      "name": "device_add_properties",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int device_add_properties(struct device * dev, const struct property_entry * properties)
```

```json
{
  "name": "device_add_properties",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586268864,
      "name": "device_add_properties",
      "external": true,
      "loc": "drivers/base/property.c:545",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/platform.c:platform_device_register_full",
        "drivers/spi/spi.c:spi_new_device",
        "drivers/i2c/i2c-core-base.c:i2c_new_client_device",
        "drivers/firmware/efi/apple-properties.c:unmarshal_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586268864,
      "name": "device_add_properties",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
int device_add_properties(struct device * dev, struct property_entry * properties)
```
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct property_entry * properties</code> ➡️ <code>const struct property_entry * properties</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
int device_add_properties(struct device * dev, const struct property_entry * properties)
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
