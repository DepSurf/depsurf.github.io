# Function: <code>check_slab</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int check_slab(struct kmem_cache * s, struct page * page)
```

```json
{
  "name": "check_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580847248,
      "name": "check_slab",
      "external": false,
      "loc": "mm/slub.c:865",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:alloc_debug_processing",
        "mm/slub.c:validate_slab",
        "mm/slub.c:free_debug_processing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580847248,
      "name": "check_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
int check_slab(struct kmem_cache * s, struct page * page)
```

```json
{
  "name": "check_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580973648,
      "name": "check_slab",
      "external": false,
      "loc": "mm/slub.c:889",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:validate_slab",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:alloc_debug_processing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580973648,
      "name": "check_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
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
int check_slab(struct kmem_cache * s, struct page * page)
```

```json
{
  "name": "check_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581047424,
      "name": "check_slab",
      "external": false,
      "loc": "mm/slub.c:888",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:validate_slab",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:alloc_debug_processing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581047424,
      "name": "check_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 178
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
int check_slab(struct kmem_cache * s, struct page * page)
```

```json
{
  "name": "check_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581095232,
      "name": "check_slab",
      "external": false,
      "loc": "mm/slub.c:890",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:validate_slab",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:alloc_debug_processing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581095232,
      "name": "check_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
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
int check_slab(struct kmem_cache * s, struct page * page)
```

```json
{
  "name": "check_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581207488,
      "name": "check_slab",
      "external": false,
      "loc": "mm/slub.c:925",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:validate_slab",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:alloc_debug_processing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581207488,
      "name": "check_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
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
int check_slab(struct kmem_cache * s, struct page * page)
```

```json
{
  "name": "check_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_slab",
      "external": false,
      "loc": "mm/slub.c:913",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:validate_slab",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:alloc_debug_processing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581351312,
      "name": "check_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
    },
    {
      "addr": 18446744071581379610,
      "name": "check_slab.cold.90",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
int check_slab(struct kmem_cache * s, struct page * page)
```

```json
{
  "name": "check_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_slab",
      "external": false,
      "loc": "mm/slub.c:918",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:validate_slab",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:alloc_debug_processing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581435088,
      "name": "check_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    },
    {
      "addr": 18446744071581463722,
      "name": "check_slab.cold.92",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int check_slab(struct kmem_cache * s, struct page * page)
```

```json
{
  "name": "check_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_slab",
      "external": false,
      "loc": "mm/slub.c:910",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:validate_slab",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:alloc_debug_processing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581547568,
      "name": "check_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
    },
    {
      "addr": 18446744071581578625,
      "name": "check_slab.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
int check_slab(struct kmem_cache * s, struct page * page)
```

```json
{
  "name": "check_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_slab",
      "external": false,
      "loc": "mm/slub.c:910",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:validate_slab",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:alloc_debug_processing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581612432,
      "name": "check_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
    },
    {
      "addr": 18446744071581643841,
      "name": "check_slab.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
int check_slab(struct kmem_cache * s, struct page * page)
```

```json
{
  "name": "check_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_slab",
      "external": false,
      "loc": "mm/slub.c:955",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:validate_slab",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:alloc_debug_processing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581827312,
      "name": "check_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
    },
    {
      "addr": 18446744071581859072,
      "name": "check_slab.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
int check_slab(struct kmem_cache * s, struct page * page)
```

```json
{
  "name": "check_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_slab",
      "external": false,
      "loc": "mm/slub.c:950",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:validate_slab",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:alloc_debug_processing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581874784,
      "name": "check_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
    },
    {
      "addr": 18446744071591334456,
      "name": "check_slab.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
int check_slab(struct kmem_cache * s, struct page * page)
```

```json
{
  "name": "check_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_slab",
      "external": false,
      "loc": "mm/slub.c:962",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:validate_slab",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:alloc_debug_processing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581905632,
      "name": "check_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
    },
    {
      "addr": 18446744071591277510,
      "name": "check_slab.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
int check_slab(struct kmem_cache * s, struct page * page)
```

```json
{
  "name": "check_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_slab",
      "external": false,
      "loc": "mm/slub.c:1088",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:validate_slab",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:alloc_debug_processing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582201440,
      "name": "check_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
    },
    {
      "addr": 18446744071592218433,
      "name": "check_slab.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
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
int check_slab(struct kmem_cache * s, struct slab * slab)
```

```json
{
  "name": "check_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_slab",
      "external": false,
      "loc": "mm/slub.c:1134",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:validate_slab",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:alloc_debug_processing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582671312,
      "name": "check_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
    },
    {
      "addr": 18446744071593998183,
      "name": "check_slab.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
int check_slab(struct kmem_cache * s, struct slab * slab)
```

```json
{
  "name": "check_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_slab",
      "external": false,
      "loc": "mm/slub.c:1229",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:validate_slab",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:alloc_debug_processing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583194896,
      "name": "check_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
    },
    {
      "addr": 18446744071596045290,
      "name": "check_slab.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
int check_slab(struct kmem_cache * s, struct slab * slab)
```

```json
{
  "name": "check_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_slab",
      "external": false,
      "loc": "mm/slub.c:1250",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:validate_slab",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:alloc_debug_processing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583412416,
      "name": "check_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
    },
    {
      "addr": 18446744071596567727,
      "name": "check_slab.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
int check_slab(struct kmem_cache * s, struct slab * slab)
```

```json
{
  "name": "check_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_slab",
      "external": false,
      "loc": "mm/slub.c:1374",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:validate_slab",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:alloc_debug_processing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583392688,
      "name": "check_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 243
    },
    {
      "addr": 18446744071597465104,
      "name": "check_slab.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
int check_slab(struct kmem_cache * s, struct page * page)
```

```json
{
  "name": "check_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493055656,
      "name": "check_slab",
      "external": false,
      "loc": "mm/slub.c:910",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:validate_slab_slab",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:alloc_debug_processing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493055656,
      "name": "check_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
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
int check_slab(struct kmem_cache * s, struct page * page)
```

```json
{
  "name": "check_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226768172,
      "name": "check_slab",
      "external": false,
      "loc": "mm/slub.c:910",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:validate_slab_slab",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:alloc_debug_processing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226768172,
      "name": "check_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
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
int check_slab(struct kmem_cache * s, struct page * page)
```

```json
{
  "name": "check_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286495168,
      "name": "check_slab",
      "external": false,
      "loc": "mm/slub.c:910",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:validate_slab",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:alloc_debug_processing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286495168,
      "name": "check_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
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
int check_slab(struct kmem_cache * s, struct page * page)
```

```json
{
  "name": "check_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272922212,
      "name": "check_slab",
      "external": false,
      "loc": "mm/slub.c:910",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:validate_slab_slab",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:alloc_debug_processing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272922212,
      "name": "check_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
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
int check_slab(struct kmem_cache * s, struct page * page)
```

```json
{
  "name": "check_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_slab",
      "external": false,
      "loc": "mm/slub.c:910",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:validate_slab",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:alloc_debug_processing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581581168,
      "name": "check_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
    },
    {
      "addr": 18446744071581612577,
      "name": "check_slab.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
int check_slab(struct kmem_cache * s, struct page * page)
```

```json
{
  "name": "check_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_slab",
      "external": false,
      "loc": "mm/slub.c:910",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:validate_slab",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:alloc_debug_processing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581522736,
      "name": "check_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
    },
    {
      "addr": 18446744071581553905,
      "name": "check_slab.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
int check_slab(struct kmem_cache * s, struct page * page)
```

```json
{
  "name": "check_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_slab",
      "external": false,
      "loc": "mm/slub.c:910",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:validate_slab",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:alloc_debug_processing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581572480,
      "name": "check_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
    },
    {
      "addr": 18446744071581603889,
      "name": "check_slab.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
int check_slab(struct kmem_cache * s, struct page * page)
```

```json
{
  "name": "check_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_slab",
      "external": false,
      "loc": "mm/slub.c:910",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:validate_slab_slab",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:alloc_debug_processing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581637568,
      "name": "check_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
    },
    {
      "addr": 18446744071581669857,
      "name": "check_slab.cold",
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
