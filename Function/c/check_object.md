# Function: <code>check_object</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int check_object(struct kmem_cache * s, struct page * page, void * object, u8 val)
```

```json
{
  "name": "check_object",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580844864,
      "name": "check_object",
      "external": false,
      "loc": "mm/slub.c:813",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:alloc_debug_processing",
        "mm/slub.c:validate_slab",
        "mm/slub.c:validate_slab",
        "mm/slub.c:__free_slab",
        "mm/slub.c:free_debug_processing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580844864,
      "name": "check_object",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 564
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
int check_object(struct kmem_cache * s, struct page * page, void * object, u8 val)
```

```json
{
  "name": "check_object",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580977232,
      "name": "check_object",
      "external": false,
      "loc": "mm/slub.c:833",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:validate_slab",
        "mm/slub.c:validate_slab",
        "mm/slub.c:__free_slab",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:alloc_debug_processing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580977232,
      "name": "check_object",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 639
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
int check_object(struct kmem_cache * s, struct page * page, void * object, u8 val)
```

```json
{
  "name": "check_object",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581051072,
      "name": "check_object",
      "external": false,
      "loc": "mm/slub.c:832",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:validate_slab",
        "mm/slub.c:validate_slab",
        "mm/slub.c:__free_slab",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:alloc_debug_processing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581051072,
      "name": "check_object",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 636
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
int check_object(struct kmem_cache * s, struct page * page, void * object, u8 val)
```

```json
{
  "name": "check_object",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581098736,
      "name": "check_object",
      "external": false,
      "loc": "mm/slub.c:834",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:validate_slab",
        "mm/slub.c:validate_slab",
        "mm/slub.c:__free_slab",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:alloc_debug_processing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581098736,
      "name": "check_object",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 639
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
int check_object(struct kmem_cache * s, struct page * page, void * object, u8 val)
```

```json
{
  "name": "check_object",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581209376,
      "name": "check_object",
      "external": false,
      "loc": "mm/slub.c:869",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:validate_slab",
        "mm/slub.c:validate_slab",
        "mm/slub.c:__free_slab",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:alloc_debug_processing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581209376,
      "name": "check_object",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 672
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
int check_object(struct kmem_cache * s, struct page * page, void * object, u8 val)
```

```json
{
  "name": "check_object",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_object",
      "external": false,
      "loc": "mm/slub.c:857",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:validate_slab",
        "mm/slub.c:validate_slab",
        "mm/slub.c:__free_slab",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:alloc_debug_processing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581355744,
      "name": "check_object",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 650
    },
    {
      "addr": 18446744071581380360,
      "name": "check_object.cold.93",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
int check_object(struct kmem_cache * s, struct page * page, void * object, u8 val)
```

```json
{
  "name": "check_object",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_object",
      "external": false,
      "loc": "mm/slub.c:862",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:validate_slab",
        "mm/slub.c:validate_slab",
        "mm/slub.c:__free_slab",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:alloc_debug_processing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581441040,
      "name": "check_object",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 650
    },
    {
      "addr": 18446744071581464472,
      "name": "check_object.cold.95",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int check_object(struct kmem_cache * s, struct page * page, void * object, u8 val)
```

```json
{
  "name": "check_object",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_object",
      "external": false,
      "loc": "mm/slub.c:854",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:validate_slab",
        "mm/slub.c:validate_slab",
        "mm/slub.c:__free_slab",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:alloc_debug_processing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581554080,
      "name": "check_object",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 609
    },
    {
      "addr": 18446744071581578824,
      "name": "check_object.cold",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int check_object(struct kmem_cache * s, struct page * page, void * object, u8 val)
```

```json
{
  "name": "check_object",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_object",
      "external": false,
      "loc": "mm/slub.c:854",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:validate_slab",
        "mm/slub.c:validate_slab",
        "mm/slub.c:__free_slab",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:alloc_debug_processing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581619072,
      "name": "check_object",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 609
    },
    {
      "addr": 18446744071581644021,
      "name": "check_object.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
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
int check_object(struct kmem_cache * s, struct page * page, void * object, u8 val)
```

```json
{
  "name": "check_object",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_object",
      "external": false,
      "loc": "mm/slub.c:899",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:validate_slab",
        "mm/slub.c:__free_slab",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:alloc_debug_processing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581835280,
      "name": "check_object",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 655
    },
    {
      "addr": 18446744071581859547,
      "name": "check_object.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
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
int check_object(struct kmem_cache * s, struct page * page, void * object, u8 val)
```

```json
{
  "name": "check_object",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_object",
      "external": false,
      "loc": "mm/slub.c:894",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:validate_slab",
        "mm/slub.c:__free_slab",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:alloc_debug_processing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581883232,
      "name": "check_object",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 655
    },
    {
      "addr": 18446744071591335505,
      "name": "check_object.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
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
int check_object(struct kmem_cache * s, struct page * page, void * object, u8 val)
```

```json
{
  "name": "check_object",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_object",
      "external": false,
      "loc": "mm/slub.c:906",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:validate_slab",
        "mm/slub.c:__free_slab",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:alloc_debug_processing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581913856,
      "name": "check_object",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 655
    },
    {
      "addr": 18446744071591278282,
      "name": "check_object.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
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
int check_object(struct kmem_cache * s, struct page * page, void * object, u8 val)
```

```json
{
  "name": "check_object",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_object",
      "external": false,
      "loc": "mm/slub.c:1032",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:validate_slab",
        "mm/slub.c:__free_slab",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:alloc_debug_processing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582209664,
      "name": "check_object",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 622
    },
    {
      "addr": 18446744071592220200,
      "name": "check_object.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
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
int check_object(struct kmem_cache * s, struct slab * slab, void * object, u8 val)
```

```json
{
  "name": "check_object",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_object",
      "external": false,
      "loc": "mm/slub.c:1078",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:validate_slab",
        "mm/slub.c:__free_slab",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:alloc_debug_processing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582674720,
      "name": "check_object",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 658
    },
    {
      "addr": 18446744071593999379,
      "name": "check_object.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
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
int check_object(struct kmem_cache * s, struct slab * slab, void * object, u8 val)
```

```json
{
  "name": "check_object",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583205104,
      "name": "check_object",
      "external": false,
      "loc": "mm/slub.c:1161",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:validate_slab",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:free_slab",
        "mm/slub.c:alloc_debug_processing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583205104,
      "name": "check_object",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 936
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
int check_object(struct kmem_cache * s, struct slab * slab, void * object, u8 val)
```

```json
{
  "name": "check_object",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583423152,
      "name": "check_object",
      "external": false,
      "loc": "mm/slub.c:1182",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:validate_slab",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:free_slab",
        "mm/slub.c:alloc_debug_processing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583423152,
      "name": "check_object",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 869
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
int check_object(struct kmem_cache * s, struct slab * slab, void * object, u8 val)
```

```json
{
  "name": "check_object",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583400368,
      "name": "check_object",
      "external": false,
      "loc": "mm/slub.c:1295",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:validate_slab",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:free_slab",
        "mm/slub.c:alloc_debug_processing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583400368,
      "name": "check_object",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 878
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
int check_object(struct kmem_cache * s, struct page * page, void * object, u8 val)
```

```json
{
  "name": "check_object",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493064592,
      "name": "check_object",
      "external": false,
      "loc": "mm/slub.c:854",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:validate_slab_slab",
        "mm/slub.c:validate_slab_slab",
        "mm/slub.c:__free_slab",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:alloc_debug_processing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493064592,
      "name": "check_object",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 692
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
int check_object(struct kmem_cache * s, struct page * page, void * object, u8 val)
```

```json
{
  "name": "check_object",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226774988,
      "name": "check_object",
      "external": false,
      "loc": "mm/slub.c:854",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:validate_slab_slab",
        "mm/slub.c:validate_slab_slab",
        "mm/slub.c:__free_slab",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:alloc_debug_processing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226774988,
      "name": "check_object",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 668
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
int check_object(struct kmem_cache * s, struct page * page, void * object, u8 val)
```

```json
{
  "name": "check_object",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286505424,
      "name": "check_object",
      "external": false,
      "loc": "mm/slub.c:854",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:validate_slab",
        "mm/slub.c:validate_slab",
        "mm/slub.c:__free_slab",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:alloc_debug_processing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286505424,
      "name": "check_object",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 900
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
int check_object(struct kmem_cache * s, struct page * page, void * object, u8 val)
```

```json
{
  "name": "check_object",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272928994,
      "name": "check_object",
      "external": false,
      "loc": "mm/slub.c:854",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:validate_slab_slab",
        "mm/slub.c:validate_slab_slab",
        "mm/slub.c:__free_slab",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:alloc_debug_processing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272928994,
      "name": "check_object",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 570
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
int check_object(struct kmem_cache * s, struct page * page, void * object, u8 val)
```

```json
{
  "name": "check_object",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_object",
      "external": false,
      "loc": "mm/slub.c:854",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:validate_slab",
        "mm/slub.c:validate_slab",
        "mm/slub.c:__free_slab",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:alloc_debug_processing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581587808,
      "name": "check_object",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 609
    },
    {
      "addr": 18446744071581612757,
      "name": "check_object.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
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
int check_object(struct kmem_cache * s, struct page * page, void * object, u8 val)
```

```json
{
  "name": "check_object",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_object",
      "external": false,
      "loc": "mm/slub.c:854",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:validate_slab",
        "mm/slub.c:validate_slab",
        "mm/slub.c:__free_slab",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:alloc_debug_processing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581529328,
      "name": "check_object",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 609
    },
    {
      "addr": 18446744071581554085,
      "name": "check_object.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
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
int check_object(struct kmem_cache * s, struct page * page, void * object, u8 val)
```

```json
{
  "name": "check_object",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_object",
      "external": false,
      "loc": "mm/slub.c:854",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:validate_slab",
        "mm/slub.c:validate_slab",
        "mm/slub.c:__free_slab",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:alloc_debug_processing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581579120,
      "name": "check_object",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 609
    },
    {
      "addr": 18446744071581604069,
      "name": "check_object.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
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
int check_object(struct kmem_cache * s, struct page * page, void * object, u8 val)
```

```json
{
  "name": "check_object",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_object",
      "external": false,
      "loc": "mm/slub.c:854",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:validate_slab_slab",
        "mm/slub.c:validate_slab_slab",
        "mm/slub.c:__free_slab",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:alloc_debug_processing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581644368,
      "name": "check_object",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 609
    },
    {
      "addr": 18446744071581670037,
      "name": "check_object.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
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
