# Function: <code>fat_get_mapped_cluster</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int fat_get_mapped_cluster(struct inode * inode, sector_t sector, sector_t last_block, long unsigned int * mapped_blocks, sector_t * bmap)
```

```json
{
  "name": "fat_get_mapped_cluster",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582159584,
      "name": "fat_get_mapped_cluster",
      "external": true,
      "loc": "fs/fat/cache.c:304",
      "file": "fs/fat/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/cache.c:fat_bmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582159584,
      "name": "fat_get_mapped_cluster",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 285
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
int fat_get_mapped_cluster(struct inode * inode, sector_t sector, sector_t last_block, long unsigned int * mapped_blocks, sector_t * bmap)
```

```json
{
  "name": "fat_get_mapped_cluster",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582248992,
      "name": "fat_get_mapped_cluster",
      "external": true,
      "loc": "fs/fat/cache.c:304",
      "file": "fs/fat/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/cache.c:fat_bmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582248992,
      "name": "fat_get_mapped_cluster",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 285
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
int fat_get_mapped_cluster(struct inode * inode, sector_t sector, sector_t last_block, long unsigned int * mapped_blocks, sector_t * bmap)
```

```json
{
  "name": "fat_get_mapped_cluster",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582333872,
      "name": "fat_get_mapped_cluster",
      "external": true,
      "loc": "fs/fat/cache.c:304",
      "file": "fs/fat/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/cache.c:fat_bmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582333872,
      "name": "fat_get_mapped_cluster",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 285
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
int fat_get_mapped_cluster(struct inode * inode, sector_t sector, sector_t last_block, long unsigned int * mapped_blocks, sector_t * bmap)
```

```json
{
  "name": "fat_get_mapped_cluster",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582484432,
      "name": "fat_get_mapped_cluster",
      "external": true,
      "loc": "fs/fat/cache.c:305",
      "file": "fs/fat/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/cache.c:fat_bmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582484432,
      "name": "fat_get_mapped_cluster",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 285
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
int fat_get_mapped_cluster(struct inode * inode, sector_t sector, sector_t last_block, long unsigned int * mapped_blocks, sector_t * bmap)
```

```json
{
  "name": "fat_get_mapped_cluster",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fat_get_mapped_cluster",
      "external": true,
      "loc": "fs/fat/cache.c:310",
      "file": "fs/fat/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/cache.c:fat_bmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582676126,
      "name": "fat_get_mapped_cluster.cold.13",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071582675680,
      "name": "fat_get_mapped_cluster",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 250
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
int fat_get_mapped_cluster(struct inode * inode, sector_t sector, sector_t last_block, long unsigned int * mapped_blocks, sector_t * bmap)
```

```json
{
  "name": "fat_get_mapped_cluster",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fat_get_mapped_cluster",
      "external": true,
      "loc": "fs/fat/cache.c:310",
      "file": "fs/fat/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/cache.c:fat_bmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582777998,
      "name": "fat_get_mapped_cluster.cold.14",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071582777552,
      "name": "fat_get_mapped_cluster",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 250
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
int fat_get_mapped_cluster(struct inode * inode, sector_t sector, sector_t last_block, long unsigned int * mapped_blocks, sector_t * bmap)
```

```json
{
  "name": "fat_get_mapped_cluster",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fat_get_mapped_cluster",
      "external": true,
      "loc": "fs/fat/cache.c:310",
      "file": "fs/fat/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/cache.c:fat_bmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582952091,
      "name": "fat_get_mapped_cluster.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071582951648,
      "name": "fat_get_mapped_cluster",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 254
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
int fat_get_mapped_cluster(struct inode * inode, sector_t sector, sector_t last_block, long unsigned int * mapped_blocks, sector_t * bmap)
```

```json
{
  "name": "fat_get_mapped_cluster",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fat_get_mapped_cluster",
      "external": true,
      "loc": "fs/fat/cache.c:310",
      "file": "fs/fat/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/cache.c:fat_bmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583058747,
      "name": "fat_get_mapped_cluster.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071583058304,
      "name": "fat_get_mapped_cluster",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 254
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
int fat_get_mapped_cluster(struct inode * inode, sector_t sector, sector_t last_block, long unsigned int * mapped_blocks, sector_t * bmap)
```

```json
{
  "name": "fat_get_mapped_cluster",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fat_get_mapped_cluster",
      "external": true,
      "loc": "fs/fat/cache.c:310",
      "file": "fs/fat/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/cache.c:fat_bmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583377870,
      "name": "fat_get_mapped_cluster.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071583377424,
      "name": "fat_get_mapped_cluster",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
int fat_get_mapped_cluster(struct inode * inode, sector_t sector, sector_t last_block, long unsigned int * mapped_blocks, sector_t * bmap)
```

```json
{
  "name": "fat_get_mapped_cluster",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fat_get_mapped_cluster",
      "external": true,
      "loc": "fs/fat/cache.c:310",
      "file": "fs/fat/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/cache.c:fat_bmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591352159,
      "name": "fat_get_mapped_cluster.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071583493360,
      "name": "fat_get_mapped_cluster",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
int fat_get_mapped_cluster(struct inode * inode, sector_t sector, sector_t last_block, long unsigned int * mapped_blocks, sector_t * bmap)
```

```json
{
  "name": "fat_get_mapped_cluster",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fat_get_mapped_cluster",
      "external": true,
      "loc": "fs/fat/cache.c:310",
      "file": "fs/fat/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/cache.c:fat_bmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591295074,
      "name": "fat_get_mapped_cluster.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071583515360,
      "name": "fat_get_mapped_cluster",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
int fat_get_mapped_cluster(struct inode * inode, sector_t sector, sector_t last_block, long unsigned int * mapped_blocks, sector_t * bmap)
```

```json
{
  "name": "fat_get_mapped_cluster",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fat_get_mapped_cluster",
      "external": true,
      "loc": "fs/fat/cache.c:310",
      "file": "fs/fat/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/cache.c:fat_bmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592278059,
      "name": "fat_get_mapped_cluster.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
    },
    {
      "addr": 18446744071583870864,
      "name": "fat_get_mapped_cluster",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 286
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
int fat_get_mapped_cluster(struct inode * inode, sector_t sector, sector_t last_block, long unsigned int * mapped_blocks, sector_t * bmap)
```

```json
{
  "name": "fat_get_mapped_cluster",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fat_get_mapped_cluster",
      "external": true,
      "loc": "fs/fat/cache.c:310",
      "file": "fs/fat/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/cache.c:fat_bmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594060291,
      "name": "fat_get_mapped_cluster.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    },
    {
      "addr": 18446744071584444432,
      "name": "fat_get_mapped_cluster",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 306
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
int fat_get_mapped_cluster(struct inode * inode, sector_t sector, sector_t last_block, long unsigned int * mapped_blocks, sector_t * bmap)
```

```json
{
  "name": "fat_get_mapped_cluster",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fat_get_mapped_cluster",
      "external": true,
      "loc": "fs/fat/cache.c:310",
      "file": "fs/fat/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/cache.c:fat_bmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596088542,
      "name": "fat_get_mapped_cluster.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071585106848,
      "name": "fat_get_mapped_cluster",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 343
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
int fat_get_mapped_cluster(struct inode * inode, sector_t sector, sector_t last_block, long unsigned int * mapped_blocks, sector_t * bmap)
```

```json
{
  "name": "fat_get_mapped_cluster",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fat_get_mapped_cluster",
      "external": true,
      "loc": "fs/fat/cache.c:310",
      "file": "fs/fat/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/cache.c:fat_bmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596611955,
      "name": "fat_get_mapped_cluster.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071585336096,
      "name": "fat_get_mapped_cluster",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 343
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
int fat_get_mapped_cluster(struct inode * inode, sector_t sector, sector_t last_block, long unsigned int * mapped_blocks, sector_t * bmap)
```

```json
{
  "name": "fat_get_mapped_cluster",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fat_get_mapped_cluster",
      "external": true,
      "loc": "fs/fat/cache.c:310",
      "file": "fs/fat/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/cache.c:fat_bmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597517909,
      "name": "fat_get_mapped_cluster.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071585570768,
      "name": "fat_get_mapped_cluster",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 343
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
int fat_get_mapped_cluster(struct inode * inode, sector_t sector, sector_t last_block, long unsigned int * mapped_blocks, sector_t * bmap)
```

```json
{
  "name": "fat_get_mapped_cluster",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494757216,
      "name": "fat_get_mapped_cluster",
      "external": true,
      "loc": "fs/fat/cache.c:310",
      "file": "fs/fat/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/cache.c:fat_bmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494757216,
      "name": "fat_get_mapped_cluster",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 356
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
int fat_get_mapped_cluster(struct inode * inode, sector_t sector, sector_t last_block, long unsigned int * mapped_blocks, sector_t * bmap)
```

```json
{
  "name": "fat_get_mapped_cluster",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228182200,
      "name": "fat_get_mapped_cluster",
      "external": true,
      "loc": "fs/fat/cache.c:310",
      "file": "fs/fat/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/cache.c:fat_bmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228182200,
      "name": "fat_get_mapped_cluster",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 432
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
int fat_get_mapped_cluster(struct inode * inode, sector_t sector, sector_t last_block, long unsigned int * mapped_blocks, sector_t * bmap)
```

```json
{
  "name": "fat_get_mapped_cluster",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288588144,
      "name": "fat_get_mapped_cluster",
      "external": true,
      "loc": "fs/fat/cache.c:310",
      "file": "fs/fat/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/cache.c:fat_bmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288588144,
      "name": "fat_get_mapped_cluster",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 496
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
int fat_get_mapped_cluster(struct inode * inode, sector_t sector, sector_t last_block, long unsigned int * mapped_blocks, sector_t * bmap)
```

```json
{
  "name": "fat_get_mapped_cluster",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274099454,
      "name": "fat_get_mapped_cluster",
      "external": true,
      "loc": "fs/fat/cache.c:310",
      "file": "fs/fat/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/cache.c:fat_bmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274099454,
      "name": "fat_get_mapped_cluster",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
int fat_get_mapped_cluster(struct inode * inode, sector_t sector, sector_t last_block, long unsigned int * mapped_blocks, sector_t * bmap)
```

```json
{
  "name": "fat_get_mapped_cluster",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fat_get_mapped_cluster",
      "external": true,
      "loc": "fs/fat/cache.c:310",
      "file": "fs/fat/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/cache.c:fat_bmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583027483,
      "name": "fat_get_mapped_cluster.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071583027040,
      "name": "fat_get_mapped_cluster",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 254
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
int fat_get_mapped_cluster(struct inode * inode, sector_t sector, sector_t last_block, long unsigned int * mapped_blocks, sector_t * bmap)
```

```json
{
  "name": "fat_get_mapped_cluster",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fat_get_mapped_cluster",
      "external": true,
      "loc": "fs/fat/cache.c:310",
      "file": "fs/fat/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/cache.c:fat_bmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582964635,
      "name": "fat_get_mapped_cluster.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071582964192,
      "name": "fat_get_mapped_cluster",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 254
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
int fat_get_mapped_cluster(struct inode * inode, sector_t sector, sector_t last_block, long unsigned int * mapped_blocks, sector_t * bmap)
```

```json
{
  "name": "fat_get_mapped_cluster",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fat_get_mapped_cluster",
      "external": true,
      "loc": "fs/fat/cache.c:310",
      "file": "fs/fat/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/cache.c:fat_bmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583016091,
      "name": "fat_get_mapped_cluster.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071583015648,
      "name": "fat_get_mapped_cluster",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 254
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
int fat_get_mapped_cluster(struct inode * inode, sector_t sector, sector_t last_block, long unsigned int * mapped_blocks, sector_t * bmap)
```

```json
{
  "name": "fat_get_mapped_cluster",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fat_get_mapped_cluster",
      "external": true,
      "loc": "fs/fat/cache.c:310",
      "file": "fs/fat/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/cache.c:fat_bmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583105275,
      "name": "fat_get_mapped_cluster.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071583104832,
      "name": "fat_get_mapped_cluster",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 254
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
int fat_get_mapped_cluster(struct inode * inode, sector_t sector, sector_t last_block, long unsigned int * mapped_blocks, sector_t * bmap)
```
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
