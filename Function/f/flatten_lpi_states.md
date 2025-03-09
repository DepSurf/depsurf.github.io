# Function: <code>flatten_lpi_states</code>

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
int flatten_lpi_states(struct acpi_processor * pr, struct acpi_lpi_states_array * curr_level, struct acpi_lpi_states_array * prev_level)
```

```json
{
  "name": "flatten_lpi_states",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584069923,
      "name": "flatten_lpi_states",
      "external": false,
      "loc": "drivers/acpi/processor_idle.c:1109",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584069923,
      "name": "flatten_lpi_states",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 456
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
int flatten_lpi_states(struct acpi_processor * pr, struct acpi_lpi_states_array * curr_level, struct acpi_lpi_states_array * prev_level)
```

```json
{
  "name": "flatten_lpi_states",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584212471,
      "name": "flatten_lpi_states",
      "external": false,
      "loc": "drivers/acpi/processor_idle.c:1110",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584212471,
      "name": "flatten_lpi_states",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 456
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
int flatten_lpi_states(struct acpi_processor * pr, struct acpi_lpi_states_array * curr_level, struct acpi_lpi_states_array * prev_level)
```

```json
{
  "name": "flatten_lpi_states",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584282432,
      "name": "flatten_lpi_states",
      "external": false,
      "loc": "drivers/acpi/processor_idle.c:1110",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584282432,
      "name": "flatten_lpi_states",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 601
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
int flatten_lpi_states(struct acpi_processor * pr, struct acpi_lpi_states_array * curr_level, struct acpi_lpi_states_array * prev_level)
```

```json
{
  "name": "flatten_lpi_states",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584678864,
      "name": "flatten_lpi_states",
      "external": false,
      "loc": "drivers/acpi/processor_idle.c:1119",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584678864,
      "name": "flatten_lpi_states",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 601
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
int flatten_lpi_states(struct acpi_processor * pr, struct acpi_lpi_states_array * curr_level, struct acpi_lpi_states_array * prev_level)
```

```json
{
  "name": "flatten_lpi_states",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "flatten_lpi_states",
      "external": false,
      "loc": "drivers/acpi/processor_idle.c:1123",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584905152,
      "name": "flatten_lpi_states",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 563
    },
    {
      "addr": 18446744071584912831,
      "name": "flatten_lpi_states.cold.15",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
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
int flatten_lpi_states(struct acpi_processor * pr, struct acpi_lpi_states_array * curr_level, struct acpi_lpi_states_array * prev_level)
```

```json
{
  "name": "flatten_lpi_states",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "flatten_lpi_states",
      "external": false,
      "loc": "drivers/acpi/processor_idle.c:1124",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585009024,
      "name": "flatten_lpi_states",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 563
    },
    {
      "addr": 18446744071585016735,
      "name": "flatten_lpi_states.cold.15",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
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
int flatten_lpi_states(struct acpi_processor * pr, struct acpi_lpi_states_array * curr_level, struct acpi_lpi_states_array * prev_level)
```

```json
{
  "name": "flatten_lpi_states",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "flatten_lpi_states",
      "external": false,
      "loc": "drivers/acpi/processor_idle.c:1119",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585212688,
      "name": "flatten_lpi_states",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 552
    },
    {
      "addr": 18446744071585220402,
      "name": "flatten_lpi_states.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
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
int flatten_lpi_states(struct acpi_processor * pr, struct acpi_lpi_states_array * curr_level, struct acpi_lpi_states_array * prev_level)
```

```json
{
  "name": "flatten_lpi_states",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "flatten_lpi_states",
      "external": false,
      "loc": "drivers/acpi/processor_idle.c:1119",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585349136,
      "name": "flatten_lpi_states",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 552
    },
    {
      "addr": 18446744071585356834,
      "name": "flatten_lpi_states.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
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
  "name": "flatten_lpi_states",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "flatten_lpi_states",
      "external": false,
      "loc": "drivers/acpi/processor_idle.c:979",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586060208,
      "name": "flatten_lpi_states.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 546
    },
    {
      "addr": 18446744071586064566,
      "name": "flatten_lpi_states.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
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
  "name": "flatten_lpi_states",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "flatten_lpi_states",
      "external": false,
      "loc": "drivers/acpi/processor_idle.c:999",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586182224,
      "name": "flatten_lpi_states.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 546
    },
    {
      "addr": 18446744071591439043,
      "name": "flatten_lpi_states.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
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
  "name": "flatten_lpi_states",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "flatten_lpi_states",
      "external": false,
      "loc": "drivers/acpi/processor_idle.c:1033",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586058208,
      "name": "flatten_lpi_states.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 544
    },
    {
      "addr": 18446744071591380186,
      "name": "flatten_lpi_states.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
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
  "name": "flatten_lpi_states",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "flatten_lpi_states",
      "external": false,
      "loc": "drivers/acpi/processor_idle.c:1034",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586550800,
      "name": "flatten_lpi_states.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 578
    },
    {
      "addr": 18446744071592416372,
      "name": "flatten_lpi_states.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
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
  "name": "flatten_lpi_states",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "flatten_lpi_states",
      "external": false,
      "loc": "drivers/acpi/processor_idle.c:1038",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587810128,
      "name": "flatten_lpi_states.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 416
    },
    {
      "addr": 18446744071594284012,
      "name": "flatten_lpi_states.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
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
  "name": "flatten_lpi_states",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589151760,
      "name": "flatten_lpi_states",
      "external": false,
      "loc": "drivers/acpi/processor_idle.c:1054",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589151760,
      "name": "flatten_lpi_states.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 418
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
  "name": "flatten_lpi_states",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "flatten_lpi_states",
      "external": false,
      "loc": "drivers/acpi/processor_idle.c:1054",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589444576,
      "name": "flatten_lpi_states.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 660
    },
    {
      "addr": 18446744071596748600,
      "name": "flatten_lpi_states.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
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
  "name": "flatten_lpi_states",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "flatten_lpi_states",
      "external": false,
      "loc": "drivers/acpi/processor_idle.c:1054",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589752512,
      "name": "flatten_lpi_states.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 660
    },
    {
      "addr": 18446744071597657228,
      "name": "flatten_lpi_states.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
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
int flatten_lpi_states(struct acpi_processor * pr, struct acpi_lpi_states_array * curr_level, struct acpi_lpi_states_array * prev_level)
```

```json
{
  "name": "flatten_lpi_states",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497635880,
      "name": "flatten_lpi_states",
      "external": false,
      "loc": "drivers/acpi/processor_idle.c:1119",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497635880,
      "name": "flatten_lpi_states",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 604
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
int flatten_lpi_states(struct acpi_processor * pr, struct acpi_lpi_states_array * curr_level, struct acpi_lpi_states_array * prev_level)
```

```json
{
  "name": "flatten_lpi_states",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "flatten_lpi_states",
      "external": false,
      "loc": "drivers/acpi/processor_idle.c:1119",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585151328,
      "name": "flatten_lpi_states",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 552
    },
    {
      "addr": 18446744071585158162,
      "name": "flatten_lpi_states.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
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
int flatten_lpi_states(struct acpi_processor * pr, struct acpi_lpi_states_array * curr_level, struct acpi_lpi_states_array * prev_level)
```

```json
{
  "name": "flatten_lpi_states",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "flatten_lpi_states",
      "external": false,
      "loc": "drivers/acpi/processor_idle.c:1119",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585065488,
      "name": "flatten_lpi_states",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 552
    },
    {
      "addr": 18446744071585072322,
      "name": "flatten_lpi_states.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
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
int flatten_lpi_states(struct acpi_processor * pr, struct acpi_lpi_states_array * curr_level, struct acpi_lpi_states_array * prev_level)
```

```json
{
  "name": "flatten_lpi_states",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "flatten_lpi_states",
      "external": false,
      "loc": "drivers/acpi/processor_idle.c:1119",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585300720,
      "name": "flatten_lpi_states",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 552
    },
    {
      "addr": 18446744071585308418,
      "name": "flatten_lpi_states.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
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
int flatten_lpi_states(struct acpi_processor * pr, struct acpi_lpi_states_array * curr_level, struct acpi_lpi_states_array * prev_level)
```

```json
{
  "name": "flatten_lpi_states",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "flatten_lpi_states",
      "external": false,
      "loc": "drivers/acpi/processor_idle.c:1119",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info",
        "drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585406880,
      "name": "flatten_lpi_states",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 552
    },
    {
      "addr": 18446744071585414562,
      "name": "flatten_lpi_states.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
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
int flatten_lpi_states(struct acpi_processor * pr, struct acpi_lpi_states_array * curr_level, struct acpi_lpi_states_array * prev_level)
```
</details>
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
int flatten_lpi_states(struct acpi_processor * pr, struct acpi_lpi_states_array * curr_level, struct acpi_lpi_states_array * prev_level)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int flatten_lpi_states(struct acpi_processor * pr, struct acpi_lpi_states_array * curr_level, struct acpi_lpi_states_array * prev_level)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int flatten_lpi_states(struct acpi_processor * pr, struct acpi_lpi_states_array * curr_level, struct acpi_lpi_states_array * prev_level)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int flatten_lpi_states(struct acpi_processor * pr, struct acpi_lpi_states_array * curr_level, struct acpi_lpi_states_array * prev_level)
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
