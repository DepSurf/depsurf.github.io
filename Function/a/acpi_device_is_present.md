# Function: <code>acpi_device_is_present</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
bool acpi_device_is_present(struct acpi_device * adev)
```

```json
{
  "name": "acpi_device_is_present",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583568052,
      "name": "acpi_device_is_present",
      "external": true,
      "loc": "drivers/acpi/scan.c:1487",
      "file": "drivers/acpi/scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/device_pm.c:acpi_bus_init_power",
        "drivers/acpi/scan.c:acpi_bus_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583568052,
      "name": "acpi_device_is_present",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
bool acpi_device_is_present(struct acpi_device * adev)
```

```json
{
  "name": "acpi_device_is_present",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583890144,
      "name": "acpi_device_is_present",
      "external": true,
      "loc": "drivers/acpi/scan.c:1545",
      "file": "drivers/acpi/scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/device_pm.c:acpi_bus_init_power",
        "drivers/acpi/scan.c:acpi_bus_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583890144,
      "name": "acpi_device_is_present",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
bool acpi_device_is_present(struct acpi_device * adev)
```

```json
{
  "name": "acpi_device_is_present",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584029258,
      "name": "acpi_device_is_present",
      "external": true,
      "loc": "drivers/acpi/scan.c:1575",
      "file": "drivers/acpi/scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/device_pm.c:acpi_bus_init_power",
        "drivers/acpi/scan.c:acpi_bus_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584029258,
      "name": "acpi_device_is_present",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool acpi_device_is_present(const struct acpi_device * adev)
```

```json
{
  "name": "acpi_device_is_present",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584086736,
      "name": "acpi_device_is_present",
      "external": true,
      "loc": "drivers/acpi/scan.c:1604",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/device_pm.c:acpi_bus_init_power",
        "drivers/acpi/property.c:acpi_fwnode_device_is_available"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584086736,
      "name": "acpi_device_is_present",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool acpi_device_is_present(const struct acpi_device * adev)
```

```json
{
  "name": "acpi_device_is_present",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584357504,
      "name": "acpi_device_is_present",
      "external": true,
      "loc": "drivers/acpi/scan.c:1703",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/device_pm.c:acpi_bus_init_power",
        "drivers/acpi/property.c:acpi_fwnode_device_is_available"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584357504,
      "name": "acpi_device_is_present",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool acpi_device_is_present(const struct acpi_device * adev)
```

```json
{
  "name": "acpi_device_is_present",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584568737,
      "name": "acpi_device_is_present",
      "external": true,
      "loc": "drivers/acpi/scan.c:1717",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_bus_attach"
      ],
      "caller_func": [
        "drivers/acpi/device_pm.c:acpi_bus_init_power"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584578384,
      "name": "acpi_device_is_present",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool acpi_device_is_present(const struct acpi_device * adev)
```

```json
{
  "name": "acpi_device_is_present",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584666529,
      "name": "acpi_device_is_present",
      "external": true,
      "loc": "drivers/acpi/scan.c:1730",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_bus_attach"
      ],
      "caller_func": [
        "drivers/acpi/device_pm.c:acpi_bus_init_power"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584675728,
      "name": "acpi_device_is_present",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
bool acpi_device_is_present(const struct acpi_device * adev)
```

```json
{
  "name": "acpi_device_is_present",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584866657,
      "name": "acpi_device_is_present",
      "external": true,
      "loc": "drivers/acpi/scan.c:1729",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_bus_attach"
      ],
      "caller_func": [
        "drivers/acpi/device_pm.c:acpi_bus_init_power",
        "drivers/acpi/property.c:acpi_fwnode_device_is_available"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584875520,
      "name": "acpi_device_is_present",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
bool acpi_device_is_present(const struct acpi_device * adev)
```

```json
{
  "name": "acpi_device_is_present",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585002529,
      "name": "acpi_device_is_present",
      "external": true,
      "loc": "drivers/acpi/scan.c:1729",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_bus_attach"
      ],
      "caller_func": [
        "drivers/acpi/device_pm.c:acpi_bus_init_power",
        "drivers/acpi/property.c:acpi_fwnode_device_is_available"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585011392,
      "name": "acpi_device_is_present",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
bool acpi_device_is_present(const struct acpi_device * adev)
```

```json
{
  "name": "acpi_device_is_present",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585702673,
      "name": "acpi_device_is_present",
      "external": true,
      "loc": "drivers/acpi/scan.c:1738",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_bus_attach"
      ],
      "caller_func": [
        "drivers/acpi/device_pm.c:acpi_bus_init_power",
        "drivers/acpi/property.c:acpi_fwnode_device_is_available"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585711024,
      "name": "acpi_device_is_present",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
bool acpi_device_is_present(const struct acpi_device * adev)
```

```json
{
  "name": "acpi_device_is_present",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585824459,
      "name": "acpi_device_is_present",
      "external": true,
      "loc": "drivers/acpi/scan.c:1811",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_bus_attach"
      ],
      "caller_func": [
        "drivers/acpi/device_pm.c:acpi_bus_init_power",
        "drivers/acpi/property.c:acpi_fwnode_device_is_available"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585834032,
      "name": "acpi_device_is_present",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
bool acpi_device_is_present(const struct acpi_device * adev)
```

```json
{
  "name": "acpi_device_is_present",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585704059,
      "name": "acpi_device_is_present",
      "external": true,
      "loc": "drivers/acpi/scan.c:1780",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_bus_attach"
      ],
      "caller_func": [
        "drivers/acpi/device_pm.c:acpi_bus_init_power",
        "drivers/acpi/property.c:acpi_fwnode_device_is_available"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585713328,
      "name": "acpi_device_is_present",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
bool acpi_device_is_present(const struct acpi_device * adev)
```

```json
{
  "name": "acpi_device_is_present",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586185019,
      "name": "acpi_device_is_present",
      "external": true,
      "loc": "drivers/acpi/scan.c:1878",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_bus_attach"
      ],
      "caller_func": [
        "drivers/acpi/device_pm.c:acpi_bus_init_power",
        "drivers/acpi/property.c:acpi_fwnode_device_is_available"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586194656,
      "name": "acpi_device_is_present",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
bool acpi_device_is_present(const struct acpi_device * adev)
```

```json
{
  "name": "acpi_device_is_present",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587420847,
      "name": "acpi_device_is_present",
      "external": true,
      "loc": "drivers/acpi/scan.c:1921",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_bus_attach"
      ],
      "caller_func": [
        "drivers/acpi/device_sysfs.c:__acpi_device_uevent_modalias",
        "drivers/acpi/device_pm.c:acpi_bus_init_power",
        "drivers/acpi/property.c:acpi_fwnode_device_is_available"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587430976,
      "name": "acpi_device_is_present",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
bool acpi_device_is_present(const struct acpi_device * adev)
```

```json
{
  "name": "acpi_device_is_present",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588677775,
      "name": "acpi_device_is_present",
      "external": true,
      "loc": "drivers/acpi/scan.c:1905",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_bus_attach"
      ],
      "caller_func": [
        "drivers/acpi/device_sysfs.c:__acpi_device_uevent_modalias",
        "drivers/acpi/device_pm.c:acpi_bus_init_power",
        "drivers/acpi/property.c:acpi_fwnode_device_is_available"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588689360,
      "name": "acpi_device_is_present",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
bool acpi_device_is_present(const struct acpi_device * adev)
```

```json
{
  "name": "acpi_device_is_present",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588965279,
      "name": "acpi_device_is_present",
      "external": true,
      "loc": "drivers/acpi/scan.c:1908",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_bus_attach"
      ],
      "caller_func": [
        "drivers/acpi/device_sysfs.c:__acpi_device_uevent_modalias",
        "drivers/acpi/device_pm.c:acpi_bus_init_power",
        "drivers/acpi/property.c:acpi_fwnode_device_is_available"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588977280,
      "name": "acpi_device_is_present",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
bool acpi_device_is_present(const struct acpi_device * adev)
```

```json
{
  "name": "acpi_device_is_present",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589262783,
      "name": "acpi_device_is_present",
      "external": true,
      "loc": "drivers/acpi/scan.c:1920",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_bus_attach",
        "drivers/acpi/scan.c:acpi_device_hotplug"
      ],
      "caller_func": [
        "drivers/acpi/device_sysfs.c:__acpi_device_uevent_modalias",
        "drivers/acpi/device_pm.c:acpi_bus_init_power",
        "drivers/acpi/property.c:acpi_fwnode_device_is_available"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589274912,
      "name": "acpi_device_is_present",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
bool acpi_device_is_present(const struct acpi_device * adev)
```

```json
{
  "name": "acpi_device_is_present",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336497412124,
      "name": "acpi_device_is_present",
      "external": true,
      "loc": "drivers/acpi/scan.c:1729",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_bus_attach"
      ],
      "caller_func": [
        "drivers/acpi/device_pm.c:acpi_bus_init_power",
        "drivers/acpi/property.c:acpi_fwnode_device_is_available"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497422328,
      "name": "acpi_device_is_present",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
bool acpi_device_is_present(const struct acpi_device * adev)
```

```json
{
  "name": "acpi_device_is_present",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584945625,
      "name": "acpi_device_is_present",
      "external": true,
      "loc": "drivers/acpi/scan.c:1729",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_bus_attach"
      ],
      "caller_func": [
        "drivers/acpi/device_pm.c:acpi_bus_init_power",
        "drivers/acpi/property.c:acpi_fwnode_device_is_available"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584954768,
      "name": "acpi_device_is_present",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
bool acpi_device_is_present(const struct acpi_device * adev)
```

```json
{
  "name": "acpi_device_is_present",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584854425,
      "name": "acpi_device_is_present",
      "external": true,
      "loc": "drivers/acpi/scan.c:1729",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_bus_attach"
      ],
      "caller_func": [
        "drivers/acpi/device_pm.c:acpi_bus_init_power",
        "drivers/acpi/property.c:acpi_fwnode_device_is_available"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584863568,
      "name": "acpi_device_is_present",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
bool acpi_device_is_present(const struct acpi_device * adev)
```

```json
{
  "name": "acpi_device_is_present",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584954113,
      "name": "acpi_device_is_present",
      "external": true,
      "loc": "drivers/acpi/scan.c:1729",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_bus_attach"
      ],
      "caller_func": [
        "drivers/acpi/device_pm.c:acpi_bus_init_power",
        "drivers/acpi/property.c:acpi_fwnode_device_is_available"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584962976,
      "name": "acpi_device_is_present",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
bool acpi_device_is_present(const struct acpi_device * adev)
```

```json
{
  "name": "acpi_device_is_present",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585060289,
      "name": "acpi_device_is_present",
      "external": true,
      "loc": "drivers/acpi/scan.c:1729",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_bus_attach"
      ],
      "caller_func": [
        "drivers/acpi/device_pm.c:acpi_bus_init_power",
        "drivers/acpi/property.c:acpi_fwnode_device_is_available"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585069152,
      "name": "acpi_device_is_present",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct acpi_device * adev</code> ➡️ <code>const struct acpi_device * adev</code>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
bool acpi_device_is_present(const struct acpi_device * adev)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
bool acpi_device_is_present(const struct acpi_device * adev)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
bool acpi_device_is_present(const struct acpi_device * adev)
```
</details>
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
