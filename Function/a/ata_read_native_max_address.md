# Function: <code>ata_read_native_max_address</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ata_read_native_max_address",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584925058,
      "name": "ata_read_native_max_address",
      "external": false,
      "loc": "drivers/ata/libata-core.c:1222",
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
  "name": "ata_read_native_max_address",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585287557,
      "name": "ata_read_native_max_address",
      "external": false,
      "loc": "drivers/ata/libata-core.c:1225",
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
  "name": "ata_read_native_max_address",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585487141,
      "name": "ata_read_native_max_address",
      "external": false,
      "loc": "drivers/ata/libata-core.c:1232",
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
int ata_read_native_max_address(struct ata_device * dev, u64 * max_sectors)
```

```json
{
  "name": "ata_read_native_max_address",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585569216,
      "name": "ata_read_native_max_address",
      "external": false,
      "loc": "drivers/ata/libata-core.c:1232",
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
      "addr": 18446744071585569216,
      "name": "ata_read_native_max_address",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 492
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
int ata_read_native_max_address(struct ata_device * dev, u64 * max_sectors)
```

```json
{
  "name": "ata_read_native_max_address",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586000912,
      "name": "ata_read_native_max_address",
      "external": false,
      "loc": "drivers/ata/libata-core.c:1232",
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
      "addr": 18446744071586000912,
      "name": "ata_read_native_max_address",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 492
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
  "name": "ata_read_native_max_address",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586250076,
      "name": "ata_read_native_max_address",
      "external": false,
      "loc": "drivers/ata/libata-core.c:1232",
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
  "name": "ata_read_native_max_address",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586390540,
      "name": "ata_read_native_max_address",
      "external": false,
      "loc": "drivers/ata/libata-core.c:1232",
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
int ata_read_native_max_address(struct ata_device * dev, u64 * max_sectors)
```

```json
{
  "name": "ata_read_native_max_address",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ata_read_native_max_address",
      "external": false,
      "loc": "drivers/ata/libata-core.c:1216",
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
      "addr": 18446744071586632304,
      "name": "ata_read_native_max_address",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 504
    },
    {
      "addr": 18446744071586648478,
      "name": "ata_read_native_max_address.cold",
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
int ata_read_native_max_address(struct ata_device * dev, u64 * max_sectors)
```

```json
{
  "name": "ata_read_native_max_address",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ata_read_native_max_address",
      "external": false,
      "loc": "drivers/ata/libata-core.c:1216",
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
      "addr": 18446744071586779872,
      "name": "ata_read_native_max_address",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 504
    },
    {
      "addr": 18446744071586795897,
      "name": "ata_read_native_max_address.cold",
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
int ata_read_native_max_address(struct ata_device * dev, u64 * max_sectors)
```

```json
{
  "name": "ata_read_native_max_address",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ata_read_native_max_address",
      "external": false,
      "loc": "drivers/ata/libata-core.c:1159",
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
      "addr": 18446744071587584784,
      "name": "ata_read_native_max_address",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 496
    },
    {
      "addr": 18446744071587599697,
      "name": "ata_read_native_max_address.cold",
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
int ata_read_native_max_address(struct ata_device * dev, u64 * max_sectors)
```

```json
{
  "name": "ata_read_native_max_address",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ata_read_native_max_address",
      "external": false,
      "loc": "drivers/ata/libata-core.c:1159",
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
      "addr": 18446744071587650944,
      "name": "ata_read_native_max_address",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 496
    },
    {
      "addr": 18446744071591523684,
      "name": "ata_read_native_max_address.cold",
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
  "name": "ata_read_native_max_address",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587534395,
      "name": "ata_read_native_max_address",
      "external": false,
      "loc": "drivers/ata/libata-core.c:1159",
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
  "name": "ata_read_native_max_address",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588112027,
      "name": "ata_read_native_max_address",
      "external": false,
      "loc": "drivers/ata/libata-core.c:1163",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ata_read_native_max_address",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589492042,
      "name": "ata_read_native_max_address",
      "external": false,
      "loc": "drivers/ata/libata-core.c:1156",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ata_read_native_max_address",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591074266,
      "name": "ata_read_native_max_address",
      "external": false,
      "loc": "drivers/ata/libata-core.c:1156",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ata_read_native_max_address",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591430714,
      "name": "ata_read_native_max_address",
      "external": false,
      "loc": "drivers/ata/libata-core.c:1190",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ata_read_native_max_address",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591783082,
      "name": "ata_read_native_max_address",
      "external": false,
      "loc": "drivers/ata/libata-core.c:1190",
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
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int ata_read_native_max_address(struct ata_device * dev, u64 * max_sectors)
```

```json
{
  "name": "ata_read_native_max_address",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499704088,
      "name": "ata_read_native_max_address",
      "external": false,
      "loc": "drivers/ata/libata-core.c:1216",
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
      "addr": 18446603336499704088,
      "name": "ata_read_native_max_address",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 556
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
  "name": "ata_read_native_max_address",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3232155008,
      "name": "ata_read_native_max_address",
      "external": false,
      "loc": "drivers/ata/libata-core.c:1216",
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
int ata_read_native_max_address(struct ata_device * dev, u64 * max_sectors)
```

```json
{
  "name": "ata_read_native_max_address",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293036432,
      "name": "ata_read_native_max_address",
      "external": false,
      "loc": "drivers/ata/libata-core.c:1216",
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
      "addr": 13835058055293036432,
      "name": "ata_read_native_max_address",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 720
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
int ata_read_native_max_address(struct ata_device * dev, u64 * max_sectors)
```

```json
{
  "name": "ata_read_native_max_address",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276871128,
      "name": "ata_read_native_max_address",
      "external": false,
      "loc": "drivers/ata/libata-core.c:1216",
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
      "addr": 18446743936276871128,
      "name": "ata_read_native_max_address",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 406
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
int ata_read_native_max_address(struct ata_device * dev, u64 * max_sectors)
```

```json
{
  "name": "ata_read_native_max_address",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ata_read_native_max_address",
      "external": false,
      "loc": "drivers/ata/libata-core.c:1216",
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
      "addr": 18446744071586538528,
      "name": "ata_read_native_max_address",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 504
    },
    {
      "addr": 18446744071586554505,
      "name": "ata_read_native_max_address.cold",
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
int ata_read_native_max_address(struct ata_device * dev, u64 * max_sectors)
```

```json
{
  "name": "ata_read_native_max_address",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ata_read_native_max_address",
      "external": false,
      "loc": "drivers/ata/libata-core.c:1216",
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
      "addr": 18446744071586407104,
      "name": "ata_read_native_max_address",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 504
    },
    {
      "addr": 18446744071586423081,
      "name": "ata_read_native_max_address.cold",
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
int ata_read_native_max_address(struct ata_device * dev, u64 * max_sectors)
```

```json
{
  "name": "ata_read_native_max_address",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ata_read_native_max_address",
      "external": false,
      "loc": "drivers/ata/libata-core.c:1216",
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
      "addr": 18446744071586734432,
      "name": "ata_read_native_max_address",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 504
    },
    {
      "addr": 18446744071586750457,
      "name": "ata_read_native_max_address.cold",
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
int ata_read_native_max_address(struct ata_device * dev, u64 * max_sectors)
```

```json
{
  "name": "ata_read_native_max_address",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ata_read_native_max_address",
      "external": false,
      "loc": "drivers/ata/libata-core.c:1216",
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
      "addr": 18446744071586840496,
      "name": "ata_read_native_max_address",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 504
    },
    {
      "addr": 18446744071586856521,
      "name": "ata_read_native_max_address.cold",
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
int ata_read_native_max_address(struct ata_device * dev, u64 * max_sectors)
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
int ata_read_native_max_address(struct ata_device * dev, u64 * max_sectors)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int ata_read_native_max_address(struct ata_device * dev, u64 * max_sectors)
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
int ata_read_native_max_address(struct ata_device * dev, u64 * max_sectors)
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
int ata_read_native_max_address(struct ata_device * dev, u64 * max_sectors)
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
