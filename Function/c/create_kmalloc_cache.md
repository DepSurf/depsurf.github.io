# Function: <code>create_kmalloc_cache</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct kmem_cache * create_kmalloc_cache(const char * name, size_t size, long unsigned int flags)
```

```json
{
  "name": "create_kmalloc_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595139276,
      "name": "create_kmalloc_cache",
      "external": true,
      "loc": "mm/slab_common.c:784",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:new_kmalloc_cache",
        "mm/slab_common.c:create_kmalloc_caches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595139276,
      "name": "create_kmalloc_cache",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 130
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
struct kmem_cache * create_kmalloc_cache(const char * name, size_t size, long unsigned int flags)
```

```json
{
  "name": "create_kmalloc_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595310008,
      "name": "create_kmalloc_cache",
      "external": true,
      "loc": "mm/slab_common.c:792",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:create_kmalloc_caches",
        "mm/slab_common.c:new_kmalloc_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595310008,
      "name": "create_kmalloc_cache",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 130
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
struct kmem_cache * create_kmalloc_cache(const char * name, size_t size, long unsigned int flags)
```

```json
{
  "name": "create_kmalloc_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595558261,
      "name": "create_kmalloc_cache",
      "external": true,
      "loc": "mm/slab_common.c:821",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:create_kmalloc_caches",
        "mm/slab_common.c:new_kmalloc_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595558261,
      "name": "create_kmalloc_cache",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 130
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
struct kmem_cache * create_kmalloc_cache(const char * name, size_t size, long unsigned int flags)
```

```json
{
  "name": "create_kmalloc_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596484994,
      "name": "create_kmalloc_cache",
      "external": true,
      "loc": "mm/slab_common.c:892",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:create_kmalloc_caches",
        "mm/slab_common.c:new_kmalloc_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596484994,
      "name": "create_kmalloc_cache",
      "section": ".init.text",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct kmem_cache * create_kmalloc_cache(const char * name, size_t size, slab_flags_t flags)
```

```json
{
  "name": "create_kmalloc_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071602811816,
      "name": "create_kmalloc_cache",
      "external": true,
      "loc": "mm/slab_common.c:901",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:create_kmalloc_caches",
        "mm/slab_common.c:new_kmalloc_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071602811816,
      "name": "create_kmalloc_cache",
      "section": ".init.text",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct kmem_cache * create_kmalloc_cache(const char * name, unsigned int size, slab_flags_t flags, unsigned int useroffset, unsigned int usersize)
```

```json
{
  "name": "create_kmalloc_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071602985061,
      "name": "create_kmalloc_cache",
      "external": true,
      "loc": "mm/slab_common.c:960",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:create_kmalloc_caches",
        "mm/slab_common.c:new_kmalloc_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071602985061,
      "name": "create_kmalloc_cache",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 167
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
struct kmem_cache * create_kmalloc_cache(const char * name, unsigned int size, slab_flags_t flags, unsigned int useroffset, unsigned int usersize)
```

```json
{
  "name": "create_kmalloc_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604785068,
      "name": "create_kmalloc_cache",
      "external": true,
      "loc": "mm/slab_common.c:987",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:create_kmalloc_caches",
        "mm/slab_common.c:new_kmalloc_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604785068,
      "name": "create_kmalloc_cache",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 167
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
struct kmem_cache * create_kmalloc_cache(const char * name, unsigned int size, slab_flags_t flags, unsigned int useroffset, unsigned int usersize)
```

```json
{
  "name": "create_kmalloc_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604880788,
      "name": "create_kmalloc_cache",
      "external": true,
      "loc": "mm/slab_common.c:1014",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:create_kmalloc_caches",
        "mm/slab_common.c:new_kmalloc_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604880788,
      "name": "create_kmalloc_cache",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 170
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
struct kmem_cache * create_kmalloc_cache(const char * name, unsigned int size, slab_flags_t flags, unsigned int useroffset, unsigned int usersize)
```

```json
{
  "name": "create_kmalloc_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604914723,
      "name": "create_kmalloc_cache",
      "external": true,
      "loc": "mm/slab_common.c:1074",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:create_kmalloc_caches",
        "mm/slab_common.c:new_kmalloc_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604914723,
      "name": "create_kmalloc_cache",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 170
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
struct kmem_cache * create_kmalloc_cache(const char * name, unsigned int size, slab_flags_t flags, unsigned int useroffset, unsigned int usersize)
```

```json
{
  "name": "create_kmalloc_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609230670,
      "name": "create_kmalloc_cache",
      "external": true,
      "loc": "mm/slab_common.c:1074",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:create_kmalloc_caches",
        "mm/slab_common.c:new_kmalloc_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609230670,
      "name": "create_kmalloc_cache",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 170
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
struct kmem_cache * create_kmalloc_cache(const char * name, unsigned int size, slab_flags_t flags, unsigned int useroffset, unsigned int usersize)
```

```json
{
  "name": "create_kmalloc_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612297812,
      "name": "create_kmalloc_cache",
      "external": true,
      "loc": "mm/slab_common.c:572",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:create_kmalloc_caches",
        "mm/slab_common.c:new_kmalloc_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612297812,
      "name": "create_kmalloc_cache",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 160
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
struct kmem_cache * create_kmalloc_cache(const char * name, unsigned int size, slab_flags_t flags, unsigned int useroffset, unsigned int usersize)
```

```json
{
  "name": "create_kmalloc_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614437772,
      "name": "create_kmalloc_cache",
      "external": true,
      "loc": "mm/slab_common.c:657",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:create_kmalloc_caches",
        "mm/slab_common.c:new_kmalloc_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614437772,
      "name": "create_kmalloc_cache",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 160
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
struct kmem_cache * create_kmalloc_cache(const char * name, unsigned int size, slab_flags_t flags, unsigned int useroffset, unsigned int usersize)
```

```json
{
  "name": "create_kmalloc_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615378173,
      "name": "create_kmalloc_cache",
      "external": true,
      "loc": "mm/slab_common.c:671",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:create_kmalloc_caches",
        "mm/slab_common.c:new_kmalloc_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615378173,
      "name": "create_kmalloc_cache",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 160
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
struct kmem_cache * create_kmalloc_cache(const char * name, unsigned int size, slab_flags_t flags, unsigned int useroffset, unsigned int usersize)
```

```json
{
  "name": "create_kmalloc_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071617167137,
      "name": "create_kmalloc_cache",
      "external": true,
      "loc": "mm/slab_common.c:671",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:new_kmalloc_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071617167137,
      "name": "create_kmalloc_cache",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 172
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
struct kmem_cache * create_kmalloc_cache(const char * name, unsigned int size, slab_flags_t flags, unsigned int useroffset, unsigned int usersize)
```

```json
{
  "name": "create_kmalloc_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071627853744,
      "name": "create_kmalloc_cache",
      "external": true,
      "loc": "mm/slab_common.c:662",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:new_kmalloc_cache",
        "mm/slab_common.c:new_kmalloc_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071627853744,
      "name": "create_kmalloc_cache",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 182
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "create_kmalloc_cache",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071619630884,
      "name": "create_kmalloc_cache",
      "external": false,
      "loc": "mm/slab_common.c:661",
      "file": "mm/slab_common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:new_kmalloc_cache"
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
  "name": "create_kmalloc_cache",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071621934873,
      "name": "create_kmalloc_cache",
      "external": false,
      "loc": "mm/slab_common.c:637",
      "file": "mm/slab_common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:new_kmalloc_cache"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct kmem_cache * create_kmalloc_cache(const char * name, unsigned int size, slab_flags_t flags, unsigned int useroffset, unsigned int usersize)
```

```json
{
  "name": "create_kmalloc_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336510952780,
      "name": "create_kmalloc_cache",
      "external": true,
      "loc": "mm/slab_common.c:1074",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:create_kmalloc_caches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336510952780,
      "name": "create_kmalloc_cache",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 188
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
struct kmem_cache * create_kmalloc_cache(const char * name, unsigned int size, slab_flags_t flags, unsigned int useroffset, unsigned int usersize)
```

```json
{
  "name": "create_kmalloc_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3243443468,
      "name": "create_kmalloc_cache",
      "external": true,
      "loc": "mm/slab_common.c:1074",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:create_kmalloc_caches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3243443468,
      "name": "create_kmalloc_cache",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 180
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
struct kmem_cache * create_kmalloc_cache(const char * name, unsigned int size, slab_flags_t flags, unsigned int useroffset, unsigned int usersize)
```

```json
{
  "name": "create_kmalloc_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055302603196,
      "name": "create_kmalloc_cache",
      "external": true,
      "loc": "mm/slab_common.c:1074",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:new_kmalloc_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055302603196,
      "name": "create_kmalloc_cache",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 236
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
struct kmem_cache * create_kmalloc_cache(const char * name, unsigned int size, slab_flags_t flags, unsigned int useroffset, unsigned int usersize)
```

```json
{
  "name": "create_kmalloc_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936270681590,
      "name": "create_kmalloc_cache",
      "external": true,
      "loc": "mm/slab_common.c:1074",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:new_kmalloc_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936270681590,
      "name": "create_kmalloc_cache",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 170
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
struct kmem_cache * create_kmalloc_cache(const char * name, unsigned int size, slab_flags_t flags, unsigned int useroffset, unsigned int usersize)
```

```json
{
  "name": "create_kmalloc_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604820183,
      "name": "create_kmalloc_cache",
      "external": true,
      "loc": "mm/slab_common.c:1074",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:create_kmalloc_caches",
        "mm/slab_common.c:new_kmalloc_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604820183,
      "name": "create_kmalloc_cache",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 170
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
struct kmem_cache * create_kmalloc_cache(const char * name, unsigned int size, slab_flags_t flags, unsigned int useroffset, unsigned int usersize)
```

```json
{
  "name": "create_kmalloc_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604789244,
      "name": "create_kmalloc_cache",
      "external": true,
      "loc": "mm/slab_common.c:1074",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:create_kmalloc_caches",
        "mm/slab_common.c:new_kmalloc_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604789244,
      "name": "create_kmalloc_cache",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 170
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
struct kmem_cache * create_kmalloc_cache(const char * name, unsigned int size, slab_flags_t flags, unsigned int useroffset, unsigned int usersize)
```

```json
{
  "name": "create_kmalloc_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604897367,
      "name": "create_kmalloc_cache",
      "external": true,
      "loc": "mm/slab_common.c:1074",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:create_kmalloc_caches",
        "mm/slab_common.c:new_kmalloc_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604897367,
      "name": "create_kmalloc_cache",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 170
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
struct kmem_cache * create_kmalloc_cache(const char * name, unsigned int size, slab_flags_t flags, unsigned int useroffset, unsigned int usersize)
```

```json
{
  "name": "create_kmalloc_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604918904,
      "name": "create_kmalloc_cache",
      "external": true,
      "loc": "mm/slab_common.c:1074",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:create_kmalloc_caches",
        "mm/slab_common.c:new_kmalloc_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604918904,
      "name": "create_kmalloc_cache",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 170
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
<b>Param type changed. </b>
<code>size_t size</code> ➡️ <code>unsigned int size</code>
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
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
struct kmem_cache * create_kmalloc_cache(const char * name, unsigned int size, slab_flags_t flags, unsigned int useroffset, unsigned int usersize)
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
