# Function: <code>acpi_cppc_processor_exit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_cppc_processor_exit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_cppc_processor_exit",
      "external": false,
      "loc": "include/acpi/processor.h:322",
      "file": "drivers/acpi/processor_driver.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_cppc_processor_exit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_cppc_processor_exit",
      "external": false,
      "loc": "include/acpi/processor.h:342",
      "file": "drivers/acpi/processor_driver.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void acpi_cppc_processor_exit(struct acpi_processor * pr)
```

```json
{
  "name": "acpi_cppc_processor_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584239955,
      "name": "acpi_cppc_processor_exit",
      "external": true,
      "loc": "drivers/acpi/cppc_acpi.c:824",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_driver.c:acpi_processor_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584239955,
      "name": "acpi_cppc_processor_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void acpi_cppc_processor_exit(struct acpi_processor * pr)
```

```json
{
  "name": "acpi_cppc_processor_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584315968,
      "name": "acpi_cppc_processor_exit",
      "external": true,
      "loc": "drivers/acpi/cppc_acpi.c:829",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_driver.c:acpi_processor_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584315968,
      "name": "acpi_cppc_processor_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
void acpi_cppc_processor_exit(struct acpi_processor * pr)
```

```json
{
  "name": "acpi_cppc_processor_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584715328,
      "name": "acpi_cppc_processor_exit",
      "external": true,
      "loc": "drivers/acpi/cppc_acpi.c:869",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_driver.c:acpi_processor_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584715328,
      "name": "acpi_cppc_processor_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 199
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
void acpi_cppc_processor_exit(struct acpi_processor * pr)
```

```json
{
  "name": "acpi_cppc_processor_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584942752,
      "name": "acpi_cppc_processor_exit",
      "external": true,
      "loc": "drivers/acpi/cppc_acpi.c:898",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_driver.c:acpi_processor_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584942752,
      "name": "acpi_cppc_processor_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
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
void acpi_cppc_processor_exit(struct acpi_processor * pr)
```

```json
{
  "name": "acpi_cppc_processor_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585046736,
      "name": "acpi_cppc_processor_exit",
      "external": true,
      "loc": "drivers/acpi/cppc_acpi.c:898",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_driver.c:acpi_processor_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585046736,
      "name": "acpi_cppc_processor_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
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
void acpi_cppc_processor_exit(struct acpi_processor * pr)
```

```json
{
  "name": "acpi_cppc_processor_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585250864,
      "name": "acpi_cppc_processor_exit",
      "external": true,
      "loc": "drivers/acpi/cppc_acpi.c:894",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_driver.c:acpi_processor_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585250864,
      "name": "acpi_cppc_processor_exit",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void acpi_cppc_processor_exit(struct acpi_processor * pr)
```

```json
{
  "name": "acpi_cppc_processor_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585388752,
      "name": "acpi_cppc_processor_exit",
      "external": true,
      "loc": "drivers/acpi/cppc_acpi.c:896",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_driver.c:acpi_processor_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585388752,
      "name": "acpi_cppc_processor_exit",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void acpi_cppc_processor_exit(struct acpi_processor * pr)
```

```json
{
  "name": "acpi_cppc_processor_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586098336,
      "name": "acpi_cppc_processor_exit",
      "external": true,
      "loc": "drivers/acpi/cppc_acpi.c:878",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_driver.c:acpi_processor_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586098336,
      "name": "acpi_cppc_processor_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
void acpi_cppc_processor_exit(struct acpi_processor * pr)
```

```json
{
  "name": "acpi_cppc_processor_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586219008,
      "name": "acpi_cppc_processor_exit",
      "external": true,
      "loc": "drivers/acpi/cppc_acpi.c:864",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_driver.c:acpi_processor_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586219008,
      "name": "acpi_cppc_processor_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
void acpi_cppc_processor_exit(struct acpi_processor * pr)
```

```json
{
  "name": "acpi_cppc_processor_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586093568,
      "name": "acpi_cppc_processor_exit",
      "external": true,
      "loc": "drivers/acpi/cppc_acpi.c:856",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_driver.c:acpi_processor_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586093568,
      "name": "acpi_cppc_processor_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
void acpi_cppc_processor_exit(struct acpi_processor * pr)
```

```json
{
  "name": "acpi_cppc_processor_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_cppc_processor_exit",
      "external": true,
      "loc": "drivers/acpi/cppc_acpi.c:856",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_driver.c:acpi_processor_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592419083,
      "name": "acpi_cppc_processor_exit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071586590944,
      "name": "acpi_cppc_processor_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 557
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
void acpi_cppc_processor_exit(struct acpi_processor * pr)
```

```json
{
  "name": "acpi_cppc_processor_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_cppc_processor_exit",
      "external": true,
      "loc": "drivers/acpi/cppc_acpi.c:906",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_driver.c:acpi_processor_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594286799,
      "name": "acpi_cppc_processor_exit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071587852320,
      "name": "acpi_cppc_processor_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 575
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void acpi_cppc_processor_exit(struct acpi_processor * pr)
```

```json
{
  "name": "acpi_cppc_processor_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_cppc_processor_exit",
      "external": true,
      "loc": "drivers/acpi/cppc_acpi.c:909",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_driver.c:acpi_processor_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596222579,
      "name": "acpi_cppc_processor_exit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071589195088,
      "name": "acpi_cppc_processor_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 575
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void acpi_cppc_processor_exit(struct acpi_processor * pr)
```

```json
{
  "name": "acpi_cppc_processor_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_cppc_processor_exit",
      "external": true,
      "loc": "drivers/acpi/cppc_acpi.c:910",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_driver.c:acpi_processor_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596750325,
      "name": "acpi_cppc_processor_exit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071589489248,
      "name": "acpi_cppc_processor_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 575
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void acpi_cppc_processor_exit(struct acpi_processor * pr)
```

```json
{
  "name": "acpi_cppc_processor_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_cppc_processor_exit",
      "external": true,
      "loc": "drivers/acpi/cppc_acpi.c:913",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_driver.c:acpi_processor_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597657960,
      "name": "acpi_cppc_processor_exit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071589796464,
      "name": "acpi_cppc_processor_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 575
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
void acpi_cppc_processor_exit(struct acpi_processor * pr)
```

```json
{
  "name": "acpi_cppc_processor_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497661696,
      "name": "acpi_cppc_processor_exit",
      "external": true,
      "loc": "drivers/acpi/cppc_acpi.c:896",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_driver.c:acpi_processor_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497661696,
      "name": "acpi_cppc_processor_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void acpi_cppc_processor_exit(struct acpi_processor * pr)
```

```json
{
  "name": "acpi_cppc_processor_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585174272,
      "name": "acpi_cppc_processor_exit",
      "external": true,
      "loc": "drivers/acpi/cppc_acpi.c:896",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_driver.c:acpi_processor_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585174272,
      "name": "acpi_cppc_processor_exit",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void acpi_cppc_processor_exit(struct acpi_processor * pr)
```

```json
{
  "name": "acpi_cppc_processor_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585115968,
      "name": "acpi_cppc_processor_exit",
      "external": true,
      "loc": "drivers/acpi/cppc_acpi.c:896",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_driver.c:acpi_processor_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585115968,
      "name": "acpi_cppc_processor_exit",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void acpi_cppc_processor_exit(struct acpi_processor * pr)
```

```json
{
  "name": "acpi_cppc_processor_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585339152,
      "name": "acpi_cppc_processor_exit",
      "external": true,
      "loc": "drivers/acpi/cppc_acpi.c:896",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_driver.c:acpi_processor_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585339152,
      "name": "acpi_cppc_processor_exit",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void acpi_cppc_processor_exit(struct acpi_processor * pr)
```

```json
{
  "name": "acpi_cppc_processor_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585446480,
      "name": "acpi_cppc_processor_exit",
      "external": true,
      "loc": "drivers/acpi/cppc_acpi.c:896",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_driver.c:acpi_processor_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585446480,
      "name": "acpi_cppc_processor_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
void acpi_cppc_processor_exit(struct acpi_processor * pr)
```
</details>
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
void acpi_cppc_processor_exit(struct acpi_processor * pr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void acpi_cppc_processor_exit(struct acpi_processor * pr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void acpi_cppc_processor_exit(struct acpi_processor * pr)
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
