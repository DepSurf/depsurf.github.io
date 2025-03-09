# Function: <code>__kmem_cache_shutdown</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int __kmem_cache_shutdown(struct kmem_cache * s)
```

```json
{
  "name": "__kmem_cache_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580868272,
      "name": "__kmem_cache_shutdown",
      "external": true,
      "loc": "mm/slub.c:3482",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:kmem_cache_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580868272,
      "name": "__kmem_cache_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 688
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
int __kmem_cache_shutdown(struct kmem_cache * s)
```

```json
{
  "name": "__kmem_cache_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580996464,
      "name": "__kmem_cache_shutdown",
      "external": true,
      "loc": "mm/slub.c:3655",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:kmem_cache_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580996464,
      "name": "__kmem_cache_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 847
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
int __kmem_cache_shutdown(struct kmem_cache * s)
```

```json
{
  "name": "__kmem_cache_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581070288,
      "name": "__kmem_cache_shutdown",
      "external": true,
      "loc": "mm/slub.c:3677",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:kmem_cache_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581070288,
      "name": "__kmem_cache_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 843
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
int __kmem_cache_shutdown(struct kmem_cache * s)
```

```json
{
  "name": "__kmem_cache_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581117328,
      "name": "__kmem_cache_shutdown",
      "external": true,
      "loc": "mm/slub.c:3681",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:shutdown_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581117328,
      "name": "__kmem_cache_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 946
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
int __kmem_cache_shutdown(struct kmem_cache * s)
```

```json
{
  "name": "__kmem_cache_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581229712,
      "name": "__kmem_cache_shutdown",
      "external": true,
      "loc": "mm/slub.c:3697",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:shutdown_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581229712,
      "name": "__kmem_cache_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 946
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
int __kmem_cache_shutdown(struct kmem_cache * s)
```

```json
{
  "name": "__kmem_cache_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__kmem_cache_shutdown",
      "external": true,
      "loc": "mm/slub.c:3688",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:shutdown_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581381142,
      "name": "__kmem_cache_shutdown.cold.99",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 313
    },
    {
      "addr": 18446744071581374304,
      "name": "__kmem_cache_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 603
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
int __kmem_cache_shutdown(struct kmem_cache * s)
```

```json
{
  "name": "__kmem_cache_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__kmem_cache_shutdown",
      "external": true,
      "loc": "mm/slub.c:3739",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:shutdown_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581465258,
      "name": "__kmem_cache_shutdown.cold.101",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 310
    },
    {
      "addr": 18446744071581458480,
      "name": "__kmem_cache_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 584
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
int __kmem_cache_shutdown(struct kmem_cache * s)
```

```json
{
  "name": "__kmem_cache_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__kmem_cache_shutdown",
      "external": true,
      "loc": "mm/slub.c:3746",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581579766,
      "name": "__kmem_cache_shutdown.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 291
    },
    {
      "addr": 18446744071581572704,
      "name": "__kmem_cache_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 571
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
int __kmem_cache_shutdown(struct kmem_cache * s)
```

```json
{
  "name": "__kmem_cache_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__kmem_cache_shutdown",
      "external": true,
      "loc": "mm/slub.c:3756",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:shutdown_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581644911,
      "name": "__kmem_cache_shutdown.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 291
    },
    {
      "addr": 18446744071581637920,
      "name": "__kmem_cache_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 571
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
int __kmem_cache_shutdown(struct kmem_cache * s)
```

```json
{
  "name": "__kmem_cache_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581854656,
      "name": "__kmem_cache_shutdown",
      "external": true,
      "loc": "mm/slub.c:3833",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:shutdown_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581854656,
      "name": "__kmem_cache_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
int __kmem_cache_shutdown(struct kmem_cache * s)
```

```json
{
  "name": "__kmem_cache_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581903296,
      "name": "__kmem_cache_shutdown",
      "external": true,
      "loc": "mm/slub.c:3921",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:kmem_cache_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581903296,
      "name": "__kmem_cache_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
int __kmem_cache_shutdown(struct kmem_cache * s)
```

```json
{
  "name": "__kmem_cache_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__kmem_cache_shutdown",
      "external": true,
      "loc": "mm/slub.c:3948",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:kmem_cache_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591279130,
      "name": "__kmem_cache_shutdown.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 303
    },
    {
      "addr": 18446744071581934176,
      "name": "__kmem_cache_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 443
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
int __kmem_cache_shutdown(struct kmem_cache * s)
```

```json
{
  "name": "__kmem_cache_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__kmem_cache_shutdown",
      "external": true,
      "loc": "mm/slub.c:4286",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:kmem_cache_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592221715,
      "name": "__kmem_cache_shutdown.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 431
    },
    {
      "addr": 18446744071582232992,
      "name": "__kmem_cache_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 414
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
int __kmem_cache_shutdown(struct kmem_cache * s)
```

```json
{
  "name": "__kmem_cache_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582702048,
      "name": "__kmem_cache_shutdown",
      "external": true,
      "loc": "mm/slub.c:4323",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:kmem_cache_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582702048,
      "name": "__kmem_cache_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
int __kmem_cache_shutdown(struct kmem_cache * s)
```

```json
{
  "name": "__kmem_cache_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583227216,
      "name": "__kmem_cache_shutdown",
      "external": true,
      "loc": "mm/slub.c:4609",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:kmem_cache_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583227216,
      "name": "__kmem_cache_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
int __kmem_cache_shutdown(struct kmem_cache * s)
```

```json
{
  "name": "__kmem_cache_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583446128,
      "name": "__kmem_cache_shutdown",
      "external": true,
      "loc": "mm/slub.c:4624",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:kmem_cache_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583446128,
      "name": "__kmem_cache_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
int __kmem_cache_shutdown(struct kmem_cache * s)
```

```json
{
  "name": "__kmem_cache_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583430336,
      "name": "__kmem_cache_shutdown",
      "external": true,
      "loc": "mm/slub.c:5228",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:kmem_cache_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583430336,
      "name": "__kmem_cache_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
int __kmem_cache_shutdown(struct kmem_cache * s)
```

```json
{
  "name": "__kmem_cache_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493086920,
      "name": "__kmem_cache_shutdown",
      "external": true,
      "loc": "mm/slub.c:3756",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:shutdown_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493086920,
      "name": "__kmem_cache_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 896
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
int __kmem_cache_shutdown(struct kmem_cache * s)
```

```json
{
  "name": "__kmem_cache_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226793908,
      "name": "__kmem_cache_shutdown",
      "external": true,
      "loc": "mm/slub.c:3756",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:shutdown_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226793908,
      "name": "__kmem_cache_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 860
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
int __kmem_cache_shutdown(struct kmem_cache * s)
```

```json
{
  "name": "__kmem_cache_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286534048,
      "name": "__kmem_cache_shutdown",
      "external": true,
      "loc": "mm/slub.c:3756",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:shutdown_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286534048,
      "name": "__kmem_cache_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1216
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
int __kmem_cache_shutdown(struct kmem_cache * s)
```

```json
{
  "name": "__kmem_cache_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272944580,
      "name": "__kmem_cache_shutdown",
      "external": true,
      "loc": "mm/slub.c:3756",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:shutdown_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272944580,
      "name": "__kmem_cache_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 802
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
int __kmem_cache_shutdown(struct kmem_cache * s)
```

```json
{
  "name": "__kmem_cache_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__kmem_cache_shutdown",
      "external": true,
      "loc": "mm/slub.c:3756",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:shutdown_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581613647,
      "name": "__kmem_cache_shutdown.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 291
    },
    {
      "addr": 18446744071581606656,
      "name": "__kmem_cache_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 571
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
int __kmem_cache_shutdown(struct kmem_cache * s)
```

```json
{
  "name": "__kmem_cache_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__kmem_cache_shutdown",
      "external": true,
      "loc": "mm/slub.c:3756",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:shutdown_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581554975,
      "name": "__kmem_cache_shutdown.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 291
    },
    {
      "addr": 18446744071581548000,
      "name": "__kmem_cache_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 560
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
int __kmem_cache_shutdown(struct kmem_cache * s)
```

```json
{
  "name": "__kmem_cache_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__kmem_cache_shutdown",
      "external": true,
      "loc": "mm/slub.c:3756",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:shutdown_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581604959,
      "name": "__kmem_cache_shutdown.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 291
    },
    {
      "addr": 18446744071581597968,
      "name": "__kmem_cache_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 571
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
int __kmem_cache_shutdown(struct kmem_cache * s)
```

```json
{
  "name": "__kmem_cache_shutdown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__kmem_cache_shutdown",
      "external": true,
      "loc": "mm/slub.c:3756",
      "file": "mm/slub.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/slab_common.c:shutdown_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581670938,
      "name": "__kmem_cache_shutdown.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 305
    },
    {
      "addr": 18446744071581663824,
      "name": "__kmem_cache_shutdown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 562
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
