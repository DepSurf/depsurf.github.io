# Function: <code>fat_bmap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int fat_bmap(struct inode * inode, sector_t sector, sector_t * phys, long unsigned int * mapped_blocks, int create)
```

```json
{
  "name": "fat_bmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581948096,
      "name": "fat_bmap",
      "external": true,
      "loc": "fs/fat/cache.c:304",
      "file": "fs/fat/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat__get_entry",
        "fs/fat/inode.c:fat_get_block",
        "fs/fat/inode.c:fat_get_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581948096,
      "name": "fat_bmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 419
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
int fat_bmap(struct inode * inode, sector_t sector, sector_t * phys, long unsigned int * mapped_blocks, int create, bool from_bmap)
```

```json
{
  "name": "fat_bmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582159872,
      "name": "fat_bmap",
      "external": true,
      "loc": "fs/fat/cache.c:352",
      "file": "fs/fat/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat__get_entry",
        "fs/fat/inode.c:fat_get_block_bmap",
        "fs/fat/inode.c:fat_get_block",
        "fs/fat/inode.c:fat_get_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582159872,
      "name": "fat_bmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
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
int fat_bmap(struct inode * inode, sector_t sector, sector_t * phys, long unsigned int * mapped_blocks, int create, bool from_bmap)
```

```json
{
  "name": "fat_bmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582249280,
      "name": "fat_bmap",
      "external": true,
      "loc": "fs/fat/cache.c:352",
      "file": "fs/fat/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat__get_entry",
        "fs/fat/inode.c:fat_get_block_bmap",
        "fs/fat/inode.c:fat_get_block",
        "fs/fat/inode.c:fat_get_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582249280,
      "name": "fat_bmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
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
int fat_bmap(struct inode * inode, sector_t sector, sector_t * phys, long unsigned int * mapped_blocks, int create, bool from_bmap)
```

```json
{
  "name": "fat_bmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582334160,
      "name": "fat_bmap",
      "external": true,
      "loc": "fs/fat/cache.c:352",
      "file": "fs/fat/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat__get_entry",
        "fs/fat/inode.c:fat_get_block_bmap",
        "fs/fat/inode.c:fat_get_block",
        "fs/fat/inode.c:fat_get_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582334160,
      "name": "fat_bmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
int fat_bmap(struct inode * inode, sector_t sector, sector_t * phys, long unsigned int * mapped_blocks, int create, bool from_bmap)
```

```json
{
  "name": "fat_bmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582484720,
      "name": "fat_bmap",
      "external": true,
      "loc": "fs/fat/cache.c:353",
      "file": "fs/fat/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat__get_entry",
        "fs/fat/inode.c:fat_get_block_bmap",
        "fs/fat/inode.c:fat_get_block",
        "fs/fat/inode.c:fat_get_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582484720,
      "name": "fat_bmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
int fat_bmap(struct inode * inode, sector_t sector, sector_t * phys, long unsigned int * mapped_blocks, int create, bool from_bmap)
```

```json
{
  "name": "fat_bmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582675936,
      "name": "fat_bmap",
      "external": true,
      "loc": "fs/fat/cache.c:358",
      "file": "fs/fat/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat__get_entry",
        "fs/fat/inode.c:fat_get_block_bmap",
        "fs/fat/inode.c:fat_get_block",
        "fs/fat/inode.c:fat_get_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582675936,
      "name": "fat_bmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
int fat_bmap(struct inode * inode, sector_t sector, sector_t * phys, long unsigned int * mapped_blocks, int create, bool from_bmap)
```

```json
{
  "name": "fat_bmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582777808,
      "name": "fat_bmap",
      "external": true,
      "loc": "fs/fat/cache.c:358",
      "file": "fs/fat/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat__get_entry",
        "fs/fat/inode.c:fat_get_block_bmap",
        "fs/fat/inode.c:fat_get_block",
        "fs/fat/inode.c:fat_get_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582777808,
      "name": "fat_bmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
int fat_bmap(struct inode * inode, sector_t sector, sector_t * phys, long unsigned int * mapped_blocks, int create, bool from_bmap)
```

```json
{
  "name": "fat_bmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582951904,
      "name": "fat_bmap",
      "external": true,
      "loc": "fs/fat/cache.c:358",
      "file": "fs/fat/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat__get_entry",
        "fs/fat/inode.c:fat_get_block",
        "fs/fat/inode.c:fat_get_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582951904,
      "name": "fat_bmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
int fat_bmap(struct inode * inode, sector_t sector, sector_t * phys, long unsigned int * mapped_blocks, int create, bool from_bmap)
```

```json
{
  "name": "fat_bmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583058560,
      "name": "fat_bmap",
      "external": true,
      "loc": "fs/fat/cache.c:358",
      "file": "fs/fat/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat__get_entry",
        "fs/fat/inode.c:fat_get_block",
        "fs/fat/inode.c:fat_get_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583058560,
      "name": "fat_bmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
int fat_bmap(struct inode * inode, sector_t sector, sector_t * phys, long unsigned int * mapped_blocks, int create, bool from_bmap)
```

```json
{
  "name": "fat_bmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583377680,
      "name": "fat_bmap",
      "external": true,
      "loc": "fs/fat/cache.c:358",
      "file": "fs/fat/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat__get_entry",
        "fs/fat/inode.c:fat_get_block_bmap",
        "fs/fat/inode.c:__fat_get_block",
        "fs/fat/inode.c:__fat_get_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583377680,
      "name": "fat_bmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
int fat_bmap(struct inode * inode, sector_t sector, sector_t * phys, long unsigned int * mapped_blocks, int create, bool from_bmap)
```

```json
{
  "name": "fat_bmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583493616,
      "name": "fat_bmap",
      "external": true,
      "loc": "fs/fat/cache.c:358",
      "file": "fs/fat/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat__get_entry",
        "fs/fat/inode.c:fat_get_block_bmap",
        "fs/fat/inode.c:__fat_get_block",
        "fs/fat/inode.c:__fat_get_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583493616,
      "name": "fat_bmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
int fat_bmap(struct inode * inode, sector_t sector, sector_t * phys, long unsigned int * mapped_blocks, int create, bool from_bmap)
```

```json
{
  "name": "fat_bmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583515648,
      "name": "fat_bmap",
      "external": true,
      "loc": "fs/fat/cache.c:358",
      "file": "fs/fat/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat__get_entry",
        "fs/fat/inode.c:fat_get_block_bmap",
        "fs/fat/inode.c:__fat_get_block",
        "fs/fat/inode.c:__fat_get_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583515648,
      "name": "fat_bmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
int fat_bmap(struct inode * inode, sector_t sector, sector_t * phys, long unsigned int * mapped_blocks, int create, bool from_bmap)
```

```json
{
  "name": "fat_bmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fat_bmap",
      "external": true,
      "loc": "fs/fat/cache.c:358",
      "file": "fs/fat/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat__get_entry",
        "fs/fat/inode.c:fat_get_block_bmap",
        "fs/fat/inode.c:__fat_get_block",
        "fs/fat/inode.c:__fat_get_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592278148,
      "name": "fat_bmap.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
    },
    {
      "addr": 18446744071583871152,
      "name": "fat_bmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 295
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
int fat_bmap(struct inode * inode, sector_t sector, sector_t * phys, long unsigned int * mapped_blocks, int create, bool from_bmap)
```

```json
{
  "name": "fat_bmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fat_bmap",
      "external": true,
      "loc": "fs/fat/cache.c:358",
      "file": "fs/fat/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat__get_entry",
        "fs/fat/inode.c:fat_get_block_bmap",
        "fs/fat/inode.c:__fat_get_block",
        "fs/fat/inode.c:__fat_get_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594060378,
      "name": "fat_bmap.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
    },
    {
      "addr": 18446744071584444752,
      "name": "fat_bmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 319
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
int fat_bmap(struct inode * inode, sector_t sector, sector_t * phys, long unsigned int * mapped_blocks, int create, bool from_bmap)
```

```json
{
  "name": "fat_bmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fat_bmap",
      "external": true,
      "loc": "fs/fat/cache.c:358",
      "file": "fs/fat/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat__get_entry",
        "fs/fat/inode.c:fat_get_block_bmap",
        "fs/fat/inode.c:__fat_get_block",
        "fs/fat/inode.c:__fat_get_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596088588,
      "name": "fat_bmap.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
    },
    {
      "addr": 18446744071585107216,
      "name": "fat_bmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 319
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
int fat_bmap(struct inode * inode, sector_t sector, sector_t * phys, long unsigned int * mapped_blocks, int create, bool from_bmap)
```

```json
{
  "name": "fat_bmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fat_bmap",
      "external": true,
      "loc": "fs/fat/cache.c:358",
      "file": "fs/fat/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat__get_entry",
        "fs/fat/inode.c:fat_get_block_bmap",
        "fs/fat/inode.c:__fat_get_block",
        "fs/fat/inode.c:__fat_get_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596612001,
      "name": "fat_bmap.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
    },
    {
      "addr": 18446744071585336464,
      "name": "fat_bmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 279
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
int fat_bmap(struct inode * inode, sector_t sector, sector_t * phys, long unsigned int * mapped_blocks, int create, bool from_bmap)
```

```json
{
  "name": "fat_bmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fat_bmap",
      "external": true,
      "loc": "fs/fat/cache.c:358",
      "file": "fs/fat/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat__get_entry",
        "fs/fat/inode.c:fat_get_block_bmap",
        "fs/fat/inode.c:__fat_get_block",
        "fs/fat/inode.c:__fat_get_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597517955,
      "name": "fat_bmap.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
    },
    {
      "addr": 18446744071585571136,
      "name": "fat_bmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 279
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
int fat_bmap(struct inode * inode, sector_t sector, sector_t * phys, long unsigned int * mapped_blocks, int create, bool from_bmap)
```

```json
{
  "name": "fat_bmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494757576,
      "name": "fat_bmap",
      "external": true,
      "loc": "fs/fat/cache.c:358",
      "file": "fs/fat/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat__get_entry",
        "fs/fat/inode.c:fat_get_block_bmap",
        "fs/fat/inode.c:fat_get_block",
        "fs/fat/inode.c:fat_get_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494757576,
      "name": "fat_bmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
int fat_bmap(struct inode * inode, sector_t sector, sector_t * phys, long unsigned int * mapped_blocks, int create, bool from_bmap)
```

```json
{
  "name": "fat_bmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228182632,
      "name": "fat_bmap",
      "external": true,
      "loc": "fs/fat/cache.c:358",
      "file": "fs/fat/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat__get_entry",
        "fs/fat/inode.c:fat_get_block_bmap",
        "fs/fat/inode.c:fat_get_block",
        "fs/fat/inode.c:fat_get_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228182632,
      "name": "fat_bmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 460
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
int fat_bmap(struct inode * inode, sector_t sector, sector_t * phys, long unsigned int * mapped_blocks, int create, bool from_bmap)
```

```json
{
  "name": "fat_bmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288588640,
      "name": "fat_bmap",
      "external": true,
      "loc": "fs/fat/cache.c:358",
      "file": "fs/fat/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat__get_entry",
        "fs/fat/inode.c:fat_get_block_bmap",
        "fs/fat/inode.c:fat_get_block",
        "fs/fat/inode.c:fat_get_block",
        "fs/fat/inode.c:fat_get_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288588640,
      "name": "fat_bmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
int fat_bmap(struct inode * inode, sector_t sector, sector_t * phys, long unsigned int * mapped_blocks, int create, bool from_bmap)
```

```json
{
  "name": "fat_bmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274099698,
      "name": "fat_bmap",
      "external": true,
      "loc": "fs/fat/cache.c:358",
      "file": "fs/fat/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat__get_entry",
        "fs/fat/inode.c:fat_get_block",
        "fs/fat/inode.c:fat_get_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274099698,
      "name": "fat_bmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
int fat_bmap(struct inode * inode, sector_t sector, sector_t * phys, long unsigned int * mapped_blocks, int create, bool from_bmap)
```

```json
{
  "name": "fat_bmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583027296,
      "name": "fat_bmap",
      "external": true,
      "loc": "fs/fat/cache.c:358",
      "file": "fs/fat/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat__get_entry",
        "fs/fat/inode.c:fat_get_block",
        "fs/fat/inode.c:fat_get_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583027296,
      "name": "fat_bmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
int fat_bmap(struct inode * inode, sector_t sector, sector_t * phys, long unsigned int * mapped_blocks, int create, bool from_bmap)
```

```json
{
  "name": "fat_bmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582964448,
      "name": "fat_bmap",
      "external": true,
      "loc": "fs/fat/cache.c:358",
      "file": "fs/fat/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat__get_entry",
        "fs/fat/inode.c:fat_get_block",
        "fs/fat/inode.c:fat_get_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582964448,
      "name": "fat_bmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
int fat_bmap(struct inode * inode, sector_t sector, sector_t * phys, long unsigned int * mapped_blocks, int create, bool from_bmap)
```

```json
{
  "name": "fat_bmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583015904,
      "name": "fat_bmap",
      "external": true,
      "loc": "fs/fat/cache.c:358",
      "file": "fs/fat/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat__get_entry",
        "fs/fat/inode.c:fat_get_block",
        "fs/fat/inode.c:fat_get_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583015904,
      "name": "fat_bmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
int fat_bmap(struct inode * inode, sector_t sector, sector_t * phys, long unsigned int * mapped_blocks, int create, bool from_bmap)
```

```json
{
  "name": "fat_bmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583105088,
      "name": "fat_bmap",
      "external": true,
      "loc": "fs/fat/cache.c:358",
      "file": "fs/fat/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat__get_entry",
        "fs/fat/inode.c:fat_get_block",
        "fs/fat/inode.c:fat_get_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583105088,
      "name": "fat_bmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool from_bmap</code>
</li>
</ul>
</details>
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
