# Function: <code>filemap_range_has_page</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
bool filemap_range_has_page(struct address_space * mapping, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "filemap_range_has_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580639120,
      "name": "filemap_range_has_page",
      "external": true,
      "loc": "mm/filemap.c:391",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_direct_write",
        "mm/filemap.c:generic_file_read_iter",
        "fs/iomap.c:iomap_dio_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580639120,
      "name": "filemap_range_has_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
bool filemap_range_has_page(struct address_space * mapping, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "filemap_range_has_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580739824,
      "name": "filemap_range_has_page",
      "external": true,
      "loc": "mm/filemap.c:491",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_direct_write",
        "mm/filemap.c:generic_file_read_iter",
        "fs/iomap.c:iomap_dio_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580739824,
      "name": "filemap_range_has_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 199
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
bool filemap_range_has_page(struct address_space * mapping, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "filemap_range_has_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580877968,
      "name": "filemap_range_has_page",
      "external": true,
      "loc": "mm/filemap.c:491",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_direct_write",
        "mm/filemap.c:generic_file_read_iter",
        "fs/iomap.c:iomap_dio_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580877968,
      "name": "filemap_range_has_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
bool filemap_range_has_page(struct address_space * mapping, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "filemap_range_has_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580925712,
      "name": "filemap_range_has_page",
      "external": true,
      "loc": "mm/filemap.c:457",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_direct_write",
        "mm/filemap.c:generic_file_read_iter",
        "fs/iomap.c:iomap_dio_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580925712,
      "name": "filemap_range_has_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
bool filemap_range_has_page(struct address_space * mapping, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "filemap_range_has_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581021312,
      "name": "filemap_range_has_page",
      "external": true,
      "loc": "mm/filemap.c:466",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_direct_write",
        "mm/filemap.c:generic_file_read_iter",
        "fs/iomap/direct-io.c:iomap_dio_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581021312,
      "name": "filemap_range_has_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
bool filemap_range_has_page(struct address_space * mapping, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "filemap_range_has_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581076544,
      "name": "filemap_range_has_page",
      "external": true,
      "loc": "mm/filemap.c:472",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_direct_write",
        "mm/filemap.c:generic_file_read_iter",
        "fs/iomap/direct-io.c:iomap_dio_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581076544,
      "name": "filemap_range_has_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
bool filemap_range_has_page(struct address_space * mapping, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "filemap_range_has_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581261776,
      "name": "filemap_range_has_page",
      "external": true,
      "loc": "mm/filemap.c:472",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_direct_write",
        "mm/filemap.c:generic_file_read_iter",
        "fs/iomap/direct-io.c:iomap_dio_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581261776,
      "name": "filemap_range_has_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
bool filemap_range_has_page(struct address_space * mapping, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "filemap_range_has_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581304096,
      "name": "filemap_range_has_page",
      "external": true,
      "loc": "mm/filemap.c:473",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_direct_write",
        "mm/filemap.c:generic_file_read_iter",
        "fs/iomap/direct-io.c:__iomap_dio_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581304096,
      "name": "filemap_range_has_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
bool filemap_range_has_page(struct address_space * mapping, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "filemap_range_has_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581321984,
      "name": "filemap_range_has_page",
      "external": true,
      "loc": "mm/filemap.c:464",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_direct_write",
        "fs/iomap/direct-io.c:__iomap_dio_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581321984,
      "name": "filemap_range_has_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
bool filemap_range_has_page(struct address_space * mapping, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "filemap_range_has_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581567424,
      "name": "filemap_range_has_page",
      "external": true,
      "loc": "mm/filemap.c:482",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_direct_write",
        "fs/iomap/direct-io.c:__iomap_dio_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581567424,
      "name": "filemap_range_has_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
bool filemap_range_has_page(struct address_space * mapping, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "filemap_range_has_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581921264,
      "name": "filemap_range_has_page",
      "external": true,
      "loc": "mm/filemap.c:470",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_direct_write",
        "fs/iomap/direct-io.c:__iomap_dio_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581921264,
      "name": "filemap_range_has_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
bool filemap_range_has_page(struct address_space * mapping, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "filemap_range_has_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582358224,
      "name": "filemap_range_has_page",
      "external": true,
      "loc": "mm/filemap.c:470",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_direct_write",
        "fs/iomap/direct-io.c:__iomap_dio_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582358224,
      "name": "filemap_range_has_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
bool filemap_range_has_page(struct address_space * mapping, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "filemap_range_has_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582561296,
      "name": "filemap_range_has_page",
      "external": true,
      "loc": "mm/filemap.c:475",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:kiocb_invalidate_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582561296,
      "name": "filemap_range_has_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
bool filemap_range_has_page(struct address_space * mapping, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "filemap_range_has_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582732080,
      "name": "filemap_range_has_page",
      "external": true,
      "loc": "mm/filemap.c:470",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:kiocb_invalidate_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582732080,
      "name": "filemap_range_has_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
bool filemap_range_has_page(struct address_space * mapping, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "filemap_range_has_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492440632,
      "name": "filemap_range_has_page",
      "external": true,
      "loc": "mm/filemap.c:472",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_direct_write",
        "mm/filemap.c:generic_file_read_iter",
        "fs/iomap/direct-io.c:iomap_dio_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492440632,
      "name": "filemap_range_has_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
bool filemap_range_has_page(struct address_space * mapping, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "filemap_range_has_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226315584,
      "name": "filemap_range_has_page",
      "external": true,
      "loc": "mm/filemap.c:472",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_direct_write",
        "mm/filemap.c:generic_file_read_iter",
        "fs/iomap/direct-io.c:iomap_dio_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226315584,
      "name": "filemap_range_has_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
bool filemap_range_has_page(struct address_space * mapping, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "filemap_range_has_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285711984,
      "name": "filemap_range_has_page",
      "external": true,
      "loc": "mm/filemap.c:472",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_direct_write",
        "mm/filemap.c:generic_file_read_iter",
        "fs/iomap/direct-io.c:iomap_dio_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285711984,
      "name": "filemap_range_has_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
bool filemap_range_has_page(struct address_space * mapping, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "filemap_range_has_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272516166,
      "name": "filemap_range_has_page",
      "external": true,
      "loc": "mm/filemap.c:472",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_direct_write",
        "mm/filemap.c:generic_file_read_iter",
        "fs/iomap/direct-io.c:iomap_dio_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272516166,
      "name": "filemap_range_has_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
bool filemap_range_has_page(struct address_space * mapping, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "filemap_range_has_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581045392,
      "name": "filemap_range_has_page",
      "external": true,
      "loc": "mm/filemap.c:472",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_direct_write",
        "mm/filemap.c:generic_file_read_iter",
        "fs/iomap/direct-io.c:iomap_dio_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581045392,
      "name": "filemap_range_has_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
bool filemap_range_has_page(struct address_space * mapping, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "filemap_range_has_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580992672,
      "name": "filemap_range_has_page",
      "external": true,
      "loc": "mm/filemap.c:472",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_direct_write",
        "mm/filemap.c:generic_file_read_iter",
        "fs/iomap/direct-io.c:iomap_dio_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580992672,
      "name": "filemap_range_has_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
bool filemap_range_has_page(struct address_space * mapping, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "filemap_range_has_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581036592,
      "name": "filemap_range_has_page",
      "external": true,
      "loc": "mm/filemap.c:472",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_direct_write",
        "mm/filemap.c:generic_file_read_iter",
        "fs/iomap/direct-io.c:iomap_dio_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581036592,
      "name": "filemap_range_has_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
bool filemap_range_has_page(struct address_space * mapping, loff_t start_byte, loff_t end_byte)
```

```json
{
  "name": "filemap_range_has_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581098160,
      "name": "filemap_range_has_page",
      "external": true,
      "loc": "mm/filemap.c:472",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_direct_write",
        "mm/filemap.c:generic_file_read_iter",
        "fs/iomap/direct-io.c:iomap_dio_rw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581098160,
      "name": "filemap_range_has_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
bool filemap_range_has_page(struct address_space * mapping, loff_t start_byte, loff_t end_byte)
```
</details>
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
