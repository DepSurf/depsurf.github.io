# Function: <code>md_bitmap_end_sync</code>

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
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void md_bitmap_end_sync(struct bitmap * bitmap, sector_t offset, sector_t * blocks, int aborted)
```

```json
{
  "name": "md_bitmap_end_sync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587428328,
      "name": "md_bitmap_end_sync",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:1564",
      "file": "drivers/md/md-bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_sync_with_cluster"
      ],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_sync_with_cluster"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587427456,
      "name": "md_bitmap_end_sync.part.21",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    },
    {
      "addr": 18446744071587427632,
      "name": "md_bitmap_end_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void md_bitmap_end_sync(struct bitmap * bitmap, sector_t offset, sector_t * blocks, int aborted)
```

```json
{
  "name": "md_bitmap_end_sync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587700456,
      "name": "md_bitmap_end_sync",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:1565",
      "file": "drivers/md/md-bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_sync_with_cluster"
      ],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_sync_with_cluster"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587699600,
      "name": "md_bitmap_end_sync.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
    },
    {
      "addr": 18446744071587699776,
      "name": "md_bitmap_end_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void md_bitmap_end_sync(struct bitmap * bitmap, sector_t offset, sector_t * blocks, int aborted)
```

```json
{
  "name": "md_bitmap_end_sync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587904744,
      "name": "md_bitmap_end_sync",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:1565",
      "file": "drivers/md/md-bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_sync_with_cluster"
      ],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_sync_with_cluster"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587903888,
      "name": "md_bitmap_end_sync.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
    },
    {
      "addr": 18446744071587904064,
      "name": "md_bitmap_end_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void md_bitmap_end_sync(struct bitmap * bitmap, sector_t offset, sector_t * blocks, int aborted)
```

```json
{
  "name": "md_bitmap_end_sync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588761144,
      "name": "md_bitmap_end_sync",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:1560",
      "file": "drivers/md/md-bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_load",
        "drivers/md/md-bitmap.c:md_bitmap_sync_with_cluster"
      ],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_load",
        "drivers/md/md-bitmap.c:md_bitmap_sync_with_cluster"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588754048,
      "name": "md_bitmap_end_sync.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    },
    {
      "addr": 18446744071588754224,
      "name": "md_bitmap_end_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void md_bitmap_end_sync(struct bitmap * bitmap, sector_t offset, sector_t * blocks, int aborted)
```

```json
{
  "name": "md_bitmap_end_sync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588781368,
      "name": "md_bitmap_end_sync",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:1561",
      "file": "drivers/md/md-bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_load",
        "drivers/md/md-bitmap.c:md_bitmap_sync_with_cluster"
      ],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_load",
        "drivers/md/md-bitmap.c:md_bitmap_sync_with_cluster"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588774272,
      "name": "md_bitmap_end_sync.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    },
    {
      "addr": 18446744071588774448,
      "name": "md_bitmap_end_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void md_bitmap_end_sync(struct bitmap * bitmap, sector_t offset, sector_t * blocks, int aborted)
```

```json
{
  "name": "md_bitmap_end_sync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588664088,
      "name": "md_bitmap_end_sync",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:1561",
      "file": "drivers/md/md-bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_load",
        "drivers/md/md-bitmap.c:md_bitmap_sync_with_cluster"
      ],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_load",
        "drivers/md/md-bitmap.c:md_bitmap_sync_with_cluster"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588661696,
      "name": "md_bitmap_end_sync.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    },
    {
      "addr": 18446744071588661872,
      "name": "md_bitmap_end_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void md_bitmap_end_sync(struct bitmap * bitmap, sector_t offset, sector_t * blocks, int aborted)
```

```json
{
  "name": "md_bitmap_end_sync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589342072,
      "name": "md_bitmap_end_sync",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:1561",
      "file": "drivers/md/md-bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_load",
        "drivers/md/md-bitmap.c:md_bitmap_sync_with_cluster"
      ],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_load",
        "drivers/md/md-bitmap.c:md_bitmap_sync_with_cluster"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589339632,
      "name": "md_bitmap_end_sync.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
    },
    {
      "addr": 18446744071592646062,
      "name": "md_bitmap_end_sync.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071589339824,
      "name": "md_bitmap_end_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void md_bitmap_end_sync(struct bitmap * bitmap, sector_t offset, sector_t * blocks, int aborted)
```

```json
{
  "name": "md_bitmap_end_sync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590816122,
      "name": "md_bitmap_end_sync",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:1562",
      "file": "drivers/md/md-bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_load",
        "drivers/md/md-bitmap.c:md_bitmap_sync_with_cluster",
        "drivers/md/md-bitmap.c:md_bitmap_cond_end_sync"
      ],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_load",
        "drivers/md/md-bitmap.c:md_bitmap_sync_with_cluster",
        "drivers/md/md-bitmap.c:md_bitmap_cond_end_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590814720,
      "name": "md_bitmap_end_sync.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
    },
    {
      "addr": 18446744071594531091,
      "name": "md_bitmap_end_sync.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071590814928,
      "name": "md_bitmap_end_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void md_bitmap_end_sync(struct bitmap * bitmap, sector_t offset, sector_t * blocks, int aborted)
```

```json
{
  "name": "md_bitmap_end_sync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592503258,
      "name": "md_bitmap_end_sync",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:1562",
      "file": "drivers/md/md-bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_load",
        "drivers/md/md-bitmap.c:md_bitmap_sync_with_cluster",
        "drivers/md/md-bitmap.c:md_bitmap_cond_end_sync"
      ],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_load",
        "drivers/md/md-bitmap.c:md_bitmap_sync_with_cluster",
        "drivers/md/md-bitmap.c:md_bitmap_cond_end_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592501776,
      "name": "md_bitmap_end_sync.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
    },
    {
      "addr": 18446744071596310777,
      "name": "md_bitmap_end_sync.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071592502000,
      "name": "md_bitmap_end_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void md_bitmap_end_sync(struct bitmap * bitmap, sector_t offset, sector_t * blocks, int aborted)
```

```json
{
  "name": "md_bitmap_end_sync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592933562,
      "name": "md_bitmap_end_sync",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:1629",
      "file": "drivers/md/md-bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_load",
        "drivers/md/md-bitmap.c:md_bitmap_sync_with_cluster",
        "drivers/md/md-bitmap.c:md_bitmap_cond_end_sync"
      ],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_load",
        "drivers/md/md-bitmap.c:md_bitmap_sync_with_cluster",
        "drivers/md/md-bitmap.c:md_bitmap_cond_end_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592931984,
      "name": "md_bitmap_end_sync.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
    },
    {
      "addr": 18446744071596840144,
      "name": "md_bitmap_end_sync.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071592932208,
      "name": "md_bitmap_end_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void md_bitmap_end_sync(struct bitmap * bitmap, sector_t offset, sector_t * blocks, int aborted)
```

```json
{
  "name": "md_bitmap_end_sync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593683861,
      "name": "md_bitmap_end_sync",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:1633",
      "file": "drivers/md/md-bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_load",
        "drivers/md/md-bitmap.c:md_bitmap_sync_with_cluster",
        "drivers/md/md-bitmap.c:md_bitmap_cond_end_sync"
      ],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_load",
        "drivers/md/md-bitmap.c:md_bitmap_sync_with_cluster",
        "drivers/md/md-bitmap.c:md_bitmap_cond_end_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593682288,
      "name": "md_bitmap_end_sync.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
    },
    {
      "addr": 18446744071597764262,
      "name": "md_bitmap_end_sync.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071593682512,
      "name": "md_bitmap_end_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline, Transformation ❓</summary>

```c
void md_bitmap_end_sync(struct bitmap * bitmap, sector_t offset, sector_t * blocks, int aborted)
```

```json
{
  "name": "md_bitmap_end_sync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336501132008,
      "name": "md_bitmap_end_sync",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:1565",
      "file": "drivers/md/md-bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_sync_with_cluster"
      ],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_sync_with_cluster"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501130912,
      "name": "md_bitmap_end_sync.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 284
    },
    {
      "addr": 18446603336501131200,
      "name": "md_bitmap_end_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
void md_bitmap_end_sync(struct bitmap * bitmap, sector_t offset, sector_t * blocks, int aborted)
```

```json
{
  "name": "md_bitmap_end_sync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3233647832,
      "name": "md_bitmap_end_sync",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:1565",
      "file": "drivers/md/md-bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_sync_with_cluster"
      ],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_sync_with_cluster"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233647368,
      "name": "md_bitmap_end_sync.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
    },
    {
      "addr": 3233647604,
      "name": "md_bitmap_end_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline, Transformation ❓</summary>

```c
void md_bitmap_end_sync(struct bitmap * bitmap, sector_t offset, sector_t * blocks, int aborted)
```

```json
{
  "name": "md_bitmap_end_sync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055294639488,
      "name": "md_bitmap_end_sync",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:1565",
      "file": "drivers/md/md-bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_sync_with_cluster"
      ],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_sync_with_cluster"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294638128,
      "name": "md_bitmap_end_sync.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 316
    },
    {
      "addr": 13835058055294638448,
      "name": "md_bitmap_end_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline, Transformation ❓</summary>

```c
void md_bitmap_end_sync(struct bitmap * bitmap, sector_t offset, sector_t * blocks, int aborted)
```

```json
{
  "name": "md_bitmap_end_sync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277849614,
      "name": "md_bitmap_end_sync",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:1565",
      "file": "drivers/md/md-bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_sync_with_cluster"
      ],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_sync_with_cluster"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277848794,
      "name": "md_bitmap_end_sync.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
    },
    {
      "addr": 18446743936277848982,
      "name": "md_bitmap_end_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void md_bitmap_end_sync(struct bitmap * bitmap, sector_t offset, sector_t * blocks, int aborted)
```

```json
{
  "name": "md_bitmap_end_sync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587535720,
      "name": "md_bitmap_end_sync",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:1565",
      "file": "drivers/md/md-bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_sync_with_cluster"
      ],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_sync_with_cluster"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587534864,
      "name": "md_bitmap_end_sync.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
    },
    {
      "addr": 18446744071587535040,
      "name": "md_bitmap_end_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void md_bitmap_end_sync(struct bitmap * bitmap, sector_t offset, sector_t * blocks, int aborted)
```

```json
{
  "name": "md_bitmap_end_sync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587303864,
      "name": "md_bitmap_end_sync",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:1565",
      "file": "drivers/md/md-bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_sync_with_cluster"
      ],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_sync_with_cluster"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587303008,
      "name": "md_bitmap_end_sync.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
    },
    {
      "addr": 18446744071587303184,
      "name": "md_bitmap_end_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void md_bitmap_end_sync(struct bitmap * bitmap, sector_t offset, sector_t * blocks, int aborted)
```

```json
{
  "name": "md_bitmap_end_sync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587860888,
      "name": "md_bitmap_end_sync",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:1565",
      "file": "drivers/md/md-bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_sync_with_cluster"
      ],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_sync_with_cluster"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587860032,
      "name": "md_bitmap_end_sync.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
    },
    {
      "addr": 18446744071587860208,
      "name": "md_bitmap_end_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void md_bitmap_end_sync(struct bitmap * bitmap, sector_t offset, sector_t * blocks, int aborted)
```

```json
{
  "name": "md_bitmap_end_sync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587974312,
      "name": "md_bitmap_end_sync",
      "external": true,
      "loc": "drivers/md/md-bitmap.c:1565",
      "file": "drivers/md/md-bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/md-bitmap.c:md_bitmap_sync_with_cluster"
      ],
      "caller_func": [
        "drivers/md/md-bitmap.c:md_bitmap_sync_with_cluster"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587973440,
      "name": "md_bitmap_end_sync.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
    },
    {
      "addr": 18446744071587973616,
      "name": "md_bitmap_end_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
void md_bitmap_end_sync(struct bitmap * bitmap, sector_t offset, sector_t * blocks, int aborted)
```
</details>
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
