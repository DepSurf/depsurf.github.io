# Function: <code>acpi_processor_get_performance_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int acpi_processor_get_performance_info(struct acpi_processor * pr)
```

```json
{
  "name": "acpi_processor_get_performance_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583755977,
      "name": "acpi_processor_get_performance_info",
      "external": true,
      "loc": "drivers/acpi/processor_perflib.c:426",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_perflib.c:acpi_processor_register_performance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583755977,
      "name": "acpi_processor_get_performance_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 462
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
int acpi_processor_get_performance_info(struct acpi_processor * pr)
```

```json
{
  "name": "acpi_processor_get_performance_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584081293,
      "name": "acpi_processor_get_performance_info",
      "external": true,
      "loc": "drivers/acpi/processor_perflib.c:426",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_perflib.c:acpi_processor_register_performance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584081293,
      "name": "acpi_processor_get_performance_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1098
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
int acpi_processor_get_performance_info(struct acpi_processor * pr)
```

```json
{
  "name": "acpi_processor_get_performance_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584223873,
      "name": "acpi_processor_get_performance_info",
      "external": true,
      "loc": "drivers/acpi/processor_perflib.c:424",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_perflib.c:acpi_processor_register_performance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584223873,
      "name": "acpi_processor_get_performance_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1098
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
int acpi_processor_get_performance_info(struct acpi_processor * pr)
```

```json
{
  "name": "acpi_processor_get_performance_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584295952,
      "name": "acpi_processor_get_performance_info",
      "external": true,
      "loc": "drivers/acpi/processor_perflib.c:422",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_perflib.c:acpi_processor_register_performance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584295952,
      "name": "acpi_processor_get_performance_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1405
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
int acpi_processor_get_performance_info(struct acpi_processor * pr)
```

```json
{
  "name": "acpi_processor_get_performance_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584694720,
      "name": "acpi_processor_get_performance_info",
      "external": true,
      "loc": "drivers/acpi/processor_perflib.c:422",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_perflib.c:acpi_processor_register_performance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584694720,
      "name": "acpi_processor_get_performance_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1763
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
int acpi_processor_get_performance_info(struct acpi_processor * pr)
```

```json
{
  "name": "acpi_processor_get_performance_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_processor_get_performance_info",
      "external": true,
      "loc": "drivers/acpi/processor_perflib.c:423",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_perflib.c:acpi_processor_register_performance",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584925138,
      "name": "acpi_processor_get_performance_info.cold.10",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
    },
    {
      "addr": 18446744071584922448,
      "name": "acpi_processor_get_performance_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 558
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
int acpi_processor_get_performance_info(struct acpi_processor * pr)
```

```json
{
  "name": "acpi_processor_get_performance_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_processor_get_performance_info",
      "external": true,
      "loc": "drivers/acpi/processor_perflib.c:423",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_perflib.c:acpi_processor_register_performance",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585029042,
      "name": "acpi_processor_get_performance_info.cold.11",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
    },
    {
      "addr": 18446744071585026352,
      "name": "acpi_processor_get_performance_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 558
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
int acpi_processor_get_performance_info(struct acpi_processor * pr)
```

```json
{
  "name": "acpi_processor_get_performance_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_processor_get_performance_info",
      "external": true,
      "loc": "drivers/acpi/processor_perflib.c:410",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_perflib.c:acpi_processor_register_performance",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585232810,
      "name": "acpi_processor_get_performance_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
    },
    {
      "addr": 18446744071585230112,
      "name": "acpi_processor_get_performance_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 564
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
int acpi_processor_get_performance_info(struct acpi_processor * pr)
```

```json
{
  "name": "acpi_processor_get_performance_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_processor_get_performance_info",
      "external": true,
      "loc": "drivers/acpi/processor_perflib.c:396",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_perflib.c:acpi_processor_register_performance",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585369538,
      "name": "acpi_processor_get_performance_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
    },
    {
      "addr": 18446744071585366656,
      "name": "acpi_processor_get_performance_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 564
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
int acpi_processor_get_performance_info(struct acpi_processor * pr)
```

```json
{
  "name": "acpi_processor_get_performance_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_processor_get_performance_info",
      "external": true,
      "loc": "drivers/acpi/processor_perflib.c:396",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_perflib.c:acpi_processor_register_performance",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586077591,
      "name": "acpi_processor_get_performance_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071586074912,
      "name": "acpi_processor_get_performance_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 249
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
int acpi_processor_get_performance_info(struct acpi_processor * pr)
```

```json
{
  "name": "acpi_processor_get_performance_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_processor_get_performance_info",
      "external": true,
      "loc": "drivers/acpi/processor_perflib.c:395",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_perflib.c:acpi_processor_register_performance",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591439864,
      "name": "acpi_processor_get_performance_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071586196368,
      "name": "acpi_processor_get_performance_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 249
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
int acpi_processor_get_performance_info(struct acpi_processor * pr)
```

```json
{
  "name": "acpi_processor_get_performance_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_processor_get_performance_info",
      "external": true,
      "loc": "drivers/acpi/processor_perflib.c:394",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_perflib.c:acpi_processor_register_performance",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591381058,
      "name": "acpi_processor_get_performance_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071586071536,
      "name": "acpi_processor_get_performance_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
int acpi_processor_get_performance_info(struct acpi_processor * pr)
```

```json
{
  "name": "acpi_processor_get_performance_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_processor_get_performance_info",
      "external": true,
      "loc": "drivers/acpi/processor_perflib.c:392",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_perflib.c:acpi_processor_register_performance",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592417631,
      "name": "acpi_processor_get_performance_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071586566288,
      "name": "acpi_processor_get_performance_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 219
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
int acpi_processor_get_performance_info(struct acpi_processor * pr)
```

```json
{
  "name": "acpi_processor_get_performance_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_processor_get_performance_info",
      "external": true,
      "loc": "drivers/acpi/processor_perflib.c:392",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_perflib.c:acpi_processor_register_performance",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594285268,
      "name": "acpi_processor_get_performance_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071587826784,
      "name": "acpi_processor_get_performance_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
int acpi_processor_get_performance_info(struct acpi_processor * pr)
```

```json
{
  "name": "acpi_processor_get_performance_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589166384,
      "name": "acpi_processor_get_performance_info",
      "external": true,
      "loc": "drivers/acpi/processor_perflib.c:389",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_perflib.c:acpi_processor_register_performance",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589166384,
      "name": "acpi_processor_get_performance_info",
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
int acpi_processor_get_performance_info(struct acpi_processor * pr)
```

```json
{
  "name": "acpi_processor_get_performance_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589459760,
      "name": "acpi_processor_get_performance_info",
      "external": true,
      "loc": "drivers/acpi/processor_perflib.c:411",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_perflib.c:acpi_processor_register_performance",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589459760,
      "name": "acpi_processor_get_performance_info",
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
int acpi_processor_get_performance_info(struct acpi_processor * pr)
```

```json
{
  "name": "acpi_processor_get_performance_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589767760,
      "name": "acpi_processor_get_performance_info",
      "external": true,
      "loc": "drivers/acpi/processor_perflib.c:411",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_perflib.c:acpi_processor_register_performance",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589767760,
      "name": "acpi_processor_get_performance_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 258
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
int acpi_processor_get_performance_info(struct acpi_processor * pr)
```

```json
{
  "name": "acpi_processor_get_performance_info",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336497640640,
      "name": "acpi_processor_get_performance_info",
      "external": true,
      "loc": "drivers/acpi/processor_perflib.c:396",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_perflib.c:acpi_processor_register_performance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497640640,
      "name": "acpi_processor_get_performance_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1096
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int acpi_processor_get_performance_info(struct acpi_processor * pr)
```

```json
{
  "name": "acpi_processor_get_performance_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_processor_get_performance_info",
      "external": true,
      "loc": "drivers/acpi/processor_perflib.c:396",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_perflib.c:acpi_processor_register_performance",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585168871,
      "name": "acpi_processor_get_performance_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
    },
    {
      "addr": 18446744071585166208,
      "name": "acpi_processor_get_performance_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 490
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
int acpi_processor_get_performance_info(struct acpi_processor * pr)
```

```json
{
  "name": "acpi_processor_get_performance_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_processor_get_performance_info",
      "external": true,
      "loc": "drivers/acpi/processor_perflib.c:396",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_perflib.c:acpi_processor_register_performance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585083116,
      "name": "acpi_processor_get_performance_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
    },
    {
      "addr": 18446744071585080448,
      "name": "acpi_processor_get_performance_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 490
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
int acpi_processor_get_performance_info(struct acpi_processor * pr)
```

```json
{
  "name": "acpi_processor_get_performance_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_processor_get_performance_info",
      "external": true,
      "loc": "drivers/acpi/processor_perflib.c:396",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_perflib.c:acpi_processor_register_performance",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585321122,
      "name": "acpi_processor_get_performance_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
    },
    {
      "addr": 18446744071585318240,
      "name": "acpi_processor_get_performance_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 564
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
int acpi_processor_get_performance_info(struct acpi_processor * pr)
```

```json
{
  "name": "acpi_processor_get_performance_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_processor_get_performance_info",
      "external": true,
      "loc": "drivers/acpi/processor_perflib.c:396",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_perflib.c:acpi_processor_register_performance",
        "drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585427266,
      "name": "acpi_processor_get_performance_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
    },
    {
      "addr": 18446744071585424384,
      "name": "acpi_processor_get_performance_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 564
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int acpi_processor_get_performance_info(struct acpi_processor * pr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int acpi_processor_get_performance_info(struct acpi_processor * pr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int acpi_processor_get_performance_info(struct acpi_processor * pr)
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
