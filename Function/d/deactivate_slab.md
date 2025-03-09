# Function: <code>deactivate_slab</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void deactivate_slab(struct kmem_cache * s, struct page * page, void * freelist)
```

```json
{
  "name": "deactivate_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580851936,
      "name": "deactivate_slab",
      "external": false,
      "loc": "mm/slub.c:1860",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:flush_cpu_slab",
        "mm/slub.c:slab_cpuup_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580851936,
      "name": "deactivate_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 988
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
void deactivate_slab(struct kmem_cache * s, struct page * page, void * freelist)
```

```json
{
  "name": "deactivate_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580980528,
      "name": "deactivate_slab",
      "external": false,
      "loc": "mm/slub.c:1989",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:slab_cpuup_callback",
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:flush_cpu_slab"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580980528,
      "name": "deactivate_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 963
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
void deactivate_slab(struct kmem_cache * s, struct page * page, void * freelist)
```

```json
{
  "name": "deactivate_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581054368,
      "name": "deactivate_slab",
      "external": false,
      "loc": "mm/slub.c:1992",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:slub_cpu_dead",
        "mm/slub.c:flush_cpu_slab"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581054368,
      "name": "deactivate_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 963
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "deactivate_slab",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581102048,
      "name": "deactivate_slab",
      "external": false,
      "loc": "mm/slub.c:1995",
      "file": "mm/slub.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:slub_cpu_dead",
        "mm/slub.c:flush_cpu_slab"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581102048,
      "name": "deactivate_slab.isra.70",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 946
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
  "name": "deactivate_slab",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581218224,
      "name": "deactivate_slab",
      "external": false,
      "loc": "mm/slub.c:2008",
      "file": "mm/slub.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:slub_cpu_dead",
        "mm/slub.c:flush_cpu_slab"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581218224,
      "name": "deactivate_slab.isra.70",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1008
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "deactivate_slab",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581357216,
      "name": "deactivate_slab",
      "external": false,
      "loc": "mm/slub.c:1991",
      "file": "mm/slub.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:slub_cpu_dead",
        "mm/slub.c:flush_cpu_slab"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581357216,
      "name": "deactivate_slab.isra.72",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1207
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "deactivate_slab",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581442512,
      "name": "deactivate_slab",
      "external": false,
      "loc": "mm/slub.c:2050",
      "file": "mm/slub.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:slub_cpu_dead",
        "mm/slub.c:flush_cpu_slab"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581442512,
      "name": "deactivate_slab.isra.75",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1219
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "deactivate_slab",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581555520,
      "name": "deactivate_slab",
      "external": false,
      "loc": "mm/slub.c:2057",
      "file": "mm/slub.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:slub_cpu_dead",
        "mm/slub.c:flush_cpu_slab"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581555520,
      "name": "deactivate_slab.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1187
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "deactivate_slab",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581620512,
      "name": "deactivate_slab",
      "external": false,
      "loc": "mm/slub.c:2036",
      "file": "mm/slub.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:slub_cpu_dead",
        "mm/slub.c:flush_cpu_slab"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581620512,
      "name": "deactivate_slab.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1187
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
void deactivate_slab(struct kmem_cache * s, struct page * page, void * freelist, struct kmem_cache_cpu * c)
```

```json
{
  "name": "deactivate_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "deactivate_slab",
      "external": false,
      "loc": "mm/slub.c:2086",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:slub_cpu_dead",
        "mm/slub.c:flush_cpu_slab"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581836768,
      "name": "deactivate_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1267
    },
    {
      "addr": 18446744071581859588,
      "name": "deactivate_slab.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
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
void deactivate_slab(struct kmem_cache * s, struct page * page, void * freelist, struct kmem_cache_cpu * c)
```

```json
{
  "name": "deactivate_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "deactivate_slab",
      "external": false,
      "loc": "mm/slub.c:2151",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:slub_cpu_dead",
        "mm/slub.c:flush_cpu_slab"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581888160,
      "name": "deactivate_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1303
    },
    {
      "addr": 18446744071591336230,
      "name": "deactivate_slab.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
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
void deactivate_slab(struct kmem_cache * s, struct page * page, void * freelist, struct kmem_cache_cpu * c)
```

```json
{
  "name": "deactivate_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "deactivate_slab",
      "external": false,
      "loc": "mm/slub.c:2179",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:slub_cpu_dead",
        "mm/slub.c:flush_cpu_slab"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581918864,
      "name": "deactivate_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1080
    },
    {
      "addr": 18446744071591279007,
      "name": "deactivate_slab.cold",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void deactivate_slab(struct kmem_cache * s, struct page * page, void * freelist)
```

```json
{
  "name": "deactivate_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "deactivate_slab",
      "external": false,
      "loc": "mm/slub.c:2313",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:slub_cpu_dead",
        "mm/slub.c:flush_cpu_slab"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582214352,
      "name": "deactivate_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1200
    },
    {
      "addr": 18446744071592221145,
      "name": "deactivate_slab.cold",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void deactivate_slab(struct kmem_cache * s, struct slab * slab, void * freelist)
```

```json
{
  "name": "deactivate_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "deactivate_slab",
      "external": false,
      "loc": "mm/slub.c:2373",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:slub_cpu_dead",
        "mm/slub.c:flush_slab"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582679616,
      "name": "deactivate_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 921
    },
    {
      "addr": 18446744071594000021,
      "name": "deactivate_slab.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
void deactivate_slab(struct kmem_cache * s, struct slab * slab, void * freelist)
```

```json
{
  "name": "deactivate_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583206448,
      "name": "deactivate_slab",
      "external": false,
      "loc": "mm/slub.c:2474",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:bootstrap",
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:slub_cpu_dead",
        "mm/slub.c:flush_slab"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583206448,
      "name": "deactivate_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 833
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
void deactivate_slab(struct kmem_cache * s, struct slab * slab, void * freelist)
```

```json
{
  "name": "deactivate_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583424416,
      "name": "deactivate_slab",
      "external": false,
      "loc": "mm/slub.c:2484",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:bootstrap",
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:slub_cpu_dead",
        "mm/slub.c:flush_slab"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583424416,
      "name": "deactivate_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 794
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
void deactivate_slab(struct kmem_cache * s, struct slab * slab, void * freelist)
```

```json
{
  "name": "deactivate_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583406448,
      "name": "deactivate_slab",
      "external": false,
      "loc": "mm/slub.c:2805",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:bootstrap",
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:slub_cpu_dead",
        "mm/slub.c:flush_slab"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583406448,
      "name": "deactivate_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 713
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "deactivate_slab",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493066248,
      "name": "deactivate_slab",
      "external": false,
      "loc": "mm/slub.c:2036",
      "file": "mm/slub.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:slub_cpu_dead",
        "mm/slub.c:flush_cpu_slab"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493066248,
      "name": "deactivate_slab.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1368
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
void deactivate_slab(struct kmem_cache * s, struct page * page, void * freelist, struct kmem_cache_cpu * c)
```

```json
{
  "name": "deactivate_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226776460,
      "name": "deactivate_slab",
      "external": false,
      "loc": "mm/slub.c:2036",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:slub_cpu_dead",
        "mm/slub.c:flush_cpu_slab"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226776460,
      "name": "deactivate_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1336
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "deactivate_slab",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055286507552,
      "name": "deactivate_slab",
      "external": false,
      "loc": "mm/slub.c:2036",
      "file": "mm/slub.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:slub_cpu_dead",
        "mm/slub.c:flush_cpu_slab"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286507552,
      "name": "deactivate_slab.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1444
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
  "name": "deactivate_slab",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272930328,
      "name": "deactivate_slab",
      "external": false,
      "loc": "mm/slub.c:2036",
      "file": "mm/slub.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:slub_cpu_dead",
        "mm/slub.c:flush_cpu_slab"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272930328,
      "name": "deactivate_slab.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 908
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "deactivate_slab",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581589248,
      "name": "deactivate_slab",
      "external": false,
      "loc": "mm/slub.c:2036",
      "file": "mm/slub.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:slub_cpu_dead",
        "mm/slub.c:flush_cpu_slab"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581589248,
      "name": "deactivate_slab.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1187
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "deactivate_slab",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581530752,
      "name": "deactivate_slab",
      "external": false,
      "loc": "mm/slub.c:2036",
      "file": "mm/slub.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:slub_cpu_dead",
        "mm/slub.c:flush_cpu_slab"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581530752,
      "name": "deactivate_slab.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1187
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "deactivate_slab",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581580560,
      "name": "deactivate_slab",
      "external": false,
      "loc": "mm/slub.c:2036",
      "file": "mm/slub.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:slub_cpu_dead",
        "mm/slub.c:flush_cpu_slab"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581580560,
      "name": "deactivate_slab.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1187
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "deactivate_slab",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581645856,
      "name": "deactivate_slab",
      "external": false,
      "loc": "mm/slub.c:2036",
      "file": "mm/slub.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:___slab_alloc",
        "mm/slub.c:slub_cpu_dead",
        "mm/slub.c:flush_cpu_slab"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581645856,
      "name": "deactivate_slab.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1343
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
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
void deactivate_slab(struct kmem_cache * s, struct page * page, void * freelist)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void deactivate_slab(struct kmem_cache * s, struct page * page, void * freelist, struct kmem_cache_cpu * c)
```
</details>
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
<b>Param removed. </b>
<code>struct kmem_cache_cpu * c</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct slab * slab</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page * page</code>
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
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void deactivate_slab(struct kmem_cache * s, struct page * page, void * freelist, struct kmem_cache_cpu * c)
```
</details>
</li>
</ul>
