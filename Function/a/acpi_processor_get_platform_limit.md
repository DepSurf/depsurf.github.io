# Function: <code>acpi_processor_get_platform_limit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Collision ❓</summary>

```c
int acpi_processor_get_platform_limit(struct acpi_processor * pr)
```

```json
{
  "name": "acpi_processor_get_platform_limit",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583750016,
      "name": "acpi_processor_get_platform_limit",
      "external": false,
      "loc": "drivers/acpi/processor_throttling.c:288",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_throttling.c:acpi_processor_tstate_has_changed",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info"
      ]
    },
    {
      "addr": 18446744071583754877,
      "name": "acpi_processor_get_platform_limit",
      "external": false,
      "loc": "drivers/acpi/processor_perflib.c:114",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info",
        "drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583750016,
      "name": "acpi_processor_get_platform_limit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
    },
    {
      "addr": 18446744071583754877,
      "name": "acpi_processor_get_platform_limit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Collision ❓</summary>

```c
int acpi_processor_get_platform_limit(struct acpi_processor * pr)
```

```json
{
  "name": "acpi_processor_get_platform_limit",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584075955,
      "name": "acpi_processor_get_platform_limit",
      "external": false,
      "loc": "drivers/acpi/processor_throttling.c:288",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_tstate_has_changed"
      ]
    },
    {
      "addr": 18446744071584080966,
      "name": "acpi_processor_get_platform_limit",
      "external": false,
      "loc": "drivers/acpi/processor_perflib.c:114",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info",
        "drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584075955,
      "name": "acpi_processor_get_platform_limit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
    },
    {
      "addr": 18446744071584080966,
      "name": "acpi_processor_get_platform_limit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Collision ❓</summary>

```c
int acpi_processor_get_platform_limit(struct acpi_processor * pr)
```

```json
{
  "name": "acpi_processor_get_platform_limit",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584218447,
      "name": "acpi_processor_get_platform_limit",
      "external": false,
      "loc": "drivers/acpi/processor_throttling.c:288",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_tstate_has_changed"
      ]
    },
    {
      "addr": 18446744071584223546,
      "name": "acpi_processor_get_platform_limit",
      "external": false,
      "loc": "drivers/acpi/processor_perflib.c:114",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info",
        "drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584218447,
      "name": "acpi_processor_get_platform_limit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
    },
    {
      "addr": 18446744071584223546,
      "name": "acpi_processor_get_platform_limit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Collision ❓</summary>

```c
int acpi_processor_get_platform_limit(struct acpi_processor * pr)
```

```json
{
  "name": "acpi_processor_get_platform_limit",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584289648,
      "name": "acpi_processor_get_platform_limit",
      "external": false,
      "loc": "drivers/acpi/processor_throttling.c:288",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_tstate_has_changed"
      ]
    },
    {
      "addr": 18446744071584295376,
      "name": "acpi_processor_get_platform_limit",
      "external": false,
      "loc": "drivers/acpi/processor_perflib.c:112",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info",
        "drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584289648,
      "name": "acpi_processor_get_platform_limit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    },
    {
      "addr": 18446744071584295376,
      "name": "acpi_processor_get_platform_limit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Collision ❓</summary>

```c
int acpi_processor_get_platform_limit(struct acpi_processor * pr)
```

```json
{
  "name": "acpi_processor_get_platform_limit",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584687056,
      "name": "acpi_processor_get_platform_limit",
      "external": false,
      "loc": "drivers/acpi/processor_throttling.c:288",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_tstate_has_changed"
      ]
    },
    {
      "addr": 18446744071584694144,
      "name": "acpi_processor_get_platform_limit",
      "external": false,
      "loc": "drivers/acpi/processor_perflib.c:112",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584687056,
      "name": "acpi_processor_get_platform_limit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    },
    {
      "addr": 18446744071584694144,
      "name": "acpi_processor_get_platform_limit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Collision ❓</summary>

```c
int acpi_processor_get_platform_limit(struct acpi_processor * pr)
```

```json
{
  "name": "acpi_processor_get_platform_limit",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584913440,
      "name": "acpi_processor_get_platform_limit",
      "external": false,
      "loc": "drivers/acpi/processor_throttling.c:288",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_tstate_has_changed"
      ]
    },
    {
      "addr": 18446744071584920576,
      "name": "acpi_processor_get_platform_limit",
      "external": false,
      "loc": "drivers/acpi/processor_perflib.c:112",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info",
        "drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584913440,
      "name": "acpi_processor_get_platform_limit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    },
    {
      "addr": 18446744071584920576,
      "name": "acpi_processor_get_platform_limit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Collision ❓</summary>

```c
int acpi_processor_get_platform_limit(struct acpi_processor * pr)
```

```json
{
  "name": "acpi_processor_get_platform_limit",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585017344,
      "name": "acpi_processor_get_platform_limit",
      "external": false,
      "loc": "drivers/acpi/processor_throttling.c:288",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_tstate_has_changed"
      ]
    },
    {
      "addr": 18446744071585024480,
      "name": "acpi_processor_get_platform_limit",
      "external": false,
      "loc": "drivers/acpi/processor_perflib.c:112",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info",
        "drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585017344,
      "name": "acpi_processor_get_platform_limit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    },
    {
      "addr": 18446744071585024480,
      "name": "acpi_processor_get_platform_limit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Collision ❓</summary>

```c
int acpi_processor_get_platform_limit(struct acpi_processor * pr)
```

```json
{
  "name": "acpi_processor_get_platform_limit",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585221008,
      "name": "acpi_processor_get_platform_limit",
      "external": false,
      "loc": "drivers/acpi/processor_throttling.c:275",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_tstate_has_changed"
      ]
    },
    {
      "addr": 18446744071585228224,
      "name": "acpi_processor_get_platform_limit",
      "external": false,
      "loc": "drivers/acpi/processor_perflib.c:99",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info",
        "drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585221008,
      "name": "acpi_processor_get_platform_limit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    },
    {
      "addr": 18446744071585228224,
      "name": "acpi_processor_get_platform_limit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
int acpi_processor_get_platform_limit(struct acpi_processor * pr)
```

```json
{
  "name": "acpi_processor_get_platform_limit",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585357440,
      "name": "acpi_processor_get_platform_limit",
      "external": false,
      "loc": "drivers/acpi/processor_throttling.c:275",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_tstate_has_changed"
      ]
    },
    {
      "addr": 0,
      "name": "acpi_processor_get_platform_limit",
      "external": false,
      "loc": "drivers/acpi/processor_perflib.c:55",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info",
        "drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585357440,
      "name": "acpi_processor_get_platform_limit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    },
    {
      "addr": 18446744071585364880,
      "name": "acpi_processor_get_platform_limit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 297
    },
    {
      "addr": 18446744071585369299,
      "name": "acpi_processor_get_platform_limit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
int acpi_processor_get_platform_limit(struct acpi_processor * pr)
```

```json
{
  "name": "acpi_processor_get_platform_limit",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586065024,
      "name": "acpi_processor_get_platform_limit",
      "external": false,
      "loc": "drivers/acpi/processor_throttling.c:275",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_tstate_has_changed"
      ]
    },
    {
      "addr": 0,
      "name": "acpi_processor_get_platform_limit",
      "external": false,
      "loc": "drivers/acpi/processor_perflib.c:55",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info",
        "drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586065024,
      "name": "acpi_processor_get_platform_limit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
    },
    {
      "addr": 18446744071586072832,
      "name": "acpi_processor_get_platform_limit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 297
    },
    {
      "addr": 18446744071586077283,
      "name": "acpi_processor_get_platform_limit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
int acpi_processor_get_platform_limit(struct acpi_processor * pr)
```

```json
{
  "name": "acpi_processor_get_platform_limit",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586186976,
      "name": "acpi_processor_get_platform_limit",
      "external": false,
      "loc": "drivers/acpi/processor_throttling.c:274",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_tstate_has_changed"
      ]
    },
    {
      "addr": 0,
      "name": "acpi_processor_get_platform_limit",
      "external": false,
      "loc": "drivers/acpi/processor_perflib.c:54",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info",
        "drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586186976,
      "name": "acpi_processor_get_platform_limit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
    },
    {
      "addr": 18446744071586194320,
      "name": "acpi_processor_get_platform_limit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 297
    },
    {
      "addr": 18446744071591439569,
      "name": "acpi_processor_get_platform_limit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
int acpi_processor_get_platform_limit(struct acpi_processor * pr)
```

```json
{
  "name": "acpi_processor_get_platform_limit",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586062608,
      "name": "acpi_processor_get_platform_limit",
      "external": false,
      "loc": "drivers/acpi/processor_throttling.c:270",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_tstate_has_changed"
      ]
    },
    {
      "addr": 0,
      "name": "acpi_processor_get_platform_limit",
      "external": false,
      "loc": "drivers/acpi/processor_perflib.c:52",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info",
        "drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586062608,
      "name": "acpi_processor_get_platform_limit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
    },
    {
      "addr": 18446744071586069632,
      "name": "acpi_processor_get_platform_limit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
    },
    {
      "addr": 18446744071591380760,
      "name": "acpi_processor_get_platform_limit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
int acpi_processor_get_platform_limit(struct acpi_processor * pr)
```

```json
{
  "name": "acpi_processor_get_platform_limit",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586556128,
      "name": "acpi_processor_get_platform_limit",
      "external": false,
      "loc": "drivers/acpi/processor_throttling.c:266",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_tstate_has_changed"
      ]
    },
    {
      "addr": 0,
      "name": "acpi_processor_get_platform_limit",
      "external": false,
      "loc": "drivers/acpi/processor_perflib.c:52",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info",
        "drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586556128,
      "name": "acpi_processor_get_platform_limit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
    },
    {
      "addr": 18446744071586564352,
      "name": "acpi_processor_get_platform_limit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 285
    },
    {
      "addr": 18446744071592417333,
      "name": "acpi_processor_get_platform_limit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
int acpi_processor_get_platform_limit(struct acpi_processor * pr)
```

```json
{
  "name": "acpi_processor_get_platform_limit",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587815472,
      "name": "acpi_processor_get_platform_limit",
      "external": false,
      "loc": "drivers/acpi/processor_throttling.c:266",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_tstate_has_changed"
      ]
    },
    {
      "addr": 0,
      "name": "acpi_processor_get_platform_limit",
      "external": false,
      "loc": "drivers/acpi/processor_perflib.c:52",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info",
        "drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587815472,
      "name": "acpi_processor_get_platform_limit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
    },
    {
      "addr": 18446744071587823408,
      "name": "acpi_processor_get_platform_limit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 299
    },
    {
      "addr": 18446744071594285029,
      "name": "acpi_processor_get_platform_limit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Collision ❓</summary>

```c
int acpi_processor_get_platform_limit(struct acpi_processor * pr)
```

```json
{
  "name": "acpi_processor_get_platform_limit",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589156496,
      "name": "acpi_processor_get_platform_limit",
      "external": false,
      "loc": "drivers/acpi/processor_throttling.c:264",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_tstate_has_changed"
      ]
    },
    {
      "addr": 18446744071589164128,
      "name": "acpi_processor_get_platform_limit",
      "external": false,
      "loc": "drivers/acpi/processor_perflib.c:52",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info",
        "drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589156496,
      "name": "acpi_processor_get_platform_limit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
    },
    {
      "addr": 18446744071589164128,
      "name": "acpi_processor_get_platform_limit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 317
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Collision ❓</summary>

```c
int acpi_processor_get_platform_limit(struct acpi_processor * pr)
```

```json
{
  "name": "acpi_processor_get_platform_limit",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589449696,
      "name": "acpi_processor_get_platform_limit",
      "external": false,
      "loc": "drivers/acpi/processor_throttling.c:264",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_tstate_has_changed"
      ]
    },
    {
      "addr": 18446744071589457440,
      "name": "acpi_processor_get_platform_limit",
      "external": false,
      "loc": "drivers/acpi/processor_perflib.c:52",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info",
        "drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589449696,
      "name": "acpi_processor_get_platform_limit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
    },
    {
      "addr": 18446744071589457440,
      "name": "acpi_processor_get_platform_limit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 374
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Collision ❓</summary>

```c
int acpi_processor_get_platform_limit(struct acpi_processor * pr)
```

```json
{
  "name": "acpi_processor_get_platform_limit",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589757680,
      "name": "acpi_processor_get_platform_limit",
      "external": false,
      "loc": "drivers/acpi/processor_throttling.c:264",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_tstate_has_changed"
      ]
    },
    {
      "addr": 18446744071589765440,
      "name": "acpi_processor_get_platform_limit",
      "external": false,
      "loc": "drivers/acpi/processor_perflib.c:52",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info",
        "drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589757680,
      "name": "acpi_processor_get_platform_limit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
    },
    {
      "addr": 18446744071589765440,
      "name": "acpi_processor_get_platform_limit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 374
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
int acpi_processor_get_platform_limit(struct acpi_processor * pr)
```

```json
{
  "name": "acpi_processor_get_platform_limit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497639712,
      "name": "acpi_processor_get_platform_limit",
      "external": false,
      "loc": "drivers/acpi/processor_perflib.c:55",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497639712,
      "name": "acpi_processor_get_platform_limit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 340
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Collision, Transformation ❓</summary>

```c
int acpi_processor_get_platform_limit(struct acpi_processor * pr)
```

```json
{
  "name": "acpi_processor_get_platform_limit",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585158640,
      "name": "acpi_processor_get_platform_limit",
      "external": false,
      "loc": "drivers/acpi/processor_throttling.c:275",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_tstate_has_changed"
      ]
    },
    {
      "addr": 0,
      "name": "acpi_processor_get_platform_limit",
      "external": false,
      "loc": "drivers/acpi/processor_perflib.c:55",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info",
        "drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585158640,
      "name": "acpi_processor_get_platform_limit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    },
    {
      "addr": 18446744071585164736,
      "name": "acpi_processor_get_platform_limit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 297
    },
    {
      "addr": 18446744071585168632,
      "name": "acpi_processor_get_platform_limit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Collision, Transformation ❓</summary>

```c
int acpi_processor_get_platform_limit(struct acpi_processor * pr)
```

```json
{
  "name": "acpi_processor_get_platform_limit",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585072784,
      "name": "acpi_processor_get_platform_limit",
      "external": false,
      "loc": "drivers/acpi/processor_throttling.c:275",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_tstate_has_changed"
      ]
    },
    {
      "addr": 0,
      "name": "acpi_processor_get_platform_limit",
      "external": false,
      "loc": "drivers/acpi/processor_perflib.c:55",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info",
        "drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585072784,
      "name": "acpi_processor_get_platform_limit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    },
    {
      "addr": 18446744071585078928,
      "name": "acpi_processor_get_platform_limit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 297
    },
    {
      "addr": 18446744071585082872,
      "name": "acpi_processor_get_platform_limit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Collision, Transformation ❓</summary>

```c
int acpi_processor_get_platform_limit(struct acpi_processor * pr)
```

```json
{
  "name": "acpi_processor_get_platform_limit",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585309024,
      "name": "acpi_processor_get_platform_limit",
      "external": false,
      "loc": "drivers/acpi/processor_throttling.c:275",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_tstate_has_changed"
      ]
    },
    {
      "addr": 0,
      "name": "acpi_processor_get_platform_limit",
      "external": false,
      "loc": "drivers/acpi/processor_perflib.c:55",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info",
        "drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585309024,
      "name": "acpi_processor_get_platform_limit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    },
    {
      "addr": 18446744071585316464,
      "name": "acpi_processor_get_platform_limit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 297
    },
    {
      "addr": 18446744071585320883,
      "name": "acpi_processor_get_platform_limit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Collision, Transformation ❓</summary>

```c
int acpi_processor_get_platform_limit(struct acpi_processor * pr)
```

```json
{
  "name": "acpi_processor_get_platform_limit",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585415168,
      "name": "acpi_processor_get_platform_limit",
      "external": false,
      "loc": "drivers/acpi/processor_throttling.c:275",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_tstate_has_changed"
      ]
    },
    {
      "addr": 0,
      "name": "acpi_processor_get_platform_limit",
      "external": false,
      "loc": "drivers/acpi/processor_perflib.c:55",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info",
        "drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585415168,
      "name": "acpi_processor_get_platform_limit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    },
    {
      "addr": 18446744071585422608,
      "name": "acpi_processor_get_platform_limit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 297
    },
    {
      "addr": 18446744071585427027,
      "name": "acpi_processor_get_platform_limit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
int acpi_processor_get_platform_limit(struct acpi_processor * pr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int acpi_processor_get_platform_limit(struct acpi_processor * pr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int acpi_processor_get_platform_limit(struct acpi_processor * pr)
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
