# Function: <code>mb_cache_shrink</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void mb_cache_shrink(struct block_device * bdev)
```

```json
{
  "name": "mb_cache_shrink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581390448,
      "name": "mb_cache_shrink",
      "external": true,
      "loc": "fs/mbcache.c:396",
      "file": "fs/mbcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/xattr.c:ext4_xattr_put_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581390448,
      "name": "mb_cache_shrink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 489
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
long unsigned int mb_cache_shrink(struct mb_cache * cache, unsigned int nr_to_scan)
```

```json
{
  "name": "mb_cache_shrink",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581567424,
      "name": "mb_cache_shrink",
      "external": false,
      "loc": "fs/mbcache.c:276",
      "file": "fs/mbcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/mbcache.c:mb_cache_shrink_worker",
        "fs/mbcache.c:mb_cache_scan",
        "fs/mbcache.c:mb_cache_entry_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581567424,
      "name": "mb_cache_shrink",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 341
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
long unsigned int mb_cache_shrink(struct mb_cache * cache, long unsigned int nr_to_scan)
```

```json
{
  "name": "mb_cache_shrink",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581652032,
      "name": "mb_cache_shrink",
      "external": false,
      "loc": "fs/mbcache.c:276",
      "file": "fs/mbcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/mbcache.c:mb_cache_shrink_worker",
        "fs/mbcache.c:mb_cache_scan",
        "fs/mbcache.c:mb_cache_entry_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581652032,
      "name": "mb_cache_shrink",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 339
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
long unsigned int mb_cache_shrink(struct mb_cache * cache, long unsigned int nr_to_scan)
```

```json
{
  "name": "mb_cache_shrink",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581706480,
      "name": "mb_cache_shrink",
      "external": false,
      "loc": "fs/mbcache.c:276",
      "file": "fs/mbcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/mbcache.c:mb_cache_shrink_worker",
        "fs/mbcache.c:mb_cache_scan",
        "fs/mbcache.c:mb_cache_entry_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581706480,
      "name": "mb_cache_shrink",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 318
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
long unsigned int mb_cache_shrink(struct mb_cache * cache, long unsigned int nr_to_scan)
```

```json
{
  "name": "mb_cache_shrink",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581852112,
      "name": "mb_cache_shrink",
      "external": false,
      "loc": "fs/mbcache.c:280",
      "file": "fs/mbcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/mbcache.c:mb_cache_shrink_worker",
        "fs/mbcache.c:mb_cache_scan",
        "fs/mbcache.c:mb_cache_entry_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581852112,
      "name": "mb_cache_shrink",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 318
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
long unsigned int mb_cache_shrink(struct mb_cache * cache, long unsigned int nr_to_scan)
```

```json
{
  "name": "mb_cache_shrink",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582032912,
      "name": "mb_cache_shrink",
      "external": false,
      "loc": "fs/mbcache.c:279",
      "file": "fs/mbcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/mbcache.c:mb_cache_shrink_worker",
        "fs/mbcache.c:mb_cache_scan",
        "fs/mbcache.c:mb_cache_entry_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582032912,
      "name": "mb_cache_shrink",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 319
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
long unsigned int mb_cache_shrink(struct mb_cache * cache, long unsigned int nr_to_scan)
```

```json
{
  "name": "mb_cache_shrink",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582120944,
      "name": "mb_cache_shrink",
      "external": false,
      "loc": "fs/mbcache.c:279",
      "file": "fs/mbcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/mbcache.c:mb_cache_shrink_worker",
        "fs/mbcache.c:mb_cache_scan",
        "fs/mbcache.c:mb_cache_entry_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582120944,
      "name": "mb_cache_shrink",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 319
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
long unsigned int mb_cache_shrink(struct mb_cache * cache, long unsigned int nr_to_scan)
```

```json
{
  "name": "mb_cache_shrink",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582282832,
      "name": "mb_cache_shrink",
      "external": false,
      "loc": "fs/mbcache.c:280",
      "file": "fs/mbcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/mbcache.c:mb_cache_shrink_worker",
        "fs/mbcache.c:mb_cache_scan",
        "fs/mbcache.c:mb_cache_entry_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582282832,
      "name": "mb_cache_shrink",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 353
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
long unsigned int mb_cache_shrink(struct mb_cache * cache, long unsigned int nr_to_scan)
```

```json
{
  "name": "mb_cache_shrink",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582381504,
      "name": "mb_cache_shrink",
      "external": false,
      "loc": "fs/mbcache.c:280",
      "file": "fs/mbcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/mbcache.c:mb_cache_shrink_worker",
        "fs/mbcache.c:mb_cache_scan",
        "fs/mbcache.c:mb_cache_entry_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582381504,
      "name": "mb_cache_shrink",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 353
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
long unsigned int mb_cache_shrink(struct mb_cache * cache, long unsigned int nr_to_scan)
```

```json
{
  "name": "mb_cache_shrink",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582667168,
      "name": "mb_cache_shrink",
      "external": false,
      "loc": "fs/mbcache.c:280",
      "file": "fs/mbcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/mbcache.c:mb_cache_shrink_worker",
        "fs/mbcache.c:mb_cache_scan",
        "fs/mbcache.c:mb_cache_entry_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582667168,
      "name": "mb_cache_shrink",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 345
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
long unsigned int mb_cache_shrink(struct mb_cache * cache, long unsigned int nr_to_scan)
```

```json
{
  "name": "mb_cache_shrink",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582736128,
      "name": "mb_cache_shrink",
      "external": false,
      "loc": "fs/mbcache.c:280",
      "file": "fs/mbcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/mbcache.c:mb_cache_shrink_worker",
        "fs/mbcache.c:mb_cache_scan",
        "fs/mbcache.c:mb_cache_entry_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582736128,
      "name": "mb_cache_shrink",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 345
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
long unsigned int mb_cache_shrink(struct mb_cache * cache, long unsigned int nr_to_scan)
```

```json
{
  "name": "mb_cache_shrink",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582765136,
      "name": "mb_cache_shrink",
      "external": false,
      "loc": "fs/mbcache.c:280",
      "file": "fs/mbcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/mbcache.c:mb_cache_shrink_worker",
        "fs/mbcache.c:mb_cache_scan",
        "fs/mbcache.c:mb_cache_entry_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582765136,
      "name": "mb_cache_shrink",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 345
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
long unsigned int mb_cache_shrink(struct mb_cache * cache, long unsigned int nr_to_scan)
```

```json
{
  "name": "mb_cache_shrink",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mb_cache_shrink",
      "external": false,
      "loc": "fs/mbcache.c:280",
      "file": "fs/mbcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/mbcache.c:mb_cache_shrink_worker",
        "fs/mbcache.c:mb_cache_scan",
        "fs/mbcache.c:mb_cache_entry_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583092176,
      "name": "mb_cache_shrink",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 397
    },
    {
      "addr": 18446744071592244596,
      "name": "mb_cache_shrink.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
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
long unsigned int mb_cache_shrink(struct mb_cache * cache, long unsigned int nr_to_scan)
```

```json
{
  "name": "mb_cache_shrink",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mb_cache_shrink",
      "external": false,
      "loc": "fs/mbcache.c:342",
      "file": "fs/mbcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/mbcache.c:mb_cache_shrink_worker",
        "fs/mbcache.c:mb_cache_scan",
        "fs/mbcache.c:mb_cache_entry_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583571008,
      "name": "mb_cache_shrink",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 553
    },
    {
      "addr": 18446744071594023706,
      "name": "mb_cache_shrink.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
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
long unsigned int mb_cache_shrink(struct mb_cache * cache, long unsigned int nr_to_scan)
```

```json
{
  "name": "mb_cache_shrink",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584172592,
      "name": "mb_cache_shrink",
      "external": false,
      "loc": "fs/mbcache.c:303",
      "file": "fs/mbcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/mbcache.c:mb_cache_shrink_worker",
        "fs/mbcache.c:mb_cache_scan",
        "fs/mbcache.c:mb_cache_entry_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584172592,
      "name": "mb_cache_shrink",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 276
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
long unsigned int mb_cache_shrink(struct mb_cache * cache, long unsigned int nr_to_scan)
```

```json
{
  "name": "mb_cache_shrink",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584400448,
      "name": "mb_cache_shrink",
      "external": false,
      "loc": "fs/mbcache.c:303",
      "file": "fs/mbcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/mbcache.c:mb_cache_shrink_worker",
        "fs/mbcache.c:mb_cache_scan",
        "fs/mbcache.c:mb_cache_entry_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584400448,
      "name": "mb_cache_shrink",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 270
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
long unsigned int mb_cache_shrink(struct mb_cache * cache, long unsigned int nr_to_scan)
```

```json
{
  "name": "mb_cache_shrink",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584621168,
      "name": "mb_cache_shrink",
      "external": false,
      "loc": "fs/mbcache.c:302",
      "file": "fs/mbcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/mbcache.c:mb_cache_shrink_worker",
        "fs/mbcache.c:mb_cache_scan",
        "fs/mbcache.c:mb_cache_entry_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584621168,
      "name": "mb_cache_shrink",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 270
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
long unsigned int mb_cache_shrink(struct mb_cache * cache, long unsigned int nr_to_scan)
```

```json
{
  "name": "mb_cache_shrink",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493978056,
      "name": "mb_cache_shrink",
      "external": false,
      "loc": "fs/mbcache.c:280",
      "file": "fs/mbcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/mbcache.c:mb_cache_shrink_worker",
        "fs/mbcache.c:mb_cache_scan",
        "fs/mbcache.c:mb_cache_entry_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493978056,
      "name": "mb_cache_shrink",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 684
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
long unsigned int mb_cache_shrink(struct mb_cache * cache, long unsigned int nr_to_scan)
```

```json
{
  "name": "mb_cache_shrink",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227442516,
      "name": "mb_cache_shrink",
      "external": false,
      "loc": "fs/mbcache.c:280",
      "file": "fs/mbcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/mbcache.c:mb_cache_shrink_worker",
        "fs/mbcache.c:mb_cache_scan",
        "fs/mbcache.c:mb_cache_entry_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227442516,
      "name": "mb_cache_shrink",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 612
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
long unsigned int mb_cache_shrink(struct mb_cache * cache, long unsigned int nr_to_scan)
```

```json
{
  "name": "mb_cache_shrink",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287620624,
      "name": "mb_cache_shrink",
      "external": false,
      "loc": "fs/mbcache.c:280",
      "file": "fs/mbcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/mbcache.c:mb_cache_shrink_worker",
        "fs/mbcache.c:mb_cache_scan",
        "fs/mbcache.c:mb_cache_entry_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287620624,
      "name": "mb_cache_shrink",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 696
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
long unsigned int mb_cache_shrink(struct mb_cache * cache, long unsigned int nr_to_scan)
```

```json
{
  "name": "mb_cache_shrink",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273499010,
      "name": "mb_cache_shrink",
      "external": false,
      "loc": "fs/mbcache.c:280",
      "file": "fs/mbcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/mbcache.c:mb_cache_shrink_worker",
        "fs/mbcache.c:mb_cache_scan",
        "fs/mbcache.c:mb_cache_entry_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273499010,
      "name": "mb_cache_shrink",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 492
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
long unsigned int mb_cache_shrink(struct mb_cache * cache, long unsigned int nr_to_scan)
```

```json
{
  "name": "mb_cache_shrink",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582350240,
      "name": "mb_cache_shrink",
      "external": false,
      "loc": "fs/mbcache.c:280",
      "file": "fs/mbcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/mbcache.c:mb_cache_shrink_worker",
        "fs/mbcache.c:mb_cache_scan",
        "fs/mbcache.c:mb_cache_entry_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582350240,
      "name": "mb_cache_shrink",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 353
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
long unsigned int mb_cache_shrink(struct mb_cache * cache, long unsigned int nr_to_scan)
```

```json
{
  "name": "mb_cache_shrink",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582287952,
      "name": "mb_cache_shrink",
      "external": false,
      "loc": "fs/mbcache.c:280",
      "file": "fs/mbcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/mbcache.c:mb_cache_shrink_worker",
        "fs/mbcache.c:mb_cache_scan",
        "fs/mbcache.c:mb_cache_entry_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582287952,
      "name": "mb_cache_shrink",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 353
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
long unsigned int mb_cache_shrink(struct mb_cache * cache, long unsigned int nr_to_scan)
```

```json
{
  "name": "mb_cache_shrink",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582340720,
      "name": "mb_cache_shrink",
      "external": false,
      "loc": "fs/mbcache.c:280",
      "file": "fs/mbcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/mbcache.c:mb_cache_shrink_worker",
        "fs/mbcache.c:mb_cache_scan",
        "fs/mbcache.c:mb_cache_entry_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582340720,
      "name": "mb_cache_shrink",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 353
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
long unsigned int mb_cache_shrink(struct mb_cache * cache, long unsigned int nr_to_scan)
```

```json
{
  "name": "mb_cache_shrink",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582420048,
      "name": "mb_cache_shrink",
      "external": false,
      "loc": "fs/mbcache.c:280",
      "file": "fs/mbcache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/mbcache.c:mb_cache_shrink_worker",
        "fs/mbcache.c:mb_cache_scan",
        "fs/mbcache.c:mb_cache_entry_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582420048,
      "name": "mb_cache_shrink",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 427
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
<code>struct mb_cache * cache</code>
</li>
<li>
<b>Param added. </b>
<code>unsigned int nr_to_scan</code>
</li>
<li>
<b>Param removed. </b>
<code>struct block_device * bdev</code>
</li>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>long unsigned int</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>unsigned int nr_to_scan</code> ➡️ <code>long unsigned int nr_to_scan</code>
</li>
</ul>
</details>
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
