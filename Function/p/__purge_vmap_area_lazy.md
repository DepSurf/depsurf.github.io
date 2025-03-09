# Function: <code>__purge_vmap_area_lazy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __purge_vmap_area_lazy(long unsigned int * start, long unsigned int * end, int sync, int force_flush)
```

```json
{
  "name": "__purge_vmap_area_lazy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580732672,
      "name": "__purge_vmap_area_lazy",
      "external": false,
      "loc": "mm/vmalloc.c:602",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:vm_unmap_aliases",
        "mm/vmalloc.c:alloc_vmap_area",
        "mm/vmalloc.c:pcpu_get_vm_areas"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580732672,
      "name": "__purge_vmap_area_lazy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 887
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
void __purge_vmap_area_lazy(long unsigned int * start, long unsigned int * end, int sync, int force_flush)
```

```json
{
  "name": "__purge_vmap_area_lazy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580851648,
      "name": "__purge_vmap_area_lazy",
      "external": false,
      "loc": "mm/vmalloc.c:626",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:pcpu_get_vm_areas",
        "mm/vmalloc.c:vm_unmap_aliases",
        "mm/vmalloc.c:alloc_vmap_area"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580851648,
      "name": "__purge_vmap_area_lazy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 776
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
bool __purge_vmap_area_lazy(long unsigned int start, long unsigned int end)
```

```json
{
  "name": "__purge_vmap_area_lazy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580921136,
      "name": "__purge_vmap_area_lazy",
      "external": false,
      "loc": "mm/vmalloc.c:626",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:free_vmap_area_noflush",
        "mm/vmalloc.c:purge_vmap_area_lazy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580921136,
      "name": "__purge_vmap_area_lazy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
bool __purge_vmap_area_lazy(long unsigned int start, long unsigned int end)
```

```json
{
  "name": "__purge_vmap_area_lazy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580965424,
      "name": "__purge_vmap_area_lazy",
      "external": false,
      "loc": "mm/vmalloc.c:677",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:free_vmap_area_noflush",
        "mm/vmalloc.c:purge_vmap_area_lazy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580965424,
      "name": "__purge_vmap_area_lazy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
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
bool __purge_vmap_area_lazy(long unsigned int start, long unsigned int end)
```

```json
{
  "name": "__purge_vmap_area_lazy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581067344,
      "name": "__purge_vmap_area_lazy",
      "external": false,
      "loc": "mm/vmalloc.c:675",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:free_vmap_area_noflush",
        "mm/vmalloc.c:purge_vmap_area_lazy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581067344,
      "name": "__purge_vmap_area_lazy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
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
bool __purge_vmap_area_lazy(long unsigned int start, long unsigned int end)
```

```json
{
  "name": "__purge_vmap_area_lazy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581210016,
      "name": "__purge_vmap_area_lazy",
      "external": false,
      "loc": "mm/vmalloc.c:655",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:free_vmap_area_noflush",
        "mm/vmalloc.c:purge_vmap_area_lazy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581210016,
      "name": "__purge_vmap_area_lazy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
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
bool __purge_vmap_area_lazy(long unsigned int start, long unsigned int end)
```

```json
{
  "name": "__purge_vmap_area_lazy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581293728,
      "name": "__purge_vmap_area_lazy",
      "external": false,
      "loc": "mm/vmalloc.c:655",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:free_vmap_area_noflush",
        "mm/vmalloc.c:purge_vmap_area_lazy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581293728,
      "name": "__purge_vmap_area_lazy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
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
bool __purge_vmap_area_lazy(long unsigned int start, long unsigned int end)
```

```json
{
  "name": "__purge_vmap_area_lazy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581371776,
      "name": "__purge_vmap_area_lazy",
      "external": false,
      "loc": "mm/vmalloc.c:1248",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:free_vmap_area_noflush",
        "mm/vmalloc.c:purge_vmap_area_lazy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581371776,
      "name": "__purge_vmap_area_lazy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 289
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
bool __purge_vmap_area_lazy(long unsigned int start, long unsigned int end)
```

```json
{
  "name": "__purge_vmap_area_lazy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581431488,
      "name": "__purge_vmap_area_lazy",
      "external": false,
      "loc": "mm/vmalloc.c:1245",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:free_vmap_area_noflush",
        "mm/vmalloc.c:purge_vmap_area_lazy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581431488,
      "name": "__purge_vmap_area_lazy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1741
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
bool __purge_vmap_area_lazy(long unsigned int start, long unsigned int end)
```

```json
{
  "name": "__purge_vmap_area_lazy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581631872,
      "name": "__purge_vmap_area_lazy",
      "external": false,
      "loc": "mm/vmalloc.c:1346",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:free_vmap_area_noflush",
        "mm/vmalloc.c:purge_vmap_area_lazy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581631872,
      "name": "__purge_vmap_area_lazy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1763
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
bool __purge_vmap_area_lazy(long unsigned int start, long unsigned int end)
```

```json
{
  "name": "__purge_vmap_area_lazy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581677504,
      "name": "__purge_vmap_area_lazy",
      "external": false,
      "loc": "mm/vmalloc.c:1337",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:free_vmap_area_noflush",
        "mm/vmalloc.c:purge_vmap_area_lazy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581677504,
      "name": "__purge_vmap_area_lazy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1761
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
bool __purge_vmap_area_lazy(long unsigned int start, long unsigned int end)
```

```json
{
  "name": "__purge_vmap_area_lazy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581699744,
      "name": "__purge_vmap_area_lazy",
      "external": false,
      "loc": "mm/vmalloc.c:1607",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:free_vmap_area_noflush",
        "mm/vmalloc.c:purge_vmap_area_lazy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581699744,
      "name": "__purge_vmap_area_lazy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1765
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
bool __purge_vmap_area_lazy(long unsigned int start, long unsigned int end)
```

```json
{
  "name": "__purge_vmap_area_lazy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581971520,
      "name": "__purge_vmap_area_lazy",
      "external": false,
      "loc": "mm/vmalloc.c:1659",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:free_vmap_area_noflush",
        "mm/vmalloc.c:purge_vmap_area_lazy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581971520,
      "name": "__purge_vmap_area_lazy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1765
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
bool __purge_vmap_area_lazy(long unsigned int start, long unsigned int end)
```

```json
{
  "name": "__purge_vmap_area_lazy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582395184,
      "name": "__purge_vmap_area_lazy",
      "external": false,
      "loc": "mm/vmalloc.c:1677",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:pcpu_get_vm_areas",
        "mm/vmalloc.c:pcpu_get_vm_areas",
        "mm/vmalloc.c:drain_vmap_area_work",
        "mm/vmalloc.c:alloc_vmap_area"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582395184,
      "name": "__purge_vmap_area_lazy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1826
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
bool __purge_vmap_area_lazy(long unsigned int start, long unsigned int end)
```

```json
{
  "name": "__purge_vmap_area_lazy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582901504,
      "name": "__purge_vmap_area_lazy",
      "external": false,
      "loc": "mm/vmalloc.c:1730",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:pcpu_get_vm_areas",
        "mm/vmalloc.c:pcpu_get_vm_areas",
        "mm/vmalloc.c:drain_vmap_area_work",
        "mm/vmalloc.c:alloc_vmap_area"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582901504,
      "name": "__purge_vmap_area_lazy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2012
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
bool __purge_vmap_area_lazy(long unsigned int start, long unsigned int end)
```

```json
{
  "name": "__purge_vmap_area_lazy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583117072,
      "name": "__purge_vmap_area_lazy",
      "external": false,
      "loc": "mm/vmalloc.c:1724",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:_vm_unmap_aliases",
        "mm/vmalloc.c:drain_vmap_area_work",
        "mm/vmalloc.c:reclaim_and_purge_vmap_areas"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583117072,
      "name": "__purge_vmap_area_lazy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1955
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
bool __purge_vmap_area_lazy(long unsigned int start, long unsigned int end)
```

```json
{
  "name": "__purge_vmap_area_lazy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583299968,
      "name": "__purge_vmap_area_lazy",
      "external": false,
      "loc": "mm/vmalloc.c:1724",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:_vm_unmap_aliases",
        "mm/vmalloc.c:drain_vmap_area_work",
        "mm/vmalloc.c:reclaim_and_purge_vmap_areas"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583299968,
      "name": "__purge_vmap_area_lazy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1955
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
bool __purge_vmap_area_lazy(long unsigned int start, long unsigned int end)
```

```json
{
  "name": "__purge_vmap_area_lazy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492833624,
      "name": "__purge_vmap_area_lazy",
      "external": false,
      "loc": "mm/vmalloc.c:1245",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:free_vmap_area_noflush",
        "mm/vmalloc.c:purge_vmap_area_lazy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492833624,
      "name": "__purge_vmap_area_lazy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1912
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
bool __purge_vmap_area_lazy(long unsigned int start, long unsigned int end)
```

```json
{
  "name": "__purge_vmap_area_lazy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226637752,
      "name": "__purge_vmap_area_lazy",
      "external": false,
      "loc": "mm/vmalloc.c:1245",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:free_vmap_area_noflush",
        "mm/vmalloc.c:purge_vmap_area_lazy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226637752,
      "name": "__purge_vmap_area_lazy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1944
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
bool __purge_vmap_area_lazy(long unsigned int start, long unsigned int end)
```

```json
{
  "name": "__purge_vmap_area_lazy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286220624,
      "name": "__purge_vmap_area_lazy",
      "external": false,
      "loc": "mm/vmalloc.c:1245",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:free_vmap_area_noflush",
        "mm/vmalloc.c:purge_vmap_area_lazy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286220624,
      "name": "__purge_vmap_area_lazy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2256
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "__purge_vmap_area_lazy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272787532,
      "name": "__purge_vmap_area_lazy",
      "external": false,
      "loc": "mm/vmalloc.c:1245",
      "file": "mm/vmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:free_vmap_area_noflush",
        "mm/vmalloc.c:purge_vmap_area_lazy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272787532,
      "name": "__purge_vmap_area_lazy.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1336
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
bool __purge_vmap_area_lazy(long unsigned int start, long unsigned int end)
```

```json
{
  "name": "__purge_vmap_area_lazy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581400336,
      "name": "__purge_vmap_area_lazy",
      "external": false,
      "loc": "mm/vmalloc.c:1245",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:free_vmap_area_noflush",
        "mm/vmalloc.c:purge_vmap_area_lazy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581400336,
      "name": "__purge_vmap_area_lazy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1741
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
bool __purge_vmap_area_lazy(long unsigned int start, long unsigned int end)
```

```json
{
  "name": "__purge_vmap_area_lazy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581342848,
      "name": "__purge_vmap_area_lazy",
      "external": false,
      "loc": "mm/vmalloc.c:1245",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:free_vmap_area_noflush",
        "mm/vmalloc.c:purge_vmap_area_lazy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581342848,
      "name": "__purge_vmap_area_lazy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1741
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
bool __purge_vmap_area_lazy(long unsigned int start, long unsigned int end)
```

```json
{
  "name": "__purge_vmap_area_lazy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581391536,
      "name": "__purge_vmap_area_lazy",
      "external": false,
      "loc": "mm/vmalloc.c:1245",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:free_vmap_area_noflush",
        "mm/vmalloc.c:purge_vmap_area_lazy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581391536,
      "name": "__purge_vmap_area_lazy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1741
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
bool __purge_vmap_area_lazy(long unsigned int start, long unsigned int end)
```

```json
{
  "name": "__purge_vmap_area_lazy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581455472,
      "name": "__purge_vmap_area_lazy",
      "external": false,
      "loc": "mm/vmalloc.c:1245",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:free_vmap_area_noflush",
        "mm/vmalloc.c:purge_vmap_area_lazy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581455472,
      "name": "__purge_vmap_area_lazy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1739
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
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int sync</code>
</li>
<li>
<b>Param removed. </b>
<code>int force_flush</code>
</li>
<li>
<b>Param type changed. </b>
<code>long unsigned int * start</code> ➡️ <code>long unsigned int start</code>
</li>
<li>
<b>Param type changed. </b>
<code>long unsigned int * end</code> ➡️ <code>long unsigned int end</code>
</li>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>bool</code>
</li>
</ul>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
bool __purge_vmap_area_lazy(long unsigned int start, long unsigned int end)
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
