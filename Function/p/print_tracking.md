# Function: <code>print_tracking</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "print_tracking",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580844000,
      "name": "print_tracking",
      "external": false,
      "loc": "mm/slub.c:575",
      "file": "mm/slub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/slub.c:print_trailer",
        "mm/slub.c:__kmem_cache_shutdown",
        "mm/slub.c:__kmem_cache_create"
      ],
      "caller_func": [
        "mm/slub.c:print_trailer",
        "mm/slub.c:__kmem_cache_shutdown",
        "mm/slub.c:__kmem_cache_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580844000,
      "name": "print_tracking.part.42",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "print_tracking",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580997236,
      "name": "print_tracking",
      "external": false,
      "loc": "mm/slub.c:586",
      "file": "mm/slub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/slub.c:__kmem_cache_shutdown",
        "mm/slub.c:print_trailer"
      ],
      "caller_func": [
        "mm/slub.c:__kmem_cache_shutdown",
        "mm/slub.c:print_trailer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580971616,
      "name": "print_tracking.part.44",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "print_tracking",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581071056,
      "name": "print_tracking",
      "external": false,
      "loc": "mm/slub.c:583",
      "file": "mm/slub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/slub.c:__kmem_cache_shutdown",
        "mm/slub.c:print_trailer"
      ],
      "caller_func": [
        "mm/slub.c:__kmem_cache_shutdown",
        "mm/slub.c:print_trailer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581045392,
      "name": "print_tracking.part.46",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
  "name": "print_tracking",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581118193,
      "name": "print_tracking",
      "external": false,
      "loc": "mm/slub.c:585",
      "file": "mm/slub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/slub.c:__kmem_cache_shutdown",
        "mm/slub.c:print_trailer"
      ],
      "caller_func": [
        "mm/slub.c:__kmem_cache_shutdown",
        "mm/slub.c:print_trailer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581093520,
      "name": "print_tracking.part.46",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
  "name": "print_tracking",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581230577,
      "name": "print_tracking",
      "external": false,
      "loc": "mm/slub.c:620",
      "file": "mm/slub.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/slub.c:__kmem_cache_shutdown",
        "mm/slub.c:print_trailer"
      ],
      "caller_func": [
        "mm/slub.c:__kmem_cache_shutdown",
        "mm/slub.c:print_trailer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581205760,
      "name": "print_tracking.part.46",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
void print_tracking(struct kmem_cache * s, void * object)
```

```json
{
  "name": "print_tracking",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581379318,
      "name": "print_tracking",
      "external": false,
      "loc": "mm/slub.c:605",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:__kmem_cache_shutdown",
        "mm/slub.c:print_trailer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581379318,
      "name": "print_tracking",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
void print_tracking(struct kmem_cache * s, void * object)
```

```json
{
  "name": "print_tracking",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581463430,
      "name": "print_tracking",
      "external": false,
      "loc": "mm/slub.c:610",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:__kmem_cache_shutdown",
        "mm/slub.c:print_trailer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581463430,
      "name": "print_tracking",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
void print_tracking(struct kmem_cache * s, void * object)
```

```json
{
  "name": "print_tracking",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581577579,
      "name": "print_tracking",
      "external": false,
      "loc": "mm/slub.c:602",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:__kmem_cache_shutdown",
        "mm/slub.c:print_trailer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581577579,
      "name": "print_tracking",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
void print_tracking(struct kmem_cache * s, void * object)
```

```json
{
  "name": "print_tracking",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581642795,
      "name": "print_tracking",
      "external": false,
      "loc": "mm/slub.c:602",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:__kmem_cache_shutdown",
        "mm/slub.c:print_trailer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581642795,
      "name": "print_tracking",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
void print_tracking(struct kmem_cache * s, void * object)
```

```json
{
  "name": "print_tracking",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581858177,
      "name": "print_tracking",
      "external": false,
      "loc": "mm/slub.c:637",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:print_trailer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581858177,
      "name": "print_tracking",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
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
void print_tracking(struct kmem_cache * s, void * object)
```

```json
{
  "name": "print_tracking",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "print_tracking",
      "external": true,
      "loc": "mm/slub.c:632",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:build_detached_freelist",
        "mm/slub.c:kmem_cache_free",
        "mm/slub.c:print_trailer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591334576,
      "name": "print_tracking.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    },
    {
      "addr": 18446744071581882176,
      "name": "print_tracking",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void print_tracking(struct kmem_cache * s, void * object)
```

```json
{
  "name": "print_tracking",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "print_tracking",
      "external": true,
      "loc": "mm/slub.c:643",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:__kmem_cache_shutdown",
        "mm/slub.c:build_detached_freelist",
        "mm/slub.c:kmem_cache_free",
        "mm/slub.c:print_trailer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591277610,
      "name": "print_tracking.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    },
    {
      "addr": 18446744071581912848,
      "name": "print_tracking",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void print_tracking(struct kmem_cache * s, void * object)
```

```json
{
  "name": "print_tracking",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "print_tracking",
      "external": true,
      "loc": "mm/slub.c:754",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:__kmem_cache_shutdown",
        "mm/slub.c:build_detached_freelist",
        "mm/slub.c:kmem_cache_free",
        "mm/slub.c:print_trailer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592219407,
      "name": "print_tracking.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    },
    {
      "addr": 18446744071582208480,
      "name": "print_tracking",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void print_tracking(struct kmem_cache * s, void * object)
```

```json
{
  "name": "print_tracking",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "print_tracking",
      "external": true,
      "loc": "mm/slub.c:800",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:free_partial",
        "mm/slub.c:build_detached_freelist",
        "mm/slub.c:kmem_cache_free",
        "mm/slub.c:print_trailer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593998352,
      "name": "print_tracking.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
    },
    {
      "addr": 18446744071582673968,
      "name": "print_tracking",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void print_tracking(struct kmem_cache * s, void * object)
```

```json
{
  "name": "print_tracking",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583203328,
      "name": "print_tracking",
      "external": true,
      "loc": "mm/slub.c:815",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:free_partial",
        "mm/slub.c:print_trailer",
        "mm/slub.c:cache_from_obj"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583203328,
      "name": "print_tracking",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
void print_tracking(struct kmem_cache * s, void * object)
```

```json
{
  "name": "print_tracking",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583421376,
      "name": "print_tracking",
      "external": true,
      "loc": "mm/slub.c:836",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:free_partial",
        "mm/slub.c:print_trailer",
        "mm/slub.c:cache_from_obj"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583421376,
      "name": "print_tracking",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
void print_tracking(struct kmem_cache * s, void * object)
```

```json
{
  "name": "print_tracking",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583398592,
      "name": "print_tracking",
      "external": true,
      "loc": "mm/slub.c:949",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:free_partial",
        "mm/slub.c:build_detached_freelist",
        "mm/slub.c:kmem_cache_free",
        "mm/slub.c:print_trailer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583398592,
      "name": "print_tracking",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
void print_tracking(struct kmem_cache * s, void * object)
```

```json
{
  "name": "print_tracking",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493094364,
      "name": "print_tracking",
      "external": false,
      "loc": "mm/slub.c:602",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:__kmem_cache_shutdown",
        "mm/slub.c:print_trailer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493094364,
      "name": "print_tracking",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
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
void print_tracking(struct kmem_cache * s, void * object)
```

```json
{
  "name": "print_tracking",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226798168,
      "name": "print_tracking",
      "external": false,
      "loc": "mm/slub.c:602",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:__kmem_cache_shutdown",
        "mm/slub.c:print_trailer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226798168,
      "name": "print_tracking",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
void print_tracking(struct kmem_cache * s, void * object)
```

```json
{
  "name": "print_tracking",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286541972,
      "name": "print_tracking",
      "external": false,
      "loc": "mm/slub.c:602",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:__kmem_cache_shutdown",
        "mm/slub.c:print_trailer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286541972,
      "name": "print_tracking",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
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
void print_tracking(struct kmem_cache * s, void * object)
```

```json
{
  "name": "print_tracking",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272948344,
      "name": "print_tracking",
      "external": false,
      "loc": "mm/slub.c:602",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:__kmem_cache_shutdown",
        "mm/slub.c:print_trailer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272948344,
      "name": "print_tracking",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
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
void print_tracking(struct kmem_cache * s, void * object)
```

```json
{
  "name": "print_tracking",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581611531,
      "name": "print_tracking",
      "external": false,
      "loc": "mm/slub.c:602",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:__kmem_cache_shutdown",
        "mm/slub.c:print_trailer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581611531,
      "name": "print_tracking",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
void print_tracking(struct kmem_cache * s, void * object)
```

```json
{
  "name": "print_tracking",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581552859,
      "name": "print_tracking",
      "external": false,
      "loc": "mm/slub.c:602",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:__kmem_cache_shutdown",
        "mm/slub.c:print_trailer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581552859,
      "name": "print_tracking",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
void print_tracking(struct kmem_cache * s, void * object)
```

```json
{
  "name": "print_tracking",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581602843,
      "name": "print_tracking",
      "external": false,
      "loc": "mm/slub.c:602",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:__kmem_cache_shutdown",
        "mm/slub.c:print_trailer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581602843,
      "name": "print_tracking",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
void print_tracking(struct kmem_cache * s, void * object)
```

```json
{
  "name": "print_tracking",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581668811,
      "name": "print_tracking",
      "external": false,
      "loc": "mm/slub.c:602",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slub.c:__kmem_cache_shutdown",
        "mm/slub.c:print_trailer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581668811,
      "name": "print_tracking",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void print_tracking(struct kmem_cache * s, void * object)
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
