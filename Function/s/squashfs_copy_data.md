# Function: <code>squashfs_copy_data</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int squashfs_copy_data(void * buffer, struct squashfs_cache_entry * entry, int offset, int length)
```

```json
{
  "name": "squashfs_copy_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582128643,
      "name": "squashfs_copy_data",
      "external": true,
      "loc": "fs/squashfs/cache.c:306",
      "file": "fs/squashfs/cache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/squashfs/cache.c:squashfs_read_metadata"
      ],
      "caller_func": [
        "fs/squashfs/cache.c:squashfs_read_metadata",
        "fs/squashfs/file.c:squashfs_copy_cache",
        "fs/squashfs/symlink.c:squashfs_symlink_readpage",
        "fs/squashfs/file_direct.c:squashfs_readpage_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582126512,
      "name": "squashfs_copy_data.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 238
    },
    {
      "addr": 18446744071582128528,
      "name": "squashfs_copy_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int squashfs_copy_data(void * buffer, struct squashfs_cache_entry * entry, int offset, int length)
```

```json
{
  "name": "squashfs_copy_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582218387,
      "name": "squashfs_copy_data",
      "external": true,
      "loc": "fs/squashfs/cache.c:306",
      "file": "fs/squashfs/cache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/squashfs/cache.c:squashfs_read_metadata"
      ],
      "caller_func": [
        "fs/squashfs/cache.c:squashfs_read_metadata",
        "fs/squashfs/file.c:squashfs_copy_cache",
        "fs/squashfs/symlink.c:squashfs_symlink_readpage",
        "fs/squashfs/file_direct.c:squashfs_readpage_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582216288,
      "name": "squashfs_copy_data.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 238
    },
    {
      "addr": 18446744071582218272,
      "name": "squashfs_copy_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int squashfs_copy_data(void * buffer, struct squashfs_cache_entry * entry, int offset, int length)
```

```json
{
  "name": "squashfs_copy_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582303697,
      "name": "squashfs_copy_data",
      "external": true,
      "loc": "fs/squashfs/cache.c:306",
      "file": "fs/squashfs/cache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/squashfs/cache.c:squashfs_read_metadata"
      ],
      "caller_func": [
        "fs/squashfs/cache.c:squashfs_read_metadata",
        "fs/squashfs/file.c:squashfs_copy_cache",
        "fs/squashfs/symlink.c:squashfs_symlink_readpage",
        "fs/squashfs/file_direct.c:squashfs_readpage_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582301728,
      "name": "squashfs_copy_data.part.1",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 238
    },
    {
      "addr": 18446744071582303584,
      "name": "squashfs_copy_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int squashfs_copy_data(void * buffer, struct squashfs_cache_entry * entry, int offset, int length)
```

```json
{
  "name": "squashfs_copy_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582452817,
      "name": "squashfs_copy_data",
      "external": true,
      "loc": "fs/squashfs/cache.c:306",
      "file": "fs/squashfs/cache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/squashfs/cache.c:squashfs_read_metadata"
      ],
      "caller_func": [
        "fs/squashfs/cache.c:squashfs_read_metadata",
        "fs/squashfs/file.c:squashfs_copy_cache",
        "fs/squashfs/symlink.c:squashfs_symlink_readpage",
        "fs/squashfs/file_direct.c:squashfs_readpage_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582450848,
      "name": "squashfs_copy_data.part.1",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 238
    },
    {
      "addr": 18446744071582452704,
      "name": "squashfs_copy_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int squashfs_copy_data(void * buffer, struct squashfs_cache_entry * entry, int offset, int length)
```

```json
{
  "name": "squashfs_copy_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582643423,
      "name": "squashfs_copy_data",
      "external": true,
      "loc": "fs/squashfs/cache.c:306",
      "file": "fs/squashfs/cache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/squashfs/cache.c:squashfs_read_metadata"
      ],
      "caller_func": [
        "fs/squashfs/cache.c:squashfs_read_metadata",
        "fs/squashfs/file.c:squashfs_fill_page",
        "fs/squashfs/symlink.c:squashfs_symlink_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582641248,
      "name": "squashfs_copy_data.part.1",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 447
    },
    {
      "addr": 18446744071582643184,
      "name": "squashfs_copy_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int squashfs_copy_data(void * buffer, struct squashfs_cache_entry * entry, int offset, int length)
```

```json
{
  "name": "squashfs_copy_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582745199,
      "name": "squashfs_copy_data",
      "external": true,
      "loc": "fs/squashfs/cache.c:306",
      "file": "fs/squashfs/cache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/squashfs/cache.c:squashfs_read_metadata"
      ],
      "caller_func": [
        "fs/squashfs/cache.c:squashfs_read_metadata",
        "fs/squashfs/file.c:squashfs_fill_page",
        "fs/squashfs/symlink.c:squashfs_symlink_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582743024,
      "name": "squashfs_copy_data.part.1",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 447
    },
    {
      "addr": 18446744071582744960,
      "name": "squashfs_copy_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int squashfs_copy_data(void * buffer, struct squashfs_cache_entry * entry, int offset, int length)
```

```json
{
  "name": "squashfs_copy_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582919232,
      "name": "squashfs_copy_data",
      "external": true,
      "loc": "fs/squashfs/cache.c:293",
      "file": "fs/squashfs/cache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/squashfs/cache.c:squashfs_read_metadata"
      ],
      "caller_func": [
        "fs/squashfs/cache.c:squashfs_read_metadata",
        "fs/squashfs/file.c:squashfs_fill_page",
        "fs/squashfs/symlink.c:squashfs_symlink_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582917056,
      "name": "squashfs_copy_data.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 441
    },
    {
      "addr": 18446744071582918992,
      "name": "squashfs_copy_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int squashfs_copy_data(void * buffer, struct squashfs_cache_entry * entry, int offset, int length)
```

```json
{
  "name": "squashfs_copy_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583025776,
      "name": "squashfs_copy_data",
      "external": true,
      "loc": "fs/squashfs/cache.c:293",
      "file": "fs/squashfs/cache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/squashfs/cache.c:squashfs_read_metadata"
      ],
      "caller_func": [
        "fs/squashfs/cache.c:squashfs_read_metadata",
        "fs/squashfs/file.c:squashfs_fill_page",
        "fs/squashfs/symlink.c:squashfs_symlink_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583023600,
      "name": "squashfs_copy_data.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 441
    },
    {
      "addr": 18446744071583025536,
      "name": "squashfs_copy_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int squashfs_copy_data(void * buffer, struct squashfs_cache_entry * entry, int offset, int length)
```

```json
{
  "name": "squashfs_copy_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583343584,
      "name": "squashfs_copy_data",
      "external": true,
      "loc": "fs/squashfs/cache.c:293",
      "file": "fs/squashfs/cache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/squashfs/cache.c:squashfs_read_metadata"
      ],
      "caller_func": [
        "fs/squashfs/cache.c:squashfs_read_metadata",
        "fs/squashfs/file.c:squashfs_fill_page",
        "fs/squashfs/symlink.c:squashfs_symlink_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583341392,
      "name": "squashfs_copy_data.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 442
    },
    {
      "addr": 18446744071583343344,
      "name": "squashfs_copy_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int squashfs_copy_data(void * buffer, struct squashfs_cache_entry * entry, int offset, int length)
```

```json
{
  "name": "squashfs_copy_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583460048,
      "name": "squashfs_copy_data",
      "external": true,
      "loc": "fs/squashfs/cache.c:293",
      "file": "fs/squashfs/cache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/squashfs/cache.c:squashfs_read_metadata"
      ],
      "caller_func": [
        "fs/squashfs/cache.c:squashfs_read_metadata",
        "fs/squashfs/file.c:squashfs_fill_page",
        "fs/squashfs/symlink.c:squashfs_symlink_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583457904,
      "name": "squashfs_copy_data.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 442
    },
    {
      "addr": 18446744071583459808,
      "name": "squashfs_copy_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int squashfs_copy_data(void * buffer, struct squashfs_cache_entry * entry, int offset, int length)
```

```json
{
  "name": "squashfs_copy_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583481776,
      "name": "squashfs_copy_data",
      "external": true,
      "loc": "fs/squashfs/cache.c:293",
      "file": "fs/squashfs/cache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/cache.c:squashfs_read_metadata",
        "fs/squashfs/file.c:squashfs_fill_page",
        "fs/squashfs/symlink.c:squashfs_symlink_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583481776,
      "name": "squashfs_copy_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 361
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
int squashfs_copy_data(void * buffer, struct squashfs_cache_entry * entry, int offset, int length)
```

```json
{
  "name": "squashfs_copy_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583836176,
      "name": "squashfs_copy_data",
      "external": true,
      "loc": "fs/squashfs/cache.c:293",
      "file": "fs/squashfs/cache.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/cache.c:squashfs_read_metadata",
        "fs/squashfs/file.c:squashfs_fill_page",
        "fs/squashfs/symlink.c:squashfs_symlink_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583836176,
      "name": "squashfs_copy_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 361
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
int squashfs_copy_data(void * buffer, struct squashfs_cache_entry * entry, int offset, int length)
```

```json
{
  "name": "squashfs_copy_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584404256,
      "name": "squashfs_copy_data",
      "external": true,
      "loc": "fs/squashfs/cache.c:293",
      "file": "fs/squashfs/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/cache.c:squashfs_read_metadata",
        "fs/squashfs/file.c:squashfs_fill_page",
        "fs/squashfs/symlink.c:squashfs_symlink_read_folio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584404256,
      "name": "squashfs_copy_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 349
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
int squashfs_copy_data(void * buffer, struct squashfs_cache_entry * entry, int offset, int length)
```

```json
{
  "name": "squashfs_copy_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585059488,
      "name": "squashfs_copy_data",
      "external": true,
      "loc": "fs/squashfs/cache.c:293",
      "file": "fs/squashfs/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/cache.c:squashfs_read_metadata",
        "fs/squashfs/file.c:squashfs_fill_page",
        "fs/squashfs/symlink.c:squashfs_symlink_read_folio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585059488,
      "name": "squashfs_copy_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 349
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
int squashfs_copy_data(void * buffer, struct squashfs_cache_entry * entry, int offset, int length)
```

```json
{
  "name": "squashfs_copy_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585288656,
      "name": "squashfs_copy_data",
      "external": true,
      "loc": "fs/squashfs/cache.c:293",
      "file": "fs/squashfs/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/cache.c:squashfs_read_metadata",
        "fs/squashfs/file.c:squashfs_fill_page",
        "fs/squashfs/symlink.c:squashfs_symlink_read_folio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585288656,
      "name": "squashfs_copy_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 482
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
int squashfs_copy_data(void * buffer, struct squashfs_cache_entry * entry, int offset, int length)
```

```json
{
  "name": "squashfs_copy_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585522400,
      "name": "squashfs_copy_data",
      "external": true,
      "loc": "fs/squashfs/cache.c:293",
      "file": "fs/squashfs/cache.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/cache.c:squashfs_read_metadata",
        "fs/squashfs/file.c:squashfs_fill_page",
        "fs/squashfs/symlink.c:squashfs_symlink_read_folio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585522400,
      "name": "squashfs_copy_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 482
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline, Transformation ❓</summary>

```c
int squashfs_copy_data(void * buffer, struct squashfs_cache_entry * entry, int offset, int length)
```

```json
{
  "name": "squashfs_copy_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336494721356,
      "name": "squashfs_copy_data",
      "external": true,
      "loc": "fs/squashfs/cache.c:293",
      "file": "fs/squashfs/cache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/squashfs/cache.c:squashfs_read_metadata"
      ],
      "caller_func": [
        "fs/squashfs/cache.c:squashfs_read_metadata",
        "fs/squashfs/file.c:squashfs_fill_page",
        "fs/squashfs/symlink.c:squashfs_symlink_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494718856,
      "name": "squashfs_copy_data.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
    },
    {
      "addr": 18446603336494721072,
      "name": "squashfs_copy_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
int squashfs_copy_data(void * buffer, struct squashfs_cache_entry * entry, int offset, int length)
```

```json
{
  "name": "squashfs_copy_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3228155952,
      "name": "squashfs_copy_data",
      "external": true,
      "loc": "fs/squashfs/cache.c:293",
      "file": "fs/squashfs/cache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/squashfs/cache.c:squashfs_read_metadata"
      ],
      "caller_func": [
        "fs/squashfs/cache.c:squashfs_read_metadata",
        "fs/squashfs/file.c:squashfs_fill_page",
        "fs/squashfs/symlink.c:squashfs_symlink_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228153752,
      "name": "squashfs_copy_data.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
    },
    {
      "addr": 3228155684,
      "name": "squashfs_copy_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline, Transformation ❓</summary>

```c
int squashfs_copy_data(void * buffer, struct squashfs_cache_entry * entry, int offset, int length)
```

```json
{
  "name": "squashfs_copy_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055288542780,
      "name": "squashfs_copy_data",
      "external": true,
      "loc": "fs/squashfs/cache.c:293",
      "file": "fs/squashfs/cache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/squashfs/cache.c:squashfs_read_metadata"
      ],
      "caller_func": [
        "fs/squashfs/cache.c:squashfs_read_metadata",
        "fs/squashfs/file.c:squashfs_fill_page",
        "fs/squashfs/symlink.c:squashfs_symlink_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288539488,
      "name": "squashfs_copy_data.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 432
    },
    {
      "addr": 13835058055288542464,
      "name": "squashfs_copy_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline, Transformation ❓</summary>

```c
int squashfs_copy_data(void * buffer, struct squashfs_cache_entry * entry, int offset, int length)
```

```json
{
  "name": "squashfs_copy_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274069638,
      "name": "squashfs_copy_data",
      "external": true,
      "loc": "fs/squashfs/cache.c:293",
      "file": "fs/squashfs/cache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/squashfs/cache.c:squashfs_read_metadata"
      ],
      "caller_func": [
        "fs/squashfs/cache.c:squashfs_read_metadata",
        "fs/squashfs/file.c:squashfs_fill_page",
        "fs/squashfs/symlink.c:squashfs_symlink_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274067354,
      "name": "squashfs_copy_data.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
    },
    {
      "addr": 18446743936274069450,
      "name": "squashfs_copy_data",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int squashfs_copy_data(void * buffer, struct squashfs_cache_entry * entry, int offset, int length)
```

```json
{
  "name": "squashfs_copy_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582994512,
      "name": "squashfs_copy_data",
      "external": true,
      "loc": "fs/squashfs/cache.c:293",
      "file": "fs/squashfs/cache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/squashfs/cache.c:squashfs_read_metadata"
      ],
      "caller_func": [
        "fs/squashfs/cache.c:squashfs_read_metadata",
        "fs/squashfs/file.c:squashfs_fill_page",
        "fs/squashfs/symlink.c:squashfs_symlink_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582992336,
      "name": "squashfs_copy_data.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 441
    },
    {
      "addr": 18446744071582994272,
      "name": "squashfs_copy_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int squashfs_copy_data(void * buffer, struct squashfs_cache_entry * entry, int offset, int length)
```

```json
{
  "name": "squashfs_copy_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582931664,
      "name": "squashfs_copy_data",
      "external": true,
      "loc": "fs/squashfs/cache.c:293",
      "file": "fs/squashfs/cache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/squashfs/cache.c:squashfs_read_metadata"
      ],
      "caller_func": [
        "fs/squashfs/cache.c:squashfs_read_metadata",
        "fs/squashfs/file.c:squashfs_fill_page",
        "fs/squashfs/symlink.c:squashfs_symlink_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582929488,
      "name": "squashfs_copy_data.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 441
    },
    {
      "addr": 18446744071582931424,
      "name": "squashfs_copy_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int squashfs_copy_data(void * buffer, struct squashfs_cache_entry * entry, int offset, int length)
```

```json
{
  "name": "squashfs_copy_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582983120,
      "name": "squashfs_copy_data",
      "external": true,
      "loc": "fs/squashfs/cache.c:293",
      "file": "fs/squashfs/cache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/squashfs/cache.c:squashfs_read_metadata"
      ],
      "caller_func": [
        "fs/squashfs/cache.c:squashfs_read_metadata",
        "fs/squashfs/file.c:squashfs_fill_page",
        "fs/squashfs/symlink.c:squashfs_symlink_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582980944,
      "name": "squashfs_copy_data.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 441
    },
    {
      "addr": 18446744071582982880,
      "name": "squashfs_copy_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int squashfs_copy_data(void * buffer, struct squashfs_cache_entry * entry, int offset, int length)
```

```json
{
  "name": "squashfs_copy_data",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583072192,
      "name": "squashfs_copy_data",
      "external": true,
      "loc": "fs/squashfs/cache.c:293",
      "file": "fs/squashfs/cache.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/squashfs/cache.c:squashfs_read_metadata"
      ],
      "caller_func": [
        "fs/squashfs/cache.c:squashfs_read_metadata",
        "fs/squashfs/file.c:squashfs_fill_page",
        "fs/squashfs/symlink.c:squashfs_symlink_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583070032,
      "name": "squashfs_copy_data.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 441
    },
    {
      "addr": 18446744071583071952,
      "name": "squashfs_copy_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int squashfs_copy_data(void * buffer, struct squashfs_cache_entry * entry, int offset, int length)
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
