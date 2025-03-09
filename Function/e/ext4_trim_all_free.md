# Function: <code>ext4_trim_all_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_trim_all_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581816710,
      "name": "ext4_trim_all_free",
      "external": false,
      "loc": "fs/ext4/mballoc.c:5095",
      "file": "fs/ext4/mballoc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_trim_fs"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_trim_all_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582012470,
      "name": "ext4_trim_all_free",
      "external": false,
      "loc": "fs/ext4/mballoc.c:5098",
      "file": "fs/ext4/mballoc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_trim_fs"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_trim_all_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582102534,
      "name": "ext4_trim_all_free",
      "external": false,
      "loc": "fs/ext4/mballoc.c:5105",
      "file": "fs/ext4/mballoc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_trim_fs"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_trim_all_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582066678,
      "name": "ext4_trim_all_free",
      "external": false,
      "loc": "fs/ext4/mballoc.c:5171",
      "file": "fs/ext4/mballoc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_trim_fs"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_trim_all_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582216306,
      "name": "ext4_trim_all_free",
      "external": false,
      "loc": "fs/ext4/mballoc.c:5175",
      "file": "fs/ext4/mballoc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_trim_fs"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_trim_all_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582406255,
      "name": "ext4_trim_all_free",
      "external": false,
      "loc": "fs/ext4/mballoc.c:5145",
      "file": "fs/ext4/mballoc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_trim_fs"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_trim_all_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582505519,
      "name": "ext4_trim_all_free",
      "external": false,
      "loc": "fs/ext4/mballoc.c:5152",
      "file": "fs/ext4/mballoc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_trim_fs"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
