# Function: <code>__earlyonly_bootmem_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__earlyonly_bootmem_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587337591,
      "name": "__earlyonly_bootmem_alloc",
      "external": false,
      "loc": "mm/sparse-vmemmap.c:38",
      "file": "mm/sparse-vmemmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse-vmemmap.c:vmemmap_alloc_block",
        "mm/sparse-vmemmap.c:sparse_mem_maps_populate_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587337591,
      "name": "__earlyonly_bootmem_alloc.constprop.1",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
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
void * __earlyonly_bootmem_alloc(int node, long unsigned int size, long unsigned int align, long unsigned int goal)
```

```json
{
  "name": "__earlyonly_bootmem_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587836099,
      "name": "__earlyonly_bootmem_alloc",
      "external": false,
      "loc": "mm/sparse-vmemmap.c:39",
      "file": "mm/sparse-vmemmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse-vmemmap.c:sparse_mem_maps_populate_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587836099,
      "name": "__earlyonly_bootmem_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
void * __earlyonly_bootmem_alloc(int node, long unsigned int size, long unsigned int align, long unsigned int goal)
```

```json
{
  "name": "__earlyonly_bootmem_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588051219,
      "name": "__earlyonly_bootmem_alloc",
      "external": false,
      "loc": "mm/sparse-vmemmap.c:39",
      "file": "mm/sparse-vmemmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse-vmemmap.c:sparse_mem_maps_populate_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588051219,
      "name": "__earlyonly_bootmem_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
void * __earlyonly_bootmem_alloc(int node, long unsigned int size, long unsigned int align, long unsigned int goal)
```

```json
{
  "name": "__earlyonly_bootmem_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588278387,
      "name": "__earlyonly_bootmem_alloc",
      "external": false,
      "loc": "mm/sparse-vmemmap.c:39",
      "file": "mm/sparse-vmemmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse-vmemmap.c:sparse_mem_maps_populate_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588278387,
      "name": "__earlyonly_bootmem_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
void * __earlyonly_bootmem_alloc(int node, long unsigned int size, long unsigned int align, long unsigned int goal)
```

```json
{
  "name": "__earlyonly_bootmem_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588844002,
      "name": "__earlyonly_bootmem_alloc",
      "external": false,
      "loc": "mm/sparse-vmemmap.c:40",
      "file": "mm/sparse-vmemmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse-vmemmap.c:sparse_mem_maps_populate_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588844002,
      "name": "__earlyonly_bootmem_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
void * __earlyonly_bootmem_alloc(int node, long unsigned int size, long unsigned int align, long unsigned int goal)
```

```json
{
  "name": "__earlyonly_bootmem_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589223231,
      "name": "__earlyonly_bootmem_alloc",
      "external": false,
      "loc": "mm/sparse-vmemmap.c:40",
      "file": "mm/sparse-vmemmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse-vmemmap.c:sparse_mem_maps_populate_node",
        "mm/sparse-vmemmap.c:vmemmap_alloc_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589223231,
      "name": "__earlyonly_bootmem_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
void * __earlyonly_bootmem_alloc(int node, long unsigned int size, long unsigned int align, long unsigned int goal)
```

```json
{
  "name": "__earlyonly_bootmem_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589465881,
      "name": "__earlyonly_bootmem_alloc",
      "external": false,
      "loc": "mm/sparse-vmemmap.c:40",
      "file": "mm/sparse-vmemmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse-vmemmap.c:vmemmap_alloc_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589465881,
      "name": "__earlyonly_bootmem_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
void * __earlyonly_bootmem_alloc(int node, long unsigned int size, long unsigned int align, long unsigned int goal)
```

```json
{
  "name": "__earlyonly_bootmem_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589926141,
      "name": "__earlyonly_bootmem_alloc",
      "external": false,
      "loc": "mm/sparse-vmemmap.c:40",
      "file": "mm/sparse-vmemmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse-vmemmap.c:vmemmap_alloc_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589926141,
      "name": "__earlyonly_bootmem_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
void * __earlyonly_bootmem_alloc(int node, long unsigned int size, long unsigned int align, long unsigned int goal)
```

```json
{
  "name": "__earlyonly_bootmem_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590152234,
      "name": "__earlyonly_bootmem_alloc",
      "external": false,
      "loc": "mm/sparse-vmemmap.c:40",
      "file": "mm/sparse-vmemmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse-vmemmap.c:vmemmap_alloc_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590152234,
      "name": "__earlyonly_bootmem_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
void * __earlyonly_bootmem_alloc(int node, long unsigned int size, long unsigned int align, long unsigned int goal)
```

```json
{
  "name": "__earlyonly_bootmem_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591170602,
      "name": "__earlyonly_bootmem_alloc",
      "external": false,
      "loc": "mm/sparse-vmemmap.c:39",
      "file": "mm/sparse-vmemmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse-vmemmap.c:vmemmap_alloc_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591170602,
      "name": "__earlyonly_bootmem_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
void * __earlyonly_bootmem_alloc(int node, long unsigned int size, long unsigned int align, long unsigned int goal)
```

```json
{
  "name": "__earlyonly_bootmem_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591666300,
      "name": "__earlyonly_bootmem_alloc",
      "external": false,
      "loc": "mm/sparse-vmemmap.c:39",
      "file": "mm/sparse-vmemmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse-vmemmap.c:vmemmap_alloc_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591666300,
      "name": "__earlyonly_bootmem_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
void * __earlyonly_bootmem_alloc(int node, long unsigned int size, long unsigned int align, long unsigned int goal)
```

```json
{
  "name": "__earlyonly_bootmem_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591615228,
      "name": "__earlyonly_bootmem_alloc",
      "external": false,
      "loc": "mm/sparse-vmemmap.c:39",
      "file": "mm/sparse-vmemmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse-vmemmap.c:vmemmap_alloc_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591615228,
      "name": "__earlyonly_bootmem_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
void * __earlyonly_bootmem_alloc(int node, long unsigned int size, long unsigned int align, long unsigned int goal)
```

```json
{
  "name": "__earlyonly_bootmem_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592788977,
      "name": "__earlyonly_bootmem_alloc",
      "external": false,
      "loc": "mm/sparse-vmemmap.c:393",
      "file": "mm/sparse-vmemmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse-vmemmap.c:vmemmap_alloc_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592788977,
      "name": "__earlyonly_bootmem_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void * __earlyonly_bootmem_alloc(int node, long unsigned int size, long unsigned int align, long unsigned int goal)
```

```json
{
  "name": "__earlyonly_bootmem_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594688278,
      "name": "__earlyonly_bootmem_alloc",
      "external": false,
      "loc": "mm/sparse-vmemmap.c:439",
      "file": "mm/sparse-vmemmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse-vmemmap.c:vmemmap_alloc_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594688278,
      "name": "__earlyonly_bootmem_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
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
void * __earlyonly_bootmem_alloc(int node, long unsigned int size, long unsigned int align, long unsigned int goal)
```

```json
{
  "name": "__earlyonly_bootmem_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596424896,
      "name": "__earlyonly_bootmem_alloc",
      "external": false,
      "loc": "mm/sparse-vmemmap.c:40",
      "file": "mm/sparse-vmemmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse-vmemmap.c:vmemmap_alloc_block",
        "mm/sparse-vmemmap.c:vmemmap_alloc_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596424896,
      "name": "__earlyonly_bootmem_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
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
void * __earlyonly_bootmem_alloc(int node, long unsigned int size, long unsigned int align, long unsigned int goal)
```

```json
{
  "name": "__earlyonly_bootmem_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596964976,
      "name": "__earlyonly_bootmem_alloc",
      "external": false,
      "loc": "mm/sparse-vmemmap.c:40",
      "file": "mm/sparse-vmemmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse-vmemmap.c:vmemmap_alloc_block",
        "mm/sparse-vmemmap.c:vmemmap_alloc_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596964976,
      "name": "__earlyonly_bootmem_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
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
void * __earlyonly_bootmem_alloc(int node, long unsigned int size, long unsigned int align, long unsigned int goal)
```

```json
{
  "name": "__earlyonly_bootmem_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597892976,
      "name": "__earlyonly_bootmem_alloc",
      "external": false,
      "loc": "mm/sparse-vmemmap.c:40",
      "file": "mm/sparse-vmemmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse-vmemmap.c:vmemmap_alloc_block",
        "mm/sparse-vmemmap.c:vmemmap_alloc_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597892976,
      "name": "__earlyonly_bootmem_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
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
void * __earlyonly_bootmem_alloc(int node, long unsigned int size, long unsigned int align, long unsigned int goal)
```

```json
{
  "name": "__earlyonly_bootmem_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503903544,
      "name": "__earlyonly_bootmem_alloc",
      "external": false,
      "loc": "mm/sparse-vmemmap.c:40",
      "file": "mm/sparse-vmemmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse-vmemmap.c:vmemmap_alloc_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503903544,
      "name": "__earlyonly_bootmem_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "__earlyonly_bootmem_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055286455908,
      "name": "__earlyonly_bootmem_alloc",
      "external": false,
      "loc": "mm/sparse-vmemmap.c:40",
      "file": "mm/sparse-vmemmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse-vmemmap.c:vmemmap_alloc_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286455908,
      "name": "__earlyonly_bootmem_alloc.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
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
void * __earlyonly_bootmem_alloc(int node, long unsigned int size, long unsigned int align, long unsigned int goal)
```

```json
{
  "name": "__earlyonly_bootmem_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279791258,
      "name": "__earlyonly_bootmem_alloc",
      "external": false,
      "loc": "mm/sparse-vmemmap.c:40",
      "file": "mm/sparse-vmemmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse-vmemmap.c:vmemmap_alloc_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279791258,
      "name": "__earlyonly_bootmem_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
void * __earlyonly_bootmem_alloc(int node, long unsigned int size, long unsigned int align, long unsigned int goal)
```

```json
{
  "name": "__earlyonly_bootmem_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589754522,
      "name": "__earlyonly_bootmem_alloc",
      "external": false,
      "loc": "mm/sparse-vmemmap.c:40",
      "file": "mm/sparse-vmemmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse-vmemmap.c:vmemmap_alloc_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589754522,
      "name": "__earlyonly_bootmem_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
void * __earlyonly_bootmem_alloc(int node, long unsigned int size, long unsigned int align, long unsigned int goal)
```

```json
{
  "name": "__earlyonly_bootmem_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589478746,
      "name": "__earlyonly_bootmem_alloc",
      "external": false,
      "loc": "mm/sparse-vmemmap.c:40",
      "file": "mm/sparse-vmemmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse-vmemmap.c:vmemmap_alloc_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589478746,
      "name": "__earlyonly_bootmem_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
void * __earlyonly_bootmem_alloc(int node, long unsigned int size, long unsigned int align, long unsigned int goal)
```

```json
{
  "name": "__earlyonly_bootmem_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590197930,
      "name": "__earlyonly_bootmem_alloc",
      "external": false,
      "loc": "mm/sparse-vmemmap.c:40",
      "file": "mm/sparse-vmemmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse-vmemmap.c:vmemmap_alloc_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590197930,
      "name": "__earlyonly_bootmem_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
void * __earlyonly_bootmem_alloc(int node, long unsigned int size, long unsigned int align, long unsigned int goal)
```

```json
{
  "name": "__earlyonly_bootmem_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590248349,
      "name": "__earlyonly_bootmem_alloc",
      "external": false,
      "loc": "mm/sparse-vmemmap.c:40",
      "file": "mm/sparse-vmemmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse-vmemmap.c:vmemmap_alloc_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590248349,
      "name": "__earlyonly_bootmem_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
void * __earlyonly_bootmem_alloc(int node, long unsigned int size, long unsigned int align, long unsigned int goal)
```
</details>
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
void * __earlyonly_bootmem_alloc(int node, long unsigned int size, long unsigned int align, long unsigned int goal)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void * __earlyonly_bootmem_alloc(int node, long unsigned int size, long unsigned int align, long unsigned int goal)
```
</details>
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
