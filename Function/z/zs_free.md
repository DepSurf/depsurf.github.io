# Function: <code>zs_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void zs_free(struct zs_pool * pool, long unsigned int handle)
```

```json
{
  "name": "zs_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580966848,
      "name": "zs_free",
      "external": true,
      "loc": "mm/zsmalloc.c:1467",
      "file": "mm/zsmalloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/zsmalloc.c:zs_zpool_free"
      ],
      "caller_func": [
        "mm/zsmalloc.c:zs_zpool_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580966848,
      "name": "zs_free.part.20",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
    },
    {
      "addr": 18446744071580967088,
      "name": "zs_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void zs_free(struct zs_pool * pool, long unsigned int handle)
```

```json
{
  "name": "zs_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581121440,
      "name": "zs_free",
      "external": true,
      "loc": "mm/zsmalloc.c:1620",
      "file": "mm/zsmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_zpool_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581121440,
      "name": "zs_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
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
void zs_free(struct zs_pool * pool, long unsigned int handle)
```

```json
{
  "name": "zs_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581196544,
      "name": "zs_free",
      "external": true,
      "loc": "mm/zsmalloc.c:1580",
      "file": "mm/zsmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_zpool_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581196544,
      "name": "zs_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
void zs_free(struct zs_pool * pool, long unsigned int handle)
```

```json
{
  "name": "zs_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581244064,
      "name": "zs_free",
      "external": true,
      "loc": "mm/zsmalloc.c:1559",
      "file": "mm/zsmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_zpool_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581244064,
      "name": "zs_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 291
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
void zs_free(struct zs_pool * pool, long unsigned int handle)
```

```json
{
  "name": "zs_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581375744,
      "name": "zs_free",
      "external": true,
      "loc": "mm/zsmalloc.c:1563",
      "file": "mm/zsmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_zpool_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581375744,
      "name": "zs_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 291
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
void zs_free(struct zs_pool * pool, long unsigned int handle)
```

```json
{
  "name": "zs_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581525648,
      "name": "zs_free",
      "external": true,
      "loc": "mm/zsmalloc.c:1566",
      "file": "mm/zsmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_zpool_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581525648,
      "name": "zs_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 291
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
void zs_free(struct zs_pool * pool, long unsigned int handle)
```

```json
{
  "name": "zs_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581610496,
      "name": "zs_free",
      "external": true,
      "loc": "mm/zsmalloc.c:1553",
      "file": "mm/zsmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_zpool_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581610496,
      "name": "zs_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 291
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
void zs_free(struct zs_pool * pool, long unsigned int handle)
```

```json
{
  "name": "zs_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581721952,
      "name": "zs_free",
      "external": true,
      "loc": "mm/zsmalloc.c:1543",
      "file": "mm/zsmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_zpool_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581721952,
      "name": "zs_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 303
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
void zs_free(struct zs_pool * pool, long unsigned int handle)
```

```json
{
  "name": "zs_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581795408,
      "name": "zs_free",
      "external": true,
      "loc": "mm/zsmalloc.c:1540",
      "file": "mm/zsmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_zpool_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581795408,
      "name": "zs_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 303
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
void zs_free(struct zs_pool * pool, long unsigned int handle)
```

```json
{
  "name": "zs_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582018480,
      "name": "zs_free",
      "external": true,
      "loc": "mm/zsmalloc.c:1542",
      "file": "mm/zsmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_zpool_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582018480,
      "name": "zs_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 289
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
void zs_free(struct zs_pool * pool, long unsigned int handle)
```

```json
{
  "name": "zs_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582066496,
      "name": "zs_free",
      "external": true,
      "loc": "mm/zsmalloc.c:1491",
      "file": "mm/zsmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_zpool_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582066496,
      "name": "zs_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 289
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
void zs_free(struct zs_pool * pool, long unsigned int handle)
```

```json
{
  "name": "zs_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582092384,
      "name": "zs_free",
      "external": true,
      "loc": "mm/zsmalloc.c:1490",
      "file": "mm/zsmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_zpool_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582092384,
      "name": "zs_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 359
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
void zs_free(struct zs_pool * pool, long unsigned int handle)
```

```json
{
  "name": "zs_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582405184,
      "name": "zs_free",
      "external": true,
      "loc": "mm/zsmalloc.c:1489",
      "file": "mm/zsmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_zpool_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582405184,
      "name": "zs_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 395
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
void zs_free(struct zs_pool * pool, long unsigned int handle)
```

```json
{
  "name": "zs_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582912144,
      "name": "zs_free",
      "external": true,
      "loc": "mm/zsmalloc.c:1491",
      "file": "mm/zsmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_zpool_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582912144,
      "name": "zs_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 294
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
void zs_free(struct zs_pool * pool, long unsigned int handle)
```

```json
{
  "name": "zs_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "zs_free",
      "external": true,
      "loc": "mm/zsmalloc.c:1659",
      "file": "mm/zsmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_zpool_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596049682,
      "name": "zs_free.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071583465568,
      "name": "zs_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
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
void zs_free(struct zs_pool * pool, long unsigned int handle)
```

```json
{
  "name": "zs_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583683344,
      "name": "zs_free",
      "external": true,
      "loc": "mm/zsmalloc.c:1445",
      "file": "mm/zsmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_zpool_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583683344,
      "name": "zs_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 281
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
void zs_free(struct zs_pool * pool, long unsigned int handle)
```

```json
{
  "name": "zs_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583877840,
      "name": "zs_free",
      "external": true,
      "loc": "mm/zsmalloc.c:1448",
      "file": "mm/zsmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_zpool_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583877840,
      "name": "zs_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 281
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
void zs_free(struct zs_pool * pool, long unsigned int handle)
```

```json
{
  "name": "zs_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493258208,
      "name": "zs_free",
      "external": true,
      "loc": "mm/zsmalloc.c:1540",
      "file": "mm/zsmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_zpool_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493258208,
      "name": "zs_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 580
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
void zs_free(struct zs_pool * pool, long unsigned int handle)
```

```json
{
  "name": "zs_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226869928,
      "name": "zs_free",
      "external": true,
      "loc": "mm/zsmalloc.c:1540",
      "file": "mm/zsmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_zpool_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226869928,
      "name": "zs_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 540
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
void zs_free(struct zs_pool * pool, long unsigned int handle)
```

```json
{
  "name": "zs_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286786144,
      "name": "zs_free",
      "external": true,
      "loc": "mm/zsmalloc.c:1540",
      "file": "mm/zsmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_zpool_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286786144,
      "name": "zs_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 580
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
void zs_free(struct zs_pool * pool, long unsigned int handle)
```

```json
{
  "name": "zs_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273014782,
      "name": "zs_free",
      "external": true,
      "loc": "mm/zsmalloc.c:1540",
      "file": "mm/zsmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_zpool_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273014782,
      "name": "zs_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 380
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
void zs_free(struct zs_pool * pool, long unsigned int handle)
```

```json
{
  "name": "zs_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581764144,
      "name": "zs_free",
      "external": true,
      "loc": "mm/zsmalloc.c:1540",
      "file": "mm/zsmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_zpool_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581764144,
      "name": "zs_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 303
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
void zs_free(struct zs_pool * pool, long unsigned int handle)
```

```json
{
  "name": "zs_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581702768,
      "name": "zs_free",
      "external": true,
      "loc": "mm/zsmalloc.c:1540",
      "file": "mm/zsmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_zpool_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581702768,
      "name": "zs_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 303
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
void zs_free(struct zs_pool * pool, long unsigned int handle)
```

```json
{
  "name": "zs_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581755456,
      "name": "zs_free",
      "external": true,
      "loc": "mm/zsmalloc.c:1540",
      "file": "mm/zsmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_zpool_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581755456,
      "name": "zs_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 303
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
void zs_free(struct zs_pool * pool, long unsigned int handle)
```

```json
{
  "name": "zs_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581826992,
      "name": "zs_free",
      "external": true,
      "loc": "mm/zsmalloc.c:1540",
      "file": "mm/zsmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_zpool_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581826992,
      "name": "zs_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 350
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
