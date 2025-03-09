# Function: <code>acpi_processor_get_power_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int acpi_processor_get_power_info(struct acpi_processor * pr)
```

```json
{
  "name": "acpi_processor_get_power_info",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583745845,
      "name": "acpi_processor_get_power_info",
      "external": false,
      "loc": "drivers/acpi/processor_idle.c:613",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_processor_hotplug",
        "drivers/acpi/processor_idle.c:acpi_processor_cst_has_changed",
        "drivers/acpi/processor_idle.c:acpi_processor_cst_has_changed",
        "drivers/acpi/processor_idle.c:acpi_processor_power_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583745845,
      "name": "acpi_processor_get_power_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1300
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
int acpi_processor_get_power_info(struct acpi_processor * pr)
```

```json
{
  "name": "acpi_processor_get_power_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584071613,
      "name": "acpi_processor_get_power_info",
      "external": false,
      "loc": "drivers/acpi/processor_idle.c:1324",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_processor_power_init",
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed",
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed",
        "drivers/acpi/processor_idle.c:acpi_processor_hotplug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584071613,
      "name": "acpi_processor_get_power_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1319
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
int acpi_processor_get_power_info(struct acpi_processor * pr)
```

```json
{
  "name": "acpi_processor_get_power_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584214161,
      "name": "acpi_processor_get_power_info",
      "external": false,
      "loc": "drivers/acpi/processor_idle.c:1325",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_processor_power_init",
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed",
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed",
        "drivers/acpi/processor_idle.c:acpi_processor_hotplug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584214161,
      "name": "acpi_processor_get_power_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1322
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
int acpi_processor_get_power_info(struct acpi_processor * pr)
```

```json
{
  "name": "acpi_processor_get_power_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584285056,
      "name": "acpi_processor_get_power_info",
      "external": false,
      "loc": "drivers/acpi/processor_idle.c:1325",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_processor_power_init",
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed",
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed",
        "drivers/acpi/processor_idle.c:acpi_processor_hotplug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584285056,
      "name": "acpi_processor_get_power_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1671
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
int acpi_processor_get_power_info(struct acpi_processor * pr)
```

```json
{
  "name": "acpi_processor_get_power_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584681552,
      "name": "acpi_processor_get_power_info",
      "external": false,
      "loc": "drivers/acpi/processor_idle.c:1334",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_processor_power_init",
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed",
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed",
        "drivers/acpi/processor_idle.c:acpi_processor_hotplug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584681552,
      "name": "acpi_processor_get_power_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2449
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
int acpi_processor_get_power_info(struct acpi_processor * pr)
```

```json
{
  "name": "acpi_processor_get_power_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_processor_get_power_info",
      "external": false,
      "loc": "drivers/acpi/processor_idle.c:1338",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_processor_power_init",
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed",
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed",
        "drivers/acpi/processor_idle.c:acpi_processor_hotplug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584907824,
      "name": "acpi_processor_get_power_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2319
    },
    {
      "addr": 18446744071584912918,
      "name": "acpi_processor_get_power_info.cold.17",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
int acpi_processor_get_power_info(struct acpi_processor * pr)
```

```json
{
  "name": "acpi_processor_get_power_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_processor_get_power_info",
      "external": false,
      "loc": "drivers/acpi/processor_idle.c:1339",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_processor_power_init",
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed",
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed",
        "drivers/acpi/processor_idle.c:acpi_processor_hotplug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585011696,
      "name": "acpi_processor_get_power_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2322
    },
    {
      "addr": 18446744071585016822,
      "name": "acpi_processor_get_power_info.cold.17",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int acpi_processor_get_power_info(struct acpi_processor * pr)
```

```json
{
  "name": "acpi_processor_get_power_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_processor_get_power_info",
      "external": false,
      "loc": "drivers/acpi/processor_idle.c:1334",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_processor_power_init",
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed",
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed",
        "drivers/acpi/processor_idle.c:acpi_processor_hotplug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585215296,
      "name": "acpi_processor_get_power_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2400
    },
    {
      "addr": 18446744071585220489,
      "name": "acpi_processor_get_power_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
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
int acpi_processor_get_power_info(struct acpi_processor * pr)
```

```json
{
  "name": "acpi_processor_get_power_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_processor_get_power_info",
      "external": false,
      "loc": "drivers/acpi/processor_idle.c:1334",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_processor_power_init",
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed",
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed",
        "drivers/acpi/processor_idle.c:acpi_processor_hotplug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585351744,
      "name": "acpi_processor_get_power_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2400
    },
    {
      "addr": 18446744071585356921,
      "name": "acpi_processor_get_power_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
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
  "name": "acpi_processor_get_power_info",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586064096,
      "name": "acpi_processor_get_power_info",
      "external": false,
      "loc": "drivers/acpi/processor_idle.c:1194",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_processor_power_init",
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed",
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed",
        "drivers/acpi/processor_idle.c:acpi_processor_hotplug"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_processor_get_power_info",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586186112,
      "name": "acpi_processor_get_power_info",
      "external": false,
      "loc": "drivers/acpi/processor_idle.c:1214",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_processor_power_init",
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed",
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed",
        "drivers/acpi/processor_idle.c:acpi_processor_hotplug"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int acpi_processor_get_power_info(struct acpi_processor * pr)
```

```json
{
  "name": "acpi_processor_get_power_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586059904,
      "name": "acpi_processor_get_power_info",
      "external": false,
      "loc": "drivers/acpi/processor_idle.c:1248",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_processor_power_init",
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed",
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed",
        "drivers/acpi/processor_idle.c:acpi_processor_hotplug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586059904,
      "name": "acpi_processor_get_power_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
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
int acpi_processor_get_power_info(struct acpi_processor * pr)
```

```json
{
  "name": "acpi_processor_get_power_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586552512,
      "name": "acpi_processor_get_power_info",
      "external": false,
      "loc": "drivers/acpi/processor_idle.c:1249",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_processor_power_init",
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed",
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed",
        "drivers/acpi/processor_idle.c:acpi_processor_hotplug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586552512,
      "name": "acpi_processor_get_power_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 287
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
int acpi_processor_get_power_info(struct acpi_processor * pr)
```

```json
{
  "name": "acpi_processor_get_power_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_processor_get_power_info",
      "external": false,
      "loc": "drivers/acpi/processor_idle.c:1258",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_processor_power_init",
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed",
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed",
        "drivers/acpi/processor_idle.c:acpi_processor_hotplug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587812000,
      "name": "acpi_processor_get_power_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 317
    },
    {
      "addr": 18446744071594284095,
      "name": "acpi_processor_get_power_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
  "name": "acpi_processor_get_power_info",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589155904,
      "name": "acpi_processor_get_power_info",
      "external": false,
      "loc": "drivers/acpi/processor_idle.c:1277",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_processor_power_init",
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed",
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed",
        "drivers/acpi/processor_idle.c:acpi_processor_hotplug"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_processor_get_power_info",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589449091,
      "name": "acpi_processor_get_power_info",
      "external": false,
      "loc": "drivers/acpi/processor_idle.c:1279",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_processor_power_init",
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed",
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed",
        "drivers/acpi/processor_idle.c:acpi_processor_hotplug"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_processor_get_power_info",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589757024,
      "name": "acpi_processor_get_power_info",
      "external": false,
      "loc": "drivers/acpi/processor_idle.c:1278",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_processor_power_init",
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed",
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed",
        "drivers/acpi/processor_idle.c:acpi_processor_hotplug"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
  "name": "acpi_processor_get_power_info",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336497639096,
      "name": "acpi_processor_get_power_info",
      "external": false,
      "loc": "drivers/acpi/processor_idle.c:1334",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_processor_power_init",
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed",
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed",
        "drivers/acpi/processor_idle.c:acpi_processor_hotplug"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int acpi_processor_get_power_info(struct acpi_processor * pr)
```

```json
{
  "name": "acpi_processor_get_power_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_processor_get_power_info",
      "external": false,
      "loc": "drivers/acpi/processor_idle.c:1334",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_processor_power_init",
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed",
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed",
        "drivers/acpi/processor_idle.c:acpi_processor_hotplug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585153856,
      "name": "acpi_processor_get_power_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1612
    },
    {
      "addr": 18446744071585158249,
      "name": "acpi_processor_get_power_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int acpi_processor_get_power_info(struct acpi_processor * pr)
```

```json
{
  "name": "acpi_processor_get_power_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_processor_get_power_info",
      "external": false,
      "loc": "drivers/acpi/processor_idle.c:1334",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_processor_power_init",
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed",
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed",
        "drivers/acpi/processor_idle.c:acpi_processor_hotplug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585068016,
      "name": "acpi_processor_get_power_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1612
    },
    {
      "addr": 18446744071585072409,
      "name": "acpi_processor_get_power_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int acpi_processor_get_power_info(struct acpi_processor * pr)
```

```json
{
  "name": "acpi_processor_get_power_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_processor_get_power_info",
      "external": false,
      "loc": "drivers/acpi/processor_idle.c:1334",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_processor_power_init",
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed",
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed",
        "drivers/acpi/processor_idle.c:acpi_processor_hotplug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585303328,
      "name": "acpi_processor_get_power_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2400
    },
    {
      "addr": 18446744071585308505,
      "name": "acpi_processor_get_power_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
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
int acpi_processor_get_power_info(struct acpi_processor * pr)
```

```json
{
  "name": "acpi_processor_get_power_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_processor_get_power_info",
      "external": false,
      "loc": "drivers/acpi/processor_idle.c:1334",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_processor_power_init",
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed",
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed",
        "drivers/acpi/processor_idle.c:acpi_processor_hotplug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585409488,
      "name": "acpi_processor_get_power_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2400
    },
    {
      "addr": 18446744071585414649,
      "name": "acpi_processor_get_power_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
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
int acpi_processor_get_power_info(struct acpi_processor * pr)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
int acpi_processor_get_power_info(struct acpi_processor * pr)
```
</details>
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
int acpi_processor_get_power_info(struct acpi_processor * pr)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int acpi_processor_get_power_info(struct acpi_processor * pr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int acpi_processor_get_power_info(struct acpi_processor * pr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int acpi_processor_get_power_info(struct acpi_processor * pr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int acpi_processor_get_power_info(struct acpi_processor * pr)
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
