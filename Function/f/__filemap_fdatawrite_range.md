# Function: <code>__filemap_fdatawrite_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int __filemap_fdatawrite_range(struct address_space * mapping, loff_t start, loff_t end, int sync_mode)
```

```json
{
  "name": "__filemap_fdatawrite_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580477520,
      "name": "__filemap_fdatawrite_range",
      "external": true,
      "loc": "mm/filemap.c:282",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_flush",
        "mm/filemap.c:filemap_fdatawrite_range",
        "fs/sync.c:SyS_sync_file_range2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580477520,
      "name": "__filemap_fdatawrite_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 249
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
int __filemap_fdatawrite_range(struct address_space * mapping, loff_t start, loff_t end, int sync_mode)
```

```json
{
  "name": "__filemap_fdatawrite_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580558304,
      "name": "__filemap_fdatawrite_range",
      "external": true,
      "loc": "mm/filemap.c:361",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_flush",
        "mm/filemap.c:filemap_fdatawrite_range",
        "mm/fadvise.c:SyS_fadvise64",
        "fs/sync.c:SyS_sync_file_range2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580558304,
      "name": "__filemap_fdatawrite_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 255
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
int __filemap_fdatawrite_range(struct address_space * mapping, loff_t start, loff_t end, int sync_mode)
```

```json
{
  "name": "__filemap_fdatawrite_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580623392,
      "name": "__filemap_fdatawrite_range",
      "external": true,
      "loc": "mm/filemap.c:326",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_flush",
        "mm/filemap.c:filemap_fdatawrite_range",
        "mm/fadvise.c:SyS_fadvise64",
        "fs/sync.c:SyS_sync_file_range2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580623392,
      "name": "__filemap_fdatawrite_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 255
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
int __filemap_fdatawrite_range(struct address_space * mapping, loff_t start, loff_t end, int sync_mode)
```

```json
{
  "name": "__filemap_fdatawrite_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580651168,
      "name": "__filemap_fdatawrite_range",
      "external": true,
      "loc": "mm/filemap.c:330",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:file_write_and_wait_range",
        "mm/filemap.c:filemap_flush",
        "mm/filemap.c:filemap_fdatawrite_range",
        "mm/fadvise.c:SyS_fadvise64",
        "fs/sync.c:SyS_sync_file_range2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580651168,
      "name": "__filemap_fdatawrite_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 241
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
int __filemap_fdatawrite_range(struct address_space * mapping, loff_t start, loff_t end, int sync_mode)
```

```json
{
  "name": "__filemap_fdatawrite_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580735392,
      "name": "__filemap_fdatawrite_range",
      "external": true,
      "loc": "mm/filemap.c:430",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:file_write_and_wait_range",
        "mm/filemap.c:filemap_flush",
        "mm/filemap.c:filemap_fdatawrite_range",
        "mm/fadvise.c:SyS_fadvise64",
        "fs/sync.c:SyS_sync_file_range2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580735392,
      "name": "__filemap_fdatawrite_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 241
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
int __filemap_fdatawrite_range(struct address_space * mapping, loff_t start, loff_t end, int sync_mode)
```

```json
{
  "name": "__filemap_fdatawrite_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580873424,
      "name": "__filemap_fdatawrite_range",
      "external": true,
      "loc": "mm/filemap.c:430",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:file_write_and_wait_range",
        "mm/filemap.c:filemap_flush",
        "mm/filemap.c:filemap_fdatawrite_range",
        "mm/fadvise.c:ksys_fadvise64_64",
        "fs/sync.c:ksys_sync_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580873424,
      "name": "__filemap_fdatawrite_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 242
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
int __filemap_fdatawrite_range(struct address_space * mapping, loff_t start, loff_t end, int sync_mode)
```

```json
{
  "name": "__filemap_fdatawrite_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580945104,
      "name": "__filemap_fdatawrite_range",
      "external": true,
      "loc": "mm/filemap.c:396",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:file_write_and_wait_range",
        "mm/filemap.c:filemap_flush",
        "mm/filemap.c:filemap_fdatawrite_range",
        "mm/fadvise.c:vfs_fadvise",
        "fs/sync.c:ksys_sync_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580945104,
      "name": "__filemap_fdatawrite_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 242
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
int __filemap_fdatawrite_range(struct address_space * mapping, loff_t start, loff_t end, int sync_mode)
```

```json
{
  "name": "__filemap_fdatawrite_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581042416,
      "name": "__filemap_fdatawrite_range",
      "external": true,
      "loc": "mm/filemap.c:400",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:file_write_and_wait_range",
        "mm/filemap.c:filemap_flush",
        "mm/filemap.c:filemap_fdatawrite_range",
        "mm/fadvise.c:vfs_fadvise",
        "fs/sync.c:sync_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581042416,
      "name": "__filemap_fdatawrite_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 253
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
int __filemap_fdatawrite_range(struct address_space * mapping, loff_t start, loff_t end, int sync_mode)
```

```json
{
  "name": "__filemap_fdatawrite_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581097824,
      "name": "__filemap_fdatawrite_range",
      "external": true,
      "loc": "mm/filemap.c:405",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:file_write_and_wait_range",
        "mm/filemap.c:filemap_flush",
        "mm/filemap.c:filemap_fdatawrite_range",
        "mm/fadvise.c:generic_fadvise",
        "fs/sync.c:sync_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581097824,
      "name": "__filemap_fdatawrite_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 270
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
int __filemap_fdatawrite_range(struct address_space * mapping, loff_t start, loff_t end, int sync_mode)
```

```json
{
  "name": "__filemap_fdatawrite_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581274272,
      "name": "__filemap_fdatawrite_range",
      "external": true,
      "loc": "mm/filemap.c:405",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:file_write_and_wait_range",
        "mm/filemap.c:filemap_flush",
        "mm/filemap.c:filemap_fdatawrite_range",
        "mm/filemap.c:filemap_fdatawrite",
        "mm/fadvise.c:generic_fadvise",
        "fs/sync.c:sync_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581274272,
      "name": "__filemap_fdatawrite_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 261
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
int __filemap_fdatawrite_range(struct address_space * mapping, loff_t start, loff_t end, int sync_mode)
```

```json
{
  "name": "__filemap_fdatawrite_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581321008,
      "name": "__filemap_fdatawrite_range",
      "external": true,
      "loc": "mm/filemap.c:406",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:file_write_and_wait_range",
        "mm/filemap.c:filemap_flush",
        "mm/filemap.c:filemap_fdatawrite_range",
        "mm/filemap.c:filemap_fdatawrite",
        "mm/fadvise.c:generic_fadvise",
        "fs/sync.c:sync_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581321008,
      "name": "__filemap_fdatawrite_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 261
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
int __filemap_fdatawrite_range(struct address_space * mapping, loff_t start, loff_t end, int sync_mode)
```

```json
{
  "name": "__filemap_fdatawrite_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581340944,
      "name": "__filemap_fdatawrite_range",
      "external": true,
      "loc": "mm/filemap.c:397",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:file_write_and_wait_range",
        "mm/filemap.c:filemap_flush",
        "mm/filemap.c:filemap_fdatawrite_range",
        "mm/filemap.c:filemap_fdatawrite",
        "mm/fadvise.c:generic_fadvise",
        "fs/sync.c:sync_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581340944,
      "name": "__filemap_fdatawrite_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 261
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
int __filemap_fdatawrite_range(struct address_space * mapping, loff_t start, loff_t end, int sync_mode)
```

```json
{
  "name": "__filemap_fdatawrite_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581577381,
      "name": "__filemap_fdatawrite_range",
      "external": true,
      "loc": "mm/filemap.c:423",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/filemap.c:file_write_and_wait_range",
        "mm/filemap.c:filemap_flush",
        "mm/filemap.c:filemap_fdatawrite_range",
        "mm/filemap.c:filemap_fdatawrite"
      ],
      "caller_func": [
        "mm/fadvise.c:generic_fadvise",
        "fs/sync.c:sync_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581589872,
      "name": "__filemap_fdatawrite_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
int __filemap_fdatawrite_range(struct address_space * mapping, loff_t start, loff_t end, int sync_mode)
```

```json
{
  "name": "__filemap_fdatawrite_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581947280,
      "name": "__filemap_fdatawrite_range",
      "external": true,
      "loc": "mm/filemap.c:411",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:file_write_and_wait_range",
        "mm/filemap.c:filemap_flush",
        "mm/filemap.c:filemap_fdatawrite_range",
        "mm/filemap.c:filemap_fdatawrite",
        "mm/fadvise.c:generic_fadvise",
        "fs/sync.c:sync_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581947280,
      "name": "__filemap_fdatawrite_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
int __filemap_fdatawrite_range(struct address_space * mapping, loff_t start, loff_t end, int sync_mode)
```

```json
{
  "name": "__filemap_fdatawrite_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582381024,
      "name": "__filemap_fdatawrite_range",
      "external": true,
      "loc": "mm/filemap.c:411",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:file_write_and_wait_range",
        "mm/filemap.c:filemap_flush",
        "mm/filemap.c:filemap_fdatawrite_range",
        "mm/filemap.c:filemap_fdatawrite",
        "mm/fadvise.c:generic_fadvise",
        "fs/sync.c:sync_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582381024,
      "name": "__filemap_fdatawrite_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
int __filemap_fdatawrite_range(struct address_space * mapping, loff_t start, loff_t end, int sync_mode)
```

```json
{
  "name": "__filemap_fdatawrite_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582582080,
      "name": "__filemap_fdatawrite_range",
      "external": true,
      "loc": "mm/filemap.c:416",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:file_write_and_wait_range",
        "mm/filemap.c:filemap_flush",
        "mm/filemap.c:filemap_fdatawrite_range",
        "mm/filemap.c:filemap_fdatawrite",
        "mm/fadvise.c:generic_fadvise",
        "fs/sync.c:sync_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582582080,
      "name": "__filemap_fdatawrite_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
int __filemap_fdatawrite_range(struct address_space * mapping, loff_t start, loff_t end, int sync_mode)
```

```json
{
  "name": "__filemap_fdatawrite_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582752640,
      "name": "__filemap_fdatawrite_range",
      "external": true,
      "loc": "mm/filemap.c:411",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:file_write_and_wait_range",
        "mm/filemap.c:filemap_flush",
        "mm/filemap.c:filemap_fdatawrite_range",
        "mm/filemap.c:filemap_fdatawrite",
        "mm/fadvise.c:generic_fadvise",
        "fs/sync.c:sync_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582752640,
      "name": "__filemap_fdatawrite_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
int __filemap_fdatawrite_range(struct address_space * mapping, loff_t start, loff_t end, int sync_mode)
```

```json
{
  "name": "__filemap_fdatawrite_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492462392,
      "name": "__filemap_fdatawrite_range",
      "external": true,
      "loc": "mm/filemap.c:405",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:file_write_and_wait_range",
        "mm/filemap.c:filemap_flush",
        "mm/filemap.c:filemap_fdatawrite_range",
        "mm/fadvise.c:generic_fadvise",
        "fs/sync.c:sync_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492462392,
      "name": "__filemap_fdatawrite_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 376
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
int __filemap_fdatawrite_range(struct address_space * mapping, loff_t start, loff_t end, int sync_mode)
```

```json
{
  "name": "__filemap_fdatawrite_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226338184,
      "name": "__filemap_fdatawrite_range",
      "external": true,
      "loc": "mm/filemap.c:405",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:file_write_and_wait_range",
        "mm/filemap.c:filemap_flush",
        "mm/filemap.c:filemap_fdatawrite_range",
        "mm/fadvise.c:generic_fadvise",
        "fs/sync.c:sync_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226338184,
      "name": "__filemap_fdatawrite_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 312
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
int __filemap_fdatawrite_range(struct address_space * mapping, loff_t start, loff_t end, int sync_mode)
```

```json
{
  "name": "__filemap_fdatawrite_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285742736,
      "name": "__filemap_fdatawrite_range",
      "external": true,
      "loc": "mm/filemap.c:405",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:file_write_and_wait_range",
        "mm/filemap.c:filemap_flush",
        "mm/filemap.c:filemap_fdatawrite_range",
        "mm/fadvise.c:generic_fadvise",
        "fs/sync.c:sync_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285742736,
      "name": "__filemap_fdatawrite_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 380
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
int __filemap_fdatawrite_range(struct address_space * mapping, loff_t start, loff_t end, int sync_mode)
```

```json
{
  "name": "__filemap_fdatawrite_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272533710,
      "name": "__filemap_fdatawrite_range",
      "external": true,
      "loc": "mm/filemap.c:405",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:file_write_and_wait_range",
        "mm/filemap.c:filemap_flush",
        "mm/filemap.c:filemap_fdatawrite_range",
        "mm/fadvise.c:generic_fadvise",
        "fs/sync.c:sync_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272533710,
      "name": "__filemap_fdatawrite_range",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int __filemap_fdatawrite_range(struct address_space * mapping, loff_t start, loff_t end, int sync_mode)
```

```json
{
  "name": "__filemap_fdatawrite_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581066672,
      "name": "__filemap_fdatawrite_range",
      "external": true,
      "loc": "mm/filemap.c:405",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:file_write_and_wait_range",
        "mm/filemap.c:filemap_flush",
        "mm/filemap.c:filemap_fdatawrite_range",
        "mm/fadvise.c:generic_fadvise",
        "fs/sync.c:sync_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581066672,
      "name": "__filemap_fdatawrite_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 270
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
int __filemap_fdatawrite_range(struct address_space * mapping, loff_t start, loff_t end, int sync_mode)
```

```json
{
  "name": "__filemap_fdatawrite_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581013872,
      "name": "__filemap_fdatawrite_range",
      "external": true,
      "loc": "mm/filemap.c:405",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:file_write_and_wait_range",
        "mm/filemap.c:filemap_flush",
        "mm/filemap.c:filemap_fdatawrite_range",
        "mm/fadvise.c:generic_fadvise",
        "fs/sync.c:sync_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581013872,
      "name": "__filemap_fdatawrite_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 270
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
int __filemap_fdatawrite_range(struct address_space * mapping, loff_t start, loff_t end, int sync_mode)
```

```json
{
  "name": "__filemap_fdatawrite_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581057872,
      "name": "__filemap_fdatawrite_range",
      "external": true,
      "loc": "mm/filemap.c:405",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:file_write_and_wait_range",
        "mm/filemap.c:filemap_flush",
        "mm/filemap.c:filemap_fdatawrite_range",
        "mm/fadvise.c:generic_fadvise",
        "fs/sync.c:sync_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581057872,
      "name": "__filemap_fdatawrite_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 270
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
int __filemap_fdatawrite_range(struct address_space * mapping, loff_t start, loff_t end, int sync_mode)
```

```json
{
  "name": "__filemap_fdatawrite_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581119456,
      "name": "__filemap_fdatawrite_range",
      "external": true,
      "loc": "mm/filemap.c:405",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:file_write_and_wait_range",
        "mm/filemap.c:filemap_flush",
        "mm/filemap.c:filemap_fdatawrite_range",
        "mm/fadvise.c:generic_fadvise",
        "fs/sync.c:sync_file_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581119456,
      "name": "__filemap_fdatawrite_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 270
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