ext4_grpblk_t ext4_trim_all_free(struct super_block * sb, ext4_group_t group, ext4_grpblk_t start, ext4_grpblk_t max, ext4_grpblk_t minblocks)
```

```json
{
  "name": "ext4_trim_all_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582663232,
      "name": "ext4_trim_all_free",
      "external": false,
      "loc": "fs/ext4/mballoc.c:5154",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_trim_fs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582663232,
      "name": "ext4_trim_all_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1505
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
ext4_grpblk_t ext4_trim_all_free(struct super_block * sb, ext4_group_t group, ext4_grpblk_t start, ext4_grpblk_t max, ext4_grpblk_t minblocks)
```

```json
{
  "name": "ext4_trim_all_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582765232,
      "name": "ext4_trim_all_free",
      "external": false,
      "loc": "fs/ext4/mballoc.c:5175",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_trim_fs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582765232,
      "name": "ext4_trim_all_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1505
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
ext4_grpblk_t ext4_trim_all_free(struct super_block * sb, ext4_group_t group, ext4_grpblk_t start, ext4_grpblk_t max, ext4_grpblk_t minblocks)
```

```json
{
  "name": "ext4_trim_all_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583076752,
      "name": "ext4_trim_all_free",
      "external": false,
      "loc": "fs/ext4/mballoc.c:5420",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_trim_fs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583076752,
      "name": "ext4_trim_all_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1219
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
ext4_grpblk_t ext4_trim_all_free(struct super_block * sb, ext4_group_t group, ext4_grpblk_t start, ext4_grpblk_t max, ext4_grpblk_t minblocks)
```

```json
{
  "name": "ext4_trim_all_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583151744,
      "name": "ext4_trim_all_free",
      "external": false,
      "loc": "fs/ext4/mballoc.c:5707",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_trim_fs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583151744,
      "name": "ext4_trim_all_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1206
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
ext4_grpblk_t ext4_trim_all_free(struct super_block * sb, ext4_group_t group, ext4_grpblk_t start, ext4_grpblk_t max, ext4_grpblk_t minblocks)
```

```json
{
  "name": "ext4_trim_all_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583176960,
      "name": "ext4_trim_all_free",
      "external": false,
      "loc": "fs/ext4/mballoc.c:6240",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_trim_fs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583176960,
      "name": "ext4_trim_all_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1380
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
ext4_grpblk_t ext4_trim_all_free(struct super_block * sb, ext4_group_t group, ext4_grpblk_t start, ext4_grpblk_t max, ext4_grpblk_t minblocks)
```

```json
{
  "name": "ext4_trim_all_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583516768,
      "name": "ext4_trim_all_free",
      "external": false,
      "loc": "fs/ext4/mballoc.c:6362",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_trim_fs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583516768,
      "name": "ext4_trim_all_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 455
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
ext4_grpblk_t ext4_trim_all_free(struct super_block * sb, ext4_group_t group, ext4_grpblk_t start, ext4_grpblk_t max, ext4_grpblk_t minblocks, bool set_trimmed)
```

```json
{
  "name": "ext4_trim_all_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584049280,
      "name": "ext4_trim_all_free",
      "external": false,
      "loc": "fs/ext4/mballoc.c:6449",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_trim_fs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584049280,
      "name": "ext4_trim_all_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 501
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
ext4_grpblk_t ext4_trim_all_free(struct super_block * sb, ext4_group_t group, ext4_grpblk_t start, ext4_grpblk_t max, ext4_grpblk_t minblocks, bool set_trimmed)
```

```json
{
  "name": "ext4_trim_all_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584681312,
      "name": "ext4_trim_all_free",
      "external": false,
      "loc": "fs/ext4/mballoc.c:6418",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_trim_fs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584681312,
      "name": "ext4_trim_all_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 722
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
ext4_grpblk_t ext4_trim_all_free(struct super_block * sb, ext4_group_t group, ext4_grpblk_t start, ext4_grpblk_t max, ext4_grpblk_t minblocks, bool set_trimmed)
```

```json
{
  "name": "ext4_trim_all_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584906672,
      "name": "ext4_trim_all_free",
      "external": false,
      "loc": "fs/ext4/mballoc.c:6994",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_trim_fs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584906672,
      "name": "ext4_trim_all_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 501
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
ext4_grpblk_t ext4_trim_all_free(struct super_block * sb, ext4_group_t group, ext4_grpblk_t start, ext4_grpblk_t max, ext4_grpblk_t minblocks)
```

```json
{
  "name": "ext4_trim_all_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585135120,
      "name": "ext4_trim_all_free",
      "external": false,
      "loc": "fs/ext4/mballoc.c:6841",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_trim_fs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585135120,
      "name": "ext4_trim_all_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 485
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
ext4_grpblk_t ext4_trim_all_free(struct super_block * sb, ext4_group_t group, ext4_grpblk_t start, ext4_grpblk_t max, ext4_grpblk_t minblocks)
```

```json
{
  "name": "ext4_trim_all_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494431784,
      "name": "ext4_trim_all_free",
      "external": false,
      "loc": "fs/ext4/mballoc.c:5175",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_trim_fs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494431784,
      "name": "ext4_trim_all_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1312
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
ext4_grpblk_t ext4_trim_all_free(struct super_block * sb, ext4_group_t group, ext4_grpblk_t start, ext4_grpblk_t max, ext4_grpblk_t minblocks)
```

```json
{
  "name": "ext4_trim_all_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227866036,
      "name": "ext4_trim_all_free",
      "external": false,
      "loc": "fs/ext4/mballoc.c:5175",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_trim_fs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227866036,
      "name": "ext4_trim_all_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2068
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
ext4_grpblk_t ext4_trim_all_free(struct super_block * sb, ext4_group_t group, ext4_grpblk_t start, ext4_grpblk_t max, ext4_grpblk_t minblocks)
```

```json
{
  "name": "ext4_trim_all_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288180048,
      "name": "ext4_trim_all_free",
      "external": false,
      "loc": "fs/ext4/mballoc.c:5175",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_trim_fs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288180048,
      "name": "ext4_trim_all_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2064
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
ext4_grpblk_t ext4_trim_all_free(struct super_block * sb, ext4_group_t group, ext4_grpblk_t start, ext4_grpblk_t max, ext4_grpblk_t minblocks)
```

```json
{
  "name": "ext4_trim_all_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273844448,
      "name": "ext4_trim_all_free",
      "external": false,
      "loc": "fs/ext4/mballoc.c:5175",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_trim_fs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273844448,
      "name": "ext4_trim_all_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1634
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
ext4_grpblk_t ext4_trim_all_free(struct super_block * sb, ext4_group_t group, ext4_grpblk_t start, ext4_grpblk_t max, ext4_grpblk_t minblocks)
```

```json
{
  "name": "ext4_trim_all_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582733968,
      "name": "ext4_trim_all_free",
      "external": false,
      "loc": "fs/ext4/mballoc.c:5175",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_trim_fs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582733968,
      "name": "ext4_trim_all_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1505
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
ext4_grpblk_t ext4_trim_all_free(struct super_block * sb, ext4_group_t group, ext4_grpblk_t start, ext4_grpblk_t max, ext4_grpblk_t minblocks)
```

```json
{
  "name": "ext4_trim_all_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582671136,
      "name": "ext4_trim_all_free",
      "external": false,
      "loc": "fs/ext4/mballoc.c:5175",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_trim_fs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582671136,
      "name": "ext4_trim_all_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1505
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
ext4_grpblk_t ext4_trim_all_free(struct super_block * sb, ext4_group_t group, ext4_grpblk_t start, ext4_grpblk_t max, ext4_grpblk_t minblocks)
```

```json
{
  "name": "ext4_trim_all_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582723824,
      "name": "ext4_trim_all_free",
      "external": false,
      "loc": "fs/ext4/mballoc.c:5175",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_trim_fs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582723824,
      "name": "ext4_trim_all_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1505
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
ext4_grpblk_t ext4_trim_all_free(struct super_block * sb, ext4_group_t group, ext4_grpblk_t start, ext4_grpblk_t max, ext4_grpblk_t minblocks)
```

```json
{
  "name": "ext4_trim_all_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582808640,
      "name": "ext4_trim_all_free",
      "external": false,
      "loc": "fs/ext4/mballoc.c:5175",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_trim_fs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582808640,
      "name": "ext4_trim_all_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1559
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
ext4_grpblk_t ext4_trim_all_free(struct super_block * sb, ext4_group_t group, ext4_grpblk_t start, ext4_grpblk_t max, ext4_grpblk_t minblocks)
```
</details>
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool set_trimmed</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool set_trimmed</code>
</li>
</ul>
</details>
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
