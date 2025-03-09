# Function: <code>__acpi_match_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
const struct acpi_device_id * __acpi_match_device(struct acpi_device * device, const struct acpi_device_id * ids, const struct of_device_id * of_ids)
```

```json
{
  "name": "__acpi_match_device",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583557831,
      "name": "__acpi_match_device",
      "external": false,
      "loc": "drivers/acpi/bus.c:617",
      "file": "drivers/acpi/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/bus.c:acpi_match_device_ids",
        "drivers/acpi/bus.c:acpi_match_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583557831,
      "name": "__acpi_match_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 309
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
const struct acpi_device_id * __acpi_match_device(struct acpi_device * device, const struct acpi_device_id * ids, const struct of_device_id * of_ids)
```

```json
{
  "name": "__acpi_match_device",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583879389,
      "name": "__acpi_match_device",
      "external": false,
      "loc": "drivers/acpi/bus.c:693",
      "file": "drivers/acpi/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/bus.c:acpi_match_device_ids",
        "drivers/acpi/bus.c:acpi_match_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583879389,
      "name": "__acpi_match_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 311
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
const struct acpi_device_id * __acpi_match_device(struct acpi_device * device, const struct acpi_device_id * ids, const struct of_device_id * of_ids)
```

```json
{
  "name": "__acpi_match_device",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584018443,
      "name": "__acpi_match_device",
      "external": false,
      "loc": "drivers/acpi/bus.c:703",
      "file": "drivers/acpi/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/bus.c:acpi_match_device_ids",
        "drivers/acpi/bus.c:acpi_match_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584018443,
      "name": "__acpi_match_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 311
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
const struct acpi_device_id * __acpi_match_device(struct acpi_device * device, const struct acpi_device_id * ids, const struct of_device_id * of_ids)
```

```json
{
  "name": "__acpi_match_device",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584071280,
      "name": "__acpi_match_device",
      "external": false,
      "loc": "drivers/acpi/bus.c:731",
      "file": "drivers/acpi/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/bus.c:acpi_bus_match",
        "drivers/acpi/bus.c:acpi_match_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584071280,
      "name": "__acpi_match_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 353
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
const struct acpi_device_id * __acpi_match_device(struct acpi_device * device, const struct acpi_device_id * ids, const struct of_device_id * of_ids)
```

```json
{
  "name": "__acpi_match_device",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584340960,
      "name": "__acpi_match_device",
      "external": false,
      "loc": "drivers/acpi/bus.c:758",
      "file": "drivers/acpi/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/bus.c:acpi_bus_match",
        "drivers/acpi/bus.c:acpi_match_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584340960,
      "name": "__acpi_match_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 353
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__acpi_match_device",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584562704,
      "name": "__acpi_match_device",
      "external": false,
      "loc": "drivers/acpi/bus.c:770",
      "file": "drivers/acpi/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/bus.c:acpi_bus_match",
        "drivers/acpi/bus.c:acpi_bus_match",
        "drivers/acpi/bus.c:acpi_match_device"
      ],
      "caller_func": [
        "drivers/acpi/bus.c:acpi_bus_match",
        "drivers/acpi/bus.c:acpi_match_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584562352,
      "name": "__acpi_match_device.part.6.constprop.11",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 332
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__acpi_match_device",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584660016,
      "name": "__acpi_match_device",
      "external": false,
      "loc": "drivers/acpi/bus.c:739",
      "file": "drivers/acpi/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/bus.c:acpi_bus_match",
        "drivers/acpi/bus.c:acpi_bus_match",
        "drivers/acpi/bus.c:acpi_match_device"
      ],
      "caller_func": [
        "drivers/acpi/bus.c:acpi_bus_match",
        "drivers/acpi/bus.c:acpi_match_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584659664,
      "name": "__acpi_match_device.part.6.constprop.11",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 332
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__acpi_match_device",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584860064,
      "name": "__acpi_match_device",
      "external": false,
      "loc": "drivers/acpi/bus.c:726",
      "file": "drivers/acpi/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/bus.c:acpi_bus_match",
        "drivers/acpi/bus.c:acpi_bus_match",
        "drivers/acpi/bus.c:acpi_match_device"
      ],
      "caller_func": [
        "drivers/acpi/bus.c:acpi_bus_match",
        "drivers/acpi/bus.c:acpi_match_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584859712,
      "name": "__acpi_match_device.part.0.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 334
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__acpi_match_device",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584995936,
      "name": "__acpi_match_device",
      "external": false,
      "loc": "drivers/acpi/bus.c:726",
      "file": "drivers/acpi/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/bus.c:acpi_bus_match",
        "drivers/acpi/bus.c:acpi_bus_match",
        "drivers/acpi/bus.c:acpi_match_device"
      ],
      "caller_func": [
        "drivers/acpi/bus.c:acpi_bus_match",
        "drivers/acpi/bus.c:acpi_match_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584995584,
      "name": "__acpi_match_device.part.0.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 334
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__acpi_match_device",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585694225,
      "name": "__acpi_match_device",
      "external": false,
      "loc": "drivers/acpi/bus.c:726",
      "file": "drivers/acpi/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/bus.c:acpi_bus_match",
        "drivers/acpi/bus.c:acpi_device_get_match_data"
      ],
      "caller_func": [
        "drivers/acpi/bus.c:acpi_bus_match",
        "drivers/acpi/bus.c:acpi_device_get_match_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585693200,
      "name": "__acpi_match_device.part.0.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 334
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__acpi_match_device",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585816465,
      "name": "__acpi_match_device",
      "external": false,
      "loc": "drivers/acpi/bus.c:731",
      "file": "drivers/acpi/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/bus.c:acpi_bus_match",
        "drivers/acpi/bus.c:acpi_device_get_match_data"
      ],
      "caller_func": [
        "drivers/acpi/bus.c:acpi_bus_match",
        "drivers/acpi/bus.c:acpi_device_get_match_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585815424,
      "name": "__acpi_match_device.part.0.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 334
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__acpi_match_device",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585696481,
      "name": "__acpi_match_device",
      "external": false,
      "loc": "drivers/acpi/bus.c:810",
      "file": "drivers/acpi/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/bus.c:acpi_bus_match",
        "drivers/acpi/bus.c:acpi_device_get_match_data"
      ],
      "caller_func": [
        "drivers/acpi/bus.c:acpi_bus_match",
        "drivers/acpi/bus.c:acpi_device_get_match_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585695872,
      "name": "__acpi_match_device.part.0.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 327
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__acpi_match_device",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586176801,
      "name": "__acpi_match_device",
      "external": false,
      "loc": "drivers/acpi/bus.c:812",
      "file": "drivers/acpi/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/bus.c:acpi_bus_match",
        "drivers/acpi/bus.c:acpi_device_get_match_data"
      ],
      "caller_func": [
        "drivers/acpi/bus.c:acpi_bus_match",
        "drivers/acpi/bus.c:acpi_device_get_match_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586176192,
      "name": "__acpi_match_device.part.0.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 327
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__acpi_match_device",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587411424,
      "name": "__acpi_match_device",
      "external": false,
      "loc": "drivers/acpi/bus.c:849",
      "file": "drivers/acpi/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/bus.c:acpi_bus_match",
        "drivers/acpi/bus.c:acpi_device_get_match_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587411424,
      "name": "__acpi_match_device.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 379
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__acpi_match_device",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588667104,
      "name": "__acpi_match_device",
      "external": false,
      "loc": "drivers/acpi/bus.c:855",
      "file": "drivers/acpi/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/bus.c:acpi_bus_match",
        "drivers/acpi/bus.c:acpi_driver_match_device",
        "drivers/acpi/bus.c:acpi_device_get_match_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588667104,
      "name": "__acpi_match_device.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 376
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__acpi_match_device",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588954272,
      "name": "__acpi_match_device",
      "external": false,
      "loc": "drivers/acpi/bus.c:811",
      "file": "drivers/acpi/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/bus.c:acpi_bus_match",
        "drivers/acpi/bus.c:acpi_driver_match_device",
        "drivers/acpi/bus.c:acpi_device_get_match_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588954272,
      "name": "__acpi_match_device.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 376
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__acpi_match_device",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589251024,
      "name": "__acpi_match_device",
      "external": false,
      "loc": "drivers/acpi/bus.c:861",
      "file": "drivers/acpi/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/bus.c:acpi_bus_match",
        "drivers/acpi/bus.c:acpi_driver_match_device",
        "drivers/acpi/bus.c:acpi_device_get_match_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589251024,
      "name": "__acpi_match_device.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 376
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "__acpi_match_device",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336497405184,
      "name": "__acpi_match_device",
      "external": false,
      "loc": "drivers/acpi/bus.c:726",
      "file": "drivers/acpi/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/bus.c:acpi_bus_match",
        "drivers/acpi/bus.c:acpi_bus_match",
        "drivers/acpi/bus.c:acpi_match_device"
      ],
      "caller_func": [
        "drivers/acpi/bus.c:acpi_bus_match",
        "drivers/acpi/bus.c:acpi_match_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497404776,
      "name": "__acpi_match_device.part.0.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 368
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__acpi_match_device",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584939840,
      "name": "__acpi_match_device",
      "external": false,
      "loc": "drivers/acpi/bus.c:726",
      "file": "drivers/acpi/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/bus.c:acpi_bus_match",
        "drivers/acpi/bus.c:acpi_bus_match",
        "drivers/acpi/bus.c:acpi_match_device"
      ],
      "caller_func": [
        "drivers/acpi/bus.c:acpi_bus_match",
        "drivers/acpi/bus.c:acpi_match_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584939488,
      "name": "__acpi_match_device.part.0.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 334
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__acpi_match_device",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584848640,
      "name": "__acpi_match_device",
      "external": false,
      "loc": "drivers/acpi/bus.c:726",
      "file": "drivers/acpi/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/bus.c:acpi_bus_match",
        "drivers/acpi/bus.c:acpi_bus_match",
        "drivers/acpi/bus.c:acpi_match_device"
      ],
      "caller_func": [
        "drivers/acpi/bus.c:acpi_bus_match",
        "drivers/acpi/bus.c:acpi_match_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584848288,
      "name": "__acpi_match_device.part.0.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 334
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__acpi_match_device",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584947520,
      "name": "__acpi_match_device",
      "external": false,
      "loc": "drivers/acpi/bus.c:726",
      "file": "drivers/acpi/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/bus.c:acpi_bus_match",
        "drivers/acpi/bus.c:acpi_bus_match",
        "drivers/acpi/bus.c:acpi_match_device"
      ],
      "caller_func": [
        "drivers/acpi/bus.c:acpi_bus_match",
        "drivers/acpi/bus.c:acpi_match_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584947168,
      "name": "__acpi_match_device.part.0.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 334
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__acpi_match_device",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585053696,
      "name": "__acpi_match_device",
      "external": false,
      "loc": "drivers/acpi/bus.c:726",
      "file": "drivers/acpi/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/bus.c:acpi_bus_match",
        "drivers/acpi/bus.c:acpi_bus_match",
        "drivers/acpi/bus.c:acpi_match_device"
      ],
      "caller_func": [
        "drivers/acpi/bus.c:acpi_bus_match",
        "drivers/acpi/bus.c:acpi_match_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585053344,
      "name": "__acpi_match_device.part.0.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 334
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
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
const struct acpi_device_id * __acpi_match_device(struct acpi_device * device, const struct acpi_device_id * ids, const struct of_device_id * of_ids)
```
</details>
</li>
</ul>
