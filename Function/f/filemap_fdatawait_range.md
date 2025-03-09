# Function: <code>filemap_fdatawait_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int filemap_fdatawait_range(struct address_space * mapping, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "filemap_fdatawait_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580470112,
      "name": "filemap_fdatawait_range",
      "external": true,
      "loc": "mm/filemap.c:385",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/sync.c:SyS_sync_file_range2",
        "fs/sync.c:SyS_sync_file_range2",
        "fs/fat/file.c:fat_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580470112,
      "name": "filemap_fdatawait_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
int filemap_fdatawait_range(struct address_space * mapping, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "filemap_fdatawait_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580547920,
      "name": "filemap_fdatawait_range",
      "external": true,
      "loc": "mm/filemap.c:464",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/sync.c:SyS_sync_file_range2",
        "fs/sync.c:SyS_sync_file_range2",
        "fs/fat/file.c:fat_cont_expand"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580547920,
      "name": "filemap_fdatawait_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
int filemap_fdatawait_range(struct address_space * mapping, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "filemap_fdatawait_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580614064,
      "name": "filemap_fdatawait_range",
      "external": true,
      "loc": "mm/filemap.c:429",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/sync.c:SyS_sync_file_range2",
        "fs/sync.c:SyS_sync_file_range2",
        "fs/fat/file.c:fat_cont_expand"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580614064,
      "name": "filemap_fdatawait_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int filemap_fdatawait_range(struct address_space * mapping, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "filemap_fdatawait_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580642905,
      "name": "filemap_fdatawait_range",
      "external": true,
      "loc": "mm/filemap.c:461",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_fdatawait"
      ],
      "caller_func": [
        "fs/sync.c:SyS_sync_file_range2",
        "fs/sync.c:SyS_sync_file_range2",
        "fs/fat/file.c:fat_cont_expand"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580642848,
      "name": "filemap_fdatawait_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int filemap_fdatawait_range(struct address_space * mapping, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "filemap_fdatawait_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580725152,
      "name": "filemap_fdatawait_range",
      "external": true,
      "loc": "mm/filemap.c:556",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:__writeback_single_inode",
        "fs/fat/file.c:fat_cont_expand"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580725152,
      "name": "filemap_fdatawait_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int filemap_fdatawait_range(struct address_space * mapping, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "filemap_fdatawait_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580860928,
      "name": "filemap_fdatawait_range",
      "external": true,
      "loc": "mm/filemap.c:556",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:__writeback_single_inode",
        "fs/fat/file.c:fat_cont_expand"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580860928,
      "name": "filemap_fdatawait_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int filemap_fdatawait_range(struct address_space * mapping, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "filemap_fdatawait_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580935520,
      "name": "filemap_fdatawait_range",
      "external": true,
      "loc": "mm/filemap.c:533",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:__writeback_single_inode",
        "fs/fat/file.c:fat_cont_expand"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580935520,
      "name": "filemap_fdatawait_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int filemap_fdatawait_range(struct address_space * mapping, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "filemap_fdatawait_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581021728,
      "name": "filemap_fdatawait_range",
      "external": true,
      "loc": "mm/filemap.c:544",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:__writeback_single_inode",
        "fs/fat/file.c:fat_cont_expand"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581021728,
      "name": "filemap_fdatawait_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int filemap_fdatawait_range(struct address_space * mapping, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "filemap_fdatawait_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581076976,
      "name": "filemap_fdatawait_range",
      "external": true,
      "loc": "mm/filemap.c:550",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:__writeback_single_inode",
        "fs/fat/file.c:fat_cont_expand"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581076976,
      "name": "filemap_fdatawait_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int filemap_fdatawait_range(struct address_space * mapping, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "filemap_fdatawait_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581267152,
      "name": "filemap_fdatawait_range",
      "external": true,
      "loc": "mm/filemap.c:550",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:__writeback_single_inode",
        "fs/fat/file.c:fat_cont_expand"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581267152,
      "name": "filemap_fdatawait_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int filemap_fdatawait_range(struct address_space * mapping, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "filemap_fdatawait_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581309680,
      "name": "filemap_fdatawait_range",
      "external": true,
      "loc": "mm/filemap.c:551",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:__writeback_single_inode",
        "fs/fat/file.c:fat_cont_expand"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581309680,
      "name": "filemap_fdatawait_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int filemap_fdatawait_range(struct address_space * mapping, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "filemap_fdatawait_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581326688,
      "name": "filemap_fdatawait_range",
      "external": true,
      "loc": "mm/filemap.c:542",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:__writeback_single_inode",
        "fs/fat/file.c:fat_cont_expand"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581326688,
      "name": "filemap_fdatawait_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int filemap_fdatawait_range(struct address_space * mapping, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "filemap_fdatawait_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581571594,
      "name": "filemap_fdatawait_range",
      "external": true,
      "loc": "mm/filemap.c:560",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:__writeback_single_inode",
        "fs/fat/file.c:fat_cont_expand"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581574256,
      "name": "filemap_fdatawait_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int filemap_fdatawait_range(struct address_space * mapping, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "filemap_fdatawait_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581925984,
      "name": "filemap_fdatawait_range",
      "external": true,
      "loc": "mm/filemap.c:548",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:__writeback_single_inode",
        "fs/fat/file.c:fat_cont_expand"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581925984,
      "name": "filemap_fdatawait_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
int filemap_fdatawait_range(struct address_space * mapping, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "filemap_fdatawait_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582363472,
      "name": "filemap_fdatawait_range",
      "external": true,
      "loc": "mm/filemap.c:545",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:__writeback_single_inode",
        "fs/fat/file.c:fat_cont_expand"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582363472,
      "name": "filemap_fdatawait_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
int filemap_fdatawait_range(struct address_space * mapping, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "filemap_fdatawait_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582571600,
      "name": "filemap_fdatawait_range",
      "external": true,
      "loc": "mm/filemap.c:552",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:__writeback_single_inode",
        "fs/fat/file.c:fat_cont_expand"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582571600,
      "name": "filemap_fdatawait_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
int filemap_fdatawait_range(struct address_space * mapping, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "filemap_fdatawait_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582741392,
      "name": "filemap_fdatawait_range",
      "external": true,
      "loc": "mm/filemap.c:547",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:__writeback_single_inode",
        "fs/fat/file.c:fat_cont_expand"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582741392,
      "name": "filemap_fdatawait_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int filemap_fdatawait_range(struct address_space * mapping, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "filemap_fdatawait_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492448840,
      "name": "filemap_fdatawait_range",
      "external": true,
      "loc": "mm/filemap.c:550",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:__writeback_single_inode",
        "fs/fat/file.c:fat_cont_expand"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492448840,
      "name": "filemap_fdatawait_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int filemap_fdatawait_range(struct address_space * mapping, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "filemap_fdatawait_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226316192,
      "name": "filemap_fdatawait_range",
      "external": true,
      "loc": "mm/filemap.c:550",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:__writeback_single_inode",
        "fs/fat/file.c:fat_cont_expand"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226316192,
      "name": "filemap_fdatawait_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int filemap_fdatawait_range(struct address_space * mapping, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "filemap_fdatawait_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285712640,
      "name": "filemap_fdatawait_range",
      "external": true,
      "loc": "mm/filemap.c:550",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:__writeback_single_inode",
        "fs/fat/file.c:fat_cont_expand"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285712640,
      "name": "filemap_fdatawait_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
int filemap_fdatawait_range(struct address_space * mapping, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "filemap_fdatawait_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272516506,
      "name": "filemap_fdatawait_range",
      "external": true,
      "loc": "mm/filemap.c:550",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:__writeback_single_inode",
        "fs/fat/file.c:fat_cont_expand"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272516506,
      "name": "filemap_fdatawait_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int filemap_fdatawait_range(struct address_space * mapping, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "filemap_fdatawait_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581045824,
      "name": "filemap_fdatawait_range",
      "external": true,
      "loc": "mm/filemap.c:550",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:__writeback_single_inode",
        "fs/fat/file.c:fat_cont_expand"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581045824,
      "name": "filemap_fdatawait_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int filemap_fdatawait_range(struct address_space * mapping, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "filemap_fdatawait_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580993104,
      "name": "filemap_fdatawait_range",
      "external": true,
      "loc": "mm/filemap.c:550",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:__writeback_single_inode",
        "fs/fat/file.c:fat_cont_expand"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580993104,
      "name": "filemap_fdatawait_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int filemap_fdatawait_range(struct address_space * mapping, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "filemap_fdatawait_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581037024,
      "name": "filemap_fdatawait_range",
      "external": true,
      "loc": "mm/filemap.c:550",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:__writeback_single_inode",
        "fs/fat/file.c:fat_cont_expand"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581037024,
      "name": "filemap_fdatawait_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int filemap_fdatawait_range(struct address_space * mapping, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "filemap_fdatawait_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581098608,
      "name": "filemap_fdatawait_range",
      "external": true,
      "loc": "mm/filemap.c:550",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:__writeback_single_inode",
        "fs/fat/file.c:fat_cont_expand"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581098608,
      "name": "filemap_fdatawait_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
