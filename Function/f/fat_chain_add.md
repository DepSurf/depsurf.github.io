# Function: <code>fat_chain_add</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int fat_chain_add(struct inode * inode, int new_dclus, int nr_cluster)
```

```json
{
  "name": "fat_chain_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581983456,
      "name": "fat_chain_add",
      "external": true,
      "loc": "fs/fat/misc.c:99",
      "file": "fs/fat/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/inode.c:fat_get_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581983456,
      "name": "fat_chain_add",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int fat_chain_add(struct inode * inode, int new_dclus, int nr_cluster)
```

```json
{
  "name": "fat_chain_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582196448,
      "name": "fat_chain_add",
      "external": true,
      "loc": "fs/fat/misc.c:99",
      "file": "fs/fat/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/inode.c:fat_add_cluster"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582196448,
      "name": "fat_chain_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 514
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
int fat_chain_add(struct inode * inode, int new_dclus, int nr_cluster)
```

```json
{
  "name": "fat_chain_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582285952,
      "name": "fat_chain_add",
      "external": true,
      "loc": "fs/fat/misc.c:99",
      "file": "fs/fat/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/inode.c:fat_add_cluster"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582285952,
      "name": "fat_chain_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 514
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
int fat_chain_add(struct inode * inode, int new_dclus, int nr_cluster)
```

```json
{
  "name": "fat_chain_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582370448,
      "name": "fat_chain_add",
      "external": true,
      "loc": "fs/fat/misc.c:99",
      "file": "fs/fat/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/inode.c:fat_add_cluster"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582370448,
      "name": "fat_chain_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 514
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
int fat_chain_add(struct inode * inode, int new_dclus, int nr_cluster)
```

```json
{
  "name": "fat_chain_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582521232,
      "name": "fat_chain_add",
      "external": true,
      "loc": "fs/fat/misc.c:99",
      "file": "fs/fat/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/inode.c:fat_add_cluster"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582521232,
      "name": "fat_chain_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 514
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
int fat_chain_add(struct inode * inode, int new_dclus, int nr_cluster)
```

```json
{
  "name": "fat_chain_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fat_chain_add",
      "external": true,
      "loc": "fs/fat/misc.c:99",
      "file": "fs/fat/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/inode.c:fat_add_cluster"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582713981,
      "name": "fat_chain_add.cold.4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071582712656,
      "name": "fat_chain_add",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
int fat_chain_add(struct inode * inode, int new_dclus, int nr_cluster)
```

```json
{
  "name": "fat_chain_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fat_chain_add",
      "external": true,
      "loc": "fs/fat/misc.c:100",
      "file": "fs/fat/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/inode.c:fat_add_cluster"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582818013,
      "name": "fat_chain_add.cold.9",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071582816688,
      "name": "fat_chain_add",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int fat_chain_add(struct inode * inode, int new_dclus, int nr_cluster)
```

```json
{
  "name": "fat_chain_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fat_chain_add",
      "external": true,
      "loc": "fs/fat/misc.c:101",
      "file": "fs/fat/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/inode.c:fat_add_cluster"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582992989,
      "name": "fat_chain_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071582991680,
      "name": "fat_chain_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 440
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
int fat_chain_add(struct inode * inode, int new_dclus, int nr_cluster)
```

```json
{
  "name": "fat_chain_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fat_chain_add",
      "external": true,
      "loc": "fs/fat/misc.c:101",
      "file": "fs/fat/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/inode.c:fat_add_cluster"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583099181,
      "name": "fat_chain_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071583097872,
      "name": "fat_chain_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 440
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
int fat_chain_add(struct inode * inode, int new_dclus, int nr_cluster)
```

```json
{
  "name": "fat_chain_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fat_chain_add",
      "external": true,
      "loc": "fs/fat/misc.c:101",
      "file": "fs/fat/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/inode.c:fat_add_cluster"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583418141,
      "name": "fat_chain_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071583416816,
      "name": "fat_chain_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 440
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
int fat_chain_add(struct inode * inode, int new_dclus, int nr_cluster)
```

```json
{
  "name": "fat_chain_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fat_chain_add",
      "external": true,
      "loc": "fs/fat/misc.c:101",
      "file": "fs/fat/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/inode.c:fat_add_cluster"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591354060,
      "name": "fat_chain_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071583531248,
      "name": "fat_chain_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 440
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
int fat_chain_add(struct inode * inode, int new_dclus, int nr_cluster)
```

```json
{
  "name": "fat_chain_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fat_chain_add",
      "external": true,
      "loc": "fs/fat/misc.c:101",
      "file": "fs/fat/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/inode.c:fat_add_cluster"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591296982,
      "name": "fat_chain_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071583554432,
      "name": "fat_chain_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 436
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
int fat_chain_add(struct inode * inode, int new_dclus, int nr_cluster)
```

```json
{
  "name": "fat_chain_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fat_chain_add",
      "external": true,
      "loc": "fs/fat/misc.c:101",
      "file": "fs/fat/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/inode.c:fat_add_cluster"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592281702,
      "name": "fat_chain_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
    },
    {
      "addr": 18446744071583912960,
      "name": "fat_chain_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 499
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
int fat_chain_add(struct inode * inode, int new_dclus, int nr_cluster)
```

```json
{
  "name": "fat_chain_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fat_chain_add",
      "external": true,
      "loc": "fs/fat/misc.c:107",
      "file": "fs/fat/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/inode.c:fat_add_cluster"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594064098,
      "name": "fat_chain_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
    },
    {
      "addr": 18446744071584490560,
      "name": "fat_chain_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 514
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
int fat_chain_add(struct inode * inode, int new_dclus, int nr_cluster)
```

```json
{
  "name": "fat_chain_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fat_chain_add",
      "external": true,
      "loc": "fs/fat/misc.c:107",
      "file": "fs/fat/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/inode.c:fat_add_cluster"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596090332,
      "name": "fat_chain_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    },
    {
      "addr": 18446744071585156560,
      "name": "fat_chain_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 545
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
int fat_chain_add(struct inode * inode, int new_dclus, int nr_cluster)
```

```json
{
  "name": "fat_chain_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fat_chain_add",
      "external": true,
      "loc": "fs/fat/misc.c:107",
      "file": "fs/fat/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/inode.c:fat_add_cluster"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596613631,
      "name": "fat_chain_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
    },
    {
      "addr": 18446744071585385696,
      "name": "fat_chain_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 545
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
int fat_chain_add(struct inode * inode, int new_dclus, int nr_cluster)
```

```json
{
  "name": "fat_chain_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fat_chain_add",
      "external": true,
      "loc": "fs/fat/misc.c:107",
      "file": "fs/fat/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/inode.c:fat_add_cluster"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597519585,
      "name": "fat_chain_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
    },
    {
      "addr": 18446744071585620560,
      "name": "fat_chain_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 545
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
int fat_chain_add(struct inode * inode, int new_dclus, int nr_cluster)
```

```json
{
  "name": "fat_chain_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494804928,
      "name": "fat_chain_add",
      "external": true,
      "loc": "fs/fat/misc.c:101",
      "file": "fs/fat/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/inode.c:fat_add_cluster"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494804928,
      "name": "fat_chain_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 476
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
int fat_chain_add(struct inode * inode, int new_dclus, int nr_cluster)
```

```json
{
  "name": "fat_chain_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228224260,
      "name": "fat_chain_add",
      "external": true,
      "loc": "fs/fat/misc.c:101",
      "file": "fs/fat/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/inode.c:fat_add_cluster"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228224260,
      "name": "fat_chain_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 536
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
int fat_chain_add(struct inode * inode, int new_dclus, int nr_cluster)
```

```json
{
  "name": "fat_chain_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288643984,
      "name": "fat_chain_add",
      "external": true,
      "loc": "fs/fat/misc.c:101",
      "file": "fs/fat/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/inode.c:fat_add_cluster"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288643984,
      "name": "fat_chain_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 656
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
int fat_chain_add(struct inode * inode, int new_dclus, int nr_cluster)
```

```json
{
  "name": "fat_chain_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274133100,
      "name": "fat_chain_add",
      "external": true,
      "loc": "fs/fat/misc.c:101",
      "file": "fs/fat/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/inode.c:fat_add_cluster"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274133100,
      "name": "fat_chain_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 394
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
int fat_chain_add(struct inode * inode, int new_dclus, int nr_cluster)
```

```json
{
  "name": "fat_chain_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fat_chain_add",
      "external": true,
      "loc": "fs/fat/misc.c:101",
      "file": "fs/fat/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/inode.c:fat_add_cluster"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583067917,
      "name": "fat_chain_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071583066608,
      "name": "fat_chain_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 440
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
int fat_chain_add(struct inode * inode, int new_dclus, int nr_cluster)
```

```json
{
  "name": "fat_chain_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fat_chain_add",
      "external": true,
      "loc": "fs/fat/misc.c:101",
      "file": "fs/fat/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/inode.c:fat_add_cluster"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583005069,
      "name": "fat_chain_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071583003760,
      "name": "fat_chain_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 440
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
int fat_chain_add(struct inode * inode, int new_dclus, int nr_cluster)
```

```json
{
  "name": "fat_chain_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fat_chain_add",
      "external": true,
      "loc": "fs/fat/misc.c:101",
      "file": "fs/fat/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/inode.c:fat_add_cluster"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583056525,
      "name": "fat_chain_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071583055216,
      "name": "fat_chain_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 440
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
int fat_chain_add(struct inode * inode, int new_dclus, int nr_cluster)
```

```json
{
  "name": "fat_chain_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fat_chain_add",
      "external": true,
      "loc": "fs/fat/misc.c:101",
      "file": "fs/fat/misc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/dir.c:fat_add_entries",
        "fs/fat/inode.c:fat_add_cluster"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583145712,
      "name": "fat_chain_add.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071583144416,
      "name": "fat_chain_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 440
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
