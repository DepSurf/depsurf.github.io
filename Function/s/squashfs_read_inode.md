# Function: <code>squashfs_read_inode</code>

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
int squashfs_read_inode(struct inode * inode, long long int ino)
```

```json
{
  "name": "squashfs_read_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582134400,
      "name": "squashfs_read_inode",
      "external": true,
      "loc": "fs/squashfs/inode.c:113",
      "file": "fs/squashfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/inode.c:squashfs_iget",
        "fs/squashfs/super.c:squashfs_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582134400,
      "name": "squashfs_read_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2207
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
int squashfs_read_inode(struct inode * inode, long long int ino)
```

```json
{
  "name": "squashfs_read_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582224144,
      "name": "squashfs_read_inode",
      "external": true,
      "loc": "fs/squashfs/inode.c:113",
      "file": "fs/squashfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/inode.c:squashfs_iget",
        "fs/squashfs/super.c:squashfs_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582224144,
      "name": "squashfs_read_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2207
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
int squashfs_read_inode(struct inode * inode, long long int ino)
```

```json
{
  "name": "squashfs_read_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582309344,
      "name": "squashfs_read_inode",
      "external": true,
      "loc": "fs/squashfs/inode.c:113",
      "file": "fs/squashfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/inode.c:squashfs_iget",
        "fs/squashfs/super.c:squashfs_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582309344,
      "name": "squashfs_read_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2210
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
int squashfs_read_inode(struct inode * inode, long long int ino)
```

```json
{
  "name": "squashfs_read_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582458512,
      "name": "squashfs_read_inode",
      "external": true,
      "loc": "fs/squashfs/inode.c:113",
      "file": "fs/squashfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/inode.c:squashfs_iget",
        "fs/squashfs/super.c:squashfs_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582458512,
      "name": "squashfs_read_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2215
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
int squashfs_read_inode(struct inode * inode, long long int ino)
```

```json
{
  "name": "squashfs_read_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "squashfs_read_inode",
      "external": true,
      "loc": "fs/squashfs/inode.c:113",
      "file": "fs/squashfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/inode.c:squashfs_iget",
        "fs/squashfs/super.c:squashfs_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582651565,
      "name": "squashfs_read_inode.cold.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    },
    {
      "addr": 18446744071582649232,
      "name": "squashfs_read_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2187
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
int squashfs_read_inode(struct inode * inode, long long int ino)
```

```json
{
  "name": "squashfs_read_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "squashfs_read_inode",
      "external": true,
      "loc": "fs/squashfs/inode.c:113",
      "file": "fs/squashfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/inode.c:squashfs_iget",
        "fs/squashfs/super.c:squashfs_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582753437,
      "name": "squashfs_read_inode.cold.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    },
    {
      "addr": 18446744071582750992,
      "name": "squashfs_read_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2300
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
int squashfs_read_inode(struct inode * inode, long long int ino)
```

```json
{
  "name": "squashfs_read_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "squashfs_read_inode",
      "external": true,
      "loc": "fs/squashfs/inode.c:100",
      "file": "fs/squashfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/inode.c:squashfs_iget",
        "fs/squashfs/super.c:squashfs_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582927700,
      "name": "squashfs_read_inode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446744071582925248,
      "name": "squashfs_read_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2294
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
int squashfs_read_inode(struct inode * inode, long long int ino)
```

```json
{
  "name": "squashfs_read_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "squashfs_read_inode",
      "external": true,
      "loc": "fs/squashfs/inode.c:100",
      "file": "fs/squashfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/inode.c:squashfs_iget",
        "fs/squashfs/super.c:squashfs_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583034276,
      "name": "squashfs_read_inode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446744071583031824,
      "name": "squashfs_read_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2294
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
int squashfs_read_inode(struct inode * inode, long long int ino)
```

```json
{
  "name": "squashfs_read_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "squashfs_read_inode",
      "external": true,
      "loc": "fs/squashfs/inode.c:100",
      "file": "fs/squashfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/inode.c:squashfs_iget",
        "fs/squashfs/super.c:squashfs_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583352036,
      "name": "squashfs_read_inode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446744071583349680,
      "name": "squashfs_read_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2200
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
int squashfs_read_inode(struct inode * inode, long long int ino)
```

```json
{
  "name": "squashfs_read_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "squashfs_read_inode",
      "external": true,
      "loc": "fs/squashfs/inode.c:100",
      "file": "fs/squashfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/inode.c:squashfs_iget",
        "fs/squashfs/super.c:squashfs_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591351487,
      "name": "squashfs_read_inode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446744071583466144,
      "name": "squashfs_read_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2199
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
int squashfs_read_inode(struct inode * inode, long long int ino)
```

```json
{
  "name": "squashfs_read_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "squashfs_read_inode",
      "external": true,
      "loc": "fs/squashfs/inode.c:100",
      "file": "fs/squashfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/inode.c:squashfs_iget",
        "fs/squashfs/super.c:squashfs_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591294371,
      "name": "squashfs_read_inode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071583488320,
      "name": "squashfs_read_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2297
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
int squashfs_read_inode(struct inode * inode, long long int ino)
```

```json
{
  "name": "squashfs_read_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "squashfs_read_inode",
      "external": true,
      "loc": "fs/squashfs/inode.c:100",
      "file": "fs/squashfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/inode.c:squashfs_iget",
        "fs/squashfs/super.c:squashfs_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592276098,
      "name": "squashfs_read_inode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071583842768,
      "name": "squashfs_read_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2289
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
int squashfs_read_inode(struct inode * inode, long long int ino)
```

```json
{
  "name": "squashfs_read_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "squashfs_read_inode",
      "external": true,
      "loc": "fs/squashfs/inode.c:100",
      "file": "fs/squashfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/inode.c:squashfs_iget",
        "fs/squashfs/super.c:squashfs_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594057955,
      "name": "squashfs_read_inode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    },
    {
      "addr": 18446744071584411520,
      "name": "squashfs_read_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2341
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
int squashfs_read_inode(struct inode * inode, long long int ino)
```

```json
{
  "name": "squashfs_read_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585069536,
      "name": "squashfs_read_inode",
      "external": true,
      "loc": "fs/squashfs/inode.c:100",
      "file": "fs/squashfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/inode.c:squashfs_iget",
        "fs/squashfs/super.c:squashfs_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585069536,
      "name": "squashfs_read_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2389
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
int squashfs_read_inode(struct inode * inode, long long int ino)
```

```json
{
  "name": "squashfs_read_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585298864,
      "name": "squashfs_read_inode",
      "external": true,
      "loc": "fs/squashfs/inode.c:100",
      "file": "fs/squashfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/inode.c:squashfs_iget",
        "fs/squashfs/super.c:squashfs_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585298864,
      "name": "squashfs_read_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2499
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
int squashfs_read_inode(struct inode * inode, long long int ino)
```

```json
{
  "name": "squashfs_read_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585532688,
      "name": "squashfs_read_inode",
      "external": true,
      "loc": "fs/squashfs/inode.c:100",
      "file": "fs/squashfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/inode.c:squashfs_iget",
        "fs/squashfs/super.c:squashfs_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585532688,
      "name": "squashfs_read_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2529
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
int squashfs_read_inode(struct inode * inode, long long int ino)
```

```json
{
  "name": "squashfs_read_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494728016,
      "name": "squashfs_read_inode",
      "external": true,
      "loc": "fs/squashfs/inode.c:100",
      "file": "fs/squashfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/inode.c:squashfs_iget",
        "fs/squashfs/super.c:squashfs_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494728016,
      "name": "squashfs_read_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2184
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
int squashfs_read_inode(struct inode * inode, long long int ino)
```

```json
{
  "name": "squashfs_read_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228163064,
      "name": "squashfs_read_inode",
      "external": true,
      "loc": "fs/squashfs/inode.c:100",
      "file": "fs/squashfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/inode.c:squashfs_iget",
        "fs/squashfs/super.c:squashfs_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228163064,
      "name": "squashfs_read_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2600
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
int squashfs_read_inode(struct inode * inode, long long int ino)
```

```json
{
  "name": "squashfs_read_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288551232,
      "name": "squashfs_read_inode",
      "external": true,
      "loc": "fs/squashfs/inode.c:100",
      "file": "fs/squashfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/inode.c:squashfs_iget",
        "fs/squashfs/super.c:squashfs_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288551232,
      "name": "squashfs_read_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2688
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
int squashfs_read_inode(struct inode * inode, long long int ino)
```

```json
{
  "name": "squashfs_read_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274075310,
      "name": "squashfs_read_inode",
      "external": true,
      "loc": "fs/squashfs/inode.c:100",
      "file": "fs/squashfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/inode.c:squashfs_iget",
        "fs/squashfs/super.c:squashfs_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274075310,
      "name": "squashfs_read_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2090
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
int squashfs_read_inode(struct inode * inode, long long int ino)
```

```json
{
  "name": "squashfs_read_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "squashfs_read_inode",
      "external": true,
      "loc": "fs/squashfs/inode.c:100",
      "file": "fs/squashfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/inode.c:squashfs_iget",
        "fs/squashfs/super.c:squashfs_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583003012,
      "name": "squashfs_read_inode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446744071583000560,
      "name": "squashfs_read_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2294
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
int squashfs_read_inode(struct inode * inode, long long int ino)
```

```json
{
  "name": "squashfs_read_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "squashfs_read_inode",
      "external": true,
      "loc": "fs/squashfs/inode.c:100",
      "file": "fs/squashfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/inode.c:squashfs_iget",
        "fs/squashfs/super.c:squashfs_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582940164,
      "name": "squashfs_read_inode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446744071582937712,
      "name": "squashfs_read_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2294
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
int squashfs_read_inode(struct inode * inode, long long int ino)
```

```json
{
  "name": "squashfs_read_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "squashfs_read_inode",
      "external": true,
      "loc": "fs/squashfs/inode.c:100",
      "file": "fs/squashfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/inode.c:squashfs_iget",
        "fs/squashfs/super.c:squashfs_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582991620,
      "name": "squashfs_read_inode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446744071582989168,
      "name": "squashfs_read_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2294
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
int squashfs_read_inode(struct inode * inode, long long int ino)
```

```json
{
  "name": "squashfs_read_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "squashfs_read_inode",
      "external": true,
      "loc": "fs/squashfs/inode.c:100",
      "file": "fs/squashfs/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/inode.c:squashfs_iget",
        "fs/squashfs/super.c:squashfs_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583080756,
      "name": "squashfs_read_inode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446744071583078304,
      "name": "squashfs_read_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2294
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
int squashfs_read_inode(struct inode * inode, long long int ino)
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
