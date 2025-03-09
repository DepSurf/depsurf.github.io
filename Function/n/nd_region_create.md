# Function: <code>nd_region_create</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct nd_region * nd_region_create(struct nvdimm_bus * nvdimm_bus, struct nd_region_desc * ndr_desc, struct device_type * dev_type, const char * caller)
```

```json
{
  "name": "nd_region_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584720304,
      "name": "nd_region_create",
      "external": false,
      "loc": "drivers/nvdimm/region_devs.c:627",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/region_devs.c:nvdimm_pmem_region_create",
        "drivers/nvdimm/region_devs.c:nvdimm_volatile_region_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584720304,
      "name": "nd_region_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 805
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct nd_region * nd_region_create(struct nvdimm_bus * nvdimm_bus, struct nd_region_desc * ndr_desc, struct device_type * dev_type, const char * caller)
```

```json
{
  "name": "nd_region_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585071856,
      "name": "nd_region_create",
      "external": false,
      "loc": "drivers/nvdimm/region_devs.c:751",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/region_devs.c:nvdimm_volatile_region_create",
        "drivers/nvdimm/region_devs.c:nvdimm_pmem_region_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585071856,
      "name": "nd_region_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 785
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
struct nd_region * nd_region_create(struct nvdimm_bus * nvdimm_bus, struct nd_region_desc * ndr_desc, struct device_type * dev_type, const char * caller)
```

```json
{
  "name": "nd_region_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585255936,
      "name": "nd_region_create",
      "external": false,
      "loc": "drivers/nvdimm/region_devs.c:795",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/region_devs.c:nvdimm_volatile_region_create",
        "drivers/nvdimm/region_devs.c:nvdimm_pmem_region_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585255936,
      "name": "nd_region_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 828
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
struct nd_region * nd_region_create(struct nvdimm_bus * nvdimm_bus, struct nd_region_desc * ndr_desc, struct device_type * dev_type, const char * caller)
```

```json
{
  "name": "nd_region_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585338960,
      "name": "nd_region_create",
      "external": false,
      "loc": "drivers/nvdimm/region_devs.c:896",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/region_devs.c:nvdimm_volatile_region_create",
        "drivers/nvdimm/region_devs.c:nvdimm_blk_region_create",
        "drivers/nvdimm/region_devs.c:nvdimm_pmem_region_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585338960,
      "name": "nd_region_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 883
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
struct nd_region * nd_region_create(struct nvdimm_bus * nvdimm_bus, struct nd_region_desc * ndr_desc, struct device_type * dev_type, const char * caller)
```

```json
{
  "name": "nd_region_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585767296,
      "name": "nd_region_create",
      "external": false,
      "loc": "drivers/nvdimm/region_devs.c:916",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/region_devs.c:nvdimm_volatile_region_create",
        "drivers/nvdimm/region_devs.c:nvdimm_blk_region_create",
        "drivers/nvdimm/region_devs.c:nvdimm_pmem_region_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585767296,
      "name": "nd_region_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 930
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
struct nd_region * nd_region_create(struct nvdimm_bus * nvdimm_bus, struct nd_region_desc * ndr_desc, struct device_type * dev_type, const char * caller)
```

```json
{
  "name": "nd_region_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586013792,
      "name": "nd_region_create",
      "external": false,
      "loc": "drivers/nvdimm/region_devs.c:955",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/region_devs.c:nvdimm_volatile_region_create",
        "drivers/nvdimm/region_devs.c:nvdimm_pmem_region_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586013792,
      "name": "nd_region_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 917
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
struct nd_region * nd_region_create(struct nvdimm_bus * nvdimm_bus, struct nd_region_desc * ndr_desc, struct device_type * dev_type, const char * caller)
```

```json
{
  "name": "nd_region_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586152464,
      "name": "nd_region_create",
      "external": false,
      "loc": "drivers/nvdimm/region_devs.c:983",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/region_devs.c:nvdimm_volatile_region_create",
        "drivers/nvdimm/region_devs.c:nvdimm_pmem_region_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586152464,
      "name": "nd_region_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 920
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
struct nd_region * nd_region_create(struct nvdimm_bus * nvdimm_bus, struct nd_region_desc * ndr_desc, struct device_type * dev_type, const char * caller)
```

```json
{
  "name": "nd_region_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nd_region_create",
      "external": false,
      "loc": "drivers/nvdimm/region_devs.c:981",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/region_devs.c:nvdimm_volatile_region_create",
        "drivers/nvdimm/region_devs.c:nvdimm_pmem_region_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586387712,
      "name": "nd_region_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 889
    },
    {
      "addr": 18446744071586392670,
      "name": "nd_region_create.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
struct nd_region * nd_region_create(struct nvdimm_bus * nvdimm_bus, struct nd_region_desc * ndr_desc, struct device_type * dev_type, const char * caller)
```

```json
{
  "name": "nd_region_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nd_region_create",
      "external": false,
      "loc": "drivers/nvdimm/region_devs.c:933",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/region_devs.c:nvdimm_volatile_region_create",
        "drivers/nvdimm/region_devs.c:nvdimm_pmem_region_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586535536,
      "name": "nd_region_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 887
    },
    {
      "addr": 18446744071586539422,
      "name": "nd_region_create.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
struct nd_region * nd_region_create(struct nvdimm_bus * nvdimm_bus, struct nd_region_desc * ndr_desc, const struct device_type * dev_type, const char * caller)
```

```json
{
  "name": "nd_region_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nd_region_create",
      "external": false,
      "loc": "drivers/nvdimm/region_devs.c:1029",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/region_devs.c:nvdimm_volatile_region_create",
        "drivers/nvdimm/region_devs.c:nvdimm_pmem_region_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587313472,
      "name": "nd_region_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 993
    },
    {
      "addr": 18446744071587323278,
      "name": "nd_region_create.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
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
struct nd_region * nd_region_create(struct nvdimm_bus * nvdimm_bus, struct nd_region_desc * ndr_desc, const struct device_type * dev_type, const char * caller)
```

```json
{
  "name": "nd_region_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nd_region_create",
      "external": false,
      "loc": "drivers/nvdimm/region_devs.c:1029",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/region_devs.c:nvdimm_volatile_region_create",
        "drivers/nvdimm/region_devs.c:nvdimm_pmem_region_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587375408,
      "name": "nd_region_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 993
    },
    {
      "addr": 18446744071591517001,
      "name": "nd_region_create.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
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
struct nd_region * nd_region_create(struct nvdimm_bus * nvdimm_bus, struct nd_region_desc * ndr_desc, const struct device_type * dev_type, const char * caller)
```

```json
{
  "name": "nd_region_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nd_region_create",
      "external": false,
      "loc": "drivers/nvdimm/region_devs.c:1036",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/region_devs.c:nvdimm_volatile_region_create",
        "drivers/nvdimm/region_devs.c:nvdimm_pmem_region_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587256544,
      "name": "nd_region_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 993
    },
    {
      "addr": 18446744071591458977,
      "name": "nd_region_create.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
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
struct nd_region * nd_region_create(struct nvdimm_bus * nvdimm_bus, struct nd_region_desc * ndr_desc, const struct device_type * dev_type, const char * caller)
```

```json
{
  "name": "nd_region_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nd_region_create",
      "external": false,
      "loc": "drivers/nvdimm/region_devs.c:1036",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/region_devs.c:nvdimm_volatile_region_create",
        "drivers/nvdimm/region_devs.c:nvdimm_pmem_region_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587826064,
      "name": "nd_region_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1039
    },
    {
      "addr": 18446744071592521714,
      "name": "nd_region_create.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
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
  "name": "nd_region_create",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "nd_region_create",
      "external": false,
      "loc": "drivers/nvdimm/region_devs.c:954",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/region_devs.c:nvdimm_volatile_region_create",
        "drivers/nvdimm/region_devs.c:nvdimm_pmem_region_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589177008,
      "name": "nd_region_create.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 913
    },
    {
      "addr": 18446744071594390571,
      "name": "nd_region_create.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
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
  "name": "nd_region_create",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590730288,
      "name": "nd_region_create",
      "external": false,
      "loc": "drivers/nvdimm/region_devs.c:999",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/region_devs.c:nvdimm_volatile_region_create",
        "drivers/nvdimm/region_devs.c:nvdimm_pmem_region_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590730288,
      "name": "nd_region_create.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1012
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
  "name": "nd_region_create",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591071616,
      "name": "nd_region_create",
      "external": false,
      "loc": "drivers/nvdimm/region_devs.c:999",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/region_devs.c:nvdimm_volatile_region_create",
        "drivers/nvdimm/region_devs.c:nvdimm_pmem_region_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591071616,
      "name": "nd_region_create.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1012
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
  "name": "nd_region_create",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591416512,
      "name": "nd_region_create",
      "external": false,
      "loc": "drivers/nvdimm/region_devs.c:1000",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/region_devs.c:nvdimm_volatile_region_create",
        "drivers/nvdimm/region_devs.c:nvdimm_pmem_region_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591416512,
      "name": "nd_region_create.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1013
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
struct nd_region * nd_region_create(struct nvdimm_bus * nvdimm_bus, struct nd_region_desc * ndr_desc, struct device_type * dev_type, const char * caller)
```

```json
{
  "name": "nd_region_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499423984,
      "name": "nd_region_create",
      "external": false,
      "loc": "drivers/nvdimm/region_devs.c:933",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/region_devs.c:nvdimm_volatile_region_create",
        "drivers/nvdimm/region_devs.c:nvdimm_pmem_region_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499423984,
      "name": "nd_region_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 928
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
struct nd_region * nd_region_create(struct nvdimm_bus * nvdimm_bus, struct nd_region_desc * ndr_desc, struct device_type * dev_type, const char * caller)
```

```json
{
  "name": "nd_region_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292667904,
      "name": "nd_region_create",
      "external": false,
      "loc": "drivers/nvdimm/region_devs.c:933",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/region_devs.c:nvdimm_volatile_region_create",
        "drivers/nvdimm/region_devs.c:nvdimm_pmem_region_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292667904,
      "name": "nd_region_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1208
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
struct nd_region * nd_region_create(struct nvdimm_bus * nvdimm_bus, struct nd_region_desc * ndr_desc, struct device_type * dev_type, const char * caller)
```

```json
{
  "name": "nd_region_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276651164,
      "name": "nd_region_create",
      "external": false,
      "loc": "drivers/nvdimm/region_devs.c:933",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/region_devs.c:nvdimm_volatile_region_create",
        "drivers/nvdimm/region_devs.c:nvdimm_pmem_region_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276651164,
      "name": "nd_region_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 788
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
struct nd_region * nd_region_create(struct nvdimm_bus * nvdimm_bus, struct nd_region_desc * ndr_desc, struct device_type * dev_type, const char * caller)
```

```json
{
  "name": "nd_region_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nd_region_create",
      "external": false,
      "loc": "drivers/nvdimm/region_devs.c:933",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/region_devs.c:nvdimm_volatile_region_create",
        "drivers/nvdimm/region_devs.c:nvdimm_pmem_region_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586226016,
      "name": "nd_region_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 887
    },
    {
      "addr": 18446744071586229902,
      "name": "nd_region_create.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
struct nd_region * nd_region_create(struct nvdimm_bus * nvdimm_bus, struct nd_region_desc * ndr_desc, struct device_type * dev_type, const char * caller)
```

```json
{
  "name": "nd_region_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nd_region_create",
      "external": false,
      "loc": "drivers/nvdimm/region_devs.c:933",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/region_devs.c:nvdimm_volatile_region_create",
        "drivers/nvdimm/region_devs.c:nvdimm_pmem_region_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586044384,
      "name": "nd_region_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 887
    },
    {
      "addr": 18446744071586048270,
      "name": "nd_region_create.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
struct nd_region * nd_region_create(struct nvdimm_bus * nvdimm_bus, struct nd_region_desc * ndr_desc, struct device_type * dev_type, const char * caller)
```

```json
{
  "name": "nd_region_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nd_region_create",
      "external": false,
      "loc": "drivers/nvdimm/region_devs.c:933",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/region_devs.c:nvdimm_volatile_region_create",
        "drivers/nvdimm/region_devs.c:nvdimm_pmem_region_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586483504,
      "name": "nd_region_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 887
    },
    {
      "addr": 18446744071586487390,
      "name": "nd_region_create.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
struct nd_region * nd_region_create(struct nvdimm_bus * nvdimm_bus, struct nd_region_desc * ndr_desc, struct device_type * dev_type, const char * caller)
```

```json
{
  "name": "nd_region_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nd_region_create",
      "external": false,
      "loc": "drivers/nvdimm/region_devs.c:933",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/region_devs.c:nvdimm_volatile_region_create",
        "drivers/nvdimm/region_devs.c:nvdimm_pmem_region_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586595248,
      "name": "nd_region_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 887
    },
    {
      "addr": 18446744071586599134,
      "name": "nd_region_create.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct device_type * dev_type</code> ➡️ <code>const struct device_type * dev_type</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
struct nd_region * nd_region_create(struct nvdimm_bus * nvdimm_bus, struct nd_region_desc * ndr_desc, const struct device_type * dev_type, const char * caller)
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
struct nd_region * nd_region_create(struct nvdimm_bus * nvdimm_bus, struct nd_region_desc * ndr_desc, struct device_type * dev_type, const char * caller)
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
