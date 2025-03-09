# Function: <code>squashfs_fill_page</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void squashfs_fill_page(struct page * page, struct squashfs_cache_entry * buffer, int offset, int avail)
```

```json
{
  "name": "squashfs_fill_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582645824,
      "name": "squashfs_fill_page",
      "external": true,
      "loc": "fs/squashfs/file.c:377",
      "file": "fs/squashfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/file.c:squashfs_copy_cache",
        "fs/squashfs/file_direct.c:squashfs_readpage_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582645824,
      "name": "squashfs_fill_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
void squashfs_fill_page(struct page * page, struct squashfs_cache_entry * buffer, int offset, int avail)
```

```json
{
  "name": "squashfs_fill_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582747600,
      "name": "squashfs_fill_page",
      "external": true,
      "loc": "fs/squashfs/file.c:377",
      "file": "fs/squashfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/file.c:squashfs_copy_cache",
        "fs/squashfs/file_direct.c:squashfs_readpage_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582747600,
      "name": "squashfs_fill_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
void squashfs_fill_page(struct page * page, struct squashfs_cache_entry * buffer, int offset, int avail)
```

```json
{
  "name": "squashfs_fill_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582923248,
      "name": "squashfs_fill_page",
      "external": true,
      "loc": "fs/squashfs/file.c:364",
      "file": "fs/squashfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/file.c:squashfs_copy_cache",
        "fs/squashfs/file_direct.c:squashfs_readpage_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582923248,
      "name": "squashfs_fill_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
void squashfs_fill_page(struct page * page, struct squashfs_cache_entry * buffer, int offset, int avail)
```

```json
{
  "name": "squashfs_fill_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583029792,
      "name": "squashfs_fill_page",
      "external": true,
      "loc": "fs/squashfs/file.c:364",
      "file": "fs/squashfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/file.c:squashfs_copy_cache",
        "fs/squashfs/file_direct.c:squashfs_readpage_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583029792,
      "name": "squashfs_fill_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
void squashfs_fill_page(struct page * page, struct squashfs_cache_entry * buffer, int offset, int avail)
```

```json
{
  "name": "squashfs_fill_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583347824,
      "name": "squashfs_fill_page",
      "external": true,
      "loc": "fs/squashfs/file.c:364",
      "file": "fs/squashfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/file.c:squashfs_copy_cache",
        "fs/squashfs/file_direct.c:squashfs_read_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583347824,
      "name": "squashfs_fill_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
void squashfs_fill_page(struct page * page, struct squashfs_cache_entry * buffer, int offset, int avail)
```

```json
{
  "name": "squashfs_fill_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583464272,
      "name": "squashfs_fill_page",
      "external": true,
      "loc": "fs/squashfs/file.c:364",
      "file": "fs/squashfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/file.c:squashfs_copy_cache",
        "fs/squashfs/file_direct.c:squashfs_read_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583464272,
      "name": "squashfs_fill_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
void squashfs_fill_page(struct page * page, struct squashfs_cache_entry * buffer, int offset, int avail)
```

```json
{
  "name": "squashfs_fill_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583486304,
      "name": "squashfs_fill_page",
      "external": true,
      "loc": "fs/squashfs/file.c:364",
      "file": "fs/squashfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/file.c:squashfs_copy_cache",
        "fs/squashfs/file_direct.c:squashfs_readpage_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583486304,
      "name": "squashfs_fill_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
void squashfs_fill_page(struct page * page, struct squashfs_cache_entry * buffer, int offset, int avail)
```

```json
{
  "name": "squashfs_fill_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583840736,
      "name": "squashfs_fill_page",
      "external": true,
      "loc": "fs/squashfs/file.c:364",
      "file": "fs/squashfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/file.c:squashfs_copy_cache",
        "fs/squashfs/file_direct.c:squashfs_readpage_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583840736,
      "name": "squashfs_fill_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
void squashfs_fill_page(struct page * page, struct squashfs_cache_entry * buffer, int offset, int avail)
```

```json
{
  "name": "squashfs_fill_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584409040,
      "name": "squashfs_fill_page",
      "external": true,
      "loc": "fs/squashfs/file.c:364",
      "file": "fs/squashfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/file.c:squashfs_copy_cache",
        "fs/squashfs/file_direct.c:squashfs_readpage_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584409040,
      "name": "squashfs_fill_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
void squashfs_fill_page(struct page * page, struct squashfs_cache_entry * buffer, int offset, int avail)
```

```json
{
  "name": "squashfs_fill_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585065568,
      "name": "squashfs_fill_page",
      "external": true,
      "loc": "fs/squashfs/file.c:365",
      "file": "fs/squashfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/file.c:squashfs_readahead",
        "fs/squashfs/file.c:squashfs_copy_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585065568,
      "name": "squashfs_fill_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 251
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
void squashfs_fill_page(struct page * page, struct squashfs_cache_entry * buffer, int offset, int avail)
```

```json
{
  "name": "squashfs_fill_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585294928,
      "name": "squashfs_fill_page",
      "external": true,
      "loc": "fs/squashfs/file.c:365",
      "file": "fs/squashfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/file.c:squashfs_readahead",
        "fs/squashfs/file.c:squashfs_copy_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585294928,
      "name": "squashfs_fill_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 251
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
void squashfs_fill_page(struct page * page, struct squashfs_cache_entry * buffer, int offset, int avail)
```

```json
{
  "name": "squashfs_fill_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585528768,
      "name": "squashfs_fill_page",
      "external": true,
      "loc": "fs/squashfs/file.c:365",
      "file": "fs/squashfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/file.c:squashfs_readahead",
        "fs/squashfs/file.c:squashfs_copy_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585528768,
      "name": "squashfs_fill_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
void squashfs_fill_page(struct page * page, struct squashfs_cache_entry * buffer, int offset, int avail)
```

```json
{
  "name": "squashfs_fill_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494725728,
      "name": "squashfs_fill_page",
      "external": true,
      "loc": "fs/squashfs/file.c:364",
      "file": "fs/squashfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/file.c:squashfs_copy_cache",
        "fs/squashfs/file_direct.c:squashfs_readpage_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494725728,
      "name": "squashfs_fill_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 300
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
void squashfs_fill_page(struct page * page, struct squashfs_cache_entry * buffer, int offset, int avail)
```

```json
{
  "name": "squashfs_fill_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228160604,
      "name": "squashfs_fill_page",
      "external": true,
      "loc": "fs/squashfs/file.c:364",
      "file": "fs/squashfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/file.c:squashfs_copy_cache",
        "fs/squashfs/file_direct.c:squashfs_readpage_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228160604,
      "name": "squashfs_fill_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
void squashfs_fill_page(struct page * page, struct squashfs_cache_entry * buffer, int offset, int avail)
```

```json
{
  "name": "squashfs_fill_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288548256,
      "name": "squashfs_fill_page",
      "external": true,
      "loc": "fs/squashfs/file.c:364",
      "file": "fs/squashfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/file.c:squashfs_copy_cache",
        "fs/squashfs/file_direct.c:squashfs_readpage_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288548256,
      "name": "squashfs_fill_page",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void squashfs_fill_page(struct page * page, struct squashfs_cache_entry * buffer, int offset, int avail)
```

```json
{
  "name": "squashfs_fill_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274073460,
      "name": "squashfs_fill_page",
      "external": true,
      "loc": "fs/squashfs/file.c:364",
      "file": "fs/squashfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/file.c:squashfs_copy_cache",
        "fs/squashfs/file_direct.c:squashfs_readpage_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274073460,
      "name": "squashfs_fill_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
void squashfs_fill_page(struct page * page, struct squashfs_cache_entry * buffer, int offset, int avail)
```

```json
{
  "name": "squashfs_fill_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582998528,
      "name": "squashfs_fill_page",
      "external": true,
      "loc": "fs/squashfs/file.c:364",
      "file": "fs/squashfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/file.c:squashfs_copy_cache",
        "fs/squashfs/file_direct.c:squashfs_readpage_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582998528,
      "name": "squashfs_fill_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
void squashfs_fill_page(struct page * page, struct squashfs_cache_entry * buffer, int offset, int avail)
```

```json
{
  "name": "squashfs_fill_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582935680,
      "name": "squashfs_fill_page",
      "external": true,
      "loc": "fs/squashfs/file.c:364",
      "file": "fs/squashfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/file.c:squashfs_copy_cache",
        "fs/squashfs/file_direct.c:squashfs_readpage_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582935680,
      "name": "squashfs_fill_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
void squashfs_fill_page(struct page * page, struct squashfs_cache_entry * buffer, int offset, int avail)
```

```json
{
  "name": "squashfs_fill_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582987136,
      "name": "squashfs_fill_page",
      "external": true,
      "loc": "fs/squashfs/file.c:364",
      "file": "fs/squashfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/file.c:squashfs_copy_cache",
        "fs/squashfs/file_direct.c:squashfs_readpage_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582987136,
      "name": "squashfs_fill_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
void squashfs_fill_page(struct page * page, struct squashfs_cache_entry * buffer, int offset, int avail)
```

```json
{
  "name": "squashfs_fill_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583076208,
      "name": "squashfs_fill_page",
      "external": true,
      "loc": "fs/squashfs/file.c:364",
      "file": "fs/squashfs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/squashfs/file.c:squashfs_copy_cache",
        "fs/squashfs/file_direct.c:squashfs_readpage_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583076208,
      "name": "squashfs_fill_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void squashfs_fill_page(struct page * page, struct squashfs_cache_entry * buffer, int offset, int avail)
```
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
