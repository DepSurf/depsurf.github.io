# Function: <code>acpi_processor_throttling_notifier</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_processor_throttling_notifier",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583751454,
      "name": "acpi_processor_throttling_notifier",
      "external": false,
      "loc": "drivers/acpi/processor_throttling.c:221",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:acpi_processor_set_throttling"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_processor_throttling_notifier",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584077544,
      "name": "acpi_processor_throttling_notifier",
      "external": false,
      "loc": "drivers/acpi/processor_throttling.c:221",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:acpi_processor_set_throttling"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_processor_throttling_notifier",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584220118,
      "name": "acpi_processor_throttling_notifier",
      "external": false,
      "loc": "drivers/acpi/processor_throttling.c:221",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:acpi_processor_set_throttling"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_processor_throttling_notifier",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584290587,
      "name": "acpi_processor_throttling_notifier",
      "external": false,
      "loc": "drivers/acpi/processor_throttling.c:221",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int acpi_processor_throttling_notifier(long unsigned int event, void * data)
```

```json
{
  "name": "acpi_processor_throttling_notifier",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584687392,
      "name": "acpi_processor_throttling_notifier",
      "external": false,
      "loc": "drivers/acpi/processor_throttling.c:221",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584687392,
      "name": "acpi_processor_throttling_notifier",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 449
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
int acpi_processor_throttling_notifier(long unsigned int event, void * data)
```

```json
{
  "name": "acpi_processor_throttling_notifier",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_processor_throttling_notifier",
      "external": false,
      "loc": "drivers/acpi/processor_throttling.c:221",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584913616,
      "name": "acpi_processor_throttling_notifier",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 413
    },
    {
      "addr": 18446744071584918929,
      "name": "acpi_processor_throttling_notifier.cold.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
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
int acpi_processor_throttling_notifier(long unsigned int event, void * data)
```

```json
{
  "name": "acpi_processor_throttling_notifier",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_processor_throttling_notifier",
      "external": false,
      "loc": "drivers/acpi/processor_throttling.c:221",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585017520,
      "name": "acpi_processor_throttling_notifier",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 413
    },
    {
      "addr": 18446744071585022833,
      "name": "acpi_processor_throttling_notifier.cold.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
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
int acpi_processor_throttling_notifier(long unsigned int event, void * data)
```

```json
{
  "name": "acpi_processor_throttling_notifier",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_processor_throttling_notifier",
      "external": false,
      "loc": "drivers/acpi/processor_throttling.c:208",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585221184,
      "name": "acpi_processor_throttling_notifier",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 419
    },
    {
      "addr": 18446744071585226514,
      "name": "acpi_processor_throttling_notifier.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
int acpi_processor_throttling_notifier(long unsigned int event, void * data)
```

```json
{
  "name": "acpi_processor_throttling_notifier",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_processor_throttling_notifier",
      "external": false,
      "loc": "drivers/acpi/processor_throttling.c:208",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585357616,
      "name": "acpi_processor_throttling_notifier",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 419
    },
    {
      "addr": 18446744071585362946,
      "name": "acpi_processor_throttling_notifier.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
  "name": "acpi_processor_throttling_notifier",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_processor_throttling_notifier",
      "external": false,
      "loc": "drivers/acpi/processor_throttling.c:208",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586066688,
      "name": "acpi_processor_throttling_notifier.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 406
    },
    {
      "addr": 18446744071586071176,
      "name": "acpi_processor_throttling_notifier.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
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
  "name": "acpi_processor_throttling_notifier",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_processor_throttling_notifier",
      "external": false,
      "loc": "drivers/acpi/processor_throttling.c:207",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586188640,
      "name": "acpi_processor_throttling_notifier.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 406
    },
    {
      "addr": 18446744071591439379,
      "name": "acpi_processor_throttling_notifier.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
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
  "name": "acpi_processor_throttling_notifier",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_processor_throttling_notifier",
      "external": false,
      "loc": "drivers/acpi/processor_throttling.c:202",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586064000,
      "name": "acpi_processor_throttling_notifier.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 271
    },
    {
      "addr": 18446744071591380502,
      "name": "acpi_processor_throttling_notifier.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
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
  "name": "acpi_processor_throttling_notifier",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_processor_throttling_notifier",
      "external": false,
      "loc": "drivers/acpi/processor_throttling.c:200",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586557648,
      "name": "acpi_processor_throttling_notifier.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 335
    },
    {
      "addr": 18446744071592416780,
      "name": "acpi_processor_throttling_notifier.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
  "name": "acpi_processor_throttling_notifier",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_processor_throttling_notifier",
      "external": false,
      "loc": "drivers/acpi/processor_throttling.c:200",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587818176,
      "name": "acpi_processor_throttling_notifier.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 393
    },
    {
      "addr": 18446744071594284634,
      "name": "acpi_processor_throttling_notifier.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
  "name": "acpi_processor_throttling_notifier",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589159584,
      "name": "acpi_processor_throttling_notifier",
      "external": false,
      "loc": "drivers/acpi/processor_throttling.c:198",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589159584,
      "name": "acpi_processor_throttling_notifier.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 430
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
  "name": "acpi_processor_throttling_notifier",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589452768,
      "name": "acpi_processor_throttling_notifier",
      "external": false,
      "loc": "drivers/acpi/processor_throttling.c:198",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589452768,
      "name": "acpi_processor_throttling_notifier.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 430
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
  "name": "acpi_processor_throttling_notifier",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589760752,
      "name": "acpi_processor_throttling_notifier",
      "external": false,
      "loc": "drivers/acpi/processor_throttling.c:198",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589760752,
      "name": "acpi_processor_throttling_notifier.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 430
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
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
  "name": "acpi_processor_throttling_notifier",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585159476,
      "name": "acpi_processor_throttling_notifier",
      "external": false,
      "loc": "drivers/acpi/processor_throttling.c:208",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_processor_throttling_notifier",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585073796,
      "name": "acpi_processor_throttling_notifier",
      "external": false,
      "loc": "drivers/acpi/processor_throttling.c:208",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int acpi_processor_throttling_notifier(long unsigned int event, void * data)
```

```json
{
  "name": "acpi_processor_throttling_notifier",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_processor_throttling_notifier",
      "external": false,
      "loc": "drivers/acpi/processor_throttling.c:208",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585309200,
      "name": "acpi_processor_throttling_notifier",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 419
    },
    {
      "addr": 18446744071585314530,
      "name": "acpi_processor_throttling_notifier.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
int acpi_processor_throttling_notifier(long unsigned int event, void * data)
```

```json
{
  "name": "acpi_processor_throttling_notifier",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_processor_throttling_notifier",
      "external": false,
      "loc": "drivers/acpi/processor_throttling.c:208",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling",
        "drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585415344,
      "name": "acpi_processor_throttling_notifier",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 419
    },
    {
      "addr": 18446744071585420674,
      "name": "acpi_processor_throttling_notifier.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
int acpi_processor_throttling_notifier(long unsigned int event, void * data)
```
</details>
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
int acpi_processor_throttling_notifier(long unsigned int event, void * data)
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
int acpi_processor_throttling_notifier(long unsigned int event, void * data)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int acpi_processor_throttling_notifier(long unsigned int event, void * data)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int acpi_processor_throttling_notifier(long unsigned int event, void * data)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int acpi_processor_throttling_notifier(long unsigned int event, void * data)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ➖</summary>

```c
int acpi_processor_throttling_notifier(long unsigned int event, void * data)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
int acpi_processor_throttling_notifier(long unsigned int event, void * data)
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
