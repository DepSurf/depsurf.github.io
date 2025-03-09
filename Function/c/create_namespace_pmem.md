# Function: <code>create_namespace_pmem</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "create_namespace_pmem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584736014,
      "name": "create_namespace_pmem",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1634",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces"
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
  "name": "create_namespace_pmem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585088339,
      "name": "create_namespace_pmem",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1676",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct device * create_namespace_pmem(struct nd_region * nd_region, struct nd_namespace_label * nd_label)
```

```json
{
  "name": "create_namespace_pmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585271888,
      "name": "create_namespace_pmem",
      "external": true,
      "loc": "drivers/nvdimm/namespace_devs.c:1700",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585271888,
      "name": "create_namespace_pmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1351
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
struct device * create_namespace_pmem(struct nd_region * nd_region, struct nd_namespace_index * nsindex, struct nd_namespace_label * nd_label)
```

```json
{
  "name": "create_namespace_pmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585356352,
      "name": "create_namespace_pmem",
      "external": true,
      "loc": "drivers/nvdimm/namespace_devs.c:1869",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585356352,
      "name": "create_namespace_pmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1417
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "create_namespace_pmem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585786280,
      "name": "create_namespace_pmem",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1878",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:scan_labels"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "create_namespace_pmem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586033210,
      "name": "create_namespace_pmem",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1873",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:scan_labels"
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
  "name": "create_namespace_pmem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586172398,
      "name": "create_namespace_pmem",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1899",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:scan_labels"
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
struct device * create_namespace_pmem(struct nd_region * nd_region, struct nd_namespace_index * nsindex, struct nd_namespace_label * nd_label)
```

```json
{
  "name": "create_namespace_pmem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "create_namespace_pmem",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1906",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:scan_labels"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586402480,
      "name": "create_namespace_pmem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1417
    },
    {
      "addr": 18446744071586413085,
      "name": "create_namespace_pmem.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
struct device * create_namespace_pmem(struct nd_region * nd_region, struct nd_namespace_index * nsindex, struct nd_namespace_label * nd_label)
```

```json
{
  "name": "create_namespace_pmem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586549312,
      "name": "create_namespace_pmem",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1906",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:scan_labels"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586549312,
      "name": "create_namespace_pmem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1401
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
struct device * create_namespace_pmem(struct nd_region * nd_region, struct nd_namespace_index * nsindex, struct nd_namespace_label * nd_label)
```

```json
{
  "name": "create_namespace_pmem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587335392,
      "name": "create_namespace_pmem",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1949",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:scan_labels"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587335392,
      "name": "create_namespace_pmem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1122
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
struct device * create_namespace_pmem(struct nd_region * nd_region, struct nd_namespace_index * nsindex, struct nd_namespace_label * nd_label)
```

```json
{
  "name": "create_namespace_pmem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587397136,
      "name": "create_namespace_pmem",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1949",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:scan_labels"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587397136,
      "name": "create_namespace_pmem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1106
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
struct device * create_namespace_pmem(struct nd_region * nd_region, struct nd_namespace_index * nsindex, struct nd_namespace_label * nd_label)
```

```json
{
  "name": "create_namespace_pmem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587278896,
      "name": "create_namespace_pmem",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1949",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:scan_labels"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587278896,
      "name": "create_namespace_pmem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1106
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
struct device * create_namespace_pmem(struct nd_region * nd_region, struct nd_mapping * nd_mapping, struct nd_namespace_label * nd_label)
```

```json
{
  "name": "create_namespace_pmem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587845712,
      "name": "create_namespace_pmem",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1942",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:scan_labels"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587845712,
      "name": "create_namespace_pmem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1116
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
struct device * create_namespace_pmem(struct nd_region * nd_region, struct nd_mapping * nd_mapping, struct nd_namespace_label * nd_label)
```

```json
{
  "name": "create_namespace_pmem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "create_namespace_pmem",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1669",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:scan_labels"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589198320,
      "name": "create_namespace_pmem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1568
    },
    {
      "addr": 18446744071594391938,
      "name": "create_namespace_pmem.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 341
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
struct device * create_namespace_pmem(struct nd_region * nd_region, struct nd_mapping * nd_mapping, struct nd_namespace_label * nd_label)
```

```json
{
  "name": "create_namespace_pmem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "create_namespace_pmem",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1661",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:scan_labels"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590753216,
      "name": "create_namespace_pmem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1620
    },
    {
      "addr": 18446744071596256090,
      "name": "create_namespace_pmem.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 319
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
struct device * create_namespace_pmem(struct nd_region * nd_region, struct nd_mapping * nd_mapping, struct nd_namespace_label * nd_label)
```

```json
{
  "name": "create_namespace_pmem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "create_namespace_pmem",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1661",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:scan_labels"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591094640,
      "name": "create_namespace_pmem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1611
    },
    {
      "addr": 18446744071596784338,
      "name": "create_namespace_pmem.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
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
struct device * create_namespace_pmem(struct nd_region * nd_region, struct nd_mapping * nd_mapping, struct nd_namespace_label * nd_label)
```

```json
{
  "name": "create_namespace_pmem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "create_namespace_pmem",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1672",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:scan_labels"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591439632,
      "name": "create_namespace_pmem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1658
    },
    {
      "addr": 18446744071597693273,
      "name": "create_namespace_pmem.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
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
struct device * create_namespace_pmem(struct nd_region * nd_region, struct nd_namespace_index * nsindex, struct nd_namespace_label * nd_label)
```

```json
{
  "name": "create_namespace_pmem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499438960,
      "name": "create_namespace_pmem",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1906",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:scan_labels"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499438960,
      "name": "create_namespace_pmem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1344
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
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct device * create_namespace_pmem(struct nd_region * nd_region, struct nd_namespace_index * nsindex, struct nd_namespace_label * nd_label)
```

```json
{
  "name": "create_namespace_pmem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292692176,
      "name": "create_namespace_pmem",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1906",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:scan_labels"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292692176,
      "name": "create_namespace_pmem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1760
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
struct device * create_namespace_pmem(struct nd_region * nd_region, struct nd_namespace_index * nsindex, struct nd_namespace_label * nd_label)
```

```json
{
  "name": "create_namespace_pmem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276663992,
      "name": "create_namespace_pmem",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1906",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:scan_labels"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276663992,
      "name": "create_namespace_pmem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1160
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct device * create_namespace_pmem(struct nd_region * nd_region, struct nd_namespace_index * nsindex, struct nd_namespace_label * nd_label)
```

```json
{
  "name": "create_namespace_pmem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586239792,
      "name": "create_namespace_pmem",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1906",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:scan_labels"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586239792,
      "name": "create_namespace_pmem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1401
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
struct device * create_namespace_pmem(struct nd_region * nd_region, struct nd_namespace_index * nsindex, struct nd_namespace_label * nd_label)
```

```json
{
  "name": "create_namespace_pmem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586058160,
      "name": "create_namespace_pmem",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1906",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:scan_labels"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586058160,
      "name": "create_namespace_pmem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1401
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
struct device * create_namespace_pmem(struct nd_region * nd_region, struct nd_namespace_index * nsindex, struct nd_namespace_label * nd_label)
```

```json
{
  "name": "create_namespace_pmem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586497280,
      "name": "create_namespace_pmem",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1906",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:scan_labels"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586497280,
      "name": "create_namespace_pmem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1401
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
struct device * create_namespace_pmem(struct nd_region * nd_region, struct nd_namespace_index * nsindex, struct nd_namespace_label * nd_label)
```

```json
{
  "name": "create_namespace_pmem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586609024,
      "name": "create_namespace_pmem",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1906",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:scan_labels"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586609024,
      "name": "create_namespace_pmem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1401
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
struct device * create_namespace_pmem(struct nd_region * nd_region, struct nd_namespace_label * nd_label)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct nd_namespace_index * nsindex</code>
</li>
<li>
<b>Param reordered. </b>
<code>nd_region, nd_label</code> ➡️ <code>nd_region, nsindex, nd_label</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➖</summary>

```c
struct device * create_namespace_pmem(struct nd_region * nd_region, struct nd_namespace_index * nsindex, struct nd_namespace_label * nd_label)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
struct device * create_namespace_pmem(struct nd_region * nd_region, struct nd_namespace_index * nsindex, struct nd_namespace_label * nd_label)
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
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct nd_mapping * nd_mapping</code>
</li>
<li>
<b>Param removed. </b>
<code>struct nd_namespace_index * nsindex</code>
</li>
</ul>
</details>
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
struct device * create_namespace_pmem(struct nd_region * nd_region, struct nd_namespace_index * nsindex, struct nd_namespace_label * nd_label)
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
