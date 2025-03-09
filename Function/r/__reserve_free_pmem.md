# Function: <code>__reserve_free_pmem</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __reserve_free_pmem(struct device * dev, void * data)
```

```json
{
  "name": "__reserve_free_pmem",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584730048,
      "name": "__reserve_free_pmem",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:715",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584730048,
      "name": "__reserve_free_pmem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 442
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __reserve_free_pmem(struct device * dev, void * data)
```

```json
{
  "name": "__reserve_free_pmem",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585082272,
      "name": "__reserve_free_pmem",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:712",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585082272,
      "name": "__reserve_free_pmem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 442
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __reserve_free_pmem(struct device * dev, void * data)
```

```json
{
  "name": "__reserve_free_pmem",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585268720,
      "name": "__reserve_free_pmem",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:783",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585268720,
      "name": "__reserve_free_pmem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 446
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __reserve_free_pmem(struct device * dev, void * data)
```

```json
{
  "name": "__reserve_free_pmem",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585353328,
      "name": "__reserve_free_pmem",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:802",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585353328,
      "name": "__reserve_free_pmem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 458
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
int __reserve_free_pmem(struct device * dev, void * data)
```

```json
{
  "name": "__reserve_free_pmem",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585781744,
      "name": "__reserve_free_pmem",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:802",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585781744,
      "name": "__reserve_free_pmem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 458
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __reserve_free_pmem(struct device * dev, void * data)
```

```json
{
  "name": "__reserve_free_pmem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "__reserve_free_pmem",
      "external": true,
      "loc": "drivers/nvdimm/namespace_devs.c:802",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586037400,
      "name": "__reserve_free_pmem.cold.23",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071586026208,
      "name": "__reserve_free_pmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 451
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __reserve_free_pmem(struct device * dev, void * data)
```

```json
{
  "name": "__reserve_free_pmem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586165414,
      "name": "__reserve_free_pmem",
      "external": true,
      "loc": "drivers/nvdimm/namespace_devs.c:805",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586176659,
      "name": "__reserve_free_pmem.cold.23",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071586165360,
      "name": "__reserve_free_pmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 451
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __reserve_free_pmem(struct device * dev, void * data)
```

```json
{
  "name": "__reserve_free_pmem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586401558,
      "name": "__reserve_free_pmem",
      "external": true,
      "loc": "drivers/nvdimm/namespace_devs.c:797",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586413073,
      "name": "__reserve_free_pmem.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071586401504,
      "name": "__reserve_free_pmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 437
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __reserve_free_pmem(struct device * dev, void * data)
```

```json
{
  "name": "__reserve_free_pmem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586548390,
      "name": "__reserve_free_pmem",
      "external": true,
      "loc": "drivers/nvdimm/namespace_devs.c:797",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586559974,
      "name": "__reserve_free_pmem.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071586548336,
      "name": "__reserve_free_pmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 437
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __reserve_free_pmem(struct device * dev, void * data)
```

```json
{
  "name": "__reserve_free_pmem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587333344,
      "name": "__reserve_free_pmem",
      "external": true,
      "loc": "drivers/nvdimm/namespace_devs.c:777",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587332112,
      "name": "__reserve_free_pmem.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 401
    },
    {
      "addr": 18446744071587344377,
      "name": "__reserve_free_pmem.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071587333344,
      "name": "__reserve_free_pmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __reserve_free_pmem(struct device * dev, void * data)
```

```json
{
  "name": "__reserve_free_pmem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587395088,
      "name": "__reserve_free_pmem",
      "external": true,
      "loc": "drivers/nvdimm/namespace_devs.c:777",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587393856,
      "name": "__reserve_free_pmem.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 401
    },
    {
      "addr": 18446744071591517160,
      "name": "__reserve_free_pmem.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071587395088,
      "name": "__reserve_free_pmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __reserve_free_pmem(struct device * dev, void * data)
```

```json
{
  "name": "__reserve_free_pmem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587277318,
      "name": "__reserve_free_pmem",
      "external": true,
      "loc": "drivers/nvdimm/namespace_devs.c:777",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591459201,
      "name": "__reserve_free_pmem.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071587277264,
      "name": "__reserve_free_pmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 437
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __reserve_free_pmem(struct device * dev, void * data)
```

```json
{
  "name": "__reserve_free_pmem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587844806,
      "name": "__reserve_free_pmem",
      "external": true,
      "loc": "drivers/nvdimm/namespace_devs.c:777",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592522310,
      "name": "__reserve_free_pmem.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071587844752,
      "name": "__reserve_free_pmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 456
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
int __reserve_free_pmem(struct device * dev, void * data)
```

```json
{
  "name": "__reserve_free_pmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__reserve_free_pmem",
      "external": true,
      "loc": "drivers/nvdimm/namespace_devs.c:607",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594392561,
      "name": "__reserve_free_pmem.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071589202480,
      "name": "__reserve_free_pmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 475
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
int __reserve_free_pmem(struct device * dev, void * data)
```

```json
{
  "name": "__reserve_free_pmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__reserve_free_pmem",
      "external": true,
      "loc": "drivers/nvdimm/namespace_devs.c:604",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596256680,
      "name": "__reserve_free_pmem.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071590757520,
      "name": "__reserve_free_pmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 487
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
int __reserve_free_pmem(struct device * dev, void * data)
```

```json
{
  "name": "__reserve_free_pmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__reserve_free_pmem",
      "external": true,
      "loc": "drivers/nvdimm/namespace_devs.c:604",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596784812,
      "name": "__reserve_free_pmem.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071591098992,
      "name": "__reserve_free_pmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 465
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
int __reserve_free_pmem(struct device * dev, void * data)
```

```json
{
  "name": "__reserve_free_pmem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__reserve_free_pmem",
      "external": true,
      "loc": "drivers/nvdimm/namespace_devs.c:609",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597693747,
      "name": "__reserve_free_pmem.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071591444128,
      "name": "__reserve_free_pmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 465
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
int __reserve_free_pmem(struct device * dev, void * data)
```

```json
{
  "name": "__reserve_free_pmem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499437952,
      "name": "__reserve_free_pmem",
      "external": true,
      "loc": "drivers/nvdimm/namespace_devs.c:797",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499437952,
      "name": "__reserve_free_pmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 440
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int __reserve_free_pmem(struct device * dev, void * data)
```

```json
{
  "name": "__reserve_free_pmem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055292689936,
      "name": "__reserve_free_pmem",
      "external": true,
      "loc": "drivers/nvdimm/namespace_devs.c:797",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292689936,
      "name": "__reserve_free_pmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 576
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int __reserve_free_pmem(struct device * dev, void * data)
```

```json
{
  "name": "__reserve_free_pmem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276663642,
      "name": "__reserve_free_pmem",
      "external": true,
      "loc": "drivers/nvdimm/namespace_devs.c:797",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276663642,
      "name": "__reserve_free_pmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 350
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __reserve_free_pmem(struct device * dev, void * data)
```

```json
{
  "name": "__reserve_free_pmem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586238870,
      "name": "__reserve_free_pmem",
      "external": true,
      "loc": "drivers/nvdimm/namespace_devs.c:797",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586250454,
      "name": "__reserve_free_pmem.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071586238816,
      "name": "__reserve_free_pmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 437
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __reserve_free_pmem(struct device * dev, void * data)
```

```json
{
  "name": "__reserve_free_pmem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586057238,
      "name": "__reserve_free_pmem",
      "external": true,
      "loc": "drivers/nvdimm/namespace_devs.c:797",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586068822,
      "name": "__reserve_free_pmem.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071586057184,
      "name": "__reserve_free_pmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 437
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __reserve_free_pmem(struct device * dev, void * data)
```

```json
{
  "name": "__reserve_free_pmem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586496358,
      "name": "__reserve_free_pmem",
      "external": true,
      "loc": "drivers/nvdimm/namespace_devs.c:797",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586507942,
      "name": "__reserve_free_pmem.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071586496304,
      "name": "__reserve_free_pmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 437
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __reserve_free_pmem(struct device * dev, void * data)
```

```json
{
  "name": "__reserve_free_pmem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586608102,
      "name": "__reserve_free_pmem",
      "external": true,
      "loc": "drivers/nvdimm/namespace_devs.c:797",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586619686,
      "name": "__reserve_free_pmem.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071586608048,
      "name": "__reserve_free_pmem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 437
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
int __reserve_free_pmem(struct device * dev, void * data)
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
