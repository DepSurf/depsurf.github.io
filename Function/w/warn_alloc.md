# Function: <code>warn_alloc</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void warn_alloc(gfp_t gfp_mask, const char * fmt, void (anon))
```

```json
{
  "name": "warn_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580657920,
      "name": "warn_alloc",
      "external": true,
      "loc": "mm/page_alloc.c:3014",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/vmalloc.c:__vmalloc_node_range",
        "mm/vmalloc.c:__vmalloc_node_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580657920,
      "name": "warn_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 358
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
void warn_alloc(gfp_t gfp_mask, nodemask_t * nodemask, const char * fmt, void (anon))
```

```json
{
  "name": "warn_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580690736,
      "name": "warn_alloc",
      "external": true,
      "loc": "mm/page_alloc.c:3216",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_slowpath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580690736,
      "name": "warn_alloc",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void warn_alloc(gfp_t gfp_mask, nodemask_t * nodemask, const char * fmt, void (anon))
```

```json
{
  "name": "warn_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580776240,
      "name": "warn_alloc",
      "external": true,
      "loc": "mm/page_alloc.c:3284",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__alloc_pages_slowpath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580776240,
      "name": "warn_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 403
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
void warn_alloc(gfp_t gfp_mask, nodemask_t * nodemask, const char * fmt, void (anon))
```

```json
{
  "name": "warn_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "warn_alloc",
      "external": true,
      "loc": "mm/page_alloc.c:3406",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/sparse-vmemmap.c:vmemmap_alloc_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580921162,
      "name": "warn_alloc.cold.115",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
    },
    {
      "addr": 18446744071580912256,
      "name": "warn_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
void warn_alloc(gfp_t gfp_mask, nodemask_t * nodemask, const char * fmt, void (anon))
```

```json
{
  "name": "warn_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "warn_alloc",
      "external": true,
      "loc": "mm/page_alloc.c:3568",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/sparse-vmemmap.c:vmemmap_alloc_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580997108,
      "name": "warn_alloc.cold.119",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 251
    },
    {
      "addr": 18446744071580987392,
      "name": "warn_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
void warn_alloc(gfp_t gfp_mask, nodemask_t * nodemask, const char * fmt, void (anon))
```

```json
{
  "name": "warn_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "warn_alloc",
      "external": true,
      "loc": "mm/page_alloc.c:3736",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/sparse-vmemmap.c:vmemmap_alloc_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581416107,
      "name": "warn_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 251
    },
    {
      "addr": 18446744071581405840,
      "name": "warn_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
void warn_alloc(gfp_t gfp_mask, nodemask_t * nodemask, const char * fmt, void (anon))
```

```json
{
  "name": "warn_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "warn_alloc",
      "external": true,
      "loc": "mm/page_alloc.c:3723",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/sparse-vmemmap.c:vmemmap_alloc_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581477090,
      "name": "warn_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 223
    },
    {
      "addr": 18446744071581466832,
      "name": "warn_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
void warn_alloc(gfp_t gfp_mask, nodemask_t * nodemask, const char * fmt, void (anon))
```

```json
{
  "name": "warn_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "warn_alloc",
      "external": true,
      "loc": "mm/page_alloc.c:3838",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:__vmalloc_node_range",
        "mm/vmalloc.c:__vmalloc_area_node",
        "mm/sparse-vmemmap.c:vmemmap_alloc_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581682052,
      "name": "warn_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 223
    },
    {
      "addr": 18446744071581673776,
      "name": "warn_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
void warn_alloc(gfp_t gfp_mask, nodemask_t * nodemask, const char * fmt, void (anon))
```

```json
{
  "name": "warn_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "warn_alloc",
      "external": true,
      "loc": "mm/page_alloc.c:3989",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:__vmalloc_node_range",
        "mm/vmalloc.c:__vmalloc_area_node",
        "mm/sparse-vmemmap.c:vmemmap_alloc_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591328932,
      "name": "warn_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 223
    },
    {
      "addr": 18446744071581721760,
      "name": "warn_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
void warn_alloc(gfp_t gfp_mask, nodemask_t * nodemask, const char * fmt, void (anon))
```

```json
{
  "name": "warn_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "warn_alloc",
      "external": true,
      "loc": "mm/page_alloc.c:4036",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:__vmalloc_node_range",
        "mm/vmalloc.c:__vmalloc_node_range",
        "mm/sparse-vmemmap.c:vmemmap_alloc_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591271070,
      "name": "warn_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
    },
    {
      "addr": 18446744071581742384,
      "name": "warn_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
void warn_alloc(gfp_t gfp_mask, nodemask_t * nodemask, const char * fmt, void (anon))
```

```json
{
  "name": "warn_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "warn_alloc",
      "external": true,
      "loc": "mm/page_alloc.c:4207",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:__vmalloc_node_range",
        "mm/vmalloc.c:__vmalloc_node_range",
        "mm/sparse-vmemmap.c:vmemmap_alloc_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592204743,
      "name": "warn_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
    },
    {
      "addr": 18446744071582020320,
      "name": "warn_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 339
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
void warn_alloc(gfp_t gfp_mask, nodemask_t * nodemask, const char * fmt, void (anon))
```

```json
{
  "name": "warn_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "warn_alloc",
      "external": true,
      "loc": "mm/page_alloc.c:4250",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:__vmalloc_node_range",
        "mm/vmalloc.c:__vmalloc_node_range",
        "mm/vmalloc.c:__vmalloc_node_range",
        "mm/vmalloc.c:__vmalloc_area_node",
        "mm/vmalloc.c:__vmalloc_area_node",
        "mm/vmalloc.c:__vmalloc_area_node",
        "mm/sparse-vmemmap.c:vmemmap_alloc_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593982006,
      "name": "warn_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071582447104,
      "name": "warn_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 387
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
void warn_alloc(gfp_t gfp_mask, nodemask_t * nodemask, const char * fmt, void (anon))
```

```json
{
  "name": "warn_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582956464,
      "name": "warn_alloc",
      "external": true,
      "loc": "mm/page_alloc.c:4335",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:__vmalloc_node_range",
        "mm/vmalloc.c:__vmalloc_node_range",
        "mm/vmalloc.c:__vmalloc_node_range",
        "mm/vmalloc.c:__vmalloc_area_node",
        "mm/vmalloc.c:__vmalloc_area_node",
        "mm/vmalloc.c:__vmalloc_area_node",
        "mm/sparse-vmemmap.c:vmemmap_alloc_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582956464,
      "name": "warn_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 486
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
void warn_alloc(gfp_t gfp_mask, nodemask_t * nodemask, const char * fmt, void (anon))
```

```json
{
  "name": "warn_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583173568,
      "name": "warn_alloc",
      "external": true,
      "loc": "mm/page_alloc.c:3278",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:__vmalloc_node_range",
        "mm/vmalloc.c:__vmalloc_node_range",
        "mm/vmalloc.c:__vmalloc_node_range",
        "mm/vmalloc.c:__vmalloc_area_node",
        "mm/vmalloc.c:__vmalloc_area_node",
        "mm/vmalloc.c:__vmalloc_area_node",
        "mm/sparse-vmemmap.c:vmemmap_alloc_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583173568,
      "name": "warn_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 481
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
void warn_alloc(gfp_t gfp_mask, nodemask_t * nodemask, const char * fmt, void (anon))
```

```json
{
  "name": "warn_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583357312,
      "name": "warn_alloc",
      "external": true,
      "loc": "mm/page_alloc.c:3368",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:__vmalloc_node_range",
        "mm/vmalloc.c:__vmalloc_node_range",
        "mm/vmalloc.c:__vmalloc_node_range",
        "mm/vmalloc.c:__vmalloc_area_node",
        "mm/vmalloc.c:__vmalloc_area_node",
        "mm/vmalloc.c:__vmalloc_area_node",
        "mm/sparse-vmemmap.c:vmemmap_alloc_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583357312,
      "name": "warn_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 481
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
void warn_alloc(gfp_t gfp_mask, nodemask_t * nodemask, const char * fmt, void (anon))
```

```json
{
  "name": "warn_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492875616,
      "name": "warn_alloc",
      "external": true,
      "loc": "mm/page_alloc.c:3723",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/sparse-vmemmap.c:vmemmap_alloc_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492875616,
      "name": "warn_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 356
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
void warn_alloc(gfp_t gfp_mask, nodemask_t * nodemask, const char * fmt, void (anon))
```

```json
{
  "name": "warn_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226674360,
      "name": "warn_alloc",
      "external": true,
      "loc": "mm/page_alloc.c:3723",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__alloc_pages_slowpath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226674360,
      "name": "warn_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 372
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
void warn_alloc(gfp_t gfp_mask, nodemask_t * nodemask, const char * fmt, void (anon))
```

```json
{
  "name": "warn_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286269248,
      "name": "warn_alloc",
      "external": true,
      "loc": "mm/page_alloc.c:3723",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/sparse-vmemmap.c:vmemmap_alloc_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286269248,
      "name": "warn_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 460
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
void warn_alloc(gfp_t gfp_mask, nodemask_t * nodemask, const char * fmt, void (anon))
```

```json
{
  "name": "warn_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272817676,
      "name": "warn_alloc",
      "external": true,
      "loc": "mm/page_alloc.c:3723",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/sparse-vmemmap.c:vmemmap_alloc_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272817676,
      "name": "warn_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 278
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
void warn_alloc(gfp_t gfp_mask, nodemask_t * nodemask, const char * fmt, void (anon))
```

```json
{
  "name": "warn_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "warn_alloc",
      "external": true,
      "loc": "mm/page_alloc.c:3723",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/sparse-vmemmap.c:vmemmap_alloc_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581445938,
      "name": "warn_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 223
    },
    {
      "addr": 18446744071581435680,
      "name": "warn_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
void warn_alloc(gfp_t gfp_mask, nodemask_t * nodemask, const char * fmt, void (anon))
```

```json
{
  "name": "warn_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "warn_alloc",
      "external": true,
      "loc": "mm/page_alloc.c:3723",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/sparse-vmemmap.c:vmemmap_alloc_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581388306,
      "name": "warn_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 223
    },
    {
      "addr": 18446744071581378064,
      "name": "warn_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
void warn_alloc(gfp_t gfp_mask, nodemask_t * nodemask, const char * fmt, void (anon))
```

```json
{
  "name": "warn_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "warn_alloc",
      "external": true,
      "loc": "mm/page_alloc.c:3723",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/sparse-vmemmap.c:vmemmap_alloc_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581437138,
      "name": "warn_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 223
    },
    {
      "addr": 18446744071581426880,
      "name": "warn_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
void warn_alloc(gfp_t gfp_mask, nodemask_t * nodemask, const char * fmt, void (anon))
```

```json
{
  "name": "warn_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "warn_alloc",
      "external": true,
      "loc": "mm/page_alloc.c:3723",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/sparse-vmemmap.c:vmemmap_alloc_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581501634,
      "name": "warn_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 223
    },
    {
      "addr": 18446744071581491328,
      "name": "warn_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
void warn_alloc(gfp_t gfp_mask, const char * fmt, void (anon))
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>nodemask_t * nodemask</code>
</li>
<li>
<b>Param reordered. </b>
<code>gfp_mask, fmt, (anon)</code> ➡️ <code>gfp_mask, nodemask, fmt, (anon)</code>
</li>
</ul>
</details>
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
