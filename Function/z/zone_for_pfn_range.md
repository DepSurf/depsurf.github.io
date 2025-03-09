# Function: <code>zone_for_pfn_range</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct zone * zone_for_pfn_range(int online_type, int nid, unsigned int start_pfn, long unsigned int nr_pages)
```

```json
{
  "name": "zone_for_pfn_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581239392,
      "name": "zone_for_pfn_range",
      "external": true,
      "loc": "mm/memory_hotplug.c:894",
      "file": "mm/memory_hotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:online_pages",
        "drivers/base/memory.c:show_valid_zones",
        "drivers/base/memory.c:print_allowed_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581239392,
      "name": "zone_for_pfn_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 335
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct zone * zone_for_pfn_range(int online_type, int nid, unsigned int start_pfn, long unsigned int nr_pages)
```

```json
{
  "name": "zone_for_pfn_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581385360,
      "name": "zone_for_pfn_range",
      "external": true,
      "loc": "mm/memory_hotplug.c:871",
      "file": "mm/memory_hotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:online_pages",
        "drivers/base/memory.c:show_valid_zones",
        "drivers/base/memory.c:print_allowed_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581385360,
      "name": "zone_for_pfn_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 324
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct zone * zone_for_pfn_range(int online_type, int nid, unsigned int start_pfn, long unsigned int nr_pages)
```

```json
{
  "name": "zone_for_pfn_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581469488,
      "name": "zone_for_pfn_range",
      "external": true,
      "loc": "mm/memory_hotplug.c:829",
      "file": "mm/memory_hotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:online_pages",
        "drivers/base/memory.c:valid_zones_show",
        "drivers/base/memory.c:print_allowed_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581469488,
      "name": "zone_for_pfn_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 324
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct zone * zone_for_pfn_range(int online_type, int nid, unsigned int start_pfn, long unsigned int nr_pages)
```

```json
{
  "name": "zone_for_pfn_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581585216,
      "name": "zone_for_pfn_range",
      "external": true,
      "loc": "mm/memory_hotplug.c:808",
      "file": "mm/memory_hotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:online_pages",
        "drivers/base/memory.c:valid_zones_show",
        "drivers/base/memory.c:print_allowed_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581585216,
      "name": "zone_for_pfn_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 335
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct zone * zone_for_pfn_range(int online_type, int nid, unsigned int start_pfn, long unsigned int nr_pages)
```

```json
{
  "name": "zone_for_pfn_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581648656,
      "name": "zone_for_pfn_range",
      "external": true,
      "loc": "mm/memory_hotplug.c:791",
      "file": "mm/memory_hotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:online_pages",
        "drivers/base/memory.c:valid_zones_show",
        "drivers/base/memory.c:print_allowed_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581648656,
      "name": "zone_for_pfn_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 335
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
struct zone * zone_for_pfn_range(int online_type, int nid, unsigned int start_pfn, long unsigned int nr_pages)
```

```json
{
  "name": "zone_for_pfn_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581865872,
      "name": "zone_for_pfn_range",
      "external": true,
      "loc": "mm/memory_hotplug.c:785",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:online_pages",
        "drivers/base/memory.c:valid_zones_show",
        "drivers/base/memory.c:print_allowed_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581865872,
      "name": "zone_for_pfn_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 346
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
struct zone * zone_for_pfn_range(int online_type, int nid, unsigned int start_pfn, long unsigned int nr_pages)
```

```json
{
  "name": "zone_for_pfn_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581910752,
      "name": "zone_for_pfn_range",
      "external": true,
      "loc": "mm/memory_hotplug.c:780",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:online_pages",
        "drivers/base/memory.c:valid_zones_show",
        "drivers/base/memory.c:valid_zones_show",
        "drivers/base/memory.c:valid_zones_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581910752,
      "name": "zone_for_pfn_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 343
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
struct zone * zone_for_pfn_range(int online_type, int nid, unsigned int start_pfn, long unsigned int nr_pages)
```

```json
{
  "name": "zone_for_pfn_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581757312,
      "name": "zone_for_pfn_range",
      "external": true,
      "loc": "mm/memory_hotplug.c:850",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/memory.c:valid_zones_show",
        "drivers/base/memory.c:valid_zones_show",
        "drivers/base/memory.c:valid_zones_show",
        "drivers/base/memory.c:memory_block_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581757312,
      "name": "zone_for_pfn_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 335
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
struct zone * zone_for_pfn_range(int online_type, int nid, struct memory_group * group, long unsigned int start_pfn, long unsigned int nr_pages)
```

```json
{
  "name": "zone_for_pfn_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "zone_for_pfn_range",
      "external": true,
      "loc": "mm/memory_hotplug.c:990",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/memory.c:valid_zones_show",
        "drivers/base/memory.c:valid_zones_show",
        "drivers/base/memory.c:valid_zones_show",
        "drivers/base/memory.c:memory_block_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592208084,
      "name": "zone_for_pfn_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
    },
    {
      "addr": 18446744071582038448,
      "name": "zone_for_pfn_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 923
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
struct zone * zone_for_pfn_range(int online_type, int nid, struct memory_group * group, long unsigned int start_pfn, long unsigned int nr_pages)
```

```json
{
  "name": "zone_for_pfn_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "zone_for_pfn_range",
      "external": true,
      "loc": "mm/memory_hotplug.c:989",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/memory.c:valid_zones_show",
        "drivers/base/memory.c:valid_zones_show",
        "drivers/base/memory.c:valid_zones_show",
        "drivers/base/memory.c:memory_block_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593985777,
      "name": "zone_for_pfn_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    },
    {
      "addr": 18446744071582468544,
      "name": "zone_for_pfn_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 753
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
struct zone * zone_for_pfn_range(int online_type, int nid, struct memory_group * group, long unsigned int start_pfn, long unsigned int nr_pages)
```

```json
{
  "name": "zone_for_pfn_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "zone_for_pfn_range",
      "external": true,
      "loc": "mm/memory_hotplug.c:985",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/memory.c:valid_zones_show",
        "drivers/base/memory.c:valid_zones_show",
        "drivers/base/memory.c:valid_zones_show",
        "drivers/base/memory.c:memory_block_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596038015,
      "name": "zone_for_pfn_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    },
    {
      "addr": 18446744071582982912,
      "name": "zone_for_pfn_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 753
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
struct zone * zone_for_pfn_range(int online_type, int nid, struct memory_group * group, long unsigned int start_pfn, long unsigned int nr_pages)
```

```json
{
  "name": "zone_for_pfn_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "zone_for_pfn_range",
      "external": true,
      "loc": "mm/memory_hotplug.c:979",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/memory.c:valid_zones_show",
        "drivers/base/memory.c:valid_zones_show",
        "drivers/base/memory.c:valid_zones_show",
        "drivers/base/memory.c:memory_block_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596560240,
      "name": "zone_for_pfn_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    },
    {
      "addr": 18446744071583194432,
      "name": "zone_for_pfn_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 753
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
struct zone * zone_for_pfn_range(int online_type, int nid, struct memory_group * group, long unsigned int start_pfn, long unsigned int nr_pages)
```

```json
{
  "name": "zone_for_pfn_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "zone_for_pfn_range",
      "external": true,
      "loc": "mm/memory_hotplug.c:1048",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/memory.c:valid_zones_show",
        "drivers/base/memory.c:valid_zones_show",
        "drivers/base/memory.c:valid_zones_show",
        "drivers/base/memory.c:memory_block_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597464688,
      "name": "zone_for_pfn_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    },
    {
      "addr": 18446744071583379328,
      "name": "zone_for_pfn_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 753
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
struct zone * zone_for_pfn_range(int online_type, int nid, unsigned int start_pfn, long unsigned int nr_pages)
```

```json
{
  "name": "zone_for_pfn_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493097728,
      "name": "zone_for_pfn_range",
      "external": true,
      "loc": "mm/memory_hotplug.c:791",
      "file": "mm/memory_hotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:online_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493097728,
      "name": "zone_for_pfn_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 476
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
struct zone * zone_for_pfn_range(int online_type, int nid, unsigned int start_pfn, long unsigned int nr_pages)
```

```json
{
  "name": "zone_for_pfn_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055286549168,
      "name": "zone_for_pfn_range",
      "external": true,
      "loc": "mm/memory_hotplug.c:791",
      "file": "mm/memory_hotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:online_pages",
        "drivers/base/memory.c:valid_zones_show",
        "drivers/base/memory.c:print_allowed_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286549168,
      "name": "zone_for_pfn_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
struct zone * zone_for_pfn_range(int online_type, int nid, unsigned int start_pfn, long unsigned int nr_pages)
```

```json
{
  "name": "zone_for_pfn_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581617392,
      "name": "zone_for_pfn_range",
      "external": true,
      "loc": "mm/memory_hotplug.c:791",
      "file": "mm/memory_hotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:online_pages",
        "drivers/base/memory.c:valid_zones_show",
        "drivers/base/memory.c:print_allowed_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581617392,
      "name": "zone_for_pfn_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 335
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
struct zone * zone_for_pfn_range(int online_type, int nid, unsigned int start_pfn, long unsigned int nr_pages)
```

```json
{
  "name": "zone_for_pfn_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581558720,
      "name": "zone_for_pfn_range",
      "external": true,
      "loc": "mm/memory_hotplug.c:791",
      "file": "mm/memory_hotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:online_pages",
        "drivers/base/memory.c:valid_zones_show",
        "drivers/base/memory.c:print_allowed_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581558720,
      "name": "zone_for_pfn_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 335
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
struct zone * zone_for_pfn_range(int online_type, int nid, unsigned int start_pfn, long unsigned int nr_pages)
```

```json
{
  "name": "zone_for_pfn_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581608704,
      "name": "zone_for_pfn_range",
      "external": true,
      "loc": "mm/memory_hotplug.c:791",
      "file": "mm/memory_hotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:online_pages",
        "drivers/base/memory.c:valid_zones_show",
        "drivers/base/memory.c:print_allowed_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581608704,
      "name": "zone_for_pfn_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 335
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
struct zone * zone_for_pfn_range(int online_type, int nid, unsigned int start_pfn, long unsigned int nr_pages)
```

```json
{
  "name": "zone_for_pfn_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581674896,
      "name": "zone_for_pfn_range",
      "external": true,
      "loc": "mm/memory_hotplug.c:791",
      "file": "mm/memory_hotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:online_pages",
        "drivers/base/memory.c:valid_zones_show",
        "drivers/base/memory.c:print_allowed_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581674896,
      "name": "zone_for_pfn_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 335
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
struct zone * zone_for_pfn_range(int online_type, int nid, unsigned int start_pfn, long unsigned int nr_pages)
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
<code>struct memory_group * group</code>
</li>
<li>
<b>Param reordered. </b>
<code>online_type, nid, start_pfn, nr_pages</code> ➡️ <code>online_type, nid, group, start_pfn, nr_pages</code>
</li>
<li>
<b>Param type changed. </b>
<code>unsigned int start_pfn</code> ➡️ <code>long unsigned int start_pfn</code>
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
struct zone * zone_for_pfn_range(int online_type, int nid, unsigned int start_pfn, long unsigned int nr_pages)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct zone * zone_for_pfn_range(int online_type, int nid, unsigned int start_pfn, long unsigned int nr_pages)
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
