# Function: <code>ata_set_max_sectors</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ata_set_max_sectors",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584925615,
      "name": "ata_set_max_sectors",
      "external": false,
      "loc": "drivers/ata/libata-core.c:1273",
      "file": "drivers/ata/libata-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:ata_hpa_resize"
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
  "name": "ata_set_max_sectors",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585288135,
      "name": "ata_set_max_sectors",
      "external": false,
      "loc": "drivers/ata/libata-core.c:1276",
      "file": "drivers/ata/libata-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:ata_hpa_resize"
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
  "name": "ata_set_max_sectors",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585487719,
      "name": "ata_set_max_sectors",
      "external": false,
      "loc": "drivers/ata/libata-core.c:1283",
      "file": "drivers/ata/libata-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:ata_hpa_resize"
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
int ata_set_max_sectors(struct ata_device * dev, u64 new_sectors)
```

```json
{
  "name": "ata_set_max_sectors",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585586514,
      "name": "ata_set_max_sectors",
      "external": false,
      "loc": "drivers/ata/libata-core.c:1283",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_dev_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585586514,
      "name": "ata_set_max_sectors",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 320
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
int ata_set_max_sectors(struct ata_device * dev, u64 new_sectors)
```

```json
{
  "name": "ata_set_max_sectors",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586018178,
      "name": "ata_set_max_sectors",
      "external": false,
      "loc": "drivers/ata/libata-core.c:1283",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_dev_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586018178,
      "name": "ata_set_max_sectors",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 320
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
  "name": "ata_set_max_sectors",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586250524,
      "name": "ata_set_max_sectors",
      "external": false,
      "loc": "drivers/ata/libata-core.c:1283",
      "file": "drivers/ata/libata-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:ata_hpa_resize"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ata_set_max_sectors",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586390988,
      "name": "ata_set_max_sectors",
      "external": false,
      "loc": "drivers/ata/libata-core.c:1283",
      "file": "drivers/ata/libata-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:ata_hpa_resize"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int ata_set_max_sectors(struct ata_device * dev, u64 new_sectors)
```

```json
{
  "name": "ata_set_max_sectors",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ata_set_max_sectors",
      "external": false,
      "loc": "drivers/ata/libata-core.c:1267",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_dev_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586632816,
      "name": "ata_set_max_sectors",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 355
    },
    {
      "addr": 18446744071586648545,
      "name": "ata_set_max_sectors.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
int ata_set_max_sectors(struct ata_device * dev, u64 new_sectors)
```

```json
{
  "name": "ata_set_max_sectors",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ata_set_max_sectors",
      "external": false,
      "loc": "drivers/ata/libata-core.c:1267",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_dev_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586780384,
      "name": "ata_set_max_sectors",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 355
    },
    {
      "addr": 18446744071586795964,
      "name": "ata_set_max_sectors.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
int ata_set_max_sectors(struct ata_device * dev, u64 new_sectors)
```

```json
{
  "name": "ata_set_max_sectors",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ata_set_max_sectors",
      "external": false,
      "loc": "drivers/ata/libata-core.c:1210",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_hpa_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587585280,
      "name": "ata_set_max_sectors",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 351
    },
    {
      "addr": 18446744071587599764,
      "name": "ata_set_max_sectors.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
int ata_set_max_sectors(struct ata_device * dev, u64 new_sectors)
```

```json
{
  "name": "ata_set_max_sectors",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ata_set_max_sectors",
      "external": false,
      "loc": "drivers/ata/libata-core.c:1210",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_hpa_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587651440,
      "name": "ata_set_max_sectors",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 358
    },
    {
      "addr": 18446744071591523751,
      "name": "ata_set_max_sectors.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
  "name": "ata_set_max_sectors",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587534897,
      "name": "ata_set_max_sectors",
      "external": false,
      "loc": "drivers/ata/libata-core.c:1210",
      "file": "drivers/ata/libata-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:ata_hpa_resize"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ata_set_max_sectors",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588112529,
      "name": "ata_set_max_sectors",
      "external": false,
      "loc": "drivers/ata/libata-core.c:1214",
      "file": "drivers/ata/libata-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:ata_hpa_resize"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int ata_set_max_sectors(struct ata_device * dev, u64 new_sectors)
```

```json
{
  "name": "ata_set_max_sectors",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ata_set_max_sectors",
      "external": false,
      "loc": "drivers/ata/libata-core.c:1207",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_hpa_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589486736,
      "name": "ata_set_max_sectors",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
    },
    {
      "addr": 18446744071594404469,
      "name": "ata_set_max_sectors.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
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
int ata_set_max_sectors(struct ata_device * dev, u64 new_sectors)
```

```json
{
  "name": "ata_set_max_sectors",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591068224,
      "name": "ata_set_max_sectors",
      "external": false,
      "loc": "drivers/ata/libata-core.c:1207",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_hpa_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591068224,
      "name": "ata_set_max_sectors",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 459
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
int ata_set_max_sectors(struct ata_device * dev, u64 new_sectors)
```

```json
{
  "name": "ata_set_max_sectors",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591423712,
      "name": "ata_set_max_sectors",
      "external": false,
      "loc": "drivers/ata/libata-core.c:1241",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_hpa_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591423712,
      "name": "ata_set_max_sectors",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 459
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
int ata_set_max_sectors(struct ata_device * dev, u64 new_sectors)
```

```json
{
  "name": "ata_set_max_sectors",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591776048,
      "name": "ata_set_max_sectors",
      "external": false,
      "loc": "drivers/ata/libata-core.c:1241",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_hpa_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591776048,
      "name": "ata_set_max_sectors",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 459
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
int ata_set_max_sectors(struct ata_device * dev, u64 new_sectors)
```

```json
{
  "name": "ata_set_max_sectors",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499704648,
      "name": "ata_set_max_sectors",
      "external": false,
      "loc": "drivers/ata/libata-core.c:1267",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_dev_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499704648,
      "name": "ata_set_max_sectors",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 428
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "ata_set_max_sectors",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3232157840,
      "name": "ata_set_max_sectors",
      "external": false,
      "loc": "drivers/ata/libata-core.c:1267",
      "file": "drivers/ata/libata-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-core.c:ata_dev_configure"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int ata_set_max_sectors(struct ata_device * dev, u64 new_sectors)
```

```json
{
  "name": "ata_set_max_sectors",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293037152,
      "name": "ata_set_max_sectors",
      "external": false,
      "loc": "drivers/ata/libata-core.c:1267",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_dev_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293037152,
      "name": "ata_set_max_sectors",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 560
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int ata_set_max_sectors(struct ata_device * dev, u64 new_sectors)
```

```json
{
  "name": "ata_set_max_sectors",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276871534,
      "name": "ata_set_max_sectors",
      "external": false,
      "loc": "drivers/ata/libata-core.c:1267",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_dev_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276871534,
      "name": "ata_set_max_sectors",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 310
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int ata_set_max_sectors(struct ata_device * dev, u64 new_sectors)
```

```json
{
  "name": "ata_set_max_sectors",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ata_set_max_sectors",
      "external": false,
      "loc": "drivers/ata/libata-core.c:1267",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_dev_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586539040,
      "name": "ata_set_max_sectors",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 355
    },
    {
      "addr": 18446744071586554572,
      "name": "ata_set_max_sectors.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
int ata_set_max_sectors(struct ata_device * dev, u64 new_sectors)
```

```json
{
  "name": "ata_set_max_sectors",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ata_set_max_sectors",
      "external": false,
      "loc": "drivers/ata/libata-core.c:1267",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_dev_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586407616,
      "name": "ata_set_max_sectors",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 355
    },
    {
      "addr": 18446744071586423148,
      "name": "ata_set_max_sectors.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
int ata_set_max_sectors(struct ata_device * dev, u64 new_sectors)
```

```json
{
  "name": "ata_set_max_sectors",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ata_set_max_sectors",
      "external": false,
      "loc": "drivers/ata/libata-core.c:1267",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_dev_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586734944,
      "name": "ata_set_max_sectors",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 355
    },
    {
      "addr": 18446744071586750524,
      "name": "ata_set_max_sectors.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
int ata_set_max_sectors(struct ata_device * dev, u64 new_sectors)
```

```json
{
  "name": "ata_set_max_sectors",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ata_set_max_sectors",
      "external": false,
      "loc": "drivers/ata/libata-core.c:1267",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_dev_configure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586841008,
      "name": "ata_set_max_sectors",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 355
    },
    {
      "addr": 18446744071586856588,
      "name": "ata_set_max_sectors.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
int ata_set_max_sectors(struct ata_device * dev, u64 new_sectors)
```
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
int ata_set_max_sectors(struct ata_device * dev, u64 new_sectors)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int ata_set_max_sectors(struct ata_device * dev, u64 new_sectors)
```
</details>
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
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
int ata_set_max_sectors(struct ata_device * dev, u64 new_sectors)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
int ata_set_max_sectors(struct ata_device * dev, u64 new_sectors)
```
</details>
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
int ata_set_max_sectors(struct ata_device * dev, u64 new_sectors)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
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
