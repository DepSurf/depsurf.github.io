# Function: <code>zone_pcp_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "zone_pcp_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587354326,
      "name": "zone_pcp_init",
      "external": false,
      "loc": "mm/page_alloc.c:4732",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:free_area_init_node"
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
  "name": "zone_pcp_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587854797,
      "name": "zone_pcp_init",
      "external": false,
      "loc": "mm/page_alloc.c:5273",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:free_area_init_node"
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
  "name": "zone_pcp_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588069664,
      "name": "zone_pcp_init",
      "external": false,
      "loc": "mm/page_alloc.c:5313",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:free_area_init_node"
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
  "name": "zone_pcp_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588296176,
      "name": "zone_pcp_init",
      "external": false,
      "loc": "mm/page_alloc.c:5612",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:free_area_init_node"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "zone_pcp_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588861184,
      "name": "zone_pcp_init",
      "external": false,
      "loc": "mm/page_alloc.c:5584",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:free_area_init_node"
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
  "name": "zone_pcp_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589240468,
      "name": "zone_pcp_init",
      "external": false,
      "loc": "mm/page_alloc.c:5722",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:free_area_init_node"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void zone_pcp_init(struct zone * zone)
```

```json
{
  "name": "zone_pcp_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589482002,
      "name": "zone_pcp_init",
      "external": false,
      "loc": "mm/page_alloc.c:5966",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:free_area_init_node",
        "mm/page_alloc.c:free_area_init_core_hotplug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589482002,
      "name": "zone_pcp_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
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
void zone_pcp_init(struct zone * zone)
```

```json
{
  "name": "zone_pcp_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589941833,
      "name": "zone_pcp_init",
      "external": false,
      "loc": "mm/page_alloc.c:6152",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:free_area_init_node",
        "mm/page_alloc.c:free_area_init_core_hotplug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589941833,
      "name": "zone_pcp_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
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
void zone_pcp_init(struct zone * zone)
```

```json
{
  "name": "zone_pcp_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590169388,
      "name": "zone_pcp_init",
      "external": false,
      "loc": "mm/page_alloc.c:6170",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:free_area_init_node",
        "mm/page_alloc.c:free_area_init_core_hotplug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590169388,
      "name": "zone_pcp_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
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
void zone_pcp_init(struct zone * zone)
```

```json
{
  "name": "zone_pcp_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591187600,
      "name": "zone_pcp_init",
      "external": false,
      "loc": "mm/page_alloc.c:6282",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:free_area_init_core",
        "mm/page_alloc.c:free_area_init_core_hotplug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591187600,
      "name": "zone_pcp_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
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
void zone_pcp_init(struct zone * zone)
```

```json
{
  "name": "zone_pcp_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591682838,
      "name": "zone_pcp_init",
      "external": false,
      "loc": "mm/page_alloc.c:6527",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:free_area_init_core",
        "mm/page_alloc.c:free_area_init_core_hotplug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591682838,
      "name": "zone_pcp_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
void zone_pcp_init(struct zone * zone)
```

```json
{
  "name": "zone_pcp_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591626274,
      "name": "zone_pcp_init",
      "external": false,
      "loc": "mm/page_alloc.c:6748",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:free_area_init_node",
        "mm/page_alloc.c:free_area_init_core_hotplug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591626274,
      "name": "zone_pcp_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
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
  "name": "zone_pcp_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592799845,
      "name": "zone_pcp_init",
      "external": false,
      "loc": "mm/page_alloc.c:6990",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:zone_init_internals"
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
  "name": "zone_pcp_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594700059,
      "name": "zone_pcp_init",
      "external": false,
      "loc": "mm/page_alloc.c:7111",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:zone_init_internals"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void zone_pcp_init(struct zone * zone)
```

```json
{
  "name": "zone_pcp_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596440640,
      "name": "zone_pcp_init",
      "external": false,
      "loc": "mm/page_alloc.c:7295",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:free_area_init_core",
        "mm/page_alloc.c:free_area_init_core_hotplug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596440640,
      "name": "zone_pcp_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
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
void zone_pcp_init(struct zone * zone)
```

```json
{
  "name": "zone_pcp_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596984000,
      "name": "zone_pcp_init",
      "external": true,
      "loc": "mm/page_alloc.c:5501",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mm_init.c:free_area_init_core",
        "mm/mm_init.c:free_area_init_core_hotplug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596984000,
      "name": "zone_pcp_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 246
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
void zone_pcp_init(struct zone * zone)
```

```json
{
  "name": "zone_pcp_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597912640,
      "name": "zone_pcp_init",
      "external": true,
      "loc": "mm/page_alloc.c:5642",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mm_init.c:free_area_init_core",
        "mm/mm_init.c:free_area_init_core_hotplug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597912640,
      "name": "zone_pcp_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
void zone_pcp_init(struct zone * zone)
```

```json
{
  "name": "zone_pcp_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503917180,
      "name": "zone_pcp_init",
      "external": false,
      "loc": "mm/page_alloc.c:6170",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:free_area_init_node",
        "mm/page_alloc.c:free_area_init_core_hotplug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503917180,
      "name": "zone_pcp_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
  "name": "zone_pcp_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3243449316,
      "name": "zone_pcp_init",
      "external": false,
      "loc": "mm/page_alloc.c:6170",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:free_area_init_node"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "zone_pcp_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055297811536,
      "name": "zone_pcp_init",
      "external": false,
      "loc": "mm/page_alloc.c:6170",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:zone_init_internals"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "zone_pcp_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936270688676,
      "name": "zone_pcp_init",
      "external": false,
      "loc": "mm/page_alloc.c:6170",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:free_area_init_node"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void zone_pcp_init(struct zone * zone)
```

```json
{
  "name": "zone_pcp_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589771676,
      "name": "zone_pcp_init",
      "external": false,
      "loc": "mm/page_alloc.c:6170",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:free_area_init_node",
        "mm/page_alloc.c:free_area_init_core_hotplug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589771676,
      "name": "zone_pcp_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
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
void zone_pcp_init(struct zone * zone)
```

```json
{
  "name": "zone_pcp_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589494499,
      "name": "zone_pcp_init",
      "external": false,
      "loc": "mm/page_alloc.c:6170",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:free_area_init_node",
        "mm/page_alloc.c:free_area_init_core_hotplug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589494499,
      "name": "zone_pcp_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
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
void zone_pcp_init(struct zone * zone)
```

```json
{
  "name": "zone_pcp_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590215084,
      "name": "zone_pcp_init",
      "external": false,
      "loc": "mm/page_alloc.c:6170",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:free_area_init_node",
        "mm/page_alloc.c:free_area_init_core_hotplug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590215084,
      "name": "zone_pcp_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
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
void zone_pcp_init(struct zone * zone)
```

```json
{
  "name": "zone_pcp_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590265452,
      "name": "zone_pcp_init",
      "external": false,
      "loc": "mm/page_alloc.c:6170",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:free_area_init_node",
        "mm/page_alloc.c:free_area_init_core_hotplug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590265452,
      "name": "zone_pcp_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
void zone_pcp_init(struct zone * zone)
```
</details>
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
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
void zone_pcp_init(struct zone * zone)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
void zone_pcp_init(struct zone * zone)
```
</details>
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
void zone_pcp_init(struct zone * zone)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void zone_pcp_init(struct zone * zone)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void zone_pcp_init(struct zone * zone)
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
