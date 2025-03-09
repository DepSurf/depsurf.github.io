# Function: <code>free_area_init_node</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void free_area_init_node(int nid, long unsigned int * zones_size, long unsigned int node_start_pfn, long unsigned int * zholes_size)
```

```json
{
  "name": "free_area_init_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587353403,
      "name": "free_area_init_node",
      "external": true,
      "loc": "mm/page_alloc.c:5314",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:free_area_init",
        "mm/memory_hotplug.c:hotadd_new_pgdat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587353403,
      "name": "free_area_init_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1186
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
void free_area_init_node(int nid, long unsigned int * zones_size, long unsigned int node_start_pfn, long unsigned int * zholes_size)
```

```json
{
  "name": "free_area_init_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587853757,
      "name": "free_area_init_node",
      "external": true,
      "loc": "mm/page_alloc.c:5900",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:free_area_init",
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/memory_hotplug.c:hotadd_new_pgdat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587853757,
      "name": "free_area_init_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1424
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
void free_area_init_node(int nid, long unsigned int * zones_size, long unsigned int node_start_pfn, long unsigned int * zholes_size)
```

```json
{
  "name": "free_area_init_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588068537,
      "name": "free_area_init_node",
      "external": true,
      "loc": "mm/page_alloc.c:5939",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/numa.c:init_cpu_to_node",
        "mm/page_alloc.c:free_area_init",
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/memory_hotplug.c:hotadd_new_pgdat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588068537,
      "name": "free_area_init_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1328
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
void free_area_init_node(int nid, long unsigned int * zones_size, long unsigned int node_start_pfn, long unsigned int * zholes_size)
```

```json
{
  "name": "free_area_init_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588295229,
      "name": "free_area_init_node",
      "external": true,
      "loc": "mm/page_alloc.c:6236",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/numa.c:init_cpu_to_node",
        "mm/page_alloc.c:free_area_init",
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/memory_hotplug.c:hotadd_new_pgdat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588295229,
      "name": "free_area_init_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1316
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
void free_area_init_node(int nid, long unsigned int * zones_size, long unsigned int node_start_pfn, long unsigned int * zholes_size)
```

```json
{
  "name": "free_area_init_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588860237,
      "name": "free_area_init_node",
      "external": true,
      "loc": "mm/page_alloc.c:6213",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/numa.c:init_cpu_to_node",
        "mm/page_alloc.c:free_area_init",
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/memory_hotplug.c:hotadd_new_pgdat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588860237,
      "name": "free_area_init_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1316
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
void free_area_init_node(int nid, long unsigned int * zones_size, long unsigned int node_start_pfn, long unsigned int * zholes_size)
```

```json
{
  "name": "free_area_init_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589239317,
      "name": "free_area_init_node",
      "external": true,
      "loc": "mm/page_alloc.c:6348",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/numa.c:init_cpu_to_node",
        "mm/page_alloc.c:free_area_init",
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/memory_hotplug.c:hotadd_new_pgdat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589239317,
      "name": "free_area_init_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1308
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
void free_area_init_node(int nid, long unsigned int * zones_size, long unsigned int node_start_pfn, long unsigned int * zholes_size)
```

```json
{
  "name": "free_area_init_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604768926,
      "name": "free_area_init_node",
      "external": true,
      "loc": "mm/page_alloc.c:6643",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/numa.c:init_cpu_to_node",
        "mm/page_alloc.c:free_area_init",
        "mm/page_alloc.c:free_area_init_nodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604768926,
      "name": "free_area_init_node",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 1091
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
void free_area_init_node(int nid, long unsigned int * zones_size, long unsigned int node_start_pfn, long unsigned int * zholes_size)
```

```json
{
  "name": "free_area_init_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604887916,
      "name": "free_area_init_node",
      "external": true,
      "loc": "mm/page_alloc.c:6839",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/numa.c:init_cpu_to_node",
        "mm/page_alloc.c:free_area_init",
        "mm/page_alloc.c:free_area_init_nodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604887916,
      "name": "free_area_init_node",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 1132
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
void free_area_init_node(int nid, long unsigned int * zones_size, long unsigned int node_start_pfn, long unsigned int * zholes_size)
```

```json
{
  "name": "free_area_init_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604921824,
      "name": "free_area_init_node",
      "external": true,
      "loc": "mm/page_alloc.c:6859",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/numa.c:init_cpu_to_node",
        "mm/page_alloc.c:free_area_init",
        "mm/page_alloc.c:free_area_init_nodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604921824,
      "name": "free_area_init_node",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 1147
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
void free_area_init_node(int nid)
```

```json
{
  "name": "free_area_init_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609237065,
      "name": "free_area_init_node",
      "external": false,
      "loc": "mm/page_alloc.c:6884",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:free_area_init",
        "mm/page_alloc.c:free_area_init_memoryless_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609237065,
      "name": "free_area_init_node",
      "section": ".init.text",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void free_area_init_node(int nid)
```

```json
{
  "name": "free_area_init_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612303465,
      "name": "free_area_init_node",
      "external": false,
      "loc": "mm/page_alloc.c:7114",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:free_area_init",
        "mm/page_alloc.c:free_area_init_memoryless_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612303465,
      "name": "free_area_init_node",
      "section": ".init.text",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void free_area_init_node(int nid)
```

```json
{
  "name": "free_area_init_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614442927,
      "name": "free_area_init_node",
      "external": false,
      "loc": "mm/page_alloc.c:7330",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:free_area_init",
        "mm/page_alloc.c:free_area_init_memoryless_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614442927,
      "name": "free_area_init_node",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 1091
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
void free_area_init_node(int nid)
```

```json
{
  "name": "free_area_init_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615385296,
      "name": "free_area_init_node",
      "external": false,
      "loc": "mm/page_alloc.c:7572",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:free_area_init",
        "mm/page_alloc.c:free_area_init_memoryless_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615385296,
      "name": "free_area_init_node",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 1043
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
void free_area_init_node(int nid)
```

```json
{
  "name": "free_area_init_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071617174841,
      "name": "free_area_init_node",
      "external": false,
      "loc": "mm/page_alloc.c:7718",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:free_area_init",
        "mm/page_alloc.c:free_area_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071617174841,
      "name": "free_area_init_node",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 1206
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
void free_area_init_node(int nid)
```

```json
{
  "name": "free_area_init_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071627865968,
      "name": "free_area_init_node",
      "external": false,
      "loc": "mm/page_alloc.c:7903",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:free_area_init",
        "mm/page_alloc.c:free_area_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071627865968,
      "name": "free_area_init_node",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 790
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
void free_area_init_node(int nid)
```

```json
{
  "name": "free_area_init_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071619616784,
      "name": "free_area_init_node",
      "external": false,
      "loc": "mm/mm_init.c:1705",
      "file": "mm/mm_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mm_init.c:free_area_init",
        "mm/mm_init.c:free_area_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619616784,
      "name": "free_area_init_node",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 421
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
void free_area_init_node(int nid)
```

```json
{
  "name": "free_area_init_node",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071621921056,
      "name": "free_area_init_node",
      "external": false,
      "loc": "mm/mm_init.c:1703",
      "file": "mm/mm_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mm_init.c:free_area_init",
        "mm/mm_init.c:free_area_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071621921056,
      "name": "free_area_init_node",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 421
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
void free_area_init_node(int nid, long unsigned int * zones_size, long unsigned int node_start_pfn, long unsigned int * zholes_size)
```

```json
{
  "name": "free_area_init_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336510960420,
      "name": "free_area_init_node",
      "external": true,
      "loc": "mm/page_alloc.c:6859",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:free_area_init",
        "mm/page_alloc.c:free_area_init_nodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336510960420,
      "name": "free_area_init_node",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 1088
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void free_area_init_node(int nid, long unsigned int * zones_size, long unsigned int node_start_pfn, long unsigned int * zholes_size)
```

```json
{
  "name": "free_area_init_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3243448652,
      "name": "free_area_init_node",
      "external": true,
      "loc": "mm/page_alloc.c:6859",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/mm/init.c:bootmem_init",
        "mm/page_alloc.c:free_area_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3243448652,
      "name": "free_area_init_node",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 812
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void free_area_init_node(int nid, long unsigned int * zones_size, long unsigned int node_start_pfn, long unsigned int * zholes_size)
```

```json
{
  "name": "free_area_init_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055302613080,
      "name": "free_area_init_node",
      "external": true,
      "loc": "mm/page_alloc.c:6859",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:free_area_init",
        "mm/page_alloc.c:free_area_init_nodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055302613080,
      "name": "free_area_init_node",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 1376
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
void free_area_init_node(int nid, long unsigned int * zones_size, long unsigned int node_start_pfn, long unsigned int * zholes_size)
```

```json
{
  "name": "free_area_init_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936270687690,
      "name": "free_area_init_node",
      "external": true,
      "loc": "mm/page_alloc.c:6859",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:free_area_init",
        "mm/page_alloc.c:free_area_init_nodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936270687690,
      "name": "free_area_init_node",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 1152
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
void free_area_init_node(int nid, long unsigned int * zones_size, long unsigned int node_start_pfn, long unsigned int * zholes_size)
```

```json
{
  "name": "free_area_init_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604827284,
      "name": "free_area_init_node",
      "external": true,
      "loc": "mm/page_alloc.c:6859",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/numa.c:init_cpu_to_node",
        "mm/page_alloc.c:free_area_init",
        "mm/page_alloc.c:free_area_init_nodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604827284,
      "name": "free_area_init_node",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 1147
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
void free_area_init_node(int nid, long unsigned int * zones_size, long unsigned int node_start_pfn, long unsigned int * zholes_size)
```

```json
{
  "name": "free_area_init_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604796345,
      "name": "free_area_init_node",
      "external": true,
      "loc": "mm/page_alloc.c:6859",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/numa.c:init_cpu_to_node",
        "mm/page_alloc.c:free_area_init",
        "mm/page_alloc.c:free_area_init_nodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604796345,
      "name": "free_area_init_node",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 1147
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
void free_area_init_node(int nid, long unsigned int * zones_size, long unsigned int node_start_pfn, long unsigned int * zholes_size)
```

```json
{
  "name": "free_area_init_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604904468,
      "name": "free_area_init_node",
      "external": true,
      "loc": "mm/page_alloc.c:6859",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/numa.c:init_cpu_to_node",
        "mm/page_alloc.c:free_area_init",
        "mm/page_alloc.c:free_area_init_nodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604904468,
      "name": "free_area_init_node",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 1147
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
void free_area_init_node(int nid, long unsigned int * zones_size, long unsigned int node_start_pfn, long unsigned int * zholes_size)
```

```json
{
  "name": "free_area_init_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604926005,
      "name": "free_area_init_node",
      "external": true,
      "loc": "mm/page_alloc.c:6859",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/numa.c:init_cpu_to_node",
        "mm/page_alloc.c:free_area_init",
        "mm/page_alloc.c:free_area_init_nodes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604926005,
      "name": "free_area_init_node",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 1147
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
<b>Param removed. </b>
<code>long unsigned int * zones_size</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int node_start_pfn</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int * zholes_size</code>
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
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
