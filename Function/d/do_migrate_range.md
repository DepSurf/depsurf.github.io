# Function: <code>do_migrate_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_migrate_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587341560,
      "name": "do_migrate_range",
      "external": false,
      "loc": "mm/memory_hotplug.c:1435",
      "file": "mm/memory_hotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "do_migrate_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587839917,
      "name": "do_migrate_range",
      "external": false,
      "loc": "mm/memory_hotplug.c:1588",
      "file": "mm/memory_hotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "do_migrate_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588054701,
      "name": "do_migrate_range",
      "external": false,
      "loc": "mm/memory_hotplug.c:1593",
      "file": "mm/memory_hotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "do_migrate_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588281116,
      "name": "do_migrate_range",
      "external": false,
      "loc": "mm/memory_hotplug.c:1391",
      "file": "mm/memory_hotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "do_migrate_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588847047,
      "name": "do_migrate_range",
      "external": false,
      "loc": "mm/memory_hotplug.c:1379",
      "file": "mm/memory_hotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:__offline_pages"
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
  "name": "do_migrate_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589225780,
      "name": "do_migrate_range",
      "external": false,
      "loc": "mm/memory_hotplug.c:1388",
      "file": "mm/memory_hotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:__offline_pages"
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
  "name": "do_migrate_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589468565,
      "name": "do_migrate_range",
      "external": false,
      "loc": "mm/memory_hotplug.c:1367",
      "file": "mm/memory_hotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:__offline_pages"
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
int do_migrate_range(long unsigned int start_pfn, long unsigned int end_pfn)
```

```json
{
  "name": "do_migrate_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_migrate_range",
      "external": false,
      "loc": "mm/memory_hotplug.c:1349",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:__offline_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581582096,
      "name": "do_migrate_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 815
    },
    {
      "addr": 18446744071581586561,
      "name": "do_migrate_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
int do_migrate_range(long unsigned int start_pfn, long unsigned int end_pfn)
```

```json
{
  "name": "do_migrate_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_migrate_range",
      "external": false,
      "loc": "mm/memory_hotplug.c:1324",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:__offline_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581646192,
      "name": "do_migrate_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 829
    },
    {
      "addr": 18446744071581649942,
      "name": "do_migrate_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
  "name": "do_migrate_range",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "do_migrate_range",
      "external": false,
      "loc": "mm/memory_hotplug.c:1294",
      "file": "mm/memory_hotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:__offline_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581864368,
      "name": "do_migrate_range.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 880
    },
    {
      "addr": 18446744071581867046,
      "name": "do_migrate_range.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
  "name": "do_migrate_range",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "do_migrate_range",
      "external": false,
      "loc": "mm/memory_hotplug.c:1288",
      "file": "mm/memory_hotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:offline_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581908848,
      "name": "do_migrate_range.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1277
    },
    {
      "addr": 18446744071591336456,
      "name": "do_migrate_range.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
  "name": "do_migrate_range",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "do_migrate_range",
      "external": false,
      "loc": "mm/memory_hotplug.c:1531",
      "file": "mm/memory_hotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:offline_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581755616,
      "name": "do_migrate_range.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1071
    },
    {
      "addr": 18446744071591273669,
      "name": "do_migrate_range.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
  "name": "do_migrate_range",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "do_migrate_range",
      "external": false,
      "loc": "mm/memory_hotplug.c:1690",
      "file": "mm/memory_hotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:offline_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582036832,
      "name": "do_migrate_range.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1182
    },
    {
      "addr": 18446744071592208000,
      "name": "do_migrate_range.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
  "name": "do_migrate_range",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "do_migrate_range",
      "external": false,
      "loc": "mm/memory_hotplug.c:1626",
      "file": "mm/memory_hotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:offline_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582465552,
      "name": "do_migrate_range.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1817
    },
    {
      "addr": 18446744071593985651,
      "name": "do_migrate_range.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
  "name": "do_migrate_range",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582980288,
      "name": "do_migrate_range",
      "external": false,
      "loc": "mm/memory_hotplug.c:1624",
      "file": "mm/memory_hotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:offline_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582980288,
      "name": "do_migrate_range.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1934
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
void do_migrate_range(long unsigned int start_pfn, long unsigned int end_pfn)
```

```json
{
  "name": "do_migrate_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583192064,
      "name": "do_migrate_range",
      "external": false,
      "loc": "mm/memory_hotplug.c:1598",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:offline_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583192064,
      "name": "do_migrate_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1807
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
void do_migrate_range(long unsigned int start_pfn, long unsigned int end_pfn)
```

```json
{
  "name": "do_migrate_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583376960,
      "name": "do_migrate_range",
      "external": false,
      "loc": "mm/memory_hotplug.c:1780",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:offline_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583376960,
      "name": "do_migrate_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1808
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
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int do_migrate_range(long unsigned int start_pfn, long unsigned int end_pfn)
```

```json
{
  "name": "do_migrate_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286546528,
      "name": "do_migrate_range",
      "external": false,
      "loc": "mm/memory_hotplug.c:1324",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:__offline_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286546528,
      "name": "do_migrate_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1456
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int do_migrate_range(long unsigned int start_pfn, long unsigned int end_pfn)
```

```json
{
  "name": "do_migrate_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_migrate_range",
      "external": false,
      "loc": "mm/memory_hotplug.c:1324",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:__offline_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581614928,
      "name": "do_migrate_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 829
    },
    {
      "addr": 18446744071581618678,
      "name": "do_migrate_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
int do_migrate_range(long unsigned int start_pfn, long unsigned int end_pfn)
```

```json
{
  "name": "do_migrate_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_migrate_range",
      "external": false,
      "loc": "mm/memory_hotplug.c:1324",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:__offline_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581556256,
      "name": "do_migrate_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 829
    },
    {
      "addr": 18446744071581560006,
      "name": "do_migrate_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
int do_migrate_range(long unsigned int start_pfn, long unsigned int end_pfn)
```

```json
{
  "name": "do_migrate_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_migrate_range",
      "external": false,
      "loc": "mm/memory_hotplug.c:1324",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:__offline_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581606240,
      "name": "do_migrate_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 829
    },
    {
      "addr": 18446744071581609990,
      "name": "do_migrate_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
int do_migrate_range(long unsigned int start_pfn, long unsigned int end_pfn)
```

```json
{
  "name": "do_migrate_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_migrate_range",
      "external": false,
      "loc": "mm/memory_hotplug.c:1324",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:__offline_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581672640,
      "name": "do_migrate_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 829
    },
    {
      "addr": 18446744071581676182,
      "name": "do_migrate_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int do_migrate_range(long unsigned int start_pfn, long unsigned int end_pfn)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int do_migrate_range(long unsigned int start_pfn, long unsigned int end_pfn)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
void do_migrate_range(long unsigned int start_pfn, long unsigned int end_pfn)
```
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int do_migrate_range(long unsigned int start_pfn, long unsigned int end_pfn)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int do_migrate_range(long unsigned int start_pfn, long unsigned int end_pfn)
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
int do_migrate_range(long unsigned int start_pfn, long unsigned int end_pfn)
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
