# Function: <code>create_cache</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct kmem_cache * create_cache(const char * name, size_t object_size, size_t size, size_t align, long unsigned int flags, void (*)(void *) ctor, struct mem_cgroup * memcg, struct kmem_cache * root_cache)
```

```json
{
  "name": "create_cache",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580626176,
      "name": "create_cache",
      "external": false,
      "loc": "mm/slab_common.c:319",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:kmem_cache_create",
        "mm/slab_common.c:memcg_create_kmem_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580626176,
      "name": "create_cache",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 416
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
struct kmem_cache * create_cache(const char * name, size_t object_size, size_t size, size_t align, long unsigned int flags, void (*)(void *) ctor, struct mem_cgroup * memcg, struct kmem_cache * root_cache)
```

```json
{
  "name": "create_cache",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580731248,
      "name": "create_cache",
      "external": false,
      "loc": "mm/slab_common.c:324",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:memcg_create_kmem_cache",
        "mm/slab_common.c:kmem_cache_create"
      ]
    },
    {
      "addr": 18446744071581116174,
      "name": "create_cache",
      "external": false,
      "loc": "mm/zsmalloc.c:328",
      "file": "mm/zsmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_create_pool"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580731248,
      "name": "create_cache",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 416
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
struct kmem_cache * create_cache(const char * name, size_t object_size, size_t size, size_t align, long unsigned int flags, void (*)(void *) ctor, struct mem_cgroup * memcg, struct kmem_cache * root_cache)
```

```json
{
  "name": "create_cache",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580796992,
      "name": "create_cache",
      "external": false,
      "loc": "mm/slab_common.c:324",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:memcg_create_kmem_cache",
        "mm/slab_common.c:kmem_cache_create"
      ]
    },
    {
      "addr": 18446744071581191262,
      "name": "create_cache",
      "external": false,
      "loc": "mm/zsmalloc.c:328",
      "file": "mm/zsmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_create_pool"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580796992,
      "name": "create_cache",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 416
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
struct kmem_cache * create_cache(const char * name, size_t object_size, size_t size, size_t align, long unsigned int flags, void (*)(void *) ctor, struct mem_cgroup * memcg, struct kmem_cache * root_cache)
```

```json
{
  "name": "create_cache",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580840208,
      "name": "create_cache",
      "external": false,
      "loc": "mm/slab_common.c:358",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:memcg_create_kmem_cache",
        "mm/slab_common.c:kmem_cache_create"
      ]
    },
    {
      "addr": 18446744071581242069,
      "name": "create_cache",
      "external": false,
      "loc": "mm/zsmalloc.c:321",
      "file": "mm/zsmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_create_pool"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580840208,
      "name": "create_cache",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 452
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
struct kmem_cache * create_cache(const char * name, size_t object_size, size_t size, size_t align, slab_flags_t flags, void (*)(void *) ctor, struct mem_cgroup * memcg, struct kmem_cache * root_cache)
```

```json
{
  "name": "create_cache",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580930912,
      "name": "create_cache",
      "external": false,
      "loc": "mm/slab_common.c:367",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:memcg_create_kmem_cache",
        "mm/slab_common.c:kmem_cache_create"
      ]
    },
    {
      "addr": 18446744071581374197,
      "name": "create_cache",
      "external": false,
      "loc": "mm/zsmalloc.c:322",
      "file": "mm/zsmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_create_pool"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580930912,
      "name": "create_cache",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 438
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
struct kmem_cache * create_cache(const char * name, unsigned int object_size, unsigned int align, slab_flags_t flags, unsigned int useroffset, unsigned int usersize, void (*)(void *) ctor, struct mem_cgroup * memcg, struct kmem_cache * root_cache)
```

```json
{
  "name": "create_cache",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581066848,
      "name": "create_cache",
      "external": false,
      "loc": "mm/slab_common.c:363",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:memcg_create_kmem_cache",
        "mm/slab_common.c:kmem_cache_create_usercopy"
      ]
    },
    {
      "addr": 18446744071581521397,
      "name": "create_cache",
      "external": false,
      "loc": "mm/zsmalloc.c:321",
      "file": "mm/zsmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_create_pool"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581066848,
      "name": "create_cache",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 469
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
struct kmem_cache * create_cache(const char * name, unsigned int object_size, unsigned int align, slab_flags_t flags, unsigned int useroffset, unsigned int usersize, void (*)(void *) ctor, struct mem_cgroup * memcg, struct kmem_cache * root_cache)
```

```json
{
  "name": "create_cache",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581144640,
      "name": "create_cache",
      "external": false,
      "loc": "mm/slab_common.c:363",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:memcg_create_kmem_cache",
        "mm/slab_common.c:kmem_cache_create_usercopy"
      ]
    },
    {
      "addr": 18446744071581606773,
      "name": "create_cache",
      "external": false,
      "loc": "mm/zsmalloc.c:321",
      "file": "mm/zsmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_create_pool"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581144640,
      "name": "create_cache",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 469
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
struct kmem_cache * create_cache(const char * name, unsigned int object_size, unsigned int align, slab_flags_t flags, unsigned int useroffset, unsigned int usersize, void (*)(void *) ctor, struct mem_cgroup * memcg, struct kmem_cache * root_cache)
```

```json
{
  "name": "create_cache",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "create_cache",
      "external": false,
      "loc": "mm/slab_common.c:378",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:memcg_create_kmem_cache",
        "mm/slab_common.c:kmem_cache_create_usercopy"
      ]
    },
    {
      "addr": 18446744071581717715,
      "name": "create_cache",
      "external": false,
      "loc": "mm/zsmalloc.c:327",
      "file": "mm/zsmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_create_pool"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581211216,
      "name": "create_cache",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 533
    },
    {
      "addr": 18446744071581214572,
      "name": "create_cache.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
struct kmem_cache * create_cache(const char * name, unsigned int object_size, unsigned int align, slab_flags_t flags, unsigned int useroffset, unsigned int usersize, void (*)(void *) ctor, struct mem_cgroup * memcg, struct kmem_cache * root_cache)
```

```json
{
  "name": "create_cache",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581269744,
      "name": "create_cache",
      "external": false,
      "loc": "mm/slab_common.c:379",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:memcg_create_kmem_cache",
        "mm/slab_common.c:kmem_cache_create_usercopy"
      ]
    },
    {
      "addr": 18446744071581791171,
      "name": "create_cache",
      "external": false,
      "loc": "mm/zsmalloc.c:327",
      "file": "mm/zsmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_create_pool"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581269744,
      "name": "create_cache",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 503
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
struct kmem_cache * create_cache(const char * name, unsigned int object_size, unsigned int align, slab_flags_t flags, unsigned int useroffset, unsigned int usersize, void (*)(void *) ctor, struct mem_cgroup * memcg, struct kmem_cache * root_cache)
```

```json
{
  "name": "create_cache",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581459760,
      "name": "create_cache",
      "external": false,
      "loc": "mm/slab_common.c:379",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:memcg_create_kmem_cache",
        "mm/slab_common.c:kmem_cache_create_usercopy"
      ]
    },
    {
      "addr": 18446744071582012502,
      "name": "create_cache",
      "external": false,
      "loc": "mm/zsmalloc.c:327",
      "file": "mm/zsmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_create_pool"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581459760,
      "name": "create_cache",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 503
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
  "name": "create_cache",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581498669,
      "name": "create_cache",
      "external": false,
      "loc": "mm/slab_common.c:233",
      "file": "mm/slab_common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:kmem_cache_create_usercopy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582060982,
      "name": "create_cache",
      "external": false,
      "loc": "mm/zsmalloc.c:323",
      "file": "mm/zsmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_create_pool"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "create_cache",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581519857,
      "name": "create_cache",
      "external": false,
      "loc": "mm/slab_common.c:241",
      "file": "mm/slab_common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:kmem_cache_create_usercopy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582085766,
      "name": "create_cache",
      "external": false,
      "loc": "mm/zsmalloc.c:323",
      "file": "mm/zsmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_create_pool"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "create_cache",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581781521,
      "name": "create_cache",
      "external": false,
      "loc": "mm/slab_common.c:241",
      "file": "mm/slab_common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:kmem_cache_create_usercopy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582398320,
      "name": "create_cache",
      "external": false,
      "loc": "mm/zsmalloc.c:323",
      "file": "mm/zsmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_create_pool"
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
  "name": "create_cache",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582168611,
      "name": "create_cache",
      "external": false,
      "loc": "mm/slab_common.c:233",
      "file": "mm/slab_common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:kmem_cache_create_usercopy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582909508,
      "name": "create_cache",
      "external": false,
      "loc": "mm/zsmalloc.c:325",
      "file": "mm/zsmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_create_pool"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "create_cache",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582648995,
      "name": "create_cache",
      "external": false,
      "loc": "mm/slab_common.c:207",
      "file": "mm/slab_common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:kmem_cache_create_usercopy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583462244,
      "name": "create_cache",
      "external": false,
      "loc": "mm/zsmalloc.c:341",
      "file": "mm/zsmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_create_pool"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "create_cache",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582858581,
      "name": "create_cache",
      "external": false,
      "loc": "mm/slab_common.c:209",
      "file": "mm/slab_common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:kmem_cache_create_usercopy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583680847,
      "name": "create_cache",
      "external": false,
      "loc": "mm/zsmalloc.c:298",
      "file": "mm/zsmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_create_pool"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "create_cache",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583033845,
      "name": "create_cache",
      "external": false,
      "loc": "mm/slab_common.c:204",
      "file": "mm/slab_common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:kmem_cache_create_usercopy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583875278,
      "name": "create_cache",
      "external": false,
      "loc": "mm/zsmalloc.c:298",
      "file": "mm/zsmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_create_pool"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Collision, Selective Inline ❓</summary>

```c
struct kmem_cache * create_cache(const char * name, unsigned int object_size, unsigned int align, slab_flags_t flags, unsigned int useroffset, unsigned int usersize, void (*)(void *) ctor, struct mem_cgroup * memcg, struct kmem_cache * root_cache)
```

```json
{
  "name": "create_cache",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492674664,
      "name": "create_cache",
      "external": false,
      "loc": "mm/slab_common.c:379",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:memcg_create_kmem_cache",
        "mm/slab_common.c:kmem_cache_create_usercopy"
      ]
    },
    {
      "addr": 18446603336493252948,
      "name": "create_cache",
      "external": false,
      "loc": "mm/zsmalloc.c:327",
      "file": "mm/zsmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_create_pool"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492674664,
      "name": "create_cache",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 464
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Collision, Selective Inline ❓</summary>

```c
struct kmem_cache * create_cache(const char * name, unsigned int object_size, unsigned int align, slab_flags_t flags, unsigned int useroffset, unsigned int usersize, void (*)(void *) ctor, struct mem_cgroup * memcg, struct kmem_cache * root_cache)
```

```json
{
  "name": "create_cache",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226513492,
      "name": "create_cache",
      "external": false,
      "loc": "mm/slab_common.c:379",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:memcg_create_kmem_cache",
        "mm/slab_common.c:kmem_cache_create_usercopy"
      ]
    },
    {
      "addr": 3226862908,
      "name": "create_cache",
      "external": false,
      "loc": "mm/zsmalloc.c:327",
      "file": "mm/zsmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_create_pool"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3226513492,
      "name": "create_cache",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 440
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Collision, Selective Inline ❓</summary>

```c
struct kmem_cache * create_cache(const char * name, unsigned int object_size, unsigned int align, slab_flags_t flags, unsigned int useroffset, unsigned int usersize, void (*)(void *) ctor, struct mem_cgroup * memcg, struct kmem_cache * root_cache)
```

```json
{
  "name": "create_cache",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285999904,
      "name": "create_cache",
      "external": false,
      "loc": "mm/slab_common.c:379",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:memcg_create_kmem_cache",
        "mm/slab_common.c:kmem_cache_create_usercopy"
      ]
    },
    {
      "addr": 13835058055286779664,
      "name": "create_cache",
      "external": false,
      "loc": "mm/zsmalloc.c:327",
      "file": "mm/zsmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_create_pool"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285999904,
      "name": "create_cache",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 616
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Collision, Selective Inline ❓</summary>

```c
struct kmem_cache * create_cache(const char * name, unsigned int object_size, unsigned int align, slab_flags_t flags, unsigned int useroffset, unsigned int usersize, void (*)(void *) ctor, struct mem_cgroup * memcg, struct kmem_cache * root_cache)
```

```json
{
  "name": "create_cache",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272681884,
      "name": "create_cache",
      "external": false,
      "loc": "mm/slab_common.c:379",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:memcg_create_kmem_cache",
        "mm/slab_common.c:kmem_cache_create_usercopy"
      ]
    },
    {
      "addr": 18446743936273011412,
      "name": "create_cache",
      "external": false,
      "loc": "mm/zsmalloc.c:327",
      "file": "mm/zsmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_create_pool"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272681884,
      "name": "create_cache",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 368
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Collision, Selective Inline ❓</summary>

```c
struct kmem_cache * create_cache(const char * name, unsigned int object_size, unsigned int align, slab_flags_t flags, unsigned int useroffset, unsigned int usersize, void (*)(void *) ctor, struct mem_cgroup * memcg, struct kmem_cache * root_cache)
```

```json
{
  "name": "create_cache",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581238592,
      "name": "create_cache",
      "external": false,
      "loc": "mm/slab_common.c:379",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:memcg_create_kmem_cache",
        "mm/slab_common.c:kmem_cache_create_usercopy"
      ]
    },
    {
      "addr": 18446744071581759907,
      "name": "create_cache",
      "external": false,
      "loc": "mm/zsmalloc.c:327",
      "file": "mm/zsmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_create_pool"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581238592,
      "name": "create_cache",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 503
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Collision, Selective Inline ❓</summary>

```c
struct kmem_cache * create_cache(const char * name, unsigned int object_size, unsigned int align, slab_flags_t flags, unsigned int useroffset, unsigned int usersize, void (*)(void *) ctor, struct mem_cgroup * memcg, struct kmem_cache * root_cache)
```

```json
{
  "name": "create_cache",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581185264,
      "name": "create_cache",
      "external": false,
      "loc": "mm/slab_common.c:379",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:memcg_create_kmem_cache",
        "mm/slab_common.c:kmem_cache_create_usercopy"
      ]
    },
    {
      "addr": 18446744071581698531,
      "name": "create_cache",
      "external": false,
      "loc": "mm/zsmalloc.c:327",
      "file": "mm/zsmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_create_pool"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581185264,
      "name": "create_cache",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 503
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Collision, Selective Inline ❓</summary>

```c
struct kmem_cache * create_cache(const char * name, unsigned int object_size, unsigned int align, slab_flags_t flags, unsigned int useroffset, unsigned int usersize, void (*)(void *) ctor, struct mem_cgroup * memcg, struct kmem_cache * root_cache)
```

```json
{
  "name": "create_cache",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581229792,
      "name": "create_cache",
      "external": false,
      "loc": "mm/slab_common.c:379",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:memcg_create_kmem_cache",
        "mm/slab_common.c:kmem_cache_create_usercopy"
      ]
    },
    {
      "addr": 18446744071581751219,
      "name": "create_cache",
      "external": false,
      "loc": "mm/zsmalloc.c:327",
      "file": "mm/zsmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_create_pool"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581229792,
      "name": "create_cache",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 503
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Collision, Selective Inline ❓</summary>

```c
struct kmem_cache * create_cache(const char * name, unsigned int object_size, unsigned int align, slab_flags_t flags, unsigned int useroffset, unsigned int usersize, void (*)(void *) ctor, struct mem_cgroup * memcg, struct kmem_cache * root_cache)
```

```json
{
  "name": "create_cache",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581293296,
      "name": "create_cache",
      "external": false,
      "loc": "mm/slab_common.c:379",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:memcg_create_kmem_cache",
        "mm/slab_common.c:kmem_cache_create_usercopy"
      ]
    },
    {
      "addr": 18446744071581819859,
      "name": "create_cache",
      "external": false,
      "loc": "mm/zsmalloc.c:327",
      "file": "mm/zsmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_create_pool"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581293296,
      "name": "create_cache",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 503
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
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>long unsigned int flags</code> ➡️ <code>slab_flags_t flags</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int useroffset</code>
</li>
<li>
<b>Param added. </b>
<code>unsigned int usersize</code>
</li>
<li>
<b>Param removed. </b>
<code>size_t size</code>
</li>
<li>
<b>Param reordered. </b>
<code>name, object_size, size, align, flags, ctor, memcg, root_cache</code> ➡️ <code>name, object_size, align, flags, useroffset, usersize, ctor, memcg, root_cache</code>
</li>
<li>
<b>Param type changed. </b>
<code>size_t object_size</code> ➡️ <code>unsigned int object_size</code>
</li>
<li>
<b>Param type changed. </b>
<code>size_t align</code> ➡️ <code>unsigned int align</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
struct kmem_cache * create_cache(const char * name, unsigned int object_size, unsigned int align, slab_flags_t flags, unsigned int useroffset, unsigned int usersize, void (*)(void *) ctor, struct mem_cgroup * memcg, struct kmem_cache * root_cache)
```
</details>
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
