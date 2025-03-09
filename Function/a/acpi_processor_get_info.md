# Function: <code>acpi_processor_get_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_processor_get_info",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583572444,
      "name": "acpi_processor_get_info",
      "external": false,
      "loc": "drivers/acpi/acpi_processor.c:231",
      "file": "drivers/acpi/acpi_processor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpi_processor.c:acpi_processor_add"
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
  "name": "acpi_processor_get_info",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583894757,
      "name": "acpi_processor_get_info",
      "external": false,
      "loc": "drivers/acpi/acpi_processor.c:231",
      "file": "drivers/acpi/acpi_processor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpi_processor.c:acpi_processor_add"
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
  "name": "acpi_processor_get_info",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584034204,
      "name": "acpi_processor_get_info",
      "external": false,
      "loc": "drivers/acpi/acpi_processor.c:236",
      "file": "drivers/acpi/acpi_processor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpi_processor.c:acpi_processor_add"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int acpi_processor_get_info(struct acpi_device * device)
```

```json
{
  "name": "acpi_processor_get_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584090112,
      "name": "acpi_processor_get_info",
      "external": false,
      "loc": "drivers/acpi/acpi_processor.c:231",
      "file": "drivers/acpi/acpi_processor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_processor.c:acpi_processor_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584090112,
      "name": "acpi_processor_get_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1142
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
int acpi_processor_get_info(struct acpi_device * device)
```

```json
{
  "name": "acpi_processor_get_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584361120,
      "name": "acpi_processor_get_info",
      "external": false,
      "loc": "drivers/acpi/acpi_processor.c:232",
      "file": "drivers/acpi/acpi_processor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_processor.c:acpi_processor_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584361120,
      "name": "acpi_processor_get_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1990
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
int acpi_processor_get_info(struct acpi_device * device)
```

```json
{
  "name": "acpi_processor_get_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_processor_get_info",
      "external": false,
      "loc": "drivers/acpi/acpi_processor.c:232",
      "file": "drivers/acpi/acpi_processor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_processor.c:acpi_processor_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584582128,
      "name": "acpi_processor_get_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1977
    },
    {
      "addr": 18446744071584584924,
      "name": "acpi_processor_get_info.cold.5",
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
int acpi_processor_get_info(struct acpi_device * device)
```

```json
{
  "name": "acpi_processor_get_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_processor_get_info",
      "external": false,
      "loc": "drivers/acpi/acpi_processor.c:232",
      "file": "drivers/acpi/acpi_processor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_processor.c:acpi_processor_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584679520,
      "name": "acpi_processor_get_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1986
    },
    {
      "addr": 18446744071584682332,
      "name": "acpi_processor_get_info.cold.6",
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
int acpi_processor_get_info(struct acpi_device * device)
```

```json
{
  "name": "acpi_processor_get_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_processor_get_info",
      "external": false,
      "loc": "drivers/acpi/acpi_processor.c:229",
      "file": "drivers/acpi/acpi_processor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_processor.c:acpi_processor_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584879776,
      "name": "acpi_processor_get_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1874
    },
    {
      "addr": 18446744071584882426,
      "name": "acpi_processor_get_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
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
int acpi_processor_get_info(struct acpi_device * device)
```

```json
{
  "name": "acpi_processor_get_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_processor_get_info",
      "external": false,
      "loc": "drivers/acpi/acpi_processor.c:229",
      "file": "drivers/acpi/acpi_processor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_processor.c:acpi_processor_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585015616,
      "name": "acpi_processor_get_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1909
    },
    {
      "addr": 18446744071585018298,
      "name": "acpi_processor_get_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
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
int acpi_processor_get_info(struct acpi_device * device)
```

```json
{
  "name": "acpi_processor_get_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_processor_get_info",
      "external": false,
      "loc": "drivers/acpi/acpi_processor.c:229",
      "file": "drivers/acpi/acpi_processor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_processor.c:acpi_processor_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585717920,
      "name": "acpi_processor_get_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1130
    },
    {
      "addr": 18446744071585719830,
      "name": "acpi_processor_get_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
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
int acpi_processor_get_info(struct acpi_device * device)
```

```json
{
  "name": "acpi_processor_get_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_processor_get_info",
      "external": false,
      "loc": "drivers/acpi/acpi_processor.c:229",
      "file": "drivers/acpi/acpi_processor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_processor.c:acpi_processor_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585840256,
      "name": "acpi_processor_get_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1133
    },
    {
      "addr": 18446744071591433260,
      "name": "acpi_processor_get_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
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
int acpi_processor_get_info(struct acpi_device * device)
```

```json
{
  "name": "acpi_processor_get_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_processor_get_info",
      "external": false,
      "loc": "drivers/acpi/acpi_processor.c:217",
      "file": "drivers/acpi/acpi_processor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_processor.c:acpi_processor_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585719248,
      "name": "acpi_processor_get_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 966
    },
    {
      "addr": 18446744071591374017,
      "name": "acpi_processor_get_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
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
int acpi_processor_get_info(struct acpi_device * device)
```

```json
{
  "name": "acpi_processor_get_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_processor_get_info",
      "external": false,
      "loc": "drivers/acpi/acpi_processor.c:217",
      "file": "drivers/acpi/acpi_processor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_processor.c:acpi_processor_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586200624,
      "name": "acpi_processor_get_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1048
    },
    {
      "addr": 18446744071592408769,
      "name": "acpi_processor_get_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
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
int acpi_processor_get_info(struct acpi_device * device)
```

```json
{
  "name": "acpi_processor_get_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_processor_get_info",
      "external": false,
      "loc": "drivers/acpi/acpi_processor.c:217",
      "file": "drivers/acpi/acpi_processor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_processor.c:acpi_processor_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587437760,
      "name": "acpi_processor_get_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1074
    },
    {
      "addr": 18446744071594275404,
      "name": "acpi_processor_get_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 189
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
int acpi_processor_get_info(struct acpi_device * device)
```

```json
{
  "name": "acpi_processor_get_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_processor_get_info",
      "external": false,
      "loc": "drivers/acpi/acpi_processor.c:217",
      "file": "drivers/acpi/acpi_processor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_processor.c:acpi_processor_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588697152,
      "name": "acpi_processor_get_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1207
    },
    {
      "addr": 18446744071596218834,
      "name": "acpi_processor_get_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
int acpi_processor_get_info(struct acpi_device * device)
```

```json
{
  "name": "acpi_processor_get_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_processor_get_info",
      "external": false,
      "loc": "drivers/acpi/acpi_processor.c:246",
      "file": "drivers/acpi/acpi_processor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_processor.c:acpi_processor_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588985216,
      "name": "acpi_processor_get_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1246
    },
    {
      "addr": 18446744071596745458,
      "name": "acpi_processor_get_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
int acpi_processor_get_info(struct acpi_device * device)
```

```json
{
  "name": "acpi_processor_get_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_processor_get_info",
      "external": false,
      "loc": "drivers/acpi/acpi_processor.c:233",
      "file": "drivers/acpi/acpi_processor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_processor.c:acpi_processor_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589289248,
      "name": "acpi_processor_get_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1246
    },
    {
      "addr": 18446744071597654106,
      "name": "acpi_processor_get_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
int acpi_processor_get_info(struct acpi_device * device)
```

```json
{
  "name": "acpi_processor_get_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497426856,
      "name": "acpi_processor_get_info",
      "external": false,
      "loc": "drivers/acpi/acpi_processor.c:229",
      "file": "drivers/acpi/acpi_processor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_processor.c:acpi_processor_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497426856,
      "name": "acpi_processor_get_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1124
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
int acpi_processor_get_info(struct acpi_device * device)
```

```json
{
  "name": "acpi_processor_get_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_processor_get_info",
      "external": false,
      "loc": "drivers/acpi/acpi_processor.c:229",
      "file": "drivers/acpi/acpi_processor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_processor.c:acpi_processor_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584958976,
      "name": "acpi_processor_get_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1009
    },
    {
      "addr": 18446744071584960762,
      "name": "acpi_processor_get_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
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
int acpi_processor_get_info(struct acpi_device * device)
```

```json
{
  "name": "acpi_processor_get_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_processor_get_info",
      "external": false,
      "loc": "drivers/acpi/acpi_processor.c:229",
      "file": "drivers/acpi/acpi_processor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_processor.c:acpi_processor_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584867776,
      "name": "acpi_processor_get_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1009
    },
    {
      "addr": 18446744071584869562,
      "name": "acpi_processor_get_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
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
int acpi_processor_get_info(struct acpi_device * device)
```

```json
{
  "name": "acpi_processor_get_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_processor_get_info",
      "external": false,
      "loc": "drivers/acpi/acpi_processor.c:229",
      "file": "drivers/acpi/acpi_processor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_processor.c:acpi_processor_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584967200,
      "name": "acpi_processor_get_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1909
    },
    {
      "addr": 18446744071584969882,
      "name": "acpi_processor_get_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
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
int acpi_processor_get_info(struct acpi_device * device)
```

```json
{
  "name": "acpi_processor_get_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_processor_get_info",
      "external": false,
      "loc": "drivers/acpi/acpi_processor.c:229",
      "file": "drivers/acpi/acpi_processor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_processor.c:acpi_processor_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585073376,
      "name": "acpi_processor_get_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1909
    },
    {
      "addr": 18446744071585076058,
      "name": "acpi_processor_get_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
int acpi_processor_get_info(struct acpi_device * device)
```
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
int acpi_processor_get_info(struct acpi_device * device)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int acpi_processor_get_info(struct acpi_device * device)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int acpi_processor_get_info(struct acpi_device * device)
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
