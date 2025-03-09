# Function: <code>squashfs_cache_init</code>

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
struct squashfs_cache * squashfs_cache_init(char * name, int entries, int block_size)
```

```json
{
  "name": "squashfs_cache_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582127936,
      "name": "squashfs_cache_init",
      "external": true,
      "loc": "fs/squashfs/cache.c:236",
      "file": "fs/squashfs/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582127936,
      "name": "squashfs_cache_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 587
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
struct squashfs_cache * squashfs_cache_init(char * name, int entries, int block_size)
```

```json
{
  "name": "squashfs_cache_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582217680,
      "name": "squashfs_cache_init",
      "external": true,
      "loc": "fs/squashfs/cache.c:236",
      "file": "fs/squashfs/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582217680,
      "name": "squashfs_cache_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 587
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
struct squashfs_cache * squashfs_cache_init(char * name, int entries, int block_size)
```

```json
{
  "name": "squashfs_cache_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582302976,
      "name": "squashfs_cache_init",
      "external": true,
      "loc": "fs/squashfs/cache.c:236",
      "file": "fs/squashfs/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582302976,
      "name": "squashfs_cache_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 596
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
struct squashfs_cache * squashfs_cache_init(char * name, int entries, int block_size)
```

```json
{
  "name": "squashfs_cache_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582452096,
      "name": "squashfs_cache_init",
      "external": true,
      "loc": "fs/squashfs/cache.c:236",
      "file": "fs/squashfs/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582452096,
      "name": "squashfs_cache_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 596
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
struct squashfs_cache * squashfs_cache_init(char * name, int entries, int block_size)
```

```json
{
  "name": "squashfs_cache_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "squashfs_cache_init",
      "external": true,
      "loc": "fs/squashfs/cache.c:236",
      "file": "fs/squashfs/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582643955,
      "name": "squashfs_cache_init.cold.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071582642656,
      "name": "squashfs_cache_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 524
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
struct squashfs_cache * squashfs_cache_init(char * name, int entries, int block_size)
```

```json
{
  "name": "squashfs_cache_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "squashfs_cache_init",
      "external": true,
      "loc": "fs/squashfs/cache.c:236",
      "file": "fs/squashfs/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582745731,
      "name": "squashfs_cache_init.cold.4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071582744432,
      "name": "squashfs_cache_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 524
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
struct squashfs_cache * squashfs_cache_init(char * name, int entries, int block_size)
```

```json
{
  "name": "squashfs_cache_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "squashfs_cache_init",
      "external": true,
      "loc": "fs/squashfs/cache.c:223",
      "file": "fs/squashfs/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582919779,
      "name": "squashfs_cache_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071582918464,
      "name": "squashfs_cache_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 527
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
struct squashfs_cache * squashfs_cache_init(char * name, int entries, int block_size)
```

```json
{
  "name": "squashfs_cache_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "squashfs_cache_init",
      "external": true,
      "loc": "fs/squashfs/cache.c:223",
      "file": "fs/squashfs/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583026323,
      "name": "squashfs_cache_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071583025008,
      "name": "squashfs_cache_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 527
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
struct squashfs_cache * squashfs_cache_init(char * name, int entries, int block_size)
```

```json
{
  "name": "squashfs_cache_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "squashfs_cache_init",
      "external": true,
      "loc": "fs/squashfs/cache.c:223",
      "file": "fs/squashfs/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583344131,
      "name": "squashfs_cache_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071583342816,
      "name": "squashfs_cache_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 519
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
struct squashfs_cache * squashfs_cache_init(char * name, int entries, int block_size)
```

```json
{
  "name": "squashfs_cache_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "squashfs_cache_init",
      "external": true,
      "loc": "fs/squashfs/cache.c:223",
      "file": "fs/squashfs/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591351276,
      "name": "squashfs_cache_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071583459280,
      "name": "squashfs_cache_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 519
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
struct squashfs_cache * squashfs_cache_init(char * name, int entries, int block_size)
```

```json
{
  "name": "squashfs_cache_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "squashfs_cache_init",
      "external": true,
      "loc": "fs/squashfs/cache.c:223",
      "file": "fs/squashfs/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591294160,
      "name": "squashfs_cache_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071583481248,
      "name": "squashfs_cache_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 516
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
struct squashfs_cache * squashfs_cache_init(char * name, int entries, int block_size)
```

```json
{
  "name": "squashfs_cache_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "squashfs_cache_init",
      "external": true,
      "loc": "fs/squashfs/cache.c:223",
      "file": "fs/squashfs/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592275741,
      "name": "squashfs_cache_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071583835648,
      "name": "squashfs_cache_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 516
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
struct squashfs_cache * squashfs_cache_init(char * name, int entries, int block_size)
```

```json
{
  "name": "squashfs_cache_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "squashfs_cache_init",
      "external": true,
      "loc": "fs/squashfs/cache.c:223",
      "file": "fs/squashfs/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594057584,
      "name": "squashfs_cache_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    },
    {
      "addr": 18446744071584403728,
      "name": "squashfs_cache_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 528
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
struct squashfs_cache * squashfs_cache_init(char * name, int entries, int block_size)
```

```json
{
  "name": "squashfs_cache_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585058896,
      "name": "squashfs_cache_init",
      "external": true,
      "loc": "fs/squashfs/cache.c:223",
      "file": "fs/squashfs/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585058896,
      "name": "squashfs_cache_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 561
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
struct squashfs_cache * squashfs_cache_init(char * name, int entries, int block_size)
```

```json
{
  "name": "squashfs_cache_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585288080,
      "name": "squashfs_cache_init",
      "external": true,
      "loc": "fs/squashfs/cache.c:223",
      "file": "fs/squashfs/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585288080,
      "name": "squashfs_cache_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 550
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
struct squashfs_cache * squashfs_cache_init(char * name, int entries, int block_size)
```

```json
{
  "name": "squashfs_cache_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585521696,
      "name": "squashfs_cache_init",
      "external": true,
      "loc": "fs/squashfs/cache.c:223",
      "file": "fs/squashfs/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585521696,
      "name": "squashfs_cache_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 684
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
struct squashfs_cache * squashfs_cache_init(char * name, int entries, int block_size)
```

```json
{
  "name": "squashfs_cache_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494720464,
      "name": "squashfs_cache_init",
      "external": true,
      "loc": "fs/squashfs/cache.c:223",
      "file": "fs/squashfs/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494720464,
      "name": "squashfs_cache_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 604
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
struct squashfs_cache * squashfs_cache_init(char * name, int entries, int block_size)
```

```json
{
  "name": "squashfs_cache_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228155160,
      "name": "squashfs_cache_init",
      "external": true,
      "loc": "fs/squashfs/cache.c:223",
      "file": "fs/squashfs/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228155160,
      "name": "squashfs_cache_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 524
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
struct squashfs_cache * squashfs_cache_init(char * name, int entries, int block_size)
```

```json
{
  "name": "squashfs_cache_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288541680,
      "name": "squashfs_cache_init",
      "external": true,
      "loc": "fs/squashfs/cache.c:223",
      "file": "fs/squashfs/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288541680,
      "name": "squashfs_cache_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 776
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
struct squashfs_cache * squashfs_cache_init(char * name, int entries, int block_size)
```

```json
{
  "name": "squashfs_cache_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274068914,
      "name": "squashfs_cache_init",
      "external": true,
      "loc": "fs/squashfs/cache.c:223",
      "file": "fs/squashfs/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274068914,
      "name": "squashfs_cache_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 536
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
struct squashfs_cache * squashfs_cache_init(char * name, int entries, int block_size)
```

```json
{
  "name": "squashfs_cache_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "squashfs_cache_init",
      "external": true,
      "loc": "fs/squashfs/cache.c:223",
      "file": "fs/squashfs/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582995059,
      "name": "squashfs_cache_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071582993744,
      "name": "squashfs_cache_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 527
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
struct squashfs_cache * squashfs_cache_init(char * name, int entries, int block_size)
```

```json
{
  "name": "squashfs_cache_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "squashfs_cache_init",
      "external": true,
      "loc": "fs/squashfs/cache.c:223",
      "file": "fs/squashfs/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582932211,
      "name": "squashfs_cache_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071582930896,
      "name": "squashfs_cache_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 527
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
struct squashfs_cache * squashfs_cache_init(char * name, int entries, int block_size)
```

```json
{
  "name": "squashfs_cache_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "squashfs_cache_init",
      "external": true,
      "loc": "fs/squashfs/cache.c:223",
      "file": "fs/squashfs/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582983667,
      "name": "squashfs_cache_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071582982352,
      "name": "squashfs_cache_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 527
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
struct squashfs_cache * squashfs_cache_init(char * name, int entries, int block_size)
```

```json
{
  "name": "squashfs_cache_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "squashfs_cache_init",
      "external": true,
      "loc": "fs/squashfs/cache.c:223",
      "file": "fs/squashfs/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/squashfs/super.c:squashfs_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583072739,
      "name": "squashfs_cache_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071583071424,
      "name": "squashfs_cache_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 527
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
struct squashfs_cache * squashfs_cache_init(char * name, int entries, int block_size)
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
