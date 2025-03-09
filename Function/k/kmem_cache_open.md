# Function: <code>kmem_cache_open</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int kmem_cache_open(struct kmem_cache * s, long unsigned int flags)
```

```json
{
  "name": "kmem_cache_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580867120,
      "name": "kmem_cache_open",
      "external": false,
      "loc": "mm/slub.c:3333",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:__kmem_cache_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580867120,
      "name": "kmem_cache_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1144
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
int kmem_cache_open(struct kmem_cache * s, long unsigned int flags)
```

```json
{
  "name": "kmem_cache_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580995264,
      "name": "kmem_cache_open",
      "external": false,
      "loc": "mm/slub.c:3510",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:__kmem_cache_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580995264,
      "name": "kmem_cache_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1140
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
int kmem_cache_open(struct kmem_cache * s, long unsigned int flags)
```

```json
{
  "name": "kmem_cache_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581069088,
      "name": "kmem_cache_open",
      "external": false,
      "loc": "mm/slub.c:3532",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:__kmem_cache_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581069088,
      "name": "kmem_cache_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1151
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
  "name": "kmem_cache_open",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581119964,
      "name": "kmem_cache_open",
      "external": false,
      "loc": "mm/slub.c:3562",
      "file": "mm/slub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/slub.c:__kmem_cache_create"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kmem_cache_open",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581232348,
      "name": "kmem_cache_open",
      "external": false,
      "loc": "mm/slub.c:3575",
      "file": "mm/slub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/slub.c:__kmem_cache_create"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
int kmem_cache_open(struct kmem_cache * s, slab_flags_t flags)
```

```json
{
  "name": "kmem_cache_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kmem_cache_open",
      "external": false,
      "loc": "mm/slub.c:3558",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:__kmem_cache_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581368432,
      "name": "kmem_cache_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1045
    },
    {
      "addr": 18446744071581381026,
      "name": "kmem_cache_open.cold.97",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
int kmem_cache_open(struct kmem_cache * s, slab_flags_t flags)
```

```json
{
  "name": "kmem_cache_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kmem_cache_open",
      "external": false,
      "loc": "mm/slub.c:3611",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:__kmem_cache_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581457296,
      "name": "kmem_cache_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1028
    },
    {
      "addr": 18446744071581465190,
      "name": "kmem_cache_open.cold.100",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int kmem_cache_open(struct kmem_cache * s, slab_flags_t flags)
```

```json
{
  "name": "kmem_cache_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kmem_cache_open",
      "external": false,
      "loc": "mm/slub.c:3622",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:__kmem_cache_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581571536,
      "name": "kmem_cache_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1029
    },
    {
      "addr": 18446744071581579734,
      "name": "kmem_cache_open.cold",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int kmem_cache_open(struct kmem_cache * s, slab_flags_t flags)
```

```json
{
  "name": "kmem_cache_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kmem_cache_open",
      "external": false,
      "loc": "mm/slub.c:3632",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:__kmem_cache_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581636752,
      "name": "kmem_cache_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1029
    },
    {
      "addr": 18446744071581644879,
      "name": "kmem_cache_open.cold",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int kmem_cache_open(struct kmem_cache * s, slab_flags_t flags)
```

```json
{
  "name": "kmem_cache_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581853904,
      "name": "kmem_cache_open",
      "external": false,
      "loc": "mm/slub.c:3710",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:__kmem_cache_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581853904,
      "name": "kmem_cache_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 566
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
int kmem_cache_open(struct kmem_cache * s, slab_flags_t flags)
```

```json
{
  "name": "kmem_cache_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581902560,
      "name": "kmem_cache_open",
      "external": false,
      "loc": "mm/slub.c:3798",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:__kmem_cache_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581902560,
      "name": "kmem_cache_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 553
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
int kmem_cache_open(struct kmem_cache * s, slab_flags_t flags)
```

```json
{
  "name": "kmem_cache_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581933184,
      "name": "kmem_cache_open",
      "external": false,
      "loc": "mm/slub.c:3825",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:__kmem_cache_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581933184,
      "name": "kmem_cache_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 802
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
int kmem_cache_open(struct kmem_cache * s, slab_flags_t flags)
```

```json
{
  "name": "kmem_cache_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582232112,
      "name": "kmem_cache_open",
      "external": false,
      "loc": "mm/slub.c:4162",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:__kmem_cache_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582232112,
      "name": "kmem_cache_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 798
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
int kmem_cache_open(struct kmem_cache * s, slab_flags_t flags)
```

```json
{
  "name": "kmem_cache_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582701312,
      "name": "kmem_cache_open",
      "external": false,
      "loc": "mm/slub.c:4198",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:__kmem_cache_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582701312,
      "name": "kmem_cache_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 632
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
int kmem_cache_open(struct kmem_cache * s, slab_flags_t flags)
```

```json
{
  "name": "kmem_cache_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583226224,
      "name": "kmem_cache_open",
      "external": false,
      "loc": "mm/slub.c:4486",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:__kmem_cache_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583226224,
      "name": "kmem_cache_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 853
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
int kmem_cache_open(struct kmem_cache * s, slab_flags_t flags)
```

```json
{
  "name": "kmem_cache_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583444976,
      "name": "kmem_cache_open",
      "external": false,
      "loc": "mm/slub.c:4501",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:__kmem_cache_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583444976,
      "name": "kmem_cache_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 975
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
int kmem_cache_open(struct kmem_cache * s, slab_flags_t flags)
```

```json
{
  "name": "kmem_cache_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583429184,
      "name": "kmem_cache_open",
      "external": false,
      "loc": "mm/slub.c:5105",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:__kmem_cache_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583429184,
      "name": "kmem_cache_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 975
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
int kmem_cache_open(struct kmem_cache * s, slab_flags_t flags)
```

```json
{
  "name": "kmem_cache_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493085584,
      "name": "kmem_cache_open",
      "external": false,
      "loc": "mm/slub.c:3632",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:__kmem_cache_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493085584,
      "name": "kmem_cache_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1156
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
int kmem_cache_open(struct kmem_cache * s, slab_flags_t flags)
```

```json
{
  "name": "kmem_cache_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226792832,
      "name": "kmem_cache_open",
      "external": false,
      "loc": "mm/slub.c:3632",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:__kmem_cache_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226792832,
      "name": "kmem_cache_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 924
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
int kmem_cache_open(struct kmem_cache * s, slab_flags_t flags)
```

```json
{
  "name": "kmem_cache_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286532432,
      "name": "kmem_cache_open",
      "external": false,
      "loc": "mm/slub.c:3632",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:__kmem_cache_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286532432,
      "name": "kmem_cache_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1384
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
int kmem_cache_open(struct kmem_cache * s, slab_flags_t flags)
```

```json
{
  "name": "kmem_cache_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272943586,
      "name": "kmem_cache_open",
      "external": false,
      "loc": "mm/slub.c:3632",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:__kmem_cache_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272943586,
      "name": "kmem_cache_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 854
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
int kmem_cache_open(struct kmem_cache * s, slab_flags_t flags)
```

```json
{
  "name": "kmem_cache_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kmem_cache_open",
      "external": false,
      "loc": "mm/slub.c:3632",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:__kmem_cache_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581605488,
      "name": "kmem_cache_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1029
    },
    {
      "addr": 18446744071581613615,
      "name": "kmem_cache_open.cold",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int kmem_cache_open(struct kmem_cache * s, slab_flags_t flags)
```

```json
{
  "name": "kmem_cache_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kmem_cache_open",
      "external": false,
      "loc": "mm/slub.c:3632",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:__kmem_cache_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581546832,
      "name": "kmem_cache_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1029
    },
    {
      "addr": 18446744071581554943,
      "name": "kmem_cache_open.cold",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int kmem_cache_open(struct kmem_cache * s, slab_flags_t flags)
```

```json
{
  "name": "kmem_cache_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kmem_cache_open",
      "external": false,
      "loc": "mm/slub.c:3632",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:__kmem_cache_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581596800,
      "name": "kmem_cache_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1029
    },
    {
      "addr": 18446744071581604927,
      "name": "kmem_cache_open.cold",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int kmem_cache_open(struct kmem_cache * s, slab_flags_t flags)
```

```json
{
  "name": "kmem_cache_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kmem_cache_open",
      "external": false,
      "loc": "mm/slub.c:3632",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:__kmem_cache_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581662656,
      "name": "kmem_cache_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1029
    },
    {
      "addr": 18446744071581670906,
      "name": "kmem_cache_open.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
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
int kmem_cache_open(struct kmem_cache * s, long unsigned int flags)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
int kmem_cache_open(struct kmem_cache * s, slab_flags_t flags)
```
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
