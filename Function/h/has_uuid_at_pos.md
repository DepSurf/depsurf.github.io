# Function: <code>has_uuid_at_pos</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "has_uuid_at_pos",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584736297,
      "name": "has_uuid_at_pos",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1444",
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
  "name": "has_uuid_at_pos",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585088622,
      "name": "has_uuid_at_pos",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1486",
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
bool has_uuid_at_pos(struct nd_region * nd_region, u8 * uuid, u64 cookie, u16 pos)
```

```json
{
  "name": "has_uuid_at_pos",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585262512,
      "name": "has_uuid_at_pos",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1594",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585262512,
      "name": "has_uuid_at_pos",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 337
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
bool has_uuid_at_pos(struct nd_region * nd_region, u8 * uuid, u64 cookie, u16 pos)
```

```json
{
  "name": "has_uuid_at_pos",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585353792,
      "name": "has_uuid_at_pos",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1752",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585353792,
      "name": "has_uuid_at_pos",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 528
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
bool has_uuid_at_pos(struct nd_region * nd_region, u8 * uuid, u64 cookie, u16 pos)
```

```json
{
  "name": "has_uuid_at_pos",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585782208,
      "name": "has_uuid_at_pos",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1761",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585782208,
      "name": "has_uuid_at_pos",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 528
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
bool has_uuid_at_pos(struct nd_region * nd_region, u8 * uuid, u64 cookie, u16 pos)
```

```json
{
  "name": "has_uuid_at_pos",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586026672,
      "name": "has_uuid_at_pos",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1758",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586026672,
      "name": "has_uuid_at_pos",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 509
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
bool has_uuid_at_pos(struct nd_region * nd_region, u8 * uuid, u64 cookie, u16 pos)
```

```json
{
  "name": "has_uuid_at_pos",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586165824,
      "name": "has_uuid_at_pos",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1784",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:scan_labels"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586165824,
      "name": "has_uuid_at_pos",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 516
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
bool has_uuid_at_pos(struct nd_region * nd_region, u8 * uuid, u64 cookie, u16 pos)
```

```json
{
  "name": "has_uuid_at_pos",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586401952,
      "name": "has_uuid_at_pos",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1791",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586401952,
      "name": "has_uuid_at_pos",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 516
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
bool has_uuid_at_pos(struct nd_region * nd_region, u8 * uuid, u64 cookie, u16 pos)
```

```json
{
  "name": "has_uuid_at_pos",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586548784,
      "name": "has_uuid_at_pos",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1791",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586548784,
      "name": "has_uuid_at_pos",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 516
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
bool has_uuid_at_pos(struct nd_region * nd_region, u8 * uuid, u64 cookie, u16 pos)
```

```json
{
  "name": "has_uuid_at_pos",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587333424,
      "name": "has_uuid_at_pos",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1834",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587333424,
      "name": "has_uuid_at_pos",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 516
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
bool has_uuid_at_pos(struct nd_region * nd_region, u8 * uuid, u64 cookie, u16 pos)
```

```json
{
  "name": "has_uuid_at_pos",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587395168,
      "name": "has_uuid_at_pos",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1834",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587395168,
      "name": "has_uuid_at_pos",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 516
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
bool has_uuid_at_pos(struct nd_region * nd_region, u8 * uuid, u64 cookie, u16 pos)
```

```json
{
  "name": "has_uuid_at_pos",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587277712,
      "name": "has_uuid_at_pos",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1834",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587277712,
      "name": "has_uuid_at_pos",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 516
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
bool has_uuid_at_pos(struct nd_region * nd_region, u8 * uuid, u64 cookie, u16 pos)
```

```json
{
  "name": "has_uuid_at_pos",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587840096,
      "name": "has_uuid_at_pos",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1834",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587840096,
      "name": "has_uuid_at_pos",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 361
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
bool has_uuid_at_pos(struct nd_region * nd_region, const uuid_t * uuid, u64 cookie, u16 pos)
```

```json
{
  "name": "has_uuid_at_pos",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "has_uuid_at_pos",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1561",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589196336,
      "name": "has_uuid_at_pos",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 585
    },
    {
      "addr": 18446744071594391479,
      "name": "has_uuid_at_pos.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 431
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
bool has_uuid_at_pos(struct nd_region * nd_region, const uuid_t * uuid, u64 cookie, u16 pos)
```

```json
{
  "name": "has_uuid_at_pos",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "has_uuid_at_pos",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1553",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590752608,
      "name": "has_uuid_at_pos",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 589
    },
    {
      "addr": 18446744071596255659,
      "name": "has_uuid_at_pos.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 431
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
bool has_uuid_at_pos(struct nd_region * nd_region, const uuid_t * uuid, u64 cookie, u16 pos)
```

```json
{
  "name": "has_uuid_at_pos",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "has_uuid_at_pos",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1553",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591091440,
      "name": "has_uuid_at_pos",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 576
    },
    {
      "addr": 18446744071596783945,
      "name": "has_uuid_at_pos.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 223
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
bool has_uuid_at_pos(struct nd_region * nd_region, const uuid_t * uuid, u64 cookie, u16 pos)
```

```json
{
  "name": "has_uuid_at_pos",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "has_uuid_at_pos",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1562",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591436384,
      "name": "has_uuid_at_pos",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 576
    },
    {
      "addr": 18446744071597692880,
      "name": "has_uuid_at_pos.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 223
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
bool has_uuid_at_pos(struct nd_region * nd_region, u8 * uuid, u64 cookie, u16 pos)
```

```json
{
  "name": "has_uuid_at_pos",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499438392,
      "name": "has_uuid_at_pos",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1791",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499438392,
      "name": "has_uuid_at_pos",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 564
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
bool has_uuid_at_pos(struct nd_region * nd_region, u8 * uuid, u64 cookie, u16 pos)
```

```json
{
  "name": "has_uuid_at_pos",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292690512,
      "name": "has_uuid_at_pos",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1791",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292690512,
      "name": "has_uuid_at_pos",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 696
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
bool has_uuid_at_pos(struct nd_region * nd_region, u8 * uuid, u64 cookie, u16 pos)
```

```json
{
  "name": "has_uuid_at_pos",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276660812,
      "name": "has_uuid_at_pos",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1791",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276660812,
      "name": "has_uuid_at_pos",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 388
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
bool has_uuid_at_pos(struct nd_region * nd_region, u8 * uuid, u64 cookie, u16 pos)
```

```json
{
  "name": "has_uuid_at_pos",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586239264,
      "name": "has_uuid_at_pos",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1791",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586239264,
      "name": "has_uuid_at_pos",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 516
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
bool has_uuid_at_pos(struct nd_region * nd_region, u8 * uuid, u64 cookie, u16 pos)
```

```json
{
  "name": "has_uuid_at_pos",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586057632,
      "name": "has_uuid_at_pos",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1791",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586057632,
      "name": "has_uuid_at_pos",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 516
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
bool has_uuid_at_pos(struct nd_region * nd_region, u8 * uuid, u64 cookie, u16 pos)
```

```json
{
  "name": "has_uuid_at_pos",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586496752,
      "name": "has_uuid_at_pos",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1791",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586496752,
      "name": "has_uuid_at_pos",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 516
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
bool has_uuid_at_pos(struct nd_region * nd_region, u8 * uuid, u64 cookie, u16 pos)
```

```json
{
  "name": "has_uuid_at_pos",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586608496,
      "name": "has_uuid_at_pos",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1791",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586608496,
      "name": "has_uuid_at_pos",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 516
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
bool has_uuid_at_pos(struct nd_region * nd_region, u8 * uuid, u64 cookie, u16 pos)
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>u8 * uuid</code> ➡️ <code>const uuid_t * uuid</code>
</li>
</ul>
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
bool has_uuid_at_pos(struct nd_region * nd_region, u8 * uuid, u64 cookie, u16 pos)
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
