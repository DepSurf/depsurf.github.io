# Function: <code>ext4_orphan_get</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct inode * ext4_orphan_get(struct super_block * sb, long unsigned int ino)
```

```json
{
  "name": "ext4_orphan_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581554160,
      "name": "ext4_orphan_get",
      "external": true,
      "loc": "fs/ext4/ialloc.c:1144",
      "file": "fs/ext4/ialloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581554160,
      "name": "ext4_orphan_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 522
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
struct inode * ext4_orphan_get(struct super_block * sb, long unsigned int ino)
```

```json
{
  "name": "ext4_orphan_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581740080,
      "name": "ext4_orphan_get",
      "external": true,
      "loc": "fs/ext4/ialloc.c:1152",
      "file": "fs/ext4/ialloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581740080,
      "name": "ext4_orphan_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 622
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
struct inode * ext4_orphan_get(struct super_block * sb, long unsigned int ino)
```

```json
{
  "name": "ext4_orphan_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581827616,
      "name": "ext4_orphan_get",
      "external": true,
      "loc": "fs/ext4/ialloc.c:1152",
      "file": "fs/ext4/ialloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581827616,
      "name": "ext4_orphan_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 622
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
struct inode * ext4_orphan_get(struct super_block * sb, long unsigned int ino)
```

```json
{
  "name": "ext4_orphan_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581951408,
      "name": "ext4_orphan_get",
      "external": true,
      "loc": "fs/ext4/ialloc.c:1204",
      "file": "fs/ext4/ialloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581951408,
      "name": "ext4_orphan_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 745
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
struct inode * ext4_orphan_get(struct super_block * sb, long unsigned int ino)
```

```json
{
  "name": "ext4_orphan_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582100448,
      "name": "ext4_orphan_get",
      "external": true,
      "loc": "fs/ext4/ialloc.c:1232",
      "file": "fs/ext4/ialloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582100448,
      "name": "ext4_orphan_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 745
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
struct inode * ext4_orphan_get(struct super_block * sb, long unsigned int ino)
```

```json
{
  "name": "ext4_orphan_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_orphan_get",
      "external": true,
      "loc": "fs/ext4/ialloc.c:1207",
      "file": "fs/ext4/ialloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582290552,
      "name": "ext4_orphan_get.cold.26",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
    },
    {
      "addr": 18446744071582288752,
      "name": "ext4_orphan_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 634
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
struct inode * ext4_orphan_get(struct super_block * sb, long unsigned int ino)
```

```json
{
  "name": "ext4_orphan_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_orphan_get",
      "external": true,
      "loc": "fs/ext4/ialloc.c:1207",
      "file": "fs/ext4/ialloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582389304,
      "name": "ext4_orphan_get.cold.27",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
    },
    {
      "addr": 18446744071582387488,
      "name": "ext4_orphan_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 649
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
struct inode * ext4_orphan_get(struct super_block * sb, long unsigned int ino)
```

```json
{
  "name": "ext4_orphan_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_orphan_get",
      "external": true,
      "loc": "fs/ext4/ialloc.c:1207",
      "file": "fs/ext4/ialloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582557368,
      "name": "ext4_orphan_get.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
    },
    {
      "addr": 18446744071582555680,
      "name": "ext4_orphan_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 560
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
struct inode * ext4_orphan_get(struct super_block * sb, long unsigned int ino)
```

```json
{
  "name": "ext4_orphan_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_orphan_get",
      "external": true,
      "loc": "fs/ext4/ialloc.c:1203",
      "file": "fs/ext4/ialloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582658307,
      "name": "ext4_orphan_get.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
    },
    {
      "addr": 18446744071582656576,
      "name": "ext4_orphan_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 560
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
struct inode * ext4_orphan_get(struct super_block * sb, long unsigned int ino)
```

```json
{
  "name": "ext4_orphan_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582967936,
      "name": "ext4_orphan_get",
      "external": true,
      "loc": "fs/ext4/ialloc.c:1218",
      "file": "fs/ext4/ialloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_orphan_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582967936,
      "name": "ext4_orphan_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 787
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
struct inode * ext4_orphan_get(struct super_block * sb, long unsigned int ino)
```

```json
{
  "name": "ext4_orphan_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583043552,
      "name": "ext4_orphan_get",
      "external": true,
      "loc": "fs/ext4/ialloc.c:1360",
      "file": "fs/ext4/ialloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_orphan_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583043552,
      "name": "ext4_orphan_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 802
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
struct inode * ext4_orphan_get(struct super_block * sb, long unsigned int ino)
```

```json
{
  "name": "ext4_orphan_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583069472,
      "name": "ext4_orphan_get",
      "external": true,
      "loc": "fs/ext4/ialloc.c:1363",
      "file": "fs/ext4/ialloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_orphan_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583069472,
      "name": "ext4_orphan_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 803
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
struct inode * ext4_orphan_get(struct super_block * sb, long unsigned int ino)
```

```json
{
  "name": "ext4_orphan_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583407552,
      "name": "ext4_orphan_get",
      "external": true,
      "loc": "fs/ext4/ialloc.c:1368",
      "file": "fs/ext4/ialloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/orphan.c:ext4_orphan_cleanup",
        "fs/ext4/orphan.c:ext4_orphan_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583407552,
      "name": "ext4_orphan_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 803
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
struct inode * ext4_orphan_get(struct super_block * sb, long unsigned int ino)
```

```json
{
  "name": "ext4_orphan_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583922784,
      "name": "ext4_orphan_get",
      "external": true,
      "loc": "fs/ext4/ialloc.c:1368",
      "file": "fs/ext4/ialloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/orphan.c:ext4_orphan_cleanup",
        "fs/ext4/orphan.c:ext4_orphan_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583922784,
      "name": "ext4_orphan_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 837
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
struct inode * ext4_orphan_get(struct super_block * sb, long unsigned int ino)
```

```json
{
  "name": "ext4_orphan_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584548816,
      "name": "ext4_orphan_get",
      "external": true,
      "loc": "fs/ext4/ialloc.c:1367",
      "file": "fs/ext4/ialloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/orphan.c:ext4_orphan_cleanup",
        "fs/ext4/orphan.c:ext4_orphan_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584548816,
      "name": "ext4_orphan_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 802
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
struct inode * ext4_orphan_get(struct super_block * sb, long unsigned int ino)
```

```json
{
  "name": "ext4_orphan_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584777664,
      "name": "ext4_orphan_get",
      "external": true,
      "loc": "fs/ext4/ialloc.c:1369",
      "file": "fs/ext4/ialloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/orphan.c:ext4_orphan_cleanup",
        "fs/ext4/orphan.c:ext4_orphan_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584777664,
      "name": "ext4_orphan_get",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct inode * ext4_orphan_get(struct super_block * sb, long unsigned int ino)
```

```json
{
  "name": "ext4_orphan_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585010544,
      "name": "ext4_orphan_get",
      "external": true,
      "loc": "fs/ext4/ialloc.c:1369",
      "file": "fs/ext4/ialloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/orphan.c:ext4_orphan_cleanup",
        "fs/ext4/orphan.c:ext4_orphan_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585010544,
      "name": "ext4_orphan_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 776
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
struct inode * ext4_orphan_get(struct super_block * sb, long unsigned int ino)
```

```json
{
  "name": "ext4_orphan_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494308968,
      "name": "ext4_orphan_get",
      "external": true,
      "loc": "fs/ext4/ialloc.c:1203",
      "file": "fs/ext4/ialloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494308968,
      "name": "ext4_orphan_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 856
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
struct inode * ext4_orphan_get(struct super_block * sb, long unsigned int ino)
```

```json
{
  "name": "ext4_orphan_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227744428,
      "name": "ext4_orphan_get",
      "external": true,
      "loc": "fs/ext4/ialloc.c:1203",
      "file": "fs/ext4/ialloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227744428,
      "name": "ext4_orphan_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 808
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
struct inode * ext4_orphan_get(struct super_block * sb, long unsigned int ino)
```

```json
{
  "name": "ext4_orphan_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288028304,
      "name": "ext4_orphan_get",
      "external": true,
      "loc": "fs/ext4/ialloc.c:1203",
      "file": "fs/ext4/ialloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288028304,
      "name": "ext4_orphan_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1100
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
struct inode * ext4_orphan_get(struct super_block * sb, long unsigned int ino)
```

```json
{
  "name": "ext4_orphan_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273750070,
      "name": "ext4_orphan_get",
      "external": true,
      "loc": "fs/ext4/ialloc.c:1203",
      "file": "fs/ext4/ialloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273750070,
      "name": "ext4_orphan_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 754
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
struct inode * ext4_orphan_get(struct super_block * sb, long unsigned int ino)
```

```json
{
  "name": "ext4_orphan_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_orphan_get",
      "external": true,
      "loc": "fs/ext4/ialloc.c:1203",
      "file": "fs/ext4/ialloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582627043,
      "name": "ext4_orphan_get.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
    },
    {
      "addr": 18446744071582625312,
      "name": "ext4_orphan_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 560
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
struct inode * ext4_orphan_get(struct super_block * sb, long unsigned int ino)
```

```json
{
  "name": "ext4_orphan_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_orphan_get",
      "external": true,
      "loc": "fs/ext4/ialloc.c:1203",
      "file": "fs/ext4/ialloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582564211,
      "name": "ext4_orphan_get.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
    },
    {
      "addr": 18446744071582562480,
      "name": "ext4_orphan_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 560
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
struct inode * ext4_orphan_get(struct super_block * sb, long unsigned int ino)
```

```json
{
  "name": "ext4_orphan_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_orphan_get",
      "external": true,
      "loc": "fs/ext4/ialloc.c:1203",
      "file": "fs/ext4/ialloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582616899,
      "name": "ext4_orphan_get.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
    },
    {
      "addr": 18446744071582615168,
      "name": "ext4_orphan_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 560
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
struct inode * ext4_orphan_get(struct super_block * sb, long unsigned int ino)
```

```json
{
  "name": "ext4_orphan_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_orphan_get",
      "external": true,
      "loc": "fs/ext4/ialloc.c:1203",
      "file": "fs/ext4/ialloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582699881,
      "name": "ext4_orphan_get.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
    },
    {
      "addr": 18446744071582698144,
      "name": "ext4_orphan_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 560
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
