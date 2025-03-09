# Function: <code>acpi_cppc_processor_probe</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_cppc_processor_probe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_cppc_processor_probe",
      "external": false,
      "loc": "include/acpi/processor.h:318",
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
  "name": "acpi_cppc_processor_probe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_cppc_processor_probe",
      "external": false,
      "loc": "include/acpi/processor.h:338",
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
int acpi_cppc_processor_probe(struct acpi_processor * pr)
```

```json
{
  "name": "acpi_cppc_processor_probe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584241583,
      "name": "acpi_cppc_processor_probe",
      "external": true,
      "loc": "drivers/acpi/cppc_acpi.c:650",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_driver.c:__acpi_processor_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584241583,
      "name": "acpi_cppc_processor_probe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1474
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
int acpi_cppc_processor_probe(struct acpi_processor * pr)
```

```json
{
  "name": "acpi_cppc_processor_probe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584317920,
      "name": "acpi_cppc_processor_probe",
      "external": true,
      "loc": "drivers/acpi/cppc_acpi.c:655",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_driver.c:__acpi_processor_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584317920,
      "name": "acpi_cppc_processor_probe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1843
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
int acpi_cppc_processor_probe(struct acpi_processor * pr)
```

```json
{
  "name": "acpi_cppc_processor_probe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584717296,
      "name": "acpi_cppc_processor_probe",
      "external": true,
      "loc": "drivers/acpi/cppc_acpi.c:691",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_driver.c:__acpi_processor_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584717296,
      "name": "acpi_cppc_processor_probe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1963
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
int acpi_cppc_processor_probe(struct acpi_processor * pr)
```

```json
{
  "name": "acpi_cppc_processor_probe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_cppc_processor_probe",
      "external": true,
      "loc": "drivers/acpi/cppc_acpi.c:718",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_driver.c:__acpi_processor_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584951025,
      "name": "acpi_cppc_processor_probe.cold.4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    },
    {
      "addr": 18446744071584944720,
      "name": "acpi_cppc_processor_probe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2121
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
int acpi_cppc_processor_probe(struct acpi_processor * pr)
```

```json
{
  "name": "acpi_cppc_processor_probe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_cppc_processor_probe",
      "external": true,
      "loc": "drivers/acpi/cppc_acpi.c:718",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_driver.c:__acpi_processor_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585055393,
      "name": "acpi_cppc_processor_probe.cold.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    },
    {
      "addr": 18446744071585048704,
      "name": "acpi_cppc_processor_probe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2105
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
int acpi_cppc_processor_probe(struct acpi_processor * pr)
```

```json
{
  "name": "acpi_cppc_processor_probe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_cppc_processor_probe",
      "external": true,
      "loc": "drivers/acpi/cppc_acpi.c:714",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_driver.c:__acpi_processor_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585259633,
      "name": "acpi_cppc_processor_probe.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    },
    {
      "addr": 18446744071585252864,
      "name": "acpi_cppc_processor_probe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2135
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
int acpi_cppc_processor_probe(struct acpi_processor * pr)
```

```json
{
  "name": "acpi_cppc_processor_probe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_cppc_processor_probe",
      "external": true,
      "loc": "drivers/acpi/cppc_acpi.c:716",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_driver.c:__acpi_processor_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585397537,
      "name": "acpi_cppc_processor_probe.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    },
    {
      "addr": 18446744071585390752,
      "name": "acpi_cppc_processor_probe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2148
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
int acpi_cppc_processor_probe(struct acpi_processor * pr)
```

```json
{
  "name": "acpi_cppc_processor_probe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_cppc_processor_probe",
      "external": true,
      "loc": "drivers/acpi/cppc_acpi.c:697",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_driver.c:__acpi_processor_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586106233,
      "name": "acpi_cppc_processor_probe.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    },
    {
      "addr": 18446744071586100128,
      "name": "acpi_cppc_processor_probe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1675
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
int acpi_cppc_processor_probe(struct acpi_processor * pr)
```

```json
{
  "name": "acpi_cppc_processor_probe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_cppc_processor_probe",
      "external": true,
      "loc": "drivers/acpi/cppc_acpi.c:681",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_driver.c:__acpi_processor_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591441069,
      "name": "acpi_cppc_processor_probe.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    },
    {
      "addr": 18446744071586220528,
      "name": "acpi_cppc_processor_probe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1690
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
int acpi_cppc_processor_probe(struct acpi_processor * pr)
```

```json
{
  "name": "acpi_cppc_processor_probe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_cppc_processor_probe",
      "external": true,
      "loc": "drivers/acpi/cppc_acpi.c:673",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_driver.c:__acpi_processor_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591382175,
      "name": "acpi_cppc_processor_probe.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    },
    {
      "addr": 18446744071586095120,
      "name": "acpi_cppc_processor_probe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1689
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
int acpi_cppc_processor_probe(struct acpi_processor * pr)
```

```json
{
  "name": "acpi_cppc_processor_probe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_cppc_processor_probe",
      "external": true,
      "loc": "drivers/acpi/cppc_acpi.c:673",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_driver.c:__acpi_processor_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592419196,
      "name": "acpi_cppc_processor_probe.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
    },
    {
      "addr": 18446744071586593072,
      "name": "acpi_cppc_processor_probe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2817
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
int acpi_cppc_processor_probe(struct acpi_processor * pr)
```

```json
{
  "name": "acpi_cppc_processor_probe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_cppc_processor_probe",
      "external": true,
      "loc": "drivers/acpi/cppc_acpi.c:660",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_driver.c:__acpi_processor_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594286926,
      "name": "acpi_cppc_processor_probe.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
    },
    {
      "addr": 18446744071587854112,
      "name": "acpi_cppc_processor_probe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3528
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
int acpi_cppc_processor_probe(struct acpi_processor * pr)
```

```json
{
  "name": "acpi_cppc_processor_probe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_cppc_processor_probe",
      "external": true,
      "loc": "drivers/acpi/cppc_acpi.c:663",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_driver.c:__acpi_processor_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596222669,
      "name": "acpi_cppc_processor_probe.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
    },
    {
      "addr": 18446744071589198352,
      "name": "acpi_cppc_processor_probe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3584
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
int acpi_cppc_processor_probe(struct acpi_processor * pr)
```

```json
{
  "name": "acpi_cppc_processor_probe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_cppc_processor_probe",
      "external": true,
      "loc": "drivers/acpi/cppc_acpi.c:664",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_driver.c:__acpi_processor_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596750415,
      "name": "acpi_cppc_processor_probe.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
    },
    {
      "addr": 18446744071589492512,
      "name": "acpi_cppc_processor_probe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3725
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
int acpi_cppc_processor_probe(struct acpi_processor * pr)
```

```json
{
  "name": "acpi_cppc_processor_probe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_cppc_processor_probe",
      "external": true,
      "loc": "drivers/acpi/cppc_acpi.c:667",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_driver.c:__acpi_processor_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597658050,
      "name": "acpi_cppc_processor_probe.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
    },
    {
      "addr": 18446744071589800080,
      "name": "acpi_cppc_processor_probe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3819
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
int acpi_cppc_processor_probe(struct acpi_processor * pr)
```

```json
{
  "name": "acpi_cppc_processor_probe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497664120,
      "name": "acpi_cppc_processor_probe",
      "external": true,
      "loc": "drivers/acpi/cppc_acpi.c:716",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_driver.c:__acpi_processor_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497664120,
      "name": "acpi_cppc_processor_probe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2260
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
int acpi_cppc_processor_probe(struct acpi_processor * pr)
```

```json
{
  "name": "acpi_cppc_processor_probe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_cppc_processor_probe",
      "external": true,
      "loc": "drivers/acpi/cppc_acpi.c:716",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_driver.c:__acpi_processor_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585183057,
      "name": "acpi_cppc_processor_probe.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    },
    {
      "addr": 18446744071585176272,
      "name": "acpi_cppc_processor_probe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2148
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
int acpi_cppc_processor_probe(struct acpi_processor * pr)
```

```json
{
  "name": "acpi_cppc_processor_probe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_cppc_processor_probe",
      "external": true,
      "loc": "drivers/acpi/cppc_acpi.c:716",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_driver.c:__acpi_processor_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585124753,
      "name": "acpi_cppc_processor_probe.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    },
    {
      "addr": 18446744071585117968,
      "name": "acpi_cppc_processor_probe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2148
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
int acpi_cppc_processor_probe(struct acpi_processor * pr)
```

```json
{
  "name": "acpi_cppc_processor_probe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_cppc_processor_probe",
      "external": true,
      "loc": "drivers/acpi/cppc_acpi.c:716",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_driver.c:__acpi_processor_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585347937,
      "name": "acpi_cppc_processor_probe.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    },
    {
      "addr": 18446744071585341152,
      "name": "acpi_cppc_processor_probe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2148
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
int acpi_cppc_processor_probe(struct acpi_processor * pr)
```

```json
{
  "name": "acpi_cppc_processor_probe",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_cppc_processor_probe",
      "external": true,
      "loc": "drivers/acpi/cppc_acpi.c:716",
      "file": "drivers/acpi/cppc_acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_driver.c:__acpi_processor_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585455245,
      "name": "acpi_cppc_processor_probe.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    },
    {
      "addr": 18446744071585448464,
      "name": "acpi_cppc_processor_probe",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2148
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
int acpi_cppc_processor_probe(struct acpi_processor * pr)
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
int acpi_cppc_processor_probe(struct acpi_processor * pr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int acpi_cppc_processor_probe(struct acpi_processor * pr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int acpi_cppc_processor_probe(struct acpi_processor * pr)
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
