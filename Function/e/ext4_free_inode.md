# Function: <code>ext4_free_inode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void ext4_free_inode(handle_t * handle, struct inode * inode)
```

```json
{
  "name": "ext4_free_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581547472,
      "name": "ext4_free_inode",
      "external": true,
      "loc": "fs/ext4/ialloc.c:253",
      "file": "fs/ext4/ialloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581547472,
      "name": "ext4_free_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1621
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
void ext4_free_inode(handle_t * handle, struct inode * inode)
```

```json
{
  "name": "ext4_free_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581733248,
      "name": "ext4_free_inode",
      "external": true,
      "loc": "fs/ext4/ialloc.c:253",
      "file": "fs/ext4/ialloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581733248,
      "name": "ext4_free_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1592
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
void ext4_free_inode(handle_t * handle, struct inode * inode)
```

```json
{
  "name": "ext4_free_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581820848,
      "name": "ext4_free_inode",
      "external": true,
      "loc": "fs/ext4/ialloc.c:253",
      "file": "fs/ext4/ialloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581820848,
      "name": "ext4_free_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1594
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
void ext4_free_inode(handle_t * handle, struct inode * inode)
```

```json
{
  "name": "ext4_free_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581944464,
      "name": "ext4_free_inode",
      "external": true,
      "loc": "fs/ext4/ialloc.c:255",
      "file": "fs/ext4/ialloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581944464,
      "name": "ext4_free_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1558
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
void ext4_free_inode(handle_t * handle, struct inode * inode)
```

```json
{
  "name": "ext4_free_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582093856,
      "name": "ext4_free_inode",
      "external": true,
      "loc": "fs/ext4/ialloc.c:256",
      "file": "fs/ext4/ialloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582093856,
      "name": "ext4_free_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1499
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
void ext4_free_inode(handle_t * handle, struct inode * inode)
```

```json
{
  "name": "ext4_free_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_free_inode",
      "external": true,
      "loc": "fs/ext4/ialloc.c:231",
      "file": "fs/ext4/ialloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582290523,
      "name": "ext4_free_inode.cold.25",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071582281792,
      "name": "ext4_free_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1388
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
void ext4_free_inode(handle_t * handle, struct inode * inode)
```

```json
{
  "name": "ext4_free_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_free_inode",
      "external": true,
      "loc": "fs/ext4/ialloc.c:231",
      "file": "fs/ext4/ialloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582389275,
      "name": "ext4_free_inode.cold.26",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071582380528,
      "name": "ext4_free_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1388
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
void ext4_free_inode(handle_t * handle, struct inode * inode)
```

```json
{
  "name": "ext4_free_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_free_inode",
      "external": true,
      "loc": "fs/ext4/ialloc.c:231",
      "file": "fs/ext4/ialloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582557339,
      "name": "ext4_free_inode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071582548960,
      "name": "ext4_free_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1323
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
void ext4_free_inode(handle_t * handle, struct inode * inode)
```

```json
{
  "name": "ext4_free_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_free_inode",
      "external": true,
      "loc": "fs/ext4/ialloc.c:231",
      "file": "fs/ext4/ialloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582658278,
      "name": "ext4_free_inode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071582649760,
      "name": "ext4_free_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1306
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
void ext4_free_inode(handle_t * handle, struct inode * inode)
```

```json
{
  "name": "ext4_free_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_free_inode",
      "external": true,
      "loc": "fs/ext4/ialloc.c:233",
      "file": "fs/ext4/ialloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582969879,
      "name": "ext4_free_inode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071582961680,
      "name": "ext4_free_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1324
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
void ext4_free_inode(handle_t * handle, struct inode * inode)
```

```json
{
  "name": "ext4_free_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_free_inode",
      "external": true,
      "loc": "fs/ext4/ialloc.c:235",
      "file": "fs/ext4/ialloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591347042,
      "name": "ext4_free_inode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071583035872,
      "name": "ext4_free_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1342
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
void ext4_free_inode(handle_t * handle, struct inode * inode)
```

```json
{
  "name": "ext4_free_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_free_inode",
      "external": true,
      "loc": "fs/ext4/ialloc.c:235",
      "file": "fs/ext4/ialloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591289869,
      "name": "ext4_free_inode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071583061360,
      "name": "ext4_free_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1373
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
void ext4_free_inode(handle_t * handle, struct inode * inode)
```

```json
{
  "name": "ext4_free_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_free_inode",
      "external": true,
      "loc": "fs/ext4/ialloc.c:235",
      "file": "fs/ext4/ialloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592256202,
      "name": "ext4_free_inode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
    },
    {
      "addr": 18446744071583399328,
      "name": "ext4_free_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1409
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
void ext4_free_inode(handle_t * handle, struct inode * inode)
```

```json
{
  "name": "ext4_free_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_free_inode",
      "external": true,
      "loc": "fs/ext4/ialloc.c:235",
      "file": "fs/ext4/ialloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594037250,
      "name": "ext4_free_inode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    },
    {
      "addr": 18446744071583914240,
      "name": "ext4_free_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1517
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
void ext4_free_inode(handle_t * handle, struct inode * inode)
```

```json
{
  "name": "ext4_free_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_free_inode",
      "external": true,
      "loc": "fs/ext4/ialloc.c:235",
      "file": "fs/ext4/ialloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596070378,
      "name": "ext4_free_inode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    },
    {
      "addr": 18446744071584540304,
      "name": "ext4_free_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1546
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
void ext4_free_inode(handle_t * handle, struct inode * inode)
```

```json
{
  "name": "ext4_free_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_free_inode",
      "external": true,
      "loc": "fs/ext4/ialloc.c:235",
      "file": "fs/ext4/ialloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596593940,
      "name": "ext4_free_inode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    },
    {
      "addr": 18446744071584769344,
      "name": "ext4_free_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1429
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
void ext4_free_inode(handle_t * handle, struct inode * inode)
```

```json
{
  "name": "ext4_free_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_free_inode",
      "external": true,
      "loc": "fs/ext4/ialloc.c:235",
      "file": "fs/ext4/ialloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597499482,
      "name": "ext4_free_inode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    },
    {
      "addr": 18446744071585002432,
      "name": "ext4_free_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1429
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
void ext4_free_inode(handle_t * handle, struct inode * inode)
```

```json
{
  "name": "ext4_free_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494302624,
      "name": "ext4_free_inode",
      "external": true,
      "loc": "fs/ext4/ialloc.c:231",
      "file": "fs/ext4/ialloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494302624,
      "name": "ext4_free_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1452
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
void ext4_free_inode(handle_t * handle, struct inode * inode)
```

```json
{
  "name": "ext4_free_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227736824,
      "name": "ext4_free_inode",
      "external": true,
      "loc": "fs/ext4/ialloc.c:231",
      "file": "fs/ext4/ialloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227736824,
      "name": "ext4_free_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1564
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
void ext4_free_inode(handle_t * handle, struct inode * inode)
```

```json
{
  "name": "ext4_free_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288019776,
      "name": "ext4_free_inode",
      "external": true,
      "loc": "fs/ext4/ialloc.c:231",
      "file": "fs/ext4/ialloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288019776,
      "name": "ext4_free_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1916
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
void ext4_free_inode(handle_t * handle, struct inode * inode)
```

```json
{
  "name": "ext4_free_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273743956,
      "name": "ext4_free_inode",
      "external": true,
      "loc": "fs/ext4/ialloc.c:231",
      "file": "fs/ext4/ialloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273743956,
      "name": "ext4_free_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1322
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
void ext4_free_inode(handle_t * handle, struct inode * inode)
```

```json
{
  "name": "ext4_free_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_free_inode",
      "external": true,
      "loc": "fs/ext4/ialloc.c:231",
      "file": "fs/ext4/ialloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582627014,
      "name": "ext4_free_inode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071582618496,
      "name": "ext4_free_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1306
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
void ext4_free_inode(handle_t * handle, struct inode * inode)
```

```json
{
  "name": "ext4_free_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_free_inode",
      "external": true,
      "loc": "fs/ext4/ialloc.c:231",
      "file": "fs/ext4/ialloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582564182,
      "name": "ext4_free_inode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071582555664,
      "name": "ext4_free_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1306
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
void ext4_free_inode(handle_t * handle, struct inode * inode)
```

```json
{
  "name": "ext4_free_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_free_inode",
      "external": true,
      "loc": "fs/ext4/ialloc.c:231",
      "file": "fs/ext4/ialloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582616870,
      "name": "ext4_free_inode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071582608352,
      "name": "ext4_free_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1306
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
void ext4_free_inode(handle_t * handle, struct inode * inode)
```

```json
{
  "name": "ext4_free_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_free_inode",
      "external": true,
      "loc": "fs/ext4/ialloc.c:231",
      "file": "fs/ext4/ialloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/inode.c:ext4_evict_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582699852,
      "name": "ext4_free_inode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071582691024,
      "name": "ext4_free_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1355
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
