# Function: <code>squashfs_readpage_block</code>

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
int squashfs_readpage_block(struct page * target_page, u64 block, int bsize)
```

```json
{
  "name": "squashfs_readpage_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582141616,
      "name": "squashfs_readpage_block",
      "external": true,
      "loc": "fs/squashfs/file_direct.c:27",
      "file": "fs/squashfs/file_direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/file.c:squashfs_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582141616,
      "name": "squashfs_readpage_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1690
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
int squashfs_readpage_block(struct page * target_page, u64 block, int bsize)
```

```json
{
  "name": "squashfs_readpage_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582231312,
      "name": "squashfs_readpage_block",
      "external": true,
      "loc": "fs/squashfs/file_direct.c:27",
      "file": "fs/squashfs/file_direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/file.c:squashfs_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582231312,
      "name": "squashfs_readpage_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1672
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
int squashfs_readpage_block(struct page * target_page, u64 block, int bsize)
```

```json
{
  "name": "squashfs_readpage_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582316416,
      "name": "squashfs_readpage_block",
      "external": true,
      "loc": "fs/squashfs/file_direct.c:27",
      "file": "fs/squashfs/file_direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/file.c:squashfs_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582316416,
      "name": "squashfs_readpage_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1366
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
int squashfs_readpage_block(struct page * target_page, u64 block, int bsize)
```

```json
{
  "name": "squashfs_readpage_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582465584,
      "name": "squashfs_readpage_block",
      "external": true,
      "loc": "fs/squashfs/file_direct.c:27",
      "file": "fs/squashfs/file_direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/file.c:squashfs_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582465584,
      "name": "squashfs_readpage_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1571
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
int squashfs_readpage_block(struct page * target_page, u64 block, int bsize, int expected)
```

```json
{
  "name": "squashfs_readpage_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "squashfs_readpage_block",
      "external": true,
      "loc": "fs/squashfs/file_direct.c:27",
      "file": "fs/squashfs/file_direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/file.c:squashfs_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582658111,
      "name": "squashfs_readpage_block.cold.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    },
    {
      "addr": 18446744071582656736,
      "name": "squashfs_readpage_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1375
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
int squashfs_readpage_block(struct page * target_page, u64 block, int bsize, int expected)
```

```json
{
  "name": "squashfs_readpage_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "squashfs_readpage_block",
      "external": true,
      "loc": "fs/squashfs/file_direct.c:27",
      "file": "fs/squashfs/file_direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/file.c:squashfs_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582759998,
      "name": "squashfs_readpage_block.cold.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071582758592,
      "name": "squashfs_readpage_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1406
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
int squashfs_readpage_block(struct page * target_page, u64 block, int bsize, int expected)
```

```json
{
  "name": "squashfs_readpage_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "squashfs_readpage_block",
      "external": true,
      "loc": "fs/squashfs/file_direct.c:25",
      "file": "fs/squashfs/file_direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/file.c:squashfs_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582934228,
      "name": "squashfs_readpage_block.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    },
    {
      "addr": 18446744071582932832,
      "name": "squashfs_readpage_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1396
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
int squashfs_readpage_block(struct page * target_page, u64 block, int bsize, int expected)
```

```json
{
  "name": "squashfs_readpage_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "squashfs_readpage_block",
      "external": true,
      "loc": "fs/squashfs/file_direct.c:25",
      "file": "fs/squashfs/file_direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/file.c:squashfs_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583040842,
      "name": "squashfs_readpage_block.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    },
    {
      "addr": 18446744071583039424,
      "name": "squashfs_readpage_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1418
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
int squashfs_readpage_block(struct page * target_page, u64 block, int bsize, int expected)
```

```json
{
  "name": "squashfs_readpage_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583357664,
      "name": "squashfs_readpage_block",
      "external": true,
      "loc": "fs/squashfs/file_direct.c:25",
      "file": "fs/squashfs/file_direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/file.c:squashfs_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583357664,
      "name": "squashfs_readpage_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1165
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
int squashfs_readpage_block(struct page * target_page, u64 block, int bsize, int expected)
```

```json
{
  "name": "squashfs_readpage_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583473824,
      "name": "squashfs_readpage_block",
      "external": true,
      "loc": "fs/squashfs/file_direct.c:25",
      "file": "fs/squashfs/file_direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/file.c:squashfs_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583473824,
      "name": "squashfs_readpage_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1156
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
int squashfs_readpage_block(struct page * target_page, u64 block, int bsize, int expected)
```

```json
{
  "name": "squashfs_readpage_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "squashfs_readpage_block",
      "external": true,
      "loc": "fs/squashfs/file_direct.c:25",
      "file": "fs/squashfs/file_direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/file.c:squashfs_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591294679,
      "name": "squashfs_readpage_block.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071583495792,
      "name": "squashfs_readpage_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1397
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
int squashfs_readpage_block(struct page * target_page, u64 block, int bsize, int expected)
```

```json
{
  "name": "squashfs_readpage_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "squashfs_readpage_block",
      "external": true,
      "loc": "fs/squashfs/file_direct.c:25",
      "file": "fs/squashfs/file_direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/file.c:squashfs_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592276455,
      "name": "squashfs_readpage_block.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    },
    {
      "addr": 18446744071583850704,
      "name": "squashfs_readpage_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1410
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
int squashfs_readpage_block(struct page * target_page, u64 block, int bsize, int expected)
```

```json
{
  "name": "squashfs_readpage_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "squashfs_readpage_block",
      "external": true,
      "loc": "fs/squashfs/file_direct.c:25",
      "file": "fs/squashfs/file_direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/file.c:squashfs_read_folio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594058384,
      "name": "squashfs_readpage_block.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071584419984,
      "name": "squashfs_readpage_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1793
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
int squashfs_readpage_block(struct page * target_page, u64 block, int bsize, int expected)
```

```json
{
  "name": "squashfs_readpage_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "squashfs_readpage_block",
      "external": true,
      "loc": "fs/squashfs/file_direct.c:22",
      "file": "fs/squashfs/file_direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/file.c:squashfs_read_folio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596087077,
      "name": "squashfs_readpage_block.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071585079856,
      "name": "squashfs_readpage_block",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int squashfs_readpage_block(struct page * target_page, u64 block, int bsize, int expected)
```

```json
{
  "name": "squashfs_readpage_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "squashfs_readpage_block",
      "external": true,
      "loc": "fs/squashfs/file_direct.c:22",
      "file": "fs/squashfs/file_direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/file.c:squashfs_read_folio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596610494,
      "name": "squashfs_readpage_block.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071585309472,
      "name": "squashfs_readpage_block",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int squashfs_readpage_block(struct page * target_page, u64 block, int bsize, int expected)
```

```json
{
  "name": "squashfs_readpage_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "squashfs_readpage_block",
      "external": true,
      "loc": "fs/squashfs/file_direct.c:22",
      "file": "fs/squashfs/file_direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/file.c:squashfs_read_folio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597516384,
      "name": "squashfs_readpage_block.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071585543744,
      "name": "squashfs_readpage_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1337
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
int squashfs_readpage_block(struct page * target_page, u64 block, int bsize, int expected)
```

```json
{
  "name": "squashfs_readpage_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494735368,
      "name": "squashfs_readpage_block",
      "external": true,
      "loc": "fs/squashfs/file_direct.c:25",
      "file": "fs/squashfs/file_direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/file.c:squashfs_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494735368,
      "name": "squashfs_readpage_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1292
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
int squashfs_readpage_block(struct page * target_page, u64 block, int bsize, int expected)
```

```json
{
  "name": "squashfs_readpage_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228171232,
      "name": "squashfs_readpage_block",
      "external": true,
      "loc": "fs/squashfs/file_direct.c:25",
      "file": "fs/squashfs/file_direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/file.c:squashfs_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228171232,
      "name": "squashfs_readpage_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1356
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
int squashfs_readpage_block(struct page * target_page, u64 block, int bsize, int expected)
```

```json
{
  "name": "squashfs_readpage_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288560768,
      "name": "squashfs_readpage_block",
      "external": true,
      "loc": "fs/squashfs/file_direct.c:25",
      "file": "fs/squashfs/file_direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/file.c:squashfs_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288560768,
      "name": "squashfs_readpage_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1992
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
int squashfs_readpage_block(struct page * target_page, u64 block, int bsize, int expected)
```

```json
{
  "name": "squashfs_readpage_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274082318,
      "name": "squashfs_readpage_block",
      "external": true,
      "loc": "fs/squashfs/file_direct.c:25",
      "file": "fs/squashfs/file_direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/file.c:squashfs_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274082318,
      "name": "squashfs_readpage_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1122
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
int squashfs_readpage_block(struct page * target_page, u64 block, int bsize, int expected)
```

```json
{
  "name": "squashfs_readpage_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "squashfs_readpage_block",
      "external": true,
      "loc": "fs/squashfs/file_direct.c:25",
      "file": "fs/squashfs/file_direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/file.c:squashfs_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583009578,
      "name": "squashfs_readpage_block.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    },
    {
      "addr": 18446744071583008160,
      "name": "squashfs_readpage_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1418
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
int squashfs_readpage_block(struct page * target_page, u64 block, int bsize, int expected)
```

```json
{
  "name": "squashfs_readpage_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "squashfs_readpage_block",
      "external": true,
      "loc": "fs/squashfs/file_direct.c:25",
      "file": "fs/squashfs/file_direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/file.c:squashfs_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582946730,
      "name": "squashfs_readpage_block.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    },
    {
      "addr": 18446744071582945312,
      "name": "squashfs_readpage_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1418
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
int squashfs_readpage_block(struct page * target_page, u64 block, int bsize, int expected)
```

```json
{
  "name": "squashfs_readpage_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "squashfs_readpage_block",
      "external": true,
      "loc": "fs/squashfs/file_direct.c:25",
      "file": "fs/squashfs/file_direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/file.c:squashfs_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582998186,
      "name": "squashfs_readpage_block.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    },
    {
      "addr": 18446744071582996768,
      "name": "squashfs_readpage_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1418
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
int squashfs_readpage_block(struct page * target_page, u64 block, int bsize, int expected)
```

```json
{
  "name": "squashfs_readpage_block",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "squashfs_readpage_block",
      "external": true,
      "loc": "fs/squashfs/file_direct.c:25",
      "file": "fs/squashfs/file_direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/file.c:squashfs_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583087373,
      "name": "squashfs_readpage_block.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    },
    {
      "addr": 18446744071583085936,
      "name": "squashfs_readpage_block",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1437
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
int squashfs_readpage_block(struct page * target_page, u64 block, int bsize)
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
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int expected</code>
</li>
</ul>
</details>
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
