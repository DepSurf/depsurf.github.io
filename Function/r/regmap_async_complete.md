# Function: <code>regmap_async_complete</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int regmap_async_complete(struct regmap * map)
```

```json
{
  "name": "regmap_async_complete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584492352,
      "name": "regmap_async_complete",
      "external": true,
      "loc": "drivers/base/regmap/regmap.c:2731",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_register_patch",
        "drivers/base/regmap/regcache.c:regcache_sync",
        "drivers/base/regmap/regcache.c:regcache_sync_region",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584492352,
      "name": "regmap_async_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 463
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
int regmap_async_complete(struct regmap * map)
```

```json
{
  "name": "regmap_async_complete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584838992,
      "name": "regmap_async_complete",
      "external": true,
      "loc": "drivers/base/regmap/regmap.c:2737",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_register_patch",
        "drivers/base/regmap/regcache.c:regcache_sync_region",
        "drivers/base/regmap/regcache.c:regcache_sync",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584838992,
      "name": "regmap_async_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 435
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
int regmap_async_complete(struct regmap * map)
```

```json
{
  "name": "regmap_async_complete",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585032352,
      "name": "regmap_async_complete",
      "external": true,
      "loc": "drivers/base/regmap/regmap.c:2775",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_register_patch",
        "drivers/base/regmap/regcache.c:regcache_sync_region",
        "drivers/base/regmap/regcache.c:regcache_sync",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585032352,
      "name": "regmap_async_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 424
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int regmap_async_complete(struct regmap * map)
```

```json
{
  "name": "regmap_async_complete",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585135045,
      "name": "regmap_async_complete",
      "external": true,
      "loc": "drivers/base/regmap/regmap.c:2782",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap.c:regmap_register_patch"
      ],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_register_patch",
        "drivers/base/regmap/regcache.c:regcache_sync_region",
        "drivers/base/regmap/regcache.c:regcache_sync",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585116784,
      "name": "regmap_async_complete.part.23",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 399
    },
    {
      "addr": 18446744071585117184,
      "name": "regmap_async_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int regmap_async_complete(struct regmap * map)
```

```json
{
  "name": "regmap_async_complete",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585561825,
      "name": "regmap_async_complete",
      "external": true,
      "loc": "drivers/base/regmap/regmap.c:2861",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap.c:regmap_register_patch"
      ],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_register_patch",
        "drivers/base/regmap/regcache.c:regcache_sync_region",
        "drivers/base/regmap/regcache.c:regcache_sync",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585543216,
      "name": "regmap_async_complete.part.23",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 405
    },
    {
      "addr": 18446744071585543632,
      "name": "regmap_async_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int regmap_async_complete(struct regmap * map)
```

```json
{
  "name": "regmap_async_complete",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585804913,
      "name": "regmap_async_complete",
      "external": true,
      "loc": "drivers/base/regmap/regmap.c:2816",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap.c:regmap_register_patch"
      ],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_register_patch",
        "drivers/base/regmap/regcache.c:regcache_sync_region",
        "drivers/base/regmap/regcache.c:regcache_sync",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585787216,
      "name": "regmap_async_complete.part.23",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 405
    },
    {
      "addr": 18446744071585787632,
      "name": "regmap_async_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int regmap_async_complete(struct regmap * map)
```

```json
{
  "name": "regmap_async_complete",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585938577,
      "name": "regmap_async_complete",
      "external": true,
      "loc": "drivers/base/regmap/regmap.c:2976",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap.c:regmap_register_patch"
      ],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_register_patch",
        "drivers/base/regmap/regcache.c:regcache_sync_region",
        "drivers/base/regmap/regcache.c:regcache_sync",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585920288,
      "name": "regmap_async_complete.part.25",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 405
    },
    {
      "addr": 18446744071585920704,
      "name": "regmap_async_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int regmap_async_complete(struct regmap * map)
```

```json
{
  "name": "regmap_async_complete",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586179888,
      "name": "regmap_async_complete",
      "external": true,
      "loc": "drivers/base/regmap/regmap.c:2973",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap.c:regmap_register_patch"
      ],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_register_patch",
        "drivers/base/regmap/regcache.c:regcache_sync_region",
        "drivers/base/regmap/regcache.c:regcache_sync",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586162128,
      "name": "regmap_async_complete.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 408
    },
    {
      "addr": 18446744071586162544,
      "name": "regmap_async_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int regmap_async_complete(struct regmap * map)
```

```json
{
  "name": "regmap_async_complete",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586328400,
      "name": "regmap_async_complete",
      "external": true,
      "loc": "drivers/base/regmap/regmap.c:2980",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap.c:regmap_register_patch"
      ],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_register_patch",
        "drivers/base/regmap/regcache.c:regcache_sync_region",
        "drivers/base/regmap/regcache.c:regcache_sync",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586310528,
      "name": "regmap_async_complete.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 408
    },
    {
      "addr": 18446744071586310944,
      "name": "regmap_async_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int regmap_async_complete(struct regmap * map)
```

```json
{
  "name": "regmap_async_complete",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587098864,
      "name": "regmap_async_complete",
      "external": true,
      "loc": "drivers/base/regmap/regmap.c:2998",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap.c:regmap_register_patch"
      ],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_register_patch",
        "drivers/base/regmap/regcache.c:regcache_sync_region",
        "drivers/base/regmap/regcache.c:regcache_sync",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587082656,
      "name": "regmap_async_complete.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 408
    },
    {
      "addr": 18446744071587083072,
      "name": "regmap_async_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int regmap_async_complete(struct regmap * map)
```

```json
{
  "name": "regmap_async_complete",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587185088,
      "name": "regmap_async_complete",
      "external": true,
      "loc": "drivers/base/regmap/regmap.c:3155",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap.c:regmap_register_patch"
      ],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_register_patch",
        "drivers/base/regmap/regcache.c:regcache_sync_region",
        "drivers/base/regmap/regcache.c:regcache_sync",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587168880,
      "name": "regmap_async_complete.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 380
    },
    {
      "addr": 18446744071587169264,
      "name": "regmap_async_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int regmap_async_complete(struct regmap * map)
```

```json
{
  "name": "regmap_async_complete",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587072560,
      "name": "regmap_async_complete",
      "external": true,
      "loc": "drivers/base/regmap/regmap.c:3155",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap.c:regmap_register_patch"
      ],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_register_patch",
        "drivers/base/regmap/regcache.c:regcache_sync_region",
        "drivers/base/regmap/regcache.c:regcache_sync",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587054128,
      "name": "regmap_async_complete.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 380
    },
    {
      "addr": 18446744071587054512,
      "name": "regmap_async_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int regmap_async_complete(struct regmap * map)
```

```json
{
  "name": "regmap_async_complete",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587643788,
      "name": "regmap_async_complete",
      "external": true,
      "loc": "drivers/base/regmap/regmap.c:3196",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap.c:regmap_register_patch"
      ],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_register_patch",
        "drivers/base/regmap/regcache.c:regcache_sync_region",
        "drivers/base/regmap/regcache.c:regcache_sync",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587624288,
      "name": "regmap_async_complete.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 377
    },
    {
      "addr": 18446744071587624672,
      "name": "regmap_async_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int regmap_async_complete(struct regmap * map)
```

```json
{
  "name": "regmap_async_complete",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588987858,
      "name": "regmap_async_complete",
      "external": true,
      "loc": "drivers/base/regmap/regmap.c:3213",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap.c:regmap_register_patch"
      ],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_register_patch",
        "drivers/base/regmap/regcache.c:regcache_sync_region",
        "drivers/base/regmap/regcache.c:regcache_sync",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588969312,
      "name": "regmap_async_complete.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 473
    },
    {
      "addr": 18446744071588969792,
      "name": "regmap_async_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
int regmap_async_complete(struct regmap * map)
```

```json
{
  "name": "regmap_async_complete",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590509024,
      "name": "regmap_async_complete",
      "external": true,
      "loc": "drivers/base/regmap/regmap.c:3367",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap.c:regmap_register_patch"
      ],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_register_patch",
        "drivers/base/regmap/regcache.c:regcache_sync_region",
        "drivers/base/regmap/regcache.c:regcache_sync",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590489152,
      "name": "regmap_async_complete.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 473
    },
    {
      "addr": 18446744071590489648,
      "name": "regmap_async_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
int regmap_async_complete(struct regmap * map)
```

```json
{
  "name": "regmap_async_complete",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590833156,
      "name": "regmap_async_complete",
      "external": true,
      "loc": "drivers/base/regmap/regmap.c:3396",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap.c:regmap_register_patch"
      ],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_register_patch",
        "drivers/base/regmap/regcache.c:regcache_sync_region",
        "drivers/base/regmap/regcache.c:regcache_sync",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590811712,
      "name": "regmap_async_complete.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 473
    },
    {
      "addr": 18446744071590812208,
      "name": "regmap_async_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
int regmap_async_complete(struct regmap * map)
```

```json
{
  "name": "regmap_async_complete",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591176196,
      "name": "regmap_async_complete",
      "external": true,
      "loc": "drivers/base/regmap/regmap.c:3276",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap.c:regmap_register_patch"
      ],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_register_patch",
        "drivers/base/regmap/regcache.c:regcache_sync_region",
        "drivers/base/regmap/regcache.c:regcache_sync",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591154944,
      "name": "regmap_async_complete.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 473
    },
    {
      "addr": 18446744071591155440,
      "name": "regmap_async_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
int regmap_async_complete(struct regmap * map)
```

```json
{
  "name": "regmap_async_complete",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499165448,
      "name": "regmap_async_complete",
      "external": true,
      "loc": "drivers/base/regmap/regmap.c:2980",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap.c:regmap_register_patch"
      ],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_register_patch",
        "drivers/base/regmap/regcache.c:regcache_sync_region",
        "drivers/base/regmap/regcache.c:regcache_sync",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499148272,
      "name": "regmap_async_complete.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 528
    },
    {
      "addr": 18446603336499148800,
      "name": "regmap_async_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
int regmap_async_complete(struct regmap * map)
```

```json
{
  "name": "regmap_async_complete",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231700860,
      "name": "regmap_async_complete",
      "external": true,
      "loc": "drivers/base/regmap/regmap.c:2980",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap.c:regmap_register_patch"
      ],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_register_patch",
        "drivers/base/regmap/regcache.c:regcache_sync_region",
        "drivers/base/regmap/regcache.c:regcache_sync",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync",
        "sound/soc/soc-io.c:snd_soc_component_async_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231681804,
      "name": "regmap_async_complete.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 492
    },
    {
      "addr": 3231682296,
      "name": "regmap_async_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
int regmap_async_complete(struct regmap * map)
```

```json
{
  "name": "regmap_async_complete",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055292365264,
      "name": "regmap_async_complete",
      "external": true,
      "loc": "drivers/base/regmap/regmap.c:2980",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap.c:regmap_register_patch"
      ],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_register_patch",
        "drivers/base/regmap/regcache.c:regcache_sync_region",
        "drivers/base/regmap/regcache.c:regcache_sync",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292339472,
      "name": "regmap_async_complete.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 628
    },
    {
      "addr": 13835058055292340112,
      "name": "regmap_async_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
int regmap_async_complete(struct regmap * map)
```

```json
{
  "name": "regmap_async_complete",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276463876,
      "name": "regmap_async_complete",
      "external": true,
      "loc": "drivers/base/regmap/regmap.c:2980",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap.c:regmap_register_patch"
      ],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_register_patch",
        "drivers/base/regmap/regcache.c:regcache_sync_region",
        "drivers/base/regmap/regcache.c:regcache_sync",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276449310,
      "name": "regmap_async_complete.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 390
    },
    {
      "addr": 18446743936276449700,
      "name": "regmap_async_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
int regmap_async_complete(struct regmap * map)
```

```json
{
  "name": "regmap_async_complete",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586091648,
      "name": "regmap_async_complete",
      "external": true,
      "loc": "drivers/base/regmap/regmap.c:2980",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap.c:regmap_register_patch"
      ],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_register_patch",
        "drivers/base/regmap/regcache.c:regcache_sync_region",
        "drivers/base/regmap/regcache.c:regcache_sync",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586073776,
      "name": "regmap_async_complete.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 408
    },
    {
      "addr": 18446744071586074192,
      "name": "regmap_async_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int regmap_async_complete(struct regmap * map)
```

```json
{
  "name": "regmap_async_complete",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585937600,
      "name": "regmap_async_complete",
      "external": true,
      "loc": "drivers/base/regmap/regmap.c:2980",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap.c:regmap_register_patch"
      ],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_register_patch",
        "drivers/base/regmap/regcache.c:regcache_sync_region",
        "drivers/base/regmap/regcache.c:regcache_sync",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585919728,
      "name": "regmap_async_complete.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 408
    },
    {
      "addr": 18446744071585920144,
      "name": "regmap_async_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int regmap_async_complete(struct regmap * map)
```

```json
{
  "name": "regmap_async_complete",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586276368,
      "name": "regmap_async_complete",
      "external": true,
      "loc": "drivers/base/regmap/regmap.c:2980",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap.c:regmap_register_patch"
      ],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_register_patch",
        "drivers/base/regmap/regcache.c:regcache_sync_region",
        "drivers/base/regmap/regcache.c:regcache_sync",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586258496,
      "name": "regmap_async_complete.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 408
    },
    {
      "addr": 18446744071586258912,
      "name": "regmap_async_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int regmap_async_complete(struct regmap * map)
```

```json
{
  "name": "regmap_async_complete",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586387632,
      "name": "regmap_async_complete",
      "external": true,
      "loc": "drivers/base/regmap/regmap.c:2980",
      "file": "drivers/base/regmap/regmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap.c:regmap_register_patch"
      ],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_register_patch",
        "drivers/base/regmap/regcache.c:regcache_sync_region",
        "drivers/base/regmap/regcache.c:regcache_sync",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586369472,
      "name": "regmap_async_complete.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 457
    },
    {
      "addr": 18446744071586369936,
      "name": "regmap_async_complete",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
